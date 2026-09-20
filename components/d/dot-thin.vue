<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rh29abc-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dot-thin" /></template>
<style>
.rh29abc-m {
  fill: currentColor;
  d: path("M136 128a8 8 0 1 1-8-8a8 8 0 0 1 8 8");
}

</style>
