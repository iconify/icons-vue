<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bu9dgxuhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:letter-y" /></template>
<style>
.bu9dgxuhi {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M114.89 16.69a2.36 2.36 0 0 0-2.09-1.25H90.5c-.77 0-1.5.38-1.94 1.02L64 51.74L39.43 16.45a2.35 2.35 0 0 0-1.94-1.02h-22.3c-.87 0-1.67.48-2.08 1.25s-.36 1.71.12 2.43l36.58 54.56v44.58c0 1.29 1.05 2.33 2.34 2.33h23.71c1.29 0 2.34-1.04 2.34-2.33V73.68l36.57-54.56c.48-.72.53-1.66.12-2.43");
}

</style>
