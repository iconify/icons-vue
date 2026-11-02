<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnpk1ibfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-fill-round" /></template>
<style>
.vnpk1ibfr {
  fill: currentColor;
  d: path("M8 3h8a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5");
}

</style>
