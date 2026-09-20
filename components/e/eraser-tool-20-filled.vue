<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xq-ma4m_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:eraser-tool-20-filled" /></template>
<style>
.xq-ma4m_x {
  fill: currentColor;
  d: path("M4 2.5a.5.5 0 0 0-1 0v12A3.5 3.5 0 0 0 6.5 18h7a3.5 3.5 0 0 0 3.5-3.5v-12a.5.5 0 0 0-1 0V6H4zM4 10V7h12v3z");
}

</style>
