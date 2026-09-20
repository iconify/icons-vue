<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q6sxctuqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-checkmark-32-filled" /></template>
<style>
.q6sxctuqg {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15m6-4.5v5.292A9 9 0 0 0 16.292 29H7.5A4.5 4.5 0 0 1 3 24.5V11zm-1.47 9.22a.75.75 0 0 0-1.06 0l-4.72 4.72l-1.97-1.97a.75.75 0 1 0-1.06 1.06l2.5 2.5a.75.75 0 0 0 1.06 0l5.25-5.25a.75.75 0 0 0 0-1.06M24.5 3A4.5 4.5 0 0 1 29 7.5V9H3V7.5A4.5 4.5 0 0 1 7.5 3z");
}

</style>
