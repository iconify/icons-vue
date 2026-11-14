<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jm-zjqblj"/><path class="y_qzhyp2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-interview" /></template>
<style>
.jm-zjqblj {
  d: path("m4.5 9.5l-1 2.5V9.5a1.5 1.5 0 0 1-1-1.5V4.5A1.5 1.5 0 0 1 4 3h5a1.5 1.5 0 0 1 1.5 1.5V8A1.5 1.5 0 0 1 9 9.5Zm15 0l1 2.5V9.5a1.5 1.5 0 0 0 1-1.5V4.5A1.5 1.5 0 0 0 20 3h-5a1.5 1.5 0 0 0-1.5 1.5V8A1.5 1.5 0 0 0 15 9.5ZM7.25 16.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_qzhyp2c {
  d: path("M12 14.75v2h2");
}

</style>
