<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lro-kbq9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:edit-sharp" /></template>
<style>
.lro-kbq9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.6 4.4l1.5-1.531L18.6 4.4l1 1l1.531 1.5L19.6 8.4L9.1 18.9l-.418.424l-.582.126l-3.6.8l.8-3.6l.126-.582l.424-.418Zm-2.1 2.1l4 4");
}

</style>
