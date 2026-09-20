<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cc4q3ybjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-up-32-filled" /></template>
<style>
.cc4q3ybjy {
  fill: currentColor;
  d: path("M25.75 27.5a1.25 1.25 0 1 1 0 2.5h-20a1.25 1.25 0 0 1 0-2.5zM14.866 2.366a1.25 1.25 0 0 1 1.768 0l7.5 7.5a1.25 1.25 0 0 1-1.768 1.768L17 6.268V23.75a1.25 1.25 0 0 1-2.5 0V6.268l-5.366 5.366a1.25 1.25 0 1 1-1.768-1.768z");
}

</style>
