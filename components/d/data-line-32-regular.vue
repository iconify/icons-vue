<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k6zz6vgdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-line-32-regular" /></template>
<style>
.k6zz6vgdo {
  fill: currentColor;
  d: path("M21 9a4 4 0 1 1 3.08 3.894l-2.372 3.162a4 4 0 1 1-6.066 5.118l-4.651 1.55Q11 22.86 11 23a4 4 0 1 1-.642-2.174l4.651-1.55a4 4 0 0 1 4.91-4.17l2.373-3.162A4 4 0 0 1 21 9m4-2a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-8 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M5 23a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
