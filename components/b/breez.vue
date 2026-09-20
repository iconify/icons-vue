<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mtljb1l0e"/><path class="fvjlndb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:breez" /></template>
<style>
.fvjlndb9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.251 23.5h4.41a7.337 7.337 0 1 1 0 14.674H16.513m9.537 0V42m0-37v3.826");
}

.mtljb1l0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.507 22.766h13.206m-4.402-5.869h13.207M9.91 30.103h16.14M19.495 8.826h10.169a7.337 7.337 0 1 1 0 14.674H28.25");
}

</style>
