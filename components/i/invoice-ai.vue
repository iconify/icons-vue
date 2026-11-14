<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dtmrvm2ap"/><path class="ha_7dg2pg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:invoice-ai" /></template>
<style>
.dtmrvm2ap {
  d: path("m12.84 20.274l-.34.226l-2.25-1.5L8 20.5L5.75 19L3.5 20.5v-18H17v9.4");
}

.ha_7dg2pg {
  d: path("M12.75 7.5h-3.5a1.75 1.75 0 0 0 0 3.5h2a1.75 1.75 0 0 1 0 3.5h-3.5m2.5-9V16M18 14.5q.75 2.75 3.5 3.5q-2.75.75-3.5 3.5q-.75-2.75-3.5-3.5q2.75-.75 3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
