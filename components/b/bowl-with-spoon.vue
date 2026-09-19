<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i74uVbe)" clip-rule="evenodd" class="zyhy7gb7h"/><path fill="url(#inkX5Ob)" clip-rule="evenodd" class="zyhy7gb7h"/><path fill="url(#iqO0Yac)" clip-rule="evenodd" class="zyhy7gb7h"/><path fill="url(#iR6R9ge)" clip-rule="evenodd" class="zyhy7gb7h"/><g filter="url(#iYiOT3b)"><path fill="url(#iUTCTJd)" class="zwkujsb5n"/><path fill="url(#iUOsCBd)" class="zwkujsb5n"/></g><path fill="url(#iIXCdtc)" class="qzrm53bma"/><path fill="url(#iPUPw9d)" class="qzrm53bma"/><g filter="url(#i2KPJfb)"><path fill="url(#iMhihke)" class="zm7kalbfl"/><path fill="url(#iMnf0Hd)" class="zm7kalbfl"/><path fill="url(#irPPpNd)" class="zm7kalbfl"/><path fill="url(#iRESE2b)" class="zm7kalbfl"/></g><path fill="url(#i10t2ge)" class="iytinxbyh"/><path fill="url(#iFIpmjc)" class="iytinxbyh"/><path fill="url(#iyEvfmc)" class="iytinxbyh"/><path fill="url(#iuYdBNe)" class="iytinxbyh"/><g filter="url(#i76utsb)"><path fill="url(#iMaez4d)" class="agh1u8gtd"/></g><g filter="url(#iZfqKac)"><path stroke="url(#i1fX2Td)" class="c6jkjrb2a"/></g><g filter="url(#iseXvwb)"><path stroke="url(#iVI4t6b)" class="oq45yk2th"/></g><defs><radialGradient id="inkX5Ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 29.9932 -24.882 0 16.031 8.382)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="ch39hql7l"/><stop offset=".892" class="adp7mk4ka"/></radialGradient><radialGradient id="iR6R9ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.8125 -16.8437 0 16.031 30.438)" gradientUnits="userSpaceOnUse"><stop class="x7dk3kb4q"/><stop offset="1" class="rhkvrha3d"/></radialGradient><radialGradient id="iUOsCBd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24998 6.9375 -6.75333 -2.19025 9.438 13.438)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="tjm6wdbii"/><stop offset=".833" class="zvga89fac"/></radialGradient><radialGradient id="iPUPw9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.125 -18.6106 0 16.031 23)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="x73ci9bga"/><stop offset="1" class="syfvz8b5t"/></radialGradient><radialGradient id="iMnf0Hd" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 .65625 -1.08947 -.57067 25.148 3)" gradientUnits="userSpaceOnUse"><stop class="n0kcloudu"/><stop offset="1" class="iq8nezvni"/></radialGradient><radialGradient id="irPPpNd" cx="0" cy="0" r="1" gradientTransform="matrix(7.375 -3.89517 3.36459 6.3704 9.68 19.989)" gradientUnits="userSpaceOnUse"><stop class="dov9oob_m"/><stop offset=".353" class="t315ibczv"/><stop offset=".862" class="mv-185but"/><stop offset="1" class="r8imsqsej"/></radialGradient><radialGradient id="iFIpmjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 .65625 -1.08947 -.57067 25.719 3)" gradientUnits="userSpaceOnUse"><stop class="n0kcloudu"/><stop offset="1" class="iq8nezvni"/></radialGradient><radialGradient id="iyEvfmc" cx="0" cy="0" r="1" gradientTransform="matrix(7.375 -3.89517 3.36459 6.3704 10.25 19.989)" gradientUnits="userSpaceOnUse"><stop class="dov9oob_m"/><stop offset=".353" class="t315ibczv"/><stop offset=".862" class="mv-185but"/><stop offset="1" class="r8imsqsej"/></radialGradient><radialGradient id="iuYdBNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53125 -1.83149 0 19.438 17.531)" gradientUnits="userSpaceOnUse"><stop class="dzrl0qsay"/><stop offset="1" class="qa1pa4bei"/></radialGradient><radialGradient id="iMaez4d" cx="0" cy="0" r="1" gradientTransform="rotate(-49.152 30.7 -3.353)scale(6.97569 3.88336)" gradientUnits="userSpaceOnUse"><stop class="m48-1fz8d"/><stop offset=".74" class="p15hx3b4i"/><stop offset=".887" class="rb2seubub"/></radialGradient><radialGradient id="i1fX2Td" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8263 -4.75 5.26197 -3.13092 28.313 19.625)" gradientUnits="userSpaceOnUse"><stop class="qoigolibk"/><stop offset="1" class="lpru3xbbb"/></radialGradient><radialGradient id="iVI4t6b" cx="0" cy="0" r="1" gradientTransform="matrix(.45311 1.67188 -2.04483 .55419 12.264 18.11)" gradientUnits="userSpaceOnUse"><stop class="mn4wgmj2v"/><stop offset="1" class="zufniuyao"/></radialGradient><linearGradient id="i74uVbe" x1="2.406" x2="29.656" y1="18" y2="18" gradientUnits="userSpaceOnUse"><stop class="bqdddgb2z"/><stop offset=".192" class="q6v3s8p0f"/><stop offset=".274" class="hqxkl8-sw"/><stop offset=".499" class="h0jetabcw"/><stop offset=".772" class="m4hrd28jc"/><stop offset=".845" class="snnjd1bnp"/><stop offset=".953" class="efdhtfboa"/><stop offset="1" class="iwzz48b1i"/></linearGradient><linearGradient id="iqO0Yac" x1="13.125" x2="13.125" y1="5.438" y2="14.25" gradientUnits="userSpaceOnUse"><stop class="quc5_gcfj"/><stop offset="1" class="wc4086uyi"/></linearGradient><linearGradient id="iUTCTJd" x1="18.205" x2="18.205" y1="6.313" y2="21.438" gradientUnits="userSpaceOnUse"><stop class="w8l-ce-gz"/><stop offset=".57" class="r9x8cy73e"/><stop offset="1" class="y_f172bgd"/></linearGradient><linearGradient id="iIXCdtc" x1="3.938" x2="28.125" y1="14.438" y2="13.821" gradientUnits="userSpaceOnUse"><stop class="v--h1sbdg"/><stop offset=".146" class="sygyo443w"/><stop offset=".272" class="bdnb2wb1d"/><stop offset=".83" class="iznaknbjx"/><stop offset="1" class="q1tof-mzt"/></linearGradient><linearGradient id="iMhihke" x1="19.742" x2="22.43" y1="8.094" y2="9.625" gradientUnits="userSpaceOnUse"><stop offset=".085" class="cj05r_7eb"/><stop offset=".368" class="opbhhyb6c"/><stop offset=".618" class="wympw1dkj"/><stop offset=".941" class="mfuw34v4v"/></linearGradient><linearGradient id="iRESE2b" x1="20.806" x2="16.637" y1="6.149" y2="19.989" gradientUnits="userSpaceOnUse"><stop offset=".062" class="e8h82sb6e"/><stop offset=".135" class="ol6i46b2e"/><stop offset="1" class="d50_b51pn"/></linearGradient><linearGradient id="i10t2ge" x1="20.313" x2="23" y1="8.094" y2="9.625" gradientUnits="userSpaceOnUse"><stop offset=".085" class="cj05r_7eb"/><stop offset=".368" class="opbhhyb6c"/><stop offset=".618" class="wympw1dkj"/><stop offset=".941" class="mfuw34v4v"/></linearGradient><filter id="iYiOT3b" width="27.506" height="15.725" x="2.263" y="6.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32561" stdDeviation=".15"/></filter><filter id="i2KPJfb" width="14.713" height="14.922" x="9.563" y="5.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32561" stdDeviation=".5"/></filter><filter id="i76utsb" width="7.126" height="3.714" x="11.406" y="16.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32561" stdDeviation=".125"/></filter><filter id="iZfqKac" width="8.719" height="7.781" x="21.031" y="14.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32561" stdDeviation=".125"/></filter><filter id="iseXvwb" width="3.375" height="4.141" x="11.391" y="16.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32561" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bowl-with-spoon" /></template>
<style>
.adp7mk4ka {
  stop-color: var(--svg-color--4d45e9, #4D45E9);
}

.agh1u8gtd {
  d: path("M16.719 17.125c-2.364-1.205-4.024 1.047-5.063 2.875h6.61c.133-.96-.523-2.353-1.547-2.875");
}

.bdnb2wb1d {
  stop-color: var(--svg-color--3c3dcb, #3C3DCB);
}

.bqdddgb2z {
  stop-color: var(--svg-color--3b74c0, #3B74C0);
}

.c6jkjrb2a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M29.25 14.781c0 .875-.057 2.822-1.469 4.469c-1.5 1.75-4.781 2.313-6.25 2.313");
}

.ch39hql7l {
  stop-color: var(--svg-color--4a45e9, #4A45E9);
  stop-opacity: 0;
}

.cj05r_7eb {
  stop-color: var(--svg-color--807e8a, #807E8A);
}

.d50_b51pn {
  stop-color: var(--svg-color--1f1e9b, #1F1E9B);
}

.dov9oob_m {
  stop-color: var(--svg-color--8a8a99, #8A8A99);
}

.dzrl0qsay {
  stop-color: var(--svg-color--bfbfca, #BFBFCA);
}

.e8h82sb6e {
  stop-color: var(--svg-color--2290d0, #2290D0);
}

.efdhtfboa {
  stop-color: var(--svg-color--53a6ff, #53A6FF);
}

.ft5dv1b6b {
  fill: none;
}

.h0jetabcw {
  stop-color: var(--svg-color--3689e8, #3689E8);
}

.hqxkl8-sw {
  stop-color: var(--svg-color--3483e7, #3483E7);
}

.iq8nezvni {
  stop-color: var(--svg-color--d7d5df, #D7D5DF);
  stop-opacity: 0;
}

.iwzz48b1i {
  stop-color: var(--svg-color--43a9ff, #43A9FF);
}

.iytinxbyh {
  d: path("M19.125 17.86c-.2-.57-.45-1.37-.11-1.86l5.704-9.875c.828-1.516 2.234-3.156.828-3.969c-1.532-.885-2.297 1.406-3.125 2.75l-5.524 9.516c-.27.57-.995.886-1.608 1.013c-2.43.502-4 2.502-4.72 4.554h8.82c0-.63-.054-1.495-.265-2.13");
}

.iznaknbjx {
  stop-color: var(--svg-color--2e30bc, #2E30BC);
}

.lpru3xbbb {
  stop-color: var(--svg-color--5fb7ff, #5FB7FF);
  stop-opacity: 0;
}

.m48-1fz8d {
  stop-color: var(--svg-color--9998a6, #9998A6);
}

.m4hrd28jc {
  stop-color: var(--svg-color--3982ea, #3982EA);
}

.mfuw34v4v {
  stop-color: var(--svg-color--b2adc2, #B2ADC2);
}

.mn4wgmj2v {
  stop-color: var(--svg-color--9e9eac, #9E9EAC);
}

.mv-185but {
  stop-color: var(--svg-color--aaa7b5, #AAA7B5);
}

.n0kcloudu {
  stop-color: var(--svg-color--d6d6dd, #D6D6DD);
}

.ol6i46b2e {
  stop-color: var(--svg-color--2731a9, #2731A9);
}

.opbhhyb6c {
  stop-color: var(--svg-color--9e98ab, #9E98AB);
}

.oq45yk2th {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.766 20.25c.25-.89.984-2.531 2.625-3.39");
}

.p15hx3b4i {
  stop-color: var(--svg-color--9796a4, #9796A4);
}

.q1tof-mzt {
  stop-color: var(--svg-color--191c97, #191C97);
}

.q6v3s8p0f {
  stop-color: var(--svg-color--2a7bdb, #2A7BDB);
}

.qa1pa4bei {
  stop-color: var(--svg-color--c0bec9, #C0BEC9);
  stop-opacity: 0;
}

.qoigolibk {
  stop-color: var(--svg-color--62b8ff, #62B8FF);
}

.quc5_gcfj {
  stop-color: var(--svg-color--29a8ea, #29A8EA);
}

.qzrm53bma {
  d: path("M22.022 7.656c3.19 0 5.79 2.953 5.79 6.165c0 3.46-2.6 6.164-5.79 6.164H10.04c-3.19 0-5.791-2.657-5.791-6.164c0-3.008 2.6-6.165 5.79-6.165z");
}

.r8imsqsej {
  stop-color: var(--svg-color--a9a5b3, #A9A5B3);
  stop-opacity: 0;
}

.r9x8cy73e {
  stop-color: var(--svg-color--2b9fee, #2B9FEE);
}

.rb2seubub {
  stop-color: var(--svg-color--646179, #646179);
}

.rhkvrha3d {
  stop-color: var(--svg-color--3b69f0, #3B69F0);
  stop-opacity: 0;
}

.snnjd1bnp {
  stop-color: var(--svg-color--4695f4, #4695F4);
}

.syfvz8b5t {
  stop-color: var(--svg-color--202096, #202096);
  stop-opacity: 0;
}

.sygyo443w {
  stop-color: var(--svg-color--5153df, #5153DF);
}

.t315ibczv {
  stop-color: var(--svg-color--9996a5, #9996A5);
}

.tjm6wdbii {
  stop-color: var(--svg-color--57bfff, #57BFFF);
}

.v--h1sbdg {
  stop-color: var(--svg-color--2f35df, #2F35DF);
}

.w8l-ce-gz {
  stop-color: var(--svg-color--26aaed, #26AAED);
}

.wc4086uyi {
  stop-color: var(--svg-color--28a8ea, #28A8EA);
  stop-opacity: 0;
}

.wympw1dkj {
  stop-color: var(--svg-color--b3acc1, #B3ACC1);
}

.x73ci9bga {
  stop-color: var(--svg-color--1f2090, #1F2090);
}

.x7dk3kb4q {
  stop-color: var(--svg-color--3f43ea, #3F43EA);
}

.y_f172bgd {
  stop-color: var(--svg-color--2f90de, #2F90DE);
}

.zm7kalbfl {
  d: path("M18.555 17.86c-.2-.57-.45-1.37-.11-1.86l4.83-9.672H21.13l-4.802 8.094c-.27.57-.995.886-1.608 1.013c-2.43.502-3.439 1.764-4.158 3.815h8.258c0-.63-.054-.756-.265-1.39");
}

.zufniuyao {
  stop-color: var(--svg-color--cfcedc, #CFCEDC);
  stop-opacity: 0;
}

.zvga89fac {
  stop-color: var(--svg-color--5dc3ff, #5DC3FF);
  stop-opacity: 0;
}

.zwkujsb5n {
  d: path("M21.863 6.313H10.2c-4.301 0-7.637 3.389-7.637 7.562s3.336 7.563 7.637 7.563h11.663c4.3 0 7.606-3.39 7.606-7.563s-3.295-7.562-7.606-7.562");
}

.zyhy7gb7h {
  fill-rule: evenodd;
  d: path("M10.2 6h11.663c4.311 0 7.793 3.382 7.793 7.546v5.321c0 6.15-4.593 11.133-10.992 11.133h-5.265C6.938 30 2.406 25.018 2.406 18.867V13.66h.001v-.115C2.406 9.382 5.898 6 10.2 6");
}

</style>
