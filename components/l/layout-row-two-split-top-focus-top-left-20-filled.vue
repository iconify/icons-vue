<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kl8--lo7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-split-top-focus-top-left-20-filled" /></template>
<style>
.kl8--lo7k {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zm4 6.5V4h4a2 2 0 0 1 2 2v3.5zm6 1V14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-3.5z");
}

</style>
