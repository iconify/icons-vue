<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m7l4_ac3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-32-regular" /></template>
<style>
.m7l4_ac3w {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14s-6.268 14-14 14c-2.368 0-4.602-.589-6.56-1.629l-5.528 1.573a1.5 1.5 0 0 1-1.853-1.854l1.571-5.527A13.94 13.94 0 0 1 2 16C2 8.268 8.27 2 16 2m0 2C9.374 4 4 9.373 4 16c0 2.165.573 4.193 1.574 5.944a1 1 0 0 1 .093.77l-1.439 5.06l5.06-1.439a1 1 0 0 1 .77.094C11.81 27.429 13.837 28 16 28c6.628 0 12-5.373 12-12S22.629 4 16 4m5.293 7.293a1 1 0 0 1 1.414 1.414l-7.502 7.5a1 1 0 0 1-1.414 0L9.793 16.21a1 1 0 0 1 1.414-1.414l3.29 3.291z");
}

</style>
