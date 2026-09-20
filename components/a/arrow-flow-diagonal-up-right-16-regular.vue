<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="io0ekxt-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-diagonal-up-right-16-regular" /></template>
<style>
.io0ekxt-e {
  fill: currentColor;
  d: path("M8.5 3a.5.5 0 0 0 0 1h2.793L5.879 9.414a2.5 2.5 0 1 0 .707.707L12 4.707V7.5a.5.5 0 0 0 1 0v-4a.5.5 0 0 0-.5-.5zM3 11.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0");
}

</style>
