<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4a0pabaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:entertainment-law" /></template>
<style>
.h4a0pabaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5L16.25 5l-.75-2.75l-13.25 3.5zm10.821 9H4.5q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T3 16V8.5h13.5v3.9M7.75 7.25L7 4.5M12.75 6L12 3.25M17.875 15h2.5a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-2.5a1.375 1.375 0 0 1-1.375-1.375A1.375 1.375 0 0 1 17.875 15M19 17.75l-3.25 3.5");
}

</style>
