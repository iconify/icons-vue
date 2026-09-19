<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e1xrdubwt"/><path class="pnnzzy_mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ayah" /></template>
<style>
.e1xrdubwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.123c1.224-1.804 5.486-4.684 8.714-4.748l5.507 15.413C34.423 26.77 27.85 29.46 24 33.194c-3.85-3.735-10.423-6.425-14.22-7.406l5.506-15.413c3.228.064 7.49 2.944 8.714 4.748");
}

.pnnzzy_mf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.42 12.354l4.104 1.281l4.895 13.75a1.4 1.4 0 0 1-.714 1.734L24 37.625L6.295 29.119a1.4 1.4 0 0 1-.713-1.734l4.894-13.75l4.103-1.281");
}

</style>
