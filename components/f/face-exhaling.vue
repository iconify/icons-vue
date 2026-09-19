<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path stroke="url(#i0sO7zd)" class="bhyq7fbxk"/><path stroke="url(#i1meywO)" class="r4of4uf5w"/><path fill="url(#ic8Opfd)" class="bwm2icv6q"/><g filter="url(#ipeFt2c)"><path clip-rule="evenodd" class="nhxps-mie"/></g><path fill="url(#iXP0zbe)" class="q18ieqb6s"/><path fill="url(#iuOZ0me)" stroke="url(#i7dAFyd)" class="s_3zh_5pp"/><path fill="url(#iYN334c)" stroke="url(#iYNQF3O)" class="bwb72p55e"/><path fill="url(#ifBlMGc)" class="lo-ozbcpj"/><g filter="url(#iLvFiCc)"><path stroke="url(#ihoEsBe)" class="atmrpwbzv"/></g><g filter="url(#ieo8KOd)"><circle class="comxoscsd"/></g><path stroke="url(#ibP05he)" class="ovdk3xbkl"/><path stroke="url(#iNxwQEc)" class="svy0j65lh"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="ic8Opfd" cx="0" cy="0" r="1" gradientTransform="rotate(-90 19.89 3.92)scale(4.88889)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="iuOZ0me" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66669 3 -3 -1.66669 19.667 26)" gradientUnits="userSpaceOnUse"><stop class="msjazp67e"/><stop offset=".624" class="rhb3_8bdi"/><stop offset="1" class="rts9zdbmk"/></radialGradient><radialGradient id="i7dAFyd" cx="0" cy="0" r="1" gradientTransform="matrix(-2 1 -.6672 -1.33441 20.667 26)" gradientUnits="userSpaceOnUse"><stop class="meefbyi2a"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iYN334c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66669 3 -3 -1.66669 13.667 26)" gradientUnits="userSpaceOnUse"><stop class="msjazp67e"/><stop offset=".624" class="rhb3_8bdi"/><stop offset="1" class="rts9zdbmk"/></radialGradient><radialGradient id="iYNQF3O" cx="0" cy="0" r="1" gradientTransform="matrix(-2 1 -.6672 -1.33441 14.667 26)" gradientUnits="userSpaceOnUse"><stop class="meefbyi2a"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="ifBlMGc" cx="0" cy="0" r="1" gradientTransform="rotate(119.055 .704 18.251)scale(5.14781)" gradientUnits="userSpaceOnUse"><stop class="msjazp67e"/><stop offset=".624" class="rhb3_8bdi"/><stop offset="1" class="rts9zdbmk"/></radialGradient><radialGradient id="ihoEsBe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 3.5 -2.33523 3.00243 13.5 27)" gradientUnits="userSpaceOnUse"><stop class="gk9jh0kvm"/><stop offset="1" class="dp4m0zbft"/></radialGradient><linearGradient id="i0sO7zd" x1="11.2" x2="10.965" y1="13.75" y2="15.161" gradientUnits="userSpaceOnUse"><stop class="d-sg2f4zs"/><stop offset="1" class="hvts7mbyo"/></linearGradient><linearGradient id="i1meywO" x1="23.2" x2="22.965" y1="13.75" y2="15.161" gradientUnits="userSpaceOnUse"><stop class="d-sg2f4zs"/><stop offset="1" class="hvts7mbyo"/></linearGradient><linearGradient id="iXP0zbe" x1="17.5" x2="14.5" y1="24.5" y2="24.5" gradientUnits="userSpaceOnUse"><stop class="tjecpubxz"/><stop offset="1" class="g3rev0b5h"/></linearGradient><linearGradient id="ibP05he" x1="6.833" x2="6.833" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iNxwQEc" x1="25.167" x2="25.167" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><filter id="ipeFt2c" width="12.048" height="11.74" x="8" y="19.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_2" stdDeviation="1"/></filter><filter id="iLvFiCc" width="8" height="8" x="12" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_2" stdDeviation=".5"/></filter><filter id="ieo8KOd" width="6" height="6" x="14" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_2" stdDeviation="1"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-exhaling" /></template>
<style>
.atmrpwbzv {
  d: path("M18.5 28a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0Z");
}

.bhyq7fbxk {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14s1 1 3 1s3-1 3-1");
}

.bwb72p55e {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.75 27a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0Z");
}

.bwm2icv6q {
  d: path("M15.97 22.92a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.comxoscsd {
  cx: 17px;
  cy: 27px;
  r: 1px;
  fill: var(--svg-color--fff, #fff);
}

.d-sg2f4zs {
  stop-color: var(--svg-color--52383e, #52383E);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.dp4m0zbft {
  stop-color: var(--svg-color--c6aabe, #C6AABE);
  stop-opacity: 0;
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g3rev0b5h {
  stop-color: var(--svg-color--dcbad5, #DCBAD5);
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.gk9jh0kvm {
  stop-color: var(--svg-color--ccb5c6, #CCB5C6);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hvts7mbyo {
  stop-color: var(--svg-color--432a35, #432A35);
}

.ii_r00eab {
  stop-color: var(--svg-color--524049, #524049);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.lo-ozbcpj {
  d: path("M16 31a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.meefbyi2a {
  stop-color: var(--svg-color--fef7ff, #FEF7FF);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.msjazp67e {
  stop-color: var(--svg-color--ece1f5, #ECE1F5);
}

.nhxps-mie {
  fill: var(--svg-color--e4694e, #E4694E);
  fill-rule: evenodd;
  d: path("M14.56 21.47S13.95 24.06 12 25a2 2 0 1 0 1.684.92h3.266s1.37-.76 1.05-.92c-2-1.02-2.61-3.53-2.61-3.53a.515.515 0 0 0-.83 0");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ovdk3xbkl {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 9.5c.333-1 1.6-3 4-3");
}

.q18ieqb6s {
  d: path("M13 25c1.95-.94 2.56-3.53 2.56-3.53c.21-.28.62-.28.83 0c0 0 .61 2.51 2.61 3.53c.32.16-1.05.92-1.05.92h-3.98z");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.r4of4uf5w {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14s1 1 3 1s3-1 3-1");
}

.rhb3_8bdi {
  stop-color: var(--svg-color--eac6ff, #EAC6FF);
}

.rts9zdbmk {
  stop-color: var(--svg-color--f595ff, #F595FF);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s_3zh_5pp {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M20.75 27a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0Z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.svy0j65lh {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.5 9.5c-.333-1-1.6-3-4-3");
}

.tjecpubxz {
  stop-color: var(--svg-color--faeef9, #FAEEF9);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zg8znn0_h {
  stop-color: var(--svg-color--4a2c42, #4A2C42);
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
