<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pk07sfbhl"/><path class="qrwpk_btf"/><path class="ecj6zqbaa"/><circle class="hbkcainmw"/><g class="hxik4rbqd"><path class="pyn4i7bbx"/><path class="k5wmteq5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-ethiopia" /></template>
<style>
.ecj6zqbaa {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M60.3 42c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10H3.7C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10z");
}

.hbkcainmw {
  cx: 32px;
  cy: 32px;
  r: 14px;
  fill: var(--svg-color--428bc1, #428bc1);
}

.hxik4rbqd {
  fill: var(--svg-color--ffce31, #ffce31);
}

.k5wmteq5t {
  d: path("M31.6 37.3V42h.8v-4.7L32 37zm-5.7-4.6L22 33.8l.2.8l4.6-1.3zm3.2-4.6l.2-.8l-3.1-3.8l-.6.5l3.3 4.1zm6 0l3.3-4.1l-.6-.5l-3.1 3.8l.2.8zm3 4.6l-.9.6l4.6 1.3l.2-.8z");
}

.pk07sfbhl {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.pyn4i7bbx {
  d: path("m35.8 33.3l6.1-4.3h-7.5L32 22l-2.3 7h-7.5l6.1 4.3l-2.3 7l6-4.3l6.1 4.3zm3.5-3.5l-3.8 2.7l-.9-2.7zM29.2 33l1.1-3.2h3.5l1.1 3.2l-2.9 2zm2.8-8.4l1.5 4.4h-2.9zm-7.3 5.2h4.7l-.9 2.7zm2.8 8.4l1.4-4.4l2.4 1.7zm9 0l-3.8-2.7l2.4-1.7z");
}

.qrwpk_btf {
  fill: var(--svg-color--699635, #699635);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

</style>
