<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dvqzphuod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-20-regular" /></template>
<style>
.dvqzphuod {
  fill: currentColor;
  d: path("M17.5 15a1.5 1.5 0 0 1 1.5 1.5c0 1.245-1 2.5-3.5 2.5S12 17.75 12 16.5a1.5 1.5 0 0 1 1.5-1.5zM9.743 2.071a.5.5 0 0 1 .514 0l7 4.2a.85.85 0 0 1 0 1.458l-7 4.2a.52.52 0 0 1-.514 0L3 7.883V14.5A1.5 1.5 0 0 0 4.5 16h6.55a2.5 2.5 0 0 0-.05.5q0 .25.038.5H4.5A2.5 2.5 0 0 1 2 14.5V7.849a2 2 0 0 1 .97-1.715zM15.5 10a2 2 0 1 1 0 4a2 2 0 0 1 0-4M3.485 6.991L3.472 7L10 10.917L16.527 7L10 3.083z");
}

</style>
