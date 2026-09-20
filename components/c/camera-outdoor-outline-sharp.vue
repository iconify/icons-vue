<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmxedvvje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:camera-outdoor-outline-sharp" /></template>
<style>
.bmxedvvje {
  fill: currentColor;
  d: path("M12 18v-6h6v2l2-1.05v4.1L18 16v2zm-8 3V9l8-6l8 6v2h-2v-1l-6-4.5L6 10v9h14v2zm8-8.75");
}

</style>
