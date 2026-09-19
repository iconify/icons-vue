<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="r3rddk09k"/><path class="sd-z9ccws"/><path class="ix_3jhs4n"/><path class="rk9uflb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-with-rolling-eyes" /></template>
<style>
.ix_3jhs4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.5 40c6.1 0 11-4.9 11-11c0-1.6-.4-3.2-1-4.6c-2.8-1.3-6.3-2-10-2s-7.2.8-10 2c-.6 1.4-1 2.9-1 4.6c0 6.1 4.9 11 11 11");
}

.r3rddk09k {
  fill: var(--svg-color--fff, #fff);
  d: path("M45.5 40c6.1 0 11-4.9 11-11c0-1.6-.4-3.2-1-4.6c-2.8-1.3-6.3-2-10-2s-7.2.8-10 2c-.6 1.4-1 2.9-1 4.6c0 6.1 4.9 11 11 11");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.rk9uflb7l {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M19 22.4c-.5.7-.8 1.6-.8 2.5c0 2.5 2 4.5 4.5 4.5s4.5-2 4.5-4.5c0-.4-.1-.7-.1-1c-2.4-.9-5.2-1.5-8.1-1.5m21.6 24.9c-5.4-2.5-11.8-2.5-17.2 0c-1.4.7.3 4.2 1.6 3.5c3.6-1.7 8.9-2.3 13.9 0c1.4.6 3.1-2.8 1.7-3.5");
}

.sd-z9ccws {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M46 22.4c-.5.7-.8 1.6-.8 2.5c0 2.5 2 4.5 4.5 4.5s4.5-2 4.5-4.5c0-.4-.1-.7-.1-1c-2.4-.9-5.2-1.5-8.1-1.5");
}

</style>
