<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l7ib7yjcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dashboard-20-regular" /></template>
<style>
.l7ib7yjcf {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zM4 14a2 2 0 0 0 2 2h1v-3H4zm4 2h6a2 2 0 0 0 2-2v-1H8zM6 4a2 2 0 0 0-2 2v6h8V4zm7 8h3V8h-3zm0-5h3V6a2 2 0 0 0-2-2h-1z");
}

</style>
