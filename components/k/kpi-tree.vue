<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3u9a76lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kpi-tree" /></template>
<style>
.s3u9a76lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11V9h-11ZM2.5 15h8v6h-8Zm11 0h8v6h-8Zm-4-9.25h5M12 9v3m-5.5 3v-3h11v3");
}

</style>
