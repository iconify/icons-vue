<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ami2-8bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-speaker-notes-off" /></template>
<style>
.ami2-8bli {
  fill: currentColor;
  d: path("m10.54 11l-.54-.54L7.54 8L6 6.46L2.38 2.84L1.27 1.73L0 3l2.01 2.01L2 22l4-4h9l5.73 5.73L22 22.46L17.54 18zM8 14H6v-2h2zm-2-3V9l2 2zm14-9H4.08L10 7.92V6h8v2h-7.92l1 1H18v2h-4.92l6.99 6.99C21.14 17.95 22 17.08 22 16V4c0-1.1-.9-2-2-2");
}

</style>
