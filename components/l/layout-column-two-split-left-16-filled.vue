<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wrzn2ab0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-two-split-left-16-filled" /></template>
<style>
.wrzn2ab0l {
  fill: currentColor;
  d: path("M11.5 14h-3V2h3A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5m-7-12h3v5.5H2v-3A2.5 2.5 0 0 1 4.5 2M2 8.5v3A2.5 2.5 0 0 0 4.5 14h3V8.5z");
}

</style>
