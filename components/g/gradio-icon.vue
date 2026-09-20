<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":224};
const content = `<defs><linearGradient id="SVGssQ2Xbjz" x1="-6.452%" x2="85.236%" y1="49.784%" y2="49.784%"><stop offset="0%" class="vlp_fac0s"/><stop offset="100%" class="lggn3pbqj"/></linearGradient><linearGradient id="SVGFlaRCblf" x1="106.079%" x2="14.268%" y1="49.784%" y2="49.784%"><stop offset="0%" class="vlp_fac0s"/><stop offset="100%" class="lggn3pbqj"/></linearGradient><linearGradient id="SVGru2OOiqc" x1="-12.871%" x2="169.796%" y1="75.863%" y2="74.878%"><stop offset="0%" class="vlp_fac0s"/><stop offset="100%" class="lggn3pbqj"/></linearGradient></defs><path fill="url(#SVGssQ2Xbjz)" class="jclc-wgtl"/><path fill="url(#SVGFlaRCblf)" class="ufxtx8mph"/><path fill="url(#SVGru2OOiqc)" class="q6r1i_bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:gradio-icon" /></template>
<style>
.jclc-wgtl {
  d: path("M119.871 64.78a16.35 16.35 0 0 1 16.258 0l111.654 64c10.956 6.28 10.956 22.083 0 28.363l-111.654 64a16.35 16.35 0 0 1-16.258 0l-111.654-64c-10.956-6.28-10.956-22.083 0-28.364zm8.126 33.014l-78.783 45.164l78.783 45.155l78.784-45.155z");
}

.lggn3pbqj {
  stop-color: var(--svg-color--f97700, #f97700);
}

.q6r1i_bko {
  d: path("m120.19 64.755l16.174 28.412l-111.93 63.723l-16.175-28.412z");
}

.ufxtx8mph {
  d: path("M119.871 2.165a16.35 16.35 0 0 1 16.258 0l111.654 64c10.956 6.28 10.956 22.083 0 28.363l-111.654 64a16.35 16.35 0 0 1-16.258 0l-111.654-64c-10.956-6.28-10.956-22.083 0-28.363zm8.126 33.015L49.214 80.343l78.783 45.156l78.784-45.156z");
}

.vlp_fac0s {
  stop-color: var(--svg-color--f9d100, #f9d100);
}

</style>
