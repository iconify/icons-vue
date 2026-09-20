<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anh1z2p1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-circle-24-regular" /></template>
<style>
.anh1z2p1r {
  fill: currentColor;
  d: path("M14.545 6.06a.75.75 0 0 1 .394.986l-4.5 10.5a.75.75 0 0 1-1.378-.591l4.5-10.5a.75.75 0 0 1 .984-.394M8.807 9.249a.75.75 0 0 1-.055 1.06L6.872 12l1.88 1.693a.75.75 0 0 1-1.004 1.114l-2.5-2.25a.75.75 0 0 1 0-1.114l2.5-2.25a.75.75 0 0 1 1.06.055m6.386 0a.75.75 0 0 0 .055 1.06L17.128 12l-1.88 1.693a.75.75 0 1 0 1.004 1.114l2.5-2.25a.75.75 0 0 0 0-1.114l-2.5-2.25a.75.75 0 0 0-1.06.055M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12s4.477 10 10 10s10-4.477 10-10M3.5 12a8.5 8.5 0 1 1 17 0a8.5 8.5 0 0 1-17 0");
}

</style>
