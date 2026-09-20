<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk5j05b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-line-spacing-outline" /></template>
<style>
.pk5j05b9f {
  fill: currentColor;
  d: path("M6.308 19L3 15.692l.708-.707l2.1 2.088V6.927l-2.1 2.089L3 8.308L6.308 5l3.308 3.308l-.708.708l-2.1-2.089v10.146l2.1-2.089l.708.708zm6.077-1v-1H21v1.23zm0-5.5v-1H21v1zm0-5.5V6L21 5.77V7z");
}

</style>
