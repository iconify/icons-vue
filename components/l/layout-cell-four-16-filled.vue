<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="imdububqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-cell-four-16-filled" /></template>
<style>
.imdububqm {
  fill: currentColor;
  d: path("M11.5 14h-3V8.5H14v3a2.5 2.5 0 0 1-2.5 2.5M14 7.5H8.5V2h3A2.5 2.5 0 0 1 14 4.5zm-6.5 0V2h-3A2.5 2.5 0 0 0 2 4.5v3zM2 8.5v3A2.5 2.5 0 0 0 4.5 14h3V8.5z");
}

</style>
