<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c8lju3c4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chalkboard-simple" /></template>
<style>
.c8lju3c4e {
  fill: currentColor;
  d: path("M240 192h-8v-24a8 8 0 0 0-8-8h-64a8 8 0 0 0-8 8v24H40V56h176v80a8 8 0 0 0 16 0V56a16 16 0 0 0-16-16H40a16 16 0 0 0-16 16v136h-8a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16m-72-16h48v16h-48Z");
}

</style>
