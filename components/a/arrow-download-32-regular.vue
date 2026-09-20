<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ounuqmiml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-download-32-regular" /></template>
<style>
.ounuqmiml {
  fill: currentColor;
  d: path("M17 4a1 1 0 1 0-2 0v16.586l-5.293-5.293a1 1 0 0 0-1.414 1.414l7 7a1 1 0 0 0 1.414 0l7-7a1 1 0 0 0-1.414-1.414L17 20.586zM7 27a1 1 0 1 0 0 2h18a1 1 0 1 0 0-2z");
}

</style>
