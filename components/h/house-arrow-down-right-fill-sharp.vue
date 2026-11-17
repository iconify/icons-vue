<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr0-ok0ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-arrow-down-right-fill-sharp" /></template>
<style>
.wr0-ok0ob {
  fill: currentColor;
  d: path("M20.659 9.247c.217.19.341.465.341.753v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0Zm-12.366 2.46L12.586 16H11a1 1 0 0 0 0 2h4a.997.997 0 0 0 1-1v-4a1 1 0 0 0-2 0v1.586l-4.293-4.293a.999.999 0 1 0-1.414 1.414");
}

</style>
