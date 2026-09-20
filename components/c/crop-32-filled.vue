<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tbywglhna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:crop-32-filled" /></template>
<style>
.tbywglhna {
  fill: currentColor;
  d: path("M9 3.25a1.25 1.25 0 1 0-2.5 0V6.5H3.25a1.25 1.25 0 1 0 0 2.5H6.5v11.5a5 5 0 0 0 5 5H23v3.25a1.25 1.25 0 1 0 2.5 0V25.5h3.25a1.25 1.25 0 1 0 0-2.5H11.5A2.5 2.5 0 0 1 9 20.5zm14 8.25v10h2.5v-10a5 5 0 0 0-5-5h-10V9h10a2.5 2.5 0 0 1 2.5 2.5");
}

</style>
