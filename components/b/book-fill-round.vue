<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxr7riqlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-fill-round" /></template>
<style>
.zxr7riqlp {
  fill: currentColor;
  d: path("M4 19V7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v8a3.01 3.01 0 0 1-2.072 2.854A5.01 5.01 0 0 1 13 22H7a3 3 0 0 1-3-3m3-1a1 1 0 0 0 0 2h6a3 3 0 0 0 2.83-2Z");
}

</style>
