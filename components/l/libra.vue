<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="wrcz4abwi"/><circle class="txoe49b7c"/><path class="ho_qqfbkv"/><path class="ic2k4xb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:libra" /></template>
<style>
.ho_qqfbkv {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.3 3-17.9 6.4-23.1 14.3c-2 3-4.9 14.4-8.6 12.3c-3.9-2.3-3.1-9.5 2.6-18.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ic2k4xb0l {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M95.5 94.2h-63c-2.5 0-4.5-2-4.5-4.5s2-4.5 4.5-4.5h63c2.5 0 4.5 2 4.5 4.5s-2 4.5-4.5 4.5m-.1-25.1h-8.2c3.5-5.2 5.1-11.5 4.6-17.8C90.7 37.7 79.6 26.8 66 25.8c-.7 0-1.3-.1-2-.1c-7.5 0-14.5 2.9-19.7 8.2c-5.3 5.3-8.2 12.3-8.2 19.7c0 5.5 1.6 10.8 4.6 15.4H32c-2.5 0-4.6 2.1-4.6 4.6s2.1 4.6 4.6 4.6h20.3c1.6 0 2.9-1.3 2.9-2.9v-3.4c0-1-.5-1.9-1.4-2.5c-.1-.1-.2-.1-.2-.2c-5.9-3.9-9.1-10.8-8.3-17.9c1-8.5 7.9-15.4 16.5-16.3c.7-.1 1.5-.1 2.2-.1c10.3 0 18.8 8.4 18.8 18.8c0 6.3-3.1 12.1-8.4 15.6c-.1.1-.2.1-.2.2c-.8.5-1.4 1.5-1.4 2.5v3.4c0 1.6 1.3 2.9 2.9 2.9h19.8c2.5 0 4.6-2.1 4.6-4.6c-.1-2.6-2.2-4.6-4.7-4.6");
}

.txoe49b7c {
  cx: 60.1px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--66bb6a, #66bb6a);
}

.wrcz4abwi {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--388e3c, #388e3c);
}

</style>
