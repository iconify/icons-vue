<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":307};
const content = `<defs><linearGradient id="SVGT5pMRdgR" x1="-24.513%" x2="130.064%" y1="75.564%" y2="-56.513%"><stop offset="0%" class="b05635ejq"/><stop offset="86%" class="oh82heb9n"/></linearGradient><linearGradient id="SVGXClSKcBv" x1="104.596%" x2="48.252%" y1="100.586%" y2="48.39%"><stop offset="2%" class="pi_ldlgez"/><stop offset="86%" class="hfc5x2bkd"/></linearGradient></defs><path fill="url(#SVGT5pMRdgR)" class="bswzlibbr"/><path fill="url(#SVGXClSKcBv)" class="fdymbib9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:fogbugz-icon" /></template>
<style>
.b05635ejq {
  stop-color: var(--svg-color--ab68fc, #ab68fc);
}

.bswzlibbr {
  d: path("M89.976 306.862L256 161.802H90.258s-.246 139.468-.282 145.06");
}

.fdymbib9w {
  d: path("M166.059 0L0 161.803h165.32S166.024 4.22 166.06 0");
}

.hfc5x2bkd {
  stop-color: var(--svg-color--c6b1ff, #c6b1ff);
}

.oh82heb9n {
  stop-color: var(--svg-color--5521b3, #5521b3);
}

.pi_ldlgez {
  stop-color: var(--svg-color--aa69ff, #aa69ff);
}

</style>
