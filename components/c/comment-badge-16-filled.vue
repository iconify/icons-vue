<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jfuub_krs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-badge-16-filled" /></template>
<style>
.jfuub_krs {
  fill: currentColor;
  d: path("M14 5a2 2 0 1 0 0-4a2 2 0 0 0 0 4M3.5 2h7.67A3 3 0 0 0 15 5.83V9.5a2.5 2.5 0 0 1-2.5 2.5H8.688l-3.063 2.68A.98.98 0 0 1 4 13.942V12h-.5A2.5 2.5 0 0 1 1 9.5v-5A2.5 2.5 0 0 1 3.5 2");
}

</style>
