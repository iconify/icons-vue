<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s71jptzak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:barcode-scanner-32-regular" /></template>
<style>
.s71jptzak {
  fill: currentColor;
  d: path("M3 21a1 1 0 0 1 1 1v2.5A2.5 2.5 0 0 0 6.5 27H9a1 1 0 1 1 0 2H6.5A4.5 4.5 0 0 1 2 24.5V22a1 1 0 0 1 1-1m26 0a1 1 0 0 1 1 1v2.5a4.5 4.5 0 0 1-4.5 4.5H23a1 1 0 1 1 0-2h2.5a2.5 2.5 0 0 0 2.5-2.5V22a1 1 0 0 1 1-1M8 9a1 1 0 0 1 1 1v12a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1m5.5 0a1 1 0 0 1 1 1v12a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1m5 0a1 1 0 0 1 1 1v12a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1M24 9a1 1 0 0 1 1 1v12a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1M9 3a1 1 0 0 1 0 2H6.5A2.5 2.5 0 0 0 4 7.5V10a1 1 0 1 1-2 0V7.5A4.5 4.5 0 0 1 6.5 3zm16.5 0A4.5 4.5 0 0 1 30 7.5V10a1 1 0 1 1-2 0V7.5A2.5 2.5 0 0 0 25.5 5H23a1 1 0 1 1 0-2z");
}

</style>
