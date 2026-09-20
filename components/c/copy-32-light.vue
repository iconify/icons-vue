<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vg0ovubpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-32-light" /></template>
<style>
.vg0ovubpq {
  fill: currentColor;
  d: path("M10.5 9h-3A3.5 3.5 0 0 0 4 12.5v12A3.5 3.5 0 0 0 7.5 28h8a3.5 3.5 0 0 0 3.355-2.5h1.032A4.5 4.5 0 0 1 15.5 29h-8A4.5 4.5 0 0 1 3 24.5v-12A4.5 4.5 0 0 1 7.5 8h3zm14-6A4.5 4.5 0 0 1 29 7.5v12a4.5 4.5 0 0 1-4.5 4.5h-8a4.5 4.5 0 0 1-4.5-4.5v-12A4.5 4.5 0 0 1 16.5 3zm-8 1A3.5 3.5 0 0 0 13 7.5v12a3.5 3.5 0 0 0 3.5 3.5h8a3.5 3.5 0 0 0 3.5-3.5v-12A3.5 3.5 0 0 0 24.5 4z");
}

</style>
