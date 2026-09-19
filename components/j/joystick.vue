<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iPPDQte)" class="v3d8dy-hi"/><path fill="url(#i74hdmc)" class="q5lrkftgv"/><path fill="url(#i74hdmc)" class="q5lrkftgv"/><path fill="url(#iddz5Bc)" class="q5lrkftgv"/><path fill="url(#iapjTQI)" class="q5lrkftgv"/><path fill="url(#i8252sd)" class="q5lrkftgv"/><g filter="url(#iS4GdFc)"><path stroke="url(#iOM6HTc)" class="i01xj9psd"/></g><g filter="url(#i6KfOde)"><path fill="url(#iobSlec)" class="pbcmoebfl"/><path fill="url(#izV7ZFd)" class="pbcmoebfl"/></g><g filter="url(#iHsKzGe)"><path fill="url(#iQ8PkKd)" class="sb702sz1j"/></g><path fill="url(#iqviMYb)" class="jep8pf8ji"/><g filter="url(#iXbdC2c)"><path class="zdr918vcd"/><path fill="url(#iJ1zL5d)" class="bhopilb6z"/><path fill="url(#i15qv2c)" class="bhopilb6z"/><path fill="url(#iYtCbBd)" class="bhopilb6z"/><path fill="url(#inCgtva)" class="bhopilb6z"/></g><path fill="url(#iIq4K7b)" class="bhopilb6z"/><path fill="url(#iaROPEe)" class="bhopilb6z"/><g filter="url(#ib975Bc)"><path class="fz0qavb7a"/></g><path fill="url(#i9xIEdc)" class="rgb3ewbat"/><path fill="url(#igRH75c)" class="rgb3ewbat"/><path fill="url(#iywW9cd)" class="rgb3ewbat"/><path fill="url(#itFCuIb)" class="b7douybuh"/><path fill="url(#idZze5b)" class="b7douybuh"/><path fill="url(#iJmtene)" class="b7douybuh"/><circle fill="url(#ivHFQYb)" class="yoyffybfu"/><circle fill="url(#iFP5ZJe)" class="yoyffybfu"/><circle fill="url(#iMjzXne)" class="yoyffybfu"/><g filter="url(#iI4XUDe)"><path class="ngpwtg5_t"/></g><defs><radialGradient id="i8252sd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65532 -9.54334 0 16.365 11.347)" gradientUnits="userSpaceOnUse"><stop class="hajt9fb-a"/><stop offset="1" class="d-og4xybv"/></radialGradient><radialGradient id="izV7ZFd" cx="0" cy="0" r="1" gradientTransform="scale(5.2725 2.375)rotate(90 -2.3 5.33)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="k1bl_hx9w"/><stop offset="1" class="m6yzath2p"/></radialGradient><radialGradient id="iJ1zL5d" cx="0" cy="0" r="1" gradientTransform="rotate(94.126 2.003 14.32)scale(6.29757 12.0208)" gradientUnits="userSpaceOnUse"><stop offset=".647" class="m04498b7z"/><stop offset="1" class="ouj5hfbfs"/></radialGradient><radialGradient id="i15qv2c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.09975 2.25628 -1.4669 -2.66543 20.076 15.75)" gradientUnits="userSpaceOnUse"><stop class="tbepa1bnn"/><stop offset="1" class="swvrbnumo"/></radialGradient><radialGradient id="iYtCbBd" cx="0" cy="0" r="1" gradientTransform="rotate(101.741 .99 11.9)scale(5.63189 3.58864)" gradientUnits="userSpaceOnUse"><stop class="wvb6qcb6n"/><stop offset="1" class="gi1zugb-u"/></radialGradient><radialGradient id="inCgtva" cx="0" cy="0" r="1" gradientTransform="matrix(3.61718 -3.9574 4.05244 3.70405 15.779 18.633)" gradientUnits="userSpaceOnUse"><stop offset=".942" class="lfm50ybmn"/><stop offset=".991" class="ezp-flqor"/></radialGradient><radialGradient id="iIq4K7b" cx="0" cy="0" r="1" gradientTransform="rotate(-44.236 27.446 -4.512)scale(4.97229 4.86741)" gradientUnits="userSpaceOnUse"><stop class="iy5hc_7kh"/><stop offset="1" class="dr6gjmbzp"/></radialGradient><radialGradient id="iaROPEe" cx="0" cy="0" r="1" gradientTransform="rotate(-139.07 11.991 6.148)scale(5.91484 7.01095)" gradientUnits="userSpaceOnUse"><stop offset=".934" class="xcjftr3_v"/><stop offset="1" class="s7a1m9bmi"/></radialGradient><radialGradient id="i9xIEdc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 0 0 -2.1875 9.008 18.102)" gradientUnits="userSpaceOnUse"><stop class="b9a625biu"/><stop offset="1" class="h5-hc-27w"/></radialGradient><radialGradient id="igRH75c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10733 .2291 -.11267 -.54459 8.87 18.162)" gradientUnits="userSpaceOnUse"><stop class="lxcvk-7ol"/><stop offset="1" class="eeb_wqb_a"/></radialGradient><radialGradient id="iywW9cd" cx="0" cy="0" r="1" gradientTransform="rotate(166.189 3.227 9.452)scale(1.93083 1.90247)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="e8h-e4blg"/><stop offset="1" class="bme_j1u2u"/></radialGradient><radialGradient id="idZze5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.71905 0 0 .9427 16.083 10.342)" gradientUnits="userSpaceOnUse"><stop class="g5j0wncxr"/><stop offset="1" class="i7qes1b1d"/></radialGradient><radialGradient id="iJmtene" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73694 2.66813 -1.6878 -1.09875 15.403 9.966)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="oz4icccql"/><stop offset="1" class="i7qes1b1d"/></radialGradient><radialGradient id="ivHFQYb" cx="0" cy="0" r="1" gradientTransform="rotate(142.722 8.645 5.417)scale(5.26263)" gradientUnits="userSpaceOnUse"><stop class="xoiqezblr"/><stop offset="1" class="e4e-_sbbp"/></radialGradient><radialGradient id="iFP5ZJe" cx="0" cy="0" r="1" gradientTransform="rotate(-180 9.309 3.2)scale(7.21875)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="iwn_tybce"/><stop offset="1" class="bmu5bdbzi"/><stop offset="1" class="bmu5bdbzi"/></radialGradient><radialGradient id="iMjzXne" cx="0" cy="0" r="1" gradientTransform="rotate(90 6.023 9.953)scale(7.375)" gradientUnits="userSpaceOnUse"><stop offset=".807" class="c926q2iuv"/><stop offset="1" class="ii1eysbtf"/></radialGradient><linearGradient id="iPPDQte" x1="5.375" x2="26.472" y1="24.227" y2="24.227" gradientUnits="userSpaceOnUse"><stop class="p9ugu8dfa"/><stop offset=".448" class="oasbnivrm"/><stop offset=".568" class="j78g0ep7p"/></linearGradient><linearGradient id="i74hdmc" x1="26.242" x2="3.305" y1="17.492" y2="17.492" gradientUnits="userSpaceOnUse"><stop class="zd_vn5bwb"/><stop offset="1" class="yp390obnp"/></linearGradient><linearGradient id="iddz5Bc" x1="9.984" x2="10.148" y1="20.679" y2="20.343" gradientUnits="userSpaceOnUse"><stop offset=".269" class="ptdeb448c"/><stop offset="1" class="lnh0e0b0i"/></linearGradient><linearGradient id="iapjTQI" x1="21.321" x2="21.091" y1="20.999" y2="20.515" gradientUnits="userSpaceOnUse"><stop offset=".338" class="en6wvvbri"/><stop offset="1" class="mk348cbqx"/></linearGradient><linearGradient id="iOM6HTc" x1="26.523" x2="17.852" y1="19.898" y2="24.211" gradientUnits="userSpaceOnUse"><stop offset=".896" class="yar_67bbi"/><stop offset="1" class="ppuhnpbpz"/></linearGradient><linearGradient id="iobSlec" x1="15.976" x2="15.976" y1="18.492" y2="24.34" gradientUnits="userSpaceOnUse"><stop class="qjdk06vld"/><stop offset="1" class="luxi6728x"/></linearGradient><linearGradient id="iQ8PkKd" x1="8.023" x2="8.023" y1="17.508" y2="21.206" gradientUnits="userSpaceOnUse"><stop class="qjdk06vld"/><stop offset="1" class="luxi6728x"/></linearGradient><linearGradient id="iqviMYb" x1="26.336" x2="3.189" y1="21.119" y2="21.119" gradientUnits="userSpaceOnUse"><stop offset=".431" class="b1s8zcc5y"/><stop offset=".464" class="qumu8w5jr"/></linearGradient><linearGradient id="itFCuIb" x1="15.273" x2="17.086" y1="12.961" y2="12.961" gradientUnits="userSpaceOnUse"><stop class="q8f601ogg"/><stop offset="1" class="uuye6t9uf"/></linearGradient><filter id="iS4GdFc" width="10.944" height="5.6" x="16.891" y="18.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3570" stdDeviation=".1"/></filter><filter id="i6KfOde" width="11.203" height="8.305" x="10.375" y="16.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3570" stdDeviation=".375"/></filter><filter id="iHsKzGe" width="3.219" height="2.645" x="6.414" y="17.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3570" stdDeviation=".125"/></filter><filter id="iXbdC2c" width="9.703" height="6.381" x="11.125" y="13.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0862745 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3570"/></filter><filter id="ib975Bc" width="3.089" height="2.066" x="6.444" y="16.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3570" stdDeviation=".075"/></filter><filter id="iI4XUDe" width="11.958" height="5.604" x="15.777" y="17.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3570" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:joystick" /></template>
<style>
.b1s8zcc5y {
  stop-color: var(--svg-color--6052a1, #6052A1);
}

.b7douybuh {
  d: path("M14.945 9.86a.992.992 0 1 1 1.985 0v4.148c0 .548-.445.719-.993.719c-.547 0-.992-.171-.992-.72z");
}

.b9a625biu {
  stop-color: var(--svg-color--ff3389, #FF3389);
}

.bhopilb6z {
  d: path("M11.153 17.356a1 1 0 0 0-.028.222c0 1.135 2.172 2.055 4.852 2.055c2.679 0 4.851-.92 4.851-2.055a1 1 0 0 0-.028-.222a4.908 4.908 0 0 0-9.647 0");
}

.bme_j1u2u {
  stop-color: var(--svg-color--c52754, #C52754);
}

.bmu5bdbzi {
  stop-color: var(--svg-color--cc515d, #CC515D);
}

.c926q2iuv {
  stop-color: var(--svg-color--b8276b, #B8276B);
  stop-opacity: 0;
}

.d-og4xybv {
  stop-color: var(--svg-color--6d6f9e, #6D6F9E);
  stop-opacity: 0;
}

.dr6gjmbzp {
  stop-color: var(--svg-color--422e3d, #422E3D);
  stop-opacity: 0;
}

.e4e-_sbbp {
  stop-color: var(--svg-color--fb426f, #FB426F);
}

.e8h-e4blg {
  stop-color: var(--svg-color--c52754, #C52754);
  stop-opacity: 0;
}

.eeb_wqb_a {
  stop-color: var(--svg-color--ff5ea3, #FF5EA3);
  stop-opacity: 0;
}

.en6wvvbri {
  stop-color: var(--svg-color--6152a2, #6152A2);
}

.ezp-flqor {
  stop-color: var(--svg-color--766f8b, #766F8B);
}

.ft5dv1b6b {
  fill: none;
}

.fz0qavb7a {
  fill: var(--svg-color--50416c, #50416C);
  d: path("M7.988 17.09c.77 0 1.395.413 1.395 1.144c0 .434-.625.621-1.395.621s-1.394-.168-1.394-.62c0-.732.624-1.145 1.394-1.145");
}

.g5j0wncxr {
  stop-color: var(--svg-color--bd7cd0, #BD7CD0);
}

.gi1zugb-u {
  stop-color: var(--svg-color--4a3947, #4A3947);
  stop-opacity: 0;
}

.h5-hc-27w {
  stop-color: var(--svg-color--e13b63, #E13B63);
}

.hajt9fb-a {
  stop-color: var(--svg-color--6d6f9e, #6D6F9E);
}

.i01xj9psd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m17.19 24.21l10.345-5");
}

.i7qes1b1d {
  stop-color: var(--svg-color--bd7cd0, #BD7CD0);
  stop-opacity: 0;
}

.ii1eysbtf {
  stop-color: var(--svg-color--b8276b, #B8276B);
}

.iwn_tybce {
  stop-color: var(--svg-color--cc515d, #CC515D);
  stop-opacity: 0;
}

.iy5hc_7kh {
  stop-color: var(--svg-color--422e3d, #422E3D);
}

.j78g0ep7p {
  stop-color: var(--svg-color--5d3e7d, #5D3E7D);
}

.jep8pf8ji {
  d: path("m4.57 18.101l10.517 4.888a2 2 0 0 0 1.684 0l10.548-4.888a1 1 0 0 0 .47-.454a1 1 0 0 1 .109.452v.798a.2.2 0 0 1-.114.18l-10.546 5.04a3 3 0 0 1-2.586 0l-10.546-5.04a.2.2 0 0 1-.114-.18V18.1c0-.16.038-.315.108-.453a1 1 0 0 0 .47.455");
}

.k1bl_hx9w {
  stop-color: var(--svg-color--281e45, #281E45);
}

.lfm50ybmn {
  stop-color: var(--svg-color--766f8b, #766F8B);
  stop-opacity: 0.082;
}

.lnh0e0b0i {
  stop-color: var(--svg-color--534177, #534177);
  stop-opacity: 0;
}

.luxi6728x {
  stop-color: var(--svg-color--4d4277, #4D4277);
  stop-opacity: 0;
}

.lxcvk-7ol {
  stop-color: var(--svg-color--ff5ea3, #FF5EA3);
}

.m04498b7z {
  stop-color: var(--svg-color--442a5d, #442A5D);
  stop-opacity: 0;
}

.m6yzath2p {
  stop-color: var(--svg-color--281e45, #281E45);
  stop-opacity: 0;
}

.mk348cbqx {
  stop-color: var(--svg-color--5f5887, #5F5887);
  stop-opacity: 0;
}

.ngpwtg5_t {
  stroke: var(--svg-color--7067a3, #7067A3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m27.535 17.868l-10.813 5.068a1.9 1.9 0 0 1-.746.134");
}

.oasbnivrm {
  stop-color: var(--svg-color--38224a, #38224A);
}

.ouj5hfbfs {
  stop-color: var(--svg-color--442a5d, #442A5D);
}

.oz4icccql {
  stop-color: var(--svg-color--b87eba, #B87EBA);
}

.p9ugu8dfa {
  stop-color: var(--svg-color--2f2137, #2F2137);
}

.pbcmoebfl {
  d: path("M15.687 24.34c-4.216-.905-4.763-4.914-4.51-6.805l9.65.161c.043 2.592-1.665 6.095-5.14 6.644");
}

.ppuhnpbpz {
  stop-color: var(--svg-color--69597d, #69597D);
  stop-opacity: 0;
}

.ptdeb448c {
  stop-color: var(--svg-color--4f3a84, #4F3A84);
}

.q5lrkftgv {
  d: path("m15.93 11.913l-11.36 5.28a1 1 0 0 0-.578.906v.798a.2.2 0 0 0 .114.18l10.546 5.04a3 3 0 0 0 2.586 0l10.546-5.04a.2.2 0 0 0 .114-.18V18.1a1 1 0 0 0-.579-.907l-11.358-5.279v-.015l-.016.008l-.016-.008z");
}

.q8f601ogg {
  stop-color: var(--svg-color--ddb7f2, #DDB7F2);
}

.qjdk06vld {
  stop-color: var(--svg-color--4d4277, #4D4277);
}

.qumu8w5jr {
  stop-color: var(--svg-color--4e3a83, #4E3A83);
}

.rgb3ewbat {
  d: path("M7.988 16.977c.732 0 1.324.413 1.324 1.144c0 .434-.592.621-1.324.621c-.731 0-1.324-.168-1.324-.62c0-.732.593-1.145 1.324-1.145");
}

.s7a1m9bmi {
  stop-color: var(--svg-color--50464d, #50464D);
}

.sb702sz1j {
  d: path("M7.942 20.117c-1.181-.285-1.334-1.548-1.263-2.144l2.704.05c.012.817-.467 1.921-1.44 2.094");
}

.swvrbnumo {
  stop-color: var(--svg-color--6f5a85, #6F5A85);
  stop-opacity: 0;
}

.tbepa1bnn {
  stop-color: var(--svg-color--6f5a85, #6F5A85);
}

.uuye6t9uf {
  stop-color: var(--svg-color--f8ebff, #F8EBFF);
}

.v3d8dy-hi {
  d: path("M4.295 19a.25.25 0 0 0-.299.246v3.927a2 2 0 0 0 1.133 1.802l8.867 4.266a4.5 4.5 0 0 0 3.902 0l8.867-4.266a2 2 0 0 0 1.133-1.803v-3.926a.25.25 0 0 0-.299-.246l-11.652 2.305z");
}

.wvb6qcb6n {
  stop-color: var(--svg-color--4a3947, #4A3947);
}

.xcjftr3_v {
  stop-color: var(--svg-color--50464d, #50464D);
  stop-opacity: 0;
}

.xoiqezblr {
  stop-color: var(--svg-color--ff78ad, #FF78AD);
}

.yar_67bbi {
  stop-color: var(--svg-color--69597d, #69597D);
}

.yoyffybfu {
  cx: 15.976px;
  cy: 6.398px;
  r: 4.578px;
}

.yp390obnp {
  stop-color: var(--svg-color--5e5681, #5E5681);
}

.zd_vn5bwb {
  stop-color: var(--svg-color--615d8d, #615D8D);
}

.zdr918vcd {
  fill: var(--svg-color--4c2f5a, #4C2F5A);
  d: path("M11.153 17.356a1 1 0 0 0-.028.222c0 1.135 2.172 2.055 4.852 2.055c2.679 0 4.851-.92 4.851-2.055a1 1 0 0 0-.028-.222a4.908 4.908 0 0 0-9.647 0");
}

</style>
