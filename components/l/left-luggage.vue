<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y5q-r40xe"/><circle class="fktweubsh"/><path class="gkqydcc0y"/><path class="mkwj4obph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:left-luggage" /></template>
<style>
.fktweubsh {
  cx: 23px;
  cy: 16px;
  r: 2px;
  fill: currentColor;
}

.gkqydcc0y {
  fill: currentColor;
  d: path("M28 28h8v4h-8z");
}

.mkwj4obph {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.431 2 32s13.432 30 30 30s30-13.431 30-30S48.568 2 32 2m-8 10c1.477 0 2.752.81 3.445 2H42l2 2l-2 2h-2l-2-2l-2 2h-2l-2-2l-2 2h-2.555c-.693 1.19-1.969 2-3.445 2a4 4 0 0 1 0-8m28 36.666C52 50.504 50.484 52 48.621 52H15.377C13.516 52 12 50.504 12 48.666V25.334C12 23.496 13.516 22 15.377 22h33.244C50.484 22 52 23.496 52 25.334z");
}

.y5q-r40xe {
  fill: currentColor;
  d: path("M48.621 24H15.377c-.76 0-1.377.599-1.377 1.334v23.332c0 .735.617 1.334 1.377 1.334h33.244c.76 0 1.379-.599 1.379-1.334V25.334c0-.735-.619-1.334-1.379-1.334M20 48h-3a1 1 0 0 1-1-1V33a1 1 0 0 1 1-1h3zm22 0H22V32h4v-4a2 2 0 0 1 2-2h8c1.102 0 2 .896 2 2v4h4zm6-1a1 1 0 0 1-1 1h-3V32h3a1 1 0 0 1 1 1z");
}

</style>
