<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG6MohjlAE" x1="-.102" x2="0" y1="-5.691" y2="-100.83" gradientTransform="matrix(1 0 0 .137 1.07 29.95)" gradientUnits="userSpaceOnUse" spreadMethod="reflect"><stop offset="0" class="x1ob552sn"/><stop offset=".13" class="fsmu1sbuy"/><stop offset=".82" class="o80xxfr4u"/></linearGradient><linearGradient id="SVGvSh2Sd0W" x1="12.01" x2="101.35" gradientTransform="matrix(.147 0 0 1 1.07 29.95)" gradientUnits="userSpaceOnUse" spreadMethod="reflect"><stop offset="0" class="la1q1sbut"/><stop offset=".26" class="q93r1ebbj"/><stop offset=".82" class="pd7g5l3ge"/></linearGradient></defs><path class="ows64lbdn"/><path fill="url(#SVG6MohjlAE)" class="i_ak-bb0j"/><path fill="url(#SVGvSh2Sd0W)" class="vjz4swbsv"/><path class="akt9gg3lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-uiua" /></template>
<style>
.akt9gg3lv {
  d: path("M6.81 6.45c2.26-2.25 5.62-3.7 9.19-3.7c3.62 0 6.92 1.48 9.3 3.8l.27-.77C23.17 3.47 19.7 2 16 2S9.01 3.41 6.53 5.69zm20.11 2.03c1.48 2.14 2.34 4.72 2.34 7.52c0 7.32-5.93 13.25-13.25 13.25S2.76 23.32 2.76 16c0-2.87.89-5.49 2.44-7.66l-.27-.91C3.03 9.89 2 12.84 2 16c0 7.73 6.27 14 14 14s14-6.27 14-14c0-3.17-1.05-6.09-2.83-8.44z");
}

.fsmu1sbuy {
  stop-color: var(--svg-color--0f0, #0f0);
  stop-opacity: 0.65;
}

.i_ak-bb0j {
  d: path("M27.07 7.95c-1.9 6.7-5.9 17.8-11 17.7c-4.5 0-8.2-8.1-11-17.7c-6.5 8-.3 21.8 11 21.7c12.3-.2 16.8-13.8 11-21.7m-11-5.6c-5.3 0-8 2.6-9.4 3.7c1.1 3.1 4.7 12.6 9.4 12.7c4.7-.1 8.3-9.6 9.4-12.7c-1.4-1.1-4.1-3.7-9.4-3.7");
}

.la1q1sbut {
  stop-color: var(--svg-color--red, red);
}

.o80xxfr4u {
  stop-color: var(--svg-color--0f0, #0f0);
  stop-opacity: 0;
}

.ows64lbdn {
  fill: var(--svg-color--191e99, #191e99);
  d: path("M27.07 7.95c-1.9 6.7-5.9 17.8-11 17.7c-4.5 0-8.2-8.1-11-17.7c-6.5 8-.3 21.8 11 21.7c12.3-.2 16.8-13.8 11-21.7m-11-5.6c-5.3 0-8 2.6-9.4 3.7c1.1 3.1 4.7 12.6 9.4 12.7c4.7-.1 8.3-9.6 9.4-12.7c-1.4-1.1-4.1-3.7-9.4-3.7");
}

.pd7g5l3ge {
  stop-color: var(--svg-color--red, red);
  stop-opacity: 0;
}

.q93r1ebbj {
  stop-color: var(--svg-color--red, red);
  stop-opacity: 0.55;
}

.vjz4swbsv {
  d: path("M27.07 7.95c-1.9 6.7-6 17.7-11 17.7c-4.5 0-8.2-8.1-11-17.7c-6.5 8-.3 21.8 11 21.7c12.3-.2 16.8-13.8 11-21.7m-11-5.6c-5.3 0-8 2.6-9.4 3.7c1.1 3.1 4.7 12.6 9.4 12.7c4.7-.1 8.3-9.6 9.4-12.7c-1.4-1.1-4.1-3.7-9.4-3.7");
}

.x1ob552sn {
  stop-color: var(--svg-color--0f0, #0f0);
}

</style>
