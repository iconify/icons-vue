<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h8u13ptub"/><path clip-rule="evenodd" class="nljpz4_zk"/><path clip-rule="evenodd" class="n6w6yrx7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aquarius" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h8u13ptub {
  fill: var(--svg-color--872ab0, #872ab0);
  d: path("M3 12c0-3.901 0-5.852 1.058-7.178q.34-.424.764-.764C6.148 3 8.1 3 12 3s5.852 0 7.178 1.058q.424.34.764.764C21 6.148 21 8.1 21 12s0 5.852-1.058 7.178a5 5 0 0 1-.764.764C17.852 21 15.9 21 12 21s-5.852 0-7.178-1.058a5 5 0 0 1-.764-.764C3 17.852 3 15.9 3 12");
}

.n6w6yrx7u {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m13.65 7.905l2.008 2l1.992-1.987l.875.866l-2.867 2.858l-2.007-1.999l-3.165 3.153l-1.699-1.692l-2.033 2.025l-.874-.867l2.907-2.896l1.699 1.692Z");
}

.nljpz4_zk {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m13.65 11.276l2.008 2l1.992-1.987l.875.866l-2.867 2.858l-2.007-2l-3.165 3.154l-1.699-1.692L6.755 16.5l-.874-.867l2.907-2.896l1.699 1.692Z");
}

</style>
