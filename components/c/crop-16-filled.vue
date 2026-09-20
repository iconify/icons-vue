<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ltb1gvbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:crop-16-filled" /></template>
<style>
.ltb1gvbea {
  fill: currentColor;
  d: path("M5 1.75a.75.75 0 0 0-1.5 0V3.5H1.75a.75.75 0 0 0 0 1.5H3.5v4.5a3 3 0 0 0 3 3H11v1.75a.75.75 0 0 0 1.5 0V12.5h1.75a.75.75 0 0 0 0-1.5H6.5A1.5 1.5 0 0 1 5 9.5zm6 4.75V10h1.5V6.5a3 3 0 0 0-3-3H6V5h3.5A1.5 1.5 0 0 1 11 6.5");
}

</style>
