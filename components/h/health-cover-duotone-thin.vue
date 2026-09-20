<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hn4kykb4m"/><path class="iz9s08bfh"/><path class="alkjmdb2u"/><path class="h4jktfbaf"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="ts5ij9bsc"/><path class="zm2dyvb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-cover-duotone-thin" /></template>
<style>
.a3eibhdgt {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

.alkjmdb2u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h4jktfbaf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 16h6");
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

.ts5ij9bsc {
  d: path("M12 13v6");
}

.z26gfvqcs {
  d: path("M4.5 9.5h15");
}

.zm2dyvb-o {
  d: path("M9 16h6");
}

</style>
