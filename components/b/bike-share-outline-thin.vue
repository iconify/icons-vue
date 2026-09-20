<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jwgl0nbvm"/><path class="erfjsdmyp"/><path class="o178hubwo"/><path class="wcu0lhc9k"/><path class="eaabexbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bike-share-outline-thin" /></template>
<style>
.eaabexbql {
  d: path("M3 6v13");
}

.erfjsdmyp {
  d: path("M13.5 15a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwgl0nbvm {
  d: path("M3.5 15a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.o178hubwo {
  d: path("m7 15 3 -3h4l3 3");
}

.wcu0lhc9k {
  d: path("M10 8v4");
}

</style>
