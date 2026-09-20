<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hjjba9bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-funnel-20-filled" /></template>
<style>
.hjjba9bfz {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2-2h12a2 2 0 1 1 0 4H4a2 2 0 0 1-2-2m2 6a2 2 0 0 1 2-2h8a2 2 0 1 1 0 4H6a2 2 0 0 1-2-2m4 4a2 2 0 1 0 0 4h4a2 2 0 1 0 0-4z");
}

</style>
