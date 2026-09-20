<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bmezcze2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:luggage-32-filled" /></template>
<style>
.bmezcze2w {
  fill: currentColor;
  d: path("M10 2a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2h-.5v2h2A4.5 4.5 0 0 1 27 9.5v15a4.5 4.5 0 0 1-4 4.473V30a1 1 0 1 1-2 0v-1H11v1a1 1 0 1 1-2 0v-1.027A4.5 4.5 0 0 1 5 24.5v-15A4.5 4.5 0 0 1 9.5 5H12V3h-1a1 1 0 0 1-1-1m4 1v2h4.5V3zm-3 8a1 1 0 1 0 0 2h10a1 1 0 1 0 0-2z");
}

</style>
