<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="alnintyhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-tag-20-filled" /></template>
<style>
.alnintyhh {
  fill: currentColor;
  d: path("M9.293 6.293A1 1 0 1 1 10 8H7a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V7.048a5 5 0 0 0-8.535-3.583a2 2 0 1 0 2.828 2.828M8 14h4a.5.5 0 0 1 0 1H8a.5.5 0 0 1 0-1");
}

</style>
