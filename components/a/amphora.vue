<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="ilTiwRb" width="16" height="24" x="8" y="4" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="c0e9-sq4a"/></mask><mask id="iSXb8He" width="16" height="24" x="8" y="4" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="dw919ubbt"/></mask><g class="ft5dv1b6b"><path stroke="url(#i889xoe)" class="oruacq74a"/><g filter="url(#ic6T6ef)"><path stroke="url(#iZB2eUb)" class="a0jw3ccfp"/></g><path stroke="url(#iRpnTAd)" class="oruacq74a"/><path stroke="url(#iMOANZd)" class="xwphuebdr"/><g filter="url(#irldJle)"><path stroke="url(#ibSRDFc)" class="vgz_ghbgh"/></g><path stroke="url(#iEUZKkc)" class="xwphuebdr"/><path fill="url(#iDuCQNb)" class="qhisvab0j"/><path fill="url(#ib7vJid)" class="qhisvab0j"/><path fill="url(#i3sTKhb)" class="qhisvab0j"/><g filter="url(#iCIxx4o)" mask="url(#ilTiwRb)"><path fill="url(#iPaqEyb)" clip-rule="evenodd" class="f2-9_gu5z"/></g><g filter="url(#isKAbEc)" mask="url(#iSXb8He)"><path fill="url(#ivHoD9d)" class="h43ls7b2d"/></g><path stroke="url(#iwyqF4G)" class="o1b_yhbtw"/><path stroke="url(#iXXed0b)" class="o1b_yhbtw"/><path class="tr7nvs7nl"/><path clip-rule="evenodd" class="xr5k7_bed"/><g filter="url(#iK1mdbR)"><path fill="url(#irogSqZ)" class="dowc7acnj"/></g><g filter="url(#ioWJKys)"><path fill="url(#ia8gWce)" class="ey6e3ll4u"/></g><defs><linearGradient id="i889xoe" x1="10.854" x2="10.854" y1="6.173" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="x74nkkhzu"/><stop offset="1" class="chy8p9bbe"/></linearGradient><linearGradient id="iZB2eUb" x1="10.854" x2="10.854" y1="6.173" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="noa2likxw"/><stop offset="1" class="rl719pb7s"/></linearGradient><linearGradient id="iRpnTAd" x1="8.191" x2="10.854" y1="10.012" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="k05n1gbkm"/><stop offset="1" class="p_qts-b_r"/></linearGradient><linearGradient id="iMOANZd" x1="21.146" x2="21.146" y1="6.173" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="caqcubbqs"/><stop offset="1" class="m0im9kbhs"/></linearGradient><linearGradient id="ibSRDFc" x1="21.146" x2="21.146" y1="6.173" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="y1alxbara"/><stop offset="1" class="jh1q9qb1c"/></linearGradient><linearGradient id="iEUZKkc" x1="25.787" x2="21.146" y1="8.405" y2="12.655" gradientUnits="userSpaceOnUse"><stop class="k05n1gbkm"/><stop offset="1" class="a2gzbfbcc"/></linearGradient><linearGradient id="iDuCQNb" x1="8.5" x2="23.5" y1="17" y2="17" gradientUnits="userSpaceOnUse"><stop class="nyhp9bb4r"/><stop offset=".281" class="zv8wb3bru"/><stop offset=".536" class="v4r148b5l"/><stop offset=".766" class="x85yawbqd"/><stop offset="1" class="c7cof4upm"/></linearGradient><linearGradient id="ib7vJid" x1="16" x2="16" y1="3.925" y2="27.567" gradientUnits="userSpaceOnUse"><stop offset=".464" class="uvqe_cc7x"/><stop offset="1" class="xv82s2iuq"/></linearGradient><linearGradient id="i3sTKhb" x1="16" x2="16" y1="3.925" y2="6" gradientUnits="userSpaceOnUse"><stop class="a2gzbfbcc"/><stop offset="1" class="k05n1gbkm"/></linearGradient><linearGradient id="iPaqEyb" x1="16" x2="16" y1="3.875" y2="27.625" gradientUnits="userSpaceOnUse"><stop class="rw5c_lizo"/><stop offset="1" class="a2gzbfbcc"/></linearGradient><linearGradient id="ivHoD9d" x1="18.21" x2="14.523" y1="8.877" y2="8.877" gradientUnits="userSpaceOnUse"><stop class="de3t7l4jk"/><stop offset="1" class="c47kfgbng"/></linearGradient><linearGradient id="iwyqF4G" x1="16" x2="16" y1="2" y2="4" gradientUnits="userSpaceOnUse"><stop class="dhsdg1hse"/><stop offset=".375" class="ex3554buj"/><stop offset=".656" class="k4xji4bvi"/><stop offset="1" class="bj6dv10ec"/></linearGradient><linearGradient id="iXXed0b" x1="15.5" x2="15.5" y1="3" y2="4" gradientUnits="userSpaceOnUse"><stop class="thffkhbdq"/><stop offset="1" class="doc68rb8d"/></linearGradient><linearGradient id="irogSqZ" x1="19.756" x2="13.774" y1="2.951" y2="2.948" gradientUnits="userSpaceOnUse"><stop class="rk_28gdkl"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ia8gWce" x1="12.257" x2="16.571" y1="3.476" y2="3.474" gradientUnits="userSpaceOnUse"><stop class="m8-zqdhge"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="ic6T6ef" width="7.708" height="7.482" x="7" y="5.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33363" stdDeviation=".125"/></filter><filter id="irldJle" width="7.708" height="7.482" x="17.292" y="5.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33363" stdDeviation=".125"/></filter><filter id="iCIxx4o" width="17.25" height="25.75" x="7.375" y="2.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33363" stdDeviation=".5"/></filter><filter id="isKAbEc" width="6.715" height="4.098" x="13.273" y="6.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33363" stdDeviation=".625"/></filter><filter id="iK1mdbR" width="7.684" height="2.158" x="12.723" y="1.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33363" stdDeviation=".35"/></filter><filter id="ioWJKys" width="5.53" height="1.626" x="11.793" y="2.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33363" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:amphora" /></template>
<style>
.a0jw3ccfp {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m10.18 12.655l-1.335-1.273C6.258 8.836 8.2 7.125 8.2 7.125s1.982-2.4 4.736.418l1.273 1.293");
}

