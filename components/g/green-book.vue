<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ig6_xvbio"/><path class="sc_foibgs"/><path class="pa0n_1f8h"/><path class="t4uuumbwj"/><path class="dmufsnbdn"/><path class="edem0-i1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:green-book" /></template>
<style>
.dmufsnbdn {
  fill: var(--svg-color--94989b, #94989b);
  d: path("m61 38l-21.1 8.6l20.8-9.5zm-.3 2.6l-22.5 9.3l22.1-10.3zm.2 1.4L32.2 54.5l28.3-13.4z");
}

.edem0-i1p {
  fill: var(--svg-color--699635, #699635);
  d: path("M22.7 57.2c-3.5-7.3 5.5-8.6 5.5-8.6l-23-35.9S0 12.6 0 18c0 2.2 1 3.9 1 3.9z");
}

.ig6_xvbio {
  fill: var(--svg-color--547725, #547725);
  d: path("m55 35.1l7.5 7.4l-33.3 15.9s-4.4 2-6.5-1.2C14.5 44.4 55 35.1 55 35.1");
}

.pa0n_1f8h {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M33.7 5L64 34.5l-35.8 14l-23-35.8z");
}

.sc_foibgs {
  fill: var(--svg-color--d9e3e8, #d9e3e8);
  d: path("M28.4 49.1s-6.4 2.2-5.2 6.5c1.2 4.4 6.3 1.7 6.3 1.7l31.6-14.7s-1.8-4.7 1.4-7.8z");
}

.t4uuumbwj {
  fill: var(--svg-color--fff, #fff);
  d: path("m34.6 11.7l5.8 6.2l-21.7 7.8l-5.1-7.9z");
}

</style>
