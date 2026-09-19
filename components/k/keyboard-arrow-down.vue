<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f21ig-h_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:keyboard-arrow-down" /></template>
<style>
.f21ig-h_x {
  fill: currentColor;
  d: path("M7.41 8.59L12 13.17l4.59-4.58L18 10l-6 6l-6-6z");
}

</style>
