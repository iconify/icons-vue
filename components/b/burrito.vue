<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#i0M8Xte)" class="zoh9b4bwg"/><path fill="url(#idmHfye)" class="zoh9b4bwg"/><path fill="url(#iOgZT2d)" class="opquxf-4a"/><path fill="url(#ixAu2Kc)" class="mnw04fb6n"/><path fill="url(#iMv0NiS)" class="a3ntnnb_v"/><path fill="url(#iJpUMtb)" class="zfh04-beu"/><g filter="url(#izllQUd)"><path class="h8uel8bry"/></g><path fill="url(#iqrNxub)" class="u05ejlbyp"/><path fill="url(#iLuaSPd)" class="u05ejlbyp"/><path fill="url(#iFIVeqb)" class="u05ejlbyp"/><path fill="url(#iHuwH1d)" class="u05ejlbyp"/><path fill="url(#iEJAxgg)" class="u05ejlbyp"/><path fill="url(#iEe5rYc)" class="u05ejlbyp"/><path fill="url(#ip9G7id)" class="cxwp84bmc"/><path fill="url(#ik8ezIg)" class="cxwp84bmc"/><path fill="url(#ibcf2ju)" class="u10ukeyyz"/><path fill="url(#i9qpEFe)" class="u10ukeyyz"/><path fill="url(#itw4LDe)" class="u10ukeyyz"/><path fill="url(#iJhimEq)" class="u10ukeyyz"/><g filter="url(#iHrMmwc)"><path class="wb2h_bl_x"/></g><g filter="url(#i1hz5bb)"><path fill="url(#iN6YOJe)" class="lmuuq4bsm"/><path fill="url(#iLHfjsb)" class="lmuuq4bsm"/><path fill="url(#i8JHzyc)" class="lmuuq4bsm"/><path fill="url(#ie2Lc7c)" class="lmuuq4bsm"/><path fill="url(#iPX2rZb)" class="lmuuq4bsm"/><path fill="url(#iK9zTFc)" class="lmuuq4bsm"/><path fill="url(#iZOGijb)" class="lmuuq4bsm"/><path fill="url(#iYdICMe)" class="lmuuq4bsm"/><path fill="url(#iuj2WUd)" class="lmuuq4bsm"/><path fill="url(#iOTqWNe)" class="lmuuq4bsm"/><path fill="url(#iOXKoGb)" class="lmuuq4bsm"/></g><g filter="url(#ixTNbrb)"><path fill="url(#iNcXzDd)" class="s6_qo0b0s"/></g><g filter="url(#iGrbAOd)"><path fill="url(#i0aBDwa)" class="ou0w_ubcf"/></g><g filter="url(#i9G95ab)"><path fill="url(#isqXFzH)" class="asx-m94_i"/></g><g filter="url(#inn9UEb)"><path fill="url(#i63loae)" class="d_qbtybqm"/></g></g><defs><radialGradient id="idmHfye" cx="0" cy="0" r="1" gradientTransform="matrix(3.62497 5.19628 -5.19459 3.6238 5.437 16.491)" gradientUnits="userSpaceOnUse"><stop class="bsqpd7b0c"/><stop offset="1" class="mt_3sfr-e"/></radialGradient><radialGradient id="iMv0NiS" cx="0" cy="0" r="1" gradientTransform="matrix(3.24462 3.60516 -6.3518 5.71657 9.43 9.428)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="km34w7oco"/><stop offset="1" class="bcnu6d3jv"/></radialGradient><radialGradient id="iJpUMtb" cx="0" cy="0" r="1" gradientTransform="rotate(48.013 -5.682 14.807)scale(4.62468 8.14807)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="kth_b_bdt"/><stop offset="1" class="msagtxbbh"/></radialGradient><radialGradient id="iLuaSPd" cx="0" cy="0" r="1" gradientTransform="matrix(.41845 .54687 -.75716 .57936 14.985 6.406)" gradientUnits="userSpaceOnUse"><stop class="g63na0b1p"/><stop offset="1" class="l3mbwqa8l"/></radialGradient><radialGradient id="iFIVeqb" cx="0" cy="0" r="1" gradientTransform="matrix(.48438 .57812 -.80043 .67063 13.063 8.39)" gradientUnits="userSpaceOnUse"><stop class="g63na0b1p"/><stop offset="1" class="l3mbwqa8l"/></radialGradient><radialGradient id="iHuwH1d" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .64062 -.88697 .649 10.984 10.375)" gradientUnits="userSpaceOnUse"><stop class="g63na0b1p"/><stop offset="1" class="l3mbwqa8l"/></radialGradient><radialGradient id="iEJAxgg" cx="0" cy="0" r="1" gradientTransform="matrix(.49219 .51563 -.7139 .68145 9.094 12.492)" gradientUnits="userSpaceOnUse"><stop class="g63na0b1p"/><stop offset="1" class="l3mbwqa8l"/></radialGradient><radialGradient id="iEe5rYc" cx="0" cy="0" r="1" gradientTransform="matrix(.46094 .51562 -.7139 .63818 7.04 14.43)" gradientUnits="userSpaceOnUse"><stop class="g63na0b1p"/><stop offset="1" class="l3mbwqa8l"/></radialGradient><radialGradient id="ik8ezIg" cx="0" cy="0" r="1" gradientTransform="matrix(8.9374 -5.75756 2.27288 3.52817 6.625 16.32)" gradientUnits="userSpaceOnUse"><stop class="qo490mcxl"/><stop offset="1" class="k_17sxbka"/></radialGradient><radialGradient id="i9qpEFe" cx="0" cy="0" r="1" gradientTransform="matrix(.21396 1.53125 -4.09729 .57251 8.005 5.063)" gradientUnits="userSpaceOnUse"><stop class="dzk3kbuba"/><stop offset=".649" class="ayji31ani"/></radialGradient><radialGradient id="itw4LDe" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 .84376 -2.9026 2.7413 4.39 10.157)" gradientUnits="userSpaceOnUse"><stop class="u74jdzbxz"/><stop offset="1" class="tu9qirb9a"/></radialGradient><radialGradient id="iJhimEq" cx="0" cy="0" r="1" gradientTransform="rotate(98.306 .121 4.092)scale(4.32663 1.72223)" gradientUnits="userSpaceOnUse"><stop class="i5oa1sbjx"/><stop offset="1" class="fspt6ub_w"/></radialGradient><radialGradient id="iZOGijb" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .5 -.85593 .08024 12.531 3.594)" gradientUnits="userSpaceOnUse"><stop class="w45qnw7dk"/><stop offset="1" class="qn12wev7h"/></radialGradient><radialGradient id="iYdICMe" cx="0" cy="0" r="1" gradientTransform="matrix(.07813 .57813 -.98967 .13374 10.39 5.61)" gradientUnits="userSpaceOnUse"><stop class="hb6-qgtba"/><stop offset="1" class="veonb_f8p"/></radialGradient><radialGradient id="iuj2WUd" cx="0" cy="0" r="1" gradientTransform="matrix(.09375 .64063 -1.09666 .1605 8.36 7.547)" gradientUnits="userSpaceOnUse"><stop class="hb6-qgtba"/><stop offset="1" class="veonb_f8p"/></radialGradient><radialGradient id="iOTqWNe" cx="0" cy="0" r="1" gradientTransform="matrix(.125 .57812 -.98967 .21398 6.406 9.64)" gradientUnits="userSpaceOnUse"><stop class="hb6-qgtba"/><stop offset="1" class="veonb_f8p"/></radialGradient><radialGradient id="iOXKoGb" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 .54688 -.93618 .18723 4.281 11.594)" gradientUnits="userSpaceOnUse"><stop class="hb6-qgtba"/><stop offset="1" class="veonb_f8p"/></radialGradient><linearGradient id="i0M8Xte" x1="18.563" x2="7" y1="6.688" y2="18" gradientUnits="userSpaceOnUse"><stop class="ou5ml8bxz"/><stop offset=".128" class="tn1-dkbaz"/><stop offset=".281" class="ly_aedc4e"/><stop offset=".527" class="iiq0k7jos"/><stop offset=".817" class="c1_9f-dam"/><stop offset="1" class="dt9lwfbnu"/></linearGradient><linearGradient id="iOgZT2d" x1="31.875" x2="23.54" y1="20.188" y2="29.74" gradientUnits="userSpaceOnUse"><stop class="qhog66_zv"/><stop offset=".059" class="o8pjqjbai"/><stop offset=".231" class="abqa825sj"/><stop offset=".345" class="e39fbbdop"/><stop offset=".554" class="s39-u0blc"/><stop offset=".713" class="e1s-xrbxs"/><stop offset="1" class="mdoxopzhz"/></linearGradient><linearGradient id="ixAu2Kc" x1="26.839" x2="14.875" y1="14" y2="26.563" gradientUnits="userSpaceOnUse"><stop class="y9gumubul"/><stop offset=".123" class="nocwy-b-w"/><stop offset=".191" class="wppe3rbgh"/><stop offset=".278" class="qya3zgb3k"/><stop offset=".449" class="nve256p6e"/><stop offset=".561" class="pxo5d1eoo"/><stop offset=".666" class="hbgk3sbdz"/><stop offset=".833" class="g9nmrfa4d"/><stop offset="1" class="sr52_cy9v"/></linearGradient><linearGradient id="iqrNxub" x1="10.078" x2="11.438" y1="10.654" y2="11.938" gradientUnits="userSpaceOnUse"><stop class="prcww9bij"/><stop offset="1" class="bz4da6inz"/></linearGradient><linearGradient id="ip9G7id" x1="5.688" x2="12" y1="5.625" y2="12.625" gradientUnits="userSpaceOnUse"><stop class="tajeamb5c"/><stop offset=".39" class="fhpmyqbhh"/><stop offset=".579" class="r9i_hacyz"/></linearGradient><linearGradient id="ibcf2ju" x1="2.76" x2="12.438" y1="12.5" y2="2.188" gradientUnits="userSpaceOnUse"><stop class="r5-2r66yr"/><stop offset=".467" class="i3-it-afm"/><stop offset=".653" class="ksizv-b8u"/><stop offset="1" class="gso0l4lde"/></linearGradient><linearGradient id="iN6YOJe" x1="7.688" x2="9.188" y1="7.563" y2="9.063" gradientUnits="userSpaceOnUse"><stop class="y8zmdzb7e"/><stop offset=".865" class="hex94sbml"/></linearGradient><linearGradient id="iLHfjsb" x1="13.703" x2="11.844" y1="3.453" y2="5.281" gradientUnits="userSpaceOnUse"><stop class="etesp2m9f"/><stop offset=".193" class="cszjjbo-i"/><stop offset=".711" class="tbvd683lo"/><stop offset="1" class="l82nk1bkn"/></linearGradient><linearGradient id="i8JHzyc" x1="11.734" x2="9.594" y1="5.375" y2="7.484" gradientUnits="userSpaceOnUse"><stop class="kcugaqbth"/><stop offset=".076" class="sjz96oa7x"/><stop offset=".168" class="cszjjbo-i"/><stop offset=".711" class="tbvd683lo"/><stop offset="1" class="l82nk1bkn"/></linearGradient><linearGradient id="ie2Lc7c" x1="9.75" x2="7.594" y1="7.422" y2="9.594" gradientUnits="userSpaceOnUse"><stop class="kcugaqbth"/><stop offset=".076" class="sjz96oa7x"/><stop offset=".168" class="cszjjbo-i"/><stop offset=".711" class="tbvd683lo"/><stop offset="1" class="l82nk1bkn"/></linearGradient><linearGradient id="iPX2rZb" x1="7.859" x2="5.656" y1="9.359" y2="11.5" gradientUnits="userSpaceOnUse"><stop class="kcugaqbth"/><stop offset=".076" class="sjz96oa7x"/><stop offset=".168" class="cszjjbo-i"/><stop offset=".711" class="tbvd683lo"/><stop offset="1" class="l82nk1bkn"/></linearGradient><linearGradient id="iK9zTFc" x1="5.844" x2="3.406" y1="11.375" y2="13.813" gradientUnits="userSpaceOnUse"><stop class="kcugaqbth"/><stop offset=".076" class="sjz96oa7x"/><stop offset=".168" class="cszjjbo-i"/><stop offset=".814" class="tbvd683lo"/><stop offset="1" class="dqkr2_bot"/></linearGradient><linearGradient id="iNcXzDd" x1="13.792" x2="14.19" y1="7.821" y2="8.227" gradientUnits="userSpaceOnUse"><stop class="u67lah9pu"/><stop offset=".829" class="mh358hkmc"/></linearGradient><linearGradient id="i0aBDwa" x1="11.808" x2="12.206" y1="9.821" y2="10.227" gradientUnits="userSpaceOnUse"><stop class="u67lah9pu"/><stop offset=".829" class="mh358hkmc"/></linearGradient><linearGradient id="isqXFzH" x1="9.824" x2="10.221" y1="11.813" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="u67lah9pu"/><stop offset=".829" class="mh358hkmc"/></linearGradient><linearGradient id="i63loae" x1="7.871" x2="8.268" y1="13.832" y2="14.237" gradientUnits="userSpaceOnUse"><stop class="u67lah9pu"/><stop offset=".829" class="mh358hkmc"/></linearGradient><filter id="izllQUd" width="10.533" height="10.529" x="5.259" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33695" stdDeviation=".25"/></filter><filter id="iHrMmwc" width="11.856" height="11.699" x="2.452" y="2.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33695" stdDeviation=".375"/></filter><filter id="i1hz5bb" width="18.832" height="18.835" x="-.856" y="3.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_33695"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_33695" result="shape"/></filter><filter id="ixTNbrb" width="1.004" height=".97" x="13.461" y="7.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33695" stdDeviation=".125"/></filter><filter id="iGrbAOd" width="1.004" height=".97" x="11.477" y="9.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33695" stdDeviation=".125"/></filter><filter id="i9G95ab" width="1.004" height=".97" x="9.492" y="11.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33695" stdDeviation=".125"/></filter><filter id="inn9UEb" width="1.004" height=".97" x="7.539" y="13.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33695" stdDeviation=".125"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:burrito" /></template>
<style>
.a3ntnnb_v {
  d: path("M15.37 6.06a3.567 3.567 0 0 0-6.06-2.09L3.94 9.34a3.567 3.567 0 0 0 0 5.04c.59.59 1.33.92 2.09 1.02z");
}

