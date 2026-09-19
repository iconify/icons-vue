<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="jeunsn1yj"><path class="z3rbwkbyc"/><path class="pehykyvdr"/></g><path class="ij-k_zb4l"/><path class="hsu8gf4ga"/><path class="kvcpjrb9b"/><path class="mdfm2yf4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:building-construction" /></template>
<style>
.hsu8gf4ga {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m6.1 32l3.4 4h3.3l3.3-4zm43.3-3v3l-8.8-3H38v33h2.6v-6l8.8 3l-8.8 3H52V29zm0 27l-8.8-3l8.8-3zm-8.8-6v-6l8.8 3zm8.8-6l-8.8-3l8.8-3zm-8.8-6v-6l8.8 3z");
}

.ij-k_zb4l {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M12.8 28H9.5l-3.4 4h10z");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.kvcpjrb9b {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M54 27.2c0 1.5-1.2 2.8-2.6 2.8H38.6c-1.4 0-2.6-1.3-2.6-2.8V4.8C36 3.3 37.2 2 38.6 2h12.9C52.8 2 54 3.3 54 4.8z");
}

.mdfm2yf4r {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M38.9 15.2c0 1 .7 1.8 1.5 1.8h9c.8 0 1.5-.8 1.5-1.8V6.8c0-1-.7-1.8-1.5-1.8h-9c-.8 0-1.5.8-1.5 1.8zm12 9.8c0 1.1-.8 2-1.7 2h-8.6c-.9 0-1.7-.9-1.7-2v-4c0-1.1.8-2 1.7-2h8.6c.9 0 1.7.9 1.7 2z");
}

.pehykyvdr {
  d: path("M10.1 19h2v10h-2z");
}

.z3rbwkbyc {
  d: path("M12.1 37.3v-2.1h-1.9v3c0 .5.4 1 .9 1c1.6 0 2.8 1.3 2.8 3s-1.3 3-2.8 3s-2.8-1.3-2.8-3c0-.5-.4-1-.9-1s-.9.4-.9 1c0 2.7 2.1 4.9 4.7 4.9s4.7-2.2 4.7-4.9c-.1-2.5-1.7-4.5-3.8-4.9M58 8H11.9L6 20h52v-3h-2.1l2.1-3.9zm-47.4 9l2.3-4.8l2.5 4.8zm4.5-6h4.2l-2.1 3.9zm3.7 6l2.1-3.9L23 17zm3.7-6h4.2l-2.1 3.9zm3.7 6l2.1-3.9l2.1 3.9zm3.7-6h4.2L32 14.9zm3.7 6l2.1-3.9l2.1 3.9zm20.7-2.1L52.2 11h4.2z");
}

</style>
