<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGNJw5d)"><path class="suq-3ocyd"/><path fill="url(#iHleCJb)" class="c5bq9ecan"/></g><path class="zvp6gs1ba"/><path fill="url(#ibLzehk)" class="fdd-_1f7k"/><path fill="url(#i8z6tzc)" class="fdd-_1f7k"/><path fill="url(#ij8WYtb)" class="fdd-_1f7k"/><path fill="url(#i8uG4Hc)" class="fdd-_1f7k"/><path fill="url(#iGpl5ke)" class="spngh7tut"/><path fill="url(#iQ2MXhc)" class="spngh7tut"/><path fill="url(#i8jHErc)" class="spngh7tut"/><path fill="url(#iUZZP2d)" class="jih6glb-i"/><path fill="url(#ijZBCLD)" class="jih6glb-i"/><path fill="url(#ikIlhhb)" class="jih6glb-i"/><path fill="url(#iKy8Ord)" class="jih6glb-i"/><path fill="url(#ixyVEfb)" class="vn_ch0-ti"/><path fill="url(#ipKXCCb)" class="vn_ch0-ti"/><path fill="url(#iagBFJI)" class="vn_ch0-ti"/><g filter="url(#id0rssd)"><path class="yn52svbdr"/><path fill="url(#iR8NO7K)" class="au7ji2dyj"/><path fill="url(#ioMaIxd)" class="au7ji2dyj"/></g><rect fill="url(#iHRm1sk)" class="qev02t-3t"/><rect fill="url(#iAkQg9b)" class="qev02t-3t"/><rect fill="url(#ibAwIab)" class="qev02t-3t"/><rect fill="url(#ibqYRSb)" class="qev02t-3t"/><g filter="url(#inVTybc)"><path fill="url(#i7AFNbe)" class="umzjm1bwk"/></g><g filter="url(#iYVKvdc)"><rect class="h5tlm6bqp"/></g><g filter="url(#ihC8dne)"><path class="pl299xbks"/></g><defs><radialGradient id="iHleCJb" cx="0" cy="0" r="1" gradientTransform="rotate(65.117 2.268 23.016)scale(9.59073 10.3722)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="hf8jqybrt"/><stop offset="1" class="ea19op8oa"/></radialGradient><radialGradient id="ij8WYtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.3466 -6.91977 0 11.63 16.42)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="vk-hei9lp"/><stop offset="1" class="u-tf3eb9y"/></radialGradient><radialGradient id="i8uG4Hc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.70039 6.30432 0 11.63 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="v2uwotllu"/><stop offset="1" class="cz5i0kbhu"/></radialGradient><radialGradient id="iQ2MXhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.42709 -6.45029 0 5.263 17.304)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="vk-hei9lp"/><stop offset="1" class="u-tf3eb9y"/></radialGradient><radialGradient id="ijZBCLD" cx="0" cy="0" r="1" gradientTransform="matrix(-3.66527 0 0 -6.70115 21.267 22.344)" gradientUnits="userSpaceOnUse"><stop class="eapn_cchb"/><stop offset="1" class="f_diivbuu"/></radialGradient><radialGradient id="ixyVEfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.0109 5.81896 0 27.738 21.194)" gradientUnits="userSpaceOnUse"><stop class="gw_8d3bye"/><stop offset="1" class="f8p5jtbxh"/></radialGradient><radialGradient id="ipKXCCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.81896 .74113 0 21.252 21.791)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="qycnp9bya"/><stop offset="1" class="zf8eueqxo"/></radialGradient><radialGradient id="iagBFJI" cx="0" cy="0" r="1" gradientTransform="matrix(3.2452 3.784 -11.4046 9.78069 20.912 13.995)" gradientUnits="userSpaceOnUse"><stop class="dd4kuf14o"/><stop offset="1" class="o1586ibev"/></radialGradient><radialGradient id="iR8NO7K" cx="0" cy="0" r="1" gradientTransform="matrix(6.04842 0 0 1.15509 23.113 21.062)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="cuo829bjc"/><stop offset="1" class="b6jg4xbux"/></radialGradient><radialGradient id="ioMaIxd" cx="0" cy="0" r="1" gradientTransform="matrix(-12.3142 .43002 -.34933 -10.0035 26.697 25.136)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="ay28kacra"/><stop offset="1" class="do97bwhkl"/></radialGradient><radialGradient id="iHRm1sk" cx="0" cy="0" r="1" gradientTransform="rotate(89.182 9.854 18.401)scale(8.47992 8.71423)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="hu0uwibjm"/><stop offset="1" class="jkh_ugbtz"/></radialGradient><radialGradient id="iAkQg9b" cx="0" cy="0" r="1" gradientTransform="matrix(-8.96358 0 0 -8.75917 28.84 9.535)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="n5hwk-_ts"/><stop offset="1" class="syic2acsx"/></radialGradient><radialGradient id="ibAwIab" cx="0" cy="0" r="1" gradientTransform="rotate(-75.847 20.655 -6.966)scale(7.18299 9.59533)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="bu7qhe7qf"/><stop offset="1" class="uyy3xnxfw"/></radialGradient><radialGradient id="ibqYRSb" cx="0" cy="0" r="1" gradientTransform="matrix(5.55345 9.83258 -8.79835 4.96931 22.894 5.766)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="ql2zrgmbf"/><stop offset=".956" class="er55yo7vc"/></radialGradient><linearGradient id="ibLzehk" x1="8.511" x2="12.011" y1="20.088" y2="20.088" gradientUnits="userSpaceOnUse"><stop class="wt33ilbms"/><stop offset="1" class="o-kq2xtml"/></linearGradient><linearGradient id="i8z6tzc" x1="14.418" x2="13.27" y1="21.08" y2="21.08" gradientUnits="userSpaceOnUse"><stop class="qi_5yqx5g"/><stop offset="1" class="w_rthdg1v"/></linearGradient><linearGradient id="iGpl5ke" x1="8.865" x2="6.902" y1="22.047" y2="22.047" gradientUnits="userSpaceOnUse"><stop class="wwebo9bjc"/><stop offset="1" class="u6o_0bbtw"/></linearGradient><linearGradient id="i8jHErc" x1="8.654" x2="8.05" y1="15.569" y2="17.271" gradientUnits="userSpaceOnUse"><stop class="cz5i0kbhu"/><stop offset="1" class="v2uwotllu"/></linearGradient><linearGradient id="iUZZP2d" x1="14.307" x2="19.349" y1="22.64" y2="22.64" gradientUnits="userSpaceOnUse"><stop class="nrlzh2qks"/><stop offset="1" class="wyiecubnk"/></linearGradient><linearGradient id="ikIlhhb" x1="14.27" x2="15.158" y1="15.605" y2="17.086" gradientUnits="userSpaceOnUse"><stop class="x3rd6yivr"/><stop offset="1" class="lqjr1gbpw"/></linearGradient><linearGradient id="iKy8Ord" x1="15.394" x2="15.394" y1="27.212" y2="22.549" gradientUnits="userSpaceOnUse"><stop offset=".097" class="dm3x6bb6j"/><stop offset="1" class="uo_7ebmzn"/></linearGradient><linearGradient id="i7AFNbe" x1="28.259" x2="19.093" y1="24.51" y2="24.51" gradientUnits="userSpaceOnUse"><stop class="oxgl5n4wa"/><stop offset="1" class="kib9ab0eq"/></linearGradient><filter id="iGNJw5d" width="22.598" height="20.153" x="2.342" y="7.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.658824 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7073"/></filter><filter id="id0rssd" width="15.807" height="10.665" x="15.128" y="18.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.603922 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.494118 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7073" result="effect2_innerShadow_20020_7073"/></filter><filter id="inVTybc" width="14.325" height="8.477" x="15.934" y="20.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7073" stdDeviation="1"/></filter><filter id="iYVKvdc" width="6.369" height="13.701" x="3.051" y="12.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7073" stdDeviation="1"/></filter><filter id="ihC8dne" width="7.27" height="6.265" x="7.292" y="8.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7073" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-at-the-viewer" /></template>
<style>
.au7ji2dyj {
  d: path("M24.304 21.14c-.614.303-.954.606-1.484.606h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.815 3.81 3.815h4.398c4.586 0 5.738-2.665 5.994-3.815c.256-1.151.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.137");
}

.ay28kacra {
  stop-color: var(--svg-color--f19b16, #F19B16);
  stop-opacity: 0;
}

.b6jg4xbux {
  stop-color: var(--svg-color--ffac0c, #FFAC0C);
  stop-opacity: 0;
}

.bu7qhe7qf {
  stop-color: var(--svg-color--f78c47, #F78C47);
}

.c5bq9ecan {
  d: path("M17.149 7.544c1.114 0 2.569.681 3.043 1.045l3.998.181v18.503l-7.268.174c-1.381 0-1.908-.833-2.226-1.613c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468c-.323.525-1.212 1.506-2.885 1.506c-2.627 0-3.401-2.387-3.361-3.497v-7.071c-.07-.646.085-2.162 1.272-3.059c1.484-1.12 2.15-.833 3.755-1.968C8.844 9.55 9.23 9.285 10.32 9.012c.977-.189 1.978.076 3.407-.265c1.224-.29 2.029-1.203 3.422-1.203");
}

.cuo829bjc {
  stop-color: var(--svg-color--ffac0c, #FFAC0C);
}

.cz5i0kbhu {
  stop-color: var(--svg-color--ffb630, #FFB630);
}

.dd4kuf14o {
  stop-color: var(--svg-color--f18b37, #F18B37);
}

.dm3x6bb6j {
  stop-color: var(--svg-color--e27b56, #E27B56);
}

.do97bwhkl {
  stop-color: var(--svg-color--f19b16, #F19B16);
}

.ea19op8oa {
  stop-color: var(--svg-color--ec8219, #EC8219);
  stop-opacity: 0;
}

.eapn_cchb {
  stop-color: var(--svg-color--ffd13a, #FFD13A);
}

.er55yo7vc {
  stop-color: var(--svg-color--e49b6b, #E49B6B);
}

.f_diivbuu {
  stop-color: var(--svg-color--ffd13a, #FFD13A);
  stop-opacity: 0;
}

.f8p5jtbxh {
  stop-color: var(--svg-color--ffac22, #FFAC22);
}

.fdd-_1f7k {
  d: path("M15.04 26.502a3.7 3.7 0 0 1-.344-.668c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468l-.064.098a52 52 0 0 1-.026-1.732v-8.892l5.996 1.351v8.459c0 .556.4 1.296.624 1.708c.067.125.118.22.138.27c-.04.098-.119.23-.23.382");
}

.ft5dv1b6b {
  fill: none;
}

.gw_8d3bye {
  stop-color: var(--svg-color--ffe54e, #FFE54E);
}

.h5tlm6bqp {
  width: 2.369px;
  height: 9.701px;
  x: 5.051px;
  y: 14.332px;
  fill: var(--svg-color--ffc341, #FFC341);
  rx: 1.185px;
}

.hf8jqybrt {
  stop-color: var(--svg-color--ec8219, #EC8219);
}

.hu0uwibjm {
  stop-color: var(--svg-color--ffe953, #FFE953);
}

.jih6glb-i {
  d: path("m14.695 25.838l.001-.004l.02.05l.034.056v.023c.324.74.867 1.484 2.172 1.484l7.267-.174V16.22l-9.68-.337v8.755c0 .621.103 1.012.185 1.2");
}

.jkh_ugbtz {
  stop-color: var(--svg-color--ffa530, #FFA530);
}

.kib9ab0eq {
  stop-color: var(--svg-color--ffe852, #FFE852);
  stop-opacity: 0;
}

.lqjr1gbpw {
  stop-color: var(--svg-color--fbac2c, #FBAC2C);
  stop-opacity: 0;
}

.n5hwk-_ts {
  stop-color: var(--svg-color--ffb32d, #FFB32D);
  stop-opacity: 0;
}

.nrlzh2qks {
  stop-color: var(--svg-color--f8941c, #F8941C);
}

.o-kq2xtml {
  stop-color: var(--svg-color--ffb346, #FFB346);
  stop-opacity: 0;
}

.o1586ibev {
  stop-color: var(--svg-color--f18b37, #F18B37);
  stop-opacity: 0;
}

.oxgl5n4wa {
  stop-color: var(--svg-color--ffe852, #FFE852);
}

.pl299xbks {
  fill: var(--svg-color--ffbf32, #FFBF32);
  d: path("M10.973 9.8c-1.005.17-1.878.949-2.18 1.393l2.937 1.786l1.332-2.967c-.757-.364-1.332-.341-2.09-.212");
}

.qev02t-3t {
  width: 10.852px;
  height: 12.128px;
  x: 19.394px;
  y: 3.471px;
  rx: 5.426px;
}

.qi_5yqx5g {
  stop-color: var(--svg-color--fd9323, #FD9323);
}

.ql2zrgmbf {
  stop-color: var(--svg-color--e49b6b, #E49B6B);
  stop-opacity: 0;
}

.qycnp9bya {
  stop-color: var(--svg-color--f1960b, #F1960B);
}

.spngh7tut {
  d: path("m8.602 24.858l.006.02a5 5 0 0 1-.096-1.027v-8.282l-6.156.65v6.648c-.04 1.11.734 3.497 3.361 3.497c1.673 0 2.562-.982 2.885-1.506");
}

.suq-3ocyd {
  fill: var(--svg-color--ffb630, #FFB630);
  d: path("M17.149 7.544c1.114 0 2.569.681 3.043 1.045l3.998.181v18.503l-7.268.174c-1.381 0-1.908-.833-2.226-1.613c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468c-.323.525-1.212 1.506-2.885 1.506c-2.627 0-3.401-2.387-3.361-3.497v-7.071c-.07-.646.085-2.162 1.272-3.059c1.484-1.12 2.15-.833 3.755-1.968C8.844 9.55 9.23 9.285 10.32 9.012c.977-.189 1.978.076 3.407-.265c1.224-.29 2.029-1.203 3.422-1.203");
}

.syic2acsx {
  stop-color: var(--svg-color--d8a052, #D8A052);
}

.u-tf3eb9y {
  stop-color: var(--svg-color--ec7c80, #EC7C80);
}

.u6o_0bbtw {
  stop-color: var(--svg-color--ffac2e, #FFAC2E);
  stop-opacity: 0;
}

.umzjm1bwk {
  d: path("M21.773 23.634H19.49a1.557 1.557 0 0 0 0 3.115h4.962c2.68 0 3.875-.778 3.803-2.496s-2.065-2.712-3.803-1.33c-.81.645-2.221.668-2.68.71");
}

.uo_7ebmzn {
  stop-color: var(--svg-color--e27b56, #E27B56);
  stop-opacity: 0;
}

.uyy3xnxfw {
  stop-color: var(--svg-color--ffbe40, #FFBE40);
  stop-opacity: 0;
}

.v2uwotllu {
  stop-color: var(--svg-color--ffb630, #FFB630);
  stop-opacity: 0;
}

.vk-hei9lp {
  stop-color: var(--svg-color--f28850, #F28850);
  stop-opacity: 0;
}

.vn_ch0-ti {
  d: path("M21.404 24.033c0-3.101-.071-8.177-.152-10.327l7.01-2.18c.752 3.973 1.035 10.013 1.136 12.506z");
}

.w_rthdg1v {
  stop-color: var(--svg-color--ffb649, #FFB649);
  stop-opacity: 0;
}

.wt33ilbms {
  stop-color: var(--svg-color--f09119, #F09119);
}

.wwebo9bjc {
  stop-color: var(--svg-color--f48820, #F48820);
}

.wyiecubnk {
  stop-color: var(--svg-color--ffab3c, #FFAB3C);
  stop-opacity: 0;
}

.x3rd6yivr {
  stop-color: var(--svg-color--fbac2c, #FBAC2C);
}

.yn52svbdr {
  fill: var(--svg-color--ffc216, #FFC216);
  d: path("M24.304 21.14c-.614.303-.954.606-1.484.606h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.815 3.81 3.815h4.398c4.586 0 5.738-2.665 5.994-3.815c.256-1.151.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.137");
}

.zf8eueqxo {
  stop-color: var(--svg-color--f1960b, #F1960B);
  stop-opacity: 0;
}

.zvp6gs1ba {
  fill: var(--svg-color--ffb548, #FFB548);
  d: path("M15.04 26.502a3.7 3.7 0 0 1-.344-.668c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468l-.064.098a52 52 0 0 1-.026-1.732v-8.892l5.996 1.351v8.459c0 .556.4 1.296.624 1.708c.067.125.118.22.138.27c-.04.098-.119.23-.23.382");
}

</style>
