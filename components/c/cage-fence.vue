<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwfjo5_iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cage-fence" /></template>
<style>
.jwfjo5_iw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3h7L21 8.5v7L15.5 21h-7L3 15.5v-7ZM3.25 8.25l12.5 12.5m-7.5-17.5l12.5 12.5m-17.5 0l12.5-12.5m-7.5 17.5l12.5-12.5");
}

</style>
