<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b7w1ydb1k"/><path class="cpwizubfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fossil-in-rock" /></template>
<style>
.b7w1ydb1k {
  d: path("m2.5 11.5l2.5-7L12 3l7.5 1.5l2 9.5l-3 6.5H6Z");
}

.cpwizubfo {
  d: path("M8.25 10C6.5 10 5.5 11 5.5 12.25s1 2.25 2.75 2.25Zm0 2.25h8.25M11 10v4.5m2.75-4.5v4.5m4.75-4.25l-2 2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
