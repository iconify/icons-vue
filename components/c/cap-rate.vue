<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obf3smb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cap-rate" /></template>
<style>
.obf3smb8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.549 21.5H6v-15l12-4v10.151M9.5 10h.01m4.99 0h.01M9.5 13.5h.01M9.5 17h.01M15 21l6-6m-5.5.5h.01m4.99 5h.01");
}

</style>
