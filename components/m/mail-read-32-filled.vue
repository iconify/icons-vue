<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cceribtle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-read-32-filled" /></template>
<style>
.cceribtle {
  fill: currentColor;
  d: path("M13.745 2.623a4.5 4.5 0 0 1 4.51 0l9.5 5.5a4.5 4.5 0 0 1 1.587 1.552L16 16.865L2.653 9.682a4.5 4.5 0 0 1 1.592-1.56zm-11.727 8.99q-.018.2-.018.405V22.5A4.5 4.5 0 0 0 6.5 27h19a4.5 4.5 0 0 0 4.5-4.5V12.018q0-.21-.02-.415L16.475 18.88a1 1 0 0 1-.948 0z");
}

</style>
