<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmhupcbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-off-fill" /></template>
<style>
.tmhupcbkn {
  fill: currentColor;
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414l-2.682-2.682c-.707.787-1.982.698-2.9.41a4.9 4.9 0 0 1-1.266-.603L12 17.202l-2.445 1.63a4.9 4.9 0 0 1-1.266.603c-.991.31-2.44.38-3.064-.629A1.54 1.54 0 0 1 5 18V6q0-.271.048-.538L2.293 2.707a.999.999 0 1 1 1.414-1.414M19 13.757L8.243 3H16a3 3 0 0 1 3 3Z");
}

</style>
