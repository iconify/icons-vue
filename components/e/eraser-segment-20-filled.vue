<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p72xavbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:eraser-segment-20-filled" /></template>
<style>
.p72xavbuu {
  fill: currentColor;
  d: path("M13.318 2.44a1.5 1.5 0 0 0-2.121 0l-8.76 8.759a1.5 1.5 0 0 0 0 2.121l4.243 4.243c.313.313.73.459 1.14.437h6.265a1.5 1.5 0 1 0 0-1h-4.72l8.196-8.197a1.5 1.5 0 0 0 0-2.121zm-8.487 7.78l4.95 4.949l-1.687 1.687a.5.5 0 0 1-.707 0l-4.243-4.243a.5.5 0 0 1 0-.707z");
}

</style>
