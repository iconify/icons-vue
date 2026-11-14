<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tszvtglof"/><path class="ckgexktlo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:helmet-ancient" /></template>
<style>
.ckgexktlo {
  d: path("M17.75 8.75C19 2.5 9 1 3.5 5.5c2 0 3 1.5 2.75 3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tszvtglof {
  d: path("M4.5 18.5v-5a7.5 7.5 0 0 1 15 0V15h-5v2l2 4h-5L10 18.5Z");
}

</style>
