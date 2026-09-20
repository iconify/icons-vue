<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="elar9pbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:git-pull-request-fill" /></template>
<style>
.elar9pbtu {
  fill: currentColor;
  d: path("M104 64a32 32 0 1 0-40 31v66a32 32 0 1 0 16 0V95a32.06 32.06 0 0 0 24-31M88 192a16 16 0 1 1-16-16a16 16 0 0 1 16 16m144 0a32 32 0 1 1-40-31v-50.37a8 8 0 0 0-2.34-5.66L152 67.31V96a8 8 0 0 1-16 0V48a8 8 0 0 1 8-8h48a8 8 0 0 1 0 16h-28.69L201 93.66a23.85 23.85 0 0 1 7 17V161a32.06 32.06 0 0 1 24 31");
}

</style>
