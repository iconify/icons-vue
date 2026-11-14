<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u6sg-rbpc"/><path class="t4xucwvgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-activate" /></template>
<style>
.t4xucwvgp {
  d: path("M19.721 15.793a3 3 0 1 1-3.442 0M18 14.75v2.75");
}

.u6sg-rbpc {
  d: path("M12.2 19H2.5V5h19v8.6m-19-4.1h19m-19 0h19M6 15h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
