<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yroeg1bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apotheek" /></template>
<style>
.yroeg1bkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.626 10.432a8.697 8.697 0 1 0 0 17.395zm2.504 29.709c6.043 0 10.942-4.899 10.942-10.942S30.173 18.257 24.13 18.257zm0-25.699a5.471 5.471 0 1 0 0-10.942zm-2.504 18.274a5.892 5.892 0 0 0 0 11.784z");
}

</style>
