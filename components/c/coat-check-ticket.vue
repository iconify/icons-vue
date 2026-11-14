<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ro80dbc1w"/><path class="jnac5sjke"/><path class="mobwjr4or"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coat-check-ticket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnac5sjke {
  d: path("M10.5 11.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.mobwjr4or {
  d: path("M12 9.75c-6-8.25 6-8.25 0 0M9.5 15.5h5m-5 3h3");
}

.ro80dbc1w {
  d: path("m7.013 9.987l2.474-2.474A1.75 1.75 0 0 1 10.725 7h2.55a1.75 1.75 0 0 1 1.238.513l2.474 2.474a1.75 1.75 0 0 1 .513 1.238v8.525a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75v-8.525a1.75 1.75 0 0 1 .513-1.238");
}

</style>
