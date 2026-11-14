<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="folf-nb5a"/><path class="wqucxcctz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-fern" /></template>
<style>
.folf-nb5a {
  d: path("M12 21.5v-14c0-3-1.5-4.75-3.5-4.25c-1.75.5-1.75 3 .25 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqucxcctz {
  d: path("M12 18q-4.5-.5-7.5-4m7.5 0q-3.5-.5-6.75-4M12 18q4.5-.5 7.5-4M12 14q3.5-.5 6.75-4M12 10q2.5-.5 4.5-3.5");
}

</style>
