<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jd3l2pb_a"/><path class="y5tkq2b_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ev-charging-schedule" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jd3l2pb_a {
  d: path("M7 2.5h3A3.5 3.5 0 0 1 13.5 6v4.5A3.5 3.5 0 0 1 10 14H7a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 7 2.5M7 14v4a3 3 0 0 1-3 3H2.5");
}

.y5tkq2b_m {
  d: path("M8.444 6.276L7.118 7.964a.486.486 0 0 0 .382.786a.744.744 0 0 1 .713.958L8.125 10a.247.247 0 0 0 .431.224l1.326-1.688A.486.486 0 0 0 9.5 7.75a.744.744 0 0 1-.713-.958l.088-.292a.247.247 0 0 0-.431-.224M16.75 15.5h2.5A1.75 1.75 0 0 1 21 17.25v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.5v-2.25a1.75 1.75 0 0 1 1.75-1.75M15 17.75h6m-4.25-3.25V16m2.5-1.5V16");
}

</style>
