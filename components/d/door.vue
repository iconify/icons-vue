<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nhijbb6mc"/><circle class="qvm_fjbvk"/><path class="kxlfr4spr"/><path class="igtib4prc"/><path class="gt8qgdbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:door" /></template>
<style>
.gt8qgdbzv {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M47.57 19.78h39.68v-7.59H40.74V58.7h6.83z");
}

.igtib4prc {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M40.74 12.19h46.51V58.7H40.74z");
}

.kxlfr4spr {
  fill: var(--svg-color--fff, #fff);
  d: path("M36.48 75.38c.42.98 1.33.65 1.56-.25c.15-.58.47-1.17.87-1.62c.4-.44 1.08-.83 1.63-1.07c.54-.24.93-.42.81-1.12c-.09-.61-.95-.57-1.41-.51c-.52.06-.99.32-1.47.53c-.31.13-.64.27-.86.53c-.84.88-1.66 2.28-1.13 3.51");
}

.nhijbb6mc {
  fill: var(--svg-color--855c52, #855c52);
  d: path("M28.25.72v126.57h71.5V.72z");
}

.qvm_fjbvk {
  cx: 40.74px;
  cy: 74.91px;
  r: 5.55px;
  fill: var(--svg-color--fcc21b, #fcc21b);
}

</style>
