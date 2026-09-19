<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cihs5mbop"/><path fill="url(#inQ9cJd)" class="napfbyb6j"/><path fill="url(#ilw8bEd)" class="napfbyb6j"/><path fill="url(#ikEqXgd)" class="napfbyb6j"/><path fill="url(#ia0KbHb)" class="napfbyb6j"/><path fill="url(#ibhv5xb)" class="iq2o_qbpb"/><path fill="url(#ioX9Mob)" class="iq2o_qbpb"/><path fill="url(#i7q9qsd)" class="iq2o_qbpb"/><path fill="url(#i7YvRFb)" class="iq2o_qbpb"/><g filter="url(#izTBgpe)"><path class="xnywgnbbf"/></g><path fill="url(#iPUzjib)" class="lvf4egbzb"/><path fill="url(#iudIWVb)" class="lvf4egbzb"/><path fill="url(#ipWwKge)" class="lvf4egbzb"/><path fill="url(#iZmfV8c)" class="lvf4egbzb"/><path fill="url(#im7Mqvj)" class="lvf4egbzb"/><g filter="url(#ikpIq1c)"><path class="aakc_on8w"/></g><path fill="url(#ily4DQe)" class="wf7f97g9x"/><path fill="url(#imiZwJe)" class="wf7f97g9x"/><path fill="url(#i8CKpnQ)" class="wf7f97g9x"/><path fill="url(#iTuPsLe)" class="wf7f97g9x"/><path fill="url(#iC8nzHd)" class="wf7f97g9x"/><path fill="url(#iyjsEMb)" class="wf7f97g9x"/><g filter="url(#idg9lNb)"><path stroke="url(#i7fuaoc)" class="jm0zesbdo"/></g><path fill="url(#iBd8uqd)" class="cob7-sk7q"/><path fill="url(#i7Muvqc)" class="cob7-sk7q"/><path fill="url(#iNVMtDc)" class="cob7-sk7q"/><g filter="url(#i7b9k3d)"><path stroke="url(#iovILgd)" class="lqq7iqafp"/></g><g filter="url(#iASzmde)"><path stroke="url(#iJkVOrd)" class="e6krpwbyv"/></g><path fill="url(#ivHj5Dc)" class="napfbyb6j"/><path fill="url(#iZTAmQc)" class="napfbyb6j"/><path fill="url(#ikqVl2c)" class="napfbyb6j"/><path fill="url(#iGD2trd)" class="napfbyb6j"/><path fill="url(#ihLF2pe)" class="napfbyb6j"/><g filter="url(#iVmTwmb)"><path stroke="url(#iGfI7Ce)" class="sm1addcji"/></g><g filter="url(#iP7gTSb)"><path stroke="url(#ijwbIBl)" class="yl8izo-9a"/></g><g filter="url(#imRLcyb)"><path stroke="url(#id9BXXd)" class="ocju3ln3y"/></g><g filter="url(#icySyNd)"><path stroke="url(#i5cd8cc)" class="mw4c-dn2n"/></g><defs><radialGradient id="inQ9cJd" cx="0" cy="0" r="1" gradientTransform="matrix(-18.00256 3.40585 -9.51981 -50.3196 22.737 15.386)" gradientUnits="userSpaceOnUse"><stop offset=".853" class="k9kl84atc"/><stop offset="1" class="ztc-_dkbo"/></radialGradient><radialGradient id="ilw8bEd" cx="0" cy="0" r="1" gradientTransform="rotate(141.22 5.794 15.35)scale(4.29081 7.10858)" gradientUnits="userSpaceOnUse"><stop class="cb46-g1qy"/><stop offset="1" class="d8p7acc1w"/></radialGradient><radialGradient id="ikEqXgd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.67638 30.65152 -20.5674 -3.13789 17.755 1.315)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="c0v2h1bql"/><stop offset="1" class="z--odq6yb"/></radialGradient><radialGradient id="ia0KbHb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.97396 28.64293 -19.21966 -3.33757 17.755 1.315)" gradientUnits="userSpaceOnUse"><stop offset=".968" class="goesxhpir"/><stop offset="1" class="rd8_-xrqq"/></radialGradient><radialGradient id="ioX9Mob" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 -.28125 .73699 5.07703 4.387 13.625)" gradientUnits="userSpaceOnUse"><stop class="zcrylwb4c"/><stop offset="1" class="zn-1ioblb"/></radialGradient><radialGradient id="i7YvRFb" cx="0" cy="0" r="1" gradientTransform="rotate(48.18 -6.725 9.016)scale(3.5372 3.99024)" gradientUnits="userSpaceOnUse"><stop class="f3dohi98n"/><stop offset="1" class="l6grq4bwi"/></radialGradient><radialGradient id="ipWwKge" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 -.125 1.0637 7.71184 8.665 13.43)" gradientUnits="userSpaceOnUse"><stop class="j-xpr0sji"/><stop offset="1" class="uvuouhl3f"/></radialGradient><radialGradient id="im7Mqvj" cx="0" cy="0" r="1" gradientTransform="rotate(58.762 .78 10.152)scale(2.71164 3.33266)" gradientUnits="userSpaceOnUse"><stop class="w8mqklcmp"/><stop offset="1" class="rfn36pbhi"/></radialGradient><radialGradient id="i8CKpnQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 -.14063 .82423 -4.48734 18.51 12.367)" gradientUnits="userSpaceOnUse"><stop class="kp5ntqbsj"/><stop offset="1" class="lt-fub42r"/></radialGradient><radialGradient id="iTuPsLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.85793 .12596 -.5544 8.17728 12.345 12.592)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="kwutu-mlc"/><stop offset="1" class="jt3t-_ayc"/></radialGradient><radialGradient id="iC8nzHd" cx="0" cy="0" r="1" gradientTransform="rotate(73.753 6.716 11.133)scale(3.21441 4.84592)" gradientUnits="userSpaceOnUse"><stop class="dg_rg9bsy"/><stop offset="1" class="aswe4j1ew"/></radialGradient><radialGradient id="iNVMtDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00074 -.47343 1.30056 -2.74911 22.306 16.32)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="r5k4mbcvk"/><stop offset="1" class="v3h3lac3b"/></radialGradient><radialGradient id="ivHj5Dc" cx="0" cy="0" r="1" gradientTransform="rotate(147.308 13.696 11.401)scale(6.01516 1.81793)" gradientUnits="userSpaceOnUse"><stop class="xsc4fpbic"/><stop offset="1" class="f88eu_8gu"/></radialGradient><radialGradient id="iZTAmQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.62446 -.94445 .93393 1.60636 24.24 5.967)" gradientUnits="userSpaceOnUse"><stop class="xsc4fpbic"/><stop offset="1" class="f88eu_8gu"/></radialGradient><radialGradient id="ikqVl2c" cx="0" cy="0" r="1" gradientTransform="rotate(-41.606 13.756 -22.063)scale(2.29883 1.9829)" gradientUnits="userSpaceOnUse"><stop class="xsc4fpbic"/><stop offset="1" class="f88eu_8gu"/></radialGradient><radialGradient id="iGD2trd" cx="0" cy="0" r="1" gradientTransform="rotate(-49.514 11.774 -9.702)scale(2.03652 1.66399)" gradientUnits="userSpaceOnUse"><stop class="xsc4fpbic"/><stop offset="1" class="f88eu_8gu"/></radialGradient><radialGradient id="ihLF2pe" cx="0" cy="0" r="1" gradientTransform="matrix(.68001 -1.2278 1.3352 .7395 6.9 9.14)" gradientUnits="userSpaceOnUse"><stop class="xsc4fpbic"/><stop offset="1" class="f88eu_8gu"/></radialGradient><linearGradient id="ibhv5xb" x1="8.962" x2="8.019" y1="12.07" y2="12.309" gradientUnits="userSpaceOnUse"><stop class="r2xadvboc"/><stop offset="1" class="m5xr39t-p"/></linearGradient><linearGradient id="i7q9qsd" x1="9.98" x2="8.29" y1="15.993" y2="14.804" gradientUnits="userSpaceOnUse"><stop class="cx0gkqb6h"/><stop offset="1" class="xdw0rebuo"/></linearGradient><linearGradient id="iPUzjib" x1="14.132" x2="12.803" y1="10.044" y2="10.132" gradientUnits="userSpaceOnUse"><stop class="thf-onb4k"/><stop offset="1" class="ofqcfbbai"/></linearGradient><linearGradient id="iudIWVb" x1="8.414" x2="10.993" y1="10.825" y2="10.463" gradientUnits="userSpaceOnUse"><stop class="n850dvb5i"/><stop offset="1" class="mokqxe8wf"/></linearGradient><linearGradient id="iZmfV8c" x1="13.366" x2="12.944" y1="15.318" y2="11.97" gradientUnits="userSpaceOnUse"><stop offset=".29" class="cx0gkqb6h"/><stop offset="1" class="xdw0rebuo"/></linearGradient><linearGradient id="ily4DQe" x1="13.572" x2="15.681" y1="8.999" y2="9.195" gradientUnits="userSpaceOnUse"><stop class="o5k0w-bwv"/><stop offset="1" class="migg17b2p"/></linearGradient><linearGradient id="imiZwJe" x1="18.79" x2="17.744" y1="11.463" y2="11.305" gradientUnits="userSpaceOnUse"><stop class="fw3a74zlr"/><stop offset="1" class="phkk0g0_g"/></linearGradient><linearGradient id="iyjsEMb" x1="15.321" x2="15.618" y1="14.938" y2="11.726" gradientUnits="userSpaceOnUse"><stop class="cx0gkqb6h"/><stop offset="1" class="kdp2exb4b"/><stop offset="1" class="xdw0rebuo"/></linearGradient><linearGradient id="i7fuaoc" x1="19.334" x2="18.259" y1="1.22" y2="9.941" gradientUnits="userSpaceOnUse"><stop class="lg7-j0bme"/><stop offset="1" class="hj5r_l0gb"/></linearGradient><linearGradient id="iBd8uqd" x1="18.76" x2="21.305" y1="10.008" y2="10.775" gradientUnits="userSpaceOnUse"><stop class="bgr181bcv"/><stop offset="1" class="uqias6yyf"/></linearGradient><linearGradient id="i7Muvqc" x1="18.52" x2="19.77" y1="16.152" y2="12.375" gradientUnits="userSpaceOnUse"><stop class="eikks2bvz"/><stop offset="1" class="lde1lbc4x"/></linearGradient><linearGradient id="iovILgd" x1="21.9" x2="25.681" y1="14.726" y2="1.82" gradientUnits="userSpaceOnUse"><stop class="kvk8wz14r"/><stop offset="1" class="umj4l4blp"/></linearGradient><linearGradient id="iJkVOrd" x1="28.15" x2="27.653" y1="15.414" y2="21.285" gradientUnits="userSpaceOnUse"><stop class="y28tgx-in"/><stop offset="1" class="h0vjas8xq"/></linearGradient><linearGradient id="iGfI7Ce" x1="9.137" x2="7.392" y1="16.357" y2="17.172" gradientUnits="userSpaceOnUse"><stop class="i3-_-w2pf"/><stop offset="1" class="hyql_fbqw"/></linearGradient><linearGradient id="ijwbIBl" x1="12.994" x2="11.075" y1="14.283" y2="14.449" gradientUnits="userSpaceOnUse"><stop class="i3-_-w2pf"/><stop offset="1" class="hyql_fbqw"/></linearGradient><linearGradient id="id9BXXd" x1="16.581" x2="14.918" y1="14.695" y2="13.744" gradientUnits="userSpaceOnUse"><stop class="i3-_-w2pf"/><stop offset="1" class="hyql_fbqw"/></linearGradient><linearGradient id="i5cd8cc" x1="20.613" x2="18.95" y1="17.223" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="i3-_-w2pf"/><stop offset="1" class="hyql_fbqw"/></linearGradient><filter id="izTBgpe" width="6.582" height="11.769" x="3.806" y="6.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation=".85"/></filter><filter id="ikpIq1c" width="6.199" height="12.268" x="8.571" y="3.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation="1"/></filter><filter id="idg9lNb" width="6.422" height="14.453" x="13.678" y="1.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation="1"/></filter><filter id="i7b9k3d" width="6.219" height="12.656" x="19.212" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation=".625"/></filter><filter id="iASzmde" width="10.125" height="9.875" x="20.025" y="13.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation=".75"/></filter><filter id="iVmTwmb" width="3.406" height="3.61" x="6.518" y="14.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation=".25"/></filter><filter id="iP7gTSb" width="4.015" height="2.827" x="10.081" y="12.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation=".25"/></filter><filter id="imRLcyb" width="4.047" height="2.406" x="13.976" y="12.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation=".25"/></filter><filter id="icySyNd" width="4.047" height="2.406" x="18.008" y="15.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1414" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-fingers-splayed-light" /></template>
<style>
.aakc_on8w {
  stroke: var(--svg-color--ffdac2, #FFDAC2);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.321 6.32l.7 6.768");
}

.aswe4j1ew {
  stop-color: var(--svg-color--d8aa90, #D8AA90);
  stop-opacity: 0;
}

.bgr181bcv {
  stop-color: var(--svg-color--df9e80, #DF9E80);
}

.c0v2h1bql {
  stop-color: var(--svg-color--ba7d97, #BA7D97);
  stop-opacity: 0;
}

.cb46-g1qy {
  stop-color: var(--svg-color--fec8b7, #FEC8B7);
}

.cihs5mbop {
  fill: var(--svg-color--fcc5b2, #FCC5B2);
  d: path("M14.47 4.124a2.415 2.415 0 0 1 4.784.666l-.92 6.613c.69-1.975 1.394-3.857 1.98-5.162c.473-1.228 1.64-2.015 3.094-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.126 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176c-.348.529-.707 1.076-1.293 1.824a10 10 0 0 1-2.305 2.148l-.008-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.292-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.cob7-sk7q {
  d: path("m21.95 16.434l-.007.003q.145-.556.309-1.128c.764-2.663 1.808-5.5 2.585-7.468q.096-.24.138-.487c.201-1.146-.419-2.33-1.568-2.706c-1.453-.422-2.62.365-3.093 1.594a44 44 0 0 0-.904 2.206c-.35.913-.714 1.921-1.076 2.955l.005-.033l-.01.042l-.6 2.03c-.183.63-.396 2.08 1.04 3s2.838.599 3.177 0z");
}

.cx0gkqb6h {
  stop-color: var(--svg-color--fcc5b2, #FCC5B2);
}

.d8p7acc1w {
  stop-color: var(--svg-color--fec8b7, #FEC8B7);
  stop-opacity: 0;
}

.dg_rg9bsy {
  stop-color: var(--svg-color--daad92, #DAAD92);
}

.e6krpwbyv {
  stroke-linecap: round;
  d: path("M28.15 15.414c-1.334.854-4.425 3.225-6.125 5.874");
}

.eikks2bvz {
  stop-color: var(--svg-color--fcc5b3, #FCC5B3);
}

.f3dohi98n {
  stop-color: var(--svg-color--dbab90, #DBAB90);
}

.f88eu_8gu {
  stop-color: var(--svg-color--ffd5bc, #FFD5BC);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fw3a74zlr {
  stop-color: var(--svg-color--d7987e, #D7987E);
}

.goesxhpir {
  stop-color: var(--svg-color--bf7b8a, #BF7B8A);
  stop-opacity: 0;
}

.h0vjas8xq {
  stop-color: var(--svg-color--ffe1c6, #FFE1C6);
  stop-opacity: 0;
}

.hj5r_l0gb {
  stop-color: var(--svg-color--ffe2c7, #FFE2C7);
  stop-opacity: 0;
}

.hyql_fbqw {
  stop-color: var(--svg-color--ffd5bf, #FFD5BF);
  stop-opacity: 0;
}

.i3-_-w2pf {
  stop-color: var(--svg-color--ffd5bf, #FFD5BF);
}

.iq2o_qbpb {
  d: path("m4.795 17.4l-.02-.174a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.656 2.676l.87 3.32c.266 1.905-2.672 3.574-4.91 2.12");
}

.j-xpr0sji {
  stop-color: var(--svg-color--ca8363, #CA8363);
}

.jm0zesbdo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.35 4.338l-.922 8.953");
}

.jt3t-_ayc {
  stop-color: var(--svg-color--d18c6e, #D18C6E);
  stop-opacity: 0;
}

.k9kl84atc {
  stop-color: var(--svg-color--dda492, #DDA492);
  stop-opacity: 0;
}

.kdp2exb4b {
  stop-color: var(--svg-color--ebb197, #EBB197);
  stop-opacity: 0;
}

.kp5ntqbsj {
  stop-color: var(--svg-color--c2846b, #C2846B);
}

.kvk8wz14r {
  stop-color: var(--svg-color--ffdcc3, #FFDCC3);
}

.kwutu-mlc {
  stop-color: var(--svg-color--d18c6e, #D18C6E);
}

.l6grq4bwi {
  stop-color: var(--svg-color--dbab90, #DBAB90);
  stop-opacity: 0;
}

.lde1lbc4x {
  stop-color: var(--svg-color--fcc5b3, #FCC5B3);
  stop-opacity: 0;
}

.lg7-j0bme {
  stop-color: var(--svg-color--ffe2c7, #FFE2C7);
}

.lqq7iqafp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.837 16.476c.354-1.25 1.469-5.256 2.969-9.406");
}

.lt-fub42r {
  stop-color: var(--svg-color--c2846b, #C2846B);
  stop-opacity: 0;
}

.lvf4egbzb {
  d: path("M13.9 14.632c0 .766-.422 1.828-1.766 2.047c-1.428.233-2.306-1.061-2.504-1.582l-.804-3.164l-.404-5.104a2.415 2.415 0 1 1 4.814-.388z");
}

.m5xr39t-p {
  stop-color: var(--svg-color--de9b80, #DE9B80);
  stop-opacity: 0;
}

.migg17b2p {
  stop-color: var(--svg-color--de9c81, #DE9C81);
  stop-opacity: 0;
}

.mokqxe8wf {
  stop-color: var(--svg-color--dc977a, #DC977A);
  stop-opacity: 0;
}

.mw4c-dn2n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.758 16.066c.546.644 1.63 1.135 2.547.794");
}

.n850dvb5i {
  stop-color: var(--svg-color--dc977a, #DC977A);
}

.napfbyb6j {
  d: path("M14.47 4.124a2.415 2.415 0 0 1 4.784.666l-.92 6.613c.69-1.975 1.394-3.857 1.98-5.162c.473-1.228 1.64-2.015 3.094-1.593c1.312.43 1.935 1.914 1.43 3.193c-.89 2.248-2.126 5.633-2.895 8.596c1.18-.496 2.422-1.528 3.582-2.406c1.523-1.04 2.994-.705 3.79.481a2.506 2.506 0 0 1-.517 3.357l-2.416 1.928a29 29 0 0 0-2.357 2.507a20 20 0 0 0-1.598 2.176c-.348.529-.707 1.076-1.293 1.824a10 10 0 0 1-2.305 2.148l-.008-.007a8.37 8.37 0 0 1-4.812 1.513a8.4 8.4 0 0 1-7.39-4.394c-1.292-2.292-1.502-4.66-1.693-6.812a49 49 0 0 0-.151-1.526a25 25 0 0 0-.531-3.709l-.756-3.082a2.415 2.415 0 1 1 4.691-1.15l.657 2.678l-.414-5.134a2.415 2.415 0 1 1 4.814-.388l.335 4.154z");
}

.o5k0w-bwv {
  stop-color: var(--svg-color--de9c81, #DE9C81);
}

.ocju3ln3y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.726 13.538c.547.644 1.63 1.135 2.548.794");
}

.ofqcfbbai {
  stop-color: var(--svg-color--d6987d, #D6987D);
  stop-opacity: 0;
}

.phkk0g0_g {
  stop-color: var(--svg-color--d7987e, #D7987E);
  stop-opacity: 0;
}

.r2xadvboc {
  stop-color: var(--svg-color--de9b80, #DE9B80);
}

.r5k4mbcvk {
  stop-color: var(--svg-color--ecb192, #ECB192);
}

.rd8_-xrqq {
  stop-color: var(--svg-color--bf7b8a, #BF7B8A);
}

.rfn36pbhi {
  stop-color: var(--svg-color--dab7a2, #DAB7A2);
  stop-opacity: 0;
}

.sm1addcji {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.268 17.547c.829-.5 1.438-1.016 1.907-2.11");
}

.thf-onb4k {
  stop-color: var(--svg-color--d6987d, #D6987D);
}

.umj4l4blp {
  stop-color: var(--svg-color--ffdcc3, #FFDCC3);
  stop-opacity: 0;
}

.uqias6yyf {
  stop-color: var(--svg-color--df9e80, #DF9E80);
  stop-opacity: 0;
}

.uvuouhl3f {
  stop-color: var(--svg-color--ca8363, #CA8363);
  stop-opacity: 0;
}

.v3h3lac3b {
  stop-color: var(--svg-color--ecb192, #ECB192);
  stop-opacity: 0;
}

.w8mqklcmp {
  stop-color: var(--svg-color--dab7a2, #DAB7A2);
}

.wf7f97g9x {
  d: path("M13.88 14.38c.31.287.72.536 1.254.69c1.613.462 2.492-1.04 2.688-1.985l.512-1.683l.92-6.612a2.415 2.415 0 0 0-4.783-.666l-.9 6.463z");
}

.xdw0rebuo {
  stop-color: var(--svg-color--fcc5b2, #FCC5B2);
  stop-opacity: 0;
}

.xnywgnbbf {
  stroke: var(--svg-color--ffdac3, #FFDAC3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("m6.206 9.313l1.781 6.968");
}

.xsc4fpbic {
  stop-color: var(--svg-color--ffd5bc, #FFD5BC);
}

.y28tgx-in {
  stop-color: var(--svg-color--ffe1c6, #FFE1C6);
}

.yl8izo-9a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.831 14.759c.95-.185 1.699-.46 2.515-1.327");
}

.z--odq6yb {
  stop-color: var(--svg-color--ba7d97, #BA7D97);
}

.zcrylwb4c {
  stop-color: var(--svg-color--dda391, #DDA391);
}

.zn-1ioblb {
  stop-color: var(--svg-color--dda391, #DDA391);
  stop-opacity: 0;
}

.ztc-_dkbo {
  stop-color: var(--svg-color--dda492, #DDA492);
}

</style>
