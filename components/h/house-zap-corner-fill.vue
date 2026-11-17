<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-ka4b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-zap-corner-fill" /></template>
<style>
.f0-ka4b7o {
  fill: currentColor;
  d: path("M17.714 9H10a.997.997 0 0 0-1 1v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l4.397 3.847A1.001 1.001 0 0 1 17.714 9m1.993 4.707L17.414 16H20a1.002 1.002 0 0 1 .707 1.707l-4 4a.999.999 0 1 1-1.414-1.414L17.586 18H15a1.002 1.002 0 0 1-.707-1.707l4-4a.999.999 0 1 1 1.414 1.414");
}

</style>
