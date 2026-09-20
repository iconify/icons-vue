<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zlvlm1bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hand-eye-fill" /></template>
<style>
.zlvlm1bci {
  fill: currentColor;
  d: path("M144 180a16 16 0 1 1-16-16a16 16 0 0 1 16 16m72-76v48a88 88 0 0 1-176 0V64a16 16 0 0 1 32 0v56a8 8 0 0 0 16 0V32a16 16 0 0 1 32 0v80a8 8 0 0 0 16 0V48a16 16 0 0 1 32 0v80a8 8 0 0 0 16 0v-24a16 16 0 0 1 32 0m-36.42 74.21c-.7-1.4-17.5-34.21-51.58-34.21s-50.88 32.81-51.58 34.21a4 4 0 0 0 0 3.58c.7 1.4 17.5 34.21 51.58 34.21s50.88-32.81 51.58-34.21a4 4 0 0 0 0-3.58");
}

</style>
