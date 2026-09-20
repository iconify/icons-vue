<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c9mt5evfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:black-medium-square" /></template>
<style>
.c9mt5evfe {
  fill: var(--svg-color--212121, #212121);
  d: path("M23 23h82v82H23z");
}

</style>
