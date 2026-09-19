<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iUrno6b)" class="qzjui6lvn"/><path fill="url(#ibxcmoc)" class="qzjui6lvn"/><path fill="url(#i8WMXxe)" class="qzjui6lvn"/><path fill="url(#iBgwzyd)" class="qzjui6lvn"/><path fill="url(#iUFz4bf)" class="qzjui6lvn"/><path fill="url(#ikXuwrc)" class="ouu82n3my"/><path fill="url(#iIR2PFd)" class="ouu82n3my"/><path fill="url(#iLW9Vvd)" class="q_vr3ubju"/><path fill="url(#iYG4ddb)" class="q_vr3ubju"/><path fill="url(#iSE5Vvd)" class="q_vr3ubju"/><path fill="url(#iZOmIDd)" class="b3kj906zw"/><path fill="url(#i3ELjIc)" class="b3kj906zw"/><path fill="url(#i6cmTib)" class="rxcwmtb7f"/><path fill="url(#iiPTJVC)" class="rxcwmtb7f"/><path fill="url(#iBgP9Lc)" class="rxcwmtb7f"/><path fill="url(#ijx28Ec)" class="rxcwmtb7f"/><path fill="url(#iMCsTde)" class="rxcwmtb7f"/><path fill="url(#iwah3ye)" class="rxcwmtb7f"/><path fill="url(#ig774Fe)" class="rxcwmtb7f"/><path fill="url(#i4VdqpM)" class="rxcwmtb7f"/><path fill="url(#igAedbb)" class="rxcwmtb7f"/><g filter="url(#iyfAqxd)"><ellipse fill="url(#i80HrBe)" transform="rotate(-21.053 21.148 14.564)" class="xv1r2q1-x"/></g><g filter="url(#ibHoUld)"><path class="afhbcynns"/></g><g filter="url(#iXKQZrc)"><path class="j0yo5obsm"/></g><path fill="url(#i9rkl2W)" class="pmm9hfe9v"/><path fill="url(#iFY19Dd)" class="pmm9hfe9v"/><path fill="url(#ihqPaVd)" class="pmm9hfe9v"/><path fill="url(#i2IFJQd)" class="hv1jxepua"/><path fill="url(#iZKOfkd)" class="hv1jxepua"/><path fill="url(#ijoAA5d)" class="hv1jxepua"/><path fill="url(#iKTmxsd)" class="nm0l6ur5i"/><path fill="url(#i5skuSc)" class="nm0l6ur5i"/><path fill="url(#icVA5BK)" class="nm0l6ur5i"/><path fill="url(#iTBwHbe)" class="li_hsbcba"/><path fill="url(#iIJZyPb)" class="nm0l6ur5i"/><g filter="url(#il4Fvnc)"><rect class="u0s5vz57c"/></g><g filter="url(#iTebfoe)"><rect class="eqw_fp1qd"/></g><defs><radialGradient id="ibxcmoc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96875 1.5 -2.85796 -3.75107 28.422 5.928)" gradientUnits="userSpaceOnUse"><stop class="tnumr2b3r"/><stop offset="1" class="veh5liige"/></radialGradient><radialGradient id="i8WMXxe" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 -5 7.53 5.6475 22.36 11.928)" gradientUnits="userSpaceOnUse"><stop class="iw2rm7bbu"/><stop offset="1" class="whx21hb2m"/></radialGradient><radialGradient id="ikXuwrc" cx="0" cy="0" r="1" gradientTransform="matrix(4.3125 -1.375 2.7846 8.73353 22.547 7.991)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ck9a4nbpr"/><stop offset="1" class="uqa0vwigp"/></radialGradient><radialGradient id="iIR2PFd" cx="0" cy="0" r="1" gradientTransform="rotate(39.679 1.746 30.573)scale(6.3342)" gradientUnits="userSpaceOnUse"><stop class="y3qyz048x"/><stop offset="1" class="q5nca1bec"/></radialGradient><radialGradient id="iYG4ddb" cx="0" cy="0" r="1" gradientTransform="rotate(125.628 5.593 5.316)scale(4.61358 8.7903)" gradientUnits="userSpaceOnUse"><stop class="tnumr2b3r"/><stop offset="1" class="veh5liige"/></radialGradient><radialGradient id="iZOmIDd" cx="0" cy="0" r="1" gradientTransform="matrix(3 1.125 -2.36896 6.31725 5.173 8.116)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ck9a4nbpr"/><stop offset="1" class="uqa0vwigp"/></radialGradient><radialGradient id="i3ELjIc" cx="0" cy="0" r="1" gradientTransform="matrix(4.40626 1.46875 -2.65 7.95 5.048 9.147)" gradientUnits="userSpaceOnUse"><stop class="yibhjabmb"/><stop offset=".462" class="ymtsqt8-z"/></radialGradient><radialGradient id="iiPTJVC" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.125 12.2503 0 15.99 28.054)" gradientUnits="userSpaceOnUse"><stop class="hmjhhkbfn"/><stop offset="1" class="pay4xcbiv"/></radialGradient><radialGradient id="iBgP9Lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.625 16.6198 0 15.99 30.929)" gradientUnits="userSpaceOnUse"><stop class="hmjhhkbfn"/><stop offset="1" class="pay4xcbiv"/></radialGradient><radialGradient id="ijx28Ec" cx="0" cy="0" r="1" gradientTransform="rotate(162.316 13.304 8.658)scale(13.5792 14.4646)" gradientUnits="userSpaceOnUse"><stop class="yjv2hiy2z"/><stop offset="1" class="krnte338w"/></radialGradient><radialGradient id="iMCsTde" cx="0" cy="0" r="1" gradientTransform="matrix(7.6875 3.5 -5.05399 11.10074 7.297 14.991)" gradientUnits="userSpaceOnUse"><stop class="z7494hb4b"/><stop offset="1" class="uzsvhebjb"/></radialGradient><radialGradient id="iwah3ye" cx="0" cy="0" r="1" gradientTransform="rotate(61.771 1.447 10.467)scale(6.739 14.9033)" gradientUnits="userSpaceOnUse"><stop class="z7494hb4b"/><stop offset="1" class="uzsvhebjb"/></radialGradient><radialGradient id="i80HrBe" cx="0" cy="0" r="1" gradientTransform="rotate(-84.75 22.19 -3.981)scale(15.364 7.51662)" gradientUnits="userSpaceOnUse"><stop class="yjv2hiy2z"/><stop offset="1" class="krnte338w"/></radialGradient><radialGradient id="ihqPaVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.44693 -1.6785 1.816 -.48354 10.128 16.841)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="ijoAA5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.44693 -1.6785 1.816 -.48354 22.074 16.841)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iKTmxsd" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.16 17.52)scale(8.44503)" gradientUnits="userSpaceOnUse"><stop class="f838f1b7h"/><stop offset=".821" class="a15_srbjb"/></radialGradient><radialGradient id="i5skuSc" cx="0" cy="0" r="1" gradientTransform="rotate(134.256 4.809 12.882)scale(1.70162 2.14052)" gradientUnits="userSpaceOnUse"><stop class="qy1bkabkd"/><stop offset="1" class="mv7xnybgj"/></radialGradient><radialGradient id="iTBwHbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.44503 -2.75803 0 17.422 22.679)" gradientUnits="userSpaceOnUse"><stop class="qe8pq8nln"/><stop offset="1" class="qj09u6b0x"/></radialGradient><radialGradient id="iIJZyPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.5781 -7.47202 0 15.94 13.71)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a3glpobeo"/><stop offset="1" class="kb86ahb-u"/></radialGradient><linearGradient id="iUrno6b" x1="22.36" x2="27.852" y1="11.803" y2="3.921" gradientUnits="userSpaceOnUse"><stop class="ci2k9ob4p"/><stop offset="1" class="mcj-veiwd"/></linearGradient><linearGradient id="iBgwzyd" x1="27.141" x2="26.422" y1="14.803" y2="11.835" gradientUnits="userSpaceOnUse"><stop class="cc_mi9bmg"/><stop offset="1" class="whx21hb2m"/></linearGradient><linearGradient id="iUFz4bf" x1="18.891" x2="20.485" y1="3.428" y2="5.366" gradientUnits="userSpaceOnUse"><stop offset=".089" class="cc_mi9bmg"/><stop offset="1" class="whx21hb2m"/></linearGradient><linearGradient id="iLW9Vvd" x1="4.61" x2="11.735" y1="14.241" y2="3.163" gradientUnits="userSpaceOnUse"><stop class="crdewebed"/><stop offset="1" class="hejxytbjx"/></linearGradient><linearGradient id="iSE5Vvd" x1="7.485" x2="5.86" y1="15.763" y2="11.741" gradientUnits="userSpaceOnUse"><stop class="r8u_a5l0w"/><stop offset="1" class="ky-lwibos"/></linearGradient><linearGradient id="i6cmTib" x1="16" x2="16" y1="6.052" y2="28.054" gradientUnits="userSpaceOnUse"><stop class="zhyo0649t"/><stop offset="1" class="a0tsucbva"/></linearGradient><linearGradient id="ig774Fe" x1="4.344" x2="5.657" y1="16.663" y2="17.116" gradientUnits="userSpaceOnUse"><stop class="wkn68tbkw"/><stop offset="1" class="vxfpfdb8n"/></linearGradient><linearGradient id="i4VdqpM" x1="14.985" x2="14.985" y1="29.616" y2="27.054" gradientUnits="userSpaceOnUse"><stop class="wkn68tbkw"/><stop offset=".791" class="vxfpfdb8n"/></linearGradient><linearGradient id="igAedbb" x1="19.172" x2="18.047" y1="4.704" y2="6.366" gradientUnits="userSpaceOnUse"><stop class="wkn68tbkw"/><stop offset="1" class="vxfpfdb8n"/></linearGradient><linearGradient id="i9rkl2W" x1="10.716" x2="9.849" y1="16.422" y2="16.422" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iFY19Dd" x1="10.949" x2="10.949" y1="17.952" y2="16.539" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="i2IFJQd" x1="22.661" x2="21.795" y1="16.422" y2="16.422" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iZKOfkd" x1="22.895" x2="22.895" y1="17.952" y2="16.539" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="icVA5BK" x1="11.391" x2="15.704" y1="23.585" y2="23.585" gradientUnits="userSpaceOnUse"><stop class="qp7tz9hrg"/><stop offset=".37" class="inw6gscdk"/><stop offset="1" class="qp7tz9hrg"/></linearGradient><filter id="iyfAqxd" width="16.777" height="21.87" x="12.76" y="3.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4187" stdDeviation="1.5"/></filter><filter id="ibHoUld" width="2.43" height="3.834" x="20.338" y="14.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4187" stdDeviation=".25"/></filter><filter id="iXKQZrc" width="2.43" height="3.834" x="8.462" y="14.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4187" stdDeviation=".25"/></filter><filter id="il4Fvnc" width="1.422" height="3.009" x="9.469" y="15.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4187" stdDeviation=".25"/></filter><filter id="iTebfoe" width="1.422" height="3.009" x="21.413" y="15.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4187" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:koala" /></template>
<style>
.a0tsucbva {
  stop-color: var(--svg-color--9a93a7, #9A93A7);
}

.a15_srbjb {
  stop-color: var(--svg-color--3c2f49, #3C2F49);
}

.a3glpobeo {
  stop-color: var(--svg-color--4b4155, #4B4155);
  stop-opacity: 0;
}

.afhbcynns {
  fill: var(--svg-color--8c8c95, #8C8C95);
  d: path("M21.553 18.09a.717.717 0 0 1-.715-.714V15.97c0-.393.322-.714.715-.714s.715.321.715.714v1.405a.717.717 0 0 1-.715.715");
}

.b3kj906zw {
  d: path("M8.84 14.853c-2.68 0-4.88-2.19-4.88-4.88c0-2.68 2.19-4.88 4.88-4.88c2.68 0 4.88 2.19 4.88 4.88c0 2.68-2.2 4.88-4.88 4.88");
}

.cc_mi9bmg {
  stop-color: var(--svg-color--888691, #888691);
}

.ci2k9ob4p {
  stop-color: var(--svg-color--9c9ea1, #9C9EA1);
}

.ck9a4nbpr {
  stop-color: var(--svg-color--828185, #828185);
}

.crdewebed {
  stop-color: var(--svg-color--86848d, #86848D);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.eqw_fp1qd {
  width: 0.422px;
  height: 2.009px;
  x: 21.913px;
  y: 15.575px;
  fill: var(--svg-color--76676a, #76676A);
  rx: 0.211px;
}

.f838f1b7h {
  stop-color: var(--svg-color--735c88, #735C88);
}

.ft5dv1b6b {
  fill: none;
}

.hejxytbjx {
  stop-color: var(--svg-color--bcbec0, #BCBEC0);
}

.hmjhhkbfn {
  stop-color: var(--svg-color--726387, #726387);
}

.hv1jxepua {
  d: path("M21.913 18.09a.75.75 0 0 1-.748-.747v-1.47a.75.75 0 0 1 .748-.748a.75.75 0 0 1 .748.748v1.47a.75.75 0 0 1-.748.748");
}

.inw6gscdk {
  stop-color: var(--svg-color--5a5163, #5A5163);
}

.iw2rm7bbu {
  stop-color: var(--svg-color--93919c, #93919C);
}

.j0yo5obsm {
  fill: var(--svg-color--8c8c95, #8C8C95);
  d: path("M9.676 18.09a.717.717 0 0 1-.714-.714V15.97a.716.716 0 0 1 1.429 0v1.405a.717.717 0 0 1-.715.715");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.kb86ahb-u {
  stop-color: var(--svg-color--60566a, #60566A);
}

.krnte338w {
  stop-color: var(--svg-color--e0e1e6, #E0E1E6);
  stop-opacity: 0;
}

.ky-lwibos {
  stop-color: var(--svg-color--77767f, #77767F);
  stop-opacity: 0;
}

.li_hsbcba {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M15.94 26.124a3.71 3.71 0 0 1-3.7-3.7v-2.74c0-2.04 1.67-3.7 3.7-3.7c2.04 0 3.7 1.67 3.7 3.7v2.74c0 2.03-1.67 3.7-3.7 3.7");
}

.mcj-veiwd {
  stop-color: var(--svg-color--b9babe, #B9BABE);
}

.mv7xnybgj {
  stop-color: var(--svg-color--7f6e91, #7F6E91);
  stop-opacity: 0;
}

.nm0l6ur5i {
  d: path("M15.94 26.124a3.71 3.71 0 0 1-3.7-3.7v-2.74c0-2.04 1.67-3.7 3.7-3.7c2.04 0 3.7 1.67 3.7 3.7v2.74c0 2.03-1.67 3.7-3.7 3.7");
}

.ouu82n3my {
  d: path("M23.12 14.853c-2.68 0-4.88-2.19-4.88-4.88c0-2.68 2.19-4.88 4.88-4.88c2.68 0 4.88 2.19 4.88 4.88c0 2.68-2.2 4.88-4.88 4.88");
}

.pay4xcbiv {
  stop-color: var(--svg-color--7d6f90, #7D6F90);
  stop-opacity: 0;
}

.pmm9hfe9v {
  d: path("M9.967 18.09a.75.75 0 0 1-.748-.747v-1.47a.75.75 0 0 1 .748-.748a.75.75 0 0 1 .749.748v1.47a.75.75 0 0 1-.749.748");
}

.q_vr3ubju {
  d: path("M8.41 15.763c-3.46 0-6.3-2.83-6.3-6.3c0-3.46 2.84-6.3 6.3-6.3c3.47 0 6.3 2.84 6.3 6.3c0 3.47-2.83 6.3-6.3 6.3");
}

.q5nca1bec {
  stop-color: var(--svg-color--878688, #878688);
  stop-opacity: 0;
}

.qe8pq8nln {
  stop-color: var(--svg-color--6e6379, #6E6379);
}

.qj09u6b0x {
  stop-color: var(--svg-color--6e6379, #6E6379);
  stop-opacity: 0;
}

.qp7tz9hrg {
  stop-color: var(--svg-color--5a5163, #5A5163);
  stop-opacity: 0;
}

.qy1bkabkd {
  stop-color: var(--svg-color--7f6e91, #7F6E91);
}

.qzjui6lvn {
  d: path("M23.59 15.763c-3.47 0-6.3-2.84-6.3-6.3c0-3.47 2.84-6.3 6.3-6.3c3.47 0 6.3 2.84 6.3 6.3c0 3.47-2.83 6.3-6.3 6.3");
}

.r8u_a5l0w {
  stop-color: var(--svg-color--77767f, #77767F);
}

.rxcwmtb7f {
  d: path("m27.39 18.124l-2.52-7.28l-.01.03c-1.34-3.6-4.79-6.17-8.86-6.17s-7.52 2.57-8.86 6.17l-.02-.03l-2.5 7.23c-.4 1.026-.67 1.9-.67 2.97c0 3.83 3.07 6.93 6.88 7v.01h10.19c3.87 0 7.01-3.14 7.01-7.01c.01-1.04-.295-1.944-.64-2.92");
}

.tnumr2b3r {
  stop-color: var(--svg-color--d9d9de, #D9D9DE);
}

.u0s5vz57c {
  width: 0.422px;
  height: 2.009px;
  x: 9.969px;
  y: 15.575px;
  fill: var(--svg-color--76676a, #76676A);
  rx: 0.211px;
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.uqa0vwigp {
  stop-color: var(--svg-color--727075, #727075);
}

.uzsvhebjb {
  stop-color: var(--svg-color--9f9fa6, #9F9FA6);
  stop-opacity: 0;
}

.veh5liige {
  stop-color: var(--svg-color--d9d9de, #D9D9DE);
  stop-opacity: 0;
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vxfpfdb8n {
  stop-color: var(--svg-color--bdbec0, #BDBEC0);
  stop-opacity: 0;
}

.whx21hb2m {
  stop-color: var(--svg-color--93919c, #93919C);
  stop-opacity: 0;
}

.wkn68tbkw {
  stop-color: var(--svg-color--bdbec0, #BDBEC0);
}

.xv1r2q1-x {
  cx: 21.148px;
  cy: 14.564px;
  rx: 4.81px;
  ry: 8.297px;
}

.y3qyz048x {
  stop-color: var(--svg-color--878688, #878688);
}

.yibhjabmb {
  stop-color: var(--svg-color--929195, #929195);
}

.yjv2hiy2z {
  stop-color: var(--svg-color--e0e1e6, #E0E1E6);
}

.ymtsqt8-z {
  stop-color: var(--svg-color--838286, #838286);
  stop-opacity: 0;
}

.z7494hb4b {
  stop-color: var(--svg-color--a3a3a9, #A3A3A9);
}

.zhyo0649t {
  stop-color: var(--svg-color--b9bbbe, #B9BBBE);
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

</style>
