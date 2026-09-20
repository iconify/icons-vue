<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r3ipxnbox"/><path class="w_j76qb_t"/><path class="ki-i2fb9q"/><path class="lra7tvy5h"/><ellipse class="fj3i_t73l"/><path class="hepizzbtj"/><ellipse class="o8zfk7bkw"/><path class="pf8pe6bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:low-battery" /></template>
<style>
.fj3i_t73l {
  cx: 18px;
  cy: 3px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 10px;
  ry: 2px;
}

.hepizzbtj {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M14 1v1.5c0 .552 1.791 1 4 1s4-.448 4-1V1z");
}

.ki-i2fb9q {
  fill: var(--svg-color--ff475c, #ff475c);
  d: path("M30 24.7c0 1.657-5.373 3.3-12 3.3S6 26.357 6 24.7S11.373 22 18 22s12 1.043 12 2.7");
}

.lra7tvy5h {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M21.956 12.788c.091.544-.321 1.066-.922 1.136c-.676.079-1.355.121-2.035.147V16a1 1 0 0 1-2 0v-1.93a26 26 0 0 1-2.035-.147c-.601-.07-1.012-.591-.922-1.136a1.04 1.04 0 0 1 1.152-.851c.6.07 1.202.109 1.804.133V10a1 1 0 0 1 2 0v2.07a25 25 0 0 0 1.804-.133a1.04 1.04 0 0 1 1.154.851M26.651 3c-1.73-.597-4.952-1-8.651-1s-6.921.403-8.651 1H8v1c0 1.105 4.477 2 10 2s10-.895 10-2V3z");
}

.o8zfk7bkw {
  cx: 18px;
  cy: 1px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 4px;
  ry: 1px;
}

.pf8pe6bgu {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.478 32.522c-.609-.067-1.026-.59-.934-1.134a1.05 1.05 0 0 1 1.153-.854c1.531.168 3.076.168 4.607 0a1.05 1.05 0 0 1 1.153.854c.091.544-.326 1.067-.934 1.134a23 23 0 0 1-5.045 0");
}

.r3ipxnbox {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M18 0C11.373 0 6 1.343 6 3v29.7h24V3c0-1.657-5.373-3-12-3");
}

.w_j76qb_t {
  fill: var(--svg-color--d42544, #d42544);
  d: path("M6 24.7v8c0 1.657 5.373 3.3 12 3.3s12-1.643 12-3.3v-8z");
}

</style>
