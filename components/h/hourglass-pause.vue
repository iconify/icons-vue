<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvt52hb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hourglass-pause" /></template>
<style>
.vvt52hb7m {
  fill: currentColor;
  d: path("M4 22v-2h2v-3q0-1.525.713-2.863T8.7 12q-1.275-.8-1.987-2.137T6 7V4H4V2h16v2h-2v3q0 1.2-.45 2.3t-1.275 1.925q-1.175.3-2.137.938T12.475 13.7t-1.087 2T11 18q0 1.075.325 2.1t.95 1.9zm10.463-.462Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463M16.25 20h1v-4h-1zm2.5 0h1v-4h-1z");
}

</style>
