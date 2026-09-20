<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uy7b4yp5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-32-filled" /></template>
<style>
.uy7b4yp5z {
  fill: currentColor;
  d: path("M12 2a2 2 0 0 0-1.897 1.368l-4 12A2 2 0 0 0 8 18h2.415l-2.288 8.825c-.67 2.587 2.64 4.28 4.345 2.222L25.54 13.276A2 2 0 0 0 24 10h-3.114l1.987-5.298A2 2 0 0 0 21 2z");
}

</style>
