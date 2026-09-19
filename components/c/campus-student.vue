<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w263nl2lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:campus-student" /></template>
<style>
.w263nl2lu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.874 13.323L24.86 4.5L11.78 21.166l24.44-.256L24.237 43.5L17.76 30.67");
}

</style>
