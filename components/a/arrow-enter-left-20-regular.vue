<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="llnybvzoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-enter-left-20-regular" /></template>
<style>
.llnybvzoy {
  fill: currentColor;
  d: path("m3.76 12l3.333 3.136a.5.5 0 0 1-.686.728l-4.25-4a.5.5 0 0 1 0-.728l4.25-4a.5.5 0 1 1 .686.728L3.76 11H15a2 2 0 0 0 2-2V4.5a.5.5 0 0 1 1 0V9a3 3 0 0 1-3 3z");
}

</style>
