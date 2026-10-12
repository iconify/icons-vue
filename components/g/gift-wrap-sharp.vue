<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2phcbbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gift-wrap-sharp" /></template>
<style>
.n2phcbbiz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h18v3.5H3zm1.75 3.5v10.75h14.5V10.5M12 7v14.25M12 7c-1.5-4-5.75-4.5-5.5-1.75l.123 1.291L8 7m4 0c1.5-4 5.75-4.5 5.5-1.75l-.123 1.291L16 7");
}

</style>
