<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnzyukykk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-up-to-line-fill" /></template>
<style>
.vnzyukykk {
  fill: currentColor;
  d: path("M6 6h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m11.293 11.707L12 12.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414l6-6a1 1 0 0 1 1.414 0l6 6a.999.999 0 1 1-1.414 1.414");
}

</style>
