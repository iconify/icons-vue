<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ppf2z0bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:app-recent-20-filled" /></template>
<style>
.ppf2z0bsr {
  fill: currentColor;
  d: path("M7 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zM2 6a2 2 0 0 1 2-2v12a2 2 0 0 1-2-2zm14 10V4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2");
}

</style>