.abqa825sj {
  stop-color: var(--svg-color--d8d3db, #D8D3DB);
}

.asx-m94_i {
  d: path("M9.883 11.73a.6.6 0 0 1-.14.145l.438.326l.065-.07z");
}

.ayji31ani {
  stop-color: var(--svg-color--95dd77, #95DD77);
  stop-opacity: 0;
}

.bcnu6d3jv {
  stop-color: var(--svg-color--e9af38, #E9AF38);
}

.bsqpd7b0c {
  stop-color: var(--svg-color--e6ae9d, #E6AE9D);
}

.bz4da6inz {
  stop-color: var(--svg-color--512316, #512316);
}

.c1_9f-dam {
  stop-color: var(--svg-color--e4a59d, #E4A59D);
}

.cszjjbo-i {
  stop-color: var(--svg-color--ffeacd, #FFEACD);
}

.cxwp84bmc {
  d: path("M11.81 2.95c.91 0 1.82.35 2.52 1.04a3.567 3.567 0 0 1 0 5.04l-5.3 5.3c-.7.7-1.61 1.04-2.52 1.04s-1.82-.35-2.52-1.04a3.567 3.567 0 0 1 0-5.04l5.3-5.3c.69-.7 1.61-1.04 2.52-1.04m0-.95c-1.2 0-2.34.47-3.19 1.32l-5.3 5.3C2.47 9.47 2 10.6 2 11.81c0 1.2.47 2.34 1.32 3.19s1.98 1.32 3.19 1.32c1.2 0 2.34-.47 3.19-1.32L15 9.7c.85-.85 1.32-1.98 1.32-3.19c0-1.2-.47-2.34-1.32-3.19A4.5 4.5 0 0 0 11.81 2");
}

.d_qbtybqm {
  d: path("M7.93 13.75a.6.6 0 0 1-.14.144l.438.326l.065-.07z");
}

.dqkr2_bot {
  stop-color: var(--svg-color--f8d2a5, #F8D2A5);
}

.dt9lwfbnu {
  stop-color: var(--svg-color--d79ea2, #D79EA2);
}

.dzk3kbuba {
  stop-color: var(--svg-color--95dd77, #95DD77);
}

.e1s-xrbxs {
  stop-color: var(--svg-color--ab9abc, #AB9ABC);
}

.e39fbbdop {
  stop-color: var(--svg-color--e0d7e8, #E0D7E8);
}

.etesp2m9f {
  stop-color: var(--svg-color--f9d0a1, #F9D0A1);
}

.fhpmyqbhh {
  stop-color: var(--svg-color--dcab8a, #DCAB8A);
}

.fspt6ub_w {
  stop-color: var(--svg-color--639060, #639060);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g63na0b1p {
  stop-color: var(--svg-color--775756, #775756);
}

.g9nmrfa4d {
  stop-color: var(--svg-color--bea6d4, #BEA6D4);
}

.gso0l4lde {
  stop-color: var(--svg-color--93dc40, #93DC40);
}

.h8uel8bry {
  fill: var(--svg-color--daa536, #DAA536);
  d: path("M14.839 8.211c.4-.72.54-1.55.4-2.34c-.39.04-.76.21-1.06.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.2-.17.37-.37.39c-.43.04-.84.23-1.16.57c-.26.28-.4.63-.44.99c.79.13 1.62 0 2.34-.4c.28-.16.54-.35.78-.59l5.37-5.37c.24-.24.43-.5.59-.78");
}

.hb6-qgtba {
  stop-color: var(--svg-color--fff5d7, #FFF5D7);
}

.hbgk3sbdz {
  stop-color: var(--svg-color--c6b3d8, #C6B3D8);
}

.hex94sbml {
  stop-color: var(--svg-color--e6b998, #E6B998);
}

.i3-it-afm {
  stop-color: var(--svg-color--70b765, #70B765);
}

.i5oa1sbjx {
  stop-color: var(--svg-color--5f915a, #5F915A);
}

.iiq0k7jos {
  stop-color: var(--svg-color--f3bba2, #F3BBA2);
}

.k_17sxbka {
  stop-color: var(--svg-color--e2ac85, #E2AC85);
  stop-opacity: 0;
}

.kcugaqbth {
  stop-color: var(--svg-color--f9d0a1, #F9D0A1);
  stop-opacity: 0;
}

.km34w7oco {
  stop-color: var(--svg-color--ffcf4d, #FFCF4D);
}

.ksizv-b8u {
  stop-color: var(--svg-color--7ecf51, #7ECF51);
}

.kth_b_bdt {
  stop-color: var(--svg-color--f64c8f, #F64C8F);
}

.l3mbwqa8l {
  stop-color: var(--svg-color--745352, #745352);
  stop-opacity: 0;
}

.l82nk1bkn {
  stop-color: var(--svg-color--ffe0c6, #FFE0C6);
  stop-opacity: 0;
}

.lmuuq4bsm {
  d: path("M13.977 3.695c-.69-.69-1.747-.745-2.437-.055c-.3.3-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.2-.17.37-.37.39c-.43.04-.84.23-1.16.57c-.59.66-.533 1.624.047 2.284c.03.03.05.06.08.08z");
}

.ly_aedc4e {
  stop-color: var(--svg-color--ffd3b7, #FFD3B7);
}

.mdoxopzhz {
  stop-color: var(--svg-color--a58dbd, #A58DBD);
}

.mh358hkmc {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
  stop-opacity: 0;
}

.mnw04fb6n {
  d: path("m24.98 13.39l-5.73-5.73a8.18 8.18 0 0 1 0 11.56a8.18 8.18 0 0 1-11.56 0l8.32 8.32a8.15 8.15 0 0 0 7.53 2.2c3.85-4.68 4.33-11.21 1.44-16.35");
}

.msagtxbbh {
  stop-color: var(--svg-color--de396d, #DE396D);
}

.mt_3sfr-e {
  stop-color: var(--svg-color--e3aca4, #E3ACA4);
  stop-opacity: 0;
}

.nocwy-b-w {
  stop-color: var(--svg-color--b4b2b4, #B4B2B4);
}

.nve256p6e {
  stop-color: var(--svg-color--dfd4e9, #DFD4E9);
}

.o8pjqjbai {
  stop-color: var(--svg-color--b2b0b2, #B2B0B2);
}

.opquxf-4a {
  d: path("M27.57 27.54a8.18 8.18 0 0 0 0-11.56l-2.59-2.59c2.89 5.14 2.41 11.67-1.44 16.35a8.05 8.05 0 0 0 4.03-2.2");
}

.ou0w_ubcf {
  d: path("M11.867 9.738a.6.6 0 0 1-.14.145l.439.326l.065-.07z");
}

.ou5ml8bxz {
  stop-color: var(--svg-color--fcd6ad, #FCD6AD);
}

.prcww9bij {
  stop-color: var(--svg-color--6e4a43, #6E4A43);
}

.pxo5d1eoo {
  stop-color: var(--svg-color--c8b9d6, #C8B9D6);
}

.qhog66_zv {
  stop-color: var(--svg-color--c0bfbf, #C0BFBF);
}

.qn12wev7h {
  stop-color: var(--svg-color--ffffe2, #FFFFE2);
  stop-opacity: 0;
}

.qo490mcxl {
  stop-color: var(--svg-color--e5b08d, #E5B08D);
}

.qya3zgb3k {
  stop-color: var(--svg-color--ebe2f3, #EBE2F3);
}

.r5-2r66yr {
  stop-color: var(--svg-color--407c64, #407C64);
}

.r9i_hacyz {
  stop-color: var(--svg-color--facaa5, #FACAA5);
}

.s39-u0blc {
  stop-color: var(--svg-color--bfb2cd, #BFB2CD);
}

.s6_qo0b0s {
  d: path("M13.852 7.738a.6.6 0 0 1-.141.145l.44.326l.064-.07z");
}

.sjz96oa7x {
  stop-color: var(--svg-color--f9cfb5, #F9CFB5);
}

.sr52_cy9v {
  stop-color: var(--svg-color--caafe2, #CAAFE2);
}

.tajeamb5c {
  stop-color: var(--svg-color--dab68c, #DAB68C);
}

.tbvd683lo {
  stop-color: var(--svg-color--ffdbc2, #FFDBC2);
}

.tn1-dkbaz {
  stop-color: var(--svg-color--ffd5ab, #FFD5AB);
}

.tu9qirb9a {
  stop-color: var(--svg-color--70b682, #70B682);
  stop-opacity: 0;
}

.u05ejlbyp {
  d: path("M14.95 8.23c.4-.72.54-1.55.4-2.34c-.39.04-.76.21-1.06.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.2-.17.37-.37.39c-.43.04-.84.23-1.16.57c-.26.28-.4.63-.44.99c.79.13 1.62 0 2.34-.4c.28-.16.54-.35.78-.59l5.37-5.37c.24-.24.43-.5.59-.78");
}

.u10ukeyyz {
  d: path("M13.203 3.219c-1.05-.62-2.396-.601-3.336.219c-.63.63-1.566.93-2.437.832a2.864 2.864 0 0 0-3.18 3.18c.1.88-.16 1.77-.75 2.43c-.01.01-.02.03-.04.04c-.82.94-.861 2.233-.241 3.283z");
}

.u67lah9pu {
  stop-color: var(--svg-color--795b58, #795B58);
}

.u74jdzbxz {
  stop-color: var(--svg-color--70b682, #70B682);
}

.veonb_f8p {
  stop-color: var(--svg-color--fff5d7, #FFF5D7);
  stop-opacity: 0;
}

.w45qnw7dk {
  stop-color: var(--svg-color--ffffe2, #FFFFE2);
}

.wb2h_bl_x {
  fill: var(--svg-color--437822, #437822);
  d: path("M13.558 3.792c-.69-.69-1.831-.66-2.2-.29c-.3.3-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.21-.18.37-.39.39c-.4.04-.78.21-1.08.51s-.47.69-.51 1.08c-.02.2-.17.37-.37.39c-.43.04-.84.23-1.16.57c-.315.315-.244 1.453.518 1.961z");
}

.wppe3rbgh {
  stop-color: var(--svg-color--d6d0db, #D6D0DB);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.y8zmdzb7e {
  stop-color: var(--svg-color--f4dab8, #F4DAB8);
}

.y9gumubul {
  stop-color: var(--svg-color--c3c2c3, #C3C2C3);
}

.zfh04-beu {
  d: path("M14.79 4.5a3.567 3.567 0 0 0-5.48-.53L3.94 9.34a3.567 3.567 0 0 0 .53 5.48z");
}

.zoh9b4bwg {
  d: path("M27.57 15.98L14.64 3.05L3.09 14.61l12.93 12.93a8.18 8.18 0 0 0 11.56 0c3.18-3.19 3.18-8.37-.01-11.56");
}

</style>
