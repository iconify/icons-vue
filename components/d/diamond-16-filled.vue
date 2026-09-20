<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kjlpoacyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-16-filled" /></template>
<style>
.kjlpoacyy {
  fill: currentColor;
  d: path("M6.232 1.233a2.5 2.5 0 0 1 3.535 0l5 4.999a2.5 2.5 0 0 1 0 3.535l-5 5a2.5 2.5 0 0 1-3.535 0l-5-5a2.5 2.5 0 0 1 0-3.535z");
}

</style>
