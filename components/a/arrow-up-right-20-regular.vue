<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5iiw1g6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-20-regular" /></template>
<style>
.r5iiw1g6x {
  fill: currentColor;
  d: path("M8.5 4a.5.5 0 1 1 0-1h8a.5.5 0 0 1 .5.5v8a.5.5 0 0 1-1 0V4.707L3.854 16.854a.5.5 0 0 1-.708-.708L15.293 4z");
}

</style>
