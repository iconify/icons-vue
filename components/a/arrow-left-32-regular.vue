<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b9x2sn8gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-left-32-regular" /></template>
<style>
.b9x2sn8gp {
  fill: currentColor;
  d: path("M29 16a1 1 0 0 1-1 1H6.414l8.293 8.293a1 1 0 0 1-1.414 1.414l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 1 1 1.414 1.414L6.414 15H28a1 1 0 0 1 1 1");
}

</style>
