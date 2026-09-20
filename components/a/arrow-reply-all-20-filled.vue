<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bm_fkhbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-all-20-filled" /></template>
<style>
.bm_fkhbnm {
  fill: currentColor;
  d: path("M7.78 4.78a.75.75 0 0 0-1.06-1.06l-4.5 4.5a.75.75 0 0 0 0 1.06l4.5 4.5a.75.75 0 0 0 1.06-1.06L3.81 8.75zm3.5 0a.75.75 0 0 0-1.06-1.06l-4.5 4.5a.75.75 0 0 0 0 1.06l4.5 4.5a.75.75 0 1 0 1.06-1.06L8.06 9.5h2.69a5.75 5.75 0 0 1 5.75 5.75a.75.75 0 0 0 1.5 0A7.25 7.25 0 0 0 10.75 8H8.06z");
}

</style>
