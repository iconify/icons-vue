<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><path class="zm54xehgk"/><circle class="xeeus_bsv"/><circle class="ivoq25b5e"/></g><path class="ue1salbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:kissing-face" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.ivoq25b5e {
  cx: 43.5px;
  cy: 25.6px;
  r: 5px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.ue1salbwt {
  fill: var(--svg-color--917524, #917524);
  d: path("M50.2 16.7c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2-1.4 1.7m-24.7-3.3c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.2.2 2.3-.4 2.2");
}

.xeeus_bsv {
  cx: 20.5px;
  cy: 25.6px;
  r: 5px;
}

.zm54xehgk {
  d: path("M41.5 50.4c1.6-1.6-1.8-3-1.8-5.9s3.4-4.2 1.8-5.9c-1.9-2-6-.5-8.6-3.1c0 2.2 1.8 4.5 5.2 4.5c0 0-2.3.9-2.3 4.5s2.3 4.5 2.3 4.5c-3.4 0-5.2 2.3-5.2 4.5c2.6-2.7 6.7-1.2 8.6-3.1");
}

</style>
