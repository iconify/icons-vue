<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qrp-a1b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-32-filled" /></template>
<style>
.qrp-a1b0x {
  fill: currentColor;
  d: path("M2 16C2 8.268 8.268 2 16 2s14 6.268 14 14s-6.268 14-14 14c-2.368 0-4.602-.589-6.56-1.629l-5.528 1.572A1.5 1.5 0 0 1 2.06 28.09l1.572-5.527A13.94 13.94 0 0 1 2 16m8-3a1 1 0 0 0 1 1h10a1 1 0 1 0 0-2H11a1 1 0 0 0-1 1m1 5a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2z");
}

</style>
