<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ltqg7bcqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-12-filled" /></template>
<style>
.ltqg7bcqx {
  fill: currentColor;
  d: path("M6 0a2.5 2.5 0 0 1 2.5 2.5v1.565A2 2 0 0 1 10 6v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 1.5-1.935V2.5A2.5 2.5 0 0 1 6 0m0 6.75a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M6 1a1.5 1.5 0 0 0-1.5 1.5V4h3V2.5A1.5 1.5 0 0 0 6 1");
}

</style>
