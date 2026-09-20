<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kilu6tbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-cube-28-regular" /></template>
<style>
.kilu6tbik {
  fill: currentColor;
  d: path("M14 5.5a5.5 5.5 0 0 0-5.496 5.28a.75.75 0 0 1-.75.72H7.5a4 4 0 0 0 0 8H13V21H7.5a5.5 5.5 0 0 1-.431-10.983a7.001 7.001 0 0 1 13.862 0a5.5 5.5 0 0 1 5 4.606a3 3 0 0 0-.633-.409l-1.276-.612A4 4 0 0 0 20.5 11.5h-.255a.75.75 0 0 1-.75-.72A5.5 5.5 0 0 0 14 5.5m12 16.58v-5.16a2 2 0 0 0-1.135-1.804l-4-1.92a2 2 0 0 0-1.73 0l-4 1.92A2 2 0 0 0 14 16.919v5.161a2 2 0 0 0 1.135 1.804l4 1.92a2 2 0 0 0 1.73 0l4-1.92A2 2 0 0 0 26 22.08m-9.95-5.296a.5.5 0 0 1 .666-.235L20 18.125l3.284-1.576a.5.5 0 1 1 .432.902L20.5 18.994V23a.5.5 0 0 1-1 0v-4.006l-3.216-1.543a.5.5 0 0 1-.235-.667");
}

</style>
