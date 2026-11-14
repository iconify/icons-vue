<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e_7cfl4ql"/><path class="gfka6zbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coloring-book" /></template>
<style>
.e_7cfl4ql {
  d: path("M21 12.16V4.5c-3-.5-6.5 0-9 1.5c-2.5-1.5-6-2-9-1.5v14c2.833-.472 6.113-.052 8.575 1.259M12 6v10.7");
}

.gfka6zbwy {
  d: path("m14.672 17.707l2.534-2.535a1.5 1.5 0 0 1 .697-.394l1.011-.253a.875.875 0 0 1 1.061 1.061l-.253 1.011a1.5 1.5 0 0 1-.394.697l-2.535 2.534a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
