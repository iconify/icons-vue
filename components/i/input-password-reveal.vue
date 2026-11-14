<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ga0sgkqyt"/><path class="mvz5xacxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:input-password-reveal" /></template>
<style>
.ga0sgkqyt {
  d: path("M2.5 3h19v8.5h-19ZM5 18c1.6-2.4 4-3.5 7-3.5s5.4 1.1 7 3.5c-1.6 2.4-4 3.5-7 3.5S6.6 20.4 5 18ZM6.5 7.25h.01m3.49 0h.01m3.49 0h.01m3.49 0h.01");
}

.mvz5xacxz {
  d: path("M10.25 18a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
