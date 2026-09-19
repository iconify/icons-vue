<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ie7Icqd)" clip-rule="evenodd" class="c3puettkh"/><path fill="url(#iioGqMc)" clip-rule="evenodd" class="g-pjbdbvu"/><path fill="url(#iT2hHFd)" class="ddrd0hzza"/><g filter="url(#i97svId)"><path class="la-5yxvvw"/></g><g filter="url(#iZfs3vi)"><path class="jey062jpl"/></g><path fill="url(#i8lVswn)" class="tjkgnbc7g"/><path fill="url(#iQVpwPd)" class="n2swj2bou"/><g filter="url(#iqI0vgd)"><path class="f_jewd1hc"/></g><g filter="url(#ihxQzve)"><path class="lhguti6iu"/></g><g filter="url(#iPYCnCe)" class="mc2zb0bvp"><path class="s1f6779qj"/></g><g filter="url(#iqZsrLr)" class="mc2zb0bvp"><path class="cinoa9bon"/></g><g filter="url(#iz4auFL)" class="mc2zb0bvp"><path class="q93_bbbci"/></g><g filter="url(#iyztDLd)" class="mc2zb0bvp"><path class="h-r0q48lr"/></g><g filter="url(#iZGrb3d)" class="mc2zb0bvp"><path class="wabowgbzo"/></g><g filter="url(#iPsXpeb)" class="z4n2hhy8u"><path class="dfkby_bro"/></g><g filter="url(#ilMzZGd)" class="z4n2hhy8u"><path class="buffyip_b"/></g><g filter="url(#iChlCcc)"><path class="qvd5rjbds"/></g><g filter="url(#idtCM3b)"><path class="j5n4x5svh"/></g><defs><filter id="i97svId" width="4" height="6" x="8.5" y="12.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><filter id="iZfs3vi" width="4" height="6" x="18.5" y="12.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><filter id="iqI0vgd" width="1.5" height="3.5" x="10.5" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".25"/></filter><filter id="ihxQzve" width="1.5" height="3.5" x="20.5" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".25"/></filter><filter id="iPYCnCe" width="6.75" height="8" x="18.5" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><filter id="iqZsrLr" width="3" height="5" x="11.5" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><filter id="iz4auFL" width="3" height="7" x="22.5" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><filter id="iyztDLd" width="3" height="3.5" x="25.5" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><filter id="iZGrb3d" width="3" height="6.5" x="27.75" y="9.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><filter id="iPsXpeb" width="8.75" height="16.5" x="1.5" y="9.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".375"/></filter><filter id="ilMzZGd" width="14.75" height="6.75" x="9.25" y="20" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".375"/></filter><filter id="iChlCcc" width="3" height="4" x="8.5" y="2.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><filter id="idtCM3b" width="3" height="4" x="21.5" y="2.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1496" stdDeviation=".5"/></filter><linearGradient id="ie7Icqd" x1="12" x2="12" y1="26" y2="28.848" gradientUnits="userSpaceOnUse"><stop class="s0wg06bhw"/><stop offset=".353" class="rjifkrlrm"/><stop offset="1" class="lu6exk1iq"/></linearGradient><linearGradient id="iioGqMc" x1="22.5" x2="22.5" y1="3.061" y2="6" gradientUnits="userSpaceOnUse"><stop class="nq3yjmb0u"/><stop offset=".629" class="q9fiad4fb"/><stop offset=".993" class="bh-4izm3a"/></linearGradient><linearGradient id="iT2hHFd" x1="16" x2="16" y1="3.061" y2="28.848" gradientUnits="userSpaceOnUse"><stop class="xu_t1hrzq"/><stop offset="1" class="slbw_3cvy"/></linearGradient><linearGradient id="i8lVswn" x1="11.485" x2="10" y1="14.965" y2="14.965" gradientUnits="userSpaceOnUse"><stop offset=".041" class="jy6-t37sm"/><stop offset="1" class="i63g2jb0q"/></linearGradient><linearGradient id="iQVpwPd" x1="21.485" x2="20" y1="14.965" y2="14.965" gradientUnits="userSpaceOnUse"><stop offset=".041" class="jy6-t37sm"/><stop offset="1" class="i63g2jb0q"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:alien-monster" /></template>
<style>
.bh-4izm3a {
  stop-color: var(--svg-color--5c48af, #5C48AF);
}

.buffyip_b {
  stroke: var(--svg-color--64389f, #64389F);
  stroke-linecap: round;
  d: path("M10.5 21.25h11.25a1 1 0 0 1 1 1v3.25");
}

.c3puettkh {
  fill-rule: evenodd;
  d: path("M13 29.03h-1.01c-1.1 0-1.99-.89-1.99-1.99v-.44c0-.31.26-.57.57-.57H13c.55 0 1 .45 1 1v1c0 .55-.45 1-1 1m5-1v-1c0-.55.45-1 1-1h2.43c.31 0 .57.25.57.57v.46c0 1.09-.88 1.97-1.97 1.97H19c-.55 0-1-.45-1-1");
}

.cinoa9bon {
  stroke: var(--svg-color--8d8ccb, #8D8CCB);
  d: path("M13 10V7");
}

.ddrd0hzza {
  d: path("M29 10.03c-.55 0-1 .45-1 1v1.43c0 .32-.26.57-.57.57h-1.86c-.3 0-.56-.21-.6-.51a4 4 0 0 0-3.5-3.46c-.27-.03-.47-.28-.47-.56V6.57c0-.31-.26-.57-.57-.57h-.36C18.93 6 18 6.93 18 8.07v.39c0 .32-.26.57-.57.57h-2.86a.57.57 0 0 1-.57-.57v-.34C14 6.95 13.05 6 11.88 6h-.3c-.32 0-.58.26-.58.57V8.5c0 .28-.2.53-.47.56c-1.82.23-3.29 1.64-3.53 3.45c-.04.29-.3.5-.6.51l-1.8.01c-.32 0-.57-.25-.57-.57v-1.43c0-.55-.45-1-1-1H3c-.55 0-1 .45-1 1v4c0 .55.45.97 1 .97h.43c.31 0 .57.29.57.6v.43c0 1.1.9 2 2 2h.43c.31 0 .57.26.57.57v4.43c0 1.1.9 2 2 2h.43c.32 0 .57-.26.57-.57V22.6c0-.32.26-.57.57-.57h10.86c.32 0 .57.26.57.57v2.86c0 .32.26.57.57.57h.44c1.1 0 1.99-.89 1.99-1.99V19.6c0-.32.26-.57.57-.57h.46c1.09 0 1.97-.88 1.97-1.97v-.46c0-.32.26-.57.57-.57H29c.55 0 1-.45 1-1v-4c0-.55-.45-1-1-1");
}

.dfkby_bro {
  stroke: var(--svg-color--6539a0, #6539A0);
  stroke-linecap: round;
  d: path("M2.75 11v3.75a.5.5 0 0 0 .5.5h.5a1 1 0 0 1 1 1v1a1 1 0 0 0 1 1h1a1 1 0 0 1 1 1v5.25a.5.5 0 0 0 .5.5H9");
}

.f_jewd1hc {
  fill: var(--svg-color--654e5d, #654E5D);
  d: path("M11 13.5h.5V16H11z");
}

.ft5dv1b6b {
  fill: none;
}

.g-pjbdbvu {
  fill-rule: evenodd;
  d: path("M9 3h1c.55 0 1 .45 1 1v1.43c0 .31-.26.57-.57.57H9c-.55 0-1-.45-1-1V4c0-.55.45-1 1-1m15 1v1c0 .55-.45 1-1 1h-1.43c-.31 0-.57-.26-.57-.57V4c0-.55.45-1 1-1h1c.55 0 1 .45 1 1");
}

.h-r0q48lr {
  stroke: var(--svg-color--8d8ccb, #8D8CCB);
  d: path("M27 16v1.5");
}

.i63g2jb0q {
  stop-color: var(--svg-color--472a34, #472A34);
}

.j5n4x5svh {
  stroke: var(--svg-color--8d8ccb, #8D8CCB);
  d: path("M23 3.5v2");
}

.jey062jpl {
  fill: var(--svg-color--533787, #533787);
  d: path("M20.5 17.5c-.555 0-1-.453-1-1.018v-1.964c0-.565.445-1.018 1-1.018s1 .453 1 1.018v1.964a1 1 0 0 1-1 1.018");
}

.jy6-t37sm {
  stop-color: var(--svg-color--574151, #574151);
}

.la-5yxvvw {
  fill: var(--svg-color--533787, #533787);
  d: path("M10.5 17.5c-.554 0-1-.453-1-1.018v-1.964c0-.565.446-1.018 1-1.018s1 .453 1 1.018v1.964a1 1 0 0 1-1 1.018");
}

.lhguti6iu {
  fill: var(--svg-color--654e5d, #654E5D);
  d: path("M21 13.5h.5V16H21z");
}

.lu6exk1iq {
  stop-color: var(--svg-color--6a30a1, #6A30A1);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n2swj2bou {
  d: path("M21 17c-.555 0-1-.453-1-1.018v-1.964c0-.565.445-1.018 1-1.018s1 .453 1 1.018v1.964A1 1 0 0 1 21 17");
}

.nq3yjmb0u {
  stop-color: var(--svg-color--6e70a5, #6E70A5);
}

.q93_bbbci {
  stroke: var(--svg-color--8d8ccb, #8D8CCB);
  d: path("M24 19v5");
}

.q9fiad4fb {
  stop-color: var(--svg-color--6a59b4, #6A59B4);
}

.qvd5rjbds {
  stroke: var(--svg-color--8d8ccb, #8D8CCB);
  d: path("M10 3.5v2");
}

.rjifkrlrm {
  stop-color: var(--svg-color--6c4d89, #6C4D89);
}

.s0wg06bhw {
  stop-color: var(--svg-color--583b70, #583B70);
}

.s1f6779qj {
  stroke: var(--svg-color--8d8ccb, #8D8CCB);
  d: path("M20 7v3h1.75a2 2 0 0 1 2 2v1");
}

.slbw_3cvy {
  stop-color: var(--svg-color--6f50a2, #6F50A2);
}

.tjkgnbc7g {
  d: path("M11 17c-.555 0-1-.453-1-1.018v-1.964c0-.565.445-1.018 1-1.018s1 .453 1 1.018v1.964A1 1 0 0 1 11 17");
}

.wabowgbzo {
  stroke: var(--svg-color--8d8ccb, #8D8CCB);
  d: path("M29.25 10.5V15");
}

.xu_t1hrzq {
  stop-color: var(--svg-color--746bb1, #746BB1);
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

</style>
