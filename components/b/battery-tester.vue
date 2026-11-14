<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1u2acb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-tester" /></template>
<style>
.n1u2acb8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5h6v13h-6Zm1.75-2h2.5v2h-2.5ZM11.5 13a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm4.25 1.75l2.25-4");
}

</style>
