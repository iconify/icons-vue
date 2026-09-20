<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xfuj1lm2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-20-regular" /></template>
<style>
.xfuj1lm2m {
  fill: currentColor;
  d: path("M15.5 4a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-1 0V5.707L5.707 15H10.5a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5v-6a.5.5 0 0 1 1 0v4.793L14.293 5H9.5a.5.5 0 0 1 0-1z");
}

</style>
