<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ztq2uyxtt"/><path class="cgx6h63ll"/><path class="tyca9wtqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:distinction-outline-bold" /></template>
<style>
.cgx6h63ll {
  d: path("M8 13v8l3 -3 3 3v-8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tyca9wtqq {
  d: path("m9 8 2 2 4 -4");
}

.ztq2uyxtt {
  d: path("M6 8a6 6 0 1 0 12 0A6 6 0 1 0 6 8");
}

</style>
