<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGx9JU3cTP" class="bn9_0m9dr"/></defs><g class="ehej3-bmx"><circle class="vdv00g47z"/><circle class="ko0v-1n5j"/><use href="#SVGx9JU3cTP"/><circle class="cjzbo_0vt"/></g><g class="ehej3-bmx"><circle class="vdv00g47z"/><circle class="ko0v-1n5j"/><use href="#SVGx9JU3cTP"/><circle class="cjzbo_0vt"/></g><g class="ehej3-bmx"><path class="kp27_34nr"/><path class="jar05488g"/></g><path class="nudqf_b7b"/><path class="glha_62vu"/><path class="vqf6bacyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:light-rail" /></template>
<style>
.bn9_0m9dr {
  d: path("M96.93 112.92c0 4.48-3.63 8.11-8.11 8.11c-4.49 0-8.12-3.63-8.12-8.11s3.63-8.11 8.12-8.11c4.48 0 8.11 3.63 8.11 8.11");
}

.cjzbo_0vt {
  cx: 105.04px;
  cy: 112.92px;
  r: 8.11px;
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.glha_62vu {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M1.16 114.35c-.15 1.71 1.11 3.11 2.81 3.11h119.71c1.7 0 2.84-1.38 2.53-3.07l.01-5.97c-.31-1.69-1.97-3.06-3.68-3.06H4.57c-1.72 0-3.25 1.39-3.41 3.1z");
}

.jar05488g {
  d: path("M61.14 35.58v-4.94c0-1.71 1.41-3.11 3.12-3.11h19.61c1.71 0 3.12 1.4 3.12 3.11v4.94z");
}

.ko0v-1n5j {
  cx: 39.19px;
  cy: 112.92px;
  r: 8.11px;
}

.kp27_34nr {
  d: path("M69.02 62.89c-.85 0-1.69-.32-2.33-.96a3.3 3.3 0 0 1 0-4.67l12.33-12.33L68.9 34.8a3.29 3.29 0 0 1 0-4.66c1.28-1.29 3.37-1.29 4.67 0L86.02 42.6a3.3 3.3 0 0 1 0 4.67L71.36 61.93c-.64.65-1.49.96-2.34.96");
}

.nudqf_b7b {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("m127.27 90.22l-5.41-25c-1.27-6.08-6.96-13-14.85-13H20.99c-7.9 0-13.58 6.92-14.85 13l-5.41 25c-.36 1.68-.2 4.37.37 5.99l3.33 9.51c.57 1.62 2.43 2.95 4.15 2.95h110.83c1.71 0 3.58-1.33 4.15-2.95l3.33-9.51c.57-1.62.74-4.32.38-5.99");
}

.vdv00g47z {
  cx: 22.96px;
  cy: 112.92px;
  r: 8.11px;
}

.vqf6bacyq {
  fill: var(--svg-color--fff, #fff);
  d: path("M70.8 61.54c-1.79 0-3.25 1.4-3.25 3.12v21.46c0 1.72 1.46 3.12 3.25 3.12h13.7c1.78 0 3.24-1.4 3.24-3.12V64.65c0-1.72-1.46-3.12-3.24-3.12H70.8zm-27.3 0c-1.78 0-3.24 1.4-3.24 3.12v21.46c0 1.72 1.46 3.12 3.24 3.12h13.69c1.79 0 3.25-1.4 3.25-3.12V64.65c0-1.72-1.46-3.12-3.25-3.12H43.5zm-22.18-.17c-2.84 0-5.13 2.01-6.07 5.5l-3.88 19.29c-.32 1.69.89 3.07 2.66 3.07h15.85c1.79 0 3.25-1.4 3.25-3.12V64.49c0-1.71-1.46-3.11-3.25-3.11h-8.56zm85.37 0c2.84 0 5.13 2.01 6.06 5.5l3.88 19.29c.32 1.69-.88 3.07-2.67 3.07H98.1c-1.78 0-3.25-1.4-3.25-3.12V64.49c0-1.71 1.47-3.11 3.25-3.11h8.59z");
}

</style>
