<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oicrsgb8u"/><path class="imyhvmakl"/><path class="ovbgymckq"/><path class="e9k8ods_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dharma" /></template>
<style>
.e9k8ods_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.546 20.427a9.636 9.636 0 0 1 9.636 9.636V42.5h0H15.91h0V30.063a9.636 9.636 0 0 1 9.636-9.636");
}

.imyhvmakl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.83 11.384a13.465 13.465 0 0 1 13.465 13.465V42.5h0h-26.93h0V24.849A13.465 13.465 0 0 1 23.83 11.384");
}

.oicrsgb8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5A18.5 18.5 0 0 1 42.5 24v16.5a2 2 0 0 1-2 2h-33a2 2 0 0 1-2-2V24A18.5 18.5 0 0 1 24 5.5");
}

.ovbgymckq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.819 28.922a5.29 5.29 0 0 1 5.29 5.29V42.5h0h-10.58h0v-8.288a5.29 5.29 0 0 1 5.29-5.29");
}

</style>
