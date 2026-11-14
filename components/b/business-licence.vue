<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sxzorq2ir"/><path class="nj_a4hb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-licence" /></template>
<style>
.nj_a4hb-c {
  d: path("M7.5 20.5v-6H11v3.3m0 .4v2.3m3.75-2.5l2 2L21 15.75");
}

.sxzorq2ir {
  d: path("m3 9l1.75-5.5h14.5L21 9Zm1.5 0v11.5h8.8m6.2-7.2V9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
