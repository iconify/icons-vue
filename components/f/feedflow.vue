<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uy7labdlj"/><path class="gi1zz02ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:feedflow" /></template>
<style>
.gi1zz02ea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.127 42.5H9.849l6.524-37h21.778l-1.107 6.278h-15.5l-1.622 9.196h10.084l-1.107 6.278H18.815z");
}

.uy7labdlj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.229 24.113h10.059M13.501 39.588l5.457-30.95h15.475");
}

</style>
