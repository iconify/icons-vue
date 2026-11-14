<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl9d8tbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:container-delete" /></template>
<style>
.kl9d8tbwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.4 15.5H2.5v-12h19v7.9m-15-5.15v6.5m3.5-6.5v6.5m3.5-6.5v6.5M15.25 16h6.5m-5.5 0l.5 5.5h3.5l.5-5.5m-3.5 0v-1.75h2.5V16");
}

</style>
