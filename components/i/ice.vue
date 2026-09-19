<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="jb3s48bja"/><path fill="url(#i8k0bCe)" class="u-skrhpwv"/><path fill="url(#icDy2vc)" class="u-skrhpwv"/><path fill="url(#iRJQTjc)" class="u-skrhpwv"/><path fill="url(#iytFytc)" class="u-skrhpwv"/><path fill="url(#iFHQIhc)" class="u-skrhpwv"/><path fill="url(#iQa9Qid)" class="u-skrhpwv"/><path fill="url(#ieb23qb)" class="xum7-mb_l"/><path fill="url(#imLU2mc)" class="xum7-mb_l"/><path fill="url(#ifHhuie)" class="xum7-mb_l"/><path fill="url(#iaCzWge)" class="xum7-mb_l"/><path fill="url(#iwBNend)" class="bl5me5bcz"/><path fill="url(#iz7EWkd)" class="bl5me5bcz"/><path fill="url(#iYRfNAc)" class="bl5me5bcz"/><path fill="url(#i6XzkKe)" class="bl5me5bcz"/><g filter="url(#iacFVpb)"><path class="ww8qu5h6i"/><path class="zgtx81gcf"/></g><path class="svonbybgo"/><path fill="url(#ijBGuae)" class="gzcyrmb0s"/><path fill="url(#i9uF1wc)" class="gzcyrmb0s"/><path fill="url(#icGBVBS)" class="gzcyrmb0s"/><g filter="url(#iqrlsHb)"><path class="was-zwi9f"/></g><path fill="url(#iat9R0b)" class="bth753b3f"/><path fill="url(#i1J8a6i)" class="bth753b3f"/><g filter="url(#iMRSXuc)"><path class="g6vpfwagr"/></g><path fill="url(#iVLyFSb)" class="d9pi6lbab"/><path fill="url(#iPu2x4c)" class="d9pi6lbab"/><g filter="url(#idDdtYF)"><path class="m8f2ww42p"/></g><path fill="url(#iTtdBFe)" class="m6sgcabjh"/><path fill="url(#iyq8OCc)" class="m6sgcabjh"/><g filter="url(#iv2iOIC)"><path class="pdqx3244b"/></g><path class="l1pkrwe9v"/><path fill="url(#i8wfxkc)" class="oywhlabhh"/><path fill="url(#i57gjjc)" class="oywhlabhh"/><path fill="url(#it2Eqcd)" class="oywhlabhh"/><g filter="url(#iktrgzc)"><path class="im8uuhbwk"/></g><defs><radialGradient id="iytFytc" cx="0" cy="0" r="1" gradientTransform="matrix(.125 .57812 -1.07478 .2324 16.328 11.906)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="mdvjo_zeu"/><stop offset="1" class="e3xoh7b4v"/></radialGradient><radialGradient id="i6XzkKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .5 -.51723 -.96983 16.375 11.938)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="iltfjibvi"/><stop offset="1" class="a-7awfpjp"/></radialGradient><radialGradient id="ijBGuae" cx="0" cy="0" r="1" gradientTransform="rotate(77.773 -1.828 21.747)scale(2.9512 1.87783)" gradientUnits="userSpaceOnUse"><stop class="pr6xapbyn"/><stop offset="1" class="l1hgkbcmq"/></radialGradient><radialGradient id="i9uF1wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.34375 -.97288 0 21.047 13.672)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="evbvtof4w"/><stop offset=".799" class="ekdgm7bqu"/></radialGradient><radialGradient id="icGBVBS" cx="0" cy="0" r="1" gradientTransform="rotate(71.061 .679 22.51)scale(3.36993 1.23565)" gradientUnits="userSpaceOnUse"><stop class="evbvtof4w"/><stop offset="1" class="zncnru-kq"/></radialGradient><radialGradient id="iat9R0b" cx="0" cy="0" r="1" gradientTransform="rotate(82.878 1.522 25.54)scale(1.08424 1.03065)" gradientUnits="userSpaceOnUse"><stop class="odkvdob0p"/><stop offset="1" class="o81qdw3ng"/></radialGradient><radialGradient id="i1J8a6i" cx="0" cy="0" r="1" gradientTransform="rotate(67.225 -1.822 30.63)scale(.444 .8617)" gradientUnits="userSpaceOnUse"><stop class="om214s09y"/><stop offset="1" class="umv9g3bdf"/></radialGradient><radialGradient id="iVLyFSb" cx="0" cy="0" r="1" gradientTransform="rotate(107.942 -.186 14.02)scale(1.72449 1.97154)" gradientUnits="userSpaceOnUse"><stop class="x_beddboc"/><stop offset=".462" class="o9zpaghws"/><stop offset=".801" class="wci10qhco"/></radialGradient><radialGradient id="iPu2x4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.29688 .20313 -.18253 -.26677 13.204 18.437)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="h43-8pbys"/><stop offset="1" class="xnssdkbld"/></radialGradient><radialGradient id="iTtdBFe" cx="0" cy="0" r="1" gradientTransform="rotate(107.533 -3.977 14.705)scale(2.04986 2.297)" gradientUnits="userSpaceOnUse"><stop class="x_beddboc"/><stop offset=".462" class="o9zpaghws"/><stop offset=".801" class="wci10qhco"/></radialGradient><radialGradient id="iyq8OCc" cx="0" cy="0" r="1" gradientTransform="rotate(144.96 .883 12.833)scale(.42149 .38205)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="h43-8pbys"/><stop offset="1" class="xnssdkbld"/></radialGradient><radialGradient id="i8wfxkc" cx="0" cy="0" r="1" gradientTransform="matrix(-.37041 4.8125 -3.05913 -.23546 6.188 14.063)" gradientUnits="userSpaceOnUse"><stop offset=".449" class="gd2k6dpqt"/><stop offset=".846" class="kyz9y2bhv"/></radialGradient><radialGradient id="i57gjjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.4375 -2.57211 0 5.817 13.75)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="n3l1ve9pr"/><stop offset="1" class="bpcj5g73j"/></radialGradient><radialGradient id="it2Eqcd" cx="0" cy="0" r="1" gradientTransform="rotate(85.4 -3.656 9.832)scale(2.72754 .62241)" gradientUnits="userSpaceOnUse"><stop class="j5_zt8bwe"/><stop offset="1" class="jpnznbcsu"/></radialGradient><linearGradient id="i8k0bCe" x1="10.5" x2="15.969" y1="4.125" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="c0t8wndak"/><stop offset="1" class="wpz-l5bng"/></linearGradient><linearGradient id="icDy2vc" x1="20.844" x2="20.469" y1="10.5" y2="9.438" gradientUnits="userSpaceOnUse"><stop offset=".175" class="yaism030s"/><stop offset=".73" class="a-7awfpjp"/></linearGradient><linearGradient id="iRJQTjc" x1="8.875" x2="9.313" y1="9.688" y2="8.438" gradientUnits="userSpaceOnUse"><stop offset=".175" class="frltds1py"/><stop offset=".73" class="ioicbcb_a"/></linearGradient><linearGradient id="iFHQIhc" x1="9.438" x2="9.719" y1="4.438" y2="5.188" gradientUnits="userSpaceOnUse"><stop class="zfgivjbdt"/><stop offset="1" class="y1p3f-bbq"/></linearGradient><linearGradient id="iQa9Qid" x1="9.438" x2="9.719" y1="4.438" y2="5.188" gradientUnits="userSpaceOnUse"><stop class="zvnr-nb7n"/><stop offset=".317" class="yrbamibps"/></linearGradient><linearGradient id="ieb23qb" x1="18.375" x2="27.875" y1="12" y2="25.625" gradientUnits="userSpaceOnUse"><stop class="utfdhqint"/><stop offset="1" class="nt7oa0bvh"/></linearGradient><linearGradient id="imLU2mc" x1="24.375" x2="23.875" y1="27.219" y2="25.875" gradientUnits="userSpaceOnUse"><stop class="imyw3fujn"/><stop offset="1" class="anbwh8ydc"/></linearGradient><linearGradient id="ifHhuie" x1="16.03" x2="18.625" y1="23.375" y2="23.375" gradientUnits="userSpaceOnUse"><stop class="js0gkfbjk"/><stop offset="1" class="z6iwvmpsb"/></linearGradient><linearGradient id="iaCzWge" x1="22.063" x2="22.5" y1="9.75" y2="11" gradientUnits="userSpaceOnUse"><stop offset=".134" class="dkh3y3boo"/><stop offset=".802" class="g7g2kwb8x"/></linearGradient><linearGradient id="iwBNend" x1="3.188" x2="14.625" y1="8.75" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="yko_63gjq"/><stop offset=".755" class="c-z2nqbfk"/></linearGradient><linearGradient id="iz7EWkd" x1="13.375" x2="16.03" y1="24.125" y2="24.125" gradientUnits="userSpaceOnUse"><stop offset=".659" class="s3yl7l3wi"/><stop offset="1" class="xop139bzz"/></linearGradient><linearGradient id="iYRfNAc" x1="9.021" x2="8.438" y1="9.063" y2="10.688" gradientUnits="userSpaceOnUse"><stop offset=".307" class="frltds1py"/><stop offset="1" class="uczhxfb1b"/></linearGradient><filter id="iacFVpb" width="5.11" height="7.527" x="17.702" y="13.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30340" stdDeviation=".5"/></filter><filter id="iqrlsHb" width="4.031" height="4.163" x="24.411" y="19.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30340" stdDeviation=".5"/></filter><filter id="iMRSXuc" width="3.938" height="4.156" x="11.171" y="16.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30340" stdDeviation=".5"/></filter><filter id="idDdtYF" width="4.252" height="4.569" x="6.781" y="20.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30340" stdDeviation=".5"/></filter><filter id="iv2iOIC" width="5.932" height="8.18" x="3.533" y="10.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30340" stdDeviation=".5"/></filter><filter id="iktrgzc" width="13.656" height="5.125" x="15.125" y="6.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30340" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ice" /></template>
<style>
.a-7awfpjp {
  stop-color: var(--svg-color--85f6ff, #85F6FF);
  stop-opacity: 0;
}

.anbwh8ydc {
  stop-color: var(--svg-color--3caeff, #3CAEFF);
  stop-opacity: 0;
}

.bl5me5bcz {
  d: path("M2.016 23.969V8.079c0-.415.125-.71.307-.93c0 0 10.426 3.942 13.707 4.843v18.035a1.6 1.6 0 0 1-.561-.074a11639 11639 0 0 0-12.156-4.437c-1-.36-1.339-1.203-1.297-1.547");
}

.bpcj5g73j {
  stop-color: var(--svg-color--6fb0e0, #6FB0E0);
  stop-opacity: 0;
}

.bth753b3f {
  d: path("M26.523 19.79c1.329-.118 1.631 1.795.454 2.116c-.546.15-1.225-.123-1.29-.64c-.074-.596.388-1.437.836-1.477");
}

.c-z2nqbfk {
  stop-color: var(--svg-color--458ef3, #458EF3);
}

.c0t8wndak {
  stop-color: var(--svg-color--70d9ea, #70D9EA);
}

.d9pi6lbab {
  d: path("M11.797 18.86c.025-.738.61-1.188.922-1.188c1.36.156 1.099 1.942.672 2.11c-.36.14-1.625 0-1.594-.923");
}

.dkh3y3boo {
  stop-color: var(--svg-color--86f7ff, #86F7FF);
}

.e3xoh7b4v {
  stop-color: var(--svg-color--82f3fe, #82F3FE);
  stop-opacity: 0;
}

.ekdgm7bqu {
  stop-color: var(--svg-color--b1ffff, #B1FFFF);
  stop-opacity: 0;
}

.evbvtof4w {
  stop-color: var(--svg-color--b0ffff, #B0FFFF);
}

.frltds1py {
  stop-color: var(--svg-color--4cbfe2, #4CBFE2);
}

.ft5dv1b6b {
  fill: none;
}

.g6vpfwagr {
  fill: var(--svg-color--268be7, #268BE7);
  d: path("M12.172 18.75c.025-.737.61-1.187.922-1.187c1.36.156 1.099 1.942.672 2.11c-.36.14-1.625 0-1.594-.923");
}

.g7g2kwb8x {
  stop-color: var(--svg-color--86f7ff, #86F7FF);
  stop-opacity: 0;
}

.gd2k6dpqt {
  stop-color: var(--svg-color--73abee, #73ABEE);
  stop-opacity: 0;
}

.gzcyrmb0s {
  d: path("M20.653 13.481c.831.81 1.65 2.173 1.847 3.214c.395 2.088-3.006 3.077-3.414 1.344c-.32-1.36.507-3.357 1.187-4.508c.1-.167.287-.161.38-.05");
}

.h43-8pbys {
  stop-color: var(--svg-color--82c6ff, #82C6FF);
}

.iltfjibvi {
  stop-color: var(--svg-color--86f8ff, #86F8FF);
}

.im8uuhbwk {
  stroke: var(--svg-color--73e7ff, #73E7FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M28.406 6.75L15.5 11.125");
}

.imyw3fujn {
  stop-color: var(--svg-color--4aa3ff, #4AA3FF);
}

.ioicbcb_a {
  stop-color: var(--svg-color--60cae4, #60CAE4);
  stop-opacity: 0;
}

.j5_zt8bwe {
  stop-color: var(--svg-color--a1d0f5, #A1D0F5);
}

.jb3s48bja {
  fill: var(--svg-color--52c3e4, #52C3E4);
  d: path("M2.016 23.969V8.079c0-1.032.78-1.329 1.265-1.532s11.666-4.266 12.016-4.39c.35-.126 1.052-.053 1.36 0C20.504 3.546 28.362 6.4 29 6.686c.637.288.901 1.047.953 1.391v15.766c0 .725-.547 1.36-.844 1.468l-12.593 4.641c-.263.088-.745.11-1.047 0a11639 11639 0 0 0-12.156-4.437c-1-.36-1.339-1.203-1.297-1.547");
}

.jpnznbcsu {
  stop-color: var(--svg-color--8dc1ea, #8DC1EA);
  stop-opacity: 0;
}

.js0gkfbjk {
  stop-color: var(--svg-color--48abff, #48ABFF);
}

.kyz9y2bhv {
  stop-color: var(--svg-color--70afe2, #70AFE2);
}

.l1hgkbcmq {
  stop-color: var(--svg-color--62c9ff, #62C9FF);
  stop-opacity: 0;
}

.l1pkrwe9v {
  fill: var(--svg-color--63a9ed, #63A9ED);
  d: path("M3.86 16c-.113-1.312 1.275-3.234 1.984-4.031c.203-.164.339-.163.531.047c.516.562 1.406 3.093 1.406 4.656c0 1.188-1.015 1.36-1.531 1.36c-.86 0-2.278-.72-2.39-2.032");
}

.m6sgcabjh {
  d: path("M7.375 23.547c-.213-1.013.563-1.625.938-1.625c1.484 0 1.462 2.176 1 2.437c-.463.262-1.726.2-1.938-.812");
}

.m8f2ww42p {
  fill: var(--svg-color--1d89e4, #1D89E4);
  d: path("M7.818 23.337c-.213-1.013.562-1.625.937-1.625c1.484 0 1.462 2.176 1 2.437c-.462.262-1.725.2-1.937-.812");
}

.mdvjo_zeu {
  stop-color: var(--svg-color--83f3fe, #83F3FE);
}

.n3l1ve9pr {
  stop-color: var(--svg-color--73b3e4, #73B3E4);
}

.nt7oa0bvh {
  stop-color: var(--svg-color--3fc0ff, #3FC0FF);
}

.o81qdw3ng {
  stop-color: var(--svg-color--51e5ff, #51E5FF);
}

.o9zpaghws {
  stop-color: var(--svg-color--52a7f3, #52A7F3);
}

.odkvdob0p {
  stop-color: var(--svg-color--5adbff, #5ADBFF);
}

.om214s09y {
  stop-color: var(--svg-color--8cf5ff, #8CF5FF);
}

.oywhlabhh {
  d: path("M3.86 16c-.113-1.312 1.275-3.234 1.984-4.031c.203-.164.339-.163.531.047c.516.562 1.406 3.093 1.406 4.656c0 1.188-1.015 1.36-1.531 1.36c-.86 0-2.278-.72-2.39-2.032");
}

.pdqx3244b {
  fill: var(--svg-color--39e, #39E);
  d: path("M4.543 16c-.113-1.312.764-3.234 1.473-4.031c.203-.164.338-.163.53.047c.516.562 1.919 3.093 1.919 4.656c0 1.188-1.016 1.36-1.531 1.36c-.86 0-2.279-.72-2.391-2.032");
}

.pr6xapbyn {
  stop-color: var(--svg-color--67c9ff, #67C9FF);
}

.s3yl7l3wi {
  stop-color: var(--svg-color--41a1ff, #41A1FF);
  stop-opacity: 0;
}

.svonbybgo {
  fill: var(--svg-color--78dcff, #78DCFF);
  d: path("M20.653 13.481c.831.81 1.65 2.173 1.847 3.214c.395 2.088-3.006 3.077-3.414 1.344c-.32-1.36.507-3.357 1.187-4.508c.1-.167.287-.161.38-.05");
}

.u-skrhpwv {
  d: path("M16.656 2.156C20.506 3.546 28.625 6.531 29 6.687c.375.157.531.423.672.61L16 12.14L2.266 7.203c.271-.324.726-.535 1.015-.656c.485-.203 11.666-4.266 12.016-4.39c.35-.126 1.052-.053 1.36 0");
}

.uczhxfb1b {
  stop-color: var(--svg-color--4abde1, #4ABDE1);
  stop-opacity: 0;
}

.umv9g3bdf {
  stop-color: var(--svg-color--78edff, #78EDFF);
  stop-opacity: 0;
}

.utfdhqint {
  stop-color: var(--svg-color--57e1ff, #57E1FF);
}

.was-zwi9f {
  fill: var(--svg-color--33b4ff, #33B4FF);
  d: path("M26.255 20.42c1.328-.118 1.63 1.796.453 2.117c-.546.149-1.225-.123-1.29-.64c-.074-.596.389-1.438.837-1.477");
}

.wci10qhco {
  stop-color: var(--svg-color--64aef1, #64AEF1);
}

.wpz-l5bng {
  stop-color: var(--svg-color--70def1, #70DEF1);
}

.ww8qu5h6i {
  fill: var(--svg-color--78dcff, #78DCFF);
  d: path("M20.151 14.381c.735.81 1.46 2.172 1.633 3.214c.35 2.088-2.658 3.077-3.019 1.344c-.283-1.36.449-3.357 1.05-4.508c.088-.167.254-.162.336-.05");
}

.x_beddboc {
  stop-color: var(--svg-color--59aff3, #59AFF3);
}

.xnssdkbld {
  stop-color: var(--svg-color--83c6ff, #83C6FF);
  stop-opacity: 0;
}

.xop139bzz {
  stop-color: var(--svg-color--49acff, #49ACFF);
}

.xum7-mb_l {
  d: path("m29.11 25.313l-12.594 4.64c-.126.042-.303.07-.486.074l.001-18.02l13.6-4.752c.195.3.322.604.322.823v15.766c0 .725-.547 1.36-.844 1.468");
}

.y1p3f-bbq {
  stop-color: var(--svg-color--78d5e6, #78D5E6);
  stop-opacity: 0;
}

.yaism030s {
  stop-color: var(--svg-color--85f6ff, #85F6FF);
}

.yko_63gjq {
  stop-color: var(--svg-color--51b0d9, #51B0D9);
}

.yrbamibps {
  stop-color: var(--svg-color--6dd1e1, #6DD1E1);
  stop-opacity: 0;
}

.z6iwvmpsb {
  stop-color: var(--svg-color--45c3ff, #45C3FF);
  stop-opacity: 0;
}

.zfgivjbdt {
  stop-color: var(--svg-color--66c5d6, #66C5D6);
}

.zgtx81gcf {
  fill: var(--svg-color--39b3ff, #39B3FF);
  d: path("M20.151 14.381c.735.81 1.46 2.172 1.633 3.214c.35 2.088-2.658 3.077-3.019 1.344c-.283-1.36.449-3.357 1.05-4.508c.088-.167.254-.162.336-.05");
}

.zncnru-kq {
  stop-color: var(--svg-color--affeff, #AFFEFF);
  stop-opacity: 0;
}

.zvnr-nb7n {
  stop-color: var(--svg-color--70c0ce, #70C0CE);
}

</style>
