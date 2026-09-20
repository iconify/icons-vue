<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iyglhogsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-below-32-regular" /></template>
<style>
.iyglhogsp {
  fill: currentColor;
  d: path("M28 27a1 1 0 1 1 0 2H4a1 1 0 1 1 0-2zM24.5 3A4.5 4.5 0 0 1 29 7.5V20a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V7.5A4.5 4.5 0 0 1 7.5 3zm-17 2A2.5 2.5 0 0 0 5 7.5V19h22V7.5A2.5 2.5 0 0 0 24.5 5z");
}

</style>
