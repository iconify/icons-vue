<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r9bmizbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:games-16-regular" /></template>
<style>
.r9bmizbmp {
  fill: currentColor;
  d: path("M3.505 7.5a.5.5 0 0 1 .5-.5h1V6a.5.5 0 0 1 1 0v1h1a.5.5 0 0 1 0 1h-1v1a.5.5 0 1 1-1 0V8h-1a.5.5 0 0 1-.5-.5M11 9a1 1 0 1 1-2 0a1 1 0 0 1 2 0m0-2a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-9.999.5a4.5 4.5 0 0 1 4.5-4.5h5.008a4.5 4.5 0 1 1 0 9H5.501a4.5 4.5 0 0 1-4.5-4.5m4.5-3.5a3.5 3.5 0 1 0 0 7h5.008a3.5 3.5 0 1 0 0-7z");
}

</style>
