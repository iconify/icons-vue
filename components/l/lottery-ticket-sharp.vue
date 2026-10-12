<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="aqzx3mb5i"/><path class="c4hhgzm0t"/><path class="x1xndnbvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lottery-ticket-sharp" /></template>
<style>
.aqzx3mb5i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25h18.5v13.5H2.75zM8 7.5V9m0 2.25v1.5M8 15v1.5");
}

.c4hhgzm0t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.5 9.5h.01m3.24 0h.01m3.24 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x1xndnbvq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 14.5H18");
}

</style>
