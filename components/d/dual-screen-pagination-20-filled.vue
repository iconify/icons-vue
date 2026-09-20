<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pdkkr7b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-pagination-20-filled" /></template>
<style>
.pdkkr7b8d {
  fill: currentColor;
  d: path("M16 16h-5.5V4H16a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2M4 4h5.5v12H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2m8.5 10a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2.5-.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0m1.5.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

</style>
