<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntsy0acvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-fill-sharp" /></template>
<style>
.ntsy0acvo {
  fill: currentColor;
  d: path("M17 4c.265 0 .52.105.707.293l4 4a1 1 0 0 1 .036 1.376l-9 10a1 1 0 0 1-1.486 0l-9-10a1 1 0 0 1 .036-1.376l4-4A1 1 0 0 1 7 4ZM8.707 8.293a.999.999 0 1 0-1.414 1.414l2 2a.999.999 0 1 0 1.414-1.414Z");
}

</style>
