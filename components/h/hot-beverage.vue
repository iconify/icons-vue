<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3QTNGc)" class="wy1uw_bau"/><path fill="url(#iKX4NGd)" class="wy1uw_bau"/><path fill="url(#ia7Mvid)" class="wy1uw_bau"/><path fill="url(#itrCBQd)" class="wy1uw_bau"/><path fill="url(#iwVk0Kc)" class="wy1uw_bau"/><g filter="url(#iO0zsfc)"><path fill="url(#i7NexPb)" class="d1yy5cbjs"/><path fill="url(#iRaY2JU)" class="d1yy5cbjs"/><path fill="url(#iZRCNce)" class="d1yy5cbjs"/><path fill="url(#ibnXywd)" class="d1yy5cbjs"/></g><path class="ngm-gnbsf"/><path fill="url(#ih0arwe)" class="zvvrldbmv"/><path fill="url(#ic9DlQp)" class="zvvrldbmv"/><path fill="url(#iuebvbc)" class="f7pigtdct"/><path class="x0o01oaqi"/><path class="vgoeyxb6z"/><path fill="url(#ieZFtyo)" class="zn0ua3bju"/><path fill="url(#i1O7y2c)" class="zn0ua3bju"/><path fill="url(#i4EhEvc)" class="zn0ua3bju"/><g filter="url(#iaiuzmd)"><path fill="url(#ixmDTkX)" class="n6c0jgpdd"/></g><defs><radialGradient id="iKX4NGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 11.49998 -12.12653 -.26363 13.938 18.5)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="di5it8gqd"/><stop offset=".818" class="h0pk7gb7b"/></radialGradient><radialGradient id="ia7Mvid" cx="0" cy="0" r="1" gradientTransform="rotate(90 5.406 18.969)scale(8.0625)" gradientUnits="userSpaceOnUse"><stop offset=".504" class="svw0vrbrv"/><stop offset="1" class="w8k9qly1w"/></radialGradient><radialGradient id="itrCBQd" cx="0" cy="0" r="1" gradientTransform="matrix(6.24998 8.93748 -5.02131 3.5114 25.125 12.813)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="qra_subfn"/><stop offset="1" class="di4rf5b8i"/></radialGradient><radialGradient id="iRaY2JU" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 11.375 -12.21727 -.60415 14.125 18.625)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="di5it8gqd"/><stop offset=".818" class="h0pk7gb7b"/></radialGradient><radialGradient id="iZRCNce" cx="0" cy="0" r="1" gradientTransform="rotate(64.428 -7.57 19.875)scale(11.2938 10.2545)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="frfoyf08o"/><stop offset=".989" class="jrcy176rw"/></radialGradient><radialGradient id="ibnXywd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.66814 -7.81055 0 24.05 13.929)" gradientUnits="userSpaceOnUse"><stop offset=".504" class="svw0vrbrv"/><stop offset="1" class="w8k9qly1w"/></radialGradient><radialGradient id="ih0arwe" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.55 18.5)scale(5.98)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="x0hc9fyla"/><stop offset=".793" class="n-x7s78wr"/><stop offset="1" class="k69-2z0ac"/></radialGradient><radialGradient id="ic9DlQp" cx="0" cy="0" r="1" gradientTransform="rotate(88.078 2.926 20.81)scale(9.31774 7.06691)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="g32xb05ap"/><stop offset=".907" class="ren6shbdt"/><stop offset="1" class="jcrfbgpud"/></radialGradient><radialGradient id="ieZFtyo" cx="0" cy="0" r="1" gradientTransform="rotate(90 .767 13.643)scale(12.75)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="m7cm9fbuq"/><stop offset=".623" class="wfxx9nv4c"/></radialGradient><radialGradient id="i1O7y2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 21.25 -20.035 0 14.41 12.875)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="zg_vn3b0b"/><stop offset=".405" class="fj6-jacsq"/></radialGradient><radialGradient id="i4EhEvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 15 -14.3475 0 14.41 14.875)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="zg_vn3b0b"/><stop offset=".596" class="fj6-jacsq"/></radialGradient><linearGradient id="i3QTNGc" x1="10.75" x2="21.125" y1="9.125" y2="30.875" gradientUnits="userSpaceOnUse"><stop class="n5rtz9pwq"/><stop offset=".453" class="xkob1oxpe"/><stop offset=".877" class="a6ofj8vhf"/></linearGradient><linearGradient id="iwVk0Kc" x1="15.375" x2="15.375" y1="30.5" y2="17.625" gradientUnits="userSpaceOnUse"><stop class="rqcrxjdtd"/><stop offset="1" class="c94ch7_0k"/></linearGradient><linearGradient id="i7NexPb" x1="10.852" x2="20.605" y1="9.709" y2="30.534" gradientUnits="userSpaceOnUse"><stop class="n5rtz9pwq"/><stop offset=".453" class="xkob1oxpe"/><stop offset=".877" class="a6ofj8vhf"/></linearGradient><linearGradient id="iuebvbc" x1="5.04" x2="23.8" y1="20.25" y2="20.25" gradientUnits="userSpaceOnUse"><stop class="soznorbgb"/><stop offset=".258" class="n5aifybya"/><stop offset=".644" class="cflwelx6g"/><stop offset="1" class="q1o--bbhy"/></linearGradient><linearGradient id="ixmDTkX" x1="6.13" x2="22.71" y1="10.438" y2="10.438" gradientUnits="userSpaceOnUse"><stop class="d2-chccwy"/><stop offset=".49" class="jicwevbbk"/><stop offset="1" class="xs6szvmhw"/></linearGradient><filter id="iO0zsfc" width="23.281" height="22.875" x="2.844" y="7.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30459" stdDeviation=".25"/></filter><filter id="iaiuzmd" width="24.58" height="17.33" x="2.13" y="4.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_30459"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_30459" result="shape"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hot-beverage" /></template>
<style>
.a6ofj8vhf {
  stop-color: var(--svg-color--c7bbda, #C7BBDA);
}

.c94ch7_0k {
  stop-color: var(--svg-color--ad95c8, #AD95C8);
  stop-opacity: 0;
}

.cflwelx6g {
  stop-color: var(--svg-color--b19bcb, #B19BCB);
}

.d1yy5cbjs {
  d: path("M14.484 29.563c6.153 0 11.141-4.897 11.141-10.938c0-6.04-4.988-10.937-11.14-10.937S3.343 12.584 3.343 18.624s4.988 10.938 11.14 10.938");
}

.d2-chccwy {
  stop-color: var(--svg-color--a298a8, #A298A8);
}

.di4rf5b8i {
  stop-color: var(--svg-color--d3d2d9, #D3D2D9);
  stop-opacity: 0;
}

.di5it8gqd {
  stop-color: var(--svg-color--9c8bb4, #9C8BB4);
}

.f7pigtdct {
  d: path("M21.4 12.38a9.35 9.35 0 0 0-6.98-3.13a9.37 9.37 0 0 0-6.99 3.13H5.04v5.25c0 5.17 4.21 9.38 9.38 9.38s9.38-4.21 9.38-9.38v-5.25z");
}

.fj6-jacsq {
  stop-color: var(--svg-color--552c2b, #552C2B);
}

.frfoyf08o {
  stop-color: var(--svg-color--bcb2cd, #BCB2CD);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g32xb05ap {
  stop-color: var(--svg-color--d9d6e0, #D9D6E0);
  stop-opacity: 0;
}

.h0pk7gb7b {
  stop-color: var(--svg-color--9d8fb2, #9D8FB2);
  stop-opacity: 0;
}

.jcrfbgpud {
  stop-color: var(--svg-color--d8d6e0, #D8D6E0);
  stop-opacity: 0;
}

.jicwevbbk {
  stop-color: var(--svg-color--9f8fae, #9F8FAE);
}

.jrcy176rw {
  stop-color: var(--svg-color--beb2cf, #BEB2CF);
}

.k69-2z0ac {
  stop-color: var(--svg-color--b4a3ca, #B4A3CA);
  stop-opacity: 0;
}

.m7cm9fbuq {
  stop-color: var(--svg-color--835358, #835358);
}

.n-x7s78wr {
  stop-color: var(--svg-color--af9dc6, #AF9DC6);
}

.n5aifybya {
  stop-color: var(--svg-color--b1a1c6, #B1A1C6);
}

.n5rtz9pwq {
  stop-color: var(--svg-color--99989f, #99989F);
}

.n6c0jgpdd {
  d: path("M14.41 6.16c4.22 0 7.71 3.17 8.23 7.25c.04-.34.07-.69.07-1.04c0-4.57-3.72-8.29-8.29-8.29S6.13 7.8 6.13 12.37c0 .35.02.7.07 1.04c.5-4.08 3.99-7.25 8.21-7.25");
}

.ngm-gnbsf {
  fill: var(--svg-color--bfbac9, #BFBAC9);
  d: path("M23.05 9.97c2.2 0 3.98 1.79 3.98 3.98a3.99 3.99 0 0 1-3.98 3.98a3.99 3.99 0 0 1-3.98-3.98c0-2.19 1.78-3.98 3.98-3.98m0-2c-3.3 0-5.98 2.68-5.98 5.98s2.68 5.98 5.98 5.98s5.98-2.68 5.98-5.98s-2.68-5.98-5.98-5.98");
}

.q1o--bbhy {
  stop-color: var(--svg-color--b5aec1, #B5AEC1);
}

.qra_subfn {
  stop-color: var(--svg-color--d1d0d7, #D1D0D7);
}

.ren6shbdt {
  stop-color: var(--svg-color--d8d6e0, #D8D6E0);
}

.rqcrxjdtd {
  stop-color: var(--svg-color--ad95c8, #AD95C8);
}

.soznorbgb {
  stop-color: var(--svg-color--a6a1b0, #A6A1B0);
}

.svw0vrbrv {
  stop-color: var(--svg-color--9d98a8, #9D98A8);
}

.vgoeyxb6z {
  fill: var(--svg-color--835358, #835358);
  d: path("M14.41 20.67a8.29 8.29 0 1 0 0-16.58a8.29 8.29 0 0 0 0 16.58");
}

.w8k9qly1w {
  stop-color: var(--svg-color--9f9aaa, #9F9AAA);
  stop-opacity: 0;
}

.wfxx9nv4c {
  stop-color: var(--svg-color--744c4d, #744C4D);
}

.wy1uw_bau {
  d: path("M14.5 30C20.851 30 26 24.851 26 18.5S20.851 7 14.5 7S3 12.149 3 18.5S8.149 30 14.5 30");
}

.x0hc9fyla {
  stop-color: var(--svg-color--958da3, #958DA3);
}

.x0o01oaqi {
  fill: var(--svg-color--c5bcd4, #C5BCD4);
  d: path("M14.41 21.76a9.38 9.38 0 1 0 0-18.76a9.38 9.38 0 0 0 0 18.76");
}

.xkob1oxpe {
  stop-color: var(--svg-color--a99bbe, #A99BBE);
}

.xs6szvmhw {
  stop-color: var(--svg-color--8c8191, #8C8191);
}

.zg_vn3b0b {
  stop-color: var(--svg-color--502728, #502728);
  stop-opacity: 0;
}

.zn0ua3bju {
  d: path("M14.41 20.67a8.29 8.29 0 1 0 0-16.58a8.29 8.29 0 0 0 0 16.58");
}

.zvvrldbmv {
  d: path("M23.05 9.97c2.2 0 3.98 1.79 3.98 3.98a3.99 3.99 0 0 1-3.98 3.98a3.99 3.99 0 0 1-3.98-3.98c0-2.19 1.78-3.98 3.98-3.98m0-2c-3.3 0-5.98 2.68-5.98 5.98s2.68 5.98 5.98 5.98s5.98-2.68 5.98-5.98s-2.68-5.98-5.98-5.98");
}

</style>
