<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p3dv1tbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-20-regular" /></template>
<style>
.p3dv1tbog {
  fill: currentColor;
  d: path("M11.5 16a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5v-8a.5.5 0 0 1 1 0v6.793L16.147 3.146a.5.5 0 1 1 .707.708L4.707 16z");
}

</style>
