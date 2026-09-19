<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="eoq00gbdh"><ellipse class="e21l34o_d"/><ellipse class="aezunnboo"/></g><circle class="rhvdvboaq"/><path class="qsxg-evhg"/><path class="qs-a-abha"/><path class="l5aqq-ddv"/><path class="emir3qmgp"/><path class="wemhrabse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:loudly-crying-face" /></template>
<style>
.aezunnboo {
  cx: 44px;
  cy: 60.2px;
  rx: 18px;
  ry: 1.8px;
}

.e21l34o_d {
  cx: 17.5px;
  cy: 59.9px;
  rx: 12.5px;
  ry: 1.5px;
}

.emir3qmgp {
  fill: var(--svg-color--917524, #917524);
  d: path("M40.7 18.3c3 3 7.2 4.5 11.4 4.1c.6-.1.9 2.1.2 2.2c-4.9.4-9.7-1.3-13.1-4.8c-.6-.5 1.1-1.9 1.5-1.5M12 22.4c4.2.4 8.4-1.1 11.4-4.1c.4-.4 2.1 1 1.6 1.5c-3.4 3.5-8.3 5.2-13.1 4.8c-.9 0-.5-2.2.1-2.2");
}

.eoq00gbdh {
  fill: var(--svg-color--65b1ef, #65b1ef);
}

.l5aqq-ddv {
  fill: var(--svg-color--65b1ef, #65b1ef);
  d: path("M44.5 60.5h6.8c8.2-9.9-1.5-20 .9-29.8c-2.3 0-4.6 2.5-6.8 2.5c-3.2 9.5 7.3 17.4-.9 27.3m-25 0h-6.8c-8.2-9.9 1.5-20-.9-29.8c2.3 0 4.6 2.5 6.8 2.5c3.2 9.5-7.3 17.4.9 27.3");
}

.qs-a-abha {
  fill: var(--svg-color--fff, #fff);
  d: path("M41 45c.1-.3 0-.6-.2-.8c0 0-2-2.2-8.8-2.2s-8.8 2.2-8.8 2.2c-.2.1-.2.5-.2.8l.2.6c.1.3.3.5.5.5h16.6c.2 0 .5-.2.5-.5z");
}

.qsxg-evhg {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M44.7 46c-1.4-3.6-4.8-6-12.7-6c-8 0-11.3 2.4-12.7 6c-.7 1.9.3 5 .3 5c1.3 3.9 1.1 5 12.4 5s11.1-1.1 12.4-5c0 0 1.1-3.1.3-5");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.wemhrabse {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M35.9 30.3c4.2 8 12.7 8 16.9 0c.2-.4-.3-.6-1-1c-4.2 3.3-11.1 3-14.9 0c-.6.4-1.2.6-1 1m-24.7 0c4.2 8 12.7 8 16.9 0c.2-.4-.3-.6-1-1c-4.2 3.3-11.1 3-14.9 0c-.7.4-1.2.6-1 1");
}

</style>
