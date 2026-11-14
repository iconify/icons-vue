<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zoej7biec"/><path class="gusycuyhz"/><path class="ukppck8yp"/><path class="imju1h85n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:holter-monitor" /></template>
<style>
.gusycuyhz {
  d: path("M14.75 15.5h2a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-2A1.75 1.75 0 0 1 13 17.75v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imju1h85n {
  d: path("M14.5 15.5c-.5-3-4-4-5.75-5.5m7.75 5.5l-.75-5.75");
}

.ukppck8yp {
  fill: currentColor;
  d: path("M7 9a1.25 1.25 0 1 0 2.5 0A1.25 1.25 0 1 0 7 9m7.25-.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.zoej7biec {
  d: path("M9.5 2.5c0 1.75-1.25 2.5-3 3L5 6c-1.25.5-1.75 1.25-1.5 2.5l2.25 5c.25 1-.5 4-.5 8h13.5c0-4-.75-7-.5-8l2.25-5c.25-1.25-.25-2-1.5-2.5l-1.5-.5c-1.75-.5-3-1.25-3-3");
}

</style>
