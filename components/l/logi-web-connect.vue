<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="et2orrbro"/><path class="u88g1ownm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:logi-web-connect" /></template>
<style>
.et2orrbro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.748 5.381l14.078 21.03h-9.9l10.826 16.208L45.5 24.002L34.748 5.383z");
}

.u88g1ownm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.248 5.381L2.5 23.998l10.752 18.619l15 .002L14.174 21.59h9.9z");
}

</style>
