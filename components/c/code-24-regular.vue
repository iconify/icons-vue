<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4u75dbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-24-regular" /></template>
<style>
.d4u75dbbq {
  fill: currentColor;
  d: path("M15.046 1.492a.75.75 0 0 1 1.408.516l-7.5 20.5a.75.75 0 0 1-1.408-.516zm-8.839 4.74a.75.75 0 0 1 1.086 1.036L2.785 12l4.508 4.733a.75.75 0 0 1-1.086 1.035l-5-5.25a.75.75 0 0 1 0-1.036zm10.526-.025a.75.75 0 0 1 1.06.025l5 5.25a.75.75 0 0 1 0 1.036l-5 5.25a.75.75 0 0 1-1.086-1.035L21.215 12l-4.508-4.732a.75.75 0 0 1 .026-1.06");
}

</style>
