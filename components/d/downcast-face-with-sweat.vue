<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fhg6xnblt"/><path class="or2pkk3vd"/><g class="fbp0m0b1e"><circle class="jtvco4d5l"/><circle class="r4qke1bax"/></g><path class="yn77rgg1b"/><path class="qoprzcc0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:downcast-face-with-sweat" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.fhg6xnblt {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("M2 32c0 16.6 13.4 30 30 30s30-13.4 30-30S48.6 2 32 2S2 15.4 2 32");
}

.jtvco4d5l {
  cx: 43.5px;
  cy: 36px;
  r: 5px;
}

.or2pkk3vd {
  fill: var(--svg-color--65b1ef, #65b1ef);
  d: path("M48.5 16.3c0 9.9 13.5 9.9 13.5 0C62 9.1 55.3 2 55.3 2s-6.8 7.1-6.8 14.3");
}

.qoprzcc0g {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40 52H24c-1.5 0-1.5-4 0-4h16c1.5 0 1.5 4 0 4");
}

.r4qke1bax {
  cx: 20.5px;
  cy: 36px;
  r: 5px;
}

.yn77rgg1b {
  fill: var(--svg-color--917524, #917524);
  d: path("M25.6 21.9c-3.2 2.7-7.5 3.9-11.7 3.1c-.6-.1-1.1 2-.4 2.2c4.8.9 9.8-.5 13.5-3.6c.5-.5-1-2.1-1.4-1.7m24.5 3c-4.2.7-8.5-.4-11.7-3.1c-.4-.4-2 1.2-1.4 1.7c3.7 3.2 8.7 4.5 13.5 3.6c.7-.2.2-2.3-.4-2.2");
}

</style>
