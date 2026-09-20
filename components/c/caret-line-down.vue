<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o6skdbbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-line-down" /></template>
<style>
.o6skdbbrk {
  fill: currentColor;
  d: path("M42.34 77.66a8 8 0 0 1 11.32-11.32L128 140.69l74.34-74.35a8 8 0 0 1 11.32 11.32l-80 80a8 8 0 0 1-11.32 0ZM208 184H48a8 8 0 0 0 0 16h160a8 8 0 0 0 0-16");
}

</style>
