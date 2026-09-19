<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="skb4s__je"/><path class="fckbcwb_b"/><path class="dl528ywfs"/><path class="z5w38gzfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:fork-and-knife-with-plate" /></template>
<style>
.dl528ywfs {
  fill: var(--svg-color--fff, #fff);
  d: path("M32.7 46.9c8.6 0 15.7-6.6 16-14.9v.5c0 8.5-7.2 15.5-16 15.5s-16-6.9-16-15.5V32c.4 8.3 7.4 14.9 16 14.9");
}

.fckbcwb_b {
  fill: var(--svg-color--acb8bf, #acb8bf);
  d: path("M32.7 17.1c-8.6 0-15.7 6.6-16 14.9v-.5c0-8.5 7.2-15.5 16-15.5s16 6.9 16 15.5v.5c-.3-8.3-7.3-14.9-16-14.9");
}

.skb4s__je {
  cx: 32.8px;
  cy: 32px;
  r: 22px;
  fill: var(--svg-color--dae3ea, #dae3ea);
}

.z5w38gzfo {
  fill: var(--svg-color--acb8bf, #acb8bf);
  d: path("M3.5 7.4c.2-.9.7 0 .7 0s.2 9.7 1.2 9.8c1.1.2.3-10 1.6-10.2c1.2-.2.5 10.4 1.6 10.3s1.3-9.9 1.3-9.9s.5-.9.7 0c2.9 11.5.6 16.2.6 16.2s-.4 1-1.4 1c-.1 0 0 27.3 0 31c0 1.8-5.5 1.7-5.5 0c0-3.7.1-31 0-31c-1 0-1.4-1-1.4-1s-2.4-4.7.6-16.2M55.6 7c1.2 0 6.4 3.7 6.4 17.5c0 4.4-2.4 4.4-2.4 7.2v24.6S57 58 55 56.1V7.4s0-.4.6-.4");
}

</style>
