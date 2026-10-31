<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="li0-r5bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-cancel-32-filled" /></template>
<style>
.li0-r5bgz {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15m6 .792A9 9 0 0 0 16.292 29H7.5A4.5 4.5 0 0 1 3 24.5V11h26zm-2.22 2.928a.75.75 0 0 0-1.06 0L23 21.94l-2.72-2.72a.75.75 0 1 0-1.06 1.06L21.94 23l-2.72 2.72a.75.75 0 1 0 1.06 1.06L23 24.06l2.72 2.72a.75.75 0 1 0 1.06-1.06L24.06 23l2.72-2.72a.75.75 0 0 0 0-1.06M24.5 3A4.5 4.5 0 0 1 29 7.5V9H3V7.5A4.5 4.5 0 0 1 7.5 3z");
}

</style>
