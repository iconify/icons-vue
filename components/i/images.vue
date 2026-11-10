<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fy_wh1bnh"/><path clip-rule="evenodd" class="b0q2_-bbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:images" /></template>
<style>
.b0q2_-bbk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 7C12 7.55 11.5523 8 11 8C10.4477 8 10 7.55 10 7C10 6.45 10.4477 6 11 6C11.5523 6 12 6.45 12 7Z");
  stroke: none;
}

.fy_wh1bnh {
  d: path("M3 8V18C3 19.66 4.3431 21 6 21H16M21 14.14L18.6044 11.93C18.1939 11.55 17.5439 11.51 17.0794 11.83L15.5873 12.86C15.1228 13.18 14.4728 13.14 14.0623 12.76L12.4917 11.31C12.036 10.9 11.2973 10.9 10.8417 11.31L7.5 14.39M10 3H18C19.6569 3 21 4.34 21 6V14C21 15.66 19.6569 17 18 17H10C8.3431 17 7 15.66 7 14V6C7 4.34 8.3431 3 10 3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
