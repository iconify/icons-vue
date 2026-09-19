<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ilDfrNo)"><path fill="url(#iGiIaae)" class="t0d6__bjf"/><path fill="url(#iT58GZb)" class="t0d6__bjf"/></g><path fill="url(#izfDC3c)" class="we0jtwbnt"/><path fill="url(#ifLzLYb)" class="we0jtwbnt"/><path fill="url(#i9ZqQwe)" class="we0jtwbnt"/><path fill="url(#iRfz3Md)" class="we0jtwbnt"/><path fill="url(#iXaXM9c)" class="we0jtwbnt"/><path fill="url(#igecIAd)" class="rldftr9qf"/><path fill="url(#inj2JDe)" class="rldftr9qf"/><path fill="url(#ioZdUEe)" class="rldftr9qf"/><path fill="url(#iAXuqke)" class="rldftr9qf"/><path fill="url(#iOMCEte)" class="rldftr9qf"/><path fill="url(#iOKuwte)" class="b6op6-bxn"/><path fill="url(#iVf7PlD)" class="b6op6-bxn"/><path fill="url(#izBfQ7b)" class="b6op6-bxn"/><path fill="url(#i09eg0d)" class="b6op6-bxn"/><path fill="url(#i0vggOb)" class="b6op6-bxn"/><path fill="url(#i45huQb)" class="qh3bvgbep"/><path fill="url(#iXRTBZB)" class="qh3bvgbep"/><path fill="url(#ixKt5ub)" class="qh3bvgbep"/><g filter="url(#ijesgFc)"><path fill="url(#iFoa3ze)" class="ulvc-_j_k"/></g><g filter="url(#iMwrxrd)"><path fill="url(#iy1xSbc)" class="hi4k0ebhx"/></g><g filter="url(#iUpAM3x)"><path fill="url(#ibcMQTd)" class="pb6ij46_z"/></g><g filter="url(#ieViqIc)"><path class="k4ja5l82m"/></g><path fill="url(#i0Gtr2d)" class="k5gvqeb_d"/><g filter="url(#ijm3Dcb)"><path stroke="url(#idtxlDd)" class="agpq_5boo"/></g><g filter="url(#i2SUTMg)"><path stroke="url(#iQDMHPb)" class="zhgaqebji"/></g><g filter="url(#iWxamve)"><path stroke="url(#imBQC6b)" class="ddszzrnfn"/></g><g filter="url(#iGYrSWd)"><path stroke="url(#ijlHb6A)" class="a1kj3tseh"/></g><g filter="url(#iaAWzli)"><path stroke="url(#ieQeArb)" class="okmjezbvj"/></g><path fill="url(#i7kHkWf)" class="t0d6__bjf"/><path fill="url(#iBswGie)" class="t0d6__bjf"/><path fill="url(#ify1hZd)" class="t0d6__bjf"/><path fill="url(#iXTsUCb)" class="t0d6__bjf"/><defs><linearGradient id="izfDC3c" x1="7.418" x2="7.524" y1="14.581" y2="12.476" gradientUnits="userSpaceOnUse"><stop offset=".043" class="n4twohluo"/><stop offset="1" class="bwenidc-p"/></linearGradient><linearGradient id="ifLzLYb" x1="3.717" x2="5.996" y1="12.112" y2="12.18" gradientUnits="userSpaceOnUse"><stop class="ri-5tqpkz"/><stop offset="1" class="tp2pvqbun"/></linearGradient><linearGradient id="i9ZqQwe" x1="10.647" x2="10.695" y1="15.04" y2="14.102" gradientUnits="userSpaceOnUse"><stop offset=".07" class="kvepmdbwe"/><stop offset="1" class="tre-1-b_h"/></linearGradient><linearGradient id="iXaXM9c" x1="15.836" x2="13.311" y1="14.105" y2="13.979" gradientUnits="userSpaceOnUse"><stop class="xu0642b-v"/><stop offset="1" class="nwo3vubbi"/></linearGradient><linearGradient id="igecIAd" x1="5.957" x2="5.988" y1="19.263" y2="16.845" gradientUnits="userSpaceOnUse"><stop offset=".043" class="uf1-nl_mx"/><stop offset="1" class="vkquyjbpw"/></linearGradient><linearGradient id="inj2JDe" x1="2.037" x2="4.237" y1="16.489" y2="16.57" gradientUnits="userSpaceOnUse"><stop class="k8i92ibsj"/><stop offset="1" class="tp2pvqbun"/></linearGradient><linearGradient id="ioZdUEe" x1="9.729" x2="9.722" y1="19.435" y2="18.475" gradientUnits="userSpaceOnUse"><stop offset=".07" class="kvepmdbwe"/><stop offset="1" class="tre-1-b_h"/></linearGradient><linearGradient id="iOMCEte" x1="15.755" x2="12.802" y1="18.478" y2="18.306" gradientUnits="userSpaceOnUse"><stop class="xu0642b-v"/><stop offset="1" class="nwo3vubbi"/></linearGradient><linearGradient id="iOKuwte" x1="7.553" x2="7.404" y1="23.668" y2="21.474" gradientUnits="userSpaceOnUse"><stop offset=".043" class="uf1-nl_mx"/><stop offset="1" class="vkquyjbpw"/></linearGradient><linearGradient id="iVf7PlD" x1="4.238" x2="6.099" y1="21.147" y2="21.211" gradientUnits="userSpaceOnUse"><stop class="k8i92ibsj"/><stop offset="1" class="tp2pvqbun"/></linearGradient><linearGradient id="izBfQ7b" x1="10.758" x2="10.748" y1="23.741" y2="23.144" gradientUnits="userSpaceOnUse"><stop offset=".07" class="kvepmdbwe"/><stop offset="1" class="tre-1-b_h"/></linearGradient><linearGradient id="i0vggOb" x1="15.837" x2="13.339" y1="22.955" y2="22.819" gradientUnits="userSpaceOnUse"><stop class="xu0642b-v"/><stop offset="1" class="nwo3vubbi"/></linearGradient><linearGradient id="i45huQb" x1="10.394" x2="10.573" y1="22.945" y2="24.722" gradientUnits="userSpaceOnUse"><stop offset=".169" class="vhpjw7-zt"/><stop offset=".828" class="er8-uubhv"/></linearGradient><linearGradient id="iXRTBZB" x1="7.108" x2="8.888" y1="26.106" y2="25.97" gradientUnits="userSpaceOnUse"><stop class="szjfkfbbd"/><stop offset="1" class="oe-5mt46b"/></linearGradient><linearGradient id="idtxlDd" x1="14.619" x2="13.939" y1="5.367" y2="10.604" gradientUnits="userSpaceOnUse"><stop class="rm3az35mv"/><stop offset="1" class="hsf9u999q"/></linearGradient><linearGradient id="iQDMHPb" x1="5.777" x2="5.773" y1="11.736" y2="12.173" gradientUnits="userSpaceOnUse"><stop class="jfke-qbbe"/><stop offset="1" class="d_oifybai"/></linearGradient><linearGradient id="imBQC6b" x1="3.513" x2="3.51" y1="15.952" y2="16.366" gradientUnits="userSpaceOnUse"><stop class="jfke-qbbe"/><stop offset="1" class="d_oifybai"/></linearGradient><linearGradient id="ijlHb6A" x1="6.148" x2="6.126" y1="20.433" y2="21.375" gradientUnits="userSpaceOnUse"><stop class="jfke-qbbe"/><stop offset="1" class="d_oifybai"/></linearGradient><linearGradient id="ieQeArb" x1="8.84" x2="8.838" y1="24.971" y2="25.224" gradientUnits="userSpaceOnUse"><stop class="jfke-qbbe"/><stop offset="1" class="d_oifybai"/></linearGradient><linearGradient id="i7kHkWf" x1="15.391" x2="15.299" y1="27.703" y2="25.812" gradientUnits="userSpaceOnUse"><stop class="dt33--rpq"/><stop offset="1" class="ihyj43bui"/></linearGradient><radialGradient id="iGiIaae" cx="0" cy="0" r="1" gradientTransform="rotate(170.048 14.094 8.764)scale(27.1022 28.0881)" gradientUnits="userSpaceOnUse"><stop class="fh582ztas"/><stop offset=".467" class="fvqrg5b_m"/></radialGradient><radialGradient id="iT58GZb" cx="0" cy="0" r="1" gradientTransform="matrix(23.24747 -5.8981 5.66878 22.3436 8.576 22.183)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="ch0s45-ku"/><stop offset=".943" class="bhz2sgb0b"/></radialGradient><radialGradient id="iRfz3Md" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46752 .41117 -.28996 -5.97146 12.173 12.476)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="x7hakgbcr"/><stop offset="1" class="aex39jb1t"/></radialGradient><radialGradient id="iAXuqke" cx="0" cy="0" r="1" gradientTransform="rotate(177.62 5.558 8.542)scale(9.9186 5.9904)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="x7hakgbcr"/><stop offset="1" class="aex39jb1t"/></radialGradient><radialGradient id="i09eg0d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.3793 .3742 -.2428 -5.43686 12.212 21.472)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="x7hakgbcr"/><stop offset="1" class="aex39jb1t"/></radialGradient><radialGradient id="ixKt5ub" cx="0" cy="0" r="1" gradientTransform="matrix(-8.3125 .47216 -1.021 -17.97483 15.281 25.156)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="kyfojnb1q"/><stop offset="1" class="adtziacfq"/></radialGradient><radialGradient id="iFoa3ze" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 -.0872 .07968 2.34138 14.948 14.75)" gradientUnits="userSpaceOnUse"><stop class="et6f-8o7s"/><stop offset="1" class="iv-7rkbjd"/></radialGradient><radialGradient id="iy1xSbc" cx="0" cy="0" r="1" gradientTransform="matrix(3.03125 -.09153 .07422 2.45803 14.43 18.894)" gradientUnits="userSpaceOnUse"><stop class="et6f-8o7s"/><stop offset="1" class="iv-7rkbjd"/></radialGradient><radialGradient id="ibcMQTd" cx="0" cy="0" r="1" gradientTransform="matrix(2.75258 -.0977 .09314 2.62374 15.132 23.344)" gradientUnits="userSpaceOnUse"><stop class="et6f-8o7s"/><stop offset="1" class="iv-7rkbjd"/></radialGradient><radialGradient id="i0Gtr2d" cx="0" cy="0" r="1" gradientTransform="rotate(-141.886 9.511 3.09)scale(5.46598 2.15008)" gradientUnits="userSpaceOnUse"><stop class="ro8hek2tt"/><stop offset=".251" class="ra4q9e1to"/><stop offset="1" class="plcvp2dil"/></radialGradient><radialGradient id="iBswGie" cx="0" cy="0" r="1" gradientTransform="rotate(67.003 -1.309 19.538)scale(15.0532 25.7656)" gradientUnits="userSpaceOnUse"><stop offset=".963" class="ihyj43bui"/><stop offset="1" class="dt33--rpq"/></radialGradient><radialGradient id="ify1hZd" cx="0" cy="0" r="1" gradientTransform="rotate(115.574 9.098 9.89)scale(5.5163 13.1955)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="z-fb9ib3h"/><stop offset="1" class="gq4ncu39j"/></radialGradient><radialGradient id="iXTsUCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 .15625 -.34108 3.06974 11.781 7.312)" gradientUnits="userSpaceOnUse"><stop class="rol3mx0hr"/><stop offset="1" class="r34io2k2i"/></radialGradient><filter id="ilDfrNo" width="28.465" height="24.039" x="1.817" y="3.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.439216 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7000"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.588235 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7000" result="effect2_innerShadow_20020_7000"/></filter><filter id="ijesgFc" width="3.163" height="3.347" x="14.648" y="13.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".15"/></filter><filter id="iMwrxrd" width="3.631" height="3.483" x="14.129" y="17.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".15"/></filter><filter id="iUpAM3x" width="3.353" height="3.679" x="14.836" y="21.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".15"/></filter><filter id="ieViqIc" width="6.246" height="16.916" x="13.694" y="10.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".75"/></filter><filter id="ijm3Dcb" width="12.792" height="9.153" x="13.198" y="4.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".625"/></filter><filter id="i2SUTMg" width="14.446" height="4.713" x="4.013" y="9.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".75"/></filter><filter id="iWxamve" width="16.246" height="4.69" x="1.813" y="13.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".75"/></filter><filter id="iGYrSWd" width="13.313" height="4.25" x="4.344" y="18.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".75"/></filter><filter id="iaAWzli" width="10.701" height="4.519" x="6.944" y="22.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7000" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-hand-medium-light" /></template>
<style>
.a1kj3tseh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.469 20.579h9.062");
}

