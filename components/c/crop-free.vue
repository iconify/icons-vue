<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3308_fmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:crop-free" /></template>
<style>
.x3308_fmz {
  fill: currentColor;
  d: path("M3 5v4h2V5h4V3H5c-1.1 0-2 .9-2 2m2 10H3v4c0 1.1.9 2 2 2h4v-2H5zm14 4h-4v2h4c1.1 0 2-.9 2-2v-4h-2zm0-16h-4v2h4v4h2V5c0-1.1-.9-2-2-2");
}

</style>
