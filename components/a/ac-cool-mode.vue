<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygx_aac0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ac-cool-mode" /></template>
<style>
.ygx_aac0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v11M7.25 5.75l9.5 5.5m-9.5 0l9.5-5.5M12 17v4.5M9.5 19l2.5 2.5l2.5-2.5");
}

</style>
