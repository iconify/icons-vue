<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lwzsk_5sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:every-proxy" /></template>
<style>
.lwzsk_5sq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.874 15.221l-.03 4.219h15.583v6.06l8.073-8.11l-8.073-8.527v6.358zm8.4 13.309H12.811v-6.624L4.5 30.55l8.31 8.586v-6.655h15.464z");
}

</style>
