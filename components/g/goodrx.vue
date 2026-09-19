<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="biazf5bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goodrx" /></template>
<style>
.biazf5bpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 18.5h-7.5V11a5.5 5.5 0 0 0-11 0v7.5H11a5.5 5.5 0 0 0 0 11h7.5V37a5.5 5.5 0 0 0 11 0v-7.5H37a5.5 5.5 0 0 0 0-11m-7.5 11h-11m0-11v11");
}

</style>
