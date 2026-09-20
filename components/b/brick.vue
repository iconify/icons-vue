<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmxz-cb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:brick" /></template>
<style>
.rmxz-cb0x {
  fill: currentColor;
  d: path("M2 20V8h3V4h6v4h2V4h6v4h3v12z");
}

</style>
