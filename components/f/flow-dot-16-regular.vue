<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yur2i38-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-dot-16-regular" /></template>
<style>
.yur2i38-b {
  fill: currentColor;
  d: path("M3.5 2a1.5 1.5 0 0 1 1.413 1H11.5a2.5 2.5 0 0 1 0 5h-7a1.5 1.5 0 1 0 0 3h6.587a1.5 1.5 0 1 1 0 1H4.5a2.5 2.5 0 0 1 0-5h7a1.5 1.5 0 0 0 0-3H4.913A1.5 1.5 0 1 1 3.5 2");
}

</style>
