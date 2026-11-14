<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t9qo4abtf"/><path class="de7yr4bfy"/><path class="xmjzcabdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashboard-settings" /></template>
<style>
.de7yr4bfy {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5m-3.5 10.25h7m-7 4.5h7");
}

.t9qo4abtf {
  d: path("M11.7 21.5H2.5v-19h19v10.4M2.5 11h19M11 11v10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmjzcabdq {
  fill: currentColor;
  d: path("M15.5 15.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm2.5 4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
