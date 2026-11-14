<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lutgj-bui"/><path class="k2oxk4w6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-charger-cells" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2oxk4w6d {
  d: path("m12.75 13.5l-2 2.75h2.5l-2 2.75");
}

.lutgj-bui {
  d: path("M6.5 11h-1a2 2 0 0 0-2 2v6.5a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V13a2 2 0 0 0-2-2h-1m-7 0h3m-7 0V5a1 1 0 0 1 1-1h.25V2.5h1.5V4h.25a1 1 0 0 1 1 1v6m3 0V5a1 1 0 0 1 1-1h.25V2.5h1.5V4h.25a1 1 0 0 1 1 1v6");
}

</style>
