<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cbow5ok7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-right-up" /></template>
<style>
.cbow5ok7a {
  fill: currentColor;
  d: path("M221.66 101.66a8 8 0 0 1-11.32 0L176 67.31V192a8 8 0 0 1-8 8H24a8 8 0 0 1 0-16h136V67.31l-34.34 34.35a8 8 0 0 1-11.32-11.32l48-48a8 8 0 0 1 11.32 0l48 48a8 8 0 0 1 0 11.32");
}

</style>
