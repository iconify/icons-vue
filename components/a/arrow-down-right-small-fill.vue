<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp9z4c-9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-right-small-fill" /></template>
<style>
.dp9z4c-9n {
  fill: currentColor;
  d: path("M16 17h-6a1 1 0 0 1 0-2h3.586L7.293 8.707a.999.999 0 1 1 1.414-1.414L15 13.586V10a1 1 0 0 1 2 0v6a.997.997 0 0 1-1 1");
}

</style>
