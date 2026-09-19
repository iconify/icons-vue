<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRXPMZd)" class="w--e4jbfb"/><path fill="url(#iDprhpc)" class="w--e4jbfb"/><path fill="url(#iNhz16c)" class="w--e4jbfb"/><g filter="url(#iNYtPpc)"><path fill="url(#isSkyDK)" class="ae47n_b5t"/></g><path fill="url(#i7kd2zL)" class="w--e4jbfb"/><path fill="url(#it5kGIb)" class="w--e4jbfb"/><path fill="url(#iLE714d)" class="dxi393zdc"/><path fill="url(#i6inV5T)" class="dxi393zdc"/><path fill="url(#i4JW5Kv)" class="dxi393zdc"/><path fill="url(#iO2Lz8b)" class="pm-mvhbjw"/><path fill="url(#iKnGGHb)" class="pm-mvhbjw"/><path fill="url(#iXKbaSb)" class="pm-mvhbjw"/><g filter="url(#iVBRLad)"><path fill="url(#iGS14qd)" class="u42mru57x"/></g><path fill="url(#ibGZEGb)" class="u42mru57x"/><path fill="url(#ikGDqwd)" class="u42mru57x"/><rect fill="url(#iZWU01O)" class="hyd2t7bnc"/><rect fill="url(#izCpzUv)" class="na4hirbhl"/><path fill="url(#ioLG49c)" class="auchd-bya"/><path fill="url(#iOPFzRc)" class="rnnuanlvn"/><path fill="url(#ii8Tq7c)" class="sa11f7rkh"/><rect fill="url(#iua8pny)" class="fmcs-p8mt"/><rect class="lw175achg"/><rect fill="url(#i2wo2EM)" class="re-z6sbgm"/><path fill="url(#ijpcnPb)" class="phzxyv1gy"/><rect fill="url(#iWXhosc)" class="fah9lubvo"/><path fill="url(#iBpHIFc)" class="qoi8rbcjc"/><rect fill="url(#iHtdMqb)" class="zoy0kdz2l"/><rect fill="url(#i0BhzLb)" class="hw0l6_b3m"/><path fill="url(#iVcp6uN)" class="gtpj9ub3u"/><path fill="url(#iaRxKKK)" class="iks0hdctb"/><defs><linearGradient id="iRXPMZd" x1="3.003" x2="6.087" y1="16.004" y2="16.004" gradientUnits="userSpaceOnUse"><stop class="rl06ome0c"/><stop offset="1" class="hhs3ugbbz"/></linearGradient><linearGradient id="isSkyDK" x1="5.543" x2="5.543" y1="3.152" y2="29.163" gradientUnits="userSpaceOnUse"><stop class="iuj3aib_p"/><stop offset="1" class="t73s1qbfl"/></linearGradient><linearGradient id="iLE714d" x1="1.994" x2="6.975" y1="7.999" y2="7.999" gradientUnits="userSpaceOnUse"><stop class="e0mfnob8i"/><stop offset="1" class="ll2f1tqku"/></linearGradient><linearGradient id="i6inV5T" x1="5.5" x2="5.5" y1="6" y2="6.68" gradientUnits="userSpaceOnUse"><stop class="xrmgngu4x"/><stop offset="1" class="ffpfzx-zl"/></linearGradient><linearGradient id="i4JW5Kv" x1="6.253" x2="6.253" y1="10.517" y2="9.04" gradientUnits="userSpaceOnUse"><stop class="ov3qpsbqo"/><stop offset="1" class="ec_yp5rel"/></linearGradient><linearGradient id="iO2Lz8b" x1="1.994" x2="6.975" y1="20.999" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="e0mfnob8i"/><stop offset="1" class="ll2f1tqku"/></linearGradient><linearGradient id="iKnGGHb" x1="5.5" x2="5.5" y1="19" y2="19.68" gradientUnits="userSpaceOnUse"><stop class="xrmgngu4x"/><stop offset="1" class="ffpfzx-zl"/></linearGradient><linearGradient id="iXKbaSb" x1="6.253" x2="6.253" y1="23.517" y2="22.04" gradientUnits="userSpaceOnUse"><stop class="ov3qpsbqo"/><stop offset="1" class="ec_yp5rel"/></linearGradient><linearGradient id="iGS14qd" x1="11.313" x2="27.563" y1="23.438" y2="5.75" gradientUnits="userSpaceOnUse"><stop class="a48_4s9xc"/><stop offset="1" class="o6vjgw-ml"/></linearGradient><linearGradient id="ibGZEGb" x1="18.5" x2="18.5" y1="25.688" y2="23.125" gradientUnits="userSpaceOnUse"><stop class="ii6uiso8t"/><stop offset="1" class="cb6i7ccig"/></linearGradient><linearGradient id="iZWU01O" x1="21.934" x2="23.973" y1="20.135" y2="20.135" gradientUnits="userSpaceOnUse"><stop class="foihnifbr"/><stop offset="1" class="sg8lu-w3g"/></linearGradient><linearGradient id="izCpzUv" x1="13.027" x2="15.066" y1="20.135" y2="20.135" gradientUnits="userSpaceOnUse"><stop class="foihnifbr"/><stop offset="1" class="sg8lu-w3g"/></linearGradient><linearGradient id="ioLG49c" x1="23.966" x2="24.439" y1="13.476" y2="13.476" gradientUnits="userSpaceOnUse"><stop class="h37282bkq"/><stop offset="1" class="virt3cm1j"/></linearGradient><linearGradient id="iOPFzRc" x1="12.539" x2="12.945" y1="13.476" y2="13.476" gradientUnits="userSpaceOnUse"><stop class="h37282bkq"/><stop offset="1" class="virt3cm1j"/></linearGradient><linearGradient id="ii8Tq7c" x1="13.785" x2="24.878" y1="8.149" y2="17.901" gradientUnits="userSpaceOnUse"><stop class="sjcpnxbbh"/><stop offset="1" class="t8x7ctbcq"/></linearGradient><linearGradient id="iua8pny" x1="24.515" x2="25.43" y1="13.07" y2="13.07" gradientUnits="userSpaceOnUse"><stop class="pwjsze1ek"/><stop offset="1" class="bkwu7aclq"/></linearGradient><linearGradient id="i2wo2EM" x1="11.639" x2="12.554" y1="13.07" y2="13.07" gradientUnits="userSpaceOnUse"><stop class="pwjsze1ek"/><stop offset="1" class="bkwu7aclq"/></linearGradient><linearGradient id="ijpcnPb" x1="14.201" x2="21.342" y1="15.969" y2="19.808" gradientUnits="userSpaceOnUse"><stop class="exrefeqbn"/><stop offset="1" class="esbr2i0hz"/></linearGradient><linearGradient id="iWXhosc" x1="14.047" x2="22.953" y1="12.231" y2="12.231" gradientUnits="userSpaceOnUse"><stop class="ss5wi3bfk"/><stop offset="1" class="b8c6xjbzu"/></linearGradient><linearGradient id="iBpHIFc" x1="14.047" x2="22.953" y1="10.361" y2="10.361" gradientUnits="userSpaceOnUse"><stop class="yafdjqp3g"/><stop offset="1" class="ru05sab7f"/></linearGradient><linearGradient id="iHtdMqb" x1="15.545" x2="21.486" y1="16.801" y2="16.801" gradientUnits="userSpaceOnUse"><stop class="co-dp-boy"/><stop offset="1" class="a8ydnd5vf"/></linearGradient><linearGradient id="i0BhzLb" x1="16.523" x2="20.477" y1="17.8" y2="17.8" gradientUnits="userSpaceOnUse"><stop class="co-dp-boy"/><stop offset="1" class="a8ydnd5vf"/></linearGradient><linearGradient id="iVcp6uN" x1="13.027" x2="14.363" y1="17.865" y2="17.865" gradientUnits="userSpaceOnUse"><stop class="kd4y0t9lz"/><stop offset="1" class="wi7combjx"/></linearGradient><linearGradient id="iaRxKKK" x1="22.464" x2="24.293" y1="17.54" y2="17.54" gradientUnits="userSpaceOnUse"><stop class="kd4y0t9lz"/><stop offset="1" class="wi7combjx"/></linearGradient><radialGradient id="iDprhpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24562 4.88853 -3.45339 -.87994 7.772 2)" gradientUnits="userSpaceOnUse"><stop class="qn605_dhr"/><stop offset="1" class="fmfjh9bjk"/></radialGradient><radialGradient id="iNhz16c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.61609 -9.2322 5.55274 -2.77636 10.117 32.607)" gradientUnits="userSpaceOnUse"><stop class="oe7imj52j"/><stop offset="1" class="xx7rj0btp"/></radialGradient><radialGradient id="i7kd2zL" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.93545 -3.83941 0 5 9.062)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="gaz5-ikjy"/><stop offset="1" class="x2_4x9b_o"/></radialGradient><radialGradient id="it5kGIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.69494 -5.34602 0 5 21.753)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="gaz5-ikjy"/><stop offset="1" class="x2_4x9b_o"/></radialGradient><radialGradient id="ikGDqwd" cx="0" cy="0" r="1" gradientTransform="rotate(130.192 13.36 8.9)scale(2.37274 1.97845)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="d04-yrbzt"/><stop offset="1" class="ig6kwmbek"/></radialGradient><filter id="iNYtPpc" width="4.087" height="29.011" x="3.5" y="1.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11612" stdDeviation=".75"/></filter><filter id="iVBRLad" width="23.5" height="23.5" x="6.75" y="2.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25" dy="1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.65098 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.32549 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11612" result="effect2_innerShadow_18_11612"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bus-stop" /></template>
<style>
.a48_4s9xc {
  stop-color: var(--svg-color--3c7bd2, #3C7BD2);
}

.a8ydnd5vf {
  stop-color: var(--svg-color--68606d, #68606D);
}

.ae47n_b5t {
  d: path("M5 3.152h1.087v26.011H5z");
}

.auchd-bya {
  d: path("M23.697 13.097h1.152v.968h-1.152z");
}

.b8c6xjbzu {
  stop-color: var(--svg-color--57d4f4, #57D4F4);
}

.bkwu7aclq {
  stop-color: var(--svg-color--543f68, #543F68);
}

.cb6i7ccig {
  stop-color: var(--svg-color--3054c2, #3054C2);
  stop-opacity: 0;
}

.co-dp-boy {
  stop-color: var(--svg-color--5b5360, #5B5360);
}

.d04-yrbzt {
  stop-color: var(--svg-color--52bbff, #52BBFF);
}

.dxi393zdc {
  d: path("M8.094 10H2.906A.905.905 0 0 1 2 9.089V6.91c0-.505.403-.91.906-.91h5.188c.503 0 .906.405.906.911v2.167a.914.914 0 0 1-.906.922");
}

.e0mfnob8i {
  stop-color: var(--svg-color--5b5763, #5B5763);
}

.ec_yp5rel {
  stop-color: var(--svg-color--625275, #625275);
  stop-opacity: 0;
}

.esbr2i0hz {
  stop-color: var(--svg-color--e2a53e, #E2A53E);
}

.exrefeqbn {
  stop-color: var(--svg-color--eeb742, #EEB742);
}

.fah9lubvo {
  width: 8.907px;
  height: 5.952px;
  x: 14.047px;
  y: 9.617px;
  rx: 0.5px;
}

.ffpfzx-zl {
  stop-color: var(--svg-color--8a8c96, #8A8C96);
  stop-opacity: 0;
}

.fmcs-p8mt {
  width: 0.983px;
  height: 2.466px;
  x: 24.446px;
  y: 12.103px;
  rx: 0.3px;
}

.fmfjh9bjk {
  stop-color: var(--svg-color--cbc9d2, #CBC9D2);
  stop-opacity: 0;
}

.foihnifbr {
  stop-color: var(--svg-color--5c4373, #5C4373);
}

.ft5dv1b6b {
  fill: none;
}

.gaz5-ikjy {
  stop-color: var(--svg-color--645775, #645775);
}

.gtpj9ub3u {
  d: path("M13.028 18.534v-1.987h1.008a.5.5 0 0 1 .5.5v.987a.5.5 0 0 1-.5.5z");
}

.h37282bkq {
  stop-color: var(--svg-color--3d3740, #3D3740);
}

.hhs3ugbbz {
  stop-color: var(--svg-color--8d8ba1, #8D8BA1);
}

.hw0l6_b3m {
  width: 3.954px;
  height: 0.51px;
  x: 16.523px;
  y: 17.545px;
  rx: 0.255px;
}

.hyd2t7bnc {
  width: 2.038px;
  height: 4.005px;
  x: 21.934px;
  y: 16.995px;
  rx: 0.5px;
}

.ig6kwmbek {
  stop-color: var(--svg-color--52bbff, #52BBFF);
  stop-opacity: 0;
}

.ii6uiso8t {
  stop-color: var(--svg-color--3054c2, #3054C2);
}

.iks0hdctb {
  d: path("M23.973 18.534v-1.987h-1.009a.5.5 0 0 0-.5.5v.987a.5.5 0 0 0 .5.5z");
}

.iuj3aib_p {
  stop-color: var(--svg-color--c1bec8, #C1BEC8);
}

.kd4y0t9lz {
  stop-color: var(--svg-color--c7b8d1, #C7B8D1);
}

.ll2f1tqku {
  stop-color: var(--svg-color--b0a8bb, #B0A8BB);
}

.lw175achg {
  width: 0.983px;
  height: 2.466px;
  x: 11.57px;
  y: 12.103px;
  fill: var(--svg-color--c86464, #C86464);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  opacity: var(--svg-opacity--0-55, 0.55);
  rx: 0.3px;
}

.na4hirbhl {
  width: 2.038px;
  height: 4.005px;
  x: 13.027px;
  y: 16.995px;
  rx: 0.5px;
}

.o6vjgw-ml {
  stop-color: var(--svg-color--3893e1, #3893E1);
}

.oe7imj52j {
  stop-color: var(--svg-color--aea1be, #AEA1BE);
}

.ov3qpsbqo {
  stop-color: var(--svg-color--625275, #625275);
}

.phzxyv1gy {
  d: path("M23.973 15.969v2.774a.8.8 0 0 1-.8.8h-9.345a.8.8 0 0 1-.8-.8v-2.774z");
}

.pm-mvhbjw {
  d: path("M8.094 23H2.906A.906.906 0 0 1 2 22.086v-2.172c0-.508.403-.914.906-.914h5.188c.503 0 .906.406.906.914v2.172a.913.913 0 0 1-.906.914");
}

.pwjsze1ek {
  stop-color: var(--svg-color--3f3742, #3F3742);
}

.qn605_dhr {
  stop-color: var(--svg-color--cbc9d2, #CBC9D2);
}

.qoi8rbcjc {
  d: path("M22.953 11.105h-8.906v-.988a.5.5 0 0 1 .5-.5h7.906a.5.5 0 0 1 .5.5z");
}

.re-z6sbgm {
  width: 0.983px;
  height: 2.466px;
  x: 11.57px;
  y: 12.103px;
  rx: 0.3px;
}

.rl06ome0c {
  stop-color: var(--svg-color--625f69, #625F69);
}

.rnnuanlvn {
  d: path("M12.452 13.097h1.152v.968h-1.152z");
}

.ru05sab7f {
  stop-color: var(--svg-color--5a436e, #5A436E);
}

.sa11f7rkh {
  d: path("M13.028 9.75a1.6 1.6 0 0 1 1.6-1.6h7.744a1.6 1.6 0 0 1 1.6 1.6v8.993a.8.8 0 0 1-.8.8h-9.344a.8.8 0 0 1-.8-.8z");
}

.sg8lu-w3g {
  stop-color: var(--svg-color--3f3944, #3F3944);
}

.sjcpnxbbh {
  stop-color: var(--svg-color--d1c4d9, #D1C4D9);
}

.ss5wi3bfk {
  stop-color: var(--svg-color--389bec, #389BEC);
}

.t73s1qbfl {
  stop-color: var(--svg-color--c1bec8, #C1BEC8);
  stop-opacity: 0;
}

.t8x7ctbcq {
  stop-color: var(--svg-color--ddcde7, #DDCDE7);
}

.u42mru57x {
  d: path("M10.255 25h16.49A2.257 2.257 0 0 0 29 22.745V6.255A2.257 2.257 0 0 0 26.745 4h-16.49A2.257 2.257 0 0 0 8 6.255v16.49A2.257 2.257 0 0 0 10.255 25");
}

.virt3cm1j {
  stop-color: var(--svg-color--453a4e, #453A4E);
}

.w--e4jbfb {
  d: path("M7 2H3v28h4z");
}

.wi7combjx {
  stop-color: var(--svg-color--decee6, #DECEE6);
}

.x2_4x9b_o {
  stop-color: var(--svg-color--645775, #645775);
  stop-opacity: 0;
}

.xrmgngu4x {
  stop-color: var(--svg-color--8a8c96, #8A8C96);
}

.xx7rj0btp {
  stop-color: var(--svg-color--aea1be, #AEA1BE);
  stop-opacity: 0;
}

.yafdjqp3g {
  stop-color: var(--svg-color--403b44, #403B44);
}

.zoy0kdz2l {
  width: 5.941px;
  height: 0.51px;
  x: 15.545px;
  y: 16.547px;
  rx: 0.255px;
}

</style>
