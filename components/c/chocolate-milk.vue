<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-6b4necy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chocolate-milk" /></template>
<style>
.r-6b4necy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.695 20.5H4.75L3.5 3h13l-.62 8.678M3.75 7.5h12.5m-.75 7h6v7h-6Zm0 3.5h6");
}

</style>
