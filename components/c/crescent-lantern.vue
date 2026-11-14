<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="djo0wlb8h"/><path class="ejs0sgbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crescent-lantern" /></template>
<style>
.djo0wlb8h {
  d: path("M12 2.5v2.25M8.5 7l1.25-2.25h4.5L15.5 7m-5.125 0h3.25A4.375 4.375 0 0 1 18 11.375v3.75a4.375 4.375 0 0 1-4.375 4.375h-3.25A4.375 4.375 0 0 1 6 15.125v-3.75A4.375 4.375 0 0 1 10.375 7M9.5 19.5v2h5v-2");
}

.ejs0sgbze {
  d: path("M13.5 10a3.25 3.25 0 0 0 0 6.5a4.5 4.5 0 0 1 0-6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
