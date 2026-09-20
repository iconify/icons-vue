<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="gakfakb2m"/><path class="espmgebih"/><path class="etqf2sb1g"/><path class="b9fj_i20p"/><path class="b5485bc3n"/><path class="wm9r7768d"/><path class="on745py2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-with-bags-under-eyes" /></template>
<style>
.b5485bc3n {
  fill: var(--svg-color--664500, #664500);
  d: path("M11.65 18.7c1.38 0 2.5-1.57 2.5-3.5v-.25l-5 .37c.06 1.87 1.15 3.38 2.5 3.38M21 27a1 1 0 0 1-.3 0a8.68 8.68 0 0 0-5.38 0a1 1 0 1 1-.62-2a10.63 10.63 0 0 1 6.6 0a1 1 0 0 1 .64 1.26A1 1 0 0 1 21 27m7.89-14.31a8.39 8.39 0 0 0-7-1.57a1 1 0 0 1-.59-1.91a10.43 10.43 0 0 1 8.75 1.86a1 1 0 0 1 .23 1.4a1 1 0 0 1-.51.37a1 1 0 0 1-.88-.15");
}

.b9fj_i20p {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.88 14.89l-7.72.58a1.54 1.54 0 0 0-1.3 2.19a5.72 5.72 0 0 0 10.63-.8a1.55 1.55 0 0 0-1.61-1.97");
}

.espmgebih {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M5.71 16.82a3 3 0 0 0-.3 3.18s0 .05 0 .07a5.72 5.72 0 0 0 9.05 1.72l.07-.07a6.76 6.76 0 0 0 1.92-4.8zm24.58 0H19.51a6.76 6.76 0 0 0 1.92 4.8a.5.5 0 0 0 .07.07a5.72 5.72 0 0 0 9-1.72v-.07a3 3 0 0 0-.21-3.08");
}

.etqf2sb1g {
  fill: var(--svg-color--664500, #664500);
  d: path("M6.22 12.84a1 1 0 0 1-.51-.37a1 1 0 0 1 .23-1.4a10.43 10.43 0 0 1 8.75-1.86a1 1 0 1 1-.59 1.91a8.41 8.41 0 0 0-7 1.57a1 1 0 0 1-.88.15");
}

.gakfakb2m {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18A18 18 0 1 1 18 0a18 18 0 0 1 18 18");
}

.on745py2i {
  fill: var(--svg-color--664500, #664500);
  d: path("M24.35 18.7c-1.38 0-2.5-1.57-2.5-3.5v-.25l5 .37c-.06 1.87-1.15 3.38-2.5 3.38");
}

.wm9r7768d {
  fill: var(--svg-color--fff, #fff);
  d: path("m21.12 14.89l7.72.58a1.54 1.54 0 0 1 1.3 2.19a5.72 5.72 0 0 1-10.63-.8a1.55 1.55 0 0 1 1.61-1.97");
}

</style>
