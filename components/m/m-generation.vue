<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rfffqtboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:m-generation" /></template>
<style>
.rfffqtboj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.28L14.258 5.5h-2.673v37H7.023m33.954 0h-4.562v-37h-2.673L24 15.28V42.5");
}

</style>
