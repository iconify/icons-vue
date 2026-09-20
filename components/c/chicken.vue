<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="db0nu0bra"/><path class="c7x40acpa"/><path class="mb36wmb_y"/><ellipse class="saqmmccib"/><path class="gvld5mr-m"/><circle class="rvqgxrbho"/><circle class="nh2l10b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:chicken" /></template>
<style>
.c7x40acpa {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M27.643 15.643C27.643 10.317 23.324 6 18 6a9.643 9.643 0 0 0-9.643 9.643c0 5.357-1.071 16.572-1.071 16.572a2.143 2.143 0 0 0 4.286 0a2.144 2.144 0 0 0 4.285 0h4.286a2.144 2.144 0 0 0 4.287 0a2.143 2.143 0 0 0 4.286 0c-.002 0-1.073-11.215-1.073-16.572");
}

.db0nu0bra {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M20.143 32.215a2.143 2.143 0 1 1-4.286 0a2.143 2.143 0 0 1 4.286 0");
}

.gvld5mr-m {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M25 22.5c0 1.5-14 1.5-14 0s4.791-4.5 7-4.5s7 3 7 4.5");
}

.mb36wmb_y {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M20 3c0 2.209-1.447 6-2 6s-2-3.791-2-6s1.448-3 2-3c.553 0 2 .791 2 3m-4.365 30c0-2.612 1.711-8 2.365-8c.653 0 2.365 5.388 2.365 8S18.652 36 18 36c-.654 0-2.365-.388-2.365-3");
}

.nh2l10b4x {
  cx: 24.5px;
  cy: 18.5px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.rvqgxrbho {
  cx: 11.5px;
  cy: 18.5px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.saqmmccib {
  cx: 18px;
  cy: 22.5px;
  fill: var(--svg-color--f4900c, #f4900c);
  rx: 7px;
  ry: 4.5px;
}

</style>
