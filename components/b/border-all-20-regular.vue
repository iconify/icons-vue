<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dsc_9nogs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-all-20-regular" /></template>
<style>
.dsc_9nogs {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3-2a2 2 0 0 0-2 2v3.5h5.5V4zm4.5 0v5.5H16V6a2 2 0 0 0-2-2zm5.5 6.5h-5.5V16H14a2 2 0 0 0 2-2zM9.5 16v-5.5H4V14a2 2 0 0 0 2 2z");
}

</style>
