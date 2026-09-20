<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="stq1nvbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-horizontal-32-regular" /></template>
<style>
.stq1nvbki {
  fill: currentColor;
  d: path("M29.842 27.54A1 1 0 0 1 29 28H18a1 1 0 0 1-1-1V3a1 1 0 0 1 1.91-.417l11 24a1 1 0 0 1-.068.957M19 7.582V26h8.442zM3 28a1 1 0 0 1-.91-1.417l11-24A1 1 0 0 1 15 3v24a1 1 0 0 1-1 1z");
}

</style>
