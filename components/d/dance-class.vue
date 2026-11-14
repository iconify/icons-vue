<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ofvbtebbi"/><path class="v-3bi0boq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dance-class" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ofvbtebbi {
  d: path("M11.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0M13 8.5L12 14l-4 7");
}

.v-3bi0boq {
  d: path("m6.5 5l6.25 4.75L18.5 6M12 14l5.5 3.5");
}

</style>
