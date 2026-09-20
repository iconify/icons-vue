<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wisu-zz6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hat-graduation-48-filled" /></template>
<style>
.wisu-zz6p {
  fill: currentColor;
  d: path("M20.588 7.014a6.25 6.25 0 0 1 6.824 0l16.02 10.44a1.25 1.25 0 0 1 0 2.094l-16.02 10.44a6.25 6.25 0 0 1-6.824 0L6.5 20.808V31.75a1.25 1.25 0 0 1-2.5 0V18.5c0-.453.242-.852.605-1.07zM11 35.75v-9.623l8.496 5.536a8.25 8.25 0 0 0 9.008 0L37 26.127v9.623q0 .12-.005.238a1.25 1.25 0 0 1-.372.844A17.95 17.95 0 0 1 24 42a17.95 17.95 0 0 1-12.623-5.168a1.25 1.25 0 0 1-.373-.844A6 6 0 0 1 11 35.75");
}

</style>
