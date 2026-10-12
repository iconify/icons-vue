<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kugz2kg3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airplane-mode" /></template>
<style>
.kugz2kg3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.03 3.78l.19.19q.53.53.02 1.08l-3.23 3.4q-.51.55-.31 1.27l2.35 8.31q.2.72-.33 1.25l-.44.44q-.53.53-.91-.11l-3.99-6.72q-.38-.64-.89-.09l-2.73 2.9q-.51.55-.46 1.3l.15 2q.05.75-.45 1.25t-.89-.14l-1.22-1.97q-.39-.64-1.03-1.03l-1.97-1.22q-.64-.39-.14-.89T5 14.55l2 .15q.75.05 1.3-.46l2.9-2.73q.55-.51-.09-.89L4.39 6.63q-.64-.38-.11-.91l.44-.44q.53-.53 1.25-.31l8.31 2.56q.72.22 1.25-.31l3.44-3.44q.53-.53 1.06 0");
}

</style>
