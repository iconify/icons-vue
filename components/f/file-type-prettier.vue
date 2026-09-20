<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="htkzkaczg"><path class="cfl-q7bnq"/><path class="hx2wsebhl"/><path class="y9mvwiu-a"/><path class="e4ltvpyms"/><path class="fik45nywq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-prettier" /></template>
<style>
.cfl-q7bnq {
  stroke: var(--svg-color--56b3b4, #56b3b4);
  d: path("M2.45 2.45h16.3M2.45 7.87h9.48m10.8 0h1.35m-16.3 2.71h1.35M13.19 16h10.8m-21.7 2.71h5.42m-5.42 8.13H5");
}

.e4ltvpyms {
  stroke: var(--svg-color--bf85bf, #bf85bf);
  d: path("M14.6 7.87h5.42m-17.6 5.42h6.77m9.48 5.42h4.06m-20.3 2.71h1.35m-1.35 2.71H9.2");
}

.fik45nywq {
  stroke: var(--svg-color--4d616e, #4d616e);
  d: path("M21.4 2.45h8.13m-4.06 2.71h4.06m-2.71 2.71h2.71m-17.6 2.71h4.06m12.2 0h1.35m-17.6 2.71H16m12.2 0h1.35M26.84 16h2.71m-4.06 2.71h4.06m-8.13 2.71h2.71m2.71 0h2.71m-17.6 2.71h2.71m2.71 0h12.2m-17.6 2.71h5.42m2.71 0h1.35m2.71 0h5.42m-17.6 2.71h8.13m2.71 0h6.77");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.htkzkaczg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-33px, 1.33px);
}

.hx2wsebhl {
  stroke: var(--svg-color--ea5e5e, #ea5e5e);
  d: path("M2.45 5.16h4.06m12.2 5.42h6.77M2.48 16h1.35m6.77 2.71h5.42m-13.5 10.8h6.77");
}

.y9mvwiu-a {
  stroke: var(--svg-color--f7b93e, #f7b93e);
  d: path("M9.23 5.16h13.5m-20.3 5.42h2.71m13.5 2.71h6.77M6.41 16h4.06m-4.06 5.42h12.2m-10.8 5.42h1.35");
}

</style>
