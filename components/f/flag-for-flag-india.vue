<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ev7fmykmw"/><path class="eubhabc9r"/><path class="r-dt63lgl"/><circle class="s0dm6vbyj"/><circle class="tek16obmc"/><path class="mktq3hehq"/><circle class="on1c9jbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-india" /></template>
<style>
.eubhabc9r {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 13h36v10H0z");
}

.ev7fmykmw {
  fill: var(--svg-color--138808, #138808);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4H0v4z");
}

.mktq3hehq {
  fill: var(--svg-color--6666b3, #6666B3);
  d: path("M18 15l.146 2.264l1.001-2.035l-.73 2.147l1.704-1.498l-1.497 1.705l2.147-.731l-2.035 1.002L21 18l-2.264.146l2.035 1.001l-2.147-.73l1.497 1.704l-1.704-1.497l.73 2.147l-1.001-2.035L18 21l-.146-2.264l-1.002 2.035l.731-2.147l-1.705 1.497l1.498-1.704l-2.147.73l2.035-1.001L15 18l2.264-.146l-2.035-1.002l2.147.731l-1.498-1.705l1.705 1.498l-.731-2.147l1.002 2.035z");
}

.on1c9jbcv {
  fill: var(--svg-color--navy, navy);
  cx: 18px;
  cy: 18px;
  r: 1px;
}

.r-dt63lgl {
  fill: var(--svg-color--f93, #F93);
  d: path("M36 13V9a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4v4h36z");
}

.s0dm6vbyj {
  fill: var(--svg-color--navy, navy);
  cx: 18px;
  cy: 18px;
  r: 4px;
}

.tek16obmc {
  fill: var(--svg-color--eee, #EEE);
  cx: 18px;
  cy: 18px;
  r: 3px;
}

</style>
