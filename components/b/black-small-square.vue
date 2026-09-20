<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tjktpnt8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:black-small-square" /></template>
<style>
.tjktpnt8t {
  fill: var(--svg-color--212121, #212121);
  d: path("M50.04 50.04h27.91v27.92H50.04z");
}

</style>
