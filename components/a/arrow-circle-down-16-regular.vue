<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="df-3eh3ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-down-16-regular" /></template>
<style>
.df-3eh3ue {
  fill: currentColor;
  d: path("m5.146 8.854l2.5 2.5a.5.5 0 0 0 .708 0l2.5-2.5a.5.5 0 0 0-.708-.708L8.5 9.793V5a.5.5 0 0 0-1 0v4.793L5.854 8.146a.5.5 0 1 0-.708.708M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14M2 8a6 6 0 1 0 12 0A6 6 0 0 0 2 8");
}

</style>
