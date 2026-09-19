<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isyxaMb)" class="jj33y33qm"/><path fill="url(#iQlo2be)" class="jj33y33qm"/><path fill="url(#iaMkfGd)" class="jj33y33qm"/><g filter="url(#iHaDska)"><path fill="url(#iy44vuc)" class="tc1s5bc7g"/></g><g filter="url(#iQwjQhb)"><path fill="url(#i46Uoad)" class="sr1zclb6u"/></g><g filter="url(#iA2NHsb)"><path stroke="url(#irk5zRd)" class="bp40-8fww"/></g><g filter="url(#ib5ifcb)"><path stroke="url(#iYlJGzb)" class="gmfhzw5zh"/></g><g filter="url(#irmSzGb)"><path fill="url(#iKmpOYc)" class="aowj32b0p"/></g><g filter="url(#iP6vnyb)"><path fill="url(#i55EW9O)" class="g41wrpy8g"/></g><path fill="url(#i7l4die)" class="s_lt5g8hq"/><path fill="url(#iIfDUId)" class="s_lt5g8hq"/><path fill="url(#ili9yqe)" class="s_lt5g8hq"/><path fill="url(#ijTk9Hd)" class="s_lt5g8hq"/><path fill="url(#ipHSt3b)" class="s_lt5g8hq"/><path fill="url(#iD8nupb)" class="s_lt5g8hq"/><path fill="url(#i2YCN2b)" class="ae9srqmdp"/><g filter="url(#i9FB0dd)"><path class="jfj6r2hbo"/></g><g filter="url(#iClnllz)"><ellipse fill="url(#iWWFs1b)" transform="rotate(-44.19 23.67 13.519)" class="jsmylfx_n"/></g><g filter="url(#i2MMuyv)"><ellipse fill="url(#i25oJgb)" transform="rotate(-128.955 14.01 15.15)" class="p775idh0b"/></g><g filter="url(#iKKZfLe)"><ellipse class="m6aeaac_i"/></g><g filter="url(#i3tVtwb)"><ellipse class="ijc3j1q_h"/></g><defs><linearGradient id="isyxaMb" x1="20.187" x2="10.812" y1="15.149" y2="-.09" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset=".721" class="h66atab_c"/><stop offset="1" class="w9napxb6c"/></linearGradient><linearGradient id="iQlo2be" x1="10" x2="4.187" y1="16.66" y2="23.66" gradientUnits="userSpaceOnUse"><stop class="kskw-5bws"/><stop offset="1" class="w9napxb6c"/></linearGradient><linearGradient id="iaMkfGd" x1="23.312" x2="20.562" y1="13.66" y2="29.17" gradientUnits="userSpaceOnUse"><stop class="kskw-5bws"/><stop offset="1" class="w9napxb6c"/></linearGradient><linearGradient id="iy44vuc" x1="14.812" x2="19.187" y1="4.004" y2="12.316" gradientUnits="userSpaceOnUse"><stop class="eoyq5pb7k"/><stop offset="1" class="qpkt06btb"/></linearGradient><linearGradient id="i46Uoad" x1="6.812" x2="11.187" y1="7.644" y2="15.957" gradientUnits="userSpaceOnUse"><stop class="eoyq5pb7k"/><stop offset="1" class="qpkt06btb"/></linearGradient><linearGradient id="irk5zRd" x1="14.527" x2="14.527" y1="2.066" y2="5.425" gradientUnits="userSpaceOnUse"><stop class="g3epatbiz"/><stop offset="1" class="p9wngpb_m"/></linearGradient><linearGradient id="iYlJGzb" x1="6.839" x2="6.839" y1="4.879" y2="8.238" gradientUnits="userSpaceOnUse"><stop class="g3epatbiz"/><stop offset="1" class="p9wngpb_m"/></linearGradient><linearGradient id="iKmpOYc" x1="21.312" x2="21.312" y1="4.129" y2="10.191" gradientUnits="userSpaceOnUse"><stop class="h66atab_c"/><stop offset="1" class="kskw-5bws"/></linearGradient><linearGradient id="i55EW9O" x1="28.879" x2="18.109" y1="13.597" y2="7.855" gradientUnits="userSpaceOnUse"><stop class="rc14lyykt"/><stop offset="1" class="rwk4h8bkd"/></linearGradient><linearGradient id="ipHSt3b" x1="17.544" x2="24.453" y1="17.764" y2="25.986" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iD8nupb" x1="16.687" x2="8.579" y1="18.107" y2="27.242" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><filter id="iHaDska" width="9.191" height="10.453" x="12.621" y=".77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".5"/></filter><filter id="iQwjQhb" width="7.699" height="11.702" x="5.614" y="3.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".5"/></filter><filter id="iA2NHsb" width="2.696" height="7.969" x="13.179" y="1.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".25"/></filter><filter id="ib5ifcb" width="2.865" height="8.813" x="6.447" y="4.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".25"/></filter><filter id="irmSzGb" width="9.031" height="10.219" x="16" y="2.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".625"/></filter><filter id="iP6vnyb" width="8.566" height="19.5" x="21.312" y="3.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".5"/></filter><filter id="i9FB0dd" width="7.382" height="11.207" x="14.642" y="10.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation="1"/></filter><filter id="iClnllz" width="9.193" height="9.131" x="19.074" y="8.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".75"/></filter><filter id="i2MMuyv" width="9.234" height="9.999" x="9.394" y="10.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".75"/></filter><filter id="iKKZfLe" width="6.517" height="3.684" x="19.015" y="7.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".75"/></filter><filter id="i3tVtwb" width="6.517" height="3.684" x="7.104" y="7.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7134_6142" stdDeviation=".75"/></filter><radialGradient id="i7l4die" cx="0" cy="0" r="1" gradientTransform="matrix(.7034 27.74999 -28.57582 .72433 15.233 1.16)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".677" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="iIfDUId" cx="0" cy="0" r="1" gradientTransform="rotate(142.986 8.763 10.523)scale(22.615 42.3601)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="ili9yqe" cx="0" cy="0" r="1" gradientTransform="rotate(-158.663 11.55 7.76)scale(19.6166 27.7308)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="ijTk9Hd" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.053 15.712)scale(17.0729)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="i2YCN2b" cx="0" cy="0" r="1" gradientTransform="rotate(164.618 8.02 8.706)scale(14.8442 15.6768)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="qnbh2pn9v"/><stop offset="1" class="pl211ybaw"/></radialGradient><radialGradient id="iWWFs1b" cx="0" cy="0" r="1" gradientTransform="rotate(-176.775 13.842 6.755)scale(5.30792 3.58415)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="i25oJgb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.37567 -.26019 .1378 -2.84707 16.445 15.75)" gradientUnits="userSpaceOnUse"><stop class="j0jx7sb_q"/><stop offset="1" class="nwq74cdll"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:heart-on-fire" /></template>
<style>
.ae9srqmdp {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.247 28.967a1.71 1.71 0 0 0 1.708-.02c3.107-1.8 8.368-5.83 10.45-11.044c3.095-6.874-4.171-12.362-9.194-8.415c-.499.392-1.12.838-1.57 1.265c-.241.23-.664.254-.913.032a22 22 0 0 0-2.057-1.581c-4.282-2.897-12.072.921-8.75 9.07c1.204 3.618 6.89 8.732 10.326 10.693");
}

.aowj32b0p {
  d: path("M23.781 11.597c-.175-3.5-2.458-7.156-3.187-7.718c0 2.156-2 5.187-3.344 6.343z");
}

.bp40-8fww {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.25 2.066c-1.01.896-2.494 3.494-.344 6.719");
}

.ejc52zb_a {
  stop-color: var(--svg-color--f12e52, #F12E52);
}

.eoyq5pb7k {
  stop-color: var(--svg-color--ffd56c, #FFD56C);
}

.fdfp5-b0w {
  stop-color: var(--svg-color--b91d43, #B91D43);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3epatbiz {
  stop-color: var(--svg-color--ffe39d, #FFE39D);
}

.g41wrpy8g {
  d: path("m24.125 22.347l-1.813-17.5c2.271.521 6.713 4.138 6.563 8.938s-3.208 7.25-4.75 8.562");
}

.gmfhzw5zh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.562 4.879c-.875 1.53-.625 5.218 1.125 7.562");
}

.h66atab_c {
  stop-color: var(--svg-color--f89c20, #F89C20);
}

.ijc3j1q_h {
  cx: 10.363px;
  cy: 9.255px;
  fill: var(--svg-color--ff93ba, #FF93BA);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 1.759px;
  ry: 0.342px;
}

.j0jx7sb_q {
  stop-color: var(--svg-color--ffa7c7, #FFA7C7);
}

.jfj6r2hbo {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M16.642 13.062v5.457c0 .904 1.095 1.332 1.645.613c1.401-1.833 2.44-4 1.15-5.785c-.502-.695-1.45-1.15-2.248-1.045c-.355.047-.547.401-.547.76");
}

.jj33y33qm {
  d: path("M18.97 5.73c-.878-.302-2.662-1.347-2.917-3.917c-.04-.382-.377-.673-.774-.683c-2.974-.08-4.696 3.072-5.48 4.638c-.329.423-.805.412-1.141.02c-.5-.582-.305-2.158-1.446-1.646c-3.26 1.465-5.195 5.3-5.195 9.758c0 7.64 11.09 14.004 13.25 15.138c.224.12 1.261.223 1.688 0c2.17-1.134 13.062-7.499 13.062-15.138c0-5.25-4.186-8.714-8.861-10.531c-.51-.201-1.07.16-1.07.702l-.077.925c-.039.383-.502.918-1.039.734");
}

.jsmylfx_n {
  cx: 23.67px;
  cy: 13.519px;
  rx: 3.589px;
  ry: 2.47px;
}

.kskw-5bws {
  stop-color: var(--svg-color--f89c20, #F89C20);
  stop-opacity: 0;
}

.lj35z3s3o {
  stop-color: var(--svg-color--b91d43, #B91D43);
}

.lr_grnbee {
  stop-color: var(--svg-color--f8ec1d, #F8EC1D);
}

.m6aeaac_i {
  cx: 22.274px;
  cy: 9.255px;
  fill: var(--svg-color--ff93ba, #FF93BA);
  rx: 1.759px;
  ry: 0.342px;
}

.nwq74cdll {
  stop-color: var(--svg-color--ffa7c7, #FFA7C7);
  stop-opacity: 0;
}

.p775idh0b {
  cx: 14.011px;
  cy: 15.149px;
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 4.124px;
  ry: 2.225px;
}

.p9wngpb_m {
  stop-color: var(--svg-color--ffdd89, #FFDD89);
  stop-opacity: 0;
}

.pl211ybaw {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
}

.qnbh2pn9v {
  stop-color: var(--svg-color--ff73a6, #FF73A6);
  stop-opacity: 0;
}

.qpkt06btb {
  stop-color: var(--svg-color--ffd56c, #FFD56C);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r-3kexbeb {
  stop-color: var(--svg-color--ff4ec6, #FF4EC6);
}

.rc14lyykt {
  stop-color: var(--svg-color--ffe39e, #FFE39E);
}

.rwk4h8bkd {
  stop-color: var(--svg-color--ffe39e, #FFE39E);
  stop-opacity: 0;
}

.s_lt5g8hq {
  d: path("M15.247 28.967a1.71 1.71 0 0 0 1.708-.02c3.107-1.8 8.368-5.83 10.45-11.044c3.095-6.874-4.171-12.362-9.194-8.415c-.499.392-1.12.838-1.57 1.265c-.241.23-.664.254-.913.032a22 22 0 0 0-2.057-1.581c-4.282-2.897-12.072.921-8.75 9.07c1.204 3.618 6.89 8.732 10.326 10.693");
}

.sr1zclb6u {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M9.219 14.379c-3.23-2.5-3.103-8.208-1.53-9.678c.055-.05.14-.017.155.055c.468 2.213 1.797 3.465 4.468 4.091c-2.3.55-2.552 4.865-3.093 5.532");
}

.tc1s5bc7g {
  d: path("M15.812 10.222c-3.504-3.23-2.135-7.054-.5-8.43c.057-.048.142-.013.157.06c.725 3.566 2.649 4.489 5.343 5.12c-2.3.55-4.458 2.584-5 3.25");
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

</style>
