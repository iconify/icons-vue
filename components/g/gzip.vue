<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6ygr9ymt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gzip" /></template>
<style>
.q6ygr9ymt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h18v6.5H3Zm0 2.75h18M12 2.5v3.75m-2.5-2.5l2.5 2.5l2.5-2.5M12 21.5v-3.25m-2.5 2.5l2.5-2.5l2.5 2.5");
}

</style>
