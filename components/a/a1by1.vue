<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dh1e0cciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:a1by1" /></template>
<style>
.dh1e0cciz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.496 40.331S38.607 32.791 43.5 24C38.607 15.208 27.496 7.668 27.496 7.668zM7.634 19.986H4.5v-8.828s7.313-3.49 12.993-3.49l-.01 32.664H7.634Z");
}

</style>
