<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="iBWt1rd" width="26" height="28" x="3" y="2" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path fill="url(#iADoeQd)" class="dml5iubiz"/><path fill="url(#iTCz3Oy)" class="dml5iubiz"/></mask><g class="ft5dv1b6b"><g filter="url(#iZiezpd)"><path fill="url(#iADoeQd)" class="dml5iubiz"/><path fill="url(#iTCz3Oy)" class="dml5iubiz"/><path fill="url(#iOsLgSU)" class="dml5iubiz"/><path fill="url(#iF4FQhl)" class="dml5iubiz"/><path fill="url(#ih5Gl1d)" class="dml5iubiz"/><path fill="url(#iLaxffc)" class="dml5iubiz"/></g><g mask="url(#iBWt1rd)"><g filter="url(#iLeoQ7d)"><path clip-rule="evenodd" class="q1g6-4b4a"/></g><g filter="url(#iRna5Pb)"><path clip-rule="evenodd" class="xg-2dhobs"/></g></g><path clip-rule="evenodd" class="cbxcmk3zh"/><path fill="url(#iXbhHze)" clip-rule="evenodd" class="b2qjdyb8h"/><path fill="url(#ik2lcie)" clip-rule="evenodd" class="b2qjdyb8h"/><path stroke="url(#i1VeuiP)" class="d7xnj-bfo"/><circle fill="url(#iF6GqVb)" class="xxps_acjr"/><circle fill="url(#iEsQ7Pc)" class="xxps_acjr"/><circle fill="url(#iCDhNAc)" class="xxps_acjr"/><path class="qlijq8b2k"/><path fill="url(#ixMgiId)" class="ppq8wb3wy"/><path fill="url(#iY56Rcb)" class="ppq8wb3wy"/><path fill="url(#iyYuUMe)" class="ppq8wb3wy"/><g filter="url(#imisMzb)"><path stroke="url(#iei1kWd)" class="gr17p0bzf"/></g><g filter="url(#idON1Ge)"><path stroke="url(#ibMBLEe)" class="my7q2k7tl"/></g><g filter="url(#i0tSTSi)"><path stroke="url(#iu1b4yd)" class="k7pi0gbkg"/></g><g filter="url(#iZbg3xc)"><path stroke="url(#icLVIVc)" class="gc3qxm91j"/></g><defs><radialGradient id="iTCz3Oy" cx="0" cy="0" r="1" gradientTransform="matrix(0 6 -8.00453 0 15.5 21)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="xaywjsqib"/><stop offset=".824" class="gy8ye8bze"/></radialGradient><radialGradient id="iOsLgSU" cx="0" cy="0" r="1" gradientTransform="matrix(.5 9.5 -4.04609 .21295 22 6)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="so6bj_boq"/><stop offset="1" class="fbtwhkbxw"/></radialGradient><radialGradient id="iF4FQhl" cx="0" cy="0" r="1" gradientTransform="matrix(.50001 18.50004 -4.25956 .11513 17 3.5)" gradientUnits="userSpaceOnUse"><stop class="so6bj_boq"/><stop offset="1" class="fbtwhkbxw"/></radialGradient><radialGradient id="ih5Gl1d" cx="0" cy="0" r="1" gradientTransform="matrix(.5 9.5 -2.93887 .15468 12.5 6.5)" gradientUnits="userSpaceOnUse"><stop class="so6bj_boq"/><stop offset="1" class="fbtwhkbxw"/></radialGradient><radialGradient id="iLaxffc" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 4 -2.89107 3.25246 5.5 12)" gradientUnits="userSpaceOnUse"><stop class="ysb6dzbhm"/><stop offset="1" class="fbtwhkbxw"/></radialGradient><radialGradient id="ik2lcie" cx="0" cy="0" r="1" gradientTransform="matrix(.5 4 -4 .5 15.5 21)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="x4i5ofbwo"/><stop offset=".962" class="aq6uxabqk"/></radialGradient><radialGradient id="iEsQ7Pc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -3.5 0 16 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="ij89jwu6o"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iCDhNAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -3.5 0 16 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="dju9_srsu"/><stop offset=".773" class="r_sm0j9fy"/></radialGradient><radialGradient id="ixMgiId" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.5 -2.5243 -.84144 16 21.5)" gradientUnits="userSpaceOnUse"><stop class="of078394p"/><stop offset="1" class="la0ek6bdw"/></radialGradient><radialGradient id="iY56Rcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5 -2.5 0 16 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dk7y_c03w"/><stop offset="1" class="cjhkubc7d"/></radialGradient><radialGradient id="iyYuUMe" cx="0" cy="0" r="1" gradientTransform="matrix(.5 1 -1.20593 .60296 16.5 20)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="yd5es9fiw"/><stop offset="1" class="z3n19ac1i"/></radialGradient><linearGradient id="iADoeQd" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="iddo2zb9v"/><stop offset="1" class="rkbgt5mew"/></linearGradient><linearGradient id="iXbhHze" x1="18" x2="13.5" y1="18" y2="25" gradientUnits="userSpaceOnUse"><stop class="a4q2dhbok"/><stop offset="1" class="jjevi1bao"/></linearGradient><linearGradient id="i1VeuiP" x1="18.5" x2="15" y1="17" y2="25" gradientUnits="userSpaceOnUse"><stop class="uz242denu"/><stop offset="1" class="nvem8qkfb"/></linearGradient><linearGradient id="iF6GqVb" x1="17" x2="14.5" y1="17.5" y2="23.5" gradientUnits="userSpaceOnUse"><stop class="jy2gxibjv"/><stop offset="1" class="zdy90zbsj"/></linearGradient><linearGradient id="iei1kWd" x1="29.558" x2="29.427" y1="13.471" y2="14.912" gradientUnits="userSpaceOnUse"><stop class="gcdycdcli"/><stop offset="1" class="lb578xbgf"/></linearGradient><linearGradient id="ibMBLEe" x1="13.5" x2="15.597" y1="15" y2="12.117" gradientUnits="userSpaceOnUse"><stop class="gcdycdcli"/><stop offset="1" class="lb578xbgf"/></linearGradient><linearGradient id="iu1b4yd" x1="18.5" x2="20.597" y1="15" y2="12.117" gradientUnits="userSpaceOnUse"><stop class="gcdycdcli"/><stop offset="1" class="lb578xbgf"/></linearGradient><linearGradient id="icLVIVc" x1="26.5" x2="24.256" y1="22.5" y2="26" gradientUnits="userSpaceOnUse"><stop class="u1evcdc0f"/><stop offset="1" class="lb578xbgf"/></linearGradient><filter id="iZiezpd" width="25.368" height="29" x="3.316" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.588235 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_656"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.423529 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4791_656" result="effect2_innerShadow_4791_656"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.756863 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4791_656" result="effect3_innerShadow_4791_656"/></filter><filter id="iLeoQ7d" width="3" height="13.484" x="11.75" y="2.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_656" stdDeviation=".5"/></filter><filter id="iRna5Pb" width="3" height="13.484" x="17.25" y="2.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_656" stdDeviation=".5"/></filter><filter id="imisMzb" width="7.224" height="4.5" x="21.276" y="11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_656" stdDeviation=".375"/></filter><filter id="idON1Ge" width="2.5" height="7.198" x="11.5" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_656" stdDeviation=".375"/></filter><filter id="i0tSTSi" width="2.5" height="7.198" x="16.5" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_656" stdDeviation=".375"/></filter><filter id="iZbg3xc" width="4.511" height="10.5" x="22" y="16.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_656" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hamsa" /></template>
<style>
.a4q2dhbok {
  stop-color: var(--svg-color--efe1ff, #EFE1FF);
}

.aq6uxabqk {
  stop-color: var(--svg-color--ddb3ff, #DDB3FF);
  stop-opacity: 0;
}

.b2qjdyb8h {
  fill-rule: evenodd;
  d: path("M15.946 16h.108c2.609 0 4.597 1.803 5.583 3.33c.49.759.485 1.736-.02 2.484C20.622 23.282 18.644 25 16.053 25h-.108c-2.59 0-4.57-1.718-5.562-3.186a2.25 2.25 0 0 1-.02-2.484c.985-1.527 2.973-3.33 5.582-3.33");
}

.cbxcmk3zh {
  fill: var(--svg-color--4e91e7, #4E91E7);
  fill-rule: evenodd;
  d: path("M13.15 4.06V14a.1.1 0 0 0 .2 0V3.593q-.12.224-.2.468m5.5-.468V14a.1.1 0 0 0 .2 0V4.06a3 3 0 0 0-.2-.468");
}

.cjhkubc7d {
  stop-color: var(--svg-color--26385d, #26385D);
}

.d7xnj-bfo {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16 16.125h.054c2.55 0 4.504 1.764 5.478 3.273c.463.717.458 1.64-.02 2.346c-.98 1.449-2.924 3.131-5.458 3.131h-.108c-2.534 0-4.479-1.682-5.459-3.131a2.13 2.13 0 0 1-.019-2.346c.974-1.509 2.928-3.273 5.478-3.273z");
}

.dju9_srsu {
  stop-color: var(--svg-color--267deb, #267DEB);
  stop-opacity: 0.6;
}

.dk7y_c03w {
  stop-color: var(--svg-color--29385c, #29385C);
  stop-opacity: 0;
}

.dml5iubiz {
  d: path("M23 12.016V7a3 3 0 0 0-4.105-2.79a3.001 3.001 0 0 0-5.79 0A3 3 0 0 0 9 7v5.016c-2.042 0-3.68.854-4.764 1.725c-.725.583-.437 1.6.306 2.16C5.497 16.618 6 17.52 6 19v1c0 5.523 4.477 10 10 10s10-4.477 10-10v-1c0-1.48.503-2.382 1.458-3.1c.744-.558 1.032-1.576.306-2.16c-1.084-.87-2.722-1.724-4.764-1.724");
}

.fbtwhkbxw {
  stop-color: var(--svg-color--57acff, #57ACFF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gc3qxm91j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M25.5 17.5c.037.5-.017 1.892-.195 3.5C25 23.74 24 25 23 26");
}

.gcdycdcli {
  stop-color: var(--svg-color--70c7ff, #70C7FF);
}

.gr17p0bzf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m22.276 12l.724.811c1 .063 3.3.489 4.5 1.689");
}

.gy8ye8bze {
  stop-color: var(--svg-color--3e7dfb, #3E7DFB);
  stop-opacity: 0;
}

.iddo2zb9v {
  stop-color: var(--svg-color--58bdfe, #58BDFE);
}

.ij89jwu6o {
  stop-color: var(--svg-color--6dc7ff, #6DC7FF);
  stop-opacity: 0.8;
}

.jjevi1bao {
  stop-color: var(--svg-color--e0bcff, #E0BCFF);
}

.jy2gxibjv {
  stop-color: var(--svg-color--5ac6ff, #5AC6FF);
}

.k7pi0gbkg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.5 9.5V14l.5.698");
}

.la0ek6bdw {
  stop-color: var(--svg-color--492464, #492464);
  stop-opacity: 0;
}

.lb578xbgf {
  stop-color: var(--svg-color--70c7ff, #70C7FF);
  stop-opacity: 0;
}

.my7q2k7tl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.5 9.5V14l.5.698");
}

.nvem8qkfb {
  stop-color: var(--svg-color--deb4ff, #DEB4FF);
}

.of078394p {
  stop-color: var(--svg-color--492365, #492365);
}

.ppq8wb3wy {
  d: path("M18 20.5a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.q1g6-4b4a {
  fill: var(--svg-color--1f7ed1, #1F7ED1);
  fill-rule: evenodd;
  d: path("M12.75 4.094V14a.5.5 0 0 0 1 0V3.016a3 3 0 0 0-.645 1.194a3 3 0 0 0-.355-.116");
}

.qlijq8b2k {
  fill: var(--svg-color--352b3f, #352B3F);
  d: path("M18 20.5a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.r_sm0j9fy {
  stop-color: var(--svg-color--7fbdff, #7FBDFF);
  stop-opacity: 0;
}

.rkbgt5mew {
  stop-color: var(--svg-color--5499ff, #5499FF);
}

.so6bj_boq {
  stop-color: var(--svg-color--71d6ff, #71D6FF);
  stop-opacity: 0.8;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.u1evcdc0f {
  stop-color: var(--svg-color--70c7ff, #70C7FF);
  stop-opacity: 0.6;
}

.uz242denu {
  stop-color: var(--svg-color--f5e9ff, #F5E9FF);
}

.x4i5ofbwo {
  stop-color: var(--svg-color--c8a1fc, #C8A1FC);
}

.xaywjsqib {
  stop-color: var(--svg-color--3a78fe, #3A78FE);
}

.xg-2dhobs {
  fill: var(--svg-color--1f7ed1, #1F7ED1);
  fill-rule: evenodd;
  d: path("M18.25 3.016V14a.5.5 0 0 0 1 0V4.095q-.183.046-.355.115a3 3 0 0 0-.645-1.194");
}

.xxps_acjr {
  cx: 16px;
  cy: 20.5px;
  r: 3.5px;
}

.yd5es9fiw {
  stop-color: var(--svg-color--5f5a65, #5F5A65);
}

.ysb6dzbhm {
  stop-color: var(--svg-color--71d6ff, #71D6FF);
}

.z3n19ac1i {
  stop-color: var(--svg-color--605a66, #605A66);
  stop-opacity: 0;
}

.zdy90zbsj {
  stop-color: var(--svg-color--467eff, #467EFF);
}

</style>
