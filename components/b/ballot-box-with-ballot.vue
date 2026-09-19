<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iTe1zTb)"><path fill="url(#iDe5xKc)" class="ykx-bmbyx"/><path fill="url(#itUJSae)" class="ykx-bmbyx"/></g><g filter="url(#iAnwexe)"><path fill="url(#iifWxvc)" class="ofii1-lwp"/><path fill="url(#iia0Vzc)" class="ofii1-lwp"/></g><rect fill="url(#i8dkjgc)" class="drrqfuwli"/><g filter="url(#iH2OIrA)"><rect fill="url(#iu39HAb)" class="cvhi5ffqq"/></g><g filter="url(#ijUK4Nb)"><path fill="url(#iSIiZ8d)" class="sp071jbzh"/></g><path fill="url(#iMZ6bwd)" class="sp071jbzh"/><g filter="url(#iGfHwTc)"><path fill="url(#i2bTeEc)" clip-rule="evenodd" class="hrid9t_dx"/></g><g filter="url(#iP17G6b)"><path class="lslbwwbil"/></g><g filter="url(#iODmThd)"><path stroke="url(#iXk0l3c)" class="vbxwffb1g"/></g><defs><linearGradient id="iDe5xKc" x1="15.511" x2="15.511" y1="6.091" y2="15.02" gradientUnits="userSpaceOnUse"><stop class="faaro1q3u"/><stop offset="1" class="skjinsnoi"/></linearGradient><linearGradient id="iifWxvc" x1="15.511" x2="15.511" y1="15.02" y2="29.989" gradientUnits="userSpaceOnUse"><stop class="q7kcjdbmc"/><stop offset="1" class="krobi38hj"/></linearGradient><linearGradient id="iia0Vzc" x1="17.679" x2="17.679" y1="29.989" y2="27.356" gradientUnits="userSpaceOnUse"><stop class="ia6lawbtn"/><stop offset="1" class="d0mq7x25f"/></linearGradient><linearGradient id="i8dkjgc" x1="24.98" x2="24.98" y1="16.981" y2="25.966" gradientUnits="userSpaceOnUse"><stop class="r55-5svbp"/><stop offset="1" class="npbo96blx"/></linearGradient><linearGradient id="iu39HAb" x1="21.844" x2="9.18" y1="9.919" y2="9.919" gradientUnits="userSpaceOnUse"><stop class="l9inlsapf"/><stop offset="1" class="uqdln67bc"/></linearGradient><linearGradient id="iSIiZ8d" x1="20.164" x2="13.945" y1="2.481" y2="9.981" gradientUnits="userSpaceOnUse"><stop class="m4a2mqbdr"/><stop offset="1" class="j8gx53l_g"/></linearGradient><linearGradient id="iMZ6bwd" x1="16.793" x2="16.793" y1="12.2" y2="10.638" gradientUnits="userSpaceOnUse"><stop class="nac8h5bmb"/><stop offset="1" class="sz_0psbmu"/></linearGradient><linearGradient id="iXk0l3c" x1="14.136" x2="18.168" y1="9.669" y2="5.153" gradientUnits="userSpaceOnUse"><stop class="n_acrx86y"/><stop offset="1" class="vdf1tebgo"/></linearGradient><filter id="iTe1zTb" width="26.038" height="10.292" x="2.443" y="6.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.760784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22220"/></filter><filter id="iAnwexe" width="26.038" height="14.969" x="2.443" y="15.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.760784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22220"/></filter><filter id="iH2OIrA" width="12.664" height="3.484" x="9.18" y="8.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.156863 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22220"/></filter><filter id="ijUK4Nb" width="10.219" height="9.959" x="10.377" y="2.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.831373 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22220"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.960784 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22220" result="effect2_innerShadow_18_22220"/></filter><filter id="iGfHwTc" width="7.42" height="6.449" x="11.765" y="4.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.666667 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22220"/></filter><filter id="iP17G6b" width="2.603" height="2.994" x="11.937" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22220" stdDeviation=".15"/></filter><filter id="iODmThd" width="5.041" height="5.869" x="13.687" y="4.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22220" stdDeviation=".15"/></filter><radialGradient id="itUJSae" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.125 -19.1396 0 12.636 4.825)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="cnpxd95yf"/><stop offset="1" class="f_-q68bif"/></radialGradient><radialGradient id="i2bTeEc" cx="0" cy="0" r="1" gradientTransform="rotate(137.517 8.582 5.933)scale(8.05111 9.29298)" gradientUnits="userSpaceOnUse"><stop class="o0rxoebbn"/><stop offset="1" class="jwmfqnb8x"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ballot-box-with-ballot" /></template>
<style>
.cnpxd95yf {
  stop-color: var(--svg-color--737275, #737275);
}

.cvhi5ffqq {
  width: 12.664px;
  height: 2.484px;
  x: 9.18px;
  y: 9.434px;
  rx: 1.242px;
}

.d0mq7x25f {
  stop-color: var(--svg-color--82778d, #82778D);
  stop-opacity: 0;
}

.drrqfuwli {
  width: 3px;
  height: 8.984px;
  x: 23.48px;
  y: 16.981px;
  rx: 1.5px;
}

.f_-q68bif {
  stop-color: var(--svg-color--8d8c8e, #8D8C8E);
  stop-opacity: 0;
}

.faaro1q3u {
  stop-color: var(--svg-color--959596, #959596);
}

.ft5dv1b6b {
  fill: none;
}

.hrid9t_dx {
  fill-rule: evenodd;
  d: path("M18.973 4.179a.6.6 0 0 1 .071.846L14.8 10.052a.8.8 0 0 1-1.249-.032l-1.513-1.997a.6.6 0 1 1 .957-.725l1.21 1.598l3.923-4.646a.6.6 0 0 1 .846-.071");
}

.ia6lawbtn {
  stop-color: var(--svg-color--716081, #716081);
}

.j8gx53l_g {
  stop-color: var(--svg-color--d4cedd, #D4CEDD);
}

.jwmfqnb8x {
  stop-color: var(--svg-color--2dad67, #2DAD67);
}

.krobi38hj {
  stop-color: var(--svg-color--8d8794, #8D8794);
}

.l9inlsapf {
  stop-color: var(--svg-color--554165, #554165);
}

.lslbwwbil {
  stroke: var(--svg-color--4dbd7c, #4DBD7C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m12.387 7.731l1.703 2.094");
}

.m4a2mqbdr {
  stop-color: var(--svg-color--ede7f5, #EDE7F5);
}

.n_acrx86y {
  stop-color: var(--svg-color--4dbd7c, #4DBD7C);
}

.nac8h5bmb {
  stop-color: var(--svg-color--ccc6d4, #CCC6D4);
}

.npbo96blx {
  stop-color: var(--svg-color--d1ccd6, #D1CCD6);
  stop-opacity: 0;
}

.o0rxoebbn {
  stop-color: var(--svg-color--26ad60, #26AD60);
}

.ofii1-lwp {
  d: path("M2.543 15.02H28.48v12.97a2 2 0 0 1-2 2H4.543a2 2 0 0 1-2-2z");
}

.q7kcjdbmc {
  stop-color: var(--svg-color--9d99a1, #9D99A1);
}

.r55-5svbp {
  stop-color: var(--svg-color--d1ccd6, #D1CCD6);
}

.skjinsnoi {
  stop-color: var(--svg-color--afadb2, #AFADB2);
}

.sp071jbzh {
  d: path("M10.527 3.36a1.3 1.3 0 0 1 1.3-1.3h7.369a1.3 1.3 0 0 1 1.3 1.3v8.559h-9.969z");
}

.sz_0psbmu {
  stop-color: var(--svg-color--ccc6d4, #CCC6D4);
  stop-opacity: 0;
}

.uqdln67bc {
  stop-color: var(--svg-color--402c50, #402C50);
}

.vbxwffb1g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m14.137 9.888l4.14-4.97");
}

.vdf1tebgo {
  stop-color: var(--svg-color--4dbd7c, #4DBD7C);
  stop-opacity: 0;
}

.ykx-bmbyx {
  d: path("M2.543 16.383H28.48V8.09a2 2 0 0 0-2-2H4.543a2 2 0 0 0-2 2z");
}

</style>
