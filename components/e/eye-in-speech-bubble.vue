<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l1rd1eddx"/><circle class="s4ggnublm"/><circle class="r_nlxzkjd"/><path class="jyflouxzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:eye-in-speech-bubble" /></template>
<style>
.jyflouxzu {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("m86.73 102.79l22.12 10.56c2.53 1.21 5.24-1.29 4.24-3.91l-8.4-22.01z");
}

.l1rd1eddx {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M64 19.39c-29.26 0-52.43 25.97-61.74 38.24a10.366 10.366 0 0 0 0 12.55c9.31 12.27 32.48 38.24 61.74 38.24s52.43-25.97 61.74-38.24c2.82-3.71 2.82-8.83 0-12.55C116.43 45.37 93.26 19.39 64 19.39");
}

.r_nlxzkjd {
  cx: 64px;
  cy: 63.91px;
  r: 16.05px;
  fill: var(--svg-color--64878e, #64878e);
}

.s4ggnublm {
  cx: 64px;
  cy: 63.91px;
  r: 28.3px;
  fill: var(--svg-color--fff, #fff);
}

</style>
