<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="i3pqU2S" width="10" height="9" x="17" y="21" maskUnits="userSpaceOnUse" style="mask-type:alpha"><circle class="aho7phl-k"/></mask><mask id="iCL1Xvc" width="9" height="9" x="19" y="15" maskUnits="userSpaceOnUse" style="mask-type:alpha"><circle class="sg0jdhbzy"/></mask><mask id="iJQZuMe" width="10" height="9" x="12" y="18" maskUnits="userSpaceOnUse" style="mask-type:alpha"><circle class="qy7-ikbnq"/></mask><mask id="ibpkLke" width="9" height="9" x="7" y="14" maskUnits="userSpaceOnUse" style="mask-type:alpha"><circle class="e0du92jtc"/></mask><mask id="i8bGXRc" width="9" height="9" x="19" y="9" maskUnits="userSpaceOnUse" style="mask-type:alpha"><circle class="v_32upb4m"/></mask><g class="ft5dv1b6b"><path fill="url(#iqn1ahd)" class="i0dcw5e-k"/><path fill="url(#iX5ag3r)" class="i0dcw5e-k"/><path fill="url(#iQh2SJr)" class="i0dcw5e-k"/><g filter="url(#iv0LNxe)"><path fill="url(#iH45utc)" class="t3nqlzlwj"/></g><g filter="url(#iz8OzZd)"><path fill="url(#ilK2Jsb)" class="gp63p4t3w"/></g><path fill="url(#iCazKMb)" clip-rule="evenodd" class="sbpp5xbup"/><g filter="url(#iNwDeSk)"><path stroke="url(#ikKVgvo)" class="spls9ntzq"/></g><g filter="url(#iiMcumb)" class="x7lr2sboj"><path stroke="url(#igFUHme)" class="pz_eaz0tg"/><path stroke="url(#itiwryd)" class="pz_eaz0tg"/></g><circle fill="url(#ixAGS5d)" class="aho7phl-k"/><circle fill="url(#iaU2lHb)" class="aho7phl-k"/><circle fill="url(#iQUwc3b)" class="aho7phl-k"/><g mask="url(#i3pqU2S)"><g filter="url(#iA637Jb)"><circle class="mpwxl5b7m"/></g><g filter="url(#id8b3bb)"><circle class="chswvibzl"/></g></g><circle fill="url(#ijrANwe)" class="sg0jdhbzy"/><circle fill="url(#iXdM3Ld)" class="sg0jdhbzy"/><circle fill="url(#iDTZcGe)" class="sg0jdhbzy"/><g mask="url(#iCL1Xvc)"><g filter="url(#iKIHXBc)"><circle class="vub5w26_i"/></g><g filter="url(#i2UnGeb)"><circle class="u1oeuvnrp"/></g></g><circle fill="url(#if7t2se)" class="qy7-ikbnq"/><circle fill="url(#ihhqeNd)" class="qy7-ikbnq"/><circle fill="url(#iwcJiNe)" class="qy7-ikbnq"/><g mask="url(#iJQZuMe)"><g filter="url(#iodS6Jj)"><circle class="ltmpwtblm"/></g><g filter="url(#iRzi6Xb)"><circle class="vub5w26_i"/></g></g><circle fill="url(#i6pgnyd)" class="e0du92jtc"/><circle fill="url(#i3Q6N5u)" class="e0du92jtc"/><circle fill="url(#i6VM0Fe)" class="e0du92jtc"/><g filter="url(#iKIHXBc)" mask="url(#ibpkLke)"><circle class="glxix1b1l"/></g><circle fill="url(#iiLR8me)" class="v_32upb4m"/><circle fill="url(#ibeYeFj)" class="v_32upb4m"/><circle fill="url(#iliROcb)" class="v_32upb4m"/><g filter="url(#iKIHXBc)" mask="url(#i8bGXRc)"><circle class="hxa7nufdb"/></g><circle fill="url(#iT15XEd)" class="ds11xk8qn"/><circle fill="url(#ij3eVee)" class="ds11xk8qn"/><defs><radialGradient id="ixAGS5d" cx="0" cy="0" r="1" gradientTransform="rotate(142.712 7.315 16.104)scale(5.4775)" gradientUnits="userSpaceOnUse"><stop class="gz6mnzbrh"/><stop offset=".474" class="rv0nqh93i"/><stop offset="1" class="pduvaccef"/></radialGradient><radialGradient id="iaU2lHb" cx="0" cy="0" r="1" gradientTransform="rotate(49.505 -15.257 36.781)scale(3.13336)" gradientUnits="userSpaceOnUse"><stop class="a8nmm2b0e"/><stop offset="1" class="n4tkegbov"/></radialGradient><radialGradient id="iQUwc3b" cx="0" cy="0" r="1" gradientTransform="rotate(-2.426 611.74 -375.032)scale(6.25215)" gradientUnits="userSpaceOnUse"><stop class="sll_zg-uo"/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="ijrANwe" cx="0" cy="0" r="1" gradientTransform="rotate(142.712 8.953 13.134)scale(5.4775)" gradientUnits="userSpaceOnUse"><stop class="gz6mnzbrh"/><stop offset=".474" class="rv0nqh93i"/><stop offset="1" class="pduvaccef"/></radialGradient><radialGradient id="iXdM3Ld" cx="0" cy="0" r="1" gradientTransform="rotate(49.505 -7.827 34.857)scale(3.13336)" gradientUnits="userSpaceOnUse"><stop class="a8nmm2b0e"/><stop offset="1" class="n4tkegbov"/></radialGradient><radialGradient id="iDTZcGe" cx="0" cy="0" r="1" gradientTransform="rotate(-2.426 462.977 -405.155)scale(6.25215)" gradientUnits="userSpaceOnUse"><stop class="sll_zg-uo"/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="if7t2se" cx="0" cy="0" r="1" gradientTransform="rotate(142.712 5.367 13.589)scale(5.4775)" gradientUnits="userSpaceOnUse"><stop class="gz6mnzbrh"/><stop offset=".474" class="rv0nqh93i"/><stop offset="1" class="pduvaccef"/></radialGradient><radialGradient id="ihhqeNd" cx="0" cy="0" r="1" gradientTransform="rotate(49.505 -14.15 29.666)scale(3.13336)" gradientUnits="userSpaceOnUse"><stop class="a8nmm2b0e"/><stop offset="1" class="n4tkegbov"/></radialGradient><radialGradient id="iwcJiNe" cx="0" cy="0" r="1" gradientTransform="rotate(-2.426 530.446 -258.114)scale(6.25215)" gradientUnits="userSpaceOnUse"><stop class="sll_zg-uo"/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="i6pgnyd" cx="0" cy="0" r="1" gradientTransform="rotate(142.712 3.467 10.654)scale(5.4775)" gradientUnits="userSpaceOnUse"><stop class="gz6mnzbrh"/><stop offset=".474" class="rv0nqh93i"/><stop offset="1" class="pduvaccef"/></radialGradient><radialGradient id="i3Q6N5u" cx="0" cy="0" r="1" gradientTransform="rotate(49.505 -12.278 21.98)scale(3.13336)" gradientUnits="userSpaceOnUse"><stop class="mlrs_7bib"/><stop offset="1" class="n4tkegbov"/></radialGradient><radialGradient id="i6VM0Fe" cx="0" cy="0" r="1" gradientTransform="rotate(-2.426 430.624 -137.687)scale(6.25215)" gradientUnits="userSpaceOnUse"><stop class="sll_zg-uo"/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iiLR8me" cx="0" cy="0" r="1" gradientTransform="rotate(142.712 10.018 9.977)scale(5.4775)" gradientUnits="userSpaceOnUse"><stop class="gz6mnzbrh"/><stop offset=".474" class="rv0nqh93i"/><stop offset="1" class="pduvaccef"/></radialGradient><radialGradient id="ibeYeFj" cx="0" cy="0" r="1" gradientTransform="rotate(49.505 -.978 31.7)scale(3.13336)" gradientUnits="userSpaceOnUse"><stop class="a8nmm2b0e"/><stop offset="1" class="n4tkegbov"/></radialGradient><radialGradient id="iliROcb" cx="0" cy="0" r="1" gradientTransform="rotate(-2.426 313.865 -408.313)scale(6.25215)" gradientUnits="userSpaceOnUse"><stop class="sll_zg-uo"/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iT15XEd" cx="0" cy="0" r="1" gradientTransform="rotate(142.712 6.765 10.114)scale(5.4775)" gradientUnits="userSpaceOnUse"><stop class="gz6mnzbrh"/><stop offset=".474" class="rv0nqh93i"/><stop offset="1" class="pduvaccef"/></radialGradient><radialGradient id="ij3eVee" cx="0" cy="0" r="1" gradientTransform="rotate(49.505 -6.261 26.563)scale(3.13336)" gradientUnits="userSpaceOnUse"><stop class="iaj3-pqfd"/><stop offset="1" class="n4tkegbov"/></radialGradient><filter id="iv0LNxe" width="13.639" height="7.195" x="1.806" y="7.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation=".5"/></filter><filter id="iz8OzZd" width="8.551" height="4.606" x="6.31" y="7.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation=".375"/></filter><filter id="iNwDeSk" width="2.576" height="10.886" x="14.457" y="2.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation=".2"/></filter><filter id="iiMcumb" width="2.398" height="10.888" x="14.888" y="1.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation=".25"/></filter><filter id="iA637Jb" width="16.197" height="16.197" x="8.835" y="14.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation="2"/></filter><filter id="id8b3bb" width="16.197" height="16.197" x="15" y="11.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation="2"/></filter><filter id="iKIHXBc" width="16.197" height="16.197" x="9.241" y="7.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation="2"/></filter><filter id="i2UnGeb" width="14.197" height="14.197" x="16" y="6.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation="1.5"/></filter><filter id="iodS6Jj" width="16.197" height="16.197" x="3.648" y="10.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation="2"/></filter><filter id="iRzi6Xb" width="12.197" height="12.197" x="11.242" y="9.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30687" stdDeviation="1"/></filter><linearGradient id="iqn1ahd" x1="2.143" x2="15.108" y1="9.991" y2="11.618" gradientUnits="userSpaceOnUse"><stop class="av-xlac9j"/><stop offset="1" class="g6dygytwt"/></linearGradient><linearGradient id="iX5ag3r" x1="6.553" x2="5.44" y1="10.795" y2="13.522" gradientUnits="userSpaceOnUse"><stop class="k05n1gbkm"/><stop offset="1" class="ni2mp6dkw"/></linearGradient><linearGradient id="iQh2SJr" x1="12.008" x2="15.108" y1="10.334" y2="11.333" gradientUnits="userSpaceOnUse"><stop class="k05n1gbkm"/><stop offset="1" class="p_qts-b_r"/></linearGradient><linearGradient id="iH45utc" x1="2.143" x2="15.108" y1="9.991" y2="11.618" gradientUnits="userSpaceOnUse"><stop class="xbk31wb_g"/><stop offset=".354" class="wka5oe1oh"/><stop offset="1" class="i_eunlbzh"/></linearGradient><linearGradient id="ilK2Jsb" x1="7.057" x2="14.109" y1="8.421" y2="10.796" gradientUnits="userSpaceOnUse"><stop class="g2au0jb2k"/><stop offset=".521" class="txwkf150v"/><stop offset="1" class="g2au0jb2k"/></linearGradient><linearGradient id="iCazKMb" x1="16.168" x2="16.168" y1="2.106" y2="11.601" gradientUnits="userSpaceOnUse"><stop class="xakhw8bck"/><stop offset="1" class="ieui3lbvt"/></linearGradient><linearGradient id="ikKVgvo" x1="15.746" x2="15.746" y1="3.101" y2="12.187" gradientUnits="userSpaceOnUse"><stop class="gkbecbc0b"/><stop offset="1" class="mdfuyhb5e"/></linearGradient><linearGradient id="igFUHme" x1="15.746" x2="15.746" y1="3.101" y2="12.187" gradientUnits="userSpaceOnUse"><stop class="o871qnbpn"/><stop offset=".307" class="ty9wjccze"/></linearGradient><linearGradient id="itiwryd" x1="16.112" x2="16.112" y1="2.951" y2="12.08" gradientUnits="userSpaceOnUse"><stop offset=".297" class="pfmk74ttr"/><stop offset="1" class="kpat9pljg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:grapes" /></template>
<style>
.a8nmm2b0e {
  stop-color: var(--svg-color--997ed0, #997ED0);
  stop-opacity: 0.6;
}

.aho7phl-k {
  cx: 21.957px;
  cy: 25.828px;
  r: 4.099px;
}

.av-xlac9j {
  stop-color: var(--svg-color--81b719, #81B719);
}

.chswvibzl {
  cx: 23.099px;
  cy: 19.503px;
  r: 4.099px;
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.ds11xk8qn {
  cx: 17.34px;
  cy: 15.405px;
  r: 4.099px;
}

.e0du92jtc {
  cx: 11.746px;
  cy: 18.373px;
  r: 4.099px;
}

.ft5dv1b6b {
  fill: none;
}

.g2au0jb2k {
  stop-color: var(--svg-color--b9e572, #B9E572);
  stop-opacity: 0.3;
}

.g6dygytwt {
  stop-color: var(--svg-color--82ca24, #82CA24);
}

.gkbecbc0b {
  stop-color: var(--svg-color--86bf1e, #86BF1E);
}

.glxix1b1l {
  cx: 17.34px;
  cy: 15.405px;
  r: 4.099px;
  fill: var(--svg-color--000, #000);
}

.gp63p4t3w {
  d: path("M14.111 10.86a5.335 5.335 0 0 0-6.74-2.482l-.311.126a5.685 5.685 0 0 1 6.484 2.586z");
}

.gz6mnzbrh {
  stop-color: var(--svg-color--764fbe, #764FBE);
}

.hxa7nufdb {
  cx: 17.34px;
  cy: 15.405px;
  r: 4.099px;
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.i_eunlbzh {
  stop-color: var(--svg-color--97c345, #97C345);
}

.i0dcw5e-k {
  d: path("M2.143 10.067L7.62 8.056a5.835 5.835 0 0 1 7.488 3.467l-5.477 2.01a5.835 5.835 0 0 1-7.488-3.466");
}

.iaj3-pqfd {
  stop-color: var(--svg-color--997ed0, #997ED0);
}

.ieui3lbvt {
  stop-color: var(--svg-color--91c627, #91C627);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.kpat9pljg {
  stop-color: var(--svg-color--b1e465, #B1E465);
}

.ltmpwtblm {
  cx: 11.746px;
  cy: 18.373px;
  r: 4.099px;
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.mdfuyhb5e {
  stop-color: var(--svg-color--92d72d, #92D72D);
}

.mlrs_7bib {
  stop-color: var(--svg-color--997ed0, #997ED0);
  stop-opacity: 0.2;
}

.mpwxl5b7m {
  cx: 16.934px;
  cy: 22.491px;
  r: 4.099px;
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
}

.n4tkegbov {
  stop-color: var(--svg-color--997ed0, #997ED0);
  stop-opacity: 0;
}

.ni2mp6dkw {
  stop-opacity: 0.12;
}

.o871qnbpn {
  stop-color: var(--svg-color--c8f584, #C8F584);
  stop-opacity: 0.8;
}

.p_qts-b_r {
  stop-opacity: 0.3;
}

.pduvaccef {
  stop-color: var(--svg-color--57198e, #57198E);
}

.pfmk74ttr {
  stop-color: var(--svg-color--b1e465, #B1E465);
  stop-opacity: 0;
}

.pz_eaz0tg {
  d: path("M16.375 2.692c-1.747 4.915.16 9.388.16 9.388");
}

.qy7-ikbnq {
  cx: 16.934px;
  cy: 22.491px;
  r: 4.099px;
}

.rv0nqh93i {
  stop-color: var(--svg-color--7542b7, #7542B7);
}

.sbpp5xbup {
  fill-rule: evenodd;
  d: path("M16.495 2.182a1 1 0 0 1 .543 1.306c-.673 1.63-1.488 6.038.834 10.096a1 1 0 1 1-1.736.993c-2.716-4.746-1.78-9.835-.947-11.852a1 1 0 0 1 1.306-.543");
}

.sg0jdhbzy {
  cx: 23.099px;
  cy: 19.503px;
  r: 4.099px;
}

.sll_zg-uo {
  stop-opacity: 0.5;
}

.spls9ntzq {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.134 3.101c-1.747 4.915 0 9.086 0 9.086");
}

.t3nqlzlwj {
  d: path("M7.793 8.525a5.335 5.335 0 0 1 6.652 2.709l-4.986 1.83a5.335 5.335 0 0 1-6.653-2.708z");
}

.txwkf150v {
  stop-color: var(--svg-color--b9e572, #B9E572);
  stop-opacity: 0.8;
}

.ty9wjccze {
  stop-color: var(--svg-color--c8f584, #C8F584);
  stop-opacity: 0;
}

.u1oeuvnrp {
  cx: 23.099px;
  cy: 13.188px;
  r: 4.099px;
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
}

.v_32upb4m {
  cx: 23.099px;
  cy: 13.188px;
  r: 4.099px;
}

.vub5w26_i {
  cx: 17.34px;
  cy: 15.405px;
  r: 4.099px;
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
}

.wka5oe1oh {
  stop-color: var(--svg-color--8fc21e, #8FC21E);
}

.x7lr2sboj {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.xakhw8bck {
  stop-color: var(--svg-color--7cb82b, #7CB82B);
}

.xbk31wb_g {
  stop-color: var(--svg-color--89bb1b, #89BB1B);
}

</style>
