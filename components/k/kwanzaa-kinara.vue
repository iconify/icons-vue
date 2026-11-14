<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky2g_2dth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kwanzaa-kinara" /></template>
<style>
.ky2g_2dth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5h19V19h-19Zm1.25-6v6m2.75-6v6m2.75-6v6M12 5v10.5m2.75-6v6m2.75-6v6m2.75-6v6");
}

</style>
