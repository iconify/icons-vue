<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xa669ib2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-expand-16-regular" /></template>
<style>
.xa669ib2m {
  fill: currentColor;
  d: path("M2 2.5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H3.707l2.647 2.646a.5.5 0 0 1-.708.708L3 3.707V5.5a.5.5 0 0 1-1 0zM13.5 2a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-1 0V3.707l-2.646 2.647a.5.5 0 0 1-.708-.708L12.293 3H10.5a.5.5 0 0 1 0-1zm0 12a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-1 0v1.793l-2.646-2.647a.5.5 0 1 0-.708.708L12.293 13H10.5a.5.5 0 0 0 0 1zm-11 0a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 1 0v1.793l2.646-2.647a.5.5 0 0 1 .708.707L3.707 13H5.5a.5.5 0 0 1 0 1z");
}

</style>
