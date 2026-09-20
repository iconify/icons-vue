<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nkz3mtbwk"/><path class="xgzlj4bea"/><path class="l2bljsbmn"/><path class="u78lc2bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lecture-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l2bljsbmn {
  d: path("M12 9v11");
}

.nkz3mtbwk {
  fill: currentColor;
  d: path("m5 8 3 -3h11v3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u78lc2bnx {
  d: path("M6 20h12");
}

.xgzlj4bea {
  d: path("m5 8 3 -3h11v3Z");
}

</style>
