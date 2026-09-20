<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kthe4lgyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-up-left-thin" /></template>
<style>
.kthe4lgyz {
  fill: currentColor;
  d: path("M196 80v144a4 4 0 0 1-8 0V84H57.66l41.17 41.17a4 4 0 0 1-5.66 5.66l-48-48a4 4 0 0 1 0-5.66l48-48a4 4 0 0 1 5.66 5.66L57.66 76H192a4 4 0 0 1 4 4");
}

</style>
