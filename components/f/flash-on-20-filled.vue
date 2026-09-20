<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ih43k_h7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-on-20-filled" /></template>
<style>
.ih43k_h7b {
  fill: currentColor;
  d: path("M7.212 2c-.474 0-.89.314-1.021.77l-2.25 7.874a1.062 1.062 0 0 0 1.022 1.354H6.23l-1.17 4.68c-.264 1.055 1.041 1.777 1.796.995l8.676-8.858l.004-.004c.64-.667.18-1.811-.767-1.811h-2.564l1.262-3.594l.002-.008A1.062 1.062 0 0 0 12.461 2z");
}

</style>
