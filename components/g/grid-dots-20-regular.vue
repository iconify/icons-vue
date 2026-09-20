<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tzot29bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:grid-dots-20-regular" /></template>
<style>
.tzot29bax {
  fill: currentColor;
  d: path("M4.25 14.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m5.75 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m5.75 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5M4.25 8.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m5.75 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m5.75 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5M4.25 3a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5M10 3a1.25 1.25 0 1 1 0 2.5A1.25 1.25 0 0 1 10 3m5.75 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
