<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7vrh5bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-clock-face-four-oclock" /></template>
<style>
.n7vrh5bst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.04 8.113V24m9.4 5.41l-9.348-5.395M2.5 24c-.004 11.87 9.619 21.496 21.493 21.5S45.496 35.884 45.5 24.014V24c.004-11.87-9.619-21.496-21.493-21.5S2.504 12.116 2.5 23.986z");
}

</style>
