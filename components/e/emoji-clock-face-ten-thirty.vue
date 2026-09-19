<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dv0-c-mex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-clock-face-ten-thirty" /></template>
<style>
.dv0-c-mex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.04 24.068v15.886m-.061-15.916l-8.905-5.14M2.5 24c-.004 11.87 9.62 21.496 21.493 21.5c11.875.004 21.503-9.616 21.507-21.487V24c.004-11.87-9.62-21.496-21.493-21.5C12.132 2.496 2.504 12.116 2.5 23.987z");
}

</style>
