<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klntusb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-search" /></template>
<style>
.klntusb0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 2L8 2C5.7909 2 4 3.7909 4 6L4 18C4 20.2091 5.7909 22 8 22L10 22M14 2L20 8L20 12M14 2L14 5C14 6.6569 15.3431 8 17 8L20 8M19 18.5C19 19.8807 17.8807 21 16.5 21C15.1193 21 14 19.8807 14 18.5C14 17.1193 15.1193 16 16.5 16C17.8807 16 19 17.1193 19 18.5ZM18.5 20.5L20 22");
}

</style>
