<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgvlu9lpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-cool-down-outline" /></template>
<style>
.kgvlu9lpc {
  fill: currentColor;
  d: path("m12 22l-7-7l1.4-1.425l4.6 4.6V11h2v7.175l4.6-4.575L19 15zM11 9V6h2v3zm0-5V2h2v2z");
}

</style>
