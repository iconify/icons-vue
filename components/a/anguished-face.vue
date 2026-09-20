<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qcm02l20p"/><path class="jec0rtbhr"/><path class="ygos3zbip"/><path class="xszhtrb1v"/><path class="ltmstbk4m"/><path class="iw6cncyvg"/><path class="q4jjk3b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:anguished-face" /></template>
<style>
.iw6cncyvg {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M43.08 97.67c1.99 1.34 4.5.46 6.71 0c6.18-1.28 11.6-1.33 14.2-1.33s8.03.05 14.2 1.33c2.21.46 4.72 1.34 6.71 0c2.52-1.71.66-7.83-3.31-11.97c-2.4-2.5-8.13-7.35-17.61-7.35s-15.2 4.85-17.61 7.35c-3.95 4.15-5.81 10.27-3.29 11.97");
}

.jec0rtbhr {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M94.42 55.4c0-.88-.13-1.71-.32-2.51c-1.84-.47-3.75-1.13-5.69-2.22a40 40 0 0 1-5.08-3.37c-2.33 1.58-3.91 4.59-3.91 8.1c0 5.11 3.35 9.25 7.5 9.25c4.15.01 7.5-4.13 7.5-9.25");
}

.ltmstbk4m {
  fill: none;
  stroke: var(--svg-color--2f2f2f, #2f2f2f);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M47.77 41.14s4.31 2.64 5.2 8.43");
}

.q4jjk3b9s {
  fill: var(--svg-color--fff, #fff);
  d: path("M119.19 68.66c-1.68 4.5-5.13 6.96-7.79 7.39c-2.99.48-5.52-.31-7.14-2.22c-2.05-2.42-2.34-6.23-.84-10.73c2.73-8.09 3.69-22.88 3.71-23.02c.04-.57.39-1.05.94-1.21c.53-.19 1.11 0 1.48.43c12.37 14.92 11.36 24.8 9.64 29.36");
}

.qcm02l20p {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64.22 9.62C1.81 9.62.34 79.58.34 93.42c0 13.86 28.59 25.08 63.88 25.08c35.28 0 63.88-11.22 63.88-25.08c0-13.84-1.48-83.8-63.88-83.8");
}

.xszhtrb1v {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M33.58 55.4c0-.88.13-1.71.32-2.51c1.84-.47 3.75-1.13 5.69-2.22c1.97-1.11 3.62-2.23 5.08-3.37c2.33 1.58 3.91 4.59 3.91 8.1c0 5.11-3.35 9.25-7.5 9.25c-4.15.01-7.5-4.13-7.5-9.25");
}

.ygos3zbip {
  fill: none;
  stroke: var(--svg-color--2f2f2f, #2f2f2f);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M80.23 41.14s-4.31 2.64-5.2 8.43");
}

</style>
