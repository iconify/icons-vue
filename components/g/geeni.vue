<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tor86vbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geeni" /></template>
<style>
.tor86vbuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.982 20.136a7.76 7.76 0 1 1 1.04-3.88m7.956-.001a7.76 7.76 0 1 1 1.04 3.88m-1.04-3.88l15.521-.04m-23.477.161H4.502m5.894 18.265c8.564 6.621 17.654 6.35 27.207 0");
}

</style>
