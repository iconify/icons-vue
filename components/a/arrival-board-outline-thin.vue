<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gkj6vbuly"/><path class="s-qvifbka"/><path class="h0lf65bzj"/><path class="b1mfh3r0j"/><path class="a67_cn3fi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrival-board-outline-thin" /></template>
<style>
.a67_cn3fi {
  d: path("M13.5 7.5 16 10l-2.5 2.5");
}

.b1mfh3r0j {
  d: path("M6 10h10");
}

.gkj6vbuly {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.h0lf65bzj {
  d: path("M17 21v-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s-qvifbka {
  d: path("M7 21v-4");
}

</style>
