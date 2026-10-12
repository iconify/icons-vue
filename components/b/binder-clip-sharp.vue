<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of-nkrb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:binder-clip-sharp" /></template>
<style>
.of-nkrb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11.25H18l.35 1.46l1.55 6.58l.35 1.46H3.75l.35-1.46l1.55-6.58l.35-1.46zM5.5 16h13m-10-4.75L6 3.5m9.5 7.75L18 3.5");
}

</style>
