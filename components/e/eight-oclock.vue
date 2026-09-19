<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q_yhtbcoj"/><path class="azx96rbzd"/><path class="a1iuryo_k"/><path class="c1riy5_6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:eight-oclock" /></template>
<style>
.a1iuryo_k {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M30.05 11.02c0-1.436.846-2.598 1.886-2.598c1.042 0 1.886 1.162 1.886 2.598v21.03c0 1.438-.847 2.6-1.886 2.6c-1.041 0-1.886-1.161-1.886-2.6z");
}

.azx96rbzd {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M31.926 0C14.322 0 0 14.321 0 31.926C0 49.529 14.322 63.85 31.926 63.85S63.85 49.53 63.85 31.926C63.85 14.321 49.529 0 31.926 0m0 57.637c-14.177 0-25.71-11.533-25.71-25.711s11.534-25.71 25.71-25.71s25.709 11.534 25.709 25.71s-11.533 25.711-25.709 25.711");
}

.c1riy5_6w {
  fill: var(--svg-color--788288, #788288);
  d: path("M20.549 43.846c-1.137.872-2.575.915-3.209.092c-.634-.826-.227-2.209.91-3.08l12.06-9.283c1.135-.874 2.576-.912 3.207-.087c.637.823.229 2.203-.905 3.08l-12.07 9.278");
}

.q_yhtbcoj {
  fill: var(--svg-color--e0e7ec, #e0e7ec);
  d: path("M61.5 31.924C61.5 48.26 48.26 61.5 31.926 61.5S2.352 48.26 2.352 31.924c0-16.332 13.24-29.572 29.574-29.572S61.5 15.592 61.5 31.924");
}

</style>
