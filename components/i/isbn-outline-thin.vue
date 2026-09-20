<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qltxbpdvm"/><path class="tr_jskylo"/><path class="z3it7clmt"/><path class="leemd3bqp"/><path class="h9fb_9biv"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:isbn-outline-thin" /></template>
<style>
.h9fb_9biv {
  d: path("M20 5v12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.leemd3bqp {
  d: path("M15 5v12");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.qltxbpdvm {
  d: path("M4 5v12");
}

.tr_jskylo {
  d: path("M7 5v12");
}

.z3it7clmt {
  d: path("M11 5v12");
}

</style>
