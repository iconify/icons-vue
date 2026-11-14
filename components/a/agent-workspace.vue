<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pq2inq04c"/><path class="n1gp3y5hw"/><path class="ciid5bzeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-workspace" /></template>
<style>
.ciid5bzeo {
  d: path("M8.5 9.5v-.75a3.5 3.5 0 0 1 7 0v.75m-7.5 7c0-1.9 1.8-3.25 4-3.25s4 1.35 4 3.25");
}

.n1gp3y5hw {
  d: path("M10.25 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.pq2inq04c {
  d: path("M2.5 3h19v13.5h-19ZM12 16.5v4m-3.5 0h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
