<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0zp-kzxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-alert" /></template>
<style>
.o0zp-kzxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.25A2.5 2.5 0 1 1 13.25 10A2.5 2.5 0 1 1 10 12.5A2.5 2.5 0 1 1 6.75 10A2.5 2.5 0 1 1 8 6.25a2.5 2.5 0 1 1 4 0Zm-2 6.25v9M10 9h.01M18 14.75v3.5M18 21h.01");
}

</style>
