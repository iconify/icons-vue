<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcaw1rmdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bus-stop-sharp" /></template>
<style>
.xcaw1rmdm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h6.5v6.5h-6.5zM7 9.25v12m5.75-12.5h8.5v10h-8.5zm0 4h8.5m-6.25 6v2m4-2v2");
}

</style>
