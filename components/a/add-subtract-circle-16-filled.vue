<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wqi86pgfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-subtract-circle-16-filled" /></template>
<style>
.wqi86pgfw {
  fill: currentColor;
  d: path("M9.5 10a.5.5 0 0 0 0 1H12a.5.5 0 0 0 0-1zM8 15A7 7 0 1 0 8 1a7 7 0 0 0 0 14m0-1a5.98 5.98 0 0 1-3.874-1.418l8.455-8.456A6 6 0 0 1 8 14M3.5 6a.5.5 0 0 1 .5-.5h1v-1a.5.5 0 0 1 1 0v1h1a.5.5 0 1 1 0 1H6v.8a.5.5 0 0 1-1 0v-.8H4a.5.5 0 0 1-.5-.5");
}

</style>
