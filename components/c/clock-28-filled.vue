<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="dqudn3bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clock-28-filled" /></template>
<style>
.dqudn3bls {
  fill: currentColor;
  d: path("M18.25 15.5h-5a.75.75 0 0 1-.75-.75v-7a.75.75 0 0 1 1.5 0V14h4.25a.75.75 0 0 1 0 1.5M14 2C7.372 2 2 7.373 2 14s5.372 12 12 12c6.627 0 12-5.373 12-12S20.627 2 14 2");
}

</style>
