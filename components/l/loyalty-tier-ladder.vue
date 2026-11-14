<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2gsalgxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loyalty-tier-ladder" /></template>
<style>
.o2gsalgxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20zA1.5 1.5 0 0 1 4 18.5h3A1.5 1.5 0 0 0 8.5 17v-.5A1.5 1.5 0 0 1 10 15h3a1.5 1.5 0 0 0 1.5-1.5v-.25a1.5 1.5 0 0 1 1.5-1.5h4a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20M18.514 4.417l.177.315a1.5 1.5 0 0 0 1.015.737l.354.071a.59.59 0 0 1 .318.978l-.245.265a1.5 1.5 0 0 0-.388 1.193l.042.359a.59.59 0 0 1-.832.605l-.328-.151a1.5 1.5 0 0 0-1.254 0l-.328.151a.59.59 0 0 1-.832-.605l.042-.359a1.5 1.5 0 0 0-.388-1.193l-.245-.265a.59.59 0 0 1 .318-.978l.354-.071a1.5 1.5 0 0 0 1.015-.737l.177-.315a.59.59 0 0 1 1.028 0");
}

</style>
