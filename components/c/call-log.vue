<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wp__5bt_s"/><path class="yt114ybnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-log" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wp__5bt_s {
  d: path("M13.2 19.5H2.5v-15h19v11.6M6 8h12M6 12h8.1M6 16h5");
}

.yt114ybnw {
  d: path("M15 15.25a.75.75 0 0 1 .75-.75h1.5l.75 2.25l-1.25 1a2 2 0 0 0 2 2l1-1.25l2.25.75v1.5a.75.75 0 0 1-.75.75A6.25 6.25 0 0 1 15 15.25Z");
}

</style>
