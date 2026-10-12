<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0t-5d1fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anchor-bolt-sharp" /></template>
<style>
.u0t-5d1fu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15h18.5v6.25H2.75zM12 15v3.25m0-15V9m0 3v3M7.5 9h9v3h-9zm3 0v3m3-3v3");
}

</style>
