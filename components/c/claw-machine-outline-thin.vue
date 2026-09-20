<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lp3etd4mx"/><path class="lh_8lcb-x"/><path class="tk9hd5usx"/><path class="s24u-_b8l"/><path class="d-_u6mtyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:claw-machine-outline-thin" /></template>
<style>
.d-_u6mtyl {
  d: path("M14 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lh_8lcb-x {
  d: path("M12 4v6");
}

.lp3etd4mx {
  d: path("M3 4v17h18V4Z");
}

.s24u-_b8l {
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.tk9hd5usx {
  d: path("m9 13 3 -3 3 3");
}

</style>
