<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5eevv4ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-dot-24-regular" /></template>
<style>
.y5eevv4ak {
  fill: currentColor;
  d: path("M5.5 2.25A2.5 2.5 0 0 1 7.885 4h8.865l.219.006a4.25 4.25 0 0 1-.219 8.494h-9.5a2.75 2.75 0 1 0 0 5.5h8.865a2.5 2.5 0 1 1 0 1.5H7.25a4.25 4.25 0 0 1 0-8.5h9.5a2.75 2.75 0 0 0 .281-5.485L16.75 5.5H7.885A2.5 2.5 0 1 1 5.5 2.25");
}

</style>
