<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u-luj0_tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-cs-16-regular" /></template>
<style>
.u-luj0_tc {
  fill: currentColor;
  d: path("M3.5 5A1.5 1.5 0 0 0 2 6.5v3a1.5 1.5 0 0 0 3 0a.5.5 0 0 1 1 0a2.5 2.5 0 0 1-5 0v-3a2.5 2.5 0 1 1 5 0a.5.5 0 0 1-1 0A1.5 1.5 0 0 0 3.5 5m6-.5a.5.5 0 0 1 .5.5v1h2V5a.5.5 0 0 1 1 0v1h1.25a.5.5 0 0 1 0 1H13v2h1.25a.5.5 0 0 1 0 1H13v1a.5.5 0 0 1-1 0v-1h-2v1a.5.5 0 0 1-1 0v-1H8a.5.5 0 0 1 0-1h1V7H8a.5.5 0 0 1 0-1h1V5a.5.5 0 0 1 .5-.5M10 7v2h2V7z");
}

</style>
