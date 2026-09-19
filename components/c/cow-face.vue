<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVlxpwe)" class="py9f7d0pf"/><path fill="url(#iYTIzYc)" class="py9f7d0pf"/><path fill="url(#iAOy2be)" class="py9f7d0pf"/><path fill="url(#isbrPBd)" class="f3rf868pe"/><path fill="url(#iLSxwBY)" class="b8gxwrb0c"/><path fill="url(#idzNb5d)" class="b8gxwrb0c"/><path fill="url(#iFCmRWd)" class="l56rysksh"/><g filter="url(#ihzXReb)"><path stroke="url(#iZAxaNH)" class="uvigdgbhj"/></g><path fill="url(#ifp2Ifb)" class="q2xl22b0p"/><path fill="url(#ipLQgUb)" class="q2xl22b0p"/><g filter="url(#ijfsEGt)"><path stroke="url(#inxyKtD)" class="vyscmcw8g"/></g><path fill="url(#ikXV3uK)" class="qqnzgcb7i"/><path fill="url(#imeJkQz)" class="qqnzgcb7i"/><path fill="url(#i5t2Utb)" class="qqnzgcb7i"/><path fill="url(#iSlEljd)" class="qqnzgcb7i"/><path fill="url(#imYu6Me)" class="tk04foi-n"/><path fill="url(#iGvCyLe)" class="tk04foi-n"/><path fill="url(#idtUGUc)" class="s-2zc1ooo"/><path fill="url(#iMubGSd)" class="s-2zc1ooo"/><path fill="url(#ig9610O)" class="s-2zc1ooo"/><path fill="url(#iBQldQe)" class="qp6zjvkvg"/><path fill="url(#iztIued)" class="g8l1z52dd"/><path fill="url(#iwDJaPe)" class="g8l1z52dd"/><path fill="url(#iMEK4Qu)" class="lqm8kfbve"/><path fill="url(#i6nyzJo)" class="lqm8kfbve"/><path fill="url(#igjaDkc)" class="lqm8kfbve"/><path fill="url(#iSHmYid)" class="lqm8kfbve"/><path class="bbh-gdsjj"/><g filter="url(#i3qiiLd)"><path fill="url(#ibPokCd)" class="dyn3cwb8u"/></g><path fill="url(#ivwij0W)" class="fqgjk-b4m"/><path fill="url(#ihr2zNd)" class="bw2x2ibjg"/><g filter="url(#iRf4fgc)"><rect class="chwyd23ci"/></g><rect fill="url(#iQvlX7b)" class="xve38m65i"/><rect fill="url(#irEftkc)" class="xve38m65i"/><rect fill="url(#ieuZMde)" class="xve38m65i"/><g filter="url(#isGh3jd)"><rect class="vpr77vckm"/></g><rect fill="url(#iLyaUCj)" class="j9rnjably"/><rect fill="url(#iHhQbDc)" class="j9rnjably"/><rect fill="url(#i0apRwc)" class="j9rnjably"/><rect fill="url(#i3SK2fc)" class="j9rnjably"/><g filter="url(#iR9J4bb)"><ellipse fill="url(#iep1jPb)" transform="rotate(47.966 22.226 21)" class="gh_65nw5c"/></g><defs><linearGradient id="iVlxpwe" x1="4.781" x2="7.094" y1="8.287" y2="5.631" gradientUnits="userSpaceOnUse"><stop class="hxf6e2bmp"/><stop offset="1" class="mr6ws7hsg"/></linearGradient><linearGradient id="iYTIzYc" x1="6.313" x2="6.313" y1="10.631" y2="7.569" gradientUnits="userSpaceOnUse"><stop class="ks87l-26m"/><stop offset="1" class="s1t5xd_as"/></linearGradient><linearGradient id="iLSxwBY" x1="17.776" x2="17.776" y1="2.004" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="u4npiobqk"/><stop offset="1" class="kmtw4t4vp"/></linearGradient><linearGradient id="idzNb5d" x1="13.094" x2="14.219" y1="8.444" y2="5.873" gradientUnits="userSpaceOnUse"><stop class="n78orrb_k"/><stop offset="1" class="ib7pygkst"/></linearGradient><linearGradient id="iZAxaNH" x1="13.391" x2="13.609" y1="3.084" y2="8.553" gradientUnits="userSpaceOnUse"><stop class="k0f6uubgg"/><stop offset="1" class="f5ail8n9p"/></linearGradient><linearGradient id="ifp2Ifb" x1="21.625" x2="21.625" y1="-.15" y2="7.725" gradientUnits="userSpaceOnUse"><stop class="u4npiobqk"/><stop offset="1" class="kmtw4t4vp"/></linearGradient><linearGradient id="ipLQgUb" x1="22.375" x2="20.469" y1="7.412" y2="5.873" gradientUnits="userSpaceOnUse"><stop class="n78orrb_k"/><stop offset="1" class="ib7pygkst"/></linearGradient><linearGradient id="inxyKtD" x1="20.236" x2="20.017" y1="3.084" y2="8.553" gradientUnits="userSpaceOnUse"><stop class="k0f6uubgg"/><stop offset="1" class="f5ail8n9p"/></linearGradient><linearGradient id="ikXV3uK" x1="11.625" x2="28.375" y1="18.787" y2="18.787" gradientUnits="userSpaceOnUse"><stop class="iotuyzavy"/><stop offset="1" class="zmi-w8b8u"/></linearGradient><linearGradient id="imeJkQz" x1="23" x2="25.75" y1="18.787" y2="18.787" gradientUnits="userSpaceOnUse"><stop class="vyn0p2oqx"/><stop offset="1" class="iotuyzavy"/></linearGradient><linearGradient id="i5t2Utb" x1="14.844" x2="12.406" y1="8.881" y2="5.475" gradientUnits="userSpaceOnUse"><stop class="pi9-8wxhc"/><stop offset="1" class="yyz8tgbrh"/></linearGradient><linearGradient id="idtUGUc" x1="24.781" x2="27.094" y1="8.287" y2="5.631" gradientUnits="userSpaceOnUse"><stop class="hxf6e2bmp"/><stop offset="1" class="mr6ws7hsg"/></linearGradient><linearGradient id="iMubGSd" x1="26.313" x2="26.313" y1="10.381" y2="7.506" gradientUnits="userSpaceOnUse"><stop class="xu1t0xb0k"/><stop offset="1" class="s1t5xd_as"/></linearGradient><linearGradient id="iztIued" x1="16.375" x2="9.563" y1="11.705" y2="11.705" gradientUnits="userSpaceOnUse"><stop class="lt6sghskf"/><stop offset="1" class="eraq4bc2n"/></linearGradient><linearGradient id="iwDJaPe" x1="8.75" x2="5.438" y1="16.971" y2="16.971" gradientUnits="userSpaceOnUse"><stop class="f7u0vwbpi"/><stop offset=".896" class="t-oue3bgz"/><stop offset="1" class="t-oue3bgz"/></linearGradient><linearGradient id="iMEK4Qu" x1="6.563" x2="20.313" y1="21.1" y2="21.1" gradientUnits="userSpaceOnUse"><stop class="sf_u8wbxp"/><stop offset="1" class="lusa8jb8z"/></linearGradient><linearGradient id="igjaDkc" x1="16.563" x2="16.563" y1="23.975" y2="29.412" gradientUnits="userSpaceOnUse"><stop offset=".432" class="uylm8vi1w"/><stop offset="1" class="r7sth-b2h"/></linearGradient><linearGradient id="iSHmYid" x1="16.563" x2="16.563" y1="23.975" y2="14.037" gradientUnits="userSpaceOnUse"><stop offset=".604" class="fkyovobpp"/><stop offset="1" class="l8x4lcb8m"/></linearGradient><linearGradient id="iQvlX7b" x1="12.75" x2="11.882" y1="14.5" y2="14.5" gradientUnits="userSpaceOnUse"><stop offset=".307" class="uvxa-eued"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="irEftkc" x1="12.984" x2="12.984" y1="16.044" y2="14.634" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ieuZMde" x1="10.754" x2="11.551" y1="15.207" y2="15.207" gradientUnits="userSpaceOnUse"><stop class="dyysy0bzo"/><stop offset="1" class="zmzak_sfz"/></linearGradient><linearGradient id="iLyaUCj" x1="20.75" x2="19.882" y1="14.5" y2="14.5" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iHhQbDc" x1="20.984" x2="20.984" y1="16.044" y2="14.634" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="i0apRwc" x1="18.754" x2="19.787" y1="15.207" y2="15.207" gradientUnits="userSpaceOnUse"><stop class="dyysy0bzo"/><stop offset="1" class="zmzak_sfz"/></linearGradient><radialGradient id="iAOy2be" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 1 -1.79108 -2.51871 8.625 5.6)" gradientUnits="userSpaceOnUse"><stop class="y3qyz048x"/><stop offset="1" class="q5nca1bec"/></radialGradient><radialGradient id="isbrPBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0625 -4.52952 0 16 28.375)" gradientUnits="userSpaceOnUse"><stop class="d73yuqb9r"/><stop offset="1" class="l1p5o23bk"/></radialGradient><radialGradient id="iFCmRWd" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -.79687 1.41862 -3.5605 13.281 4.662)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ib7pygkst"/><stop offset="1" class="n78orrb_k"/></radialGradient><radialGradient id="iSlEljd" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 3.9375 -3.3708 3.2638 10.813 7.037)" gradientUnits="userSpaceOnUse"><stop class="iotuyzavy"/><stop offset="1" class="vyn0p2oqx"/></radialGradient><radialGradient id="imYu6Me" cx="0" cy="0" r="1" gradientTransform="matrix(-2.85937 -1.6094 1.08885 -1.93453 5.11 7.96)" gradientUnits="userSpaceOnUse"><stop class="wf2qyhb8c"/><stop offset="1" class="mfktgf4qd"/></radialGradient><radialGradient id="iGvCyLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2425 1.77506 -2.86977 -.39204 6.187 5.224)" gradientUnits="userSpaceOnUse"><stop class="eyfdkaj8n"/><stop offset="1" class="nmkezebsz"/></radialGradient><radialGradient id="ig9610O" cx="0" cy="0" r="1" gradientTransform="rotate(141.017 13.478 7.746)scale(4.32169 1.46602)" gradientUnits="userSpaceOnUse"><stop class="y3qyz048x"/><stop offset="1" class="q5nca1bec"/></radialGradient><radialGradient id="iBQldQe" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 -3.52506 4.075 .50576 20.875 10)" gradientUnits="userSpaceOnUse"><stop class="d6f68ab6r"/><stop offset="1" class="pz8osybzb"/></radialGradient><radialGradient id="i6nyzJo" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 9.8125 -20.78408 -1.19145 17.125 19.975)" gradientUnits="userSpaceOnUse"><stop offset=".432" class="uylm8vi1w"/><stop offset="1" class="ogq471pbh"/></radialGradient><radialGradient id="ibPokCd" cx="0" cy="0" r="1" gradientTransform="matrix(4.15625 -2.53743 .95778 1.56882 24.063 8.037)" gradientUnits="userSpaceOnUse"><stop class="wf2qyhb8c"/><stop offset=".931" class="mfktgf4qd"/></radialGradient><radialGradient id="ivwij0W" cx="0" cy="0" r="1" gradientTransform="translate(12.344 21)scale(1.15625)" gradientUnits="userSpaceOnUse"><stop class="nh243vb7e"/><stop offset="1" class="c0eyosg6f"/></radialGradient><radialGradient id="ihr2zNd" cx="0" cy="0" r="1" gradientTransform="translate(18.484 21)scale(1.10938)" gradientUnits="userSpaceOnUse"><stop class="nh243vb7e"/><stop offset="1" class="c0eyosg6f"/></radialGradient><radialGradient id="i3SK2fc" cx="0" cy="0" r="1" gradientTransform="matrix(-.57862 -1.63534 1.58971 -.56248 20.292 14.68)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iep1jPb" cx="0" cy="0" r="1" gradientTransform="rotate(90.557 1.566 20.69)scale(4.66288 4.48435)" gradientUnits="userSpaceOnUse"><stop class="z0s9qkbbl"/><stop class="z0s9qkbbl"/><stop offset="1" class="hl3c_wbah"/></radialGradient><filter id="ihzXReb" width="2.467" height="5.516" x="12.017" y="1.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2767" stdDeviation=".375"/></filter><filter id="ijfsEGt" width="3.189" height="5.625" x="18.891" y="1.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2767" stdDeviation=".375"/></filter><filter id="i3qiiLd" width="4.89" height="3.3" x="23.61" y="5.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.486275 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_2767"/></filter><filter id="iRf4fgc" width="2.655" height="3.689" x="10.595" y="12.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2767" stdDeviation=".25"/></filter><filter id="isGh3jd" width="2.345" height="3.689" x="18.545" y="12.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2767" stdDeviation=".25"/></filter><filter id="iR9J4bb" width="8.607" height="8.744" x="17.922" y="16.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2767" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cow-face" /></template>
<style>
.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b8gxwrb0c {
  d: path("M14.13 6.24a3.98 3.98 0 0 1-.15-3.7c.14-.31-.16-.63-.47-.51c-.25.1-.49.22-.72.38a4.01 4.01 0 0 0-1.34 5.18A3.994 3.994 0 0 0 17 9.2c.46-.27.85-.61 1.15-1c-1.57.22-3.18-.51-4.02-1.96");
}

.bbh-gdsjj {
  fill: var(--svg-color--f4b9a8, #F4B9A8);
  d: path("M26.09 5.5c-1.17 0-2.17.78-2.48 1.85c.34.33.63.72.85 1.15h1.45a2.59 2.59 0 0 0 2.59-2.59v-.2c0-.12-.09-.21-.21-.21z");
}

.bw2x2ibjg {
  d: path("M19 22a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.c0eyosg6f {
  stop-color: var(--svg-color--fe7883, #FE7883);
}

.chwyd23ci {
  width: 1.655px;
  height: 2.689px;
  x: 11.095px;
  y: 13.155px;
  fill: var(--svg-color--4e4854, #4E4854);
  rx: 0.828px;
}

.d6f68ab6r {
  stop-color: var(--svg-color--8c8b8d, #8C8B8D);
}

.d73yuqb9r {
  stop-color: var(--svg-color--d04568, #D04568);
}

.dyn3cwb8u {
  d: path("M26.09 5.5c-1.17 0-2.17.78-2.48 1.85c.34.33.63.72.85 1.15h1.45a2.59 2.59 0 0 0 2.59-2.59v-.2c0-.12-.09-.21-.21-.21z");
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.eraq4bc2n {
  stop-color: var(--svg-color--6b696d, #6B696D);
}

.eyfdkaj8n {
  stop-color: var(--svg-color--db7376, #DB7376);
}

.f3rf868pe {
  d: path("M16 29.99a5.65 5.65 0 1 0 0-11.3a5.65 5.65 0 0 0 0 11.3");
}

.f5ail8n9p {
  stop-color: var(--svg-color--ffe3bf, #FFE3BF);
  stop-opacity: 0;
}

.f7u0vwbpi {
  stop-color: var(--svg-color--828183, #828183);
  stop-opacity: 0;
}

.fkyovobpp {
  stop-color: var(--svg-color--de9e8f, #DE9E8F);
  stop-opacity: 0;
}

.fqgjk-b4m {
  d: path("M13 22a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.g8l1z52dd {
  d: path("M16 18.46v-4.51c0-3.276-3.77-7.495-6.52-7.495C8.363 6.995 7 8.502 7 10.51V20z");
}

.gh_65nw5c {
  cx: 22.226px;
  cy: 21px;
  rx: 3.654px;
  ry: 2.988px;
}

.hl3c_wbah {
  stop-color: var(--svg-color--ffd9cf, #FFD9CF);
  stop-opacity: 0;
}

.hxf6e2bmp {
  stop-color: var(--svg-color--626061, #626061);
}

.ib7pygkst {
  stop-color: var(--svg-color--cb9964, #CB9964);
  stop-opacity: 0;
}

.iotuyzavy {
  stop-color: var(--svg-color--d4d1d7, #D4D1D7);
}

.j9rnjably {
  width: 1.5px;
  height: 3px;
  x: 19.25px;
  y: 13px;
  rx: 0.75px;
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.k0f6uubgg {
  stop-color: var(--svg-color--fff5e8, #FFF5E8);
}

.kmtw4t4vp {
  stop-color: var(--svg-color--d9ae7f, #D9AE7F);
}

.ks87l-26m {
  stop-color: var(--svg-color--5f4478, #5F4478);
}

.l1p5o23bk {
  stop-color: var(--svg-color--da6585, #DA6585);
}

.l56rysksh {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M14.13 6.24a3.98 3.98 0 0 1-.15-3.7c.14-.31-.16-.63-.47-.51c-.25.1-.49.22-.72.38a4.01 4.01 0 0 0-1.34 5.18A3.994 3.994 0 0 0 17 9.2c.46-.27.85-.61 1.15-1c-1.57.22-3.18-.51-4.02-1.96");
}

.l8x4lcb8m {
  stop-color: var(--svg-color--de9e8f, #DE9E8F);
}

.lqm8kfbve {
  d: path("M26 22.421c-.04-3.01-2.53-5.43-5.52-5.42h-8.87c-3.03-.06-5.57 2.39-5.61 5.42a5.5 5.5 0 0 0 5.5 5.58h9c3.06 0 5.54-2.5 5.5-5.58");
}

.lt6sghskf {
  stop-color: var(--svg-color--706973, #706973);
}

.lusa8jb8z {
  stop-color: var(--svg-color--f3b9ad, #F3B9AD);
}

.mfktgf4qd {
  stop-color: var(--svg-color--e58082, #E58082);
}

.mr6ws7hsg {
  stop-color: var(--svg-color--727273, #727273);
}

.n78orrb_k {
  stop-color: var(--svg-color--cb9964, #CB9964);
}

.nh243vb7e {
  stop-color: var(--svg-color--ffa0a8, #FFA0A8);
}

.nmkezebsz {
  stop-color: var(--svg-color--db7376, #DB7376);
  stop-opacity: 0;
}

.ogq471pbh {
  stop-color: var(--svg-color--ce79ad, #CE79AD);
}

.pi9-8wxhc {
  stop-color: var(--svg-color--c3c0c7, #C3C0C7);
  stop-opacity: 0;
}

.py9f7d0pf {
  d: path("M10 10H6.09C3.83 10 2 8.17 2 5.91V4.62c0-.34.28-.62.62-.62H5.9C8.17 4 10 5.83 10 8.09z");
}

.pz8osybzb {
  stop-color: var(--svg-color--747474, #747474);
}

.q2xl22b0p {
  d: path("M18.87 6.24c.68-1.18.69-2.56.15-3.7c-.14-.31.16-.63.47-.51c.25.1.49.22.72.38a4.01 4.01 0 0 1 1.34 5.18A3.994 3.994 0 0 1 16 9.2c-.46-.27-.85-.61-1.15-1c1.57.22 3.18-.51 4.02-1.96");
}

.q5nca1bec {
  stop-color: var(--svg-color--878688, #878688);
  stop-opacity: 0;
}

.qp6zjvkvg {
  d: path("M22.3 10h2.65c-.33-2.26-2.28-4-4.64-4H16l2.38 2.38A5.54 5.54 0 0 0 22.3 10");
}

.qqnzgcb7i {
  d: path("M19.724 6h-8.411C8.743 6 7 8.438 7 10.69v11.78h18V10.69C25 8.1 22.637 6 19.724 6");
}

.r7sth-b2h {
  stop-color: var(--svg-color--ad618f, #AD618F);
}

.s-2zc1ooo {
  d: path("M22 10h3.91C28.17 10 30 8.17 30 5.91V4.62c0-.34-.28-.62-.63-.62h-3.28C23.83 4 22 5.83 22 8.09z");
}

.s1t5xd_as {
  stop-color: var(--svg-color--5c4c69, #5C4C69);
  stop-opacity: 0;
}

.sf_u8wbxp {
  stop-color: var(--svg-color--e7a8a9, #E7A8A9);
}

.t-oue3bgz {
  stop-color: var(--svg-color--828183, #828183);
}

.tk04foi-n {
  d: path("M5.91 5.5c1.17 0 2.17.78 2.48 1.85c-.34.34-.62.73-.85 1.15H6.09A2.59 2.59 0 0 1 3.5 5.91v-.2c0-.12.09-.21.21-.21z");
}

.u4npiobqk {
  stop-color: var(--svg-color--f6d4ad, #F6D4AD);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.uvigdgbhj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.61 2.506c-.459.547-1.166 2.066-.329 3.766");
}

.uvxa-eued {
  stop-color: var(--svg-color--615154, #615154);
}

.uylm8vi1w {
  stop-color: var(--svg-color--d17dae, #D17DAE);
  stop-opacity: 0;
}

.vpr77vckm {
  width: 1.345px;
  height: 2.689px;
  x: 19.045px;
  y: 13.155px;
  fill: var(--svg-color--bbb1bb, #BBB1BB);
  rx: 0.672px;
}

.vyn0p2oqx {
  stop-color: var(--svg-color--d4d1d7, #D4D1D7);
  stop-opacity: 0;
}

.vyscmcw8g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.766 2.584c.64.297 1.828 2.313 1.312 3.875");
}

.wf2qyhb8c {
  stop-color: var(--svg-color--ffb6ae, #FFB6AE);
}

.xu1t0xb0k {
  stop-color: var(--svg-color--5c4c69, #5C4C69);
}

.xve38m65i {
  width: 1.5px;
  height: 3px;
  x: 11.25px;
  y: 13px;
  rx: 0.75px;
}

.y3qyz048x {
  stop-color: var(--svg-color--878688, #878688);
}

.yyz8tgbrh {
  stop-color: var(--svg-color--bcb7c0, #BCB7C0);
}

.z0s9qkbbl {
  stop-color: var(--svg-color--ffd9cf, #FFD9CF);
}

.zmi-w8b8u {
  stop-color: var(--svg-color--fbf6ff, #FBF6FF);
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

</style>
