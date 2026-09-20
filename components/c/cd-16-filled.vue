<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bi741aczb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cd-16-filled" /></template>
<style>
.bi741aczb {
  fill: currentColor;
  d: path("M8 6a2 2 0 1 1 .001 3.999A2 2 0 0 1 8 6m0 3a1 1 0 1 1 0-2a1 1 0 0 1 0 2m0-7a6 6 0 1 0 0 12A6 6 0 0 0 8 2");
}

</style>
