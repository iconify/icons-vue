<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rr_u0sbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:briefcase-add-32-filled" /></template>
<style>
.rr_u0sbqc {
  fill: currentColor;
  d: path("M19 3a3 3 0 0 1 3 3v2h3.5a4.5 4.5 0 0 1 4.5 4.5v11a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5v-11A4.5 4.5 0 0 1 6.5 8H10V6a3 3 0 0 1 3-3zm-3 10a1 1 0 0 0-1 1v3h-3a1 1 0 1 0 0 2h3v3a1 1 0 1 0 2 0v-3h3a1 1 0 1 0 0-2h-3v-3a1 1 0 0 0-1-1m-3-8a1 1 0 0 0-1 1v2h8V6a1 1 0 0 0-1-1z");
}

</style>
