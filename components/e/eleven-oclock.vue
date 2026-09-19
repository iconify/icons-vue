<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="d6z8b5epc"/><path class="keogjuphs"/><path class="b2yze84rc"/><path class="y89-obcxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:eleven-oclock" /></template>
<style>
.b2yze84rc {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M30.1 11.03c0-1.438.847-2.603 1.89-2.603s1.89 1.164 1.89 2.603V32.1c0 1.441-.847 2.604-1.89 2.604S30.1 33.541 30.1 32.1z");
}

.d6z8b5epc {
  cx: 31.981px;
  cy: 31.981px;
  r: 29.627px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.keogjuphs {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M31.983 0C14.348 0 0 14.346 0 31.983c0 17.634 14.348 31.981 31.983 31.981s31.981-14.347 31.981-31.981C63.964 14.346 49.617 0 31.983 0m0 57.739c-14.202 0-25.756-11.554-25.756-25.756S17.781 6.227 31.983 6.227s25.753 11.554 25.753 25.756s-11.552 25.756-25.753 25.756");
}

.y89-obcxb {
  fill: var(--svg-color--788288, #788288);
  d: path("M21.812 20.19c-.743-1.229-.618-2.663.273-3.2c.895-.54 2.222.023 2.963 1.255l7.875 13.06c.739 1.232.614 2.669-.278 3.203c-.891.538-2.22-.021-2.96-1.249l-7.873-13.07");
}

</style>
