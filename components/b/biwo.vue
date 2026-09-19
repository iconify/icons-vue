<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sio04nbqb"/><path class="rc7g21mbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:biwo" /></template>
<style>
.rc7g21mbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.939 35.023v1.75a5.645 5.645 0 0 0 5.642 5.643h15.277a5.646 5.646 0 0 0 5.642-5.642V21.53a5.645 5.645 0 0 0-5.642-5.642H21.58a5.644 5.644 0 0 0-5.642 5.642v7.742");
}

.sio04nbqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.062 12.976v-1.75a5.645 5.645 0 0 0-5.642-5.642H11.142A5.645 5.645 0 0 0 5.5 11.226V26.47a5.646 5.646 0 0 0 5.642 5.642H26.42a5.645 5.645 0 0 0 5.642-5.642v-7.743");
}

</style>
