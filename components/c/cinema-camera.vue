<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-cvv9b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cinema-camera" /></template>
<style>
.p-cvv9b6i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 8.256q.124-.006.25-.006h5.5q.126 0 .25.006V6.75h-6zm7.5.357q.682.309 1.255.882q.521.52.824 1.131q.236-.146.524-.257l3-1.154q1.228-.472 2.312.273q1.085.744 1.085 2.06v4.404q0 1.316-1.085 2.06q-1.084.745-2.312.273l-3-1.154q-.187-.072-.352-.159q-.308.845-.996 1.533Q13.26 19.75 11.5 19.75H6q-1.76 0-3.005-1.245T1.75 15.5v-3q0-1.76 1.245-3.005q.573-.573 1.255-.882V6q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 5.25h7.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
