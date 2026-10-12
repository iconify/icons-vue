<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx-9d113h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bongo-sharp" /></template>
<style>
.kx-9d113h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5h7l-.07 1l-.86 12.75l-.07 1h-6l-.07-1L2.82 6l-.07-1zm10.5 3h7l-.08 1l-.84 9.75l-.08 1h-6l-.08-1L13.33 9l-.08-1zm-4.04 5h3.47");
}

</style>
