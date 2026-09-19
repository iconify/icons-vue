<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ifGAttb)" class="plblo7bjy"/><path fill="url(#ikZl8Sb)" class="t032u_bro"/><path fill="url(#iBsFwhb)" class="t032u_bro"/><path fill="url(#iv2XBGd)" class="jan7prb1q"/><path fill="url(#iW3FBgK)" class="sztonfbol"/><path fill="url(#i7ZY6jc)" class="sztonfbol"/><defs><linearGradient id="ifGAttb" x1="15.094" x2="18.219" y1="16.656" y2="18.313" gradientUnits="userSpaceOnUse"><stop offset=".324" class="engp9bcof"/><stop offset=".609" class="ahzkdibln"/><stop offset=".88" class="b8qnwtb5f"/></linearGradient><linearGradient id="ikZl8Sb" x1="20.891" x2="23.309" y1="7.422" y2="8.786" gradientUnits="userSpaceOnUse"><stop offset=".272" class="dhnnhdbpd"/><stop offset=".615" class="q8jk94bvq"/><stop offset=".964" class="hc3rtcb5k"/></linearGradient><linearGradient id="iv2XBGd" x1="9.625" x2="12.125" y1="16.007" y2="16.625" gradientUnits="userSpaceOnUse"><stop offset=".324" class="engp9bcof"/><stop offset=".609" class="ahzkdibln"/><stop offset=".88" class="b8qnwtb5f"/></linearGradient><linearGradient id="iW3FBgK" x1="12.313" x2="14.891" y1="5.082" y2="5.672" gradientUnits="userSpaceOnUse"><stop offset=".272" class="dhnnhdbpd"/><stop offset=".615" class="qvnrg7w1p"/><stop offset=".964" class="hc3rtcb5k"/></linearGradient><radialGradient id="iBsFwhb" cx="0" cy="0" r="1" gradientTransform="rotate(95.711 9.556 13.608)scale(.78515 .92661)" gradientUnits="userSpaceOnUse"><stop class="az4zub7qk"/><stop offset="1" class="a1e4dtbys"/></radialGradient><radialGradient id="i7ZY6jc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 .65625 -.7848 -.03737 14.734 2.797)" gradientUnits="userSpaceOnUse"><stop class="d3c1-oa-w"/><stop offset="1" class="l11zvab1l"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chopsticks" /></template>
<style>
.a1e4dtbys {
  stop-color: var(--svg-color--5e5865, #5E5865);
  stop-opacity: 0;
}

.ahzkdibln {
  stop-color: var(--svg-color--d32c5d, #D32C5D);
}

.az4zub7qk {
  stop-color: var(--svg-color--655f6c, #655F6C);
}

.b8qnwtb5f {
  stop-color: var(--svg-color--de254c, #DE254C);
}

.d3c1-oa-w {
  stop-color: var(--svg-color--605b68, #605B68);
}

.dhnnhdbpd {
  stop-color: var(--svg-color--35303c, #35303C);
}

.engp9bcof {
  stop-color: var(--svg-color--b12a3c, #B12A3C);
}

.ft5dv1b6b {
  fill: none;
}

.hc3rtcb5k {
  stop-color: var(--svg-color--443c4f, #443C4F);
}

.jan7prb1q {
  d: path("m7.024 28.934l5.78-25.95c.11-.45.45-.81.9-.93c.94-.25 1.8.61 1.55 1.55l-6.54 25.75a.87.87 0 0 1-1.69-.42");
}

.l11zvab1l {
  stop-color: var(--svg-color--625d69, #625D69);
  stop-opacity: 0;
}

.plblo7bjy {
  d: path("m9.844 28.714l12.3-23.57c.22-.41.65-.67 1.11-.67c.97 0 1.58 1.05 1.1 1.9l-12.98 23.19a.89.89 0 0 1-.76.44c-.66 0-1.08-.7-.77-1.29");
}

.q8jk94bvq {
  stop-color: var(--svg-color--544a61, #544A61);
}

.qvnrg7w1p {
  stop-color: var(--svg-color--544a62, #544A62);
}

.sztonfbol {
  d: path("m14.094 8.164l1.16-4.57c.25-.94-.61-1.8-1.55-1.55c-.45.12-.8.48-.9.93l-1.06 4.78c.79.11 1.58.25 2.35.41");
}

.t032u_bro {
  d: path("m21.884 10.794l2.47-4.41c.49-.84-.12-1.9-1.1-1.9c-.47 0-.89.26-1.11.67l-2.45 4.7c.74.28 1.47.6 2.19.94");
}

</style>
