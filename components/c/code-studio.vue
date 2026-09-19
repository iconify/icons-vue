<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g9gtfac6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:code-studio" /></template>
<style>
.g9gtfac6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.205 8.609a4.853 4.853 0 0 0-4.853 4.852v5.687A4.853 4.853 0 0 1 5.5 24a4.853 4.853 0 0 1 4.852 4.853v5.686a4.853 4.853 0 0 0 4.853 4.853m17.59-30.783a4.853 4.853 0 0 1 4.853 4.852v5.687A4.853 4.853 0 0 0 42.5 24a4.853 4.853 0 0 0-4.852 4.853v5.686a4.853 4.853 0 0 1-4.853 4.853");
}

</style>
