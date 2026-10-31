<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="fgaa-1dri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-accent-28-regular" /></template>
<style>
.fgaa-1dri {
  fill: currentColor;
  d: path("M22.251 18.5a2.25 2.25 0 0 1 2.25 2.25v1.5a2.25 2.25 0 0 1-2.25 2.25H5.754a2.25 2.25 0 0 1-2.25-2.25v-1.5a2.25 2.25 0 0 1 1.538-2.134c.07.325.229.63.47.871a1.75 1.75 0 0 0 1.626.47l4.938-1.123q.475-.11.902-.334z");
}

</style>
