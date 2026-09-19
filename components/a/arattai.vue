<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dre2t3b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arattai" /></template>
<style>
.dre2t3b4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 8.994v30.475M11.982 15.94V8.531h21.889v30.054l-7.387-3.031H5.5V22.21h16.922");
}

</style>
