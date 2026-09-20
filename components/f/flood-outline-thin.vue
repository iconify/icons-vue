<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wlpa9-b1f"/><path class="pzm21jb5s"/><path class="fcnh_acnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flood-outline-thin" /></template>
<style>
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

.pzm21jb5s {
  d: path("M7 11v5h10v-5");
}

.wlpa9-b1f {
  d: path("m5 11 7 -7 7 7");
}

</style>
