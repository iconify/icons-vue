<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gocsj1byk"/><path class="sc_foibgs"/><path class="ckgyu_9-j"/><path class="t4uuumbwj"/><path class="qlgdd7bxd"/><path class="odkiscbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:closed-book" /></template>
<style>
.ckgyu_9-j {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M33.7 5L64 34.5l-35.8 14l-23-35.8z");
}

.gocsj1byk {
  fill: var(--svg-color--962c2c, #962c2c);
  d: path("m55 35.1l7.5 7.4l-33.3 15.9s-4.4 2-6.5-1.2C14.5 44.4 55 35.1 55 35.1");
}

.odkiscbxe {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M22.7 57.2c-3.5-7.3 5.5-8.6 5.5-8.6l-23-35.9S0 12.6 0 18c0 2.2 1 3.9 1 3.9z");
}

.qlgdd7bxd {
  fill: var(--svg-color--94989b, #94989b);
  d: path("m61 38l-21.1 8.6l20.8-9.5zm-.3 2.6l-22.5 9.3l22.1-10.3zm.2 1.4L32.2 54.4l28.3-13.3z");
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
