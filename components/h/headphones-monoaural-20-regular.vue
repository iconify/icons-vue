<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qf13m2bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-monoaural-20-regular" /></template>
<style>
.qf13m2bfb {
  fill: currentColor;
  d: path("M10.002 2a8 8 0 0 1 8 8v1l-.002.02V16a2 2 0 0 1-2 2h-2.5a.5.5 0 0 1-.5-.5v-6a.5.5 0 0 1 .5-.5H17l.002-1A7 7 0 0 0 3.15 8.57a.53.53 0 0 1-.513.43a.477.477 0 0 1-.479-.563A8 8 0 0 1 10.002 2M14 17h2a1 1 0 0 0 1-1v-4h-3z");
}

</style>
