<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwl3o3iiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:escalation-tier-3" /></template>
<style>
.xwl3o3iiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 9.25l7.5-5.5l7.5 5.5m-15 5.5l7.5-5.5l7.5 5.5m-15 5.5l7.5-5.5l7.5 5.5");
}

</style>
