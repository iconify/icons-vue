<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylz0ybbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-5-24-regular" /></template>
<style>
.ylz0ybbit {
  fill: currentColor;
  d: path("M3 17.75v1.5a.75.75 0 0 0 1.5 0v-1.5a.75.75 0 0 0-1.5 0");
}

</style>
