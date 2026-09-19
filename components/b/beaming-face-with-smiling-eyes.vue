<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="gkr2ukjrj"/><path class="ikmcaobtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:beaming-face-with-smiling-eyes" /></template>
<style>
.gkr2ukjrj {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M28.5 27.9c-1.9-5.1-4.7-7.7-7.5-7.7s-5.6 2.6-7.5 7.7c-.2.5.8 1.4 1.3.9c1.8-1.9 4-2.7 6.2-2.7s4.4.8 6.2 2.7c.6.6 1.5-.4 1.3-.9m21.9 0c-1.9-5.1-4.7-7.7-7.5-7.7s-5.6 2.6-7.5 7.7c-.2.5.8 1.4 1.3.9c1.8-1.9 4-2.7 6.2-2.7s4.4.8 6.2 2.7c.5.6 1.5-.4 1.3-.9m3.6 9.5c0-.8-.6-1.8-2.4-2.1C47.2 34.7 40.5 34 32 34s-15.2.7-19.6 1.3c-1.7.3-2.4 1.3-2.4 2.1C10 47 13.5 50 27.8 50h8.4C50.5 50 54 47 54 37.4");
}

.ikmcaobtw {
  fill: var(--svg-color--fff, #fff);
  d: path("M48.9 38.2c.2-.5-.1-1-.5-1.1c0 0-7.4-1.1-16.4-1.1s-16.4 1.1-16.4 1.1c-.5.1-.7.6-.5 1.1l1.1 2.9c.2.5.8.9 1.3.9h29.1c.5 0 1.1-.4 1.3-.9zM32 48c6.4 0 15.5 0 15.2-2.1c0-.4-.1-.8-.3-1.3s-.3-.7-1.4-.7H18.4c-1.1 0-1.2.1-1.4.7c-.1.5-.2.9-.3 1.3C16.5 48 25.6 48 32 48");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
