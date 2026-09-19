<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="y6-qxybqn"/><circle class="ysndbbbeh"/><path class="rt3i-ac0i"/><path class="by866tujd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:control-knobs" /></template>
<style>
.by866tujd {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M63.4 43.4c1.1-6.1.6-12.5-1.6-18.3s-6.1-11-11.2-14.7c-5-3.7-11.2-5.9-17.5-6.2c-6.3-.2-12.6 1.4-18 4.8c-5.3 3.3-9.7 8.3-12.3 14.1S-.6 35.5.4 41.7c.7 4.3 2.3 8.4 4.7 12.1h3.2C6 50.4 4.5 46.6 3.8 42.6c-.9-5.3-.3-10.8 1.6-15.7c2-5 5.4-9.3 9.7-12.4s9.5-4.9 14.7-5c5.3-.2 10.5 1.3 14.9 4.1s7.9 7 9.9 11.8c2.1 4.8 2.6 10.2 1.7 15.3c-.9 5-3.2 9.5-6.7 13.2h9.9c1.9-3.2 3.2-6.8 3.9-10.5");
}

.rt3i-ac0i {
  fill: var(--svg-color--fff, #fff);
  d: path("M31.6 33.7c0 .8-.6 1.4-1.4 1.4s-1.4-.6-1.4-1.4V18.4c0-.8.6-1.4 1.4-1.4s1.4.6 1.4 1.4z");
}

.y6-qxybqn {
  cx: 30.3px;
  cy: 36.7px;
  r: 23.1px;
  fill: var(--svg-color--7d8993, #7d8993);
}

.ysndbbbeh {
  cx: 30.3px;
  cy: 38.3px;
  r: 20.2px;
  fill: var(--svg-color--5b636b, #5b636b);
}

</style>
