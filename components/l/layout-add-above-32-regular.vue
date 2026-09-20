<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ex75zsm6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-above-32-regular" /></template>
<style>
.ex75zsm6f {
  fill: currentColor;
  d: path("M28 11a1 1 0 0 1 1 1v12.5a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5V12a1 1 0 0 1 1-1zM5 24.5A2.5 2.5 0 0 0 7.5 27h17a2.5 2.5 0 0 0 2.5-2.5V13H5zM28 3a1 1 0 1 1 0 2H4a1 1 0 0 1 0-2z");
}

</style>
