<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r-0vdabar"/><path class="la_v0ub4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:frog-prince" /></template>
<style>
.la_v0ub4w {
  d: path("M8 17q4 2 8 0");
}

.r-0vdabar {
  d: path("M3 16c0-2.5.5-3.5 1-4a2.75 2.75 0 0 1 5-1.25h6A2.75 2.75 0 0 1 20 12c.5.5 1 1.5 1 4c0 3-4 5-9 5s-9-2-9-5Zm6.5-8.75V3.5L11 5.25l1-2l1 2l1.5-1.75v3.75Zm-3 5.25h.01m10.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
