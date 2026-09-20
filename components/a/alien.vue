<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zty6m6b7w"/><path class="qgnr_cbmw"/><path class="wreysjbwe"/><path class="n_q9-cbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:alien" /></template>
<style>
.n_q9-cbwa {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M103.13 83.64c-9.45 7.08-23.94 6.28-27.26 2.45c-3.33-3.84-2.63-17.74 6.9-26.51c7.83-7.2 20.73-8.3 25.98-2.24c5.24 6.06 2.89 19.91-5.62 26.3");
}

.qgnr_cbmw {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M24.6 83.64c-8.51-6.39-10.87-20.25-5.63-26.3c5.27-6.06 18.16-4.96 25.99 2.24c9.52 8.77 10.23 22.67 6.89 26.51c-3.32 3.84-17.8 4.64-27.25-2.45");
}

.wreysjbwe {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M64 110.48c-6.9 0-17.47-2.02-17.47-4.96c0-2.14 6.72-3.92 17.47-3.92c10.74 0 17.46 1.78 17.46 3.92c.01 3.07-10.55 4.96-17.46 4.96");
}

.zty6m6b7w {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M64 2.32C24.89 2.32.4 27.04.4 56.76c0 40.92 38.46 68.93 63.6 68.93s63.59-26.21 63.59-68.93c0-29.73-24.47-54.44-63.59-54.44");
}

</style>