.adtziacfq {
  stop-color: var(--svg-color--db9f88, #DB9F88);
}

.aex39jb1t {
  stop-color: var(--svg-color--dfa586, #DFA586);
}

.agpq_5boo {
  stroke-linecap: round;
  d: path("M14.948 6.19c1.48 1.397 5.871 4.074 9.292 5.652");
}

.b6op6-bxn {
  d: path("M5.1 19.275a2.406 2.406 0 0 0 1.4 4.393l9.813-.214v-4.179z");
}

.bhz2sgb0b {
  stop-color: var(--svg-color--ffd1aa, #FFD1AA);
}

.bwenidc-p {
  stop-color: var(--svg-color--d89881, #D89881);
  stop-opacity: 0;
}

.ch0s45-ku {
  stop-color: var(--svg-color--ffd1aa, #FFD1AA);
  stop-opacity: 0;
}

.d_oifybai {
  stop-color: var(--svg-color--e6b390, #E6B390);
  stop-opacity: 0;
}

.ddszzrnfn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m3.938 16.016l11.996.44");
}

.dt33--rpq {
  stop-color: var(--svg-color--b67395, #B67395);
}

.er8-uubhv {
  stop-color: var(--svg-color--b36e53, #B36E53);
  stop-opacity: 0;
}

.et6f-8o7s {
  stop-color: var(--svg-color--cc8b69, #CC8B69);
}

.fh582ztas {
  stop-color: var(--svg-color--ffcaa9, #FFCAA9);
}

.ft5dv1b6b {
  fill: none;
}

.fvqrg5b_m {
  stop-color: var(--svg-color--e3aa93, #E3AA93);
}

.gq4ncu39j {
  stop-color: var(--svg-color--f2c49a, #F2C49A);
  stop-opacity: 0;
}

.hi4k0ebhx {
  d: path("M17.46 20.335c-1.005-.887-2.44-1.084-3.03-1.072c1.537-.177 2.66-1.281 3.03-1.811z");
}

.hsf9u999q {
  stop-color: var(--svg-color--f5c49b, #F5C49B);
  stop-opacity: 0;
}

.ihyj43bui {
  stop-color: var(--svg-color--c17e8b, #C17E8B);
  stop-opacity: 0;
}

.iv-7rkbjd {
  stop-color: var(--svg-color--cc8b69, #CC8B69);
  stop-opacity: 0;
}

.jfke-qbbe {
  stop-color: var(--svg-color--e6b390, #E6B390);
}

.k4ja5l82m {
  stroke: var(--svg-color--dda48c, #DDA48C);
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.343 12.09c-1.146 2-2.663 7.438.437 13.188");
}

.k5gvqeb_d {
  d: path("M17.684 10.53L12.69 5.505q-.13.13-.243.282a2.536 2.536 0 0 0 .495 3.53l1.424 1.088z");
}

.k8i92ibsj {
  stop-color: var(--svg-color--d0987c, #D0987C);
}

.kvepmdbwe {
  stop-color: var(--svg-color--a85d36, #A85D36);
}

.kyfojnb1q {
  stop-color: var(--svg-color--db9f88, #DB9F88);
  stop-opacity: 0;
}

.n4twohluo {
  stop-color: var(--svg-color--d89881, #D89881);
}

.nwo3vubbi {
  stop-color: var(--svg-color--e3aa94, #E3AA94);
  stop-opacity: 0;
}

.oe-5mt46b {
  stop-color: var(--svg-color--d09984, #D09984);
  stop-opacity: 0;
}

.okmjezbvj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m9.069 25.278l6.45-.268");
}

.pb6ij46_z {
  d: path("M17.888 24.888c-1.038-1.052-2.16-1.434-2.752-1.422c1.538-.177 2.383-1.127 2.752-1.657z");
}

.plcvp2dil {
  stop-color: var(--svg-color--b67352, #B67352);
  stop-opacity: 0;
}

.qh3bvgbep {
  d: path("M7.87 23.642a2.406 2.406 0 0 0 1.736 4.16l6.91-.27c0-1.342-.852-3.157-.852-4.079z");
}

.r34io2k2i {
  stop-color: var(--svg-color--dca182, #DCA182);
  stop-opacity: 0;
}

.ra4q9e1to {
  stop-color: var(--svg-color--b67352, #B67352);
}

.ri-5tqpkz {
  stop-color: var(--svg-color--cf9c79, #CF9C79);
}

.rldftr9qf {
  d: path("M1.815 16.766a2.406 2.406 0 0 1 2.472-2.337c4.003.113 8.021.291 12.03.437v4.397H5.093l-.941-.024a2.406 2.406 0 0 1-2.337-2.473");
}

.rm3az35mv {
  stop-color: var(--svg-color--f5c49b, #F5C49B);
}

.ro8hek2tt {
  stop-color: var(--svg-color--a25b3d, #A25B3D);
}

.rol3mx0hr {
  stop-color: var(--svg-color--dca182, #DCA182);
}

.szjfkfbbd {
  stop-color: var(--svg-color--bb7d66, #BB7D66);
}

.t0d6__bjf {
  d: path("M4.29 14.44a2.406 2.406 0 0 0-.135 4.809l.945.026a2.406 2.406 0 0 0 1.4 4.393l1.37-.026a2.406 2.406 0 0 0 1.736 4.16l8.822-.335c1.33-.005 3.695-.15 5.76-1.004c3.267-1.207 5.595-4.34 5.595-8.016c0-3.715-2.38-6.876-5.702-8.054c-2.108-.889-4.283-2.362-5.205-2.987l-.06-.04l-2.82-2.1a2.536 2.536 0 0 0-3.054 4.05l1.424 1.089l-7.953-.344a2.385 2.385 0 0 0-1.378 4.4z");
}

.tp2pvqbun {
  stop-color: var(--svg-color--cf9c79, #CF9C79);
  stop-opacity: 0;
}

.tre-1-b_h {
  stop-color: var(--svg-color--c17e58, #C17E58);
  stop-opacity: 0;
}

.uf1-nl_mx {
  stop-color: var(--svg-color--c28281, #C28281);
}

.ulvc-_j_k {
  d: path("M17.51 16.123c-.835-.896-2.062-1.226-2.562-1.216c1.3-.15 2.25-1.083 2.563-1.531z");
}

.vhpjw7-zt {
  stop-color: var(--svg-color--ac6347, #AC6347);
}

.vkquyjbpw {
  stop-color: var(--svg-color--c28281, #C28281);
  stop-opacity: 0;
}

.we0jtwbnt {
  d: path("m6.181 10.062l10.136.423v4.404l-11.288-.433a2.384 2.384 0 0 1 1.152-4.394");
}

.x7hakgbcr {
  stop-color: var(--svg-color--dfa586, #DFA586);
  stop-opacity: 0;
}

.xu0642b-v {
  stop-color: var(--svg-color--e3aa94, #E3AA94);
}

.z-fb9ib3h {
  stop-color: var(--svg-color--f2c49a, #F2C49A);
}

.zhgaqebji {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m6.138 11.804l10.196.463");
}

</style>
