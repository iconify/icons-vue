<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAU1Sad)" class="rkvrnwfzg"/><path fill="url(#iirZAOc)" class="vm8084ikz"/><path fill="url(#iq1Weib)" class="vm8084ikz"/><g filter="url(#ioHUqse)"><path class="h8hh0nb0b"/></g><g filter="url(#ibXD89b)"><path clip-rule="evenodd" class="m0ipv_w5i"/></g><g filter="url(#iKHtgdb)"><path class="vmu6fmblc"/></g><path fill="url(#iCcseub)" class="ht247frtr"/><path fill="url(#iE0oV1W)" class="ht247frtr"/><path fill="url(#ie2wvwc)" class="ej1f5fbqm"/><g filter="url(#iS425Kl)"><path fill="url(#imvU3mr)" class="jx1e0mbuu"/></g><g filter="url(#igALHmc)"><path class="qkimg5ajv"/></g><path fill="url(#iekqhFe)" class="it4m0hb7g"/><path fill="url(#iUld6fc)" class="it4m0hb7g"/><path fill="url(#i0x9fme)" class="it4m0hb7g"/><g filter="url(#isIX9rr)"><path fill="url(#iq0YoRd)" class="sbadhkn8d"/></g><g filter="url(#imPGtQb)"><circle class="m2p5idzvp"/></g><circle fill="url(#iEoBDeI)" class="wqwg8-bep"/><g filter="url(#iuiHZKe)"><circle class="eh41u8bvz"/></g><circle fill="url(#inhc5yR)" class="w_77idbre"/><defs><filter id="ioHUqse" width="18.869" height="6.635" x="7.569" y="19.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32336" stdDeviation=".5"/></filter><filter id="ibXD89b" width="17.547" height="8.518" x="12.517" y="20.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32336" stdDeviation=".05"/></filter><filter id="iKHtgdb" width="17.57" height="5.135" x="8.912" y="19.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32336" stdDeviation=".125"/></filter><filter id="iS425Kl" width="9.769" height="9.954" x="8.641" y="15.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32336" stdDeviation=".5"/></filter><filter id="igALHmc" width="10.51" height="5.053" x="5.463" y="21.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32336" stdDeviation=".125"/></filter><filter id="isIX9rr" width="9.674" height="9.886" x="5.296" y="17.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32336" stdDeviation=".5"/></filter><filter id="imPGtQb" width="2.184" height="2.184" x="2.728" y="21.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32336" stdDeviation=".05"/></filter><filter id="iuiHZKe" width="1.169" height="1.169" x="4.831" y="22.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32336" stdDeviation=".05"/></filter><linearGradient id="iAU1Sad" x1="2" x2="29.99" y1="23.188" y2="23.188" gradientUnits="userSpaceOnUse"><stop class="jrziw1_bq"/><stop offset=".145" class="rd11_ab4y"/><stop offset=".371" class="nr3z1-bdq"/><stop offset=".424" class="zzar8peoe"/><stop offset=".485" class="kxb9xvx1t"/><stop offset=".893" class="eda45-b3b"/><stop offset="1" class="be346cccn"/></linearGradient><linearGradient id="iirZAOc" x1="11.75" x2="16.688" y1="17.563" y2="27.875" gradientUnits="userSpaceOnUse"><stop class="jauuqubgw"/><stop offset=".4" class="ca_7vybcj"/><stop offset=".823" class="dgq3w1b3d"/></linearGradient><linearGradient id="iCcseub" x1="15.25" x2="20.313" y1="13.344" y2="24.063" gradientUnits="userSpaceOnUse"><stop class="zdj6rr99o"/><stop offset=".053" class="v3vzezj8m"/><stop offset=".569" class="x_tzl0b1k"/><stop offset=".599" class="wayi0i_nv"/><stop offset=".622" class="ts8s639gn"/><stop offset="1" class="qh3ewd2ay"/></linearGradient><linearGradient id="iE0oV1W" x1="20.313" x2="19.219" y1="23.375" y2="21.063" gradientUnits="userSpaceOnUse"><stop offset=".067" class="irceznbqo"/><stop offset=".301" class="gsio302ak"/></linearGradient><linearGradient id="ie2wvwc" x1="12" x2="14.656" y1="22.938" y2="16.656" gradientUnits="userSpaceOnUse"><stop class="x_tzl0b1k"/><stop offset="1" class="srhaheb1w"/></linearGradient><linearGradient id="iekqhFe" x1="8.531" x2="13.719" y1="16.719" y2="26.281" gradientUnits="userSpaceOnUse"><stop class="na00enumj"/><stop offset=".286" class="c9zwp1blf"/><stop offset=".638" class="x_tzl0b1k"/><stop offset=".659" class="abu7066rq"/><stop offset=".681" class="yyx58cb_t"/><stop offset="1" class="cdpl7fbfv"/></linearGradient><linearGradient id="iUld6fc" x1="8.188" x2="10.905" y1="24.156" y2="19.344" gradientUnits="userSpaceOnUse"><stop class="ror-yx9ue"/><stop offset=".28" class="yns9m5bws"/></linearGradient><radialGradient id="iq1Weib" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 4.3125 -8.55926 .62023 12.625 22)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="epai6cd8u"/><stop offset="1" class="q9serxqtx"/></radialGradient><radialGradient id="imvU3mr" cx="0" cy="0" r="1" gradientTransform="matrix(11.81247 5.69929 -4.15181 8.60514 11.938 20.426)" gradientUnits="userSpaceOnUse"><stop class="x3yr1zrcb"/><stop offset=".339" class="eac1lsbhd"/><stop offset="1" class="rgd0xnbly"/></radialGradient><radialGradient id="i0x9fme" cx="0" cy="0" r="1" gradientTransform="rotate(28.94 -42.337 21.13)scale(6.07055 6.53927)" gradientUnits="userSpaceOnUse"><stop class="g-xj588vf"/><stop offset="1" class="gzxus2y1n"/></radialGradient><radialGradient id="iq0YoRd" cx="0" cy="0" r="1" gradientTransform="rotate(25.597 -44.643 29.32)scale(13.6049 9.86695)" gradientUnits="userSpaceOnUse"><stop class="x3yr1zrcb"/><stop offset=".339" class="eac1lsbhd"/><stop offset="1" class="rgd0xnbly"/></radialGradient><radialGradient id="iEoBDeI" cx="0" cy="0" r="1" gradientTransform="rotate(74.899 -12.787 13.775)scale(2.03917)" gradientUnits="userSpaceOnUse"><stop class="do429pbzr"/><stop offset=".444" class="ari18mgam"/><stop offset=".808" class="yse1l7b3a"/></radialGradient><radialGradient id="inhc5yR" cx="0" cy="0" r="1" gradientTransform="rotate(76.954 -11.967 15.133)scale(.6576)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="spiq9v3hw"/><stop offset="1" class="yse1l7b3a"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:butter" /></template>
<style>
.abu7066rq {
  stop-color: var(--svg-color--fed65a, #FED65A);
}

.ari18mgam {
  stop-color: var(--svg-color--d7a541, #D7A541);
}

.be346cccn {
  stop-color: var(--svg-color--dccff4, #DCCFF4);
}

.c9zwp1blf {
  stop-color: var(--svg-color--f2c841, #F2C841);
}

.ca_7vybcj {
  stop-color: var(--svg-color--cababe, #CABABE);
}

.cdpl7fbfv {
  stop-color: var(--svg-color--fabf41, #FABF41);
}

.dgq3w1b3d {
  stop-color: var(--svg-color--e6d3c4, #E6D3C4);
}

.do429pbzr {
  stop-color: var(--svg-color--d3ad48, #D3AD48);
}

.eac1lsbhd {
  stop-color: var(--svg-color--e7ab16, #E7AB16);
}

.eda45-b3b {
  stop-color: var(--svg-color--decff8, #DECFF8);
}

.eh41u8bvz {
  cx: 5.416px;
  cy: 23.578px;
  r: 0.484px;
  fill: var(--svg-color--b0978a, #B0978A);
}

.ej1f5fbqm {
  d: path("M9.35 20.4v-3.77c0-.2.21-.34.4-.25L17.1 20c.19.09.31.29.31.5v3.73c0 .24-.25.4-.47.29l-7.23-3.55a.63.63 0 0 1-.36-.57");
}

.epai6cd8u {
  stop-color: var(--svg-color--b79a90, #B79A90);
}

.ft5dv1b6b {
  fill: none;
}

.g-xj588vf {
  stop-color: var(--svg-color--d48b1f, #D48B1F);
}

.gsio302ak {
  stop-color: var(--svg-color--fab842, #FAB842);
  stop-opacity: 0;
}

.gzxus2y1n {
  stop-color: var(--svg-color--d99a40, #D99A40);
  stop-opacity: 0;
}

.h8hh0nb0b {
  fill: var(--svg-color--bf9a82, #BF9A82);
  d: path("M8.569 20.882c0 .24.14.46.35.57l7.37 3.62c.21.1.258.1.478 0l8.32-3.99c.22-.11.35-.33.35-.57z");
}

.ht247frtr {
  d: path("M18.91 12.13c-.35-.17-.75-.17-1.09 0l-8.04 3.85c-.26.13-.43.4-.43.69v3.74c0 .24.14.46.35.57l7.37 3.62c.21.1.46.1.68 0l8.32-3.99c.22-.11.35-.33.35-.57V16.3c0-.29-.17-.56-.43-.69z");
}

.irceznbqo {
  stop-color: var(--svg-color--f8b644, #F8B644);
}

.it4m0hb7g {
  d: path("M8.4 17.31c-.35-.17-.75-.17-1.09 0l-.98.47c-.26.13-.43.39-.43.69v3.74c0 .24.14.46.35.57l7.37 3.62c.21.1.46.1.68 0l1.26-.61c.22-.11.35-.33.35-.57v-3.74c0-.29-.17-.56-.43-.69z");
}

.jauuqubgw {
  stop-color: var(--svg-color--b1a09a, #B1A09A);
}

.jrziw1_bq {
  stop-color: var(--svg-color--bea8c2, #BEA8C2);
}

.jx1e0mbuu {
  d: path("M9.64 20.344v-3.532c0-.2.201-.34.391-.25L17.1 20c.19.09.31.29.31.5v3.663c0 .24-.25.4-.47.29l-6.949-3.54a.62.62 0 0 1-.35-.57");
}

.kxb9xvx1t {
  stop-color: var(--svg-color--e4cfff, #E4CFFF);
}

.m0ipv_w5i {
  fill: var(--svg-color--ede7f1, #EDE7F1);
  fill-rule: evenodd;
  d: path("M29.765 21.047c-.135.136-.32.25-.484.343c-.169.096-3.76 1.866-7.343 3.627s-7.179 3.521-7.357 3.598c-.192.082-.57.174-.98.2c-.407.027-.632-.051-.984-.249c0 0 .536.029.968 0c.39-.025.738-.113.897-.18c.171-.074 3.756-1.83 7.346-3.593c3.591-1.765 7.17-3.53 7.329-3.62a2 2 0 0 0 .43-.302l.363-.369c.053.223-.049.406-.185.545");
}

.m2p5idzvp {
  cx: 3.82px;
  cy: 23.07px;
  r: 0.992px;
  fill: var(--svg-color--b0978a, #B0978A);
}

.na00enumj {
  stop-color: var(--svg-color--e9bd42, #E9BD42);
}

.nr3z1-bdq {
  stop-color: var(--svg-color--c19fe2, #C19FE2);
}

.q9serxqtx {
  stop-color: var(--svg-color--ba9e96, #BA9E96);
  stop-opacity: 0;
}

.qh3ewd2ay {
  stop-color: var(--svg-color--fab842, #FAB842);
}

.qkimg5ajv {
  fill: var(--svg-color--9e7968, #9E7968);
  d: path("M5.713 22.366c0 .24.14.46.35.57l7.37 3.62c.21.1.46.1.68 0l1.26-.61c.22-.11.35-.33.35-.57c0 0-9.098-4.454-10.01-3.01");
}

.rd11_ab4y {
  stop-color: var(--svg-color--c1a6d1, #C1A6D1);
}

.rgd0xnbly {
  stop-color: var(--svg-color--dc9819, #DC9819);
  stop-opacity: 0;
}

.rkvrnwfzg {
  d: path("M28.87 20.52v.3l-10.09-4.96a.6.6 0 0 0-.52 0L3.12 23.23v-.3H2v1.22c0 .21.11.42.33.53l10.15 4.99c.62.31 1.36.31 1.98 0l15.2-7.4c.22-.11.33-.32.33-.53v-1.22z");
}

.ror-yx9ue {
  stop-color: var(--svg-color--d28a30, #D28A30);
}

.sbadhkn8d {
  d: path("M6.296 22.083V18.53c0-.2.21-.34.4-.25l6.964 3.52c.19.09.31.29.31.5v3.512c0 .24-.25.4-.47.29l-6.844-3.46a.62.62 0 0 1-.36-.56");
}

.spiq9v3hw {
  stop-color: var(--svg-color--d3a53e, #D3A53E);
}

.srhaheb1w {
  stop-color: var(--svg-color--f2c941, #F2C941);
  stop-opacity: 0;
}

.ts8s639gn {
  stop-color: var(--svg-color--f9c83f, #F9C83F);
}

.v3vzezj8m {
  stop-color: var(--svg-color--f1c740, #F1C740);
}

.vm8084ikz {
  d: path("M18.26 14.67L2.33 22.43a.59.59 0 0 0 0 1.06l10.15 4.99c.62.31 1.36.31 1.98 0l15.2-7.4a.59.59 0 0 0 0-1.06l-10.88-5.35a.6.6 0 0 0-.52 0");
}

.vmu6fmblc {
  fill: var(--svg-color--a67858, #A67858);
  d: path("M9.162 20.52c0 .24.14.46.35.57l7.37 3.62c.21.1.46.1.68 0l8.32-3.99c.22-.11.35-.33.35-.57z");
}

.w_77idbre {
  cx: 5.516px;
  cy: 23.531px;
  r: 0.484px;
}

.wayi0i_nv {
  stop-color: var(--svg-color--ffd85e, #FFD85E);
}

.wqwg8-bep {
  cx: 4.016px;
  cy: 23.016px;
  r: 1.047px;
}

.x_tzl0b1k {
  stop-color: var(--svg-color--f2c941, #F2C941);
}

.x3yr1zrcb {
  stop-color: var(--svg-color--db9718, #DB9718);
}

.yns9m5bws {
  stop-color: var(--svg-color--d28a30, #D28A30);
  stop-opacity: 0;
}

.yse1l7b3a {
  stop-color: var(--svg-color--d48f27, #D48F27);
}

.yyx58cb_t {
  stop-color: var(--svg-color--fac840, #FAC840);
}

.zdj6rr99o {
  stop-color: var(--svg-color--e7bb42, #E7BB42);
}

.zzar8peoe {
  stop-color: var(--svg-color--d8b8ff, #D8B8FF);
}

</style>
