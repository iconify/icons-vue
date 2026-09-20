<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kbnq5bc4a"/><path class="dk5jyixqt"/><path class="i2-ny_bzf"/><path class="mxzk029nb"/><path class="ffs26fbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flip-horizontal-outline-bold" /></template>
<style>
.dk5jyixqt {
  d: path("m15 5 7 7 -7 7Z");
}

.ffs26fbkv {
  d: path("M12 17v4");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.kbnq5bc4a {
  d: path("m9 5 -7 7 7 7Z");
}

.mxzk029nb {
  d: path("M12 10v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
