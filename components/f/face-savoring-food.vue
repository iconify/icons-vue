<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iMQWSGb)" class="mc2zb0bvp"><path class="bo-hfpbkv"/></g><g filter="url(#iAkM7wb)" class="mc2zb0bvp"><path class="a79h18b3f"/></g><path class="kj167yb9b"/><g filter="url(#izZJlec)" class="qfgt6tb2e"><path class="ca3x0hbrn"/></g><path class="ij5txvb3z"/><g filter="url(#i1PyEKJ)" class="qfgt6tb2e"><path class="ti57i9b9x"/></g><path fill="url(#i4anlBy)" class="q2qq0q8dp"/><path fill="url(#iuZchqe)" class="z8kowybds"/><path stroke="url(#id0J2Fe)" class="s5itvfb9z"/><path fill="url(#iKPNJ4c)" clip-rule="evenodd" class="oz0wracjg"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="i4anlBy" cx="0" cy="0" r="1" gradientTransform="rotate(129.007 5.449 13.952)scale(7.72137 5.2163)" gradientUnits="userSpaceOnUse"><stop class="g2l7rnbzu"/><stop offset="1" class="vw5q-acih"/></radialGradient><radialGradient id="id0J2Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6 -9.18387 0 16 14)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="opsjn_43s"/><stop offset=".703" class="vb6ihbceu"/><stop offset="1" class="opsjn_43s"/><stop offset="1" class="opsjn_43s"/></radialGradient><radialGradient id="iKPNJ4c" cx="0" cy="0" r="1" gradientTransform="matrix(1.33333 2 -6 4 22.667 21)" gradientUnits="userSpaceOnUse"><stop class="xk3w8rbbu"/><stop offset="1" class="ps1t-6nit"/></radialGradient><filter id="iMQWSGb" width="10" height="7" x="5" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_15" stdDeviation=".75"/></filter><filter id="iAkM7wb" width="10.001" height="7" x="16" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_15" stdDeviation=".75"/></filter><filter id="izZJlec" width="8.75" height="5.75" x="6.375" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_15" stdDeviation=".75"/></filter><filter id="i1PyEKJ" width="8.75" height="5.75" x="17.375" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_15" stdDeviation=".75"/></filter><linearGradient id="iuZchqe" x1="23.5" x2="20.383" y1="22.5" y2="16.006" gradientUnits="userSpaceOnUse"><stop class="p34uj-wux"/><stop offset=".341" class="nop1e4biw"/><stop offset="1" class="ne72a4bmy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-savoring-food" /></template>
<style>
.a79h18b3f {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 11.5s.5-2 2.5-2s2.5 2 2.5 2");
}

.bo-hfpbkv {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 11.5s.25-2 2.5-2s2.5 2 2.5 2");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ca3x0hbrn {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.25 10.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g2l7rnbzu {
  stop-color: var(--svg-color--f63711, #F63711);
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.ij5txvb3z {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 11s.5-2 2.5-2s2.5 2 2.5 2");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kj167yb9b {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11s.25-2 2.5-2s2.5 2 2.5 2");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.ne72a4bmy {
  stop-color: var(--svg-color--ff278e, #FF278E);
}

.nop1e4biw {
  stop-color: var(--svg-color--ff2375, #FF2375);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.opsjn_43s {
  stop-color: var(--svg-color--4e2553, #4E2553);
}

.oz0wracjg {
  fill-rule: evenodd;
  d: path("m18.176 22.176l.192.192a3.734 3.734 0 0 0 6.087-4.076l-.267-.641A4 4 0 0 0 22 17c-.424 0-.832.066-1.215.188l-.756.33a4 4 0 0 0-1.854 4.657");
}

.p34uj-wux {
  stop-color: var(--svg-color--d40f31, #D40F31);
}

.ps1t-6nit {
  stop-color: var(--svg-color--ff7291, #FF7291);
  stop-opacity: 0;
}

.q2qq0q8dp {
  d: path("M11.62 18.5h6.48l5.4 3l-3.78 8L10 26z");
}

.qfgt6tb2e {
  opacity: var(--svg-opacity--0-26, 0.26);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s5itvfb9z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 16c.5.667 2.5 2.5 7 2.5s6.5-1.833 7-2.5");
}

.ti57i9b9x {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.25 10.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.vb6ihbceu {
  stop-color: var(--svg-color--5b4852, #5B4852);
}

.vw5q-acih {
  stop-color: var(--svg-color--e24a2c, #E24A2C);
  stop-opacity: 0;
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.xk3w8rbbu {
  stop-color: var(--svg-color--ff7291, #FF7291);
}

.z8kowybds {
  d: path("M18.368 22.368L15.5 19.5l8-3.5l.955 2.292a3.734 3.734 0 0 1-6.087 4.076");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
