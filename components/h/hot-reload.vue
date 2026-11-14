<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfdz4thtj"/><path class="no73d75sv"/><path class="ojevw_b1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-reload" /></template>
<style>
.gfdz4thtj {
  d: path("M16 5.072a8 8 0 0 1 0 13.856m-8 0A8 8 0 0 1 8 5.072");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.no73d75sv {
  d: path("M18.75 19.75L16 19l.75-3M5.25 4.25L8 5l-.75 3");
}

.ojevw_b1g {
  fill: currentColor;
  d: path("m11.712 9.11l-1.775 2.219A.721.721 0 0 0 10.5 12.5a1.17 1.17 0 0 1 1.136 1.455l-.136.545a.45.45 0 0 0 .788.39l1.775-2.219A.721.721 0 0 0 13.5 11.5a1.17 1.17 0 0 1-1.136-1.455L12.5 9.5a.45.45 0 0 0-.788-.39");
}

</style>
