<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="aw-d49oof"/><path class="vvwpg6y3d"/><path class="jqywddn6h"/><path class="ywqkvx3mw"/><path class="mg3mgebrz"/><path class="jss_6sfey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:airplane" /></template>
<style>
.aw-d49oof {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M33.41 35.09a3.495 3.495 0 0 1 0-4.95l6.36-6.36a3.495 3.495 0 0 1 4.95 0a3.495 3.495 0 0 1 0 4.95l-6.36 6.36a3.495 3.495 0 0 1-4.95 0m19.25 0a3.495 3.495 0 0 1 0-4.95l6.36-6.36a3.495 3.495 0 0 1 4.95 0a3.495 3.495 0 0 1 0 4.95l-6.36 6.36a3.495 3.495 0 0 1-4.95 0m40.87 38.75a3.495 3.495 0 0 1 0-4.95l6.36-6.36a3.495 3.495 0 0 1 4.95 0a3.495 3.495 0 0 1 0 4.95l-6.36 6.36a3.495 3.495 0 0 1-4.95 0m-.51 19.5a3.495 3.495 0 0 1 0-4.95l6.36-6.36a3.495 3.495 0 0 1 4.95 0a3.495 3.495 0 0 1 0 4.95l-6.36 6.36a3.495 3.495 0 0 1-4.95 0");
}

.jqywddn6h {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M90.29 18.39L26.75 85.24A10 10 0 0 0 24 92.13V98c0 3.31 2.69 6 6 6h5.87c2.56 0 5.03-.98 6.89-2.75l66.85-63.54c3.12-2.96 5.2-6.85 5.93-11.09l1.51-8.74c.71-4.09-2.85-7.64-6.93-6.93l-8.74 1.51c-4.24.73-8.13 2.81-11.09 5.93");
}

.jss_6sfey {
  fill: none;
  stroke: var(--svg-color--016ca2, #016ca2);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("m99 19.7l2.29-.24c4.95-.37 8.72 4.37 7.24 9.11v0");
}

.mg3mgebrz {
  fill: var(--svg-color--016ca2, #016ca2);
  d: path("m47.02 81.87l-25.85 25.91s13.4-2.16 25.85-25.91");
}

.vvwpg6y3d {
  fill: var(--svg-color--016ca2, #016ca2);
  d: path("M96.69 35.31s3.67 45 0 79.98c-.6 5.7-8.62 7.1-9.78 1.48c-6.56-31.79-20.72-49.96-20.72-49.96zm-3.97-3.37s-45-3.67-79.98 0c-5.7.6-7.1 8.62-1.48 9.78c31.79 6.56 49.96 20.72 49.96 20.72zM43 85H8.02c-3.94 0-5.51 5.1-2.25 7.31L23 104zm0 0v34.98c0 3.94-5.1 5.51-7.31 2.25L24 105z");
}

.ywqkvx3mw {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("m47.02 81.87l-25.85 25.91s2.34-13.6 25.85-25.91");
}

</style>
