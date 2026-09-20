<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fpxjt2gmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-line-down-bold" /></template>
<style>
.fpxjt2gmy {
  fill: currentColor;
  d: path("M39.51 80.49a12 12 0 0 1 17-17L128 135l71.51-71.52a12 12 0 0 1 17 17l-80 80a12 12 0 0 1-17 0ZM208 180H48a12 12 0 0 0 0 24h160a12 12 0 0 0 0-24");
}

</style>
