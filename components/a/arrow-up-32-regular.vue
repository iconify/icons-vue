<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q1t6bsb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-32-regular" /></template>
<style>
.q1t6bsb1s {
  fill: currentColor;
  d: path("M16 29a1 1 0 0 1-1-1V6.414l-8.293 8.293a1 1 0 0 1-1.414-1.414l10-10a1 1 0 0 1 1.414 0l10 10a1 1 0 0 1-1.414 1.414L17 6.414V28a1 1 0 0 1-1 1");
}

</style>
