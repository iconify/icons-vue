<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ef87yidyf"/><path class="w-dx3wilf"/><path class="mr9tlqpkq"/><path class="m35p8tb1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hockey-linear" /></template>
<style>
.ef87yidyf {
  d: path("M18.1215 3.03905C18.7215 2.13905 20.0215 2.03905 20.8215 2.63905C21.5215 3.13905 21.7215 4.23905 21.1215 5.13905L14.3215 18.939C13.3215 20.739 11.5215 21.739 9.42148 21.739H4.52148C3.22148 21.739 2.52148 20.939 2.52148 19.739C2.52148 18.539 3.22148 17.739 4.52148 17.739H9.32148C10.3215 17.739 11.0215 17.239 11.5215 16.339L18.1215 3.03905Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m35p8tb1v {
  d: path("M2.72266 5.33911V8.33911C2.72266 9.43911 4.52266 10.3391 6.72266 10.3391C8.92266 10.3391 10.7227 9.43911 10.7227 8.33911V5.33911");
}

.mr9tlqpkq {
  d: path("M10.7227 5.33911C10.7227 6.44371 8.93176 7.33911 6.72266 7.33911C4.51356 7.33911 2.72266 6.44371 2.72266 5.33911C2.72266 4.23451 4.51356 3.33911 6.72266 3.33911C8.93176 3.33911 10.7227 4.23451 10.7227 5.33911Z");
}

.w-dx3wilf {
  d: path("M7.12305 17.7391V21.7391");
}

</style>
