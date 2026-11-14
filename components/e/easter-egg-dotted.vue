<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmu4s_byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:easter-egg-dotted" /></template>
<style>
.zmu4s_byk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c4.5 0 7 7.5 7 12c0 4-3 7-7 7s-7-3-7-7c0-4.5 2.5-12 7-12ZM8.5 14h.01M12 14h.01m3.49 0h.01");
}

</style>
