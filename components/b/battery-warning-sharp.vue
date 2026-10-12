<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy4f59b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:battery-warning-sharp" /></template>
<style>
.xy4f59b7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25h18.5v13H2.75zm2.5-2.75h3.5v2.75h-3.5zm10 0h3.5v2.75h-3.5zM12 10.25v4.5m0 2.5v.01");
}

</style>
