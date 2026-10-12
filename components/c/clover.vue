<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh79lh47d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clover" /></template>
<style>
.zh79lh47d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 8.75c-2.43.57-4.17.34-4.91-.75c-.7-1.04.23-2.55 1.91-2.25c-.3-1.68 1.21-2.61 2.25-1.91c1.09.74 1.32 2.48.75 4.91m3 0c-.57-2.43-.34-4.17.75-4.91c1.04-.7 2.55.23 2.25 1.91c1.68-.3 2.61 1.21 1.91 2.25c-.74 1.09-2.48 1.32-4.91.75m0 3c2.43-.57 4.17-.34 4.91.75c.7 1.04-.23 2.55-1.91 2.25c.3 1.68-1.21 2.61-2.25 1.91c-1.09-.74-1.32-2.48-.75-4.91m-3 0c.57 2.43.34 4.17-.75 4.91c-1.04.7-2.55-.23-2.25-1.91c-1.68.3-2.61-1.21-1.91-2.25c.74-1.09 2.48-1.32 4.91-.75M12 18c0 1.5.5 2.5 1.5 3.25");
}

</style>
