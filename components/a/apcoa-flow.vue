<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m6m1n3upe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apcoa-flow" /></template>
<style>
.m6m1n3upe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.239 9.484h30.638l-2.157 9.25H9.118zm-2.121 9.25h30.639l-2.157 9.25H6.998zm-2.12 9.25h16.574l-2.312 9.25H4.877z");
}

</style>
