<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlne_acgv"/><path class="c28tezb1q"/><path class="wehpfj2qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:googleauthenticator" /></template>
<style>
.c28tezb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.75 40.888za3.285 3.285 0 0 1-4.488-1.202L24 30.572l-5.262 9.114a3.285 3.285 0 1 1-5.69-3.286l5.26-9.115H29.69l5.262 9.115a3.285 3.285 0 0 1-1.202 4.488M24 17.428l-1.92 3.325l-3.771-.038l-5.262-9.115a3.285 3.285 0 0 1 5.691-3.286z");
}

.nlne_acgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24za3.285 3.285 0 0 1-3.285 3.285H29.69L24 17.428l5.262-9.113a3.285 3.285 0 0 1 5.691 3.286l-5.262 9.114h10.524A3.285 3.285 0 0 1 43.5 24");
}

.wehpfj2qb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.08 20.753l-3.771 6.532H7.785a3.285 3.285 0 1 1 0-6.57zm-3.771 6.532L24 17.428l5.691 9.857z");
}

</style>
