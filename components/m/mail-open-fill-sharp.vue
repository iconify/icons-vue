<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xykas6b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-fill-sharp" /></template>
<style>
.xykas6b-v {
  fill: currentColor;
  d: path("M20.873 7.713L14.586 14H9.414L3.127 7.713l8.318-5.545a1 1 0 0 1 1.11 0ZM22 9.414V21a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9.414l6.293 6.293A1 1 0 0 0 9 16h6c.265 0 .52-.105.707-.293Z");
}

</style>
