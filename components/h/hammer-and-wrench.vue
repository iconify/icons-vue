<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifbXKfe)"><path class="pm7om36cp"/><path fill="url(#iwlgWYc)" class="hp6f5kufy"/><path fill="url(#iY6SVje)" class="hp6f5kufy"/></g><g filter="url(#itpwMCb)"><path fill="url(#i4Ht4th)" class="mps7rf9cd"/><path fill="url(#ib8WVid)" class="mps7rf9cd"/></g><g filter="url(#iCAcrTb)"><path class="o7inghb-w"/><path fill="url(#izhZAjc)" class="lh0xd0ziy"/><path fill="url(#iflsagc)" class="lh0xd0ziy"/><path fill="url(#iTwuqgc)" class="lh0xd0ziy"/><path fill="url(#iecpvOt)" class="lh0xd0ziy"/></g><path fill="url(#iVvGbEb)" class="hp6f5kufy"/><g filter="url(#icpt8oc)"><path class="z9ep4-b-o"/></g><path fill="url(#ilWrwWb)" class="xu0ubhbvg"/><path fill="url(#iFqSx2w)" class="xu0ubhbvg"/><path fill="url(#iOhLLgl)" class="xu0ubhbvg"/><g filter="url(#ip7aBPM)"><path fill="url(#iXkPkJb)" transform="rotate(-45 6.621 11.927)" class="wctw1os0l"/><path fill="url(#i7TtvJd)" transform="rotate(-45 6.621 11.927)" class="wctw1os0l"/></g><g filter="url(#iniuk7H)"><path fill="url(#ixmoAZc)" class="dkd-jst7r"/><path fill="url(#iQDrIJn)" class="dkd-jst7r"/></g><path fill="url(#ime8kze)" transform="rotate(45 19.463 9.746)" class="bb_cfnvza"/><path fill="url(#i8d7Cke)" transform="rotate(45 19.463 9.746)" class="bb_cfnvza"/><path fill="url(#iADaxUd)" transform="rotate(45 19.463 9.746)" class="bb_cfnvza"/><path fill="url(#iMKLM7b)" transform="rotate(45 19.463 9.746)" class="bb_cfnvza"/><path fill="url(#iNS1S0S)" class="h26up6bfv"/><path fill="url(#iI1Z0se)" class="h26up6bfv"/><path fill="url(#iTtyE8f)" class="h26up6bfv"/><path fill="url(#iM2YPlb)" class="hrnr45b7u"/><path fill="url(#iJXYyje)" class="hrnr45b7u"/><defs><radialGradient id="ib8WVid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78126 -1.28124 1.64014 -2.28022 28.355 25.943)" gradientUnits="userSpaceOnUse"><stop class="m627u5g2x"/><stop offset="1" class="c-_9o7psl"/></radialGradient><radialGradient id="izhZAjc" cx="0" cy="0" r="1" gradientTransform="matrix(2.15627 -2.20266 2.20324 2.15683 5.137 15.87)" gradientUnits="userSpaceOnUse"><stop class="q7_ufs0ub"/><stop offset="1" class="m09cfzbmf"/></radialGradient><radialGradient id="iflsagc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.332 19.577 2.572)scale(4.8875 11.3328)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="qh-rxvbzu"/><stop offset=".776" class="ap8oqin0f"/></radialGradient><radialGradient id="iTwuqgc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 1.4375 -4.40954 -3.83437 6.23 13.224)" gradientUnits="userSpaceOnUse"><stop class="y5y7fdbtn"/><stop offset="1" class="na31ucalb"/></radialGradient><radialGradient id="iecpvOt" cx="0" cy="0" r="1" gradientTransform="rotate(-177.818 3.833 6.448)scale(6.56726 8.47243)" gradientUnits="userSpaceOnUse"><stop offset=".547" class="n1pmm6bhx"/><stop offset="1" class="kxkwn6bek"/></radialGradient><radialGradient id="iVvGbEb" cx="0" cy="0" r="1" gradientTransform="rotate(-132.466 11.531 4.405)scale(2.75103 21.6672)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="hy0vsds1u"/><stop offset="1" class="z8w81op9n"/></radialGradient><radialGradient id="iFqSx2w" cx="0" cy="0" r="1" gradientTransform="rotate(136.759 7.216 4.733)scale(1.67855 .33786)" gradientUnits="userSpaceOnUse"><stop class="h0gm66blm"/><stop offset="1" class="xx6311btn"/></radialGradient><radialGradient id="iOhLLgl" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49836 2.39699 -1.91507 -2.795 15.456 8.29)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="a9zy8cc4w"/><stop offset="1" class="fasfrhbko"/></radialGradient><radialGradient id="iQDrIJn" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21876 4.03125 -2.7613 -2.88975 29.506 6.32)" gradientUnits="userSpaceOnUse"><stop class="di3zo2b_y"/><stop offset="1" class="rz13jtbjh"/></radialGradient><radialGradient id="iMKLM7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.13258 -1.12695 2.49429 -.29345 22.175 22.54)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="hf6m7vpqt"/><stop offset="1" class="ew83zqbfg"/></radialGradient><radialGradient id="iNS1S0S" cx="0" cy="0" r="1" gradientTransform="matrix(-6.53123 -1.96879 2.30664 -7.65204 10.694 24.04)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="j4t-9ebmo"/><stop offset="1" class="tu65cbb7h"/></radialGradient><radialGradient id="iI1Z0se" cx="0" cy="0" r="1" gradientTransform="matrix(.09375 7.1875 -9.91348 .1293 8.85 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="nyv783e3i"/><stop offset=".945" class="au2-4ovfo"/></radialGradient><radialGradient id="iTtyE8f" cx="0" cy="0" r="1" gradientTransform="rotate(133.719 1.804 13.212)scale(3.70771 3.64672)" gradientUnits="userSpaceOnUse"><stop class="p4jl5ccxc"/><stop offset="1" class="qh7wfse2l"/></radialGradient><radialGradient id="iM2YPlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.625 -6.09375 8.4139 -.86296 23.881 13.29)" gradientUnits="userSpaceOnUse"><stop offset=".012" class="b3dpq7bps"/><stop offset="1" class="xrc7-fbpf"/></radialGradient><radialGradient id="iJXYyje" cx="0" cy="0" r="1" gradientTransform="matrix(-7.8125 -2.71877 2.88538 -8.29127 26.756 9.04)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="bn271xbka"/><stop offset=".956" class="ekqws7woy"/></radialGradient><linearGradient id="iwlgWYc" x1="30.199" x2="25.855" y1="27.224" y2="22.88" gradientUnits="userSpaceOnUse"><stop offset=".065" class="kgv3yxbue"/><stop offset="1" class="e31_17snh"/></linearGradient><linearGradient id="iY6SVje" x1="17.574" x2="21.136" y1="20.943" y2="17.255" gradientUnits="userSpaceOnUse"><stop offset=".058" class="m1mq_hbaa"/><stop offset="1" class="g8jajs8rt"/></linearGradient><linearGradient id="i4Ht4th" x1="17.543" x2="26.73" y1="16.661" y2="25.693" gradientUnits="userSpaceOnUse"><stop class="i8baiqb6e"/><stop offset="1" class="cb2eqtb2u"/></linearGradient><linearGradient id="ilWrwWb" x1="14.096" x2="13.998" y1="2.622" y2="3.853" gradientUnits="userSpaceOnUse"><stop class="z5j-t0xuy"/><stop offset="1" class="ev28ay-9m"/></linearGradient><linearGradient id="iXkPkJb" x1="13.803" x2="6.552" y1="14.924" y2="15.356" gradientUnits="userSpaceOnUse"><stop class="fddknwbru"/><stop offset="1" class="zd_66jbuq"/></linearGradient><linearGradient id="i7TtvJd" x1="10.234" x2="10.256" y1="11.927" y2="13.208" gradientUnits="userSpaceOnUse"><stop offset=".111" class="o2vd8exeu"/><stop offset="1" class="ozlqh76_i"/></linearGradient><linearGradient id="ixmoAZc" x1="13.194" x2="18.444" y1="12.883" y2="19.07" gradientUnits="userSpaceOnUse"><stop class="lse0qd2kj"/><stop offset="1" class="ubn8dccbe"/></linearGradient><linearGradient id="ime8kze" x1="18.375" x2="22.323" y1="16.706" y2="16.827" gradientUnits="userSpaceOnUse"><stop class="utab66byq"/><stop offset="1" class="d8n4_ibse"/></linearGradient><linearGradient id="i8d7Cke" x1="21.711" x2="21.675" y1="9.424" y2="10.267" gradientUnits="userSpaceOnUse"><stop offset=".275" class="litt7qsqf"/><stop offset="1" class="y2qek39ff"/></linearGradient><linearGradient id="iADaxUd" x1="24.827" x2="21.44" y1="16.062" y2="15.955" gradientUnits="userSpaceOnUse"><stop class="qxh3z3vnu"/><stop offset="1" class="l3q0v5bub"/></linearGradient><filter id="ifbXKfe" width="21.374" height="21.524" x="7.742" y="7.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.384314 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23916"/></filter><filter id="itpwMCb" width="18.428" height="18.428" x="10.63" y="8.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23916" stdDeviation=".5"/></filter><filter id="iCAcrTb" width="7.773" height="7.771" x="1.326" y="10.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.541176 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23916"/></filter><filter id="icpt8oc" width="12.121" height="13.21" x="4.424" y="2.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.52549 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23916"/></filter><filter id="ip7aBPM" width="10.134" height="10.134" x="5.621" y="5.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23916" stdDeviation=".5"/></filter><filter id="iniuk7H" width="25.9" height="25.853" x="3.415" y="3.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.686275 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23916"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.854902 0 0 0 0 0.894118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23916" result="effect2_innerShadow_18_23916"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hammer-and-wrench" /></template>
<style>
.a9zy8cc4w {
  stop-color: var(--svg-color--eceaf4, #ECEAF4);
}

.ap8oqin0f {
  stop-color: var(--svg-color--8c889a, #8C889A);
}

.au2-4ovfo {
  stop-color: var(--svg-color--cba8e2, #CBA8E2);
}

.b3dpq7bps {
  stop-color: var(--svg-color--c3a9d9, #C3A9D9);
}

.bb_cfnvza {
  d: path("M19.463 9.746h4.464v12.927h-4.464z");
}

.bn271xbka {
  stop-color: var(--svg-color--afa6bb, #AFA6BB);
  stop-opacity: 0;
}

.c-_9o7psl {
  stop-color: var(--svg-color--9b7775, #9B7775);
  stop-opacity: 0;
}

.cb2eqtb2u {
  stop-color: var(--svg-color--8f6969, #8F6969);
}

.d8n4_ibse {
  stop-color: var(--svg-color--d2ced9, #D2CED9);
  stop-opacity: 0;
}

.di3zo2b_y {
  stop-color: var(--svg-color--e1dfe7, #E1DFE7);
}

.dkd-jst7r {
  d: path("M25.388 3.439c.342.09.425.511.175.761L23.14 6.624a.75.75 0 0 0 0 1.06l1.548 1.55a.75.75 0 0 0 1.061 0L28.182 6.8c.249-.25.67-.167.761.173a5.008 5.008 0 0 1-6.094 6.156a.65.65 0 0 0-.622.157l-8.589 8.589a.65.65 0 0 0-.158.617q.15.59.151 1.226a5.008 5.008 0 0 1-6.289 4.842c-.341-.09-.425-.511-.175-.761l2.424-2.424a.75.75 0 0 0 0-1.06l-1.549-1.55a.75.75 0 0 0-1.06 0L4.549 25.2c-.25.25-.67.167-.761-.173a5.014 5.014 0 0 1 6.083-6.158c.22.056.459.003.62-.158l8.598-8.598a.65.65 0 0 0 .16-.616a5.008 5.008 0 0 1 6.14-6.057");
}

.e31_17snh {
  stop-color: var(--svg-color--7f494f, #7F494F);
  stop-opacity: 0;
}

.ekqws7woy {
  stop-color: var(--svg-color--9c98a3, #9C98A3);
}

.ev28ay-9m {
  stop-color: var(--svg-color--ccccd3, #CCCCD3);
  stop-opacity: 0;
}

.ew83zqbfg {
  stop-color: var(--svg-color--d3ceda, #D3CEDA);
  stop-opacity: 0;
}

.fasfrhbko {
  stop-color: var(--svg-color--eceaf4, #ECEAF4);
  stop-opacity: 0;
}

.fddknwbru {
  stop-color: var(--svg-color--edeaf7, #EDEAF7);
}

.ft5dv1b6b {
  fill: none;
}

.g8jajs8rt {
  stop-color: var(--svg-color--7c425a, #7C425A);
  stop-opacity: 0;
}

.h0gm66blm {
  stop-color: var(--svg-color--dfdde8, #DFDDE8);
}

.h26up6bfv {
  d: path("M7.167 27.8c-.25.25-.166.671.175.761q.616.164 1.281.166a5.008 5.008 0 1 0-4.835-3.7c.092.34.512.421.761.172l2.433-2.433a.75.75 0 0 1 1.06 0l1.55 1.55a.75.75 0 0 1 0 1.06z");
}

.hf6m7vpqt {
  stop-color: var(--svg-color--e0dbe9, #E0DBE9);
}

.hp6f5kufy {
  d: path("M11.894 7.997L28.255 24.36a2.936 2.936 0 1 1-4.152 4.152L7.742 12.15z");
}

.hrnr45b7u {
  d: path("M25.388 3.439c.342.09.425.511.175.761L23.14 6.624a.75.75 0 0 0 0 1.06l1.548 1.55a.75.75 0 0 0 1.061 0L28.182 6.8c.249-.25.67-.167.761.173a5.008 5.008 0 0 1-5.87 6.208a.9.9 0 0 1-.45-.252l-3.164-3.164a.9.9 0 0 1-.252-.45a5.008 5.008 0 0 1 6.182-5.877");
}

.hy0vsds1u {
  stop-color: var(--svg-color--563235, #563235);
}

.i8baiqb6e {
  stop-color: var(--svg-color--a77975, #A77975);
}

.j4t-9ebmo {
  stop-color: var(--svg-color--9d99a6, #9D99A6);
  stop-opacity: 0;
}

.kgv3yxbue {
  stop-color: var(--svg-color--7f494f, #7F494F);
}

.kxkwn6bek {
  stop-color: var(--svg-color--8f8c98, #8F8C98);
}

.l3q0v5bub {
  stop-color: var(--svg-color--d3c1e6, #D3C1E6);
  stop-opacity: 0;
}

.lh0xd0ziy {
  d: path("M2.433 10.818c.714-.714 1.571-.508 2.494-.05c.177.087.335.206.474.345l2.843 2.844c.1.1.19.208.26.33c.569.981.605 1.964.03 2.538L7.43 17.9a.25.25 0 0 1-.353 0l-5.678-5.68a.25.25 0 0 1 0-.354z");
}

.litt7qsqf {
  stop-color: var(--svg-color--c8b4d9, #C8B4D9);
}

.lse0qd2kj {
  stop-color: var(--svg-color--bab6c1, #BAB6C1);
}

.m09cfzbmf {
  stop-color: var(--svg-color--cabfdd, #CABFDD);
  stop-opacity: 0;
}

.m1mq_hbaa {
  stop-color: var(--svg-color--733464, #733464);
}

.m627u5g2x {
  stop-color: var(--svg-color--9b7775, #9B7775);
}

.mps7rf9cd {
  d: path("M11.855 11.255a.766.766 0 0 1 1.082-1.083l14.897 14.897a.766.766 0 0 1-1.083 1.082z");
}

.n1pmm6bhx {
  stop-color: var(--svg-color--8f8c98, #8F8C98);
  stop-opacity: 0;
}

.na31ucalb {
  stop-color: var(--svg-color--cac1dc, #CAC1DC);
  stop-opacity: 0;
}

.nyv783e3i {
  stop-color: var(--svg-color--e0d0ef, #E0D0EF);
  stop-opacity: 0;
}

.o2vd8exeu {
  stop-color: var(--svg-color--b2adc0, #B2ADC0);
}

.o7inghb-w {
  fill: var(--svg-color--ada9b9, #ADA9B9);
  d: path("M2.433 10.818c.714-.714 1.571-.508 2.494-.05c.177.087.335.206.474.345l2.843 2.844c.1.1.19.208.26.33c.569.981.605 1.964.03 2.538L7.43 17.9a.25.25 0 0 1-.353 0l-5.678-5.68a.25.25 0 0 1 0-.354z");
}

.ozlqh76_i {
  stop-color: var(--svg-color--b2adc0, #B2ADC0);
  stop-opacity: 0;
}

.p4jl5ccxc {
  stop-color: var(--svg-color--e9e3f3, #E9E3F3);
}

.pm7om36cp {
  fill: var(--svg-color--a3796e, #A3796E);
  d: path("M11.894 7.997L28.255 24.36a2.936 2.936 0 1 1-4.152 4.152L7.742 12.15z");
}

.q7_ufs0ub {
  stop-color: var(--svg-color--cabfdd, #CABFDD);
}

.qh-rxvbzu {
  stop-color: var(--svg-color--bbb9c3, #BBB9C3);
  stop-opacity: 0;
}

.qh7wfse2l {
  stop-color: var(--svg-color--e9e3f3, #E9E3F3);
  stop-opacity: 0;
}

.qxh3z3vnu {
  stop-color: var(--svg-color--d3c1e6, #D3C1E6);
}

.rz13jtbjh {
  stop-color: var(--svg-color--e1dfe7, #E1DFE7);
  stop-opacity: 0;
}

.tu65cbb7h {
  stop-color: var(--svg-color--9d99a6, #9D99A6);
}

.ubn8dccbe {
  stop-color: var(--svg-color--e0dbe7, #E0DBE7);
}

.utab66byq {
  stop-color: var(--svg-color--9e9aa4, #9E9AA4);
}

.wctw1os0l {
  d: path("M6.621 11.927h7.225v4.278H6.621z");
}

.xrc7-fbpf {
  stop-color: var(--svg-color--c3a9d9, #C3A9D9);
  stop-opacity: 0;
}

.xu0ubhbvg {
  d: path("M12.853 6.704a.5.5 0 0 0 0 .706l2.141 2.14a.4.4 0 0 1 0 .566L9.85 15.261a.4.4 0 0 1-.566 0l-4.64-4.64a.75.75 0 0 1 0-1.06L11.2 3.004a2 2 0 0 1 1.578-.579l3.149.26a.4.4 0 0 1 .25.68z");
}

.xx6311btn {
  stop-color: var(--svg-color--ccc9d6, #CCC9D6);
  stop-opacity: 0;
}

.y2qek39ff {
  stop-color: var(--svg-color--c8b4d9, #C8B4D9);
  stop-opacity: 0;
}

.y5y7fdbtn {
  stop-color: var(--svg-color--ded9ea, #DED9EA);
}

.z5j-t0xuy {
  stop-color: var(--svg-color--ccccd3, #CCCCD3);
}

.z8w81op9n {
  stop-color: var(--svg-color--563235, #563235);
  stop-opacity: 0;
}

.z9ep4-b-o {
  fill: var(--svg-color--cac3da, #CAC3DA);
  d: path("M12.853 6.704a.5.5 0 0 0 0 .706l2.141 2.14a.4.4 0 0 1 0 .566L9.85 15.261a.4.4 0 0 1-.566 0l-4.64-4.64a.75.75 0 0 1 0-1.06L11.2 3.004a2 2 0 0 1 1.578-.579l3.149.26a.4.4 0 0 1 .25.68z");
}

.zd_66jbuq {
  stop-color: var(--svg-color--a89abe, #A89ABE);
}

</style>
