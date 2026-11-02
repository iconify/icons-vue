<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrd1trbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-fill" /></template>
<style>
.qrd1trbms {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 1 5.829V18a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V8.829A3.001 3.001 0 0 1 5 3m1 6v9a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V9Zm8 2a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
