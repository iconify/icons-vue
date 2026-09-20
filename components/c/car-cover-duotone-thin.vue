<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybxmeccml"/><path class="z2ytn2b4x"/><path class="hn4kykb4m"/><path class="iz9s08bfh"/><path class="glqo0q-sj"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="uct8v-rdb"/><path class="p47b7s_df"/><path class="j6_bngbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:car-cover-duotone-thin" /></template>
<style>
.a3eibhdgt {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

.glqo0q-sj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 18v-3L7 12.5h7.5L17 15h2.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hn4kykb4m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iz9s08bfh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.ybxmeccml {
  fill: currentColor;
  d: path("M7 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z26gfvqcs {
  d: path("M4.5 9.5h15");
}

.z2ytn2b4x {
  fill: currentColor;
  d: path("M15 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
