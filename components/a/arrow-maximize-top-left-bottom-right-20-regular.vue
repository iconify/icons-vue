<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tzdca0fvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-top-left-bottom-right-20-regular" /></template>
<style>
.tzdca0fvs {
  fill: currentColor;
  d: path("M10.5 4a.5.5 0 0 1 0 1H5.707L15 14.293V9.5a.5.5 0 0 1 1 0v6a.5.5 0 0 1-.5.5h-6a.5.5 0 0 1 0-1h4.793L5 5.707V10.5a.5.5 0 0 1-1 0v-6a.5.5 0 0 1 .5-.5z");
}

</style>
