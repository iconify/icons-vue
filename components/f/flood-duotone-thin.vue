<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yejxb6b5w"/><path class="aicg7_erx"/><path class="n1gjkoido"/><path class="wlpa9-b1f"/><path class="pzm21jb5s"/><path class="fcnh_acnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flood-duotone-thin" /></template>
<style>
.aicg7_erx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 11v5h10v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fcnh_acnz {
  d: path("m3 19 2.5 -2.5L8 19l2.5 -2.5L13 19l2.5 -2.5L18 19l2.5 -2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n1gjkoido {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 19 2.5 -2.5L8 19l2.5 -2.5L13 19l2.5 -2.5L18 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pzm21jb5s {
  d: path("M7 11v5h10v-5");
}

.wlpa9-b1f {
  d: path("m5 11 7 -7 7 7");
}

.yejxb6b5w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 11 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
