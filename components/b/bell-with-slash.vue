<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dzgvq7fhv"/><circle class="cwy35vdky"/><path class="xzzy5jo_i"/><path class="bu7pb4iqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bell-with-slash" /></template>
<style>
.bu7pb4iqg {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M31.003 33.003L3.997 5.997a1.41 1.41 0 0 1 0-1.994l.006-.006a1.41 1.41 0 0 1 1.994 0l27.006 27.006a1.41 1.41 0 0 1 0 1.994l-.006.006a1.41 1.41 0 0 1-1.994 0");
}

.cwy35vdky {
  cx: 18px;
  cy: 3px;
  r: 3px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.dzgvq7fhv {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M28 13c0 11 5 10 5 15c0 0 0 2-2 2H5c-2 0-2-2-2-2c0-5 5-4 5-15C8 7.478 12.477 3 18 3s10 4.478 10 10");
}

.xzzy5jo_i {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M18 36a4 4 0 0 0 4-4h-8a4 4 0 0 0 4 4");
}

</style>
