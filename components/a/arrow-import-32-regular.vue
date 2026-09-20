<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i56g8nb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-import-32-regular" /></template>
<style>
.i56g8nb0b {
  fill: currentColor;
  d: path("M29 5a1 1 0 0 1 1 1v20a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1M15.793 7.793a1 1 0 0 1 1.414 0l7.5 7.5a1 1 0 0 1 0 1.414l-7.5 7.5a1 1 0 1 1-1.414-1.414L21.586 17H3a1 1 0 1 1 0-2h18.586l-5.793-5.793a1 1 0 0 1 0-1.414");
}

</style>
