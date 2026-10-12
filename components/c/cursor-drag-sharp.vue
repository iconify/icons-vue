<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zswvy3fop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursor-drag-sharp" /></template>
<style>
.zswvy3fop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.41 7.71l10.18 4.08l1.16.46l-1.17.44l-3.66 1.37l-1.17.44l-.42 1.18l-1.41 3.89l-.42 1.18l-.38-1.19L8.63 8.44l-.38-1.19zm-4.66-.46h-2m4.5-2.5v-2m-2 2.5l-1.5-1.5");
}

</style>
