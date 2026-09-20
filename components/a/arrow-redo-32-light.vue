<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jd4r3r-7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-redo-32-light" /></template>
<style>
.jd4r3r-7k {
  fill: currentColor;
  d: path("M25.995 3.5a.5.5 0 0 1 1 0v12a.5.5 0 0 1-.5.5h-12a.5.5 0 0 1 0-1h10.793l-9.07-9.07a6.571 6.571 0 1 0-9.293 9.292l12.924 12.925a.5.5 0 0 1-.707.707L6.218 15.93A7.571 7.571 0 0 1 16.925 5.222l9.07 9.07z");
}

</style>
