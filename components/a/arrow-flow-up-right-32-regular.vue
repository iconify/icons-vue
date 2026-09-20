<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ldndmkxms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-up-right-32-regular" /></template>
<style>
.ldndmkxms {
  fill: currentColor;
  d: path("M23.207 2.293a1 1 0 1 0-1.414 1.414L26.586 8.5H19a4 4 0 0 0-4 4v7a2 2 0 0 1-2 2h-.09A5.502 5.502 0 0 0 2 22.5a5.5 5.5 0 0 0 10.91 1H13a4 4 0 0 0 4-4v-7a2 2 0 0 1 2-2h7.586l-4.793 4.793a1 1 0 0 0 1.414 1.414l6.5-6.5a1 1 0 0 0 0-1.414zM11 22.5a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0");
}

</style>
