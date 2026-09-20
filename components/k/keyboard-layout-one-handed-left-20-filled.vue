<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wkkdjpi0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-layout-one-handed-left-20-filled" /></template>
<style>
.wkkdjpi0a {
  fill: currentColor;
  d: path("M3.5 4A1.5 1.5 0 0 0 2 5.5v8A1.5 1.5 0 0 0 3.5 15h13a1.5 1.5 0 0 0 1.5-1.5v-8A1.5 1.5 0 0 0 16.5 4zm2 8h3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1m0-4.75a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0M7.75 8a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5M6 9.75a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2.25.75a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5");
}

</style>
