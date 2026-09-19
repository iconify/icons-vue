<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGRMObZ)"><path fill="url(#ihNgABc)" class="fn4n99bcw"/><path fill="url(#iDRrHGT)" class="fn4n99bcw"/><path fill="url(#inCnJ8H)" class="fn4n99bcw"/><path fill="url(#ilIHWEd)" class="fn4n99bcw"/><path fill="url(#iDO50ge)" class="fn4n99bcw"/><path fill="url(#i02SoRb)" class="fn4n99bcw"/><path fill="url(#iD8ViSd)" class="fn4n99bcw"/></g><rect fill="url(#iGHNroc)" transform="matrix(0 1 1 0 9.54 2.018)" class="w9j89i09g"/><rect fill="url(#i8f0AIe)" transform="matrix(0 1 1 0 9.54 2.018)" class="w9j89i09g"/><rect fill="url(#iaMawVH)" transform="matrix(0 1 1 0 9.54 2.018)" class="w9j89i09g"/><g filter="url(#iEY1sSK)"><rect fill="url(#ivcgCwb)" transform="matrix(0 1 1 0 16.838 8.902)" class="wg1br-r4n"/></g><g filter="url(#iJTiqBc)"><rect fill="url(#iy1iWtU)" transform="matrix(0 1 1 0 12.178 3.205)" class="z98qqbrqy"/></g><g filter="url(#iXNi7Zr)"><rect fill="url(#iCPHEed)" transform="scale(1 -1)rotate(-32.82 -23.788 -14.853)" class="se-fv22-b"/></g><g filter="url(#i812lOd)"><rect fill="url(#ivcgCwb)" transform="matrix(0 1 1 0 21.313 9.68)" class="wg1br-r4n"/></g><g filter="url(#iu2J0yd)"><rect fill="url(#ivcgCwb)" transform="matrix(0 1 1 0 25.943 10.801)" class="wg1br-r4n"/></g><path fill="url(#iOFGyOe)" class="h183lcgfl"/><defs><linearGradient id="iD8ViSd" x1="24.342" x2="28.358" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="ctulet8ct"/><stop offset="1" class="ym70zel1f"/></linearGradient><linearGradient id="iGHNroc" x1="5.442" x2="5.442" y1="-1.384" y2="1.992" gradientUnits="userSpaceOnUse"><stop class="rqw3eabdh"/><stop offset="1" class="fk6-ao0tx"/></linearGradient><linearGradient id="i8f0AIe" x1="14.104" x2="12.027" y1="4.026" y2="4.026" gradientUnits="userSpaceOnUse"><stop class="ga1oo6bdd"/><stop offset="1" class="az7rp9iah"/></linearGradient><linearGradient id="iaMawVH" x1="5.622" x2="7.432" y1="7.661" y2="3.593" gradientUnits="userSpaceOnUse"><stop class="aoqxd366p"/><stop offset="1" class="n7kdr6bjq"/></linearGradient><linearGradient id="ivcgCwb" x1=".813" x2="6.25" y1="2.225" y2=".954" gradientUnits="userSpaceOnUse"><stop class="kbuu85jbe"/><stop offset="1" class="q59v_vbuo"/></linearGradient><linearGradient id="iy1iWtU" x1="1.89" x2="14.384" y1="2.179" y2="-2.398" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="q59v_vbuo"/></linearGradient><linearGradient id="iCPHEed" x1="-.286" x2="6.813" y1="1.361" y2=".091" gradientUnits="userSpaceOnUse"><stop class="kbuu85jbe"/><stop offset="1" class="q59v_vbuo"/></linearGradient><radialGradient id="ihNgABc" cx="0" cy="0" r="1" gradientTransform="rotate(123.538 9.147 13.205)scale(20.5218 30.2361)" gradientUnits="userSpaceOnUse"><stop class="uktlsgetn"/><stop offset="1" class="vu-mgjy8s"/></radialGradient><radialGradient id="iDRrHGT" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.75553 -1.47134 0 15.86 8.766)" gradientUnits="userSpaceOnUse"><stop class="he-5e1bka"/><stop offset="1" class="xtldl8dlu"/></radialGradient><radialGradient id="inCnJ8H" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.14032 -1.53295 0 20.404 7.9)" gradientUnits="userSpaceOnUse"><stop class="he-5e1bka"/><stop offset="1" class="xtldl8dlu"/></radialGradient><radialGradient id="ilIHWEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.92863 -1.27281 0 24.818 9.328)" gradientUnits="userSpaceOnUse"><stop class="he-5e1bka"/><stop offset="1" class="xtldl8dlu"/></radialGradient><radialGradient id="iDO50ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.375 -.20313 0 23.848 10.169)" gradientUnits="userSpaceOnUse"><stop class="ncscsibxz"/><stop offset="1" class="p5a8sofmi"/></radialGradient><radialGradient id="i02SoRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.80817 -.3257 0 19.452 7.987)" gradientUnits="userSpaceOnUse"><stop class="ncscsibxz"/><stop offset="1" class="p5a8sofmi"/></radialGradient><radialGradient id="iOFGyOe" cx="0" cy="0" r="1" gradientTransform="matrix(.82222 -3.49518 .7984 .18782 14.389 11.102)" gradientUnits="userSpaceOnUse"><stop class="o5rj2wb-n"/><stop offset="1" class="ek92bwb4k"/></radialGradient><filter id="iGRMObZ" width="26.537" height="28.714" x="2.821" y="1.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5210"/></filter><filter id="iEY1sSK" width="3.908" height="6.885" x="15.838" y="7.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5210" stdDeviation=".5"/></filter><filter id="iJTiqBc" width="3.869" height="13.359" x="11.178" y="2.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5210" stdDeviation=".5"/></filter><filter id="iXNi7Zr" width="9.346" height="7.507" x="3.668" y="12.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5210" stdDeviation=".5"/></filter><filter id="i812lOd" width="3.908" height="6.885" x="20.313" y="8.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5210" stdDeviation=".5"/></filter><filter id="iu2J0yd" width="3.908" height="6.885" x="24.943" y="9.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5210" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-up-dark" /></template>
<style>
.aoqxd366p {
  stop-color: var(--svg-color--644e4b, #644E4B);
}

.az7rp9iah {
  stop-color: var(--svg-color--493035, #493035);
  stop-opacity: 0;
}

.ctulet8ct {
  stop-color: var(--svg-color--5a403e, #5A403E);
  stop-opacity: 0;
}

.ek92bwb4k {
  stop-color: var(--svg-color--1c0d0b, #1C0D0B);
  stop-opacity: 0;
}

.fk6-ao0tx {
  stop-color: var(--svg-color--2d1b19, #2D1B19);
  stop-opacity: 0;
}

.fn4n99bcw {
  d: path("M4.116 18.12c-1.24-.86-1.701-2.597-.888-3.849a2.657 2.657 0 0 1 3.703-.781l2.61 1.695V4.655a2.637 2.637 0 0 1 5.274 0v4.284a2.493 2.493 0 0 1 4.563.344a2.724 2.724 0 0 1 4.487.884a2.723 2.723 0 0 1 4.493 2.07v3.102q0 .053-.002.104v4.859c0 1.431-.848 3.878-2.51 6.022a9 9 0 0 1-.537.65a9.2 9.2 0 0 1-6.832 3.008a9.2 9.2 0 0 1-7.577-3.944c-.604-.833-.892-1.507-1.179-2.176c-.22-.513-.438-1.023-.796-1.601c-.567-.913-1.4-1.59-1.865-1.969l-.099-.08h.002z");
}

.ft5dv1b6b {
  fill: none;
}

.ga1oo6bdd {
  stop-color: var(--svg-color--493035, #493035);
}

.h183lcgfl {
  d: path("M17.185 7.612v6.423h-2.37V8.939a2.49 2.49 0 0 1 2.37-1.327");
}

.he-5e1bka {
  stop-color: var(--svg-color--220f0d, #220F0D);
}

.kbuu85jbe {
  stop-color: var(--svg-color--624e4c, #624E4C);
}

.n7kdr6bjq {
  stop-color: var(--svg-color--644e4b, #644E4B);
  stop-opacity: 0;
}

.ncscsibxz {
  stop-color: var(--svg-color--362522, #362522);
}

.o5rj2wb-n {
  stop-color: var(--svg-color--1c0d0b, #1C0D0B);
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.p5a8sofmi {
  stop-color: var(--svg-color--362522, #362522);
  stop-opacity: 0;
}

.q59v_vbuo {
  stop-color: var(--svg-color--624e4c, #624E4C);
  stop-opacity: 0;
}

.rqw3eabdh {
  stop-color: var(--svg-color--2d1b19, #2D1B19);
}

.se-fv22-b {
  width: 8.33px;
  height: 2.167px;
  rx: 1.083px;
}

.uktlsgetn {
  stop-color: var(--svg-color--4e3637, #4E3637);
}

.vu-mgjy8s {
  stop-color: var(--svg-color--452a32, #452A32);
}

.w9j89i09g {
  width: 14.864px;
  height: 5.274px;
  rx: 2.637px;
}

.wg1br-r4n {
  width: 4.885px;
  height: 1.908px;
  rx: 0.954px;
}

.xtldl8dlu {
  stop-color: var(--svg-color--220f0d, #220F0D);
  stop-opacity: 0;
}

.ym70zel1f {
  stop-color: var(--svg-color--5a403e, #5A403E);
}

.z98qqbrqy {
  width: 11.359px;
  height: 1.869px;
  rx: 0.934px;
}

</style>
