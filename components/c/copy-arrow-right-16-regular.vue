<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kb7lyuqmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-arrow-right-16-regular" /></template>
<style>
.kb7lyuqmg {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M5 6H3.5A1.5 1.5 0 0 0 2 7.5v5A1.5 1.5 0 0 0 3.5 14h3.102q.274.538.656 1H3.5A2.5 2.5 0 0 1 1 12.5v-5A2.5 2.5 0 0 1 3.5 5H5zm6.854 3.146a.5.5 0 1 0-.707.708L12.293 11H9.5a.5.5 0 0 0 0 1h2.793l-1.146 1.146a.5.5 0 1 0 .707.707l2.002-2.001a.5.5 0 0 0-.002-.706zM12.5 1A2.5 2.5 0 0 1 15 3.5v3.757a5.5 5.5 0 0 0-1-.656V3.5A1.5 1.5 0 0 0 12.5 2h-4A1.5 1.5 0 0 0 7 3.5v4.839a5.5 5.5 0 0 0-.696 1.356A2.5 2.5 0 0 1 6 8.5v-5A2.5 2.5 0 0 1 8.5 1z");
}

</style>
