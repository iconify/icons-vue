<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kjve07b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-person-20-filled" /></template>
<style>
.kjve07b3l {
  fill: currentColor;
  d: path("M17.5 14a1.5 1.5 0 0 1 1.5 1.5c0 1.245-1 2.5-3.5 2.5S12 16.75 12 15.5a1.5 1.5 0 0 1 1.5-1.5zm-6.45 1a2.5 2.5 0 0 0-.05.5q0 .25.038.5H2.5a.5.5 0 0 1 0-1zM15 5a2 2 0 0 1 2 2v1.404a3 3 0 0 0-3.727 4.606c-.724.065-1.36.44-1.773.99H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2zm.5 4a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
