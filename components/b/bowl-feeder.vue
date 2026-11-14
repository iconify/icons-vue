<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jp446ab6i"/><path class="wk5t6mpqm"/><path class="plss6k64m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bowl-feeder" /></template>
<style>
.jp446ab6i {
  d: path("M2.5 5h19c0 8-4.5 11.5-9.5 11.5S2.5 13 2.5 5ZM12 16.5V20m-4 0h8");
}

.plss6k64m {
  d: path("M9.25 10.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wk5t6mpqm {
  d: path("M7 12q7 2 12.5-7");
}

</style>
