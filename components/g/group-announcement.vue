<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cznw62bep"/><path class="hbvdddbdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:group-announcement" /></template>
<style>
.cznw62bep {
  d: path("m3 9l9-4.5V18l-9-4.5Z");
}

.hbvdddbdi {
  d: path("M6 15v4.5h3v-3m5.662-7.114a3.25 3.25 0 0 1 0 3.728m2.253-5.305a6 6 0 0 1 0 6.882m2.253-8.46a8.75 8.75 0 0 1 0 10.038");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
