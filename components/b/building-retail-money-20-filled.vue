<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j5tbp3bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-retail-money-20-filled" /></template>
<style>
.j5tbp3bfy {
  fill: currentColor;
  d: path("M6 10V8h8v2zm11-4.085A1.5 1.5 0 0 0 16.5 3h-13A1.5 1.5 0 0 0 3 5.915V16.5a.5.5 0 0 0 .5.5H5v-4.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 .456.294A2 2 0 0 1 11 12h6zM3.5 4h13a.5.5 0 0 1 0 1h-13a.5.5 0 0 1 0-1M5 7.5a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5zM9 13v4H6v-4zm8.5 0a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5v-3a1.5 1.5 0 0 1 1.5-1.5zm0 5a.5.5 0 0 1 .5-.5v-1a1.5 1.5 0 0 0-1.5 1.5zm.5-3.5a.5.5 0 0 1-.5-.5h-1a1.5 1.5 0 0 0 1.5 1.5zm-6.5-.5a.5.5 0 0 1-.5.5v1a1.5 1.5 0 0 0 1.5-1.5zm-.5 3.5a.5.5 0 0 1 .5.5h1a1.5 1.5 0 0 0-1.5-1.5zm3.5-3a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
