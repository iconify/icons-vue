<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="am2qp0owq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:alarm-thin" /></template>
<style>
.am2qp0owq {
  fill: currentColor;
  d: path("M128 44a92 92 0 1 0 92 92a92.1 92.1 0 0 0-92-92m0 176a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84M58.83 34.83l-32 32a4 4 0 0 1-5.66-5.66l32-32a4 4 0 0 1 5.66 5.66m176 32a4 4 0 0 1-5.66 0l-32-32a4 4 0 0 1 5.66-5.66l32 32a4 4 0 0 1 0 5.66M188 136a4 4 0 0 1-4 4h-56a4 4 0 0 1-4-4V80a4 4 0 0 1 8 0v52h52a4 4 0 0 1 4 4");
}

</style>
