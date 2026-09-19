<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ociax_4ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-musical-note" /></template>
<style>
.ociax_4ff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.099 9.389l-21.182 4.715l-.058-3.893l21.24-4.71zm-21.239.822l.364 27.477M39.099 9.389l.312 23.662M8.59 37.688c0 2.657 2.156 4.811 4.817 4.811s4.817-2.154 4.817-4.81s-2.157-4.812-4.817-4.812s-4.817 2.154-4.817 4.811m21.186-4.637a4.814 4.814 0 0 0 4.815 4.813a4.814 4.814 0 0 0 4.82-4.809v-.004a4.814 4.814 0 0 0-4.814-4.814a4.814 4.814 0 0 0-4.821 4.807z");
}

</style>
