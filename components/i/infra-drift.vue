<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtj3ewvgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:infra-drift" /></template>
<style>
.mtj3ewvgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h15v6h-15Zm8.7 15H2.5v-6h16v.2m-9-6.2h.01m-4.01 9h.01m12.49 0V18m0 3h.01");
}

</style>
