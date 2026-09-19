<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="g0ra3gj-s"/><circle class="vx9v-qhlm"/></g><path class="ikl84zo_m"/><circle class="l--i_bb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:hushed-face" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.g0ra3gj-s {
  cx: 20px;
  cy: 27px;
  r: 5px;
}

.ikl84zo_m {
  fill: var(--svg-color--917524, #917524);
  d: path("M50.2 17c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2.1-1.4 1.7m-24.7-3.2c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.1.2 2.3-.4 2.2");
}

.l--i_bb6p {
  cx: 32px;
  cy: 48px;
  r: 5px;
  fill: var(--svg-color--664e27, #664e27);
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.vx9v-qhlm {
  cx: 44px;
  cy: 27px;
  r: 5px;
}

</style>
