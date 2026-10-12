<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tgzbk0b2q"/><circle class="t9sqlg7hc"/><path class="v6qhv1bxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kite-kids" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t9sqlg7hc {
  cx: 6.25px;
  cy: 10.75px;
  r: 2.25px;
}

.tgzbk0b2q {
  d: path("m17.53 3.28l3.19 3.19q.53.53 0 1.06l-3.19 3.19q-.53.53-1.06 0l-3.19-3.19q-.53-.53 0-1.06l3.19-3.19q.53-.53 1.06 0M17 11.25c0 3-4 3-8 5");
}

.v6qhv1bxz {
  d: path("M3 21.25v-2.5a3.25 3.25 0 0 1 6.5 0v2.5Z");
}

</style>
