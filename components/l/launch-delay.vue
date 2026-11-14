<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gd31j5yyf"/><path class="d-4fj5ien"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:launch-delay" /></template>
<style>
.d-4fj5ien {
  d: path("M7.25 8.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM3 19.5h9.7m2.8-4.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.gd31j5yyf {
  d: path("M8.5 2.5c3.5 2 4 5.5 4 9v4h-8v-4c0-3.5.5-7 4-9Zm-4 9l-2 2.5v2.5l2-1m8-4l.375.469");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
