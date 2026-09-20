<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qot-h_byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:asterisk-thin" /></template>
<style>
.qot-h_byj {
  fill: currentColor;
  d: path("M211.43 178.06a4 4 0 0 1-5.49 1.37L132 135.06V216a4 4 0 0 1-8 0v-80.94l-73.94 44.37a4 4 0 0 1-4.12-6.86L120.22 128L45.94 83.43a4 4 0 0 1 4.12-6.86L124 120.94V40a4 4 0 0 1 8 0v80.94l73.94-44.37a4 4 0 1 1 4.12 6.86L135.78 128l74.28 44.57a4 4 0 0 1 1.37 5.49");
}

</style>
