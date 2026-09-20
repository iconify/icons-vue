<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="sjfuoqofe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-down-28-regular" /></template>
<style>
.sjfuoqofe {
  fill: currentColor;
  d: path("M4.22 9.47a.75.75 0 0 1 1.06 0L14 18.19l8.72-8.72a.75.75 0 1 1 1.06 1.06l-9.25 9.25a.75.75 0 0 1-1.06 0l-9.25-9.25a.75.75 0 0 1 0-1.06");
}

</style>
