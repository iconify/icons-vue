<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ftqzjnb8u"/><path class="tkvxdludj"/><path class="k58vknb8e"/><path class="a1go-lhea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-failed-outline-bold" /></template>
<style>
.a1go-lhea {
  d: path("m21 13 -5 5");
}

.ftqzjnb8u {
  d: path("M6 3v18");
}

.k58vknb8e {
  d: path("m16 13 5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tkvxdludj {
  d: path("M6 3h9l-3 3 3 3H6");
}

</style>
