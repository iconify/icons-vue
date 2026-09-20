<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nswqt2b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-right-16-filled" /></template>
<style>
.nswqt2b1k {
  fill: currentColor;
  d: path("M8.293 8.5H1.5a.5.5 0 0 1 0-1h6.793L6.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708zM15 8a2 2 0 1 0-4 0a2 2 0 0 0 4 0");
}

</style>
