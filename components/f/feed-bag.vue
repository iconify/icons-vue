<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n4z_51bpm"/><path class="vnprk6bnv"/><circle class="r1z5s1m9e"/><path class="uc28uob0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feed-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4z_51bpm {
  d: path("M5 3.5c4.5 1 9.5 1 14 0l-1 8.75l1 9c-4.5-1-9.5-1-14 0l1-9Z");
}

.r1z5s1m9e {
  cx: 12px;
  cy: 13.75px;
  r: 3.25px;
}

.uc28uob0h {
  d: path("M12 11.75c.9.9.9 3.1 0 4c-.9-.9-.9-3.1 0-4");
}

.vnprk6bnv {
  d: path("M7 6.5c3.25.5 6.75.5 10 0");
}

</style>
