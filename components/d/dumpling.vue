<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipOnIqc)" class="ps5_pfb_x"/><path fill="url(#i77Kmwb)" class="ps5_pfb_x"/><path fill="url(#iJ3gi8N)" class="ps5_pfb_x"/><g filter="url(#iijqKNQ)"><path fill="url(#iZHFfSX)" class="opp2uk1ey"/><path fill="url(#iqudTjd)" class="opp2uk1ey"/></g><g filter="url(#iB6rD5c)"><path fill="url(#ipnkrec)" class="oa7qrvbiq"/><path fill="url(#i045fWb)" class="oa7qrvbiq"/><path fill="url(#iA4tndd)" class="oa7qrvbiq"/><path fill="url(#i9E0dAe)" class="oa7qrvbiq"/></g><path class="lv040og8p"/><g filter="url(#ijbAh2c)"><path class="rt_e-w45a"/></g><path fill="url(#iCDyUWg)" class="q46z4zrsy"/><path fill="url(#iPvxkAd)" class="c4xg9eb6k"/><path fill="url(#ieZGPPc)" class="cktpzbbqn"/><g filter="url(#idhi1js)"><path class="k21mp6j-s"/></g><path fill="url(#ivSigAT)" class="b2-fu5bid"/><g filter="url(#ioRcvod)"><path stroke="url(#imvH60h)" class="p76f3bc_u"/></g><g filter="url(#i7FY5mb)"><path class="opbvdwzit"/></g><path fill="url(#ipHEQke)" class="m23ctwbhl"/><g filter="url(#iprZAzJ)"><path stroke="url(#ikmi44c)" class="moqrqojqd"/></g><defs><radialGradient id="iJ3gi8N" cx="0" cy="0" r="1" gradientTransform="rotate(130.029 6.92 16.005)scale(11.8125 6.20796)" gradientUnits="userSpaceOnUse"><stop class="b7e3ssb0e"/><stop offset="1" class="w2qxtcbwn"/></radialGradient><radialGradient id="iqudTjd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.625 9.93752 -4.06195 -2.70796 21.563 20.938)" gradientUnits="userSpaceOnUse"><stop class="zfezf30id"/><stop offset="1" class="zqejr0b6r"/></radialGradient><radialGradient id="ipnkrec" cx="0" cy="0" r="1" gradientTransform="matrix(-10.23347 12.3574 -11.10253 -9.19428 24.751 14.08)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="dpzp2n7vg"/><stop offset=".576" class="kt2v4fbcp"/><stop offset=".932" class="a_x5f_bbm"/><stop offset="1" class="uhdd8-btk"/></radialGradient><radialGradient id="i045fWb" cx="0" cy="0" r="1" gradientTransform="rotate(60.576 -17.882 21.351)scale(10.345 10.3407)" gradientUnits="userSpaceOnUse"><stop class="sqkoziunj"/><stop offset="1" class="l7vablb-w"/></radialGradient><radialGradient id="iA4tndd" cx="0" cy="0" r="1" gradientTransform="rotate(149.036 9.191 13.799)scale(10.1328 6.43491)" gradientUnits="userSpaceOnUse"><stop offset=".447" class="z9127ccxp"/><stop offset="1" class="a_epv6b-y"/></radialGradient><radialGradient id="i9E0dAe" cx="0" cy="0" r="1" gradientTransform="rotate(106.28 -3.593 18.71)scale(7.57661 12.3291)" gradientUnits="userSpaceOnUse"><stop class="dchsn01hb"/><stop offset="1" class="q9t82ubre"/></radialGradient><radialGradient id="iCDyUWg" cx="0" cy="0" r="1" gradientTransform="matrix(3.5128 1.67197 -1.60115 3.36403 7.51 9.633)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="aum2zcc5w"/><stop offset=".75" class="b-s1jzbjp"/></radialGradient><radialGradient id="iPvxkAd" cx="0" cy="0" r="1" gradientTransform="matrix(3.87717 1.18752 -.8206 2.6792 4.125 15.375)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="aum2zcc5w"/><stop offset=".75" class="b-s1jzbjp"/></radialGradient><radialGradient id="ivSigAT" cx="0" cy="0" r="1" gradientTransform="rotate(36.455 -2.967 24.233)scale(3.11246 3.67093)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="aum2zcc5w"/><stop offset=".75" class="b-s1jzbjp"/></radialGradient><radialGradient id="imvH60h" cx="0" cy="0" r="1" gradientTransform="matrix(1.45311 1.23438 -.94085 1.10757 20.703 3.344)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="emquv51tq"/><stop offset="1" class="f-hjtbbss"/></radialGradient><radialGradient id="ipHEQke" cx="0" cy="0" r="1" gradientTransform="rotate(54.752 5.537 22.885)scale(2.8699 3.50134)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="aum2zcc5w"/><stop offset=".75" class="b-s1jzbjp"/></radialGradient><radialGradient id="ikmi44c" cx="0" cy="0" r="1" gradientTransform="rotate(68.587 8.836 23.883)scale(4.80009 2.49357)" gradientUnits="userSpaceOnUse"><stop class="vflmnlb-o"/><stop offset="1" class="f-hjtbbss"/></radialGradient><filter id="iijqKNQ" width="28.539" height="28.327" x="1.719" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31189" stdDeviation=".25"/></filter><filter id="iB6rD5c" width="19.365" height="19.372" x="8.5" y="8.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31189" stdDeviation=".5"/></filter><filter id="ijbAh2c" width="4.643" height="4.642" x="6.63" y="6.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31189" stdDeviation=".125"/></filter><filter id="idhi1js" width="3.452" height="5.082" x="13.02" y="3.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31189" stdDeviation=".125"/></filter><filter id="ioRcvod" width="3.538" height="2.65" x="18.219" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31189" stdDeviation=".125"/></filter><filter id="i7FY5mb" width="3.018" height="4.938" x="20.271" y="3.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31189" stdDeviation=".125"/></filter><filter id="iprZAzJ" width="5.894" height="9.154" x="24.215" y="3.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31189" stdDeviation=".125"/></filter><linearGradient id="ipOnIqc" x1="27.375" x2="6.625" y1="8" y2="26.25" gradientUnits="userSpaceOnUse"><stop offset=".298" class="z1524gxwo"/><stop offset="1" class="fx_ogqk7f"/></linearGradient><linearGradient id="i77Kmwb" x1="2.563" x2="27.063" y1="24.063" y2="10.375" gradientUnits="userSpaceOnUse"><stop class="zw5xxfthd"/><stop offset=".22" class="c7koycbtl"/><stop offset=".457" class="l4gw-n02b"/><stop offset=".994" class="l5svflbbo"/></linearGradient><linearGradient id="iZHFfSX" x1="26.926" x2="6.997" y1="8.317" y2="25.845" gradientUnits="userSpaceOnUse"><stop offset=".298" class="z1524gxwo"/><stop offset="1" class="fx_ogqk7f"/></linearGradient><linearGradient id="ieZGPPc" x1="4.289" x2="7.263" y1="22.076" y2="23.861" gradientUnits="userSpaceOnUse"><stop class="aum2zcc5w"/><stop offset=".75" class="b-s1jzbjp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dumpling" /></template>
<style>
.a_epv6b-y {
  stop-color: var(--svg-color--d49b6e, #D49B6E);
  stop-opacity: 0;
}

.a_x5f_bbm {
  stop-color: var(--svg-color--d39d51, #D39D51);
}

.aum2zcc5w {
  stop-color: var(--svg-color--e39a5f, #E39A5F);
}

.b-s1jzbjp {
  stop-color: var(--svg-color--d07b3b, #D07B3B);
}

.b2-fu5bid {
  d: path("M15.6 8c.53-.16.84-.72.68-1.25l-.98-3.29l-.35.2c-.37.18-.77.29-1.18.35l-.4.01l.98 3.29c.16.54.72.85 1.25.69");
}

.b7e3ssb0e {
  stop-color: var(--svg-color--bc8266, #BC8266);
}

.c4xg9eb6k {
  d: path("M7.96 15.64c-.16.53-.72.84-1.25.68l-3.28-.98l.2-.34c.18-.37.29-.77.35-1.18l.01-.4l3.29.98c.53.15.84.71.68 1.24");
}

.c7koycbtl {
  stop-color: var(--svg-color--be7365, #BE7365);
}

.cktpzbbqn {
  d: path("M8.19 21.68c.08.55-.29 1.06-.84 1.15l-3.39.51l.04-.41c0-.41-.06-.82-.19-1.22l-.16-.37l3.4-.52c.55-.07 1.06.31 1.14.86");
}

.dchsn01hb {
  stop-color: var(--svg-color--cb825f, #CB825F);
}

.dpzp2n7vg {
  stop-color: var(--svg-color--ffeb9d, #FFEB9D);
}

.emquv51tq {
  stop-color: var(--svg-color--efd092, #EFD092);
}

.f-hjtbbss {
  stop-color: var(--svg-color--f6d898, #F6D898);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx_ogqk7f {
  stop-color: var(--svg-color--dca16e, #DCA16E);
}

.k21mp6j-s {
  fill: var(--svg-color--ecc28a, #ECC28A);
  d: path("M15.5 8.209c.53-.16.84-.72.68-1.25l-.98-3.29l-.35.2c-.37.18-.77.29-1.18.35l-.4.01l.98 3.29c.16.54.72.85 1.25.69");
}

.kt2v4fbcp {
  stop-color: var(--svg-color--f3bc6d, #F3BC6D);
}

.l4gw-n02b {
  stop-color: var(--svg-color--c9a766, #C9A766);
}

.l5svflbbo {
  stop-color: var(--svg-color--d5b674, #D5B674);
}

.l7vablb-w {
  stop-color: var(--svg-color--d18a65, #D18A65);
  stop-opacity: 0;
}

.lv040og8p {
  fill: var(--svg-color--cf7840, #CF7840);
  d: path("M10.73 10.73c-.39.39-1.03.39-1.42 0L6.88 8.31l.35-.21c.33-.24.63-.54.87-.87l.2-.35l2.43 2.43c.39.39.39 1.03 0 1.42");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.m23ctwbhl {
  d: path("M21.63 8.24c.55.08 1.06-.29 1.15-.84l.51-3.39l-.4.04c-.41 0-.82-.06-1.22-.19l-.37-.16l-.52 3.4c-.07.54.3 1.05.85 1.14");
}

.moqrqojqd {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M24.484 4.313c.271-.021 1.05-.124 1.47.203c1.811 1.409 4.234 3.832 3.53 6.343c-.35 1.25-.463 1.558-.609 1.579");
}

.oa7qrvbiq {
  d: path("M12.006 11.579c-3.341 3.341-3.341 8.772 0 12.114l2.745 2.744l12.114-12.114l-2.744-2.745c-3.351-3.35-8.773-3.35-12.115 0");
}

.opbvdwzit {
  fill: var(--svg-color--e7c185, #E7C185);
  d: path("M21.38 8.24a1.01 1.01 0 0 0 1.15-.819l.51-3.306l-.4.039c-.41 0-.82-.059-1.22-.185l-.37-.156l-.52 3.315c-.07.527.3 1.025.85 1.112");
}

.opp2uk1ey {
  d: path("M26.563 4.828a7 7 0 0 0-.625-.458c-1.134-.653-2.738.128-3.977-.198c-1.258-.336-2.346-1.883-3.633-1.883c-1.296 0-2.624 1.492-3.883 1.828c-1.239.327-3.101-.402-4.047.14c-1.104.635-1.597 2.692-2.539 3.634c-.94.94-2.795 1.116-3.43 2.21c-.652 1.134.015 3.027-.312 4.266c-.336 1.258-1.898 2.415-1.898 3.711c0 1.297 1.539 2.46 1.875 3.719c.326 1.239-.283 3.127.37 4.26c.49.833 1.361 1.487 2.036 2.162c2.017 2.017 5.438 1.775 7.455-.242s14.03-13.954 14.03-13.954c2.016-2.016 2.554-4.96.335-7.445z");
}

.p76f3bc_u {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.469 2.5c.146 0 .493.05.718.25c.226.2 1.553 1.042 2.188 1.438");
}

.ps5_pfb_x {
  d: path("M26.67 4.48c-.13-.11-.28-.22-.45-.32c-1.18-.68-2.96.07-4.25-.27C20.66 3.54 19.49 2 18.15 2c-1.35 0-2.51 1.54-3.82 1.89c-1.29.34-3.07-.41-4.25.27c-1.15.66-1.39 2.57-2.37 3.55s-2.89 1.22-3.55 2.36c-.68 1.18.07 2.96-.27 4.25C3.54 15.63 2 16.8 2 18.15s1.54 2.51 1.89 3.82c.34 1.29-.41 3.07.27 4.25c.1.17.21.31.32.45l.02.02c.08.09.16.17.25.25l1.53 1.53a5.36 5.36 0 0 0 7.59 0l14.61-14.61a5.36 5.36 0 0 0 0-7.59z");
}

.q46z4zrsy {
  d: path("M10.73 10.73c-.39.39-1.03.39-1.42 0L6.88 8.31l.35-.21c.33-.24.63-.54.87-.87l.2-.35l2.43 2.43c.39.39.39 1.03 0 1.42");
}

.q9t82ubre {
  stop-color: var(--svg-color--c87d5a, #C87D5A);
  stop-opacity: 0;
}

.rt_e-w45a {
  fill: var(--svg-color--eab97c, #EAB97C);
  d: path("M10.73 11.011c-.39.39-1.03.39-1.42 0l-2.43-2.42l.35-.21c.33-.24.63-.54.87-.87l.2-.35l2.43 2.43c.39.39.39 1.03 0 1.42");
}

.sqkoziunj {
  stop-color: var(--svg-color--c97e5e, #C97E5E);
}

.uhdd8-btk {
  stop-color: var(--svg-color--cc944d, #CC944D);
}

.vflmnlb-o {
  stop-color: var(--svg-color--f6d898, #F6D898);
}

.w2qxtcbwn {
  stop-color: var(--svg-color--bd7f66, #BD7F66);
  stop-opacity: 0;
}

.z1524gxwo {
  stop-color: var(--svg-color--ddba85, #DDBA85);
}

.z9127ccxp {
  stop-color: var(--svg-color--d39a6e, #D39A6E);
}

.zfezf30id {
  stop-color: var(--svg-color--c48c69, #C48C69);
}

.zqejr0b6r {
  stop-color: var(--svg-color--c28567, #C28567);
  stop-opacity: 0;
}

.zw5xxfthd {
  stop-color: var(--svg-color--a5895f, #A5895F);
}

</style>
