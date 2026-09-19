<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#im5Ze5d)"><path fill="url(#iGGYAWb)" class="yp50xjbfj"/><path fill="url(#itRjr6b)" class="yp50xjbfj"/></g><path fill="url(#i72regd)" class="yp50xjbfj"/><path fill="url(#i7ZgSXh)" class="yp50xjbfj"/><path fill="url(#iwzTyGc)" class="yp50xjbfj"/><path fill="url(#iPaGWYc)" class="ihc2r9byb"/><path fill="url(#iABsM1c)" class="ihc2r9byb"/><path fill="url(#i77Ghud)" class="ihc2r9byb"/><path fill="url(#iI1tK1c)" class="ihc2r9byb"/><path fill="url(#iV20wFe)" class="ihc2r9byb"/><path fill="url(#iKI4kIe)" class="rxx6fcbyu"/><path fill="url(#iTaEUSd)" class="rxx6fcbyu"/><path fill="url(#iriygXb)" class="rxx6fcbyu"/><path fill="url(#iUXLTwc)" class="rxx6fcbyu"/><path fill="url(#ixFORve)" class="rxx6fcbyu"/><path fill="url(#iCfEJ2b)" class="h_lkk6x-n"/><path fill="url(#i4HVRac)" class="h_lkk6x-n"/><path fill="url(#i6Ouj7c)" class="h_lkk6x-n"/><path fill="url(#itwWBrd)" class="h_lkk6x-n"/><path fill="url(#i5aD8qQ)" class="h_lkk6x-n"/><path fill="url(#i7Ksm5c)" class="kxxb1lb2h"/><path fill="url(#ih6wOKc)" class="kxxb1lb2h"/><g filter="url(#i80naVd)"><path fill="url(#iMDSSie)" class="iyuwcfbkp"/></g><g filter="url(#iTHLs6O)"><path fill="url(#imDgnAe)" class="bshm7ab1f"/></g><g filter="url(#izHTSoe)"><path fill="url(#iMAGhUb)" class="gu-6dfbvd"/></g><g filter="url(#iTr2Kbd)"><path class="tkeybgguy"/></g><path fill="url(#is9UAue)" class="goy_v5zna"/><g filter="url(#ip2VDdd)"><path stroke="url(#iAII37s)" class="jnr3akbnv"/></g><g filter="url(#if4Qu9b)"><path stroke="url(#iWfRJUm)" class="v2mkq6gxe"/></g><g filter="url(#ixxgwmc)"><path stroke="url(#izGrz7c)" class="o9m5dmbbc"/></g><g filter="url(#iu2AySd)"><path stroke="url(#ibMMctb)" class="gcy-48b7i"/></g><g filter="url(#iqURYIe)"><path stroke="url(#ifQq4qF)" class="qkf9iz39r"/></g><defs><linearGradient id="i72regd" x1="15.273" x2="15.299" y1="27.696" y2="25.703" gradientUnits="userSpaceOnUse"><stop class="h2o8xccud"/><stop offset="1" class="t5ywdexfz"/></linearGradient><linearGradient id="iPaGWYc" x1="7.418" x2="7.524" y1="14.473" y2="12.368" gradientUnits="userSpaceOnUse"><stop offset=".043" class="nw90-cmxf"/><stop offset="1" class="kxpy61hjv"/></linearGradient><linearGradient id="iABsM1c" x1="3.717" x2="5.996" y1="12.004" y2="12.072" gradientUnits="userSpaceOnUse"><stop class="sd5fm_b6b"/><stop offset="1" class="w-n6dkbve"/></linearGradient><linearGradient id="i77Ghud" x1="10.669" x2="10.695" y1="14.72" y2="13.994" gradientUnits="userSpaceOnUse"><stop offset=".07" class="rx2xn_b5f"/><stop offset="1" class="n5951bcgk"/></linearGradient><linearGradient id="iV20wFe" x1="15.836" x2="13.311" y1="13.997" y2="13.871" gradientUnits="userSpaceOnUse"><stop class="moxhw_6pc"/><stop offset="1" class="uz116r7qu"/></linearGradient><linearGradient id="iKI4kIe" x1="5.903" x2="6.02" y1="18.847" y2="16.504" gradientUnits="userSpaceOnUse"><stop offset=".043" class="ew9adiufz"/><stop offset="1" class="eg1detdti"/></linearGradient><linearGradient id="iTaEUSd" x1="1.571" x2="4.237" y1="16.373" y2="16.467" gradientUnits="userSpaceOnUse"><stop class="nr5dyxbyw"/><stop offset="1" class="bs8m1k2vr"/></linearGradient><linearGradient id="iriygXb" x1="9.721" x2="9.741" y1="19.402" y2="18.729" gradientUnits="userSpaceOnUse"><stop offset=".07" class="rx2xn_b5f"/><stop offset="1" class="n5951bcgk"/></linearGradient><linearGradient id="ixFORve" x1="15.755" x2="12.802" y1="18.37" y2="18.198" gradientUnits="userSpaceOnUse"><stop class="moxhw_6pc"/><stop offset="1" class="uz116r7qu"/></linearGradient><linearGradient id="iCfEJ2b" x1="7.507" x2="7.487" y1="23.28" y2="21.364" gradientUnits="userSpaceOnUse"><stop offset=".043" class="ew9adiufz"/><stop offset="1" class="eg1detdti"/></linearGradient><linearGradient id="i4HVRac" x1="3.844" x2="6.099" y1="21.032" y2="21.106" gradientUnits="userSpaceOnUse"><stop class="nr5dyxbyw"/><stop offset="1" class="bs8m1k2vr"/></linearGradient><linearGradient id="i6Ouj7c" x1="10.736" x2="10.717" y1="23.785" y2="23.09" gradientUnits="userSpaceOnUse"><stop offset=".07" class="rx2xn_b5f"/><stop offset="1" class="n5951bcgk"/></linearGradient><linearGradient id="i5aD8qQ" x1="15.837" x2="13.339" y1="22.847" y2="22.711" gradientUnits="userSpaceOnUse"><stop class="moxhw_6pc"/><stop offset="1" class="uz116r7qu"/></linearGradient><linearGradient id="i7Ksm5c" x1="10.394" x2="10.573" y1="22.837" y2="24.614" gradientUnits="userSpaceOnUse"><stop offset=".169" class="u8ddxobwj"/><stop offset=".828" class="hyj9jzb0a"/></linearGradient><linearGradient id="ih6wOKc" x1="7.108" x2="8.784" y1="25.998" y2="25.946" gradientUnits="userSpaceOnUse"><stop class="j7g0nx-wo"/><stop offset="1" class="ix-t37cej"/></linearGradient><linearGradient id="iAII37s" x1="14.619" x2="13.939" y1="5.259" y2="10.495" gradientUnits="userSpaceOnUse"><stop class="n7ek59bhr"/><stop offset="1" class="noydr7b2o"/></linearGradient><linearGradient id="iWfRJUm" x1="5.777" x2="5.773" y1="11.628" y2="12.065" gradientUnits="userSpaceOnUse"><stop class="zfvqyjbnu"/><stop offset="1" class="ntil8ibhf"/></linearGradient><linearGradient id="izGrz7c" x1="3.513" x2="3.51" y1="15.844" y2="16.258" gradientUnits="userSpaceOnUse"><stop class="zfvqyjbnu"/><stop offset="1" class="ntil8ibhf"/></linearGradient><linearGradient id="ibMMctb" x1="6.148" x2="6.126" y1="20.325" y2="21.266" gradientUnits="userSpaceOnUse"><stop class="zfvqyjbnu"/><stop offset="1" class="ntil8ibhf"/></linearGradient><linearGradient id="ifQq4qF" x1="8.84" x2="8.838" y1="24.862" y2="25.115" gradientUnits="userSpaceOnUse"><stop class="zfvqyjbnu"/><stop offset="1" class="ntil8ibhf"/></linearGradient><radialGradient id="iGGYAWb" cx="0" cy="0" r="1" gradientTransform="rotate(170.048 14.099 8.71)scale(27.1022 28.0881)" gradientUnits="userSpaceOnUse"><stop class="bqczxvbwq"/><stop offset=".467" class="eze8grbpz"/></radialGradient><radialGradient id="itRjr6b" cx="0" cy="0" r="1" gradientTransform="matrix(23.24747 -5.8981 5.66878 22.3436 8.576 22.074)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="r6-gvnzjc"/><stop offset=".943" class="fmviwobxm"/></radialGradient><radialGradient id="i7ZgSXh" cx="0" cy="0" r="1" gradientTransform="rotate(67.003 -1.227 19.484)scale(15.0532 25.7656)" gradientUnits="userSpaceOnUse"><stop offset=".963" class="deu--4b7s"/><stop offset="1" class="h2o8xccud"/></radialGradient><radialGradient id="iwzTyGc" cx="0" cy="0" r="1" gradientTransform="rotate(115.574 9.132 9.837)scale(5.5163 13.1955)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="yhvuvydpv"/><stop offset="1" class="yg4-s3brc"/></radialGradient><radialGradient id="iI1tK1c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46752 .41117 -.28996 -5.97146 12.173 12.368)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="r-h8rsm3t"/><stop offset="1" class="syuavppvq"/></radialGradient><radialGradient id="iUXLTwc" cx="0" cy="0" r="1" gradientTransform="rotate(177.62 5.56 8.488)scale(9.9186 5.9904)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="r-h8rsm3t"/><stop offset="1" class="syuavppvq"/></radialGradient><radialGradient id="itwWBrd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.3793 .3742 -.2428 -5.43686 12.212 21.363)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="r-h8rsm3t"/><stop offset="1" class="syuavppvq"/></radialGradient><radialGradient id="iMDSSie" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 -.0872 .07968 2.34138 14.948 14.641)" gradientUnits="userSpaceOnUse"><stop class="wt7uzkbjq"/><stop offset="1" class="yp-p4bcqp"/></radialGradient><radialGradient id="imDgnAe" cx="0" cy="0" r="1" gradientTransform="matrix(3.03125 -.09153 .07422 2.45803 14.43 18.785)" gradientUnits="userSpaceOnUse"><stop class="wt7uzkbjq"/><stop offset="1" class="yp-p4bcqp"/></radialGradient><radialGradient id="iMAGhUb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75258 -.09773 .09316 2.62374 15.136 23.24)" gradientUnits="userSpaceOnUse"><stop class="wt7uzkbjq"/><stop offset="1" class="yp-p4bcqp"/></radialGradient><radialGradient id="is9UAue" cx="0" cy="0" r="1" gradientTransform="rotate(-141.886 9.493 3.036)scale(5.46598 2.15008)" gradientUnits="userSpaceOnUse"><stop class="sayspsbii"/><stop offset=".251" class="u45-6y-vy"/><stop offset="1" class="yw01km_ew"/></radialGradient><filter id="im5Ze5d" width="28.465" height="24.039" x="1.817" y="3.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.4 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6959"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.439216 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6959" result="effect2_innerShadow_20020_6959"/></filter><filter id="i80naVd" width="3.163" height="3.347" x="14.648" y="12.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".15"/></filter><filter id="iTHLs6O" width="3.631" height="3.483" x="14.129" y="17.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".15"/></filter><filter id="izHTSoe" width="3.353" height="3.679" x="14.836" y="21.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".15"/></filter><filter id="iTr2Kbd" width="6.246" height="16.916" x="13.694" y="10.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".75"/></filter><filter id="ip2VDdd" width="12.792" height="9.153" x="13.198" y="4.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".625"/></filter><filter id="if4Qu9b" width="14.446" height="4.713" x="4.013" y="9.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".75"/></filter><filter id="ixxgwmc" width="16.246" height="4.69" x="1.813" y="13.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".75"/></filter><filter id="iu2AySd" width="13.313" height="4.25" x="4.344" y="18.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".75"/></filter><filter id="iqURYIe" width="10.701" height="4.519" x="6.944" y="22.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6959" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-hand-medium" /></template>
<style>
.bqczxvbwq {
  stop-color: var(--svg-color--cba38d, #CBA38D);
}

.bs8m1k2vr {
  stop-color: var(--svg-color--936f5d, #936F5D);
  stop-opacity: 0;
}

.bshm7ab1f {
  d: path("M17.46 20.227c-1.005-.887-2.44-1.084-3.03-1.072c1.537-.177 2.66-1.281 3.03-1.811z");
}

.deu--4b7s {
  stop-color: var(--svg-color--9a5a88, #9A5A88);
  stop-opacity: 0;
}

.eg1detdti {
  stop-color: var(--svg-color--945e6e, #945E6E);
  stop-opacity: 0;
}

.ew9adiufz {
  stop-color: var(--svg-color--945e6e, #945E6E);
}

.eze8grbpz {
  stop-color: var(--svg-color--af8278, #AF8278);
}

.fmviwobxm {
  stop-color: var(--svg-color--d0a98c, #D0A98C);
}

.ft5dv1b6b {
  fill: none;
}

.gcy-48b7i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.469 20.47h9.062");
}

.goy_v5zna {
  d: path("M17.684 10.422L12.69 5.397q-.13.13-.243.282a2.536 2.536 0 0 0 .495 3.53l1.424 1.088z");
}

.gu-6dfbvd {
  d: path("M17.888 24.78c-1.038-1.052-2.16-1.434-2.752-1.422c1.538-.177 2.383-1.127 2.752-1.657z");
}

.h_lkk6x-n {
  d: path("M5.1 19.167a2.406 2.406 0 0 0 1.4 4.393l9.813-.215v-4.178z");
}

.h2o8xccud {
  stop-color: var(--svg-color--9a5a88, #9A5A88);
}

.hyj9jzb0a {
  stop-color: var(--svg-color--825948, #825948);
  stop-opacity: 0;
}

.ihc2r9byb {
  d: path("m6.181 9.954l10.136.423v4.404l-11.288-.433A2.384 2.384 0 0 1 6.18 9.954");
}

.ix-t37cej {
  stop-color: var(--svg-color--8a6356, #8A6356);
  stop-opacity: 0;
}

.iyuwcfbkp {
  d: path("M17.51 16.015c-.835-.896-2.062-1.226-2.562-1.216c1.3-.15 2.25-1.083 2.563-1.531z");
}

.j7g0nx-wo {
  stop-color: var(--svg-color--9c7368, #9C7368);
}

.jnr3akbnv {
  stroke-linecap: round;
  d: path("M14.948 6.081c1.48 1.398 5.871 4.075 9.292 5.654");
}

.kxpy61hjv {
  stop-color: var(--svg-color--956067, #956067);
  stop-opacity: 0;
}

.kxxb1lb2h {
  d: path("M7.87 23.534a2.406 2.406 0 0 0 1.736 4.16l6.91-.27c0-1.342-.852-3.157-.852-4.079z");
}

.moxhw_6pc {
  stop-color: var(--svg-color--b08279, #B08279);
}

.n5951bcgk {
  stop-color: var(--svg-color--7e5445, #7E5445);
  stop-opacity: 0;
}

.n7ek59bhr {
  stop-color: var(--svg-color--c0987a, #C0987A);
}

.noydr7b2o {
  stop-color: var(--svg-color--c0987a, #C0987A);
  stop-opacity: 0;
}

.nr5dyxbyw {
  stop-color: var(--svg-color--936f5d, #936F5D);
}

.ntil8ibhf {
  stop-color: var(--svg-color--af8870, #AF8870);
  stop-opacity: 0;
}

.nw90-cmxf {
  stop-color: var(--svg-color--956067, #956067);
}

.o9m5dmbbc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m3.938 15.908l11.996.44");
}

.qkf9iz39r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m9.069 25.17l6.45-.269");
}

.r-h8rsm3t {
  stop-color: var(--svg-color--9c7867, #9C7867);
  stop-opacity: 0;
}

.r6-gvnzjc {
  stop-color: var(--svg-color--d0a98c, #D0A98C);
  stop-opacity: 0;
}

.rx2xn_b5f {
  stop-color: var(--svg-color--4c2d1c, #4C2D1C);
}

.rxx6fcbyu {
  d: path("M1.815 16.658a2.406 2.406 0 0 1 2.472-2.337c4.003.113 8.021.291 12.03.436v4.398H5.093l-.941-.025a2.406 2.406 0 0 1-2.337-2.472");
}

.sayspsbii {
  stop-color: var(--svg-color--4f3124, #4F3124);
}

.sd5fm_b6b {
  stop-color: var(--svg-color--926f5d, #926F5D);
}

.syuavppvq {
  stop-color: var(--svg-color--9c7867, #9C7867);
}

.t5ywdexfz {
  stop-color: var(--svg-color--a7737b, #A7737B);
  stop-opacity: 0;
}

.tkeybgguy {
  stroke: var(--svg-color--a67c6e, #A67C6E);
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.343 11.983c-1.146 2-2.663 7.437.437 13.187");
}

.u45-6y-vy {
  stop-color: var(--svg-color--6c483d, #6C483D);
}

.u8ddxobwj {
  stop-color: var(--svg-color--643f32, #643F32);
}

.uz116r7qu {
  stop-color: var(--svg-color--b08279, #B08279);
  stop-opacity: 0;
}

.v2mkq6gxe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m6.138 11.696l10.196.463");
}

.w-n6dkbve {
  stop-color: var(--svg-color--926f5d, #926F5D);
  stop-opacity: 0;
}

.wt7uzkbjq {
  stop-color: var(--svg-color--92675b, #92675B);
}

.yg4-s3brc {
  stop-color: var(--svg-color--c39c7d, #C39C7D);
  stop-opacity: 0;
}

.yhvuvydpv {
  stop-color: var(--svg-color--c39c7d, #C39C7D);
}

.yp-p4bcqp {
  stop-color: var(--svg-color--92675b, #92675B);
  stop-opacity: 0;
}

.yp50xjbfj {
  d: path("M4.29 14.331a2.406 2.406 0 0 0-.135 4.81l.945.026a2.406 2.406 0 0 0 1.4 4.393l1.37-.026a2.406 2.406 0 0 0 1.736 4.16l8.822-.335c1.33-.005 3.695-.15 5.76-1.004c3.267-1.207 5.595-4.34 5.595-8.016c0-3.715-2.38-6.876-5.702-8.054c-2.108-.889-4.283-2.362-5.205-2.987l-.06-.041l-2.82-2.098a2.536 2.536 0 0 0-3.054 4.05l1.424 1.088l-7.953-.344a2.385 2.385 0 0 0-1.378 4.4z");
}

.yw01km_ew {
  stop-color: var(--svg-color--8e645d, #8E645D);
  stop-opacity: 0;
}

.zfvqyjbnu {
  stop-color: var(--svg-color--af8870, #AF8870);
}

</style>
