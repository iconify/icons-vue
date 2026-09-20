<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tid-pwb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home" /></template>
<style>
.tid-pwb3b {
  fill: currentColor;
  d: path("M5 20V9.5l7-5.288L19 9.5V20h-5.192v-6.384h-3.616V20z");
}

</style>
