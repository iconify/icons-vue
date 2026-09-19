<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<defs><linearGradient id="SVG9W6TDc3p" x1="31.902" x2="32.494" y1="35.512" y2="33.945" gradientTransform="matrix(1 0 0 -1 0 66)" gradientUnits="userSpaceOnUse"><stop class="gr1x3ab4p"/><stop offset="1" class="la1q1sbut"/></linearGradient></defs><path class="swv2lybrj"/><path class="mh79h9x1l"/><path class="dvf955nmx"/><path class="cvqsj7bpu"/><path fill="url(#SVG9W6TDc3p)" class="zoddf_bxn"/><path class="dqu3olw1y"/><path class="dzosk_bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-nicaragua" /></template>
<style>
.cvqsj7bpu {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("m28.9 30.4l-3.2 5h12.6l-3.2-5z");
}

.dqu3olw1y {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M37.6 34.4c-1-.1-1.9-1-2.1-1.9c0 0-.1-.1-.2-.1c-.2 0-.2.1-.2.1c-.1.3-.3.7-.6 1c-.3-.3-.5-.7-.6-1c0 0-.1-.1-.2-.1c-.2 0-.2.1-.2.1c-.1.3-.3.7-.6 1c-.3-.3-.5-.7-.6-1c0 0-.1-.1-.2-.1s-.2.1-.2.1c-.1.3-.3.7-.6 1c-.3-.3-.5-.7-.6-1c0 0-.1-.1-.2-.1c-.2 0-.2.1-.2.1c-.1.3-.3.7-.6 1c-.3-.3-.5-.7-.6-1c0 0-.1-.1-.2-.1c-.2 0-.2.1-.2.1c-.3.9-1.2 2-2.3 2.1l-.5.7h12.4z");
}

.dvf955nmx {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("m32 25.3l-6.3 10.1h12.6z");
}

.dzosk_bkj {
  fill: var(--svg-color--dbb471, #dbb471);
  d: path("M32 23c-5 0-9 4-9 9s4 9 9 9s9-4 9-9s-4-9-9-9m0 16.5c-4.1 0-7.5-3.4-7.5-7.5s3.4-7.5 7.5-7.5s7.5 3.4 7.5 7.5s-3.4 7.5-7.5 7.5");
}

.gr1x3ab4p {
  stop-color: var(--svg-color--ff2a2a, #ff2a2a);
}

.la1q1sbut {
  stop-color: var(--svg-color--red, red);
}

.mh79h9x1l {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

.swv2lybrj {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2m0 60c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.zoddf_bxn {
  d: path("M33 31v-.4c0-.3-.2-.7-.5-1.1c-.2-.4-.5-.5-1-.2c-.2.1-.3.2-.4.5v.3s.2.1.3-.1c.1 0 .1-.1.1-.1c-.1 0-.1.1-.1.1c-.1.1-.2.2-.3.4s-.1.4-.1.5c0 0 .1.2.3.2c.2.1.3.2.4.3s.1.2.1.4c0 .1 0 .3.1.3s.2-.1.3-.2c0-.2.1-.3.1-.4c.1-.1.1-.1.3-.1c.1 0 .2 0 .2-.1v-.1c.2 0 .1-.1.2-.2");
}

</style>
