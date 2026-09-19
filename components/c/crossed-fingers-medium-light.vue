<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBlh4qd)" class="wfl5wx7hb"/><path fill="url(#ip4Alse)" class="wfl5wx7hb"/><path fill="url(#i1LyMkd)" class="wfl5wx7hb"/><path fill="url(#iYD8vKb)" class="wfl5wx7hb"/><path fill="url(#iSQZLKe)" class="wfl5wx7hb"/><path fill="url(#isq2GLU)" class="wfl5wx7hb"/><g filter="url(#ipprWEb)"><path class="qlhjp1p2p"/></g><g filter="url(#iGNVMae)"><path class="nhnuc82hc"/><path fill="url(#i1jPNLS)" class="o-r-8bb8u"/><path fill="url(#ivVt94d)" class="o-r-8bb8u"/><path fill="url(#iI7gbKb)" class="o-r-8bb8u"/></g><g filter="url(#ivfa5eb)"><path class="xyy5iib7i"/></g><g filter="url(#iLaQVld)"><path class="vld922zqj"/></g><g filter="url(#iWV1nBe)"><path class="tja74n3rh"/></g><path class="ilbyrbbnd"/><path fill="url(#iLRT9ie)" class="shd1pcihy"/><path fill="url(#ieOQJ9d)" class="shd1pcihy"/><path fill="url(#iiCIjZc)" class="shd1pcihy"/><path fill="url(#iQThCZb)" class="shd1pcihy"/><path class="yq7198bxo"/><path fill="url(#ifYyZbA)" class="ab57labcn"/><path fill="url(#ixLsCKb)" class="ab57labcn"/><path fill="url(#io50G1d)" class="ab57labcn"/><g filter="url(#iwbwKae)"><path class="is7t50bcw"/></g><path fill="url(#in6Trqb)" class="i_i99zb_b"/><path fill="url(#iYbF4Nd)" class="i_i99zb_b"/><path fill="url(#ijN25Yc)" class="i_i99zb_b"/><path fill="url(#ihfLp5f)" class="i_i99zb_b"/><g filter="url(#iKEnKuE)"><rect fill="url(#i94DBkb)" class="begnnabtr"/></g><g filter="url(#iDMOWvd)"><rect class="f1pwmg1vx"/></g><path fill="url(#iBc9Sed)" class="ppxi3hbyy"/><path fill="url(#iPgcuHd)" class="ppxi3hbyy"/><g filter="url(#ixT0Njc)"><path stroke="url(#iWLRAMe)" class="u1id6-2yn"/></g><path fill="url(#ie19tLc)" class="fbe_pkbss"/><path fill="url(#ipyWIYb)" class="fbe_pkbss"/><defs><radialGradient id="ip4Alse" cx="0" cy="0" r="1" gradientTransform="rotate(-145.784 13.28 1.689)scale(7.55811 20.3298)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="r6shb2dsi"/><stop offset="1" class="fhbxyx9ha"/></radialGradient><radialGradient id="i1LyMkd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44892 .96594 -7.83612 -11.75422 20.126 11.329)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="yanezzb1i"/><stop offset="1" class="hqo9m3buv"/></radialGradient><radialGradient id="iYD8vKb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0767 .48941 -3.97031 -8.73467 20.016 11.897)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="k6gfwsb2k"/><stop offset=".652" class="ox-4blbft"/></radialGradient><radialGradient id="iSQZLKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.26935 1.63468 0 19.197 14.561)" gradientUnits="userSpaceOnUse"><stop class="nkjzf0b6u"/><stop offset="1" class="hxbh8kxkb"/></radialGradient><radialGradient id="isq2GLU" cx="0" cy="0" r="1" gradientTransform="rotate(128.409 12.367 7.35)scale(3.53833 4.6463)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="at62h09-a"/><stop offset="1" class="tjvo8fbqd"/></radialGradient><radialGradient id="i1jPNLS" cx="0" cy="0" r="1" gradientTransform="matrix(9.31253 10.06253 -14.13907 13.08522 6.687 14.29)" gradientUnits="userSpaceOnUse"><stop class="pg2oiun8s"/><stop offset="1" class="x6madwiix"/></radialGradient><radialGradient id="ivVt94d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53125 0 0 -2.78125 20.704 20.5)" gradientUnits="userSpaceOnUse"><stop class="h3ob7cbsq"/><stop offset="1" class="t2t5_41bj"/></radialGradient><radialGradient id="iI7gbKb" cx="0" cy="0" r="1" gradientTransform="matrix(.61472 -8.4666 16.95696 1.23117 14.364 29.684)" gradientUnits="userSpaceOnUse"><stop class="tg-f5p2um"/><stop offset="1" class="oo_zx1bzl"/></radialGradient><radialGradient id="ieOQJ9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.14698 -4.32661 0 8.614 10.25)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="x32yq_bvf"/><stop offset="1" class="shadloymm"/></radialGradient><radialGradient id="iiCIjZc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.375 0 0 -3.75 10.874 12.459)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="gecp7ebgl"/><stop offset="1" class="tttmr5g8j"/></radialGradient><radialGradient id="ifYyZbA" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.80191 -4.23235 0 13.174 9.322)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="oa6vubbod"/><stop offset="1" class="lnrayldzw"/></radialGradient><radialGradient id="io50G1d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16274 -.82077 1.14253 -1.61856 15.598 15.637)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="ayp266b7l"/><stop offset="1" class="akue_eplq"/></radialGradient><radialGradient id="in6Trqb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36442 6.31216 -14.65791 -5.49058 23.382 14.66)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="p-a6fabqo"/><stop offset="1" class="wy9zyrb9z"/></radialGradient><radialGradient id="ijN25Yc" cx="0" cy="0" r="1" gradientTransform="matrix(2.53066 1.77831 -3.77054 5.36574 14.657 14.372)" gradientUnits="userSpaceOnUse"><stop class="irr6_ucxz"/><stop offset="1" class="oprjbyrit"/></radialGradient><radialGradient id="ihfLp5f" cx="0" cy="0" r="1" gradientTransform="matrix(.90292 -.5788 .91809 1.43221 15.386 17.67)" gradientUnits="userSpaceOnUse"><stop class="nt4zvzfwx"/><stop offset="1" class="kysl153tu"/></radialGradient><radialGradient id="iBc9Sed" cx="0" cy="0" r="1" gradientTransform="matrix(17.92986 -4.46025 4.67365 18.78772 8.247 18.119)" gradientUnits="userSpaceOnUse"><stop offset=".876" class="gm636achl"/><stop offset="1" class="fb9ar7bup"/></radialGradient><radialGradient id="iPgcuHd" cx="0" cy="0" r="1" gradientTransform="matrix(-16.56248 5.49997 -10.06467 -30.30848 23 17.996)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="w1owp3bda"/><stop offset="1" class="yu4rfcbbo"/></radialGradient><radialGradient id="ie19tLc" cx="0" cy="0" r="1" gradientTransform="matrix(2.53891 -1.50963 7.16354 12.04777 18.266 9.404)" gradientUnits="userSpaceOnUse"><stop class="vce1meq1x"/><stop offset="1" class="w56pk0bgz"/></radialGradient><radialGradient id="ipyWIYb" cx="0" cy="0" r="1" gradientTransform="matrix(1.99614 3.81794 -5.7135 2.9872 16.285 1.838)" gradientUnits="userSpaceOnUse"><stop class="jauq-ac4b"/><stop offset="1" class="h-pzy4f_z"/></radialGradient><filter id="ipprWEb" width="9.747" height="10.915" x="17.084" y="1.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2255" stdDeviation="1"/></filter><filter id="iGNVMae" width="20.855" height="28.601" x="5.823" y="1.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.47451 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2255"/></filter><filter id="ivfa5eb" width="14.735" height="10.475" x="11.706" y="12.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2255" stdDeviation="1"/></filter><filter id="iLaQVld" width="7.158" height="9.171" x="5.375" y="8.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2255" stdDeviation=".5"/></filter><filter id="iWV1nBe" width="9.128" height="11.13" x="7.827" y="8.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2255" stdDeviation="1"/></filter><filter id="iwbwKae" width="11.372" height="22.961" x="15.73" y=".988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2255" stdDeviation="1"/></filter><filter id="iKEnKuE" width="3.86" height="6.984" x="7.217" y="8.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2255" stdDeviation=".625"/></filter><filter id="iDMOWvd" width="5.193" height="8.957" x="11.629" y="7.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2255" stdDeviation=".875"/></filter><filter id="ixT0Njc" width="11.553" height="9.797" x="15.735" y="12.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2255" stdDeviation="1"/></filter><linearGradient id="iBlh4qd" x1="16.8" x2="25.028" y1="15.813" y2="3.045" gradientUnits="userSpaceOnUse"><stop class="z1ue1p8kp"/><stop offset="1" class="j9j0k-qyr"/></linearGradient><linearGradient id="iLRT9ie" x1="5.823" x2="8.155" y1="13.115" y2="13.115" gradientUnits="userSpaceOnUse"><stop class="iaqyn4gnc"/><stop offset="1" class="j29bp6b0k"/></linearGradient><linearGradient id="iQThCZb" x1="5.495" x2="9.238" y1="12.78" y2="12.78" gradientUnits="userSpaceOnUse"><stop class="ygyw0w6ry"/><stop offset=".25" class="co-smcbqs"/></linearGradient><linearGradient id="ixLsCKb" x1="9.944" x2="12.707" y1="12.62" y2="12.62" gradientUnits="userSpaceOnUse"><stop class="vlta00d1v"/><stop offset="1" class="tnnzrj4wa"/></linearGradient><linearGradient id="iYbF4Nd" x1="23.378" x2="23.378" y1="22.989" y2="19.912" gradientUnits="userSpaceOnUse"><stop class="ye6vdexnj"/><stop offset="1" class="c-egdjb5i"/></linearGradient><linearGradient id="i94DBkb" x1="9.497" x2="9.497" y1="14.317" y2="10.246" gradientUnits="userSpaceOnUse"><stop class="qrija3blo"/><stop offset="1" class="sotznib2z"/></linearGradient><linearGradient id="iWLRAMe" x1="17.666" x2="27.234" y1="15.76" y2="20.125" gradientUnits="userSpaceOnUse"><stop class="wzfdw2luh"/><stop offset="1" class="xznyxnbwm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crossed-fingers-medium-light" /></template>
<style>
.ab57labcn {
  d: path("M10.335 10.673c0-1.646 1.27-2.98 2.84-2.98c1.567 0 2.839 1.334 2.839 2.98v2.743c0 1.646-1.272 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.akue_eplq {
  stop-color: var(--svg-color--ac6848, #AC6848);
  stop-opacity: 0;
}

.at62h09-a {
  stop-color: var(--svg-color--f4c8a0, #F4C8A0);
}

.ayp266b7l {
  stop-color: var(--svg-color--ac6848, #AC6848);
}

.begnnabtr {
  width: 1.36px;
  height: 4.484px;
  x: 8.467px;
  y: 10.246px;
  rx: 0.68px;
}

.c-egdjb5i {
  stop-color: var(--svg-color--d69c8e, #D69C8E);
  stop-opacity: 0;
}

.co-smcbqs {
  stop-color: var(--svg-color--dea587, #DEA587);
  stop-opacity: 0;
}

.f1pwmg1vx {
  width: 1.693px;
  height: 5.457px;
  x: 13.379px;
  y: 9.273px;
  fill: var(--svg-color--ffd0a9, #FFD0A9);
  rx: 0.847px;
}

.fb9ar7bup {
  stop-color: var(--svg-color--f9c9a0, #F9C9A0);
}

.fbe_pkbss {
  d: path("M20.125 13.24c1.027.112 3.18.378 4.78 2.76c.886-7.739-4.406-12.815-4.406-12.815c-.727-1.148-2.47-1.859-3.946-.898c-1.135.739-1.937 2.414-.515 4.305c1.979 2.63 3.582 5.307 4.087 6.648");
}

.fhbxyx9ha {
  stop-color: var(--svg-color--c39472, #C39472);
}

.ft5dv1b6b {
  fill: none;
}

.gecp7ebgl {
  stop-color: var(--svg-color--b77c58, #B77C58);
}

.gm636achl {
  stop-color: var(--svg-color--f9c9a0, #F9C9A0);
  stop-opacity: 0;
}

.h-pzy4f_z {
  stop-color: var(--svg-color--c49777, #C49777);
  stop-opacity: 0;
}

.h3ob7cbsq {
  stop-color: var(--svg-color--e4ab99, #E4AB99);
}

.hqo9m3buv {
  stop-color: var(--svg-color--c17b56, #C17B56);
  stop-opacity: 0;
}

.hxbh8kxkb {
  stop-color: var(--svg-color--e8b691, #E8B691);
  stop-opacity: 0;
}

.i_i99zb_b {
  d: path("M17.827 13.24a2.984 2.984 0 0 0 0 5.969h1.59a1 1 0 0 1 .788.385l2.044 2.621c1.17 1.501 3.578.674 3.578-1.23V19.24a6 6 0 0 0-5.212-5.949a3 3 0 0 0-.554-.051z");
}

.iaqyn4gnc {
  stop-color: var(--svg-color--c99976, #C99976);
}

.ilbyrbbnd {
  fill: var(--svg-color--d7a783, #D7A783);
  d: path("M5.823 11.424c0-1.43 1.25-2.59 2.79-2.59c1.542 0 2.792 1.16 2.792 2.59v2.383c0 1.43-1.25 2.59-2.791 2.59c-1.542 0-2.791-1.16-2.791-2.59z");
}

.irr6_ucxz {
  stop-color: var(--svg-color--c68d69, #C68D69);
}

.is7t50bcw {
  stroke: var(--svg-color--ffd1a9, #FFD1A9);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.73 3.988c2.11 2.245 4.896 6.194 5.22 9.602c.345 3.617 0 5.966 0 7.36");
}

.j29bp6b0k {
  stop-color: var(--svg-color--c99976, #C99976);
  stop-opacity: 0;
}

.j9j0k-qyr {
  stop-color: var(--svg-color--f1be98, #F1BE98);
}

.jauq-ac4b {
  stop-color: var(--svg-color--c49777, #C49777);
}

.k6gfwsb2k {
  stop-color: var(--svg-color--cc8b65, #CC8B65);
}

.kysl153tu {
  stop-color: var(--svg-color--c98e7e, #C98E7E);
  stop-opacity: 0;
}

.lnrayldzw {
  stop-color: var(--svg-color--b77379, #B77379);
}

.nhnuc82hc {
  fill: var(--svg-color--d59a8d, #D59A8D);
  d: path("m6.01 20.559l-.187-5.114V13.89H20.29c.01-.844-1.843-4.116-4.253-7.32c-1.422-1.891-.62-3.566.515-4.305c1.477-.961 3.051-.16 3.946.898c0 0 5.636 5.93 5.636 13.304c.127 4.64.032 5.398-1.219 7.86c-1.815 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.471-4.138-9.659-9.125");
}

.nkjzf0b6u {
  stop-color: var(--svg-color--e8b691, #E8B691);
}

.nt4zvzfwx {
  stop-color: var(--svg-color--c98e7e, #C98E7E);
}

.o-r-8bb8u {
  d: path("m6.01 20.559l-.187-5.114V13.89H20.29c.01-.844-1.843-4.116-4.253-7.32c-1.422-1.891-.62-3.566.515-4.305c1.477-.961 3.051-.16 3.946.898c0 0 5.636 5.93 5.636 13.304c.127 4.64.032 5.398-1.219 7.86c-1.815 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.471-4.138-9.659-9.125");
}

.oa6vubbod {
  stop-color: var(--svg-color--b77379, #B77379);
  stop-opacity: 0;
}

.oo_zx1bzl {
  stop-color: var(--svg-color--dc9e96, #DC9E96);
  stop-opacity: 0;
}

.oprjbyrit {
  stop-color: var(--svg-color--c68d69, #C68D69);
  stop-opacity: 0;
}

.ox-4blbft {
  stop-color: var(--svg-color--cc8b65, #CC8B65);
  stop-opacity: 0;
}

.p-a6fabqo {
  stop-color: var(--svg-color--eebc91, #EEBC91);
}

.pg2oiun8s {
  stop-color: var(--svg-color--bf8574, #BF8574);
}

.ppxi3hbyy {
  d: path("m6.01 20.578l-.187-5.114v-1.556h.002c.06 1.382 1.285 2.485 2.789 2.485c.967 0 1.819-.456 2.32-1.15c.52.7 1.33 1.15 2.24 1.15c1.407 0 2.576-1.075 2.8-2.485h4.317c.01-.843-1.843-4.115-4.253-7.32c-1.422-1.89-.62-3.565.515-4.305c1.477-.96 3.219-.25 3.946.899c0 0 5.636 5.93 5.636 13.304c.127 4.64.032 5.398-1.219 7.86c-1.815 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.471-4.138-9.659-9.125");
}

.qlhjp1p2p {
  stroke: var(--svg-color--fac9a2, #FAC9A2);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M23.581 4.419c-.929 1.151-1.946 2.619-3.247 4.415");
}

.qrija3blo {
  stop-color: var(--svg-color--dfac98, #DFAC98);
}

.r6shb2dsi {
  stop-color: var(--svg-color--c39472, #C39472);
  stop-opacity: 0;
}

.shadloymm {
  stop-color: var(--svg-color--b97679, #B97679);
}

.shd1pcihy {
  d: path("M5.823 11.424c0-1.43 1.25-2.59 2.79-2.59c1.542 0 2.792 1.16 2.792 2.59v2.383c0 1.43-1.25 2.59-2.791 2.59c-1.542 0-2.791-1.16-2.791-2.59z");
}

.sotznib2z {
  stop-color: var(--svg-color--dfac98, #DFAC98);
  stop-opacity: 0;
}

.t2t5_41bj {
  stop-color: var(--svg-color--e4ab99, #E4AB99);
  stop-opacity: 0;
}

.tg-f5p2um {
  stop-color: var(--svg-color--dc9e96, #DC9E96);
}

.tja74n3rh {
  fill: var(--svg-color--a26057, #A26057);
  d: path("M9.827 12.673c0-1.348 1.148-2.441 2.564-2.441s2.564 1.093 2.564 2.441v2.247c0 1.348-1.148 2.441-2.564 2.441s-2.564-1.093-2.564-2.441z");
}

.tjvo8fbqd {
  stop-color: var(--svg-color--f4c8a0, #F4C8A0);
  stop-opacity: 0;
}

.tnnzrj4wa {
  stop-color: var(--svg-color--b98361, #B98361);
  stop-opacity: 0;
}

.tttmr5g8j {
  stop-color: var(--svg-color--b77c58, #B77C58);
  stop-opacity: 0;
}

.u1id6-2yn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.735 15.76h.615c2.03 0 4.2.588 4.723 2.548c.1.372.175.788.215 1.25");
}

.vce1meq1x {
  stop-color: var(--svg-color--cb8658, #CB8658);
}

.vld922zqj {
  fill: var(--svg-color--a26057, #A26057);
  d: path("M6.375 11.915c0-1.357 1.155-2.456 2.58-2.456c1.424 0 2.578 1.1 2.578 2.456v2.26c0 1.356-1.154 2.455-2.579 2.455c-1.424 0-2.579-1.1-2.579-2.456z");
}

.vlta00d1v {
  stop-color: var(--svg-color--b98361, #B98361);
}

.w1owp3bda {
  stop-color: var(--svg-color--dea288, #DEA288);
  stop-opacity: 0;
}

.w56pk0bgz {
  stop-color: var(--svg-color--cb8658, #CB8658);
  stop-opacity: 0;
}

.wfl5wx7hb {
  d: path("M20.811 2.67c-2.136 2.178-4.64 5.148-5.515 8.633l-.223 2.765h5.03c1.032-1.823 2.813-5.32 4.575-7.305s.555-3.777-.066-4.308a2.68 2.68 0 0 0-3.8.215");
}

.wy9zyrb9z {
  stop-color: var(--svg-color--b57079, #B57079);
}

.wzfdw2luh {
  stop-color: var(--svg-color--ffd0ac, #FFD0AC);
}

.x32yq_bvf {
  stop-color: var(--svg-color--b97679, #B97679);
  stop-opacity: 0;
}

.x6madwiix {
  stop-color: var(--svg-color--bf8574, #BF8574);
  stop-opacity: 0;
}

.xyy5iib7i {
  fill: var(--svg-color--a26057, #A26057);
  d: path("M16.842 14.865c-1.732 0-3.136 1.246-3.136 2.782s1.404 2.783 3.136 2.783h1.671c2.525 0 3.18.132 3.379.359l1.536-.178c1.23 1.4.995.652.995-1.122v-.505c0-2.84-1.56-3.711-4.65-4.071a3.6 3.6 0 0 0-.583-.048z");
}

.xznyxnbwm {
  stop-color: var(--svg-color--ffd0ac, #FFD0AC);
  stop-opacity: 0;
}

.yanezzb1i {
  stop-color: var(--svg-color--c17b56, #C17B56);
}

.ye6vdexnj {
  stop-color: var(--svg-color--d69c8e, #D69C8E);
}

.ygyw0w6ry {
  stop-color: var(--svg-color--dea587, #DEA587);
}

.yq7198bxo {
  fill: var(--svg-color--e1ab85, #E1AB85);
  d: path("M10.335 10.673c0-1.646 1.27-2.98 2.84-2.98c1.567 0 2.839 1.334 2.839 2.98v2.743c0 1.646-1.272 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.yu4rfcbbo {
  stop-color: var(--svg-color--dea288, #DEA288);
}

.z1ue1p8kp {
  stop-color: var(--svg-color--cf8a5f, #CF8A5F);
}

</style>