.a2gzbfbcc {
  stop-opacity: 0.2;
}

.bj6dv10ec {
  stop-color: var(--svg-color--7d4030, #7D4030);
}

.c0e9-sq4a {
  fill: var(--svg-color--d3883e, #D3883E);
  d: path("M13 4s.1.755.455 2.456c.354 1.7.557 2.705-.455 3.33l-.106.064c-1.492.918-4.403 2.708-4.394 6.733c0 1.8.317 2.577 2.021 5.45A89 89 0 0 1 13.5 27.5h5s1.274-2.593 2.979-5.467c1.704-2.873 2.021-3.65 2.021-5.45c.01-4.025-2.902-5.815-4.394-6.733L19 9.785c-1.012-.624-.809-1.629-.455-3.33C18.9 4.756 19 4 19 4z");
}

.c47kfgbng {
  stop-color: var(--svg-color--cda16d, #CDA16D);
  stop-opacity: 0.2;
}

.c7cof4upm {
  stop-color: var(--svg-color--d7a36a, #D7A36A);
}

.caqcubbqs {
  stop-color: var(--svg-color--7d4f3b, #7D4F3B);
}

.chy8p9bbe {
  stop-color: var(--svg-color--744b3a, #744B3A);
}

.de3t7l4jk {
  stop-color: var(--svg-color--efc28d, #EFC28D);
}

.dhsdg1hse {
  stop-color: var(--svg-color--795d4e, #795D4E);
}

.doc68rb8d {
  stop-color: var(--svg-color--8d2d61, #8D2D61);
  stop-opacity: 0.2;
}

.dowc7acnj {
  d: path("m19.585 2.504l-.28-.13l-5.882.382l5.52.301l.642.076l.122-.13v-.247z");
}

.dw919ubbt {
  d: path("M13 4s.1.755.455 2.456c.354 1.7.557 2.705-.455 3.33l-.106.064c-1.492.918-4.403 2.708-4.394 6.733c0 1.8.317 2.577 2.021 5.45A89 89 0 0 1 13.5 27.5h5s1.274-2.593 2.979-5.467c1.704-2.873 2.021-3.65 2.021-5.45c.01-4.025-2.902-5.815-4.394-6.733L19 9.785c-1.012-.624-.809-1.629-.455-3.33C18.9 4.756 19 4 19 4z");
}

.ex3554buj {
  stop-color: var(--svg-color--81533c, #81533C);
}

.ey6e3ll4u {
  d: path("M12.381 3.107L12.582 3l4.241.315l-3.98.249l-.462.062l-.088-.107v-.204z");
}

.f2-9_gu5z {
  fill-rule: evenodd;
  d: path("M12.906 3.918A.13.13 0 0 1 13 3.875h6a.125.125 0 0 1 .124.141v.003l-.001.007l-.004.028l-.017.11q-.022.146-.073.447a56 56 0 0 1-.361 1.87c-.179.857-.313 1.514-.283 2.036c.015.257.07.475.176.662s.267.353.505.5l.11.068c1.493.918 4.458 2.741 4.449 6.836c0 .91-.08 1.57-.38 2.367c-.296.79-.808 1.712-1.659 3.147a89 89 0 0 0-2.916 5.342l-.043.087l-.011.022l-.004.007l-.112-.055v-.125h-.078l.024-.048l.168-.334a89 89 0 0 1 2.757-5.024c.853-1.438 1.352-2.34 1.64-3.107c.286-.76.364-1.388.364-2.279c.009-3.95-2.842-5.708-4.335-6.626l-.106-.065a1.64 1.64 0 0 1-.59-.59a1.74 1.74 0 0 1-.209-.77c-.032-.563.112-1.258.288-2.102c.177-.849.29-1.462.36-1.861q.05-.3.072-.443l-5.71-.001q.022.145.073.444c.069.4.182 1.012.36 1.861c.175.844.32 1.54.287 2.101a1.74 1.74 0 0 1-.208.771c-.13.23-.323.424-.591.59l-.106.065c-1.493.918-4.344 2.675-4.335 6.626c0 .89.078 1.519.364 2.279c.287.766.787 1.67 1.64 3.108a90 90 0 0 1 2.925 5.357l.024.048h4.844l-.02.04l-.01.022l-.004.007l.112.056l.112.055a.13.13 0 0 1-.112.07h-5a.13.13 0 0 1-.112-.07l-.004-.007l-.01-.022l-.044-.087l-.167-.332a89 89 0 0 0-2.749-5.01c-.851-1.435-1.363-2.357-1.66-3.147c-.299-.797-.379-1.457-.379-2.367c-.01-4.095 2.956-5.918 4.449-6.836l.11-.068c.239-.147.4-.312.505-.5c.106-.187.161-.405.176-.662c.03-.522-.104-1.18-.283-2.036a56 56 0 0 1-.36-1.87a24 24 0 0 1-.09-.557l-.005-.028v-.009a.13.13 0 0 1 .029-.1");
}

.ft5dv1b6b {
  fill: none;
}

.h43ls7b2d {
  d: path("M18.738 9.676c-.468-.324-.623-.957-.535-1.598c0 0-2.638.754-3.68.854c0 0 3.47.341 4.215.744");
}

.jh1q9qb1c {
  stop-color: var(--svg-color--965e54, #965E54);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k4xji4bvi {
  stop-color: var(--svg-color--774a3c, #774A3C);
}

.m0im9kbhs {
  stop-color: var(--svg-color--835047, #835047);
}

.m8-zqdhge {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.08;
}

.noa2likxw {
  stop-color: var(--svg-color--8e5c52, #8E5C52);
}

.nyhp9bb4r {
  stop-color: var(--svg-color--8e643e, #8E643E);
}

.o1b_yhbtw {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 3h6.5");
}

.oruacq74a {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m10.18 12.655l-1.335-1.273C6.258 8.836 8.2 7.125 8.2 7.125s1.982-2.4 4.736.418l1.273 1.293");
}

.p_qts-b_r {
  stop-opacity: 0.3;
}

.qhisvab0j {
  d: path("M13.455 6.455C13.1 4.755 13 4 13 4l.043-.075h5.86L19 4s-.1.755-.455 2.455c-.354 1.701-.557 2.706.455 3.33l.106.065c1.224.753 3.404 2.094 4.142 4.775l-.021.047l.14.672l.042.03q.057.362.08.75l-.036.04v.664l.044.047c-.015.65-.085 1.174-.27 1.75l-.051.031l-.27.668l.028.05c-.306.682-.768 1.5-1.456 2.66C19.775 24.906 18.5 27.5 18.5 27.5l-.073.067H13.56l-.06-.067s-1.274-2.593-2.978-5.467c-.688-1.159-1.15-1.977-1.456-2.658l.024-.05l-.274-.665l-.042-.035c-.186-.576-.256-1.1-.27-1.75l.039-.035v-.664l-.031-.051q.02-.39.079-.75l.038-.027l.145-.688l-.022-.035c.738-2.681 2.918-4.022 4.142-4.775L13 9.785c1.012-.624.809-1.629.455-3.33");
}

.rk_28gdkl {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.35;
}

.rl719pb7s {
  stop-color: var(--svg-color--915b45, #915B45);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.thffkhbdq {
  stop-color: var(--svg-color--7b4545, #7B4545);
  stop-opacity: 0;
}

.tr7nvs7nl {
  fill: var(--svg-color--8c5543, #8C5543);
  d: path("M18.5 27.5h-5l-1 1.5c-.5.75 0 1 .5 1h6c.5 0 1-.25.5-1z");
}

.uvqe_cc7x {
  stop-color: var(--svg-color--c946a4, #C946A4);
  stop-opacity: 0;
}

.v4r148b5l {
  stop-color: var(--svg-color--c8874c, #C8874C);
}

.vgz_ghbgh {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.82 12.655l1.335-1.273c2.587-2.546.646-4.257.646-4.257s-1.982-2.4-4.736.418l-1.273 1.293");
}

.x74nkkhzu {
  stop-color: var(--svg-color--79493a, #79493A);
}

.x85yawbqd {
  stop-color: var(--svg-color--e4a669, #E4A669);
}

.xr5k7_bed {
  fill: var(--svg-color--6d3437, #6D3437);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  fill-rule: evenodd;
  d: path("M23.248 14.625H21a.375.375 0 0 0-.375.375v1.5c0 .207.168.375.375.375h2.497q.003-.142.003-.292q0-.234-.012-.458h-2.113v-.75h2.034a7 7 0 0 0-.161-.75m-.021 4h-3.352V15a.375.375 0 0 0-.375-.375H14a.375.375 0 0 0-.375.375v1.5c0 .207.168.375.375.375h3.125v1.75h-4.25V15a.375.375 0 0 0-.375-.375H8.752q-.1.36-.161.75h3.534V19c0 .207.168.375.375.375h5a.375.375 0 0 0 .375-.375v-2.5a.375.375 0 0 0-.375-.375h-3.125v-.75h4.75V19c0 .207.168.375.375.375h3.434a7 7 0 0 0 .293-.75m-14.161.75H10.5a.375.375 0 0 0 .375-.375v-2.5a.375.375 0 0 0-.375-.375H8.512q-.012.224-.012.458q0 .15.003.292h1.622v1.75H8.774c.076.237.172.483.292.75");
}

.xv82s2iuq {
  stop-color: var(--svg-color--c946a4, #C946A4);
  stop-opacity: 0.4;
}

.xwphuebdr {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m21.82 12.655l1.335-1.273c2.587-2.546.646-4.257.646-4.257s-1.982-2.4-4.736.418l-1.273 1.293");
}

.y1alxbara {
  stop-color: var(--svg-color--8d5c41, #8D5C41);
}

.zv8wb3bru {
  stop-color: var(--svg-color--ac723c, #AC723C);
}

</style>
