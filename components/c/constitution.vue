<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nqt-62bnq"/><rect class="k_-l91bhq"/><rect class="rp-ou3bem"/><path class="rpuzxgb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:constitution" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_-l91bhq {
  width: 14.5px;
  height: 3.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 1.75px;
}

.nqt-62bnq {
  d: path("M6.25 6.25h11.5v11.5H6.25Z");
}

.rp-ou3bem {
  width: 14.5px;
  height: 3.5px;
  x: 4.75px;
  y: 17.75px;
  rx: 1.75px;
}

.rpuzxgb9i {
  d: path("M8.75 9h6.5m-6.5 2.75h6.5m-6.5 2.75h4");
}

</style>
