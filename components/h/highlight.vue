<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_gvg5bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:highlight" /></template>
<style>
.q_gvg5bns {
  fill: currentColor;
  d: path("M5.65 8L3.5 5.9l1.4-1.45L7.05 6.6zM11 5V2h2v3zm7.4 3l-1.45-1.4l2.15-2.1l1.4 1.4zM9 22v-5l-3-3V9h12v5l-3 3v5z");
}

</style>
