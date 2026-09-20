<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="q85actrjt"/><path class="nmrasxmpq"/><path class="rc315s9no"/><circle class="zxd8mmban"/><circle class="x3xatnrcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:front-facing-baby-chick" /></template>
<style>
.nmrasxmpq {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M34 24c-1-2-3-5-4-10h-.008c.001-.052.008-.102.008-.154c0-5.943-4.324-10.864-9.996-11.819c1.189-.26 2.031-.509.996-1.027c-1.115-.558-2.23.129-2.999.846h-.002C17.23 1.129 16.116.442 15 1c-1.035.518-.193.767.996 1.026C10.325 2.981 6 7.902 6 13.846c0 .052.007.102.008.154H6c-1 5-3 8-4 10c-.447.895 0 3 2 2c1.191-.596 2.377-1.912 3.357-3.715C8.902 26.94 12.066 31 18 31s9.098-4.06 10.643-8.715c.98 1.803 2.166 3.119 3.357 3.715c2 1 2.447-1.105 2-2");
}

.q85actrjt {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M17.38 33.098a.97.97 0 0 0-.417-.391C15.366 31.001 16.5 29 16.5 29c0-.553 1-2 0-2l-1 1c-1 1-1 4-1 4h-2a1 1 0 1 0 0 2h1.108l-.222.12a1 1 0 1 0 .952 1.759l2.639-1.427a1 1 0 0 0 .403-1.354M23.5 32h-2s0-3-1-4l-1-1c-1 0 0 1.447 0 2c0 0 1.135 2.001-.462 3.707a1 1 0 0 0-.418.391a1 1 0 0 0 .404 1.355l2.639 1.427a1 1 0 0 0 .952-1.759L22.393 34H23.5a1 1 0 1 0 0-2");
}

.rc315s9no {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M21 14c0 1.657-1.343 2-3 2s-3-.343-3-2a3 3 0 1 1 6 0");
}

.x3xatnrcb {
  cx: 24.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: var(--svg-color--662113, #662113);
}

.zxd8mmban {
  cx: 11.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: var(--svg-color--662113, #662113);
}

</style>
