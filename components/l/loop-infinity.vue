<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ln5rwnb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:loop-infinity" /></template>
<style>
.ln5rwnb5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.269 28.202l-1.517 1.709a8.352 8.352 0 1 1 0-11.822l10.496 11.822a8.352 8.352 0 1 0 0-11.822l-1.517 1.709");
}

</style>
