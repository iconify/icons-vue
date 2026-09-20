<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="q1wtcabjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-record-28-filled" /></template>
<style>
.q1wtcabjb {
  fill: currentColor;
  d: path("M25 9.5v5A7.5 7.5 0 0 0 14.5 25H6.25A3.25 3.25 0 0 1 3 21.75V9.5zM21.75 3A3.25 3.25 0 0 1 25 6.25V8H3V6.25A3.25 3.25 0 0 1 6.25 3zM20.5 15.5a5 5 0 1 1 0 10a5 5 0 0 1 0-10m0 11.5a6.5 6.5 0 1 0 0-13a6.5 6.5 0 0 0 0 13m3.5-6.5a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0");
}

</style>
