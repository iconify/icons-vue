<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zn_e_hboj"/><path class="i64wkrq6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cricket-helmet" /></template>
<style>
.i64wkrq6e {
  d: path("M13 18.75h3.5c2.5 0 4-3 4-6.5m-3.75 0v6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zn_e_hboj {
  d: path("M3.5 18.75v-4.5c0-5.25 4-9 9-9c4.25 0 7.25 3 8 7H13v6.5Z");
}

</style>
