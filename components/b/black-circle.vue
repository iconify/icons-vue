<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qbnl6lbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:black-circle" /></template>
<style>
.qbnl6lbfx {
  fill: var(--svg-color--212121, #212121);
  d: path("M212 32.2c-17.56 0-31.79 14.23-31.79 31.79S194.44 95.8 212 95.8s31.79-14.25 31.79-31.82S229.56 32.2 212 32.2M64 24.3c-21.92 0-39.69 17.78-39.69 39.71S42.08 103.7 64 103.7s39.69-17.77 39.69-39.69S85.92 24.3 64 24.3");
}

</style>
