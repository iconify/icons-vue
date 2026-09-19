<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iwQm6Vc)" clip-rule="evenodd" class="kg7vqrbkt"/><path fill="url(#ie1qR1b)" clip-rule="evenodd" class="kg7vqrbkt"/><path fill="url(#iZDVbDe)" clip-rule="evenodd" class="kg7vqrbkt"/><path fill="url(#iPoazyc)" clip-rule="evenodd" class="kg7vqrbkt"/><path fill="url(#icB3Qrc)" clip-rule="evenodd" class="q9x5kwc0d"/><path fill="url(#ipGmtEb)" clip-rule="evenodd" class="q9x5kwc0d"/><path fill="url(#iEJjBgd)" clip-rule="evenodd" class="q9x5kwc0d"/><path fill="url(#iVG3QYb)" clip-rule="evenodd" class="h9invdb4y"/><path fill="url(#ifKqddc)" clip-rule="evenodd" class="h9invdb4y"/><path fill="url(#idon9Yc)" clip-rule="evenodd" class="lxlgjwb-r"/><path fill="url(#i2KG85d)" clip-rule="evenodd" class="lxlgjwb-r"/><path fill="url(#iXf8Itb)" clip-rule="evenodd" class="lxlgjwb-r"/><g filter="url(#iJNOIgb)"><path stroke="url(#iLGo0Ne)" class="ytj8nhbrk"/></g><g filter="url(#iCSyK5b)"><ellipse fill="url(#iJkIMLe)" transform="rotate(48.885 24.188 4.112)" class="mignlwo2c"/></g><g filter="url(#iIakozb)"><ellipse fill="url(#ixQUR6K)" transform="rotate(48.885 28.035 8.152)" class="ra1y3-bvq"/></g><g filter="url(#ii6nNke)"><ellipse fill="url(#ipBunhb)" transform="rotate(121.165 24.467 27.771)" class="tywraubie"/></g><g filter="url(#ihi5kWd)"><path stroke="url(#irE1Cgc)" class="w875vsbji"/></g><g filter="url(#imDhDDc)"><path stroke="url(#ifxJmSc)" class="bzsllzbyr"/></g><g filter="url(#iUstnjw)"><path stroke="url(#iRXvI6y)" class="lftn_0bpj"/></g><defs><linearGradient id="iwQm6Vc" x1="29.547" x2="6.672" y1="-1.111" y2="-1.111" gradientUnits="userSpaceOnUse"><stop class="yiq__d07e"/><stop offset=".372" class="emo973b4a"/><stop offset="1" class="uojyabbji"/></linearGradient><linearGradient id="iZDVbDe" x1="13.734" x2="2.984" y1=".57" y2="1.695" gradientUnits="userSpaceOnUse"><stop offset=".527" class="msakmjbbj"/><stop offset="1" class="oyfwheb3w"/></linearGradient><linearGradient id="iPoazyc" x1="18.172" x2="18.234" y1="4.758" y2="-.367" gradientUnits="userSpaceOnUse"><stop offset=".297" class="msakmjbbj"/><stop offset=".774" class="oyfwheb3w"/></linearGradient><linearGradient id="icB3Qrc" x1="2.672" x2="23.172" y1="31.258" y2="31.258" gradientUnits="userSpaceOnUse"><stop class="yiq__d07e"/><stop offset=".444" class="emo973b4a"/><stop offset="1" class="uojyabbji"/></linearGradient><linearGradient id="iVG3QYb" x1="33.284" x2="33.284" y1="27.383" y2="9.383" gradientUnits="userSpaceOnUse"><stop class="yiq__d07e"/><stop offset=".444" class="emo973b4a"/><stop offset="1" class="uojyabbji"/></linearGradient><linearGradient id="idon9Yc" x1="1.297" x2="1.297" y1="6.883" y2="27.383" gradientUnits="userSpaceOnUse"><stop class="yiq__d07e"/><stop offset=".444" class="emo973b4a"/><stop offset="1" class="uojyabbji"/></linearGradient><linearGradient id="iXf8Itb" x1="5.547" x2=".12" y1="10.508" y2="7.851" gradientUnits="userSpaceOnUse"><stop offset=".297" class="msakmjbbj"/><stop offset=".774" class="oyfwheb3w"/></linearGradient><linearGradient id="iLGo0Ne" x1="8.391" x2="32.871" y1="2.383" y2="5.872" gradientUnits="userSpaceOnUse"><stop class="m524thbhz"/><stop offset=".818" class="j79-om_-z"/></linearGradient><linearGradient id="iJkIMLe" x1="24.188" x2="24.132" y1="2.786" y2="4.872" gradientUnits="userSpaceOnUse"><stop class="m524thbhz"/><stop offset="1" class="j79-om_-z"/></linearGradient><linearGradient id="ixQUR6K" x1="28.035" x2="27.98" y1="6.827" y2="8.913" gradientUnits="userSpaceOnUse"><stop class="tervjcnsn"/><stop offset="1" class="j79-om_-z"/><stop offset="1" class="x31ndebkv"/></linearGradient><linearGradient id="ipBunhb" x1="24.467" x2="24.411" y1="26.445" y2="28.532" gradientUnits="userSpaceOnUse"><stop class="tervjcnsn"/><stop offset="1" class="j79-om_-z"/><stop offset="1" class="x31ndebkv"/></linearGradient><linearGradient id="irE1Cgc" x1="28.859" x2="25.254" y1="3.945" y2="31.289" gradientUnits="userSpaceOnUse"><stop class="j79-om_-z"/><stop offset=".707" class="m524thbhz"/></linearGradient><linearGradient id="ifxJmSc" x1="28.364" x2="1.027" y1="27.52" y2="23.863" gradientUnits="userSpaceOnUse"><stop class="m524thbhz"/><stop offset="1" class="j79-om_-z"/></linearGradient><linearGradient id="iRXvI6y" x1="4.596" x2="10.273" y1="4.09" y2="31.081" gradientUnits="userSpaceOnUse"><stop class="m4r3ypb6p"/><stop offset="1" class="ofgxtfhsc"/></linearGradient><filter id="iJNOIgb" width="18.719" height="6.392" x="6.641" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6188" stdDeviation=".625"/></filter><filter id="iCSyK5b" width="4.297" height="4.174" x="22.039" y="2.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6188" stdDeviation=".5"/></filter><filter id="iIakozb" width="4.297" height="4.174" x="25.886" y="6.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6188" stdDeviation=".5"/></filter><filter id="ii6nNke" width="4.438" height="4.014" x="22.247" y="25.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6188" stdDeviation=".5"/></filter><filter id="ihi5kWd" width="6.657" height="19.523" x="24.03" y="6.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6188" stdDeviation=".625"/></filter><filter id="imDhDDc" width="20.281" height="6.632" x="6.078" y="23.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6188" stdDeviation=".625"/></filter><filter id="iUstnjw" width="6.353" height="20.121" x="3.056" y="6.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7139_6188" stdDeviation=".625"/></filter><radialGradient id="ie1qR1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 6.125 -12.28145 -.37596 16.61 3.945)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="msakmjbbj"/><stop offset="1" class="oyfwheb3w"/></radialGradient><radialGradient id="ipGmtEb" cx="0" cy="0" r="1" gradientTransform="rotate(-94.086 21.063 6.533)scale(6.14061 12.3127)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="msakmjbbj"/><stop offset="1" class="oyfwheb3w"/></radialGradient><radialGradient id="iEJjBgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.1875 -7.32701 0 16.047 28.508)" gradientUnits="userSpaceOnUse"><stop class="oyfwheb3w"/><stop offset=".828" class="msakmjbbj"/></radialGradient><radialGradient id="ifKqddc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 13.06245 -7.58315 -.10885 29.61 15.258)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="msakmjbbj"/><stop offset="1" class="oyfwheb3w"/></radialGradient><radialGradient id="i2KG85d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.93753 4.56661 0 2.047 16.133)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="oyfwheb3w"/><stop offset="1" class="msakmjbbj"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:anger-symbol" /></template>
<style>
.bzsllzbyr {
  stroke-linecap: round;
  d: path("M24.61 27.59c-2.157-1.77-10.813-5.426-16.782.355");
}

.emo973b4a {
  stop-color: var(--svg-color--ea0a4f, #EA0A4F);
}

.ft5dv1b6b {
  fill: none;
}

.h9invdb4y {
  fill-rule: evenodd;
  d: path("M29.416 6.675a2 2 0 0 1 .089 2.827c-3.277 3.49-3.277 9.771 0 13.262a2 2 0 0 1-2.916 2.738c-4.723-5.03-4.723-13.709 0-18.738a2 2 0 0 1 2.827-.09");
}

.j79-om_-z {
  stop-color: var(--svg-color--ff8f9e, #FF8F9E);
  stop-opacity: 0;
}

.kg7vqrbkt {
  fill-rule: evenodd;
  d: path("M6.552 2.804a2 2 0 0 1 2.824-.166c3.742 3.326 9.6 3.326 13.342 0a2 2 0 1 1 2.658 2.99c-5.258 4.673-13.4 4.673-18.658 0a2 2 0 0 1-.166-2.824");
}

.lftn_0bpj {
  stroke-linecap: round;
  d: path("M4.806 7.84c1.924 2.02 5.322 10.24 0 16.62");
}

.lxlgjwb-r {
  fill-rule: evenodd;
  d: path("M2.678 6.675a2 2 0 0 1 2.827.089c4.722 5.03 4.722 13.708 0 18.738a2 2 0 0 1-2.916-2.738c3.277-3.49 3.277-9.772 0-13.262a2 2 0 0 1 .089-2.827");
}

.m4r3ypb6p {
  stop-color: var(--svg-color--ff97a5, #FF97A5);
}

.m524thbhz {
  stop-color: var(--svg-color--ff8f9e, #FF8F9E);
}

.mignlwo2c {
  cx: 24.188px;
  cy: 4.112px;
  rx: 0.862px;
  ry: 1.326px;
}

.msakmjbbj {
  stop-color: var(--svg-color--a11749, #A11749);
  stop-opacity: 0;
}

.ofgxtfhsc {
  stop-color: var(--svg-color--ffa1ad, #FFA1AD);
  stop-opacity: 0;
}

.oyfwheb3w {
  stop-color: var(--svg-color--a21749, #A21749);
}

.q9x5kwc0d {
  fill-rule: evenodd;
  d: path("M22.678 29.59c-3.49-3.276-9.772-3.276-13.262 0a2 2 0 1 1-2.738-2.915c5.03-4.723 13.708-4.723 18.738 0a2 2 0 0 1-2.738 2.916");
}

.ra1y3-bvq {
  cx: 28.035px;
  cy: 8.152px;
  rx: 0.862px;
  ry: 1.326px;
}

.tervjcnsn {
  stop-color: var(--svg-color--ff9fac, #FF9FAC);
}

.tywraubie {
  cx: 24.467px;
  cy: 27.771px;
  rx: 0.862px;
  ry: 1.326px;
}

.uojyabbji {
  stop-color: var(--svg-color--ec008c, #EC008C);
}

.w875vsbji {
  stroke-linecap: round;
  d: path("M28.936 8.047c-1.105.997-6.514 8.398 0 16.023");
}

.x31ndebkv {
  stop-color: var(--svg-color--ffa6b2, #FFA6B2);
  stop-opacity: 0;
}

.yiq__d07e {
  stop-color: var(--svg-color--e81123, #E81123);
}

.ytj8nhbrk {
  stroke-linecap: round;
  d: path("M8.39 3.54c1.042 1.062 7.25 5.655 15.22.468");
}

</style>
