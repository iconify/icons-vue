<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_a4zhb0w"/><path class="ra1ubp4as"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-paint" /></template>
<style>
.d_a4zhb0w {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm6.25-4h.01m6.49 0h.01");
}

.ra1ubp4as {
  d: path("m15.25 11l.75 2h2l-1.5 1.5l.5 2l-1.75-1.25l-1.75 1.25l.5-2l-1.5-1.5h2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
