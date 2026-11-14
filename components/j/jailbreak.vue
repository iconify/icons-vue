<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1wuy6zuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jailbreak" /></template>
<style>
.p1wuy6zuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h13v10.5H3Zm9.5 0V6.5a3.75 3.75 0 0 1 7.5 0v3m-10.5 5V18M5.25 8.25L3.5 6.5m5 1.5V5.5");
}

</style>
