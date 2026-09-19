<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kw64rmi1c"/><path class="d-k_zfb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cpspeed" /></template>
<style>
.d-k_zfb6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.048 33.184a15.5 15.5 0 0 1-17.622 8.532A15.5 15.5 0 0 1 5.507 26.183a15.5 15.5 0 0 1 12.802-14.814");
}

.kw64rmi1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.994 34.119l7.57-28.253A21.5 21.5 0 0 1 42.5 26.633H21");
}

</style>
