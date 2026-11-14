<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm2zuqb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:demolition-wall" /></template>
<style>
.sm2zuqb7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5h8v11H3Zm0 3.75h8M3 17h8M7 9.5v3.75M7 17v3.5m7-6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm3.5-11v7.5");
}

</style>
