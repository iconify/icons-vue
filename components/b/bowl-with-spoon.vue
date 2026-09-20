<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="foornj4eg"/><ellipse class="ezjyipb-f"/><ellipse class="ajmrq2bgv"/><path class="d8k7n0hcv"/><ellipse class="fxifti04t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bowl-with-spoon" /></template>
<style>
.ajmrq2bgv {
  cx: 16px;
  cy: 15px;
  fill: var(--svg-color--662113, #662113);
  rx: 14.641px;
  ry: 7.719px;
}

.d8k7n0hcv {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M34 8c-1 0-4 1-8 4c-4.525 3.394-7.596 2.187-7.596 2.187l.001.003C16.981 13.453 15.087 13 13 13c-4.418 0-8 2.015-8 4.5S8.582 22 13 22c2.773 0 5.216-.794 6.651-2c0 0 4.995-4.431 7.349-6c3-2 5-3 7-3s2-3 0-3");
}

.ezjyipb-f {
  cx: 16px;
  cy: 15px;
  fill: var(--svg-color--ea596e, #ea596e);
  rx: 16.051px;
  ry: 8.917px;
}

.foornj4eg {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M16 31c8.837 0 16-7.163 16-16H0c0 8.837 7.164 16 16 16");
}

.fxifti04t {
  cx: 13px;
  cy: 19px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 5px;
  ry: 2.5px;
}

</style>
