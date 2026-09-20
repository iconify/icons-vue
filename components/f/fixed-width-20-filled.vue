<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="thqc8qa_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:fixed-width-20-filled" /></template>
<style>
.thqc8qa_u {
  fill: currentColor;
  d: path("M3.5 3a.5.5 0 0 1 .5.5V5h5.5V3.5a.5.5 0 0 1 1 0V5H16V3.5a.5.5 0 0 1 1 0v4a.5.5 0 0 1-1 0V6h-5.5v1.5a.5.5 0 0 1-1 0V6H4v1.5a.5.5 0 0 1-1 0v-4a.5.5 0 0 1 .5-.5m6 6H5a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4.5zm1 8H15a2 2 0 0 0 2-2v-4a2 2 0 0 0-2-2h-4.5z");
}

</style>
