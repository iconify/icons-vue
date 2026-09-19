<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect class="n5pfnlb-l"/><rect fill="url(#iF8nhJc)" class="eud_w5b5b"/><path fill="url(#iTIaNZb)" class="kwu0ecbgx"/><path fill="url(#itBg0Dc)" class="kwu0ecbgx"/><path fill="url(#izS0Abe)" class="kwu0ecbgx"/><rect transform="matrix(-1 0 0 1 21.375 2.223)" class="nsg8_tbyk"/><rect fill="url(#ioXlHJd)" transform="matrix(-1 0 0 1 21.375 2.223)" class="e4xcmebwj"/><rect fill="url(#iCwC1kK)" transform="matrix(-1 0 0 1 21.375 2.223)" class="e4xcmebwj"/><path fill="url(#iyy8gxu)" class="aya86ob_i"/><path fill="url(#iqRT7hb)" class="aya86ob_i"/><g filter="url(#iSGCyHb)"><path stroke="url(#irKZvXN)" class="p5r1espwo"/></g><g filter="url(#iy7cAwc)"><path stroke="url(#iLB5T0c)" class="eqwqidcpi"/></g><g filter="url(#i2m1Jwd)"><path fill="url(#iGlNmKc)" class="eqto79wbm"/></g><g filter="url(#iWIfZEc)"><path fill="url(#icISBXR)" class="qxwbxgb_x"/></g><g filter="url(#ikIW9ie)"><ellipse fill="url(#iJ6E1Oc)" transform="rotate(-39.49 19.849 3.814)" class="r2u3ribwc"/></g><g filter="url(#iGqiHne)"><ellipse transform="rotate(-39.49 15.456 3.855)" class="glmfhjaic"/></g><path fill="url(#irQWWGv)" class="c2ymzseoj"/><path fill="url(#iuSxZld)" class="c2ymzseoj"/><path fill="url(#izNVhmg)" class="c2ymzseoj"/><path fill="url(#iylUNWc)" class="c2ymzseoj"/><path fill="url(#iuwFvwc)" class="c2ymzseoj"/><path fill="url(#iGE9STf)" class="n418v0b3f"/><path fill="url(#ilma3Md)" class="n418v0b3f"/><path fill="url(#iSNOo9d)" class="n418v0b3f"/><path fill="url(#iEIz0mc)" class="n418v0b3f"/><defs><linearGradient id="iF8nhJc" x1="14.453" x2="14.453" y1="6.938" y2="4" gradientUnits="userSpaceOnUse"><stop class="d7kakebat"/><stop offset="1" class="zweebwbov"/></linearGradient><linearGradient id="iTIaNZb" x1="13.269" x2="13.269" y1="5.125" y2="16.702" gradientUnits="userSpaceOnUse"><stop class="cloiw-bik"/><stop offset="1" class="bm_8rcs5d"/></linearGradient><linearGradient id="izS0Abe" x1="16.984" x2="16.297" y1="12.544" y2="12.544" gradientUnits="userSpaceOnUse"><stop class="a4svzgbor"/><stop offset="1" class="kb7lyjwig"/></linearGradient><linearGradient id="ioXlHJd" x1="2.922" x2="2.922" y1="6.09" y2="1.496" gradientUnits="userSpaceOnUse"><stop class="e3tt6hbar"/><stop offset="1" class="kw-ew0zug"/></linearGradient><linearGradient id="iyy8gxu" x1="20.699" x2="20.699" y1="8.915" y2="24.762" gradientUnits="userSpaceOnUse"><stop class="cloiw-bik"/><stop offset="1" class="bm_8rcs5d"/></linearGradient><linearGradient id="irKZvXN" x1="25.265" x2="25.265" y1="16.348" y2="25.857" gradientUnits="userSpaceOnUse"><stop class="wci41ibjf"/><stop offset=".49" class="fhsjt5paq"/><stop offset="1" class="wci41ibjf"/></linearGradient><linearGradient id="iLB5T0c" x1="10.914" x2="16.958" y1="15.896" y2="23.236" gradientUnits="userSpaceOnUse"><stop offset=".214" class="bctddzirn"/><stop offset=".49" class="j8pwmbb_m"/><stop offset=".776" class="bctddzirn"/></linearGradient><linearGradient id="iGlNmKc" x1="20.954" x2="20.954" y1="5.765" y2="24.331" gradientUnits="userSpaceOnUse"><stop class="tp32gibdm"/><stop offset="1" class="ij06bg9_u"/></linearGradient><linearGradient id="icISBXR" x1="16.759" x2="12.234" y1="6.778" y2="31.761" gradientUnits="userSpaceOnUse"><stop class="zyjhg7fdy"/><stop offset="1" class="wdjpwrb9j"/></linearGradient><linearGradient id="iJ6E1Oc" x1="19.849" x2="19.849" y1="2.68" y2="6.352" gradientUnits="userSpaceOnUse"><stop class="j_6u7db_l"/><stop offset="1" class="t28nszcry"/></linearGradient><linearGradient id="irQWWGv" x1="7.609" x2="13.234" y1="15.195" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="q9gpy7bkq"/><stop offset="1" class="d5z2kxb0h"/></linearGradient><linearGradient id="iuSxZld" x1="13.633" x2="12.784" y1="18.983" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iylUNWc" x1="8.357" x2="9.211" y1="22.593" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="tyfxpdb0w"/><stop offset="1" class="ki9m_gb7k"/></linearGradient><linearGradient id="iuwFvwc" x1="13.297" x2="12.992" y1="26.703" y2="26.359" gradientUnits="userSpaceOnUse"><stop class="opu5b_bed"/><stop offset="1" class="t2er4acdn"/></linearGradient><linearGradient id="iGE9STf" x1="23.735" x2="19.084" y1="18.733" y2="28.212" gradientUnits="userSpaceOnUse"><stop class="b1lbi7bol"/><stop offset="1" class="k03uj4bcp"/></linearGradient><linearGradient id="iSNOo9d" x1="20.335" x2="20.88" y1="18.983" y2="19.439" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iEIz0mc" x1="20.672" x2="20.914" y1="26.703" y2="26.422" gradientUnits="userSpaceOnUse"><stop class="ewlg17b4k"/><stop offset="1" class="b5b0myb0o"/></linearGradient><filter id="iSGCyHb" width=".65" height="8.419" x="24.44" y="16.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4060" stdDeviation=".125"/></filter><filter id="iy7cAwc" width="5.65" height="6.709" x="10.725" y="16.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4060" stdDeviation=".125"/></filter><filter id="i2m1Jwd" width="6.934" height="13.95" x="17.266" y="4.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4060" stdDeviation=".75"/></filter><filter id="iWIfZEc" width="8.303" height="18.853" x="9.476" y="4.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4060" stdDeviation=".75"/></filter><filter id="ikIW9ie" width="3.928" height="4.044" x="17.885" y="1.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4060" stdDeviation=".5"/></filter><filter id="iGqiHne" width="3.753" height="3.85" x="13.579" y="1.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4060" stdDeviation=".5"/></filter><radialGradient id="itBg0Dc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 15.865 23.496)" gradientUnits="userSpaceOnUse"><stop class="wg70sx3qq"/><stop offset="1" class="c6l0jfpnu"/></radialGradient><radialGradient id="iCwC1kK" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28212 -3.24419 3.42677 -3.46684 3.636 3.244)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="db563qb2s"/><stop offset=".907" class="vq6b4tbeu"/></radialGradient><radialGradient id="iqRT7hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 18.103 23.496)" gradientUnits="userSpaceOnUse"><stop class="syw9l1bgq"/><stop offset="1" class="k_ssu0baz"/></radialGradient><radialGradient id="izNVhmg" cx="0" cy="0" r="1" gradientTransform="rotate(-45 34.16 1.731)scale(8.65467 3.14404)" gradientUnits="userSpaceOnUse"><stop class="w6o4myf_b"/><stop offset="1" class="c8s6441kg"/></radialGradient><radialGradient id="ilma3Md" cx="0" cy="0" r="1" gradientTransform="matrix(4.15623 3.31253 -1.73902 2.18195 22.078 17.063)" gradientUnits="userSpaceOnUse"><stop class="cpbnylbqu"/><stop offset="1" class="bgm6-ubvx"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:folded-hands-medium-dark" /></template>
<style>
.a4svzgbor {
  stop-color: var(--svg-color--67443e, #67443E);
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

.bctddzirn {
  stop-color: var(--svg-color--9867f8, #9867F8);
  stop-opacity: 0;
}

.bgm6-ubvx {
  stop-color: var(--svg-color--9d5bef, #9D5BEF);
  stop-opacity: 0;
}

.bm_8rcs5d {
  stop-color: var(--svg-color--835952, #835952);
}

.c2ymzseoj {
  d: path("M16.645 22.903L10.36 15.41a.6.6 0 0 0-.822-.093l-.358.27a1 1 0 0 0-.398.799V29.74a.25.25 0 0 0 .41.192l7.38-6.184a.6.6 0 0 0 .074-.846");
}

.c6l0jfpnu {
  stop-color: var(--svg-color--683754, #683754);
  stop-opacity: 0;
}

.c8s6441kg {
  stop-color: var(--svg-color--8253ff, #8253FF);
  stop-opacity: 0;
}

.cloiw-bik {
  stop-color: var(--svg-color--805b4d, #805B4D);
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

.d7kakebat {
  stop-color: var(--svg-color--402519, #402519);
}

.db563qb2s {
  stop-color: var(--svg-color--997868, #997868);
  stop-opacity: 0;
}

.dk3ah5owx {
  stop-color: var(--svg-color--6c2ac4, #6C2AC4);
  stop-opacity: 0;
}

.e3tt6hbar {
  stop-color: var(--svg-color--523022, #523022);
}

.e4xcmebwj {
  width: 4.39px;
  height: 8.125px;
  rx: 2.195px;
}

.eqto79wbm {
  d: path("M20.898 6.831a1.066 1.066 0 0 0-2.132 0v6.641c0 .734.309 1.435.85 1.93l1.093 1.001a1.19 1.19 0 0 0 1.627-1.734l-.918-.882c-.332-.32-.52-.76-.52-1.221z");
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

.ewlg17b4k {
  stop-color: var(--svg-color--9469ff, #9469FF);
}

.fhsjt5paq {
  stop-color: var(--svg-color--a578ff, #A578FF);
}

.ft5dv1b6b {
  fill: none;
}

.glmfhjaic {
  cx: 15.456px;
  cy: 3.855px;
  fill: var(--svg-color--997a6b, #997A6B);
  rx: 0.764px;
  ry: 1.019px;
}

.ij06bg9_u {
  stop-color: var(--svg-color--9f7b70, #9F7B70);
  stop-opacity: 0;
}

.j_6u7db_l {
  stop-color: var(--svg-color--9e7a6a, #9E7A6A);
}

.j8pwmbb_m {
  stop-color: var(--svg-color--9867f8, #9867F8);
}

.k_ssu0baz {
  stop-color: var(--svg-color--602859, #602859);
  stop-opacity: 0;
}

.k03uj4bcp {
  stop-color: var(--svg-color--573eff, #573EFF);
}

.kb7lyjwig {
  stop-color: var(--svg-color--67443e, #67443E);
  stop-opacity: 0;
}

.ki9m_gb7k {
  stop-color: var(--svg-color--6236ae, #6236AE);
  stop-opacity: 0;
}

.kw-ew0zug {
  stop-color: var(--svg-color--523022, #523022);
  stop-opacity: 0;
}

.kwu0ecbgx {
  d: path("M14.779 4.737a2.206 2.206 0 0 0-2.206 2.205v5.4a2 2 0 0 1-.69 1.512l-2.33 2.018l6.47 7.624l.654-.635a1 1 0 0 0 .323-.713c-.024-5.068-.016-10.137-.016-15.206a2.206 2.206 0 0 0-2.206-2.205");
}

.n418v0b3f {
  d: path("m17.323 22.903l6.287-7.494a.6.6 0 0 1 .821-.093l.358.27a1 1 0 0 1 .398.799V29.74a.25.25 0 0 1-.41.192l-7.38-6.184a.6.6 0 0 1-.074-.846");
}

.n5pfnlb-l {
  width: 4.39px;
  height: 8.125px;
  x: 12.594px;
  y: 2.223px;
  fill: var(--svg-color--714e42, #714E42);
  rx: 2.195px;
}

.nsg8_tbyk {
  width: 4.39px;
  height: 8.125px;
  fill: var(--svg-color--654338, #654338);
  rx: 2.195px;
}

.opu5b_bed {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
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

.syw9l1bgq {
  stop-color: var(--svg-color--602859, #602859);
}

.t28nszcry {
  stop-color: var(--svg-color--9e7a6a, #9E7A6A);
  stop-opacity: 0;
}

.t2er4acdn {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
  stop-opacity: 0;
}

.tp32gibdm {
  stop-color: var(--svg-color--9f7b70, #9F7B70);
}

.tyfxpdb0w {
  stop-color: var(--svg-color--6236ae, #6236AE);
}

.vq6b4tbeu {
  stop-color: var(--svg-color--997868, #997868);
}

.w6o4myf_b {
  stop-color: var(--svg-color--8253ff, #8253FF);
}

.wci41ibjf {
  stop-color: var(--svg-color--9a69fb, #9A69FB);
  stop-opacity: 0;
}

.wdjpwrb9j {
  stop-color: var(--svg-color--9d7b6f, #9D7B6F);
  stop-opacity: 0;
}

.wg70sx3qq {
  stop-color: var(--svg-color--683754, #683754);
}

.zweebwbov {
  stop-color: var(--svg-color--402519, #402519);
  stop-opacity: 0;
}

.zyjhg7fdy {
  stop-color: var(--svg-color--9d7b6f, #9D7B6F);
}

</style>
