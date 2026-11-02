<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwi01ccmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backspace-fill" /></template>
<style>
.cwi01ccmh {
  fill: currentColor;
  d: path("M9 5h10a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H9a1 1 0 0 1-.707-.293l-5-5a2.414 2.414 0 0 1 0-3.414l5-5A1 1 0 0 1 9 5m4.707 4.293a.999.999 0 1 0-1.414 1.414L13.586 12l-1.293 1.293a.999.999 0 1 0 1.414 1.414L15 13.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L16.414 12l1.293-1.293a.999.999 0 1 0-1.414-1.414L15 10.586Z");
}

</style>
