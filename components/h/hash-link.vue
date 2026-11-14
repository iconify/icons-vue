<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl3x2dbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hash-link" /></template>
<style>
.zl3x2dbeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 3l-.75 9m4.75-9l-.75 9M3 6h9.5M2.75 9.25H12m.75 6.25H12a2.5 2.5 0 0 0 0 5h.75m3.5-5H17a2.5 2.5 0 0 1 0 5h-.75M12.5 18h4");
}

</style>
