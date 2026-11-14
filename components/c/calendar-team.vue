<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r4aouzm0b"/><path class="ds76n4qhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-team" /></template>
<style>
.ds76n4qhf {
  d: path("M14.25 15.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-1 6c0-1.25 1.25-2 2.75-2s2.75.75 2.75 2M20 14a1.75 1.75 0 0 1 0 3.5m.75 2.25c.75.25 1 1 1 2");
}

.r4aouzm0b {
  d: path("M11 19.5H2.5V4H19v7.2M7 2.5V6m7.5-3.5V6m-12 3.5H19m-12.5 4h.01m3.99 0h.01M6.5 17h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
