<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2y9v-u5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brick-wall-sharp" /></template>
<style>
.u2y9v-u5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.25h18.5v15.5H2.75zm0 5.25h18.5m-18.5 5h18.5M12 4.25V9.5m-4.5 0v5m9-5v5m-4.5 0v5.25");
}

</style>
