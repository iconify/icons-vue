<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2b0b_w9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-map-pin-corner-fill" /></template>
<style>
.m2b0b_w9y {
  fill: currentColor;
  d: path("M10 9a.997.997 0 0 0-1 1v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l4.397 3.847A1.001 1.001 0 0 1 17.714 9Zm5.184 11.777C13.952 19.518 13 17.798 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0a8 8 0 0 1-1.261-1.055m1.11-4.069A1 1 0 0 0 17 17h.01a1 1 0 0 0 0-2H17a1 1 0 0 0-.925.621a.99.99 0 0 0 .216 1.085l.002.001Z");
}

</style>
