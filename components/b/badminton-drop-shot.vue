<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5nqawb6l"/><path class="cb-lpcciv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badminton-drop-shot" /></template>
<style>
.cb-lpcciv {
  d: path("M7.5 16.5L4.5 3h9l-3 13.5m7.5-13V17m-2.5-2.5L18 17l2.5-2.5M9 3v13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5nqawb6l {
  d: path("M6.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
