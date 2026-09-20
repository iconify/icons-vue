<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bfhn30bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-above-32-filled" /></template>
<style>
.bfhn30bfc {
  fill: currentColor;
  d: path("M28 11a1 1 0 0 1 1 1v12.5a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5V12a1 1 0 0 1 1-1zm0-8a1 1 0 1 1 0 2H4a1 1 0 0 1 0-2z");
}

</style>
