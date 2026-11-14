<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9a_yd4lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anti-inflammatory" /></template>
<style>
.e9a_yd4lq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.027 21.5H12c-3.75 0-7-3-7-7c0-3 1.5-5 3-6.5c.25 2 1.25 3.25 2.5 3.75c-.25-3.5.25-6.75 1.5-9.25c2.629 2.254 5.259 5.072 6.404 8.454m.76 3.157l2.475 2.475l-5.303 5.303l-2.475-2.475Zm-2.651 2.652l2.474 2.474");
}

</style>
