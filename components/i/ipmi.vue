<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn7g7z-xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ipmi" /></template>
<style>
.fn7g7z-xi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 15.5h-10v-12h19v9.4m-15-3.4h.01m3.49 0h7.5M16 15.25a3 3 0 1 0 4 0m-2-1.75v4");
}

</style>
