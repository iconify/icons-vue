<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2gscpqqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-alt-off-sharp" /></template>
<style>
.i2gscpqqp {
  fill: currentColor;
  d: path("M14.089 11.264L7.825 5H19.05zm5.744 9.99L13 14.42V19h-2v-6.579L2.746 4.167l.708-.713l17.092 17.092z");
}

</style>
