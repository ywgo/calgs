cmake_minimum_required(VERSION 3.8)
project(calgs)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp
        02-Sorting-Basic/Student.h SortTestHelper.h
        02-Sorting-Basic/SelectionSort.h
        02-Sorting-Basic/InsertionSort.h
        02-Sorting-Basic/BubbleSort.h
        02-Sorting-Basic/ShellSort.h
        02-Sorting-Basic/SortBaseMain.h
        03-Sorting-Advance/MergeSort.h
        03-Sorting-Advance/SortAdvance.h
        03-Sorting-Advance/MergeSortButtonUp.h
        03-Sorting-Advance/QuickSort.h
        03-Sorting-Advance/MergeSortBU.h
        03-Sorting-Advance/MergeSortBUO.h
        03-Sorting-Advance/MergeSortO.h
        03-Sorting-Advance/QuickSort2Ways.h
        03-Sorting-Advance/QuickSort3Ways.h
        )
add_executable(calgs ${SOURCE_FILES})