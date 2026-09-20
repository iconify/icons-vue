<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="so_khjbtd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:block-16-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.so_khjbtd {
  d: path("M8 2a6 6 0 1 1 0 12A6 6 0 0 1 8 2zm0 1a5 5 0 1 0 0 10A5 5 0 0 0 8 3zM5.5 7.5h5.002a.5.5 0 0 1 .09.992l-.09.008H5.5a.5.5 0 0 1-.09-.992L5.5 7.5h5.002H5.5z");
  fill: currentColor;
}

</style>
