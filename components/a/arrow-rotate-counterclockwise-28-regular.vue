<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="st_ef_bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-28-regular" /></template>
<style>
.st_ef_bep {
  fill: currentColor;
  d: path("M14 3c6.075 0 11 4.925 11 11a.75.75 0 0 1-1.5 0a9.5 9.5 0 0 0-19 0a9.49 9.49 0 0 0 5 8.363V19.75a.75.75 0 0 1 1.5 0v4.5a.75.75 0 0 1-.75.75h-4.5a.75.75 0 0 1 0-1.5h2.71A10.99 10.99 0 0 1 3 14C3 7.925 7.925 3 14 3m0 7.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7m0 1.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
