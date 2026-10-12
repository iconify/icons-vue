<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxoezwdab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:composition-grid-sharp" /></template>
<style>
.qxoezwdab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25v-3.5h3.5m11.5 0h3.5v3.5m0 5.5v3.5h-3.5m-11.5 0h-3.5v-3.5m3.75 1l11-7.5m-11 0l3.5 5.12m7.5 2.38L14 10.63");
}

</style>
