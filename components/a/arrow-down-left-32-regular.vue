<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pqbn7cb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-32-regular" /></template>
<style>
.pqbn7cb2i {
  fill: currentColor;
  d: path("M17.004 28.996a1 1 0 1 0 0-2H6.418L28.707 4.707a1 1 0 0 0-1.414-1.414L5.003 25.582V14.996a1 1 0 1 0-2 0v13a1 1 0 0 0 1 1z");
}

</style>
