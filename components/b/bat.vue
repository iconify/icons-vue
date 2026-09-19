<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivPWACe)" class="nqepuibnm"/><path fill="url(#isWTmvc)" class="nqepuibnm"/><path fill="url(#i0AC2fb)" class="nqepuibnm"/><path fill="url(#ibCc8Zd)" class="nqepuibnm"/><path fill="url(#isGNp8N)" class="nqepuibnm"/><path fill="url(#izJ4bEe)" class="nqepuibnm"/><path fill="url(#iPxEOAc)" class="nqepuibnm"/><path class="w4lx21b0g"/><path fill="url(#ifgCRKc)" class="rwd8gbc2j"/><path fill="url(#ihJpm8h)" class="rwd8gbc2j"/><path fill="url(#iRDXRHd)" class="rwd8gbc2j"/><path fill="url(#igCb74d)" class="rwd8gbc2j"/><path fill="url(#i1an7od)" class="rwd8gbc2j"/><path class="uwa3ttbhj"/><path fill="url(#iKu60dd)" class="o5-h55xck"/><path fill="url(#if4gXgd)" class="o5-h55xck"/><path fill="url(#iLrcd2c)" class="o5-h55xck"/><path fill="url(#iFoXeNQ)" class="o5-h55xck"/><path fill="url(#iheWjPb)" class="o5-h55xck"/><g filter="url(#iip49Ub)"><path class="ty479ebfd"/></g><path fill="url(#im53Q3b)" class="n0qrwc-6r"/><path fill="url(#iw6olId)" class="n0qrwc-6r"/><path fill="url(#il4dALd)" class="n0qrwc-6r"/><g filter="url(#iyJJEsc)"><ellipse fill="url(#i3C0B3l)" transform="rotate(-8.83 20.821 18.424)" class="ahekfsb3f"/></g><g filter="url(#iZDW4dc)"><path class="m_of-4bmj"/></g><path class="ygzrahbsn"/><path fill="url(#i8gCF3G)" class="p830di_ey"/><path fill="url(#iwXbvlb)" class="p830di_ey"/><path fill="url(#ihqyrod)" class="p830di_ey"/><path fill="url(#iTOUQMe)" class="y18tqbbep"/><path fill="url(#iEgDogc)" class="y18tqbbep"/><path fill="url(#ijc9Gcc)" class="y18tqbbep"/><path fill="url(#inTnzRd)" class="q3sue90os"/><path fill="url(#iGot8Ub)" class="q3sue90os"/><path fill="url(#ivDTjAe)" class="q3sue90os"/><path fill="url(#iE1A9ad)" class="tvqkqkdyf"/><path fill="url(#iQFpxMd)" class="tvqkqkdyf"/><path fill="url(#iodH1Pc)" class="tvqkqkdyf"/><path fill="url(#i0AfLwd)" class="tvqkqkdyf"/><path fill="url(#izb8ABi)" class="heffrlbfp"/><path fill="url(#iVl949b)" class="heffrlbfp"/><g filter="url(#iLgo5Ob)"><path fill="url(#iJZKBje)" class="lhu0wu5md"/></g><g filter="url(#iNAwFXc)"><path fill="url(#igFJVxc)" class="sg93lmh4f"/></g><g filter="url(#iXGq7db)"><path fill="url(#ivlXEQd)" class="ka9fyabff"/></g><g filter="url(#i6v4p5b)"><path fill="url(#iJw5IJb)" class="yipebkb3o"/></g><g filter="url(#i5Q3hBK)"><path fill="url(#iU0xjyb)" class="lb95hyb0v"/></g><g filter="url(#iWKYXyb)"><path fill="url(#iiKZZVc)" class="u4xqr4yrg"/></g><g filter="url(#iG3ek5b)"><path stroke="url(#i7ro4Zd)" class="u2osnhisw"/></g><defs><linearGradient id="ivPWACe" x1="19.562" x2="12.382" y1="21.517" y2="29.017" gradientUnits="userSpaceOnUse"><stop class="af8ojzbpm"/><stop offset="1" class="qus9-0y3d"/></linearGradient><linearGradient id="isWTmvc" x1="19.812" x2="16.125" y1="23.392" y2="27.705" gradientUnits="userSpaceOnUse"><stop offset=".093" class="w0a_pd53w"/><stop offset="1" class="ik0gfybbi"/></linearGradient><linearGradient id="izJ4bEe" x1="5.875" x2="7.469" y1="21.205" y2="22.892" gradientUnits="userSpaceOnUse"><stop offset=".225" class="abbk3qyqs"/><stop offset="1" class="aneo64bsc"/></linearGradient><linearGradient id="iRDXRHd" x1="19.656" x2="20.672" y1="8.486" y2="9.408" gradientUnits="userSpaceOnUse"><stop class="cgo_wh8iu"/><stop offset="1" class="bjh1p8n5p"/></linearGradient><linearGradient id="igCb74d" x1="22.375" x2="26.625" y1="23.642" y2="16.205" gradientUnits="userSpaceOnUse"><stop class="cgo_wh8iu"/><stop offset="1" class="bjh1p8n5p"/></linearGradient><linearGradient id="iKu60dd" x1="18.703" x2="19.391" y1="23.97" y2="23.267" gradientUnits="userSpaceOnUse"><stop offset=".305" class="yamyfybfx"/><stop offset="1" class="g9cu0obdv"/></linearGradient><linearGradient id="if4gXgd" x1="24.328" x2="25.406" y1="27.673" y2="25.673" gradientUnits="userSpaceOnUse"><stop class="c_ajneb3i"/><stop offset="1" class="sulbs0bax"/></linearGradient><linearGradient id="iLrcd2c" x1="18.188" x2="22.017" y1="24.486" y2="20.955" gradientUnits="userSpaceOnUse"><stop class="yamyfybfx"/><stop offset="1" class="g9cu0obdv"/></linearGradient><linearGradient id="im53Q3b" x1="21.062" x2="15" y1="16.642" y2="24.455" gradientUnits="userSpaceOnUse"><stop offset=".158" class="ctkil917h"/><stop offset="1" class="n5w3clbbd"/></linearGradient><linearGradient id="i8gCF3G" x1="18.906" x2="19.906" y1="20.548" y2="19.611" gradientUnits="userSpaceOnUse"><stop class="oqdw0bbee"/><stop offset="1" class="ebr5g-b8h"/></linearGradient><linearGradient id="ijc9Gcc" x1="17.32" x2="16.977" y1="19.087" y2="18.869" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ivDTjAe" x1="19.311" x2="18.967" y1="17.126" y2="16.907" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iE1A9ad" x1="15.283" x2="11.789" y1="20.33" y2="17.128" gradientUnits="userSpaceOnUse"><stop class="oxjxaknob"/><stop offset="1" class="o4y4q2e2y"/></linearGradient><linearGradient id="iQFpxMd" x1="12.858" x2="13.233" y1="18.478" y2="18.097" gradientUnits="userSpaceOnUse"><stop class="g92aahbxm"/><stop offset=".663" class="naycknqqw"/></linearGradient><linearGradient id="iodH1Pc" x1="13.754" x2="13.702" y1="16.814" y2="17.322" gradientUnits="userSpaceOnUse"><stop class="a-8ecpm3d"/><stop offset="1" class="bbnkcrj5q"/></linearGradient><linearGradient id="i0AfLwd" x1="15.004" x2="15.428" y1="19.037" y2="18.972" gradientUnits="userSpaceOnUse"><stop class="kf9i38bhd"/><stop offset="1" class="nbs0_16iw"/></linearGradient><linearGradient id="izb8ABi" x1="16.836" x2="18.247" y1="13.752" y2="13.427" gradientUnits="userSpaceOnUse"><stop class="g92aahbxm"/><stop offset=".577" class="naycknqqw"/></linearGradient><linearGradient id="iVl949b" x1="16.75" x2="16.938" y1="13.72" y2="16.187" gradientUnits="userSpaceOnUse"><stop class="m6znli44l"/><stop offset=".695" class="t3b5v6f1p"/></linearGradient><linearGradient id="iJZKBje" x1="16.891" x2="18.313" y1="12.377" y2="16.111" gradientUnits="userSpaceOnUse"><stop class="sniyh5kig"/><stop offset="1" class="bn1006bii"/></linearGradient><linearGradient id="igFJVxc" x1="17.797" x2="19.906" y1="12.533" y2="16.252" gradientUnits="userSpaceOnUse"><stop class="mcr2ltb0p"/><stop offset="1" class="eu8x4hb4l"/></linearGradient><linearGradient id="ivlXEQd" x1="15.453" x2="17.297" y1="14.96" y2="17.023" gradientUnits="userSpaceOnUse"><stop class="o0gr2qbhp"/><stop offset="1" class="v1ep16bkm"/></linearGradient><linearGradient id="iJw5IJb" x1="26.789" x2="25.008" y1="2.728" y2="4.509" gradientUnits="userSpaceOnUse"><stop class="xgd183b-u"/><stop offset="1" class="kbxnsobwp"/></linearGradient><linearGradient id="iU0xjyb" x1="31.5" x2="21.863" y1="9.267" y2="7.756" gradientUnits="userSpaceOnUse"><stop class="xgd183b-u"/><stop offset="1" class="kbxnsobwp"/></linearGradient><linearGradient id="iiKZZVc" x1="30.188" x2="25.719" y1="16.049" y2="13.917" gradientUnits="userSpaceOnUse"><stop class="xgd183b-u"/><stop offset="1" class="kbxnsobwp"/></linearGradient><linearGradient id="i7ro4Zd" x1="10.188" x2="13.25" y1="19.924" y2="22.267" gradientUnits="userSpaceOnUse"><stop class="djpn3ks8x"/><stop offset="1" class="e9xd3fbhw"/></linearGradient><radialGradient id="i0AC2fb" cx="0" cy="0" r="1" gradientTransform="rotate(151.174 6.931 16.132)scale(5.3148 3.74614)" gradientUnits="userSpaceOnUse"><stop class="f7g69wbyn"/><stop offset="1" class="fey-3__9s"/></radialGradient><radialGradient id="ibCc8Zd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -3.6875 2.9141 1.8275 5.219 29.08)" gradientUnits="userSpaceOnUse"><stop class="cqbmeccph"/><stop offset="1" class="jvrkj7hyc"/></radialGradient><radialGradient id="isGNp8N" cx="0" cy="0" r="1" gradientTransform="rotate(-101.899 18.519 10.173)scale(4.88624 4.81884)" gradientUnits="userSpaceOnUse"><stop class="rqmsvsbgo"/><stop offset="1" class="wpo2q2bdf"/></radialGradient><radialGradient id="iPxEOAc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.42192 1.32058 -1.59497 -5.3407 22.769 24.86)" gradientUnits="userSpaceOnUse"><stop class="k4am52bxc"/><stop offset="1" class="ta6cssfuo"/></radialGradient><radialGradient id="ifgCRKc" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 -.40625 .87077 4.55478 20.469 14.236)" gradientUnits="userSpaceOnUse"><stop class="cgo_wh8iu"/><stop offset="1" class="bjh1p8n5p"/></radialGradient><radialGradient id="ihJpm8h" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65626 .78123 -.52875 -2.4746 30.844 9.83)" gradientUnits="userSpaceOnUse"><stop class="cgo_wh8iu"/><stop offset="1" class="bjh1p8n5p"/></radialGradient><radialGradient id="i1an7od" cx="0" cy="0" r="1" gradientTransform="rotate(173.517 14.68 9.124)scale(3.45962 1.17627)" gradientUnits="userSpaceOnUse"><stop class="sujkbt5ix"/><stop offset="1" class="ijx_r71xe"/></radialGradient><radialGradient id="iFoXeNQ" cx="0" cy="0" r="1" gradientTransform="matrix(.32812 2.03125 -2.2299 .3602 19.453 21.126)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="yamyfybfx"/><stop offset="1" class="g9cu0obdv"/></radialGradient><radialGradient id="iheWjPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -1.53125 9.19377 7.599 21.688 26.768)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="rfgh9r7in"/><stop offset=".399" class="nv_93ebuv"/></radialGradient><radialGradient id="iw6olId" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 1.4375 -3.32334 -5.7797 22.812 16.236)" gradientUnits="userSpaceOnUse"><stop class="gkd603cfd"/><stop offset="1" class="r7jhs-bxo"/></radialGradient><radialGradient id="il4dALd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5937 -5.03125 5.03124 -.5937 19.032 24.486)" gradientUnits="userSpaceOnUse"><stop class="yi1m734ub"/><stop offset="1" class="y39xlt5dz"/></radialGradient><radialGradient id="i3C0B3l" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -3.13224 21.766 18.424)" gradientUnits="userSpaceOnUse"><stop class="n4791ymrh"/><stop offset="1" class="jvpn6mb2a"/></radialGradient><radialGradient id="iwXbvlb" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 1.75 -2.61922 .8185 19.875 19.08)" gradientUnits="userSpaceOnUse"><stop offset=".49" class="p4kfrjfto"/><stop offset=".959" class="rz_hbgbbn"/></radialGradient><radialGradient id="ihqyrod" cx="0" cy="0" r="1" gradientTransform="rotate(155.844 8.392 11.797)scale(.85909 .38873)" gradientUnits="userSpaceOnUse"><stop class="mebto9quo"/><stop offset="1" class="g-3jcm1lb"/></radialGradient><radialGradient id="iTOUQMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 17.566 19.319)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iEgDogc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13608 .37246 -.31397 -.11471 17.5 19.299)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="inTnzRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 19.557 17.358)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iGot8Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-.13608 .37246 -.31397 -.11471 19.49 17.337)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><filter id="iip49Ub" width="10.464" height="9.977" x="18.031" y="16.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation="1"/></filter><filter id="iyJJEsc" width="4.528" height="5.934" x="18.557" y="15.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".5"/></filter><filter id="iZDW4dc" width="3.179" height="3.137" x="17.985" y="18.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".25"/></filter><filter id="iLgo5Ob" width="3.375" height="4.984" x="16.625" y="11.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".25"/></filter><filter id="iNAwFXc" width="4.313" height="5.148" x="16.688" y="11.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".25"/></filter><filter id="iXGq7db" width="5.747" height="5.622" x="14.854" y="14.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".25"/></filter><filter id="i6v4p5b" width="2.213" height="5.21" x="25.238" y="1.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".2"/></filter><filter id="i5Q3hBK" width="4.764" height="6.31" x="25.081" y="2.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".2"/></filter><filter id="iWKYXyb" width="3.054" height="6.167" x="26.916" y="9.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".2"/></filter><filter id="iG3ek5b" width="5.906" height="4" x="9.188" y="18.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4068" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bat" /></template>
<style>
.a-8ecpm3d {
  stop-color: var(--svg-color--d3a28c, #D3A28C);
}

.abbk3qyqs {
  stop-color: var(--svg-color--c89c8d, #C89C8D);
}

.af8ojzbpm {
  stop-color: var(--svg-color--9e5d5f, #9E5D5F);
}

.ahekfsb3f {
  cx: 20.821px;
  cy: 18.424px;
  rx: 1.241px;
  ry: 1.981px;
}

.aneo64bsc {
  stop-color: var(--svg-color--c89c8d, #C89C8D);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bbnkcrj5q {
  stop-color: var(--svg-color--d3a28c, #D3A28C);
  stop-opacity: 0;
}

.bjh1p8n5p {
  stop-color: var(--svg-color--a35946, #A35946);
  stop-opacity: 0;
}

.bn1006bii {
  stop-color: var(--svg-color--b25c33, #B25C33);
  stop-opacity: 0;
}

.c_ajneb3i {
  stop-color: var(--svg-color--995885, #995885);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cgo_wh8iu {
  stop-color: var(--svg-color--a35946, #A35946);
}

.cqbmeccph {
  stop-color: var(--svg-color--9f5668, #9F5668);
}

.ctkil917h {
  stop-color: var(--svg-color--bf7951, #BF7951);
}

.djpn3ks8x {
  stop-color: var(--svg-color--ad7565, #AD7565);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.e9xd3fbhw {
  stop-color: var(--svg-color--ad7565, #AD7565);
  stop-opacity: 0;
}

.ebr5g-b8h {
  stop-color: var(--svg-color--eeaea8, #EEAEA8);
  stop-opacity: 0;
}

.eu8x4hb4l {
  stop-color: var(--svg-color--c98d6f, #C98D6F);
  stop-opacity: 0;
}

.f7g69wbyn {
  stop-color: var(--svg-color--954b6b, #954B6B);
}

.fey-3__9s {
  stop-color: var(--svg-color--954b6b, #954B6B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-3jcm1lb {
  stop-color: var(--svg-color--ffdacc, #FFDACC);
  stop-opacity: 0;
}

.g92aahbxm {
  stop-color: var(--svg-color--a3533a, #A3533A);
}

.g9cu0obdv {
  stop-color: var(--svg-color--844248, #844248);
  stop-opacity: 0;
}

.gkd603cfd {
  stop-color: var(--svg-color--df9867, #DF9867);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.heffrlbfp {
  d: path("m17.263 11.924l2.1 2.1l-2.117 2.115l-.409-4.013a.25.25 0 0 1 .425-.202");
}

.ijx_r71xe {
  stop-color: var(--svg-color--a66871, #A66871);
  stop-opacity: 0;
}

.ik0gfybbi {
  stop-color: var(--svg-color--8d434e, #8D434E);
  stop-opacity: 0;
}

.jvpn6mb2a {
  stop-color: var(--svg-color--eeab7d, #EEAB7D);
  stop-opacity: 0;
}

.jvrkj7hyc {
  stop-color: var(--svg-color--9f5668, #9F5668);
  stop-opacity: 0;
}

.k4am52bxc {
  stop-color: var(--svg-color--8e4457, #8E4457);
}

.ka9fyabff {
  d: path("m15.65 17.063l1.546-1.536a1 1 0 0 1 .84-.28l2.066.284l-4.696 4.328l-.051-2.062a1 1 0 0 1 .295-.734");
}

.kbxnsobwp {
  stop-color: var(--svg-color--c69483, #C69483);
  stop-opacity: 0;
}

.kf9i38bhd {
  stop-color: var(--svg-color--b96d56, #B96D56);
  stop-opacity: 0;
}

.lb95hyb0v {
  d: path("M27.062 7.072c-1.13-1.271-.817-3.216-.5-3.977c-.343.302-1.271 1.188-1.046 2.813c.266 1.925 2.102 2.56 2.609 2.656c.539.102.992.016 1.32-.281c-.578.125-1.633-.367-2.383-1.211");
}

.lhu0wu5md {
  d: path("m17.125 12.127l.656 3.984l1.719-.594z");
}

.m_of-4bmj {
  fill: var(--svg-color--b15b43, #B15B43);
  d: path("M18.816 21.055c-.433-.433-.406-1.507-.123-1.79c.364-.364 1.518-.257 1.844.069c.209.209.236.513-.513 1.262c-.748.748-1.058.609-1.208.46");
}

.m6znli44l {
  stop-color: var(--svg-color--bf7951, #BF7951);
  stop-opacity: 0;
}

.mcr2ltb0p {
  stop-color: var(--svg-color--c98d6f, #C98D6F);
}

.mebto9quo {
  stop-color: var(--svg-color--ffdacc, #FFDACC);
}

.n0qrwc-6r {
  d: path("M17.262 11.924a.25.25 0 0 0-.425.202l.31 3.035a.5.5 0 0 1-.144.404L15.5 17.067a.5.5 0 0 1-.404.144l-3.035-.31a.25.25 0 0 0-.202.425l4.172 4.173a3.6 3.6 0 0 0 5.091 0l.312-.312a3.6 3.6 0 0 0 0-5.09z");
}

.n4791ymrh {
  stop-color: var(--svg-color--eeab7d, #EEAB7D);
}

.n5w3clbbd {
  stop-color: var(--svg-color--b46558, #B46558);
}

.naycknqqw {
  stop-color: var(--svg-color--a3533a, #A3533A);
  stop-opacity: 0;
}

.nbs0_16iw {
  stop-color: var(--svg-color--b96d56, #B96D56);
}

.nqepuibnm {
  d: path("M9.644 19.335L2.26 26.629q-.02.021-.052.047c-.105.091-.274.237-.189.393c.127.232.372.165.534.069c1.455-.868 4.875-.914 5.533 2.417c.033.143.276.276.496.055c1.05-1.05 4.475-2.972 7.071.265c.063.114.232.245.41-.143l.05-.121c.318-.787 1.59-3.93 6.656-2.83l-6.32-6.32c-.608.675-2.603 1.397-5.723-1.104c-.613-.491-1.082-.022-1.082-.022");
}

.nv_93ebuv {
  stop-color: var(--svg-color--b181ab, #B181AB);
  stop-opacity: 0;
}

.o0gr2qbhp {
  stop-color: var(--svg-color--dfb4a1, #DFB4A1);
}

.o4y4q2e2y {
  stop-color: var(--svg-color--ab5e46, #AB5E46);
  stop-opacity: 0;
}

.o5-h55xck {
  d: path("m17.998 18.106l.008-.008l.008-.009a3.164 3.164 0 0 1 4.475 0l2.856 2.856c2.149 2.15 1.926 3.93.69 5.166l-.008.008l-.008.008c-1.236 1.236-3.016 1.459-5.165-.69l-2.856-2.856a3.164 3.164 0 0 1 0-4.475");
}

.oqdw0bbee {
  stop-color: var(--svg-color--eeaea8, #EEAEA8);
}

.oxjxaknob {
  stop-color: var(--svg-color--ab5e46, #AB5E46);
}

.p4kfrjfto {
  stop-color: var(--svg-color--e398ac, #E398AC);
  stop-opacity: 0;
}

.p830di_ey {
  d: path("M18.968 20.815c-.448-.447-.42-1.558-.127-1.85c.375-.376 1.569-.265 1.906.072c.215.215.243.53-.53 1.303c-.774.774-1.095.63-1.25.475");
}

.q3sue90os {
  d: path("M19.41 18.019a.5.5 0 1 0-.001-1a.5.5 0 0 0 0 1");
}

.qus9-0y3d {
  stop-color: var(--svg-color--a5655e, #A5655E);
}

.r7jhs-bxo {
  stop-color: var(--svg-color--df9867, #DF9867);
  stop-opacity: 0;
}

.rfgh9r7in {
  stop-color: var(--svg-color--b181ab, #B181AB);
}

.rqmsvsbgo {
  stop-color: var(--svg-color--a44d62, #A44D62);
}

.rwd8gbc2j {
  d: path("m19.347 9.656l7.294-7.384q.021-.02.047-.052c.09-.105.237-.274.393-.189c.232.127.165.372.069.533c-.869 1.456-.915 4.876 2.416 5.534c.144.032.276.276.056.496c-1.05 1.05-2.972 4.475.265 7.071c.114.063.245.232-.144.409l-.12.05c-.788.319-3.942 1.812-2.842 6.878l-6.307-6.541c.674-.608 1.396-2.603-1.105-5.723c-.492-.613-.023-1.082-.023-1.082");
}

.rz_hbgbbn {
  stop-color: var(--svg-color--e398ac, #E398AC);
}

.sg93lmh4f {
  d: path("m17.188 12.103l2.062 4.149l1.25-.485z");
}

.sniyh5kig {
  stop-color: var(--svg-color--b35c33, #B35C33);
}

.sujkbt5ix {
  stop-color: var(--svg-color--a66871, #A66871);
}

.sulbs0bax {
  stop-color: var(--svg-color--995885, #995885);
  stop-opacity: 0;
}

.t3b5v6f1p {
  stop-color: var(--svg-color--be7652, #BE7652);
}

.ta6cssfuo {
  stop-color: var(--svg-color--8e4457, #8E4457);
  stop-opacity: 0;
}

.tvqkqkdyf {
  d: path("m11.878 17.327l3.825 3.846l-.42-3.945l-3.203-.327c-.233-.024-.367.26-.202.426");
}

.ty479ebfd {
  fill: var(--svg-color--c59687, #C59687);
  d: path("M25.51 24.188L20.03 20L22 18.337l4.343 4.96a.613.613 0 0 1-.833.89");
}

.u2osnhisw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.188 19.924c.541.52 2.08 1.65 3.906 2");
}

.u4xqr4yrg {
  d: path("M28.07 10.361c-.867 3.125.76 4.883 1.5 5.367h-1.5c-.937-1.312-1.07-3.195 0-5.367");
}

.uwa3ttbhj {
  fill: var(--svg-color--a56b64, #A56B64);
  d: path("m17.998 18.106l.008-.008l.008-.009a3.164 3.164 0 0 1 4.475 0l2.856 2.856c2.149 2.15 1.926 3.93.69 5.166l-.008.008l-.008.008c-1.236 1.236-3.016 1.459-5.165-.69l-2.856-2.856a3.164 3.164 0 0 1 0-4.475");
}

.v1ep16bkm {
  stop-color: var(--svg-color--dfb4a1, #DFB4A1);
  stop-opacity: 0;
}

.w0a_pd53w {
  stop-color: var(--svg-color--8d434e, #8D434E);
}

.w4lx21b0g {
  fill: var(--svg-color--b07668, #B07668);
  d: path("m19.347 9.656l7.294-7.384q.021-.02.047-.052c.09-.105.237-.274.393-.189c.232.127.165.372.069.533c-.869 1.456-.915 4.876 2.416 5.534c.144.032.276.276.056.496c-1.05 1.05-2.972 4.475.265 7.071c.114.063.245.232-.144.409l-.12.05c-.788.319-3.942 1.812-2.842 6.878l-6.307-6.541c.674-.608 1.396-2.603-1.105-5.723c-.492-.613-.023-1.082-.023-1.082");
}

.wpo2q2bdf {
  stop-color: var(--svg-color--a44d62, #A44D62);
  stop-opacity: 0;
}

.xgd183b-u {
  stop-color: var(--svg-color--c69483, #C69483);
}

.y18tqbbep {
  d: path("M17.419 19.98a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.y39xlt5dz {
  stop-color: var(--svg-color--c15d6e, #C15D6E);
  stop-opacity: 0;
}

.yamyfybfx {
  stop-color: var(--svg-color--844248, #844248);
}

.ygzrahbsn {
  fill: var(--svg-color--ffc3b7, #FFC3B7);
  d: path("M18.968 20.815c-.448-.447-.42-1.558-.127-1.85c.375-.376 1.569-.265 1.906.072c.215.215.243.53-.53 1.303c-.774.774-1.095.63-1.25.475");
}

.yi1m734ub {
  stop-color: var(--svg-color--c15d6e, #C15D6E);
}

.yipebkb3o {
  d: path("m27.02 2.3l.03-.037zc-.523.647-1.37 2.424-.536 4.374l-.57-.97a2 2 0 0 1 .184-2.29z");
}

</style>
