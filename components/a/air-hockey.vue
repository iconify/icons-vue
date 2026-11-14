<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4emuxb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:air-hockey" /></template>
<style>
.c4emuxb8i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 9.5q0-3.003 2.123-5.127T14.5 2.25t5.127 2.123T21.75 9.5t-2.123 5.127Q17.503 16.75 14.5 16.75t-5.127-2.123T7.25 9.5m4 0q0-3.25 3.25-3.25t3.25 3.25t-3.25 3.25t-3.25-3.25M5.5 14.25q-3.75 0-3.75 3.75t3.75 3.75T9.25 18T5.5 14.25");
}

</style>
