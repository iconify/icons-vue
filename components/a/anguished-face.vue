<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="i3dp_0b1d"/><circle class="xxje09bfz"/><path class="ced-gy0-d"/></g><path class="pvt3p-rwc"/><path class="qdm-iccpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:anguished-face" /></template>
<style>
.ced-gy0-d {
  d: path("M47.7 42c-1.7-3.6-5.9-6-15.7-6s-14 2.4-15.7 6c-.9 1.9.4 5 .4 5c1.6 3.9 1.4 5 15.3 5s13.6-1.1 15.3-5c0 0 1.3-3.1.4-5");
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.i3dp_0b1d {
  cx: 20.5px;
  cy: 26px;
  r: 5px;
}

.pvt3p-rwc {
  fill: var(--svg-color--fff, #fff);
  d: path("M43.4 41c.1-.3 0-.6-.2-.8c0 0-2.5-2.2-11.1-2.2S21 40.2 21 40.2c-.2.2-.3.5-.2.8l.2.6c.1.3.4.5.7.5h21c.3 0 .6-.2.7-.5z");
}

.qdm-iccpo {
  fill: var(--svg-color--917524, #917524);
  d: path("M52.2 16.7c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2.1-1.4 1.7m-28.7-3.3c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.2.2 2.3-.4 2.2");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.xxje09bfz {
  cx: 43.5px;
  cy: 26px;
  r: 5px;
}

</style>
