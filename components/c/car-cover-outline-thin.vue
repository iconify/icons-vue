<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="uct8v-rdb"/><path class="p47b7s_df"/><path class="j6_bngbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:car-cover-outline-thin" /></template>
<style>
.a3eibhdgt {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6_bngbnz {
  d: path("M15 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p47b7s_df {
  d: path("M7 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uct8v-rdb {
  d: path("M4.5 18v-3L7 12.5h7.5L17 15h2.5v3");
}

.z26gfvqcs {
  d: path("M4.5 9.5h15");
}

</style>
