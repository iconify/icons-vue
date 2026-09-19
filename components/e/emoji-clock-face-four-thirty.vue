<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e4qn0lbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-clock-face-four-thirty" /></template>
<style>
.e4qn0lbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.04 24.068v15.886m9.4-10.544l-9.348-5.395M2.5 24c-.004 11.87 9.619 21.496 21.493 21.5S45.496 35.884 45.5 24.014V24c.004-11.87-9.619-21.496-21.493-21.5S2.504 12.116 2.5 23.986z");
}

</style>
