<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dc6c18b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-12-filled" /></template>
<style>
.dc6c18b4s {
  fill: currentColor;
  d: path("M4.585 1.085a2 2 0 0 1 2.83 0l3.5 3.5a2 2 0 0 1 0 2.827l-3.5 3.5c-.782.78-2.049.78-2.83 0l-3.5-3.5a2 2 0 0 1 0-2.828z");
}

</style>
