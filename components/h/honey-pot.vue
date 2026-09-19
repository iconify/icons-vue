<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iJrNZnB)" class="kiib3ebao"/><path fill="url(#iwNMs8H)" class="xm1e01bih"/><path fill="url(#ipBxMKX)" class="qyrn2tbxk"/><path fill="url(#iONx4id)" class="qyrn2tbxk"/><path fill="url(#iE3fdve)" class="qyrn2tbxk"/><path fill="url(#iQfBUhc)" class="z5xn7sb8q"/><path fill="url(#iU8kZ3d)" class="z5xn7sb8q"/><path fill="url(#irdTexc)" class="z5xn7sb8q"/><path fill="url(#iIaWysz)" class="z5xn7sb8q"/><path fill="url(#iP9AUEd)" class="z5xn7sb8q"/><path fill="url(#iM4qLod)" class="yjyzrxbua"/><g filter="url(#iIvUwQd)"><path class="vxmmm3bek"/></g><path fill="url(#izMIj5b)" class="du02r0b0v"/><path fill="url(#iYWpK9c)" class="du02r0b0v"/><path fill="url(#ic3ujYd)" class="du02r0b0v"/><g filter="url(#ilSLONb)"><path class="rqkk-ztnr"/></g><path fill="url(#i6u2vxV)" class="m0t9424qu"/><g filter="url(#iPSwmFb)"><path fill="url(#iizzDJe)" class="c3as9lb8c"/></g><g filter="url(#izxTwJc)"><path fill="url(#im9HBub)" class="m-ry_bvro"/></g><defs><linearGradient id="iwNMs8H" x1="18.031" x2="19.5" y1="6.219" y2="6.625" gradientUnits="userSpaceOnUse"><stop class="eeln3cb_c"/><stop offset=".624" class="q4n--dbwk"/><stop offset="1" class="b7vcw4b2d"/></linearGradient><linearGradient id="ipBxMKX" x1="6" x2="26" y1="8.375" y2="8.375" gradientUnits="userSpaceOnUse"><stop class="cy-zcwbnr"/><stop offset=".603" class="xgmjmy0wn"/><stop offset=".809" class="a83ludbts"/><stop offset="1" class="fiey3jbim"/></linearGradient><linearGradient id="iQfBUhc" x1="7.75" x2="24.75" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="akv5zczmz"/><stop offset=".287" class="x496j7b4d"/><stop offset=".629" class="b6xk0abeg"/><stop offset="1" class="hushotbag"/></linearGradient><linearGradient id="iU8kZ3d" x1="21" x2="21" y1="30" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="xif_90b9p"/><stop offset=".657" class="ruq2rcc-b"/></linearGradient><linearGradient id="iP9AUEd" x1="16" x2="16" y1="8.781" y2="9.922" gradientUnits="userSpaceOnUse"><stop offset=".096" class="ricqfojvn"/><stop offset=".848" class="p-sqlybfl"/></linearGradient><linearGradient id="iM4qLod" x1="4.61" x2="27.39" y1="24.45" y2="24.45" gradientUnits="userSpaceOnUse"><stop class="bw7mtli4i"/><stop offset=".157" class="obs_54cbe"/><stop offset=".451" class="pmc2_yben"/><stop offset=".791" class="ne6acebxh"/><stop offset="1" class="vt1cwxbai"/></linearGradient><linearGradient id="izMIj5b" x1="9.188" x2="22.75" y1="8.188" y2="8.188" gradientUnits="userSpaceOnUse"><stop class="my4v_wxhf"/><stop offset=".336" class="e59k3tpiv"/><stop offset=".535" class="y3tkggoki"/><stop offset=".742" class="libbhw1oc"/><stop offset=".889" class="zoj2ppbmg"/><stop offset="1" class="f5y-t7bdu"/></linearGradient><linearGradient id="iYWpK9c" x1="16.005" x2="16" y1="6.82" y2="7.781" gradientUnits="userSpaceOnUse"><stop class="o3xhekbsx"/><stop offset="1" class="b3e-vdiip"/></linearGradient><linearGradient id="iizzDJe" x1="9.19" x2="22.753" y1="8.109" y2="8.109" gradientUnits="userSpaceOnUse"><stop class="bu7w9eb8a"/><stop offset=".829" class="yxs8p9bsn"/></linearGradient><radialGradient id="iJrNZnB" cx="0" cy="0" r="1" gradientTransform="rotate(132.709 9.408 5.944)scale(2.76434)" gradientUnits="userSpaceOnUse"><stop class="wlym7kb6r"/><stop offset=".756" class="o6jn4sbjw"/></radialGradient><radialGradient id="iONx4id" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -8.6009 0 22.906 7.438)" gradientUnits="userSpaceOnUse"><stop class="qx1dhac4r"/><stop offset=".767" class="wbfntwm-m"/></radialGradient><radialGradient id="iE3fdve" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90625 -8.31422 0 7.906 8.313)" gradientUnits="userSpaceOnUse"><stop class="b3h07cc5r"/><stop offset=".565" class="iorxj5bpk"/></radialGradient><radialGradient id="irdTexc" cx="0" cy="0" r="1" gradientTransform="rotate(135.864 .986 4.839)scale(8.79564 10.0522)" gradientUnits="userSpaceOnUse"><stop class="kq_z3fbel"/><stop offset="1" class="h4i4nhb_g"/></radialGradient><radialGradient id="iIaWysz" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.75 -16.9375 0 23.625 11.563)" gradientUnits="userSpaceOnUse"><stop class="i2smiekrp"/><stop offset=".574" class="qt_9twbiv"/></radialGradient><radialGradient id="ic3ujYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0625 -12.2813 0 22.563 7.063)" gradientUnits="userSpaceOnUse"><stop class="xf6to5bmx"/><stop offset="1" class="nzhiaubdh"/></radialGradient><radialGradient id="i6u2vxV" cx="0" cy="0" r="1" gradientTransform="rotate(124.484 7.26 11.682)scale(1.98703)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="u3xyxrkmr"/><stop offset=".771" class="qyy-ij41p"/></radialGradient><radialGradient id="im9HBub" cx="0" cy="0" r="1" gradientTransform="rotate(120.542 5.396 9.759)scale(2.82109 1.708)" gradientUnits="userSpaceOnUse"><stop class="nm--fvbpt"/><stop offset="1" class="walkd9itv"/></radialGradient><filter id="iIvUwQd" width="15.594" height="7.031" x="8.094" y="6.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30505" stdDeviation=".5"/></filter><filter id="ilSLONb" width="2.773" height="2.797" x="19.047" y="11.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30505" stdDeviation=".125"/></filter><filter id="iPSwmFb" width="14.344" height="6.165" x="8.859" y="6.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30505" stdDeviation=".25"/></filter><filter id="izxTwJc" width="4.172" height="4.984" x="14.313" y="7.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30505" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:honey-pot" /></template>
<style>
.a83ludbts {
  stop-color: var(--svg-color--c6844b, #C6844B);
}

.akv5zczmz {
  stop-color: var(--svg-color--aa7055, #AA7055);
}

.b3e-vdiip {
  stop-color: var(--svg-color--b48a31, #B48A31);
  stop-opacity: 0;
}

.b3h07cc5r {
  stop-color: var(--svg-color--ae7352, #AE7352);
}

.b6xk0abeg {
  stop-color: var(--svg-color--d6855a, #D6855A);
}

.b7vcw4b2d {
  stop-color: var(--svg-color--82573c, #82573C);
}

.bu7w9eb8a {
  stop-color: var(--svg-color--b68d22, #B68D22);
}

.bw7mtli4i {
  stop-color: var(--svg-color--7c5750, #7C5750);
}

.c3as9lb8c {
  d: path("M21.768 9.17c.146-.25.662-1.56.935-2.06H9.36s.61 2.289 1.266 3.468c.656 1.18 1.947 1.697 3.108 1.697c1.13 0 1.955-.59 2.465-1.452c.226-.383 1.132-1.87 1.445-2.47c.281-.443 1.165-.365 1.365 0l.4.789c.28.505.57.742 1.22.742c.64 0 .85-.218 1.14-.714");
}

.cy-zcwbnr {
  stop-color: var(--svg-color--9e6d47, #9E6D47);
}

.du02r0b0v {
  d: path("M21.93 9.32c.36-.57.843-1.78 1.117-2.5H8.953s.453 2.396 1.156 3.633c.704 1.237 1.927 2.297 3.454 2.297c1.13 0 2.14-.527 2.75-1.492c.608-.966.625-1.469 1.18-2.07c.554-.602 1.07-.575 1.437.132c.28.54.87.88 1.52.88c.64 0 1.12-.31 1.48-.88");
}

.e59k3tpiv {
  stop-color: var(--svg-color--d89640, #D89640);
}

.eeln3cb_c {
  stop-color: var(--svg-color--76442d, #76442D);
}

.f5y-t7bdu {
  stop-color: var(--svg-color--eebb35, #EEBB35);
}

.fiey3jbim {
  stop-color: var(--svg-color--c48950, #C48950);
}

.ft5dv1b6b {
  fill: none;
}

.h4i4nhb_g {
  stop-color: var(--svg-color--96673d, #96673D);
  stop-opacity: 0;
}

.hushotbag {
  stop-color: var(--svg-color--d28d59, #D28D59);
}

.i2smiekrp {
  stop-color: var(--svg-color--e8a86c, #E8A86C);
}

.iorxj5bpk {
  stop-color: var(--svg-color--b77855, #B77855);
  stop-opacity: 0;
}

.kiib3ebao {
  cx: 19.426px;
  cy: 3.734px;
  r: 1.734px;
}

.kq_z3fbel {
  stop-color: var(--svg-color--95653d, #95653D);
}

.libbhw1oc {
  stop-color: var(--svg-color--cd8607, #CD8607);
}

.m-ry_bvro {
  d: path("M18.147 7.994a.125.125 0 0 0-.076-.238zM16.47 9.875l.114.051zm-1.81 2.113a.125.125 0 0 0 .056.243zm3.412-4.232c-.216.069-.512.293-.814.635a5.7 5.7 0 0 0-.902 1.433l.228.102c.26-.582.572-1.042.861-1.37c.294-.332.553-.514.703-.562zm-1.716 2.068c-.138.307-.407.82-.726 1.273c-.16.226-.33.434-.498.595c-.172.162-.332.264-.471.296l.055.243c.204-.046.404-.184.587-.358a4 4 0 0 0 .531-.633a8.5 8.5 0 0 0 .75-1.314z");
}

.m0t9424qu {
  d: path("M20.75 13.96c.43 0 .914-.414.914-1.038s-.602-1.258-1.227-1.258c-.624 0-1.046.532-1.046 1.156s.453 1.14 1.359 1.14");
}

.my4v_wxhf {
  stop-color: var(--svg-color--ab8237, #AB8237);
}

.ne6acebxh {
  stop-color: var(--svg-color--a06150, #A06150);
}

.nm--fvbpt {
  stop-color: var(--svg-color--f7c357, #F7C357);
}

.nzhiaubdh {
  stop-color: var(--svg-color--fcce59, #FCCE59);
  stop-opacity: 0;
}

.o3xhekbsx {
  stop-color: var(--svg-color--af8435, #AF8435);
}

.o6jn4sbjw {
  stop-color: var(--svg-color--77391a, #77391A);
}

.obs_54cbe {
  stop-color: var(--svg-color--804e49, #804E49);
}

.p-sqlybfl {
  stop-color: var(--svg-color--9a4a0d, #9A4A0D);
  stop-opacity: 0;
}

.pmc2_yben {
  stop-color: var(--svg-color--925154, #925154);
}

.q4n--dbwk {
  stop-color: var(--svg-color--895e48, #895E48);
}

.qt_9twbiv {
  stop-color: var(--svg-color--e8a86c, #E8A86C);
  stop-opacity: 0;
}

.qx1dhac4r {
  stop-color: var(--svg-color--d29d6c, #D29D6C);
}

.qyrn2tbxk {
  d: path("M24.91 6.82H7.09c-.6 0-1.09.49-1.09 1.09S6.49 9 7.09 9h17.82c.6 0 1.09-.49 1.09-1.09s-.49-1.09-1.09-1.09");
}

.qyy-ij41p {
  stop-color: var(--svg-color--f1ab38, #F1AB38);
}

.ricqfojvn {
  stop-color: var(--svg-color--99490c, #99490C);
}

.rqkk-ztnr {
  fill: var(--svg-color--d1854f, #D1854F);
  d: path("M20.656 14.07c.43 0 .914-.415.914-1.039s-.602-1.258-1.226-1.258s-1.047.533-1.047 1.157s.453 1.14 1.36 1.14");
}

.ruq2rcc-b {
  stop-color: var(--svg-color--c66b68, #C66B68);
  stop-opacity: 0;
}

.u3xyxrkmr {
  stop-color: var(--svg-color--ffcd5e, #FFCD5E);
}

.vt1cwxbai {
  stop-color: var(--svg-color--9b6654, #9B6654);
}

.vxmmm3bek {
  fill: var(--svg-color--904012, #904012);
  d: path("M21.434 9.568s0-.009.01-.009l1.244-2.153H9.093l2.187 3.688c.468.83 1.396 1.344 2.481 1.344c2.123 0 2.534-1.804 3.425-3.346c.197-.337 1.01-.337 1.197 0l.262.45c.262.467.795.787 1.403.787c.599 0 1.114-.303 1.385-.761");
}

.walkd9itv {
  stop-color: var(--svg-color--f9c557, #F9C557);
  stop-opacity: 0;
}

.wbfntwm-m {
  stop-color: var(--svg-color--d49f6d, #D49F6D);
  stop-opacity: 0;
}

.wlym7kb6r {
  stop-color: var(--svg-color--a87d68, #A87D68);
}

.x496j7b4d {
  stop-color: var(--svg-color--c57357, #C57357);
}

.xf6to5bmx {
  stop-color: var(--svg-color--fece55, #FECE55);
}

.xgmjmy0wn {
  stop-color: var(--svg-color--9e491e, #9E491E);
}

.xif_90b9p {
  stop-color: var(--svg-color--c66d81, #C66D81);
}

.xm1e01bih {
  d: path("m18.3 5.04l-1.15 4.29l1.45.39l1.15-4.29z");
}

.y3tkggoki {
  stop-color: var(--svg-color--f1b321, #F1B321);
}

.yjyzrxbua {
  d: path("M6.56 24.45h18.88L27.39 17H4.61z");
}

.yxs8p9bsn {
  stop-color: var(--svg-color--ffd15d, #FFD15D);
}

.z5xn7sb8q {
  d: path("M23 9H9a5.002 5.002 0 0 0-4.82 6.33L7.63 28.6c.22.82.97 1.4 1.82 1.4h13.1c.85 0 1.6-.58 1.81-1.4l3.45-13.23A5.002 5.002 0 0 0 23 9");
}

.zoj2ppbmg {
  stop-color: var(--svg-color--f0af1f, #F0AF1F);
}

</style>
