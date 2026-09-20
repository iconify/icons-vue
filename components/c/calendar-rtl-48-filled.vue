<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aag0ipbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-rtl-48-filled" /></template>
<style>
.aag0ipbdm {
  fill: currentColor;
  d: path("M42 12.25A6.25 6.25 0 0 0 35.75 6h-23.5A6.25 6.25 0 0 0 6 12.25V14h36zm0 4.25v19.25A6.25 6.25 0 0 1 35.75 42h-23.5A6.25 6.25 0 0 1 6 35.75V16.5zm-12 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 0 0-5 0M24 26a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m-11-2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 0 0-5 0M32.5 34a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m-11-2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 0 0-5 0");
}

</style>
