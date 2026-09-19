<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="x4xf73vlv"/><path class="l_tbsqb2b"/><path class="qaxvoabtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:grinning-face-with-sweat" /></template>
<style>
.l_tbsqb2b {
  fill: var(--svg-color--fff, #fff);
  d: path("M41.7 38.3c-2.2-.4-6.8-1-12.7-1s-10.5.6-12.7 1c-1.3.2-1.4.7-1.3 1.5c.1.4.1 1 .3 1.6c.1.6.3.9 1.3.8c1.9-.2 23-.2 24.9 0c1 .1 1.1-.2 1.3-.8c.1-.6.2-1.1.3-1.6c0-.8-.1-1.3-1.4-1.5");
}

.qaxvoabtv {
  fill: var(--svg-color--65b1ef, #65b1ef);
  d: path("M60 30.2c0 7.2-9.7 7.2-9.7 0c0-5.2 4.9-10.4 4.9-10.4S60 25 60 30.2");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.x4xf73vlv {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M25.5 26.9c-1.9-5.1-4.7-7.7-7.5-7.7s-5.6 2.6-7.5 7.7c-.2.5.8 1.4 1.3.9c1.8-1.9 4-2.7 6.2-2.7s4.4.8 6.2 2.7c.6.5 1.5-.4 1.3-.9m21.9 0c-1.9-5.1-4.7-7.7-7.5-7.7s-5.6 2.6-7.5 7.7c-.2.5.8 1.4 1.3.9c1.8-1.9 4-2.7 6.2-2.7s4.4.8 6.2 2.7c.5.5 1.5-.4 1.3-.9M46 38c0-.8-.5-1.8-1.8-2.1c-3.5-.7-8.6-1.3-15.2-1.3s-11.7.7-15.2 1.3c-1.3.3-1.8 1.3-1.8 2.1c0 7.3 5.6 14.6 17 14.6S46 45.3 46 38");
}

</style>
