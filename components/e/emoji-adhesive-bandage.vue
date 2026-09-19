<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qw973rbfj"/><path class="u43vatbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-adhesive-bandage" /></template>
<style>
.qw973rbfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.255 18.089A7.314 7.314 0 0 0 29.911 7.745m-11.822 32.51A7.314 7.314 0 0 1 7.745 29.911M29.91 7.745L7.746 29.91m5.171-5.171L23.26 35.083m1.479-22.166L35.083 23.26M18.089 40.255L40.255 18.09");
}

.u43vatbdk {
  fill: currentColor;
  d: path("M10.974 30.058a.75.75 0 0 0 1.5 0a.75.75 0 0 0-1.5 0m2.069 2.069a.75.75 0 1 0 1.5 0a.75.75 0 0 0-1.5 0m2.069 2.068a.75.75 0 1 0 1.5 0a.75.75 0 0 0-1.5 0m2.081 2.069a.75.75 0 0 0 1.499.002v-.002a.75.75 0 0 0-1.5-.002zm-8.423-3.99a.75.75 0 1 0 1.5 0a.75.75 0 0 0-1.5 0m2.068 2.069a.75.75 0 1 0 1.5 0a.75.75 0 0 0-1.5 0m2.069 2.069a.75.75 0 1 0 1.5 0a.75.75 0 0 0-1.5 0m2.069 2.068a.75.75 0 1 0 1.5 0a.75.75 0 0 0-1.5 0M31.663 9.37a.75.75 0 1 0 1.5.001V9.37a.75.75 0 1 0-1.5-.002zm2.069 2.068a.75.75 0 1 0 1.5.002v-.002a.75.75 0 1 0-1.5-.002zm2.068 2.069a.75.75 0 0 0 1.5.002v-.002a.75.75 0 0 0-1.5-.002zm2.07 2.069a.75.75 0 0 0 1.499.002v-.002a.75.75 0 0 0-1.5-.002zm-8.423-3.99a.75.75 0 0 0 1.499.002v-.002a.75.75 0 0 0-1.5-.002zm2.068 2.069a.75.75 0 1 0 0-.002zm2.069 2.069a.75.75 0 0 0 1.5.002v-.003a.75.75 0 0 0-1.5-.002zm2.069 2.068a.75.75 0 1 0 1.5.002v-.002a.75.75 0 1 0-1.5-.002z");
}

</style>
