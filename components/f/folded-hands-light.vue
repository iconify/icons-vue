<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iytQiQb)" class="eud_w5b5b"/><rect fill="url(#i6Mg9xe)" class="eud_w5b5b"/><path fill="url(#iXPN7je)" class="kwu0ecbgx"/><path fill="url(#iiHJ9sp)" class="kwu0ecbgx"/><path fill="url(#ioWH6dd)" class="kwu0ecbgx"/><rect fill="url(#ijSPg3b)" transform="matrix(-1 0 0 1 21.375 2.223)" class="e4xcmebwj"/><rect fill="url(#iwuZAom)" transform="matrix(-1 0 0 1 21.375 2.223)" class="e4xcmebwj"/><path fill="url(#iP0xwuc)" class="aya86ob_i"/><path fill="url(#iWP7FZe)" class="aya86ob_i"/><g filter="url(#ixVXgqb)"><path stroke="url(#irKZvXN)" class="p5r1espwo"/></g><g filter="url(#ieA5Xud)"><path stroke="url(#iLB5T0c)" class="eqwqidcpi"/></g><g filter="url(#iNnI1Jd)"><path fill="url(#iwZC3fc)" class="y9f8gy2ni"/></g><g filter="url(#ihUeyuR)"><path fill="url(#i1kg91i)" class="qxwbxgb_x"/></g><g filter="url(#iPynLfe)"><ellipse fill="url(#iLC6I2b)" transform="rotate(-39.49 19.849 3.814)" class="r2u3ribwc"/></g><g filter="url(#indcG3d)"><ellipse transform="rotate(-39.49 15.456 3.855)" class="ovde0_bdt"/></g><path fill="url(#irQWWGv)" class="c2ymzseoj"/><path fill="url(#iuSxZld)" class="c2ymzseoj"/><path fill="url(#izNVhmg)" class="c2ymzseoj"/><path fill="url(#iylUNWc)" class="c2ymzseoj"/><path fill="url(#iuwFvwc)" class="c2ymzseoj"/><path fill="url(#iGE9STf)" class="n418v0b3f"/><path fill="url(#ilma3Md)" class="n418v0b3f"/><path fill="url(#iSNOo9d)" class="n418v0b3f"/><path fill="url(#iEIz0mc)" class="n418v0b3f"/><defs><linearGradient id="i6Mg9xe" x1="14.453" x2="14.453" y1="6.938" y2="4" gradientUnits="userSpaceOnUse"><stop class="f3r2aydaz"/><stop offset="1" class="cc46tddta"/></linearGradient><linearGradient id="iXPN7je" x1="13.269" x2="13.269" y1="5.125" y2="16.702" gradientUnits="userSpaceOnUse"><stop class="uc5tunbpi"/><stop offset="1" class="mlsexxbpb"/></linearGradient><linearGradient id="ioWH6dd" x1="16.984" x2="16.297" y1="12.544" y2="12.544" gradientUnits="userSpaceOnUse"><stop class="fi6t2wbco"/><stop offset="1" class="kapg7fbpl"/></linearGradient><linearGradient id="iwuZAom" x1="2.922" x2="2.922" y1="6.09" y2="1.496" gradientUnits="userSpaceOnUse"><stop class="f3r2aydaz"/><stop offset="1" class="cc46tddta"/></linearGradient><linearGradient id="iP0xwuc" x1="20.699" x2="20.699" y1="8.915" y2="22.188" gradientUnits="userSpaceOnUse"><stop class="p-sgdu4ak"/><stop offset="1" class="ew4asvbfm"/></linearGradient><linearGradient id="irKZvXN" x1="25.265" x2="25.265" y1="16.348" y2="25.857" gradientUnits="userSpaceOnUse"><stop class="wci41ibjf"/><stop offset=".49" class="fhsjt5paq"/><stop offset="1" class="wci41ibjf"/></linearGradient><linearGradient id="iLB5T0c" x1="10.914" x2="16.958" y1="15.896" y2="23.236" gradientUnits="userSpaceOnUse"><stop offset=".214" class="bctddzirn"/><stop offset=".49" class="j8pwmbb_m"/><stop offset=".776" class="bctddzirn"/></linearGradient><linearGradient id="iwZC3fc" x1="20.954" x2="20.954" y1="5.765" y2="24.331" gradientUnits="userSpaceOnUse"><stop class="mla4tgzzc"/><stop offset="1" class="b98qsobty"/><stop offset="1" class="ms07w1btv"/></linearGradient><linearGradient id="i1kg91i" x1="16.759" x2="12.234" y1="6.778" y2="31.761" gradientUnits="userSpaceOnUse"><stop class="fiiy5zbbw"/><stop offset="1" class="epaqfzjfn"/></linearGradient><linearGradient id="iLC6I2b" x1="19.849" x2="19.849" y1="2.68" y2="6.352" gradientUnits="userSpaceOnUse"><stop class="nv25l8k6g"/><stop offset="1" class="g-bz5-b2k"/></linearGradient><linearGradient id="irQWWGv" x1="7.609" x2="13.234" y1="15.195" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="q9gpy7bkq"/><stop offset="1" class="d5z2kxb0h"/></linearGradient><linearGradient id="iuSxZld" x1="13.633" x2="12.784" y1="18.983" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iylUNWc" x1="8.357" x2="9.211" y1="22.593" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="tyfxpdb0w"/><stop offset="1" class="ki9m_gb7k"/></linearGradient><linearGradient id="iuwFvwc" x1="13.297" x2="12.992" y1="26.703" y2="26.359" gradientUnits="userSpaceOnUse"><stop class="opu5b_bed"/><stop offset="1" class="t2er4acdn"/></linearGradient><linearGradient id="iGE9STf" x1="23.735" x2="19.084" y1="18.733" y2="28.212" gradientUnits="userSpaceOnUse"><stop class="b1lbi7bol"/><stop offset="1" class="k03uj4bcp"/></linearGradient><linearGradient id="iSNOo9d" x1="20.335" x2="20.88" y1="18.983" y2="19.439" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iEIz0mc" x1="20.672" x2="20.914" y1="26.703" y2="26.422" gradientUnits="userSpaceOnUse"><stop class="ewlg17b4k"/><stop offset="1" class="b5b0myb0o"/></linearGradient><radialGradient id="iytQiQb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50714 7.49011 -3.27146 -.65828 16.296 2.223)" gradientUnits="userSpaceOnUse"><stop class="jsiezd-_e"/><stop offset="1" class="b5rk5gx5h"/></radialGradient><radialGradient id="iiHJ9sp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 15.865 23.496)" gradientUnits="userSpaceOnUse"><stop class="sxvugyb6w"/><stop offset="1" class="av6lnlzlc"/></radialGradient><radialGradient id="ijSPg3b" cx="0" cy="0" r="1" gradientTransform="rotate(76.079 -.2 .937)scale(4.74993 3.74633)" gradientUnits="userSpaceOnUse"><stop class="k_i_p7bcf"/><stop offset="1" class="u94mo785n"/></radialGradient><radialGradient id="iWP7FZe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 18.103 23.496)" gradientUnits="userSpaceOnUse"><stop class="ro5br2yzs"/><stop offset="1" class="ba_iefbxu"/></radialGradient><radialGradient id="izNVhmg" cx="0" cy="0" r="1" gradientTransform="rotate(-45 34.16 1.731)scale(8.65467 3.14404)" gradientUnits="userSpaceOnUse"><stop class="w6o4myf_b"/><stop offset="1" class="c8s6441kg"/></radialGradient><radialGradient id="ilma3Md" cx="0" cy="0" r="1" gradientTransform="matrix(4.15623 3.31253 -1.73902 2.18195 22.078 17.063)" gradientUnits="userSpaceOnUse"><stop class="cpbnylbqu"/><stop offset="1" class="bgm6-ubvx"/></radialGradient><filter id="ixVXgqb" width=".65" height="8.419" x="24.44" y="16.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4099" stdDeviation=".125"/></filter><filter id="ieA5Xud" width="5.65" height="6.709" x="10.725" y="16.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4099" stdDeviation=".125"/></filter><filter id="iNnI1Jd" width="6.934" height="13.95" x="17.266" y="4.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4099" stdDeviation=".75"/></filter><filter id="ihUeyuR" width="8.303" height="18.853" x="9.476" y="4.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4099" stdDeviation=".75"/></filter><filter id="iPynLfe" width="3.928" height="4.044" x="17.885" y="1.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4099" stdDeviation=".5"/></filter><filter id="indcG3d" width="3.753" height="3.85" x="13.579" y="1.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4099" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:folded-hands-light" /></template>
<style>
.av6lnlzlc {
  stop-color: var(--svg-color--b97090, #B97090);
  stop-opacity: 0;
}

.aya86ob_i {
  d: path("M19.19 4.737c1.218 0 2.205.987 2.205 2.205v5.4a2 2 0 0 0 .69 1.512l2.33 2.018l-6.47 7.624l-.654-.635a.96.96 0 0 1-.303-.7v-4.094l-.004-.128V6.942c0-1.218.988-2.205 2.206-2.205");
}

.b1lbi7bol {
  stop-color: var(--svg-color--945bcc, #945BCC);
}

.b5b0myb0o {
  stop-color: var(--svg-color--9469ff, #9469FF);
  stop-opacity: 0;
}

.b5rk5gx5h {
  stop-color: var(--svg-color--dfa78c, #DFA78C);
}

.b98qsobty {
  stop-color: var(--svg-color--fccca7, #FCCCA7);
  stop-opacity: 0;
}

.ba_iefbxu {
  stop-color: var(--svg-color--ba6e8e, #BA6E8E);
  stop-opacity: 0;
}

.bctddzirn {
  stop-color: var(--svg-color--9867f8, #9867F8);
  stop-opacity: 0;
}

.bgm6-ubvx {
  stop-color: var(--svg-color--9d5bef, #9D5BEF);
  stop-opacity: 0;
}

.c2ymzseoj {
  d: path("M16.645 22.903L10.36 15.41a.6.6 0 0 0-.822-.093l-.358.27a1 1 0 0 0-.398.799V29.74a.25.25 0 0 0 .41.192l7.38-6.184a.6.6 0 0 0 .074-.846");
}

.c8s6441kg {
  stop-color: var(--svg-color--8253ff, #8253FF);
  stop-opacity: 0;
}

.cc46tddta {
  stop-color: var(--svg-color--dea487, #DEA487);
  stop-opacity: 0;
}

.cp95w770i {
  stop-color: var(--svg-color--6c2ac4, #6C2AC4);
}

.cpbnylbqu {
  stop-color: var(--svg-color--9d5bef, #9D5BEF);
}

.d5z2kxb0h {
  stop-color: var(--svg-color--6d43ff, #6D43FF);
}

.dk3ah5owx {
  stop-color: var(--svg-color--6c2ac4, #6C2AC4);
  stop-opacity: 0;
}

.e4xcmebwj {
  width: 4.39px;
  height: 8.125px;
  rx: 2.195px;
}

.epaqfzjfn {
  stop-color: var(--svg-color--ffdcc4, #FFDCC4);
  stop-opacity: 0;
}

.eqwqidcpi {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m11.033 16.827l5.034 6.113");
}

.eud_w5b5b {
  width: 4.39px;
  height: 8.125px;
  x: 12.594px;
  y: 2.223px;
  rx: 2.195px;
}

.ew4asvbfm {
  stop-color: var(--svg-color--e7ae9e, #E7AE9E);
}

.ewlg17b4k {
  stop-color: var(--svg-color--9469ff, #9469FF);
}

.f3r2aydaz {
  stop-color: var(--svg-color--dea487, #DEA487);
}

.fhsjt5paq {
  stop-color: var(--svg-color--a578ff, #A578FF);
}

.fi6t2wbco {
  stop-color: var(--svg-color--d69880, #D69880);
}

.fiiy5zbbw {
  stop-color: var(--svg-color--ffdcc4, #FFDCC4);
}

.ft5dv1b6b {
  fill: none;
}

.g-bz5-b2k {
  stop-color: var(--svg-color--ffe3c6, #FFE3C6);
  stop-opacity: 0;
}

.j8pwmbb_m {
  stop-color: var(--svg-color--9867f8, #9867F8);
}

.jsiezd-_e {
  stop-color: var(--svg-color--eabc9e, #EABC9E);
}

.k_i_p7bcf {
  stop-color: var(--svg-color--f8ceb3, #F8CEB3);
}

.k03uj4bcp {
  stop-color: var(--svg-color--573eff, #573EFF);
}

.kapg7fbpl {
  stop-color: var(--svg-color--d69880, #D69880);
  stop-opacity: 0;
}

.ki9m_gb7k {
  stop-color: var(--svg-color--6236ae, #6236AE);
  stop-opacity: 0;
}

.kwu0ecbgx {
  d: path("M14.779 4.737a2.206 2.206 0 0 0-2.206 2.205v5.4a2 2 0 0 1-.69 1.512l-2.33 2.018l6.47 7.624l.654-.635a1 1 0 0 0 .323-.713c-.024-5.068-.016-10.137-.016-15.206a2.206 2.206 0 0 0-2.206-2.205");
}

.mla4tgzzc {
  stop-color: var(--svg-color--ffe3c8, #FFE3C8);
}

.mlsexxbpb {
  stop-color: var(--svg-color--f0bca5, #F0BCA5);
}

.ms07w1btv {
  stop-color: var(--svg-color--ffe3c8, #FFE3C8);
  stop-opacity: 0;
}

.n418v0b3f {
  d: path("m17.323 22.903l6.287-7.494a.6.6 0 0 1 .821-.093l.358.27a1 1 0 0 1 .398.799V29.74a.25.25 0 0 1-.41.192l-7.38-6.184a.6.6 0 0 1-.074-.846");
}

.nv25l8k6g {
  stop-color: var(--svg-color--ffe3c6, #FFE3C6);
}

.opu5b_bed {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
}

.ovde0_bdt {
  cx: 15.456px;
  cy: 3.855px;
  fill: var(--svg-color--ffdbbf, #FFDBBF);
  rx: 0.764px;
  ry: 1.019px;
}

.p-sgdu4ak {
  stop-color: var(--svg-color--f2bfa4, #F2BFA4);
}

.p5r1espwo {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.765 17.143v7.92");
}

.q9gpy7bkq {
  stop-color: var(--svg-color--6640a2, #6640A2);
}

.qxwbxgb_x {
  d: path("M14.147 6.66a1.066 1.066 0 0 1 2.132 0v12.503a2.284 2.284 0 0 1-4.272 1.124l-.643-1.137a3 3 0 0 1 .46-3.567l1.758-1.81a2 2 0 0 0 .565-1.393z");
}

.r2u3ribwc {
  cx: 19.849px;
  cy: 3.814px;
  rx: 0.828px;
  ry: 1.134px;
}

.ro5br2yzs {
  stop-color: var(--svg-color--ba6e8e, #BA6E8E);
}

.sxvugyb6w {
  stop-color: var(--svg-color--b97090, #B97090);
}

.t2er4acdn {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
  stop-opacity: 0;
}

.tyfxpdb0w {
  stop-color: var(--svg-color--6236ae, #6236AE);
}

.u94mo785n {
  stop-color: var(--svg-color--e1a889, #E1A889);
}

.uc5tunbpi {
  stop-color: var(--svg-color--ecba9f, #ECBA9F);
}

.w6o4myf_b {
  stop-color: var(--svg-color--8253ff, #8253FF);
}

.wci41ibjf {
  stop-color: var(--svg-color--9a69fb, #9A69FB);
  stop-opacity: 0;
}

.y9f8gy2ni {
  d: path("M20.898 6.831a1.066 1.066 0 0 0-2.132 0v6.64c0 .735.309 1.436.85 1.931l1.093 1.001a1.19 1.19 0 0 0 1.627-1.734l-.918-.882c-.332-.32-.52-.76-.52-1.221z");
}

</style>
