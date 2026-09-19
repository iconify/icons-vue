<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i6gbN3b)" class="vj5ghtafm"/><path fill="url(#iYVov3t)" class="vj5ghtafm"/><path fill="url(#iJ9wSme)" class="vj5ghtafm"/><g filter="url(#iZNqCsb)"><path stroke="url(#ip3P50b)" class="h0rmxe_4m"/></g><path fill="url(#i3a9Tab)" class="m_ua78btu"/><path fill="url(#i5AQ91b)" class="m_ua78btu"/><path fill="url(#i7EDiOd)" class="m_ua78btu"/><path fill="url(#iLnUshd)" class="m_ua78btu"/><path fill="url(#ixOdene)" class="l0dbtlbva"/><path fill="url(#iPNHFOc)" class="sacfwgwyv"/><path class="yrhnwfbgx"/><path fill="url(#i4ksfKd)" class="u--irczuc"/><g filter="url(#iRRqQYd)"><path class="v2510fb5y"/><path fill="url(#irCCbbe)" class="dn1-3tb_i"/></g><g filter="url(#imFprsd)"><path fill="url(#ije1D7c)" class="bh1ozr_5t"/><path fill="url(#idvD7ic)" class="bh1ozr_5t"/><path fill="url(#ijMZzFd)" class="bh1ozr_5t"/></g><path class="hky1sqdvl"/><path fill="url(#iW6Ue1d)" class="c77gj-70g"/><path fill="url(#iCx3Mud)" class="c77gj-70g"/><g filter="url(#i9M3Lxe)"><path fill="url(#iMUBq9b)" class="y3b8pmbvt"/><path fill="url(#iD43Lbc)" class="y3b8pmbvt"/></g><g filter="url(#i5fN68c)"><path fill="url(#iLr2BIe)" class="o4dwrkj5n"/></g><path fill="url(#ikgBKRc)" class="dg-j6up8d"/><path fill="url(#iFyY0Fb)" class="dg-j6up8d"/><path fill="url(#iHjGlBe)" class="dg-j6up8d"/><g filter="url(#iwgBOxd)"><path fill="url(#iHCHEVE)" class="zpp74p80k"/><path fill="url(#iMuZIWU)" class="zpp74p80k"/></g><g filter="url(#iTMT5rb)"><path class="xvxw1vg8l"/></g><path fill="url(#iALX2sb)" class="z6u-ipbwk"/><path fill="url(#ijefUCb)" class="z6u-ipbwk"/><path fill="url(#iqTMtBd)" class="z6u-ipbwk"/><path fill="url(#ipmSQFe)" class="qufmd3b6t"/><path fill="url(#imCnyYc)" class="qufmd3b6t"/><path fill="url(#i2Ulywd)" class="qufmd3b6t"/><g filter="url(#iTvx0pd)"><path fill="url(#i57DSsH)" class="oxfz6d9oi"/></g><path fill="url(#i0Eyowe)" class="liduz3bts"/><path fill="url(#iiOEkOd)" class="liduz3bts"/><g filter="url(#i5mVkvb)"><path stroke="url(#iI8kayb)" class="h1gug-ivs"/></g><g filter="url(#iShHh3d)"><path class="gpds1nbxd"/></g><g filter="url(#irUVThb)"><path fill="url(#iLXSWVc)" class="mvdsgdb2k"/></g><g filter="url(#iI8TFUb)"><path class="rynhwmbia"/></g><defs><radialGradient id="iJ9wSme" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.37461 .951 0 16.76 11.38)" gradientUnits="userSpaceOnUse"><stop class="x0sqhq5gl"/><stop offset="1" class="f1qgipbfl"/></radialGradient><radialGradient id="i5AQ91b" cx="0" cy="0" r="1" gradientTransform="rotate(-148.333 3.765 .657)scale(.98217 .82731)" gradientUnits="userSpaceOnUse"><stop class="s_n_m-bfl"/><stop offset="1" class="ysdtaebqs"/></radialGradient><radialGradient id="i7EDiOd" cx="0" cy="0" r="1" gradientTransform="rotate(-56.547 6.017 -3.53)scale(1.3507 1.80299)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="s4nw2331q"/><stop offset=".955" class="yfv4p3bng"/></radialGradient><radialGradient id="ixOdene" cx="0" cy="0" r="1" gradientTransform="rotate(156.801 5.052 3.21)scale(1.20115 2.39489)" gradientUnits="userSpaceOnUse"><stop class="wtc2g2hnp"/><stop offset="1" class="cysg0jfku"/></radialGradient><radialGradient id="iPNHFOc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.02 1.23921 -2.47078 -4.02753 13.099 6.76)" gradientUnits="userSpaceOnUse"><stop class="cc2sislzy"/><stop offset="1" class="v_47q4bkc"/></radialGradient><radialGradient id="i4ksfKd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07288 1.3744 -1.78442 -2.69126 14.7 10.028)" gradientUnits="userSpaceOnUse"><stop class="av82fyaqe"/><stop offset="1" class="gpshpzbth"/></radialGradient><radialGradient id="irCCbbe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27477 0 0 -.27967 29.369 17.297)" gradientUnits="userSpaceOnUse"><stop class="u44kqtbwx"/><stop offset="1" class="g5usn5plv"/></radialGradient><radialGradient id="idvD7ic" cx="0" cy="0" r="1" gradientTransform="rotate(123.453 5.384 16.784)scale(3.04044 3.6627)" gradientUnits="userSpaceOnUse"><stop offset=".48" class="yfksle2hz"/><stop offset="1" class="o34az8bpc"/></radialGradient><radialGradient id="iW6Ue1d" cx="0" cy="0" r="1" gradientTransform="rotate(131.208 -.633 6.514)scale(1.528 2.26023)" gradientUnits="userSpaceOnUse"><stop class="ndup4sbve"/><stop offset="1" class="r9pb4-bwl"/></radialGradient><radialGradient id="ikgBKRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1998 4.62527 0 16.483 29.979)" gradientUnits="userSpaceOnUse"><stop class="q8_niobbz"/><stop offset=".651" class="lxsph8izk"/><stop offset=".787" class="mui-l1nqt"/></radialGradient><radialGradient id="iHjGlBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.61635 .93098 0 16.618 29.979)" gradientUnits="userSpaceOnUse"><stop class="plcltqw7z"/><stop offset="1" class="o7-4khdrm"/></radialGradient><radialGradient id="iHCHEVE" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70523 .63844 -1.88797 -7.99976 8.764 14.387)" gradientUnits="userSpaceOnUse"><stop class="qpp-a9byy"/><stop offset="1" class="hz_vkjb_m"/></radialGradient><radialGradient id="iMuZIWU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09084 -3.17505 1.15415 -.39653 7.844 15.47)" gradientUnits="userSpaceOnUse"><stop class="hfacq8bjg"/><stop offset="1" class="qghdw-mfe"/></radialGradient><radialGradient id="iqTMtBd" cx="0" cy="0" r="1" gradientTransform="rotate(-46.998 17.73 .61)scale(2.74198 1.29138)" gradientUnits="userSpaceOnUse"><stop offset=".199" class="cei_u6bpy"/><stop offset="1" class="a30p8ccsx"/></radialGradient><radialGradient id="ipmSQFe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8313 1.49498 -.40483 -.7667 7.464 3)" gradientUnits="userSpaceOnUse"><stop class="bvbkf70ft"/><stop offset="1" class="rfj-ib8no"/></radialGradient><radialGradient id="imCnyYc" cx="0" cy="0" r="1" gradientTransform="matrix(.80151 -1.8125 2.90463 1.28447 4.257 5.756)" gradientUnits="userSpaceOnUse"><stop class="x2pve9bbg"/><stop offset="1" class="usl7aub2n"/></radialGradient><radialGradient id="i2Ulywd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50072 1.42755 -1.03898 -2.54785 6.56 3.595)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="gt1ooh3ht"/><stop offset=".939" class="x8nbo2b_c"/></radialGradient><radialGradient id="i57DSsH" cx="0" cy="0" r="1" gradientTransform="rotate(157.218 1.869 4.477)scale(.67159 .71195)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="eyatc9bkt"/><stop offset="1" class="jpw18ybgx"/></radialGradient><linearGradient id="i6gbN3b" x1="16.059" x2="16.059" y1="2.487" y2="10.829" gradientUnits="userSpaceOnUse"><stop offset="0" class="yrtoc-01q"/><stop offset="1" class="rdz2y6i7v"/></linearGradient><linearGradient id="iYVov3t" x1="15.059" x2="16.059" y1="9.091" y2="9.091" gradientUnits="userSpaceOnUse"><stop class="g6ws9bbay"/><stop offset="1" class="dmy1vtjkw"/></linearGradient><linearGradient id="ip3P50b" x1="17.489" x2="17.489" y1=".602" y2="12.71" gradientUnits="userSpaceOnUse"><stop class="yqoyh4sxu"/><stop offset="1" class="ky-xwu1jz"/></linearGradient><linearGradient id="i3a9Tab" x1="6.059" x2="6.059" y1="2" y2="3.584" gradientUnits="userSpaceOnUse"><stop class="p6nuougos"/><stop offset="1" class="j2mrz2bol"/></linearGradient><linearGradient id="iLnUshd" x1="5.059" x2="5.398" y1="2.408" y2="2.408" gradientUnits="userSpaceOnUse"><stop class="n1sg4qn7s"/><stop offset=".102" class="awm1h0cdv"/></linearGradient><linearGradient id="ije1D7c" x1="21.059" x2="21.059" y1="20.582" y2="27.82" gradientUnits="userSpaceOnUse"><stop class="xjcwu0qkc"/><stop offset="1" class="kp9mht1av"/></linearGradient><linearGradient id="ijMZzFd" x1="24.303" x2="21.947" y1="25.349" y2="25.44" gradientUnits="userSpaceOnUse"><stop class="yfksle2hz"/><stop offset="1" class="o34az8bpc"/></linearGradient><linearGradient id="iCx3Mud" x1="2.675" x2="3.308" y1="12.584" y2="11.85" gradientUnits="userSpaceOnUse"><stop offset=".66" class="ocsaurbzd"/><stop offset="1" class="jbkz065vw"/></linearGradient><linearGradient id="iMUBq9b" x1="12.674" x2="8.416" y1="20.23" y2="28.979" gradientUnits="userSpaceOnUse"><stop class="r-046vbdt"/><stop offset="1" class="mbb6dqblh"/></linearGradient><linearGradient id="iD43Lbc" x1="12.212" x2="12.218" y1="19.623" y2="21.495" gradientUnits="userSpaceOnUse"><stop class="qokqd_59w"/><stop offset="1" class="o34az8bpc"/><stop offset="1" class="x8424g3as"/></linearGradient><linearGradient id="iLr2BIe" x1="7.538" x2="24.571" y1="7.706" y2="28.087" gradientUnits="userSpaceOnUse"><stop class="gqsygd64j"/><stop offset="1" class="h9q6r6b6n"/></linearGradient><linearGradient id="iFyY0Fb" x1="14.593" x2="15.876" y1="24.126" y2="24.126" gradientUnits="userSpaceOnUse"><stop class="nk0igufns"/><stop offset=".026" class="nk0igufns"/><stop offset="1" class="ct71bhbcp"/></linearGradient><linearGradient id="iALX2sb" x1="7.538" x2="6.601" y1="10.928" y2="9.771" gradientUnits="userSpaceOnUse"><stop class="h28721kom"/><stop offset="1" class="bl642fixv"/></linearGradient><linearGradient id="ijefUCb" x1="2.984" x2="4.381" y1="7.707" y2="8.225" gradientUnits="userSpaceOnUse"><stop offset=".218" class="z8kkkg14p"/><stop offset="1" class="fin5nsbrp"/></linearGradient><linearGradient id="i0Eyowe" x1="14.976" x2="20.476" y1="13.928" y2="13.928" gradientUnits="userSpaceOnUse"><stop class="t3mh7cjqe"/><stop offset="1" class="gp35dgmcz"/></linearGradient><linearGradient id="iiOEkOd" x1="16.054" x2="16.054" y1="10.834" y2="11.896" gradientUnits="userSpaceOnUse"><stop class="wcbbgdcqg"/><stop offset="1" class="gdphgvr2s"/></linearGradient><linearGradient id="iI8kayb" x1="17.329" x2="17.329" y1="19.565" y2="30.503" gradientUnits="userSpaceOnUse"><stop class="ofdaxzayt"/><stop offset="1" class="bcps22b7q"/></linearGradient><linearGradient id="iLXSWVc" x1="6.947" x2="6.947" y1="20.005" y2="19.045" gradientUnits="userSpaceOnUse"><stop offset=".009" class="on3gwmcnu"/><stop offset="1" class="z5lu5r0js"/></linearGradient><filter id="iZNqCsb" width="1.5" height="10.582" x="15.725" y="1.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8498" stdDeviation=".25"/></filter><filter id="iRRqQYd" width="7" height="10" x="23.449" y="11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.419608 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8498"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.172549 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8498" result="effect2_innerShadow_18_8498"/></filter><filter id="imFprsd" width="6" height="8.999" x="18.059" y="19.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.211765 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8498"/></filter><filter id="i9M3Lxe" width="6.509" height="9" x="6.813" y="19.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.211765 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8498"/></filter><filter id="i5fN68c" width="26.898" height="24.196" x="1.25" y="5.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.698039 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8498"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.32549 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8498" result="effect2_innerShadow_18_8498"/></filter><filter id="iwgBOxd" width="2.573" height="7.853" x="5.809" y="9.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8498" stdDeviation=".125"/></filter><filter id="iTMT5rb" width="8.041" height="10.77" x="2.078" y="1.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.760784 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8498"/></filter><filter id="iTvx0pd" width="1.46" height="1.46" x="4.279" y="7.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.470588 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_8498"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_8498" result="shape"/></filter><filter id="i5mVkvb" width="1.25" height="9.454" x="15.689" y="20.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8498" stdDeviation=".25"/></filter><filter id="iShHh3d" width="3.292" height="5.076" x="3.398" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8498" stdDeviation=".3"/></filter><filter id="irUVThb" width="3.422" height="1.386" x="4.535" y="18.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8498" stdDeviation=".125"/></filter><filter id="iI8TFUb" width="5.46" height="9.6" x="6.934" y="2.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8498" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:carousel-horse" /></template>
<style>
.a30p8ccsx {
  stop-color: var(--svg-color--985b4e, #985B4E);
  stop-opacity: 0;
}

.av82fyaqe {
  stop-color: var(--svg-color--866860, #866860);
}

.awm1h0cdv {
  stop-color: var(--svg-color--b69772, #B69772);
  stop-opacity: 0;
}

.bcps22b7q {
  stop-color: var(--svg-color--ffd05c, #FFD05C);
}

.bh1ozr_5t {
  d: path("M23.548 23.979h.51v-4h-6v1.32a2.68 2.68 0 0 0 2.49 2.673l-1.35 3.037c-.31.7-.02 1.57.69 1.86c.73.3 1.5-.05 1.8-.7z");
}

.bl642fixv {
  stop-color: var(--svg-color--de9f70, #DE9F70);
  stop-opacity: 0;
}

.bvbkf70ft {
  stop-color: var(--svg-color--876a61, #876A61);
}

.c77gj-70g {
  d: path("M4 12.96a2 2 0 1 0 0-3.999a2 2 0 0 0 0 3.999");
}

.cc2sislzy {
  stop-color: var(--svg-color--81645d, #81645D);
}

.cei_u6bpy {
  stop-color: var(--svg-color--985b4e, #985B4E);
}

.ct71bhbcp {
  stop-color: var(--svg-color--a57b49, #A57B49);
  stop-opacity: 0;
}

.cysg0jfku {
  stop-color: var(--svg-color--74524b, #74524B);
}

.dg-j6up8d {
  d: path("M17.059 19.979h-2v10h2z");
}

.dmy1vtjkw {
  stop-color: var(--svg-color--a76e42, #A76E42);
  stop-opacity: 0;
}

.dn1-3tb_i {
  d: path("M28.94 14a2.996 2.996 0 0 0-2.947-3h-.054a2 2 0 0 0-1.99 2c0 .74.402 1.57 1 2.035v1.935h.99V19h.01a2 2 0 1 0 2.99-1.738z");
}

.eyatc9bkt {
  stop-color: var(--svg-color--ba7f52, #BA7F52);
}

.f1qgipbfl {
  stop-color: var(--svg-color--ffb854, #FFB854);
  stop-opacity: 0;
}

.fin5nsbrp {
  stop-color: var(--svg-color--967a60, #967A60);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g5usn5plv {
  stop-color: var(--svg-color--856a63, #856A63);
  stop-opacity: 0;
}

.g6ws9bbay {
  stop-color: var(--svg-color--a76e42, #A76E42);
}

.gdphgvr2s {
  stop-color: var(--svg-color--da3b29, #DA3B29);
  stop-opacity: 0;
}

.gp35dgmcz {
  stop-color: var(--svg-color--d83534, #D83534);
}

.gpds1nbxd {
  stroke: var(--svg-color--f8b178, #F8B178);
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m4.274 19.795l1.539 3.642");
}

.gpshpzbth {
  stop-color: var(--svg-color--6c4a40, #6C4A40);
}

.gqsygd64j {
  stop-color: var(--svg-color--dfa173, #DFA173);
}

.gt1ooh3ht {
  stop-color: var(--svg-color--48322d, #48322D);
  stop-opacity: 0;
}

.h0rmxe_4m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M16.475 2.535v9.082");
}

.h1gug-ivs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.314 21.311v8.204");
}

.h28721kom {
  stop-color: var(--svg-color--de9f70, #DE9F70);
}

.h9q6r6b6n {
  stop-color: var(--svg-color--cb824e, #CB824E);
}

.hfacq8bjg {
  stop-color: var(--svg-color--da9966, #DA9966);
}

.hky1sqdvl {
  fill: var(--svg-color--ffb000, #FFB000);
  d: path("M15.059 12h-2v4h2z");
}

.hz_vkjb_m {
  stop-color: var(--svg-color--9b6e4b, #9B6E4B);
}

.j2mrz2bol {
  stop-color: var(--svg-color--cfa574, #CFA574);
}

.jbkz065vw {
  stop-color: var(--svg-color--744635, #744635);
  stop-opacity: 0;
}

.jpw18ybgx {
  stop-color: var(--svg-color--824c2d, #824C2D);
}

.kp9mht1av {
  stop-color: var(--svg-color--a16545, #A16545);
}

.ky-xwu1jz {
  stop-color: var(--svg-color--ffba55, #FFBA55);
}

.l0dbtlbva {
  d: path("M9.059 7.03a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.liduz3bts {
  d: path("M18.969 16h-5.82c-.6 0-1.09-.49-1.09-1.09v-3.955h7.99v3.955c0 .6-.48 1.09-1.08 1.09");
}

.lxsph8izk {
  stop-color: var(--svg-color--dda03b, #DDA03B);
}

.m_ua78btu {
  d: path("M7.059 8h-2V2c1.1 0 2 .9 2 2z");
}

.mbb6dqblh {
  stop-color: var(--svg-color--ad6f48, #AD6F48);
}

.mui-l1nqt {
  stop-color: var(--svg-color--aa6630, #AA6630);
}

.mvdsgdb2k {
  d: path("M4.785 19.045h2.922v.886H5.214z");
}

.n1sg4qn7s {
  stop-color: var(--svg-color--b69772, #B69772);
}

.ndup4sbve {
  stop-color: var(--svg-color--b47449, #B47449);
}

.nk0igufns {
  stop-color: var(--svg-color--a57b49, #A57B49);
}

.o34az8bpc {
  stop-color: var(--svg-color--6f3a2c, #6F3A2C);
  stop-opacity: 0;
}

.o4dwrkj5n {
  d: path("m5.95 5.933l3.932-.13l2.164 5.158h8.203c3.15 0 5.7 2.554 5.7 5.71v3.304h-.01v1.026c1.274.154 2.077 1.514 1.54 2.74l-1.97 4.448a1.39 1.39 0 0 1-1.8.7c-.71-.29-1-1.161-.69-1.862l1.347-3.035h-1.747a2.68 2.68 0 0 1-2.68-2.684v-1.323c-4.886 0-9.77-.006-14.657 0L6.63 23.02c.31.701.02 1.563-.69 1.853c-.74.31-1.51-.04-1.8-.7l-1.97-4.448c-.57-1.292.37-2.744 1.78-2.744h2.678a5.7 5.7 0 0 1-.678-2.705z");
}

.o7-4khdrm {
  stop-color: var(--svg-color--ffd55d, #FFD55D);
  stop-opacity: 0;
}

.ocsaurbzd {
  stop-color: var(--svg-color--744635, #744635);
}

.ofdaxzayt {
  stop-color: var(--svg-color--e2a752, #E2A752);
}

.on3gwmcnu {
  stop-color: var(--svg-color--ae674f, #AE674F);
}

.oxfz6d9oi {
  d: path("M5.059 8.48a.48.48 0 1 0 0-.96a.48.48 0 0 0 0 .96");
}

.p6nuougos {
  stop-color: var(--svg-color--edc38f, #EDC38F);
}

.plcltqw7z {
  stop-color: var(--svg-color--ffd55d, #FFD55D);
}

.q8_niobbz {
  stop-color: var(--svg-color--f0bc42, #F0BC42);
}

.qghdw-mfe {
  stop-color: var(--svg-color--da9966, #DA9966);
  stop-opacity: 0;
}

.qokqd_59w {
  stop-color: var(--svg-color--71392e, #71392E);
}

.qpp-a9byy {
  stop-color: var(--svg-color--9b6c4c, #9B6C4C);
  stop-opacity: 0;
}

.qufmd3b6t {
  d: path("M3.059 4.495c0 .827.67 1.495 1.5 1.495c.458 0 .868-.204 1.143-.526l1.25-1.349a.4.4 0 0 0 .107-.272V3h-2.56v.001a1.495 1.495 0 0 0-1.44 1.494");
}

.r-046vbdt {
  stop-color: var(--svg-color--9a5f40, #9A5F40);
}

.r9pb4-bwl {
  stop-color: var(--svg-color--744538, #744538);
}

.rdz2y6i7v {
  stop-color: var(--svg-color--f2a145, #F2A145);
}

.rfj-ib8no {
  stop-color: var(--svg-color--674b40, #674B40);
}

.rynhwmbia {
  stroke: var(--svg-color--fec590, #FEC590);
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m8.166 3.854l2.997 7.413");
}

.s_n_m-bfl {
  stop-color: var(--svg-color--b88e63, #B88E63);
}

.s4nw2331q {
  stop-color: var(--svg-color--ffd399, #FFD399);
  stop-opacity: 0;
}

.sacfwgwyv {
  d: path("M11.079 10.02a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.t3mh7cjqe {
  stop-color: var(--svg-color--e83937, #E83937);
}

.u--irczuc {
  d: path("M13.059 13.01a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.u44kqtbwx {
  stop-color: var(--svg-color--856a63, #856A63);
}

.usl7aub2n {
  stop-color: var(--svg-color--684245, #684245);
  stop-opacity: 0;
}

.v_47q4bkc {
  stop-color: var(--svg-color--6d453f, #6D453F);
}

.v2510fb5y {
  fill: var(--svg-color--6a4644, #6A4644);
  d: path("M28.94 14a2.996 2.996 0 0 0-2.947-3h-.054a2 2 0 0 0-1.99 2c0 .74.402 1.57 1 2.035v1.935h.99V19h.01a2 2 0 1 0 2.99-1.738z");
}

.vj5ghtafm {
  d: path("M17.059 2h-2v9h2z");
}

.wcbbgdcqg {
  stop-color: var(--svg-color--da3b29, #DA3B29);
}

.wtc2g2hnp {
  stop-color: var(--svg-color--866961, #866961);
}

.x0sqhq5gl {
  stop-color: var(--svg-color--ffb854, #FFB854);
}

.x2pve9bbg {
  stop-color: var(--svg-color--684245, #684245);
}

.x8424g3as {
  stop-color: var(--svg-color--71392e, #71392E);
  stop-opacity: 0;
}

.x8nbo2b_c {
  stop-color: var(--svg-color--48322d, #48322D);
}

.xjcwu0qkc {
  stop-color: var(--svg-color--8a5138, #8A5138);
}

.xvxw1vg8l {
  fill: var(--svg-color--e2a87c, #E2A87C);
  d: path("M7.059 1.99v1.02c0 .548-.454.978-.971 1.16A3.04 3.04 0 0 0 4.36 5.71L2.328 9.865l2.96 2.645l3.548-3.004q.217-.155.405-.343l.098-.083l-.012-.008a3.02 3.02 0 0 0 .792-2.042c0-.422-.06-.807-.216-1.172L8.995 3.49c-.275-.87-1.009-1.5-1.936-1.5");
}

.y3b8pmbvt {
  d: path("M13.072 19.979h-3l-3.14 7.07c-.4.91.26 1.93 1.25 1.93c.54 0 1.03-.32 1.25-.81z");
}

.yfksle2hz {
  stop-color: var(--svg-color--6f3a2c, #6F3A2C);
}

.yfv4p3bng {
  stop-color: var(--svg-color--ffd399, #FFD399);
}

.yqoyh4sxu {
  stop-color: var(--svg-color--ffb861, #FFB861);
}

.yrhnwfbgx {
  fill: var(--svg-color--6a4532, #6A4532);
  d: path("M13.059 13.01a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.yrtoc-01q {
  stop-color: var(--svg-color--fca852, #FCA852);
}

.ysdtaebqs {
  stop-color: var(--svg-color--b88e63, #B88E63);
  stop-opacity: 0;
}

.z5lu5r0js {
  stop-color: var(--svg-color--ae674f, #AE674F);
  stop-opacity: 0;
}

.z6u-ipbwk {
  d: path("M7.059 1.99v1.02c0 .548-.454.978-.971 1.16A3.04 3.04 0 0 0 4.36 5.71L2.328 9.865l2.96 2.645l3.548-3.004q.217-.155.405-.343l.098-.083l-.012-.008a3.02 3.02 0 0 0 .792-2.042c0-.422-.06-.807-.216-1.172L8.995 3.49c-.275-.87-1.009-1.5-1.936-1.5");
}

.z8kkkg14p {
  stop-color: var(--svg-color--967a60, #967A60);
}

.zpp74p80k {
  d: path("M6.693 16.96h.044a5.7 5.7 0 0 1-.678-2.704V10.16h.26l.35 3.436a8 8 0 0 0 1.086 3.285l.377.632z");
}

</style>
