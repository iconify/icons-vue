<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c7g64ob4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-up-right-fill" /></template>
<style>
.c7g64ob4p {
  fill: currentColor;
  d: path("m221.66 85.66l-48 48A8 8 0 0 1 160 128V88H80v136a8 8 0 0 1-16 0V80a8 8 0 0 1 8-8h88V32a8 8 0 0 1 13.66-5.66l48 48a8 8 0 0 1 0 11.32");
}

</style>
