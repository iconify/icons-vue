<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vb533kbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-2-dashes-solid-20-regular" /></template>
<style>
.vb533kbcj {
  fill: currentColor;
  d: path("M2.5 6a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm6 0a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm6 0a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm-12 6a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
