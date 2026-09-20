<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p565k4bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-align-center-outline" /></template>
<style>
.p565k4bfg {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm4-3.75v-1h8v1zM4 12.5v-1h16v1zm4-3.75v-1h8v1zM4 5V4h16v1z");
}

</style>
