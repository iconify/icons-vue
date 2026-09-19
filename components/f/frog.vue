<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDJ8Owg)" class="bygth95pe"/><path fill="url(#iDHXFxc)" class="bygth95pe"/><path fill="url(#iFwY2gc)" class="bygth95pe"/><path class="wl6k89f4i"/><path fill="url(#iXRBske)" class="hpripvbpd"/><path class="qt8guro8u"/><path fill="url(#iOTN65c)" class="z7-4yyeuh"/><path class="uj_sjsi8c"/><path fill="url(#iTxYsBd)" class="xs718_bbi"/><defs><radialGradient id="iDJ8Owg" cx="0" cy="0" r="1" gradientTransform="matrix(-21.625 1.12424 -1.21066 -23.28735 22.375 16)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="s74r6lwlz"/><stop offset="1" class="zm-ajfbir"/></radialGradient><radialGradient id="iDHXFxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -2.65625 3.88918 2.19624 11.125 7.781)" gradientUnits="userSpaceOnUse"><stop class="l0ek3-uea"/><stop offset="1" class="s81pkknuo"/></radialGradient><radialGradient id="iFwY2gc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78121 -4.21877 5.53073 2.33513 23.782 8.656)" gradientUnits="userSpaceOnUse"><stop class="l0ek3-uea"/><stop offset="1" class="s81pkknuo"/></radialGradient><radialGradient id="iXRBske" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18751 2.06249 -1.0725 -1.6575 12 7.125)" gradientUnits="userSpaceOnUse"><stop class="tg07-ljnl"/><stop offset="1" class="i2a37hb6j"/></radialGradient><radialGradient id="iOTN65c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18751 2.06249 -1.0725 -1.6575 25 7.126)" gradientUnits="userSpaceOnUse"><stop class="tg07-ljnl"/><stop offset="1" class="i2a37hb6j"/></radialGradient><linearGradient id="iTxYsBd" x1="16" x2="16" y1="41.875" y2="18.125" gradientUnits="userSpaceOnUse"><stop offset=".513" class="qsvyo0b7a"/><stop offset=".605" class="obsxpdexl"/><stop offset="1" class="jc5vk4p_i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:frog" /></template>
<style>
.bygth95pe {
  d: path("M27.48 10.841c.34-.73.53-1.54.52-2.4a5.527 5.527 0 0 0-5.38-5.44a5.5 5.5 0 0 0-5.57 4.73c-.02.15-.15.27-.31.27h-1.49c-.16 0-.29-.12-.31-.27a5.49 5.49 0 0 0-5.56-4.73c-2.95.07-5.34 2.48-5.38 5.43c-.01.86.18 1.68.52 2.4c.15.33.1.72-.13 1A10.5 10.5 0 0 0 2 18.501c0 5.8 4.7 10.5 10.5 10.5h7c5.8 0 10.5-4.7 10.5-10.5c0-2.53-.9-4.85-2.39-6.67a.94.94 0 0 1-.13-.99");
}

.ft5dv1b6b {
  fill: none;
}

.hpripvbpd {
  d: path("M9.5 11a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

.i2a37hb6j {
  stop-color: var(--svg-color--3c2a4f, #3C2A4F);
}

.jc5vk4p_i {
  stop-color: var(--svg-color--ffe55d, #FFE55D);
}

.l0ek3-uea {
  stop-color: var(--svg-color--60eea4, #60EEA4);
}

.obsxpdexl {
  stop-color: var(--svg-color--fa946c, #FA946C);
}

.qsvyo0b7a {
  stop-color: var(--svg-color--ff95f4, #FF95F4);
}

.qt8guro8u {
  fill: var(--svg-color--f8d41e, #F8D41E);
  d: path("M22.5 12a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.s74r6lwlz {
  stop-color: var(--svg-color--63f6ae, #63F6AE);
}

.s81pkknuo {
  stop-color: var(--svg-color--60eea4, #60EEA4);
  stop-opacity: 0;
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.uj_sjsi8c {
  fill: var(--svg-color--30223d, #30223D);
  d: path("M17.5 14.001a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m-3 0a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.wl6k89f4i {
  fill: var(--svg-color--f8d41e, #F8D41E);
  d: path("M9.5 12a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.xs718_bbi {
  d: path("M27.57 20.391c-1.18 0-2.27-.4-3.15-1.06a13.43 13.43 0 0 0-8.43-2.95c-3.22 0-6.17 1.12-8.49 3v-.01a5.2 5.2 0 0 1-3.1 1.02H2.17c.89 4.9 5.18 8.61 10.33 8.61h7c5.15 0 9.44-3.71 10.33-8.61z");
}

.z7-4yyeuh {
  d: path("M22.5 11.001a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

.zm-ajfbir {
  stop-color: var(--svg-color--4eb883, #4EB883);
}

</style>
