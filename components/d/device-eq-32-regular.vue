<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w1lsa3cks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-eq-32-regular" /></template>
<style>
.w1lsa3cks {
  fill: currentColor;
  d: path("M16 2a1 1 0 0 1 1 1v26a1 1 0 1 1-2 0V3a1 1 0 0 1 1-1m-6 5a1 1 0 0 1 1 1v16a1 1 0 1 1-2 0V8a1 1 0 0 1 1-1m12 0a1 1 0 0 1 1 1v16a1 1 0 1 1-2 0V8a1 1 0 0 1 1-1M4 12a1 1 0 0 1 1 1v6a1 1 0 1 1-2 0v-6a1 1 0 0 1 1-1m24 0a1 1 0 0 1 1 1v6a1 1 0 1 1-2 0v-6a1 1 0 0 1 1-1");
}

</style>
