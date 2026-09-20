<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mmg8iphml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-0-32-filled" /></template>
<style>
.mmg8iphml {
  fill: currentColor;
  d: path("M6.5 8A4.5 4.5 0 0 0 2 12.5v7A4.5 4.5 0 0 0 6.5 24h17a4.5 4.5 0 0 0 4.5-4.5V19h.5a1.5 1.5 0 0 0 1.5-1.5v-3a1.5 1.5 0 0 0-1.5-1.5H28v-.5A4.5 4.5 0 0 0 23.5 8z");
}

</style>
