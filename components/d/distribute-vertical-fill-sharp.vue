<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi3o2g18e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-fill-sharp" /></template>
<style>
.hi3o2g18e {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2ZM5 9a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm16 10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
