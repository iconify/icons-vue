<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jlkpmjb6r"/><circle class="c1myp4vea"/><path class="a0x7qs0dl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:job-search" /></template>
<style>
.a0x7qs0dl {
  d: path("m18.25 18l3 3");
}

.c1myp4vea {
  cx: 16px;
  cy: 15.75px;
  r: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlkpmjb6r {
  d: path("M10.25 17.25h-5a2.5 2.5 0 0 1-2.5-2.5v-5.5a2.5 2.5 0 0 1 2.5-2.5h10a2.5 2.5 0 0 1 2.5 2.5v1m-10-3.5v-1.5a1.5 1.5 0 0 1 1.5-1.5h2.5a1.5 1.5 0 0 1 1.5 1.5v1.5");
}

</style>
