<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi5t206xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hair-dye" /></template>
<style>
.zi5t206xl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13 8.25l5.75-5.5m-5.67 6.58l-1.16-1.16q-.42-.42-.84 0L9.92 9.33q-.42.42 0 .84l1.16 1.16q.42.42.84 0l1.16-1.16q.42-.42 0-.84M2.75 14h14.5a7.25 7.25 0 0 1-14.5 0M6 17h8");
}

</style>
