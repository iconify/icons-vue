<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rdwcm3bhq"/><path class="w0w4vqbtr"/><path class="kwv375b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:assembly-line" /></template>
<style>
.kwv375b8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.05 36.384L24 37.51v-4.347l-1.95-1.282zm-15.6-9.007l15.6 9.007v-4.503l-15.6-9.007zM24 37.51l19.5-11.258v-4.504m-1.95-1.125l-15.6-9.007m0 18.014l-15.6-9.007m1.95-1.126l15.6 9.006m3.9-2.251l-15.6-9.007l1.95-1.126l15.6 9.007m3.9-2.252l-15.6-9.006L24 12.742l15.6 9.006");
}

.rdwcm3bhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 10.49l1.95 1.126l-19.5 11.258l-1.95-1.126z");
}

.w0w4vqbtr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.45 22.874v4.503L4.5 26.252v-4.504zm37.05-1.126L24 33.163l-1.95-1.282l19.5-11.258z");
}

</style>
