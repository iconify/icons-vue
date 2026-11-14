<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e_1el6bgc"/><path class="jo34ko0tj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-outline-check" /></template>
<style>
.e_1el6bgc {
  d: path("M12 20.5c-5-3.5-9.5-7-9.5-11.75A5 5 0 0 1 12 6.5a5 5 0 0 1 9.5 2.25C21.5 13.5 17 17 12 20.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo34ko0tj {
  d: path("m8.5 12l2.5 2.5l4.5-4.5");
}

</style>
