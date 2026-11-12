<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5qf07t7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cassette-fill" /></template>
<style>
.h5qf07t7j {
  fill: currentColor;
  d: path("M5 4h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3h-1.857L15 15H9l-2.143 5H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3m.236 4.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M13 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
