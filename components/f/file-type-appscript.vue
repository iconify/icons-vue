<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="hrcfc5buf"/><circle class="pns4aob3g"/><rect transform="rotate(-144 14.99 19.03)" class="e2iqol_wv"/><circle class="jnpicbbrp"/><rect transform="rotate(72 19.19 15.96)" class="b0x6sgbww"/><circle class="tqjot-qqb"/><rect transform="rotate(-72 24.31 15.96)" class="oqdql2w1s"/><circle class="ezb6a2b2f"/><circle class="yu5oottbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-appscript" /></template>
<style>
.b0x6sgbww {
  width: 23.31px;
  height: 6.69px;
  x: 7.53px;
  y: 12.62px;
  fill: var(--svg-color--34a853, #34a853);
  rx: 3.34px;
}

.e2iqol_wv {
  width: 23.31px;
  height: 6.69px;
  x: 3.33px;
  y: 15.68px;
  fill: var(--svg-color--fbbc04, #fbbc04);
  rx: 3.34px;
}

.ezb6a2b2f {
  cx: 21.76px;
  cy: 23.85px;
  r: 1.67px;
  fill: var(--svg-color--fff, #fff);
}

.hrcfc5buf {
  width: 23.31px;
  height: 6.69px;
  x: 1.72px;
  y: 20.56px;
  fill: var(--svg-color--ea4335, #ea4335);
  rx: 3.34px;
}

.jnpicbbrp {
  cx: 8.22px;
  cy: 14.09px;
  r: 1.67px;
  fill: var(--svg-color--fff, #fff);
}

.oqdql2w1s {
  width: 23.31px;
  height: 6.69px;
  x: 12.66px;
  y: 12.62px;
  fill: var(--svg-color--4285f4, #4285f4);
  rx: 3.34px;
}

.pns4aob3g {
  cx: 5.09px;
  cy: 23.91px;
  r: 1.67px;
  fill: var(--svg-color--fff, #fff);
}

.tqjot-qqb {
  cx: 16.62px;
  cy: 8.08px;
  r: 1.67px;
  fill: var(--svg-color--fff, #fff);
}

.yu5oottbd {
  cx: 26.92px;
  cy: 7.99px;
  r: 1.67px;
  fill: var(--svg-color--fff, #fff);
}

</style>
