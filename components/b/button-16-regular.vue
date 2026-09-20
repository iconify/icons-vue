<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gz1y-8bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:button-16-regular" /></template>
<style>
.gz1y-8bok {
  fill: currentColor;
  d: path("M1 5.5A2.5 2.5 0 0 1 3.5 3h9A2.5 2.5 0 0 1 15 5.5v4a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 9.5zM3.5 4A1.5 1.5 0 0 0 2 5.5v4A1.5 1.5 0 0 0 3.5 11h9A1.5 1.5 0 0 0 14 9.5v-4A1.5 1.5 0 0 0 12.5 4zM7 7.5a.5.5 0 0 1 .5-.5H12a.5.5 0 0 1 0 1H7.5a.5.5 0 0 1-.5-.5m-1 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
