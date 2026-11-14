<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kap_zgbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mace-ceremonial" /></template>
<style>
.kap_zgbvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM4.5 19.5l8.75-8.75M9 12.25l3 3m6.75-10L20.5 3.5");
}

</style>
