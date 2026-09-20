<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tpl-ptwad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:ladder-simple-fill" /></template>
<style>
.tpl-ptwad {
  fill: currentColor;
  d: path("M192 24a8 8 0 0 0-8 8v8H72v-8a8 8 0 0 0-16 0v192a8 8 0 0 0 16 0v-8h112v8a8 8 0 0 0 16 0V32a8 8 0 0 0-8-8m-16 160H80a8 8 0 0 1 0-16h96a8 8 0 0 1 0 16m0-48H80a8 8 0 0 1 0-16h96a8 8 0 0 1 0 16m0-48H80a8 8 0 0 1 0-16h96a8 8 0 0 1 0 16");
}

</style>
