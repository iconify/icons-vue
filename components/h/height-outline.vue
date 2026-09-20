<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-8o9rvqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:height-outline" /></template>
<style>
.l-8o9rvqz {
  fill: currentColor;
  d: path("m11.98 20l-3.288-3.288l.689-.689l2.1 2.056V5.902L9.4 7.977l-.688-.688L12 4l3.289 3.289l-.708.713l-2.1-2.08v12.157l2.1-2.056l.688.689z");
}

</style>
