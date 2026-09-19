<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="thfarib8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hamburger" /></template>
<style>
.thfarib8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 20.257c0-5.509-8.73-9.975-19.5-9.975S4.5 14.748 4.5 20.257zm-39 7.486c0 5.509 8.73 9.975 19.5 9.975s19.5-4.466 19.5-9.975z");
}

</style>
