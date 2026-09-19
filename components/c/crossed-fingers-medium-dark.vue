<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixaT9Ib)" class="ud6449hwx"/><path fill="url(#iAcCxtd)" class="ud6449hwx"/><path fill="url(#iKStIQG)" class="ud6449hwx"/><path fill="url(#ioq4KOd)" class="ud6449hwx"/><path fill="url(#iTmfgRb)" class="ud6449hwx"/><path fill="url(#iEUCsoe)" class="ud6449hwx"/><g filter="url(#ip1GIWd)"><path class="wr8448b8l"/></g><g filter="url(#iC2tO8c)"><path class="mta58-bjn"/><path fill="url(#iS1yi7V)" class="eejosv2sa"/><path fill="url(#iJ68MNc)" class="eejosv2sa"/><path fill="url(#i7raSid)" class="eejosv2sa"/></g><g filter="url(#i0UkaCj)"><path class="o0m5se7_i"/></g><g filter="url(#iMBUIEA)"><path class="obhc15brq"/></g><g filter="url(#iAiiU4b)"><path class="rzgvsokpv"/></g><path class="i3-_t5agn"/><path fill="url(#iGM7mWd)" class="rh2h964-f"/><path fill="url(#iRCmoUb)" class="rh2h964-f"/><path fill="url(#itXHZFc)" class="rh2h964-f"/><path class="a942zobjl"/><path fill="url(#imY4Kte)" class="ueyp-cciv"/><path fill="url(#iAUGw7c)" class="ueyp-cciv"/><path fill="url(#ioF367b)" class="ueyp-cciv"/><g filter="url(#iBD3lyb)"><path class="sgktppb-k"/></g><path fill="url(#irNAhdb)" class="b5j_5bbsn"/><path fill="url(#i8v4nAb)" class="b5j_5bbsn"/><path fill="url(#ijBphed)" class="b5j_5bbsn"/><path fill="url(#i64ot1a)" class="b5j_5bbsn"/><g filter="url(#iEnhXCc)"><rect fill="url(#iqjDaRb)" class="ytlgtccqz"/></g><g filter="url(#isyHLJc)"><rect class="rq3y1en_n"/></g><path fill="url(#ibABE3s)" clip-rule="evenodd" class="lvp85ybie"/><path fill="url(#iDQPodb)" clip-rule="evenodd" class="lvp85ybie"/><g filter="url(#i1mOAUd)"><path stroke="url(#ikyuPwe)" class="asntwcb6j"/></g><path fill="url(#ipkdDQe)" class="iqa5olbwt"/><defs><radialGradient id="iAcCxtd" cx="0" cy="0" r="1" gradientTransform="rotate(-145.784 13.311 1.816)scale(7.55811 20.3298)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="pbyuwkbue"/><stop offset="1" class="qvi87ccvw"/></radialGradient><radialGradient id="iKStIQG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44892 .96594 -7.83612 -11.75422 20.112 11.58)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="z75fk4b-d"/><stop offset="1" class="s8scx1bpu"/><stop offset="1" class="ow1rghb4m"/></radialGradient><radialGradient id="ioq4KOd" cx="0" cy="0" r="1" gradientTransform="rotate(148.855 8.288 8.62)scale(1.26883 10.2933)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="qh_v_ybmp"/><stop offset=".652" class="g5k97gebt"/></radialGradient><radialGradient id="iTmfgRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.26935 1.63468 0 19.183 14.811)" gradientUnits="userSpaceOnUse"><stop class="ksbpoih5h"/><stop offset="1" class="u3dlze20h"/></radialGradient><radialGradient id="iEUCsoe" cx="0" cy="0" r="1" gradientTransform="rotate(128.409 12.3 7.472)scale(3.53833 4.6463)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="j-qaxebpg"/><stop offset="1" class="ygn0rzcig"/></radialGradient><radialGradient id="iS1yi7V" cx="0" cy="0" r="1" gradientTransform="matrix(9.31253 10.06253 -14.13907 13.08522 6.674 14.563)" gradientUnits="userSpaceOnUse"><stop class="qpc5u4x8h"/><stop offset="1" class="mn4fm1n0u"/></radialGradient><radialGradient id="iJ68MNc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53125 0 0 -2.78125 20.69 20.772)" gradientUnits="userSpaceOnUse"><stop class="y8yymsbkp"/><stop offset="1" class="f5plm9-fv"/></radialGradient><radialGradient id="i7raSid" cx="0" cy="0" r="1" gradientTransform="matrix(.61472 -8.4666 16.95696 1.23117 14.35 29.957)" gradientUnits="userSpaceOnUse"><stop class="q2w23abcf"/><stop offset="1" class="ctbdhnbrj"/></radialGradient><radialGradient id="iRCmoUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.14698 -4.32661 0 8.6 10.5)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="txojg_b2d"/><stop offset="1" class="tsiazhbsu"/></radialGradient><radialGradient id="itXHZFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.375 0 0 -3.75 10.86 12.709)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="adcg5jb5w"/><stop offset="1" class="isr859e2o"/></radialGradient><radialGradient id="imY4Kte" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.80191 -4.23235 0 13.16 9.572)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="v35an2b5h"/><stop offset="1" class="np0g39_mk"/></radialGradient><radialGradient id="ioF367b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16274 -.82077 1.14253 -1.61856 15.584 15.888)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="wg65kkbwa"/><stop offset="1" class="p0acc8bzx"/></radialGradient><radialGradient id="irNAhdb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45453 6.27643 -14.57501 -5.69986 23.459 14.946)" gradientUnits="userSpaceOnUse"><stop class="j91wkyvib"/><stop offset="1" class="e-1krccpq"/></radialGradient><radialGradient id="ijBphed" cx="0" cy="0" r="1" gradientTransform="matrix(2.53066 1.77831 -3.77054 5.36574 14.643 14.622)" gradientUnits="userSpaceOnUse"><stop class="rgcbzi4wz"/><stop offset="1" class="u9frl-isj"/></radialGradient><radialGradient id="i64ot1a" cx="0" cy="0" r="1" gradientTransform="matrix(.90292 -.5788 .91809 1.43221 15.373 17.92)" gradientUnits="userSpaceOnUse"><stop class="khmw94b_w"/><stop offset="1" class="a4fbkgbsw"/></radialGradient><radialGradient id="ibABE3s" cx="0" cy="0" r="1" gradientTransform="rotate(-8.84 118.13 -28.67)scale(20.9074 21.9078)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="qhreg282s"/><stop offset="1" class="wqdvlq5ms"/></radialGradient><radialGradient id="iDQPodb" cx="0" cy="0" r="1" gradientTransform="matrix(-16.56248 5.49997 -10.06467 -30.30848 22.986 18.25)" gradientUnits="userSpaceOnUse"><stop offset=".853" class="tw4snvbku"/><stop offset="1" class="uefvz4bvs"/></radialGradient><radialGradient id="ipkdDQe" cx="0" cy="0" r="1" gradientTransform="matrix(3.09542 -1.98245 5.36717 8.38035 17.135 10.598)" gradientUnits="userSpaceOnUse"><stop class="u2qomm69t"/><stop offset="1" class="nof768djk"/></radialGradient><filter id="ip1GIWd" width="9.747" height="10.915" x="17.071" y="1.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2220" stdDeviation="1"/></filter><filter id="iC2tO8c" width="20.855" height="28.619" x="5.809" y="1.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.25098 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2220"/></filter><filter id="i0UkaCj" width="14.735" height="10.475" x="11.692" y="13.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2220" stdDeviation="1"/></filter><filter id="iMBUIEA" width="7.158" height="9.171" x="5.362" y="8.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2220" stdDeviation=".5"/></filter><filter id="iAiiU4b" width="9.128" height="11.13" x="7.814" y="8.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2220" stdDeviation="1"/></filter><filter id="iBD3lyb" width="11.711" height="22.797" x="15.717" y="1.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2220" stdDeviation="1"/></filter><filter id="iEnhXCc" width="3.86" height="6.984" x="7.204" y="9.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2220" stdDeviation=".625"/></filter><filter id="isyHLJc" width="5.193" height="8.957" x="11.616" y="7.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2220" stdDeviation=".875"/></filter><filter id="i1mOAUd" width="11.553" height="9.797" x="15.722" y="13.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2220" stdDeviation="1"/></filter><linearGradient id="ixaT9Ib" x1="18.305" x2="25.014" y1="12.488" y2="3.296" gradientUnits="userSpaceOnUse"><stop class="bzyznjz2b"/><stop offset="1" class="f05gracxc"/></linearGradient><linearGradient id="iGM7mWd" x1="5.809" x2="8.141" y1="13.365" y2="13.365" gradientUnits="userSpaceOnUse"><stop class="vxz4fbnaf"/><stop offset="1" class="dwir1wbts"/></linearGradient><linearGradient id="iAUGw7c" x1="9.93" x2="12.694" y1="12.87" y2="12.87" gradientUnits="userSpaceOnUse"><stop class="oup8pdbac"/><stop offset="1" class="xmajhtbhe"/></linearGradient><linearGradient id="i8v4nAb" x1="23.364" x2="23.364" y1="23.24" y2="20.163" gradientUnits="userSpaceOnUse"><stop class="mmd087bli"/><stop offset="1" class="e0zag61xl"/></linearGradient><linearGradient id="iqjDaRb" x1="9.483" x2="9.483" y1="14.567" y2="10.496" gradientUnits="userSpaceOnUse"><stop class="xqw6lsjsq"/><stop offset="1" class="l2e5tebmb"/></linearGradient><linearGradient id="ikyuPwe" x1="17.652" x2="24.843" y1="16.011" y2="19.747" gradientUnits="userSpaceOnUse"><stop class="ep4r49b6b"/><stop offset="1" class="v9v3t3bso"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crossed-fingers-medium-dark" /></template>
<style>
.a4fbkgbsw {
  stop-color: var(--svg-color--764e4f, #764E4F);
  stop-opacity: 0;
}

.a942zobjl {
  fill: var(--svg-color--906959, #906959);
  d: path("M10.32 10.924c0-1.646 1.272-2.98 2.84-2.98c1.569 0 2.84 1.334 2.84 2.98v2.742c0 1.646-1.271 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.adcg5jb5w {
  stop-color: var(--svg-color--583029, #583029);
}

.asntwcb6j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.722 16.01h.614c2.03 0 4.2.588 4.724 2.548c.1.373.175.788.214 1.25");
}

.b5j_5bbsn {
  d: path("M17.813 13.49a2.984 2.984 0 1 0 0 5.969h1.59a1 1 0 0 1 .788.385l2.045 2.622c1.17 1.5 3.577.673 3.577-1.23V19.49a6 6 0 0 0-5.212-5.948a3 3 0 0 0-.554-.052z");
}

.bzyznjz2b {
  stop-color: var(--svg-color--613b2f, #613B2F);
}

.ctbdhnbrj {
  stop-color: var(--svg-color--885561, #885561);
  stop-opacity: 0;
}

.dwir1wbts {
  stop-color: var(--svg-color--75564b, #75564B);
  stop-opacity: 0;
}

.e-1krccpq {
  stop-color: var(--svg-color--723c56, #723C56);
}

.e0zag61xl {
  stop-color: var(--svg-color--8f6060, #8F6060);
  stop-opacity: 0;
}

.eejosv2sa {
  d: path("m5.997 20.832l-.188-5.115v-1.555h14.469c.01-.844-1.844-4.115-4.254-7.32c-1.422-1.89-.62-3.566.516-4.305c1.476-.96 3.218-.25 3.945.899c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.397-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.139-9.658-9.126");
}

.ep4r49b6b {
  stop-color: var(--svg-color--a47f74, #A47F74);
}

.f05gracxc {
  stop-color: var(--svg-color--956a5c, #956A5C);
}

.f5plm9-fv {
  stop-color: var(--svg-color--845b5f, #845B5F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g5k97gebt {
  stop-color: var(--svg-color--65433a, #65433A);
  stop-opacity: 0;
}

.i3-_t5agn {
  fill: var(--svg-color--7b584c, #7B584C);
  d: path("M5.81 11.674c0-1.43 1.249-2.59 2.79-2.59c1.542 0 2.791 1.16 2.791 2.59v2.383c0 1.43-1.25 2.59-2.79 2.59c-1.542 0-2.792-1.16-2.792-2.59z");
}

.iqa5olbwt {
  d: path("M20.112 13.49c1.027.113 3.179.378 4.779 2.76c.887-7.738-4.406-12.814-4.406-12.814c-.727-1.149-2.469-1.86-3.945-.899c-1.136.74-1.938 2.414-.516 4.305c1.979 2.631 3.583 5.308 4.088 6.648");
}

.isr859e2o {
  stop-color: var(--svg-color--583029, #583029);
  stop-opacity: 0;
}

.j-qaxebpg {
  stop-color: var(--svg-color--9f7b6a, #9F7B6A);
}

.j91wkyvib {
  stop-color: var(--svg-color--87614e, #87614E);
}

.khmw94b_w {
  stop-color: var(--svg-color--764e4f, #764E4F);
}

.ksbpoih5h {
  stop-color: var(--svg-color--896c5e, #896C5E);
}

.l2e5tebmb {
  stop-color: var(--svg-color--906c6a, #906C6A);
  stop-opacity: 0;
}

.lvp85ybie {
  fill-rule: evenodd;
  d: path("m5.997 20.832l-.188-5.115v-1.555h.002c.06 1.382 1.286 2.484 2.79 2.484c.966 0 1.818-.456 2.319-1.149c.52.7 1.33 1.15 2.24 1.15c1.408 0 2.576-1.075 2.8-2.485h4.318c.01-.844-1.844-4.115-4.254-7.32c-1.422-1.89-.62-3.566.516-4.305c1.476-.96 3.218-.25 3.945.899c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.397-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.139-9.658-9.126");
}

.mmd087bli {
  stop-color: var(--svg-color--8f6060, #8F6060);
}

.mn4fm1n0u {
  stop-color: var(--svg-color--6b4645, #6B4645);
  stop-opacity: 0;
}

.mta58-bjn {
  fill: var(--svg-color--8f6060, #8F6060);
  d: path("m5.997 20.832l-.188-5.115v-1.555h14.469c.01-.844-1.844-4.115-4.254-7.32c-1.422-1.89-.62-3.566.516-4.305c1.476-.96 3.218-.25 3.945.899c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.397-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.139-9.658-9.126");
}

.nof768djk {
  stop-color: var(--svg-color--593227, #593227);
  stop-opacity: 0;
}

.np0g39_mk {
  stop-color: var(--svg-color--703d54, #703D54);
}

.o0m5se7_i {
  fill: var(--svg-color--51292f, #51292F);
  d: path("M16.829 15.115c-1.733 0-3.137 1.246-3.137 2.783s1.404 2.782 3.137 2.782h1.67c2.526 0 3.18.133 3.38.36l1.535-.178c1.23 1.399.996.651.996-1.123v-.505c0-2.84-1.56-3.71-4.65-4.07a3.5 3.5 0 0 0-.583-.049z");
}

.obhc15brq {
  fill: var(--svg-color--51292f, #51292F);
  d: path("M6.362 12.165c0-1.356 1.154-2.456 2.579-2.456c1.424 0 2.579 1.1 2.579 2.456v2.26c0 1.356-1.155 2.455-2.58 2.455c-1.424 0-2.578-1.1-2.578-2.455z");
}

.oup8pdbac {
  stop-color: var(--svg-color--725246, #725246);
}

.ow1rghb4m {
  stop-color: var(--svg-color--522d26, #522D26);
  stop-opacity: 0;
}

.p0acc8bzx {
  stop-color: var(--svg-color--532a23, #532A23);
  stop-opacity: 0;
}

.pbyuwkbue {
  stop-color: var(--svg-color--755a50, #755A50);
  stop-opacity: 0;
}

.q2w23abcf {
  stop-color: var(--svg-color--885561, #885561);
}

.qh_v_ybmp {
  stop-color: var(--svg-color--65433a, #65433A);
}

.qhreg282s {
  stop-color: var(--svg-color--a07e6f, #A07E6F);
  stop-opacity: 0;
}

.qpc5u4x8h {
  stop-color: var(--svg-color--6b4645, #6B4645);
}

.qvi87ccvw {
  stop-color: var(--svg-color--755a50, #755A50);
}

.rgcbzi4wz {
  stop-color: var(--svg-color--613b31, #613B31);
}

.rh2h964-f {
  d: path("M5.81 11.674c0-1.43 1.249-2.59 2.79-2.59c1.542 0 2.791 1.16 2.791 2.59v2.383c0 1.43-1.25 2.59-2.79 2.59c-1.542 0-2.792-1.16-2.792-2.59z");
}

.rq3y1en_n {
  width: 1.693px;
  height: 5.457px;
  x: 13.366px;
  y: 9.523px;
  fill: var(--svg-color--a47f74, #A47F74);
  rx: 0.847px;
}

.rzgvsokpv {
  fill: var(--svg-color--51292f, #51292F);
  d: path("M9.814 12.923c0-1.348 1.148-2.441 2.564-2.441s2.564 1.093 2.564 2.441v2.247c0 1.348-1.148 2.442-2.564 2.442s-2.564-1.093-2.564-2.442z");
}

.s8scx1bpu {
  stop-color: var(--svg-color--261716, #261716);
  stop-opacity: 0;
}

.sgktppb-k {
  stroke: var(--svg-color--a27e72, #A27E72);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.717 4.239c2.11 2.245 4.896 6.194 5.22 9.602c.345 3.616.613 6.275.433 7.194");
}

.tsiazhbsu {
  stop-color: var(--svg-color--6f384f, #6F384F);
}

.tw4snvbku {
  stop-color: var(--svg-color--825a59, #825A59);
  stop-opacity: 0;
}

.txojg_b2d {
  stop-color: var(--svg-color--6f384f, #6F384F);
  stop-opacity: 0;
}

.u2qomm69t {
  stop-color: var(--svg-color--593227, #593227);
}

.u3dlze20h {
  stop-color: var(--svg-color--896c5e, #896C5E);
  stop-opacity: 0;
}

.u9frl-isj {
  stop-color: var(--svg-color--613b31, #613B31);
  stop-opacity: 0;
}

.ud6449hwx {
  d: path("M20.798 2.92c-2.137 2.178-4.641 5.148-5.516 8.633l-.223 2.765h5.031c1.032-1.822 2.813-5.32 4.575-7.304c1.762-1.985.555-3.778-.067-4.309c-.43-.367-2.222-1.394-3.8.215");
}

.uefvz4bvs {
  stop-color: var(--svg-color--825a59, #825A59);
}

.ueyp-cciv {
  d: path("M10.32 10.924c0-1.646 1.272-2.98 2.84-2.98c1.569 0 2.84 1.334 2.84 2.98v2.742c0 1.646-1.271 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.v35an2b5h {
  stop-color: var(--svg-color--703d54, #703D54);
  stop-opacity: 0;
}

.v9v3t3bso {
  stop-color: var(--svg-color--a47f74, #A47F74);
  stop-opacity: 0;
}

.vxz4fbnaf {
  stop-color: var(--svg-color--75564b, #75564B);
}

.wg65kkbwa {
  stop-color: var(--svg-color--532a23, #532A23);
}

.wqdvlq5ms {
  stop-color: var(--svg-color--a07e6f, #A07E6F);
}

.wr8448b8l {
  stroke: var(--svg-color--9e7d6f, #9E7D6F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M23.567 4.669c-.928 1.152-1.946 2.62-3.246 4.415");
}

.xmajhtbhe {
  stop-color: var(--svg-color--725246, #725246);
  stop-opacity: 0;
}

.xqw6lsjsq {
  stop-color: var(--svg-color--916c6a, #916C6A);
}

.y8yymsbkp {
  stop-color: var(--svg-color--845b5f, #845B5F);
}

.ygn0rzcig {
  stop-color: var(--svg-color--9f7b6a, #9F7B6A);
  stop-opacity: 0;
}

.ytlgtccqz {
  width: 1.36px;
  height: 4.484px;
  x: 8.454px;
  y: 10.496px;
  rx: 0.68px;
}

.z75fk4b-d {
  stop-color: var(--svg-color--522d26, #522D26);
}

</style>
