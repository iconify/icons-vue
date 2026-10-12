<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s03y58bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:geyser" /></template>
<style>
.s03y58bpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.07 20.74l1.11-1.73q.32-.51.92-.51h13.8q.6 0 .92.51l1.11 1.73q.32.51-.28.51H3.35q-.6 0-.28-.51M12 15.5V4.25m0 0c-1.75-1-3.25-.75-4.5 1m4.5-1c1.75-1 3.25-.75 4.5 1M6.5 15q-1.125-1.125 0-2.25c1.125-1.125.75-1.5 0-2.25m11 4.5q-1.125-1.125 0-2.25c1.125-1.125.75-1.5 0-2.25");
}

</style>
