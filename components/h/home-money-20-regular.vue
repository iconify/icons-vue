<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="meixd_byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-money-20-regular" /></template>
<style>
.meixd_byy {
  fill: currentColor;
  d: path("M16.5 12a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-6A1.5 1.5 0 0 1 9 16.5v-3a1.5 1.5 0 0 1 1.5-1.5zM8.996 2.386a1.5 1.5 0 0 1 2.008 0l5.5 4.949A1.5 1.5 0 0 1 17 8.45v2.6a2.5 2.5 0 0 0-.5-.05H16V8.45a.5.5 0 0 0-.165-.372l-5.5-4.95a.5.5 0 0 0-.67 0l-5.5 4.95A.5.5 0 0 0 4 8.45v7.055a.5.5 0 0 0 .5.5H8v.495q0 .26.05.505H4.5a1.5 1.5 0 0 1-1.5-1.5V8.45c0-.425.18-.83.496-1.115zM10 16.5a.5.5 0 0 1 .5.5h1a1.5 1.5 0 0 0-1.5-1.5zm7-1a1.5 1.5 0 0 0-1.5 1.5h1a.5.5 0 0 1 .5-.5zm-3.5-2a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-3-.5a.5.5 0 0 1-.5.5v1a1.5 1.5 0 0 0 1.5-1.5zm5 0a1.5 1.5 0 0 0 1.5 1.5v-1a.5.5 0 0 1-.5-.5z");
}

</style>
