<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="rd1fb_b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:letter-o" /></template>
<style>
.rd1fb_b7t {
  fill: var(--svg-color--40c0e7, #40c0e7);
  fill-rule: evenodd;
  d: path("M64.01 15.06c-34.13 0-55.46 24.1-55.46 53.82c0 29.73 21.33 53.82 55.46 53.82c34.12 0 55.45-24.1 55.45-53.82c-.01-29.73-21.33-53.82-55.45-53.82m0 81.78c-17.73 0-28.82-12.52-28.82-27.96s11.08-27.96 28.82-27.96c17.73 0 28.81 12.52 28.81 27.96c-.01 15.44-11.09 27.96-28.81 27.96");
}

</style>
