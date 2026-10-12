<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vku-esbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:electric-guitar" /></template>
<style>
.vku-esbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.96 9.76l.51-1.54q.38-1.14.54.05l.25 1.86q.15 1.19 1 2.04l.57.57q.85.85 2.03 1.06l.75.14q1.18.21.22.94l-1.62 1.23q-.96.73-1.59 1.75l-1 1.63q-.63 1.03-1.83 1.03H7.8q-1.2 0-2.05-.85l-1.42-1.42q-.85-.85-.85-2.05v-.99q0-1.2 1.08-1.74l.68-.34q1.07-.53 2.03-1.25l.35-.26q.96-.72 1.34-1.86m7.68-2.96l.63.63q.43.43.85 0l1.27-1.27q.43-.42 0-.85l-.63-.63q-.43-.43-.85 0l-1.27 1.27q-.43.42 0 .85m-5.09 5.65l5.51-5.51m-9.05 6.22l2.83 2.83M6.17 15L9 17.83");
}

</style>
