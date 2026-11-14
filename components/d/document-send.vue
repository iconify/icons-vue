<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2isdrm_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:document-send" /></template>
<style>
.v2isdrm_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10a2 2 0 0 1 2-2h5l3.5 3.5v8a2 2 0 0 1-2 2H4.5a2 2 0 0 1-2-2Zm15.129-5.373l-2.311 1.116a.754.754 0 0 0 .057 1.382l.944.363a1.5 1.5 0 0 1 .895.959l.286.928a.58.58 0 0 0 1.097.033l1.089-2.903a1.5 1.5 0 0 0-2.057-1.878M17 7.75L21 3M5.5 14H9m-3.5 4H8");
}

</style>
