<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ioXK5ce)" class="ag3ibpoat"/><path fill="url(#iVZhODc)" class="ag3ibpoat"/><path fill="url(#iuMYtIc)" class="ag3ibpoat"/><path fill="url(#iltsYpc)" class="ag3ibpoat"/><path fill="url(#imZTYMd)" class="ag3ibpoat"/><g filter="url(#irwgrFc)"><rect class="ddkie1fjc"/></g><g filter="url(#i5cZiCZ)"><rect class="wxo_0icfn"/></g><rect fill="url(#iB8kALe)" class="gxo_x8a1h"/><rect fill="url(#iqOwtHc)" class="gxo_x8a1h"/><g filter="url(#iVQgIDe)"><path class="bi51omblu"/><path fill="url(#itSWzHd)" class="awphukbvo"/><path fill="url(#iWYhXce)" class="awphukbvo"/></g><g filter="url(#iZJnkqe)"><path class="hwm1nhbtt"/><path fill="url(#i1wZ3Dd)" class="m7w09ib0i"/></g><path fill="url(#iNOGrmQ)" class="m7w09ib0i"/><path fill="url(#iWSLYId)" class="m7w09ib0i"/><path fill="url(#iuqwx9c)" class="m7w09ib0i"/><defs><linearGradient id="ioXK5ce" x1="19.116" x2="9.726" y1="26" y2="26" gradientUnits="userSpaceOnUse"><stop class="hv9j4obau"/><stop offset="1" class="o6i87ybea"/></linearGradient><linearGradient id="iVZhODc" x1="16.21" x2="16.21" y1="30.531" y2="29.156" gradientUnits="userSpaceOnUse"><stop offset=".068" class="x-utcs1yi"/><stop offset="1" class="ijwloix7c"/></linearGradient><linearGradient id="iltsYpc" x1="16.21" x2="16.21" y1="22.75" y2="24.969" gradientUnits="userSpaceOnUse"><stop class="ernjknbbn"/><stop offset="1" class="jh8kt8rhm"/></linearGradient><linearGradient id="imZTYMd" x1="9.334" x2="11.726" y1="27.764" y2="27.764" gradientUnits="userSpaceOnUse"><stop class="zxbt7isnw"/><stop offset="1" class="cv87p0buz"/></linearGradient><linearGradient id="iB8kALe" x1="16.348" x2="16.348" y1="28.531" y2="27.906" gradientUnits="userSpaceOnUse"><stop class="j12op6wdo"/><stop offset="1" class="xmxzhbcit"/></linearGradient><linearGradient id="iqOwtHc" x1="16.348" x2="16.348" y1="24.938" y2="25.719" gradientUnits="userSpaceOnUse"><stop class="y8amicc2m"/><stop offset="1" class="s2mz5acia"/></linearGradient><linearGradient id="iNOGrmQ" x1="15.929" x2="15.929" y1="24.156" y2="22.219" gradientUnits="userSpaceOnUse"><stop class="mee53imno"/><stop offset="1" class="xzdey_bmk"/></linearGradient><radialGradient id="iuMYtIc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84374 .46876 -2.7023 -10.62865 21.898 23.188)" gradientUnits="userSpaceOnUse"><stop class="z-38zfb1k"/><stop offset="1" class="sg35b-bgy"/></radialGradient><radialGradient id="itSWzHd" cx="0" cy="0" r="1" gradientTransform="matrix(4.29969 0 0 3.5625 22.942 10.906)" gradientUnits="userSpaceOnUse"><stop class="l8ows4u_w"/><stop offset="1" class="v793hhbxh"/></radialGradient><radialGradient id="iWYhXce" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.73437 -2.08828 2.14472 23.913 7.875)" gradientUnits="userSpaceOnUse"><stop class="a7b-esb7f"/><stop offset="1" class="s7pnfdbng"/></radialGradient><radialGradient id="i1wZ3Dd" cx="0" cy="0" r="1" gradientTransform="rotate(62.564 6.672 21.006)scale(8.54578 7.81186)" gradientUnits="userSpaceOnUse"><stop class="t9q16qsye"/><stop offset="1" class="pimqqdhxc"/></radialGradient><radialGradient id="iWSLYId" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43753 -6.24998 3.09279 -2.1959 25.366 22.219)" gradientUnits="userSpaceOnUse"><stop offset=".389" class="lhkmpx-js"/><stop offset="1" class="ksf159bpz"/></radialGradient><radialGradient id="iuqwx9c" cx="0" cy="0" r="1" gradientTransform="matrix(11.3125 0 0 34.5682 13.054 12.99)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="vt0l5-39m"/><stop offset=".975" class="odf-jnbrz"/></radialGradient><filter id="irwgrFc" width="6.732" height="3.87" x="12.728" y="25.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3139" stdDeviation=".25"/></filter><filter id="i5cZiCZ" width="6.564" height="3.094" x="13.066" y="25.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.964706 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3139"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.635294 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3139" result="effect2_innerShadow_18_3139"/></filter><filter id="iVQgIDe" width="7.423" height="14.419" x="19.13" y="8.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.423529 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3139"/></filter><filter id="iZJnkqe" width="20.88" height="22.511" x="6.868" y="1.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="4" dy="-1"/><feGaussianBlur stdDeviation="2.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.219608 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3139"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:boxing-glove" /></template>
<style>
.a7b-esb7f {
  stop-color: var(--svg-color--ff5f93, #FF5F93);
}

.ag3ibpoat {
  d: path("M9.726 22.44h12.968v6.794a1 1 0 0 1-1 1H10.726a1 1 0 0 1-1-1z");
}

.awphukbvo {
  d: path("M19.33 8.02h4.223a3 3 0 0 1 3 3v4.452a6 6 0 0 1-1.79 4.275l-1.795 1.767c-.102.142-.237.445-.237.926H21.33v-.64h-2z");
}

.bi51omblu {
  fill: var(--svg-color--ff378f, #FF378F);
  d: path("M19.33 8.02h4.223a3 3 0 0 1 3 3v4.452a6 6 0 0 1-1.79 4.275l-1.795 1.767c-.102.142-.237.445-.237.926H21.33v-.64h-2z");
}

.cv87p0buz {
  stop-color: var(--svg-color--7d7484, #7D7484);
  stop-opacity: 0;
}

.ddkie1fjc {
  width: 5.732px;
  height: 2.87px;
  x: 13.228px;
  y: 25.578px;
  fill: var(--svg-color--a28cb5, #A28CB5);
  rx: 0.5px;
}

.ernjknbbn {
  stop-color: var(--svg-color--cec1d0, #CEC1D0);
}

.ft5dv1b6b {
  fill: none;
}

.gxo_x8a1h {
  width: 5.964px;
  height: 3.094px;
  x: 13.366px;
  y: 25.219px;
  rx: 0.5px;
}

.hv9j4obau {
  stop-color: var(--svg-color--beaec6, #BEAEC6);
}

.hwm1nhbtt {
  fill: var(--svg-color--ee3863, #EE3863);
  d: path("M13.868 2.236a7 7 0 0 0-7 7v5.249q0 .234.015.464v1.237a6 6 0 0 0 1.654 4.136l.635.668a2 2 0 0 1 .551 1.379v.877a.5.5 0 0 0 .5.5h12.008a.5.5 0 0 0 .5-.5V18.12a6.97 6.97 0 0 0 1.017-3.635v-5.25a7 7 0 0 0-7-7z");
}

.ijwloix7c {
  stop-color: var(--svg-color--946cb6, #946CB6);
  stop-opacity: 0;
}

.j12op6wdo {
  stop-color: var(--svg-color--b18cd0, #B18CD0);
}

.jh8kt8rhm {
  stop-color: var(--svg-color--cec1d0, #CEC1D0);
  stop-opacity: 0;
}

.ksf159bpz {
  stop-color: var(--svg-color--ff3989, #FF3989);
  stop-opacity: 0;
}

.l8ows4u_w {
  stop-color: var(--svg-color--ff6da9, #FF6DA9);
}

.lhkmpx-js {
  stop-color: var(--svg-color--ff3989, #FF3989);
}

.m7w09ib0i {
  d: path("M13.868 2.236a7 7 0 0 0-7 7v5.249q0 .234.015.464v1.237a6 6 0 0 0 1.654 4.136l.635.668a2 2 0 0 1 .551 1.379v.877a.5.5 0 0 0 .5.5h12.008a.5.5 0 0 0 .5-.5V18.12a6.97 6.97 0 0 0 1.017-3.635v-5.25a7 7 0 0 0-7-7z");
}

.mee53imno {
  stop-color: var(--svg-color--c72985, #C72985);
}

.o6i87ybea {
  stop-color: var(--svg-color--a794ad, #A794AD);
}

.odf-jnbrz {
  stop-color: var(--svg-color--ff7aa3, #FF7AA3);
}

.pimqqdhxc {
  stop-color: var(--svg-color--ff6aa0, #FF6AA0);
  stop-opacity: 0;
}

.s2mz5acia {
  stop-color: var(--svg-color--edd5dd, #EDD5DD);
  stop-opacity: 0;
}

.s7pnfdbng {
  stop-color: var(--svg-color--ff5f93, #FF5F93);
  stop-opacity: 0;
}

.sg35b-bgy {
  stop-color: var(--svg-color--d3cad7, #D3CAD7);
  stop-opacity: 0;
}

.t9q16qsye {
  stop-color: var(--svg-color--ff6aa0, #FF6AA0);
}

.v793hhbxh {
  stop-color: var(--svg-color--ff6da9, #FF6DA9);
  stop-opacity: 0;
}

.vt0l5-39m {
  stop-color: var(--svg-color--ff7aa3, #FF7AA3);
  stop-opacity: 0;
}

.wxo_0icfn {
  width: 5.964px;
  height: 3.094px;
  x: 13.366px;
  y: 25.219px;
  fill: var(--svg-color--d8cae2, #D8CAE2);
  rx: 0.5px;
}

.x-utcs1yi {
  stop-color: var(--svg-color--946cb6, #946CB6);
}

.xmxzhbcit {
  stop-color: var(--svg-color--b18cd0, #B18CD0);
  stop-opacity: 0;
}

.xzdey_bmk {
  stop-color: var(--svg-color--c72985, #C72985);
  stop-opacity: 0;
}

.y8amicc2m {
  stop-color: var(--svg-color--edd5dd, #EDD5DD);
}

.z-38zfb1k {
  stop-color: var(--svg-color--d3cad7, #D3CAD7);
}

.zxbt7isnw {
  stop-color: var(--svg-color--7d7484, #7D7484);
}

</style>
