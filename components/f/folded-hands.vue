<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect class="i5d79dbps"/><rect fill="url(#ip0Clqe)" class="ptvfwgbhs"/><path fill="url(#ikpLiQc)" class="wb4fvkb5s"/><path fill="url(#i2AcIxz)" class="wb4fvkb5s"/><path fill="url(#iwlYY7c)" class="wb4fvkb5s"/><rect transform="matrix(-1 0 0 1 20.875 2.223)" class="krjc9rbvv"/><rect fill="url(#iKgLyxc)" transform="matrix(-1 0 0 1 20.875 2.223)" class="e4xcmebwj"/><rect fill="url(#iM8aAic)" transform="matrix(-1 0 0 1 20.875 2.223)" class="e4xcmebwj"/><path fill="url(#iqKPFBc)" class="sq3revbau"/><path fill="url(#i4iLqNc)" class="sq3revbau"/><g filter="url(#igTu2oc)"><path stroke="url(#ikFF1Je)" class="x8eka5b5x"/></g><g filter="url(#i15Sp5d)"><path stroke="url(#i4552qB)" class="t-oc4zkkq"/></g><g filter="url(#iM5Z9oe)"><path fill="url(#ivGg0sA)" class="luc6otb8q"/></g><g filter="url(#iDbHOzd)"><path fill="url(#iosfoIe)" class="vkslctbjc"/></g><g filter="url(#igE5bFe)"><ellipse fill="url(#iJfRayd)" transform="rotate(-39.49 19.35 3.814)" class="p_14uvbpk"/></g><g filter="url(#igoKUmb)"><ellipse transform="rotate(-39.49 15.005 3.814)" class="wseblkogy"/></g><path fill="url(#izgjoXb)" class="jxq7atbey"/><path fill="url(#iUA2Czc)" class="jxq7atbey"/><path fill="url(#iLTicQc)" class="jxq7atbey"/><path fill="url(#iPEbpIc)" class="jxq7atbey"/><path fill="url(#ityvSGd)" class="jxq7atbey"/><path fill="url(#iyD4HKe)" class="ci5amtxdu"/><path fill="url(#ipIlaoc)" class="ci5amtxdu"/><path fill="url(#imIYmMd)" class="ci5amtxdu"/><path fill="url(#izPQdDa)" class="ci5amtxdu"/><defs><linearGradient id="ip0Clqe" x1="13.953" x2="13.953" y1="6.938" y2="4" gradientUnits="userSpaceOnUse"><stop class="gl85jdbev"/><stop offset="1" class="ddr08xbmr"/></linearGradient><linearGradient id="ikpLiQc" x1="12.769" x2="12.769" y1="5.125" y2="22" gradientUnits="userSpaceOnUse"><stop class="b8excebxy"/><stop offset="1" class="gnpix7i2k"/></linearGradient><linearGradient id="iwlYY7c" x1="16.484" x2="15.797" y1="12.544" y2="12.544" gradientUnits="userSpaceOnUse"><stop class="rnyiy3b0d"/><stop offset="1" class="xh1qmcchw"/></linearGradient><linearGradient id="iKgLyxc" x1="2.922" x2="2.922" y1="6.09" y2="1.496" gradientUnits="userSpaceOnUse"><stop class="ip-obw-bu"/><stop offset="1" class="ehcwi7mvr"/></linearGradient><linearGradient id="iqKPFBc" x1="20.2" x2="20.2" y1="8.915" y2="24.762" gradientUnits="userSpaceOnUse"><stop class="b115ghbqh"/><stop offset="1" class="gnpix7i2k"/></linearGradient><linearGradient id="ikFF1Je" x1="24.766" x2="24.766" y1="16.348" y2="25.857" gradientUnits="userSpaceOnUse"><stop class="wci41ibjf"/><stop offset=".49" class="fhsjt5paq"/><stop offset="1" class="wci41ibjf"/></linearGradient><linearGradient id="i4552qB" x1="10.414" x2="16.459" y1="15.896" y2="23.236" gradientUnits="userSpaceOnUse"><stop offset=".214" class="bctddzirn"/><stop offset=".49" class="j8pwmbb_m"/><stop offset=".776" class="bctddzirn"/></linearGradient><linearGradient id="ivGg0sA" x1="20.455" x2="20.455" y1="5.765" y2="24.331" gradientUnits="userSpaceOnUse"><stop class="yril9lbdq"/><stop offset="1" class="is5kyac3c"/></linearGradient><linearGradient id="iosfoIe" x1="16.047" x2="11.523" y1="6.778" y2="31.761" gradientUnits="userSpaceOnUse"><stop class="sspv43s2v"/><stop offset="1" class="ealucwtke"/></linearGradient><linearGradient id="iJfRayd" x1="19.349" x2="19.349" y1="2.68" y2="6.352" gradientUnits="userSpaceOnUse"><stop class="yril9lbdq"/><stop offset="1" class="is5kyac3c"/></linearGradient><linearGradient id="izgjoXb" x1="7.109" x2="12.734" y1="15.195" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="q9gpy7bkq"/><stop offset="1" class="d5z2kxb0h"/></linearGradient><linearGradient id="iUA2Czc" x1="13.134" x2="12.284" y1="18.983" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iPEbpIc" x1="7.857" x2="8.711" y1="22.593" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="tyfxpdb0w"/><stop offset="1" class="ki9m_gb7k"/></linearGradient><linearGradient id="ityvSGd" x1="12.797" x2="12.492" y1="26.703" y2="26.359" gradientUnits="userSpaceOnUse"><stop class="opu5b_bed"/><stop offset="1" class="t2er4acdn"/></linearGradient><linearGradient id="iyD4HKe" x1="23.235" x2="18.584" y1="18.733" y2="28.212" gradientUnits="userSpaceOnUse"><stop class="b1lbi7bol"/><stop offset="1" class="k03uj4bcp"/></linearGradient><linearGradient id="imIYmMd" x1="19.835" x2="20.38" y1="18.983" y2="19.439" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="izPQdDa" x1="20.172" x2="20.414" y1="26.703" y2="26.422" gradientUnits="userSpaceOnUse"><stop class="ewlg17b4k"/><stop offset="1" class="b5b0myb0o"/></linearGradient><filter id="igTu2oc" width=".65" height="8.419" x="23.941" y="16.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4034" stdDeviation=".125"/></filter><filter id="i15Sp5d" width="5.65" height="6.709" x="10.226" y="16.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4034" stdDeviation=".125"/></filter><filter id="iM5Z9oe" width="6.934" height="13.95" x="16.767" y="4.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4034" stdDeviation=".75"/></filter><filter id="iDbHOzd" width="8.303" height="18.853" x="8.764" y="4.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4034" stdDeviation=".75"/></filter><filter id="igE5bFe" width="3.928" height="4.044" x="17.385" y="1.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4034" stdDeviation=".5"/></filter><filter id="igoKUmb" width="3.928" height="4.044" x="13.041" y="1.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4034" stdDeviation=".5"/></filter><radialGradient id="i2AcIxz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 15.365 23.496)" gradientUnits="userSpaceOnUse"><stop class="yzk2qz-6n"/><stop offset="1" class="x4iqcwbbb"/></radialGradient><radialGradient id="iM8aAic" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28212 -3.24419 3.42677 -3.46684 3.636 3.244)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="adkf43xer"/><stop offset=".907" class="f1z86gvqq"/></radialGradient><radialGradient id="i4iLqNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 17.604 23.496)" gradientUnits="userSpaceOnUse"><stop class="yzk2qz-6n"/><stop offset="1" class="x4iqcwbbb"/></radialGradient><radialGradient id="iLTicQc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 33.91 2.334)scale(8.65467 3.14404)" gradientUnits="userSpaceOnUse"><stop class="w6o4myf_b"/><stop offset="1" class="c8s6441kg"/></radialGradient><radialGradient id="ipIlaoc" cx="0" cy="0" r="1" gradientTransform="matrix(4.15623 3.31253 -1.73902 2.18195 21.579 17.063)" gradientUnits="userSpaceOnUse"><stop class="cpbnylbqu"/><stop offset="1" class="bgm6-ubvx"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:folded-hands" /></template>
<style>
.adkf43xer {
  stop-color: var(--svg-color--ffe051, #FFE051);
  stop-opacity: 0;
}

.b115ghbqh {
  stop-color: var(--svg-color--ffbd2c, #FFBD2C);
}

.b1lbi7bol {
  stop-color: var(--svg-color--945bcc, #945BCC);
}

.b5b0myb0o {
  stop-color: var(--svg-color--9469ff, #9469FF);
  stop-opacity: 0;
}

.b8excebxy {
  stop-color: var(--svg-color--ffb725, #FFB725);
}

.bctddzirn {
  stop-color: var(--svg-color--9867f8, #9867F8);
  stop-opacity: 0;
}

.bgm6-ubvx {
  stop-color: var(--svg-color--9d5bef, #9D5BEF);
  stop-opacity: 0;
}

.c8s6441kg {
  stop-color: var(--svg-color--8253ff, #8253FF);
  stop-opacity: 0;
}

.ci5amtxdu {
  d: path("m16.823 22.903l6.287-7.494a.6.6 0 0 1 .821-.093l.359.27a1 1 0 0 1 .397.799V29.74a.25.25 0 0 1-.41.192l-7.38-6.184a.6.6 0 0 1-.074-.846");
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

.ddr08xbmr {
  stop-color: var(--svg-color--df9100, #DF9100);
  stop-opacity: 0;
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

.ealucwtke {
  stop-color: var(--svg-color--ffd75a, #FFD75A);
  stop-opacity: 0;
}

.ehcwi7mvr {
  stop-color: var(--svg-color--cb7f00, #CB7F00);
  stop-opacity: 0;
}

.ewlg17b4k {
  stop-color: var(--svg-color--9469ff, #9469FF);
}

.f1z86gvqq {
  stop-color: var(--svg-color--ffe051, #FFE051);
}

.fhsjt5paq {
  stop-color: var(--svg-color--a578ff, #A578FF);
}

.ft5dv1b6b {
  fill: none;
}

.gl85jdbev {
  stop-color: var(--svg-color--df9100, #DF9100);
}

.gnpix7i2k {
  stop-color: var(--svg-color--f2882e, #F2882E);
}

.i5d79dbps {
  width: 4.39px;
  height: 8.125px;
  x: 12.094px;
  y: 2.223px;
  fill: var(--svg-color--ffb924, #FFB924);
  rx: 2.195px;
}

.ip-obw-bu {
  stop-color: var(--svg-color--cb7f00, #CB7F00);
}

.is5kyac3c {
  stop-color: var(--svg-color--ffe563, #FFE563);
  stop-opacity: 0;
}

.j8pwmbb_m {
  stop-color: var(--svg-color--9867f8, #9867F8);
}

.jxq7atbey {
  d: path("M16.146 22.903L9.859 15.41a.6.6 0 0 0-.821-.093l-.359.27a1 1 0 0 0-.398.799V29.74a.25.25 0 0 0 .411.192l7.38-6.184a.6.6 0 0 0 .074-.846");
}

.k03uj4bcp {
  stop-color: var(--svg-color--573eff, #573EFF);
}

.ki9m_gb7k {
  stop-color: var(--svg-color--6236ae, #6236AE);
  stop-opacity: 0;
}

.krjc9rbvv {
  width: 4.39px;
  height: 8.125px;
  fill: var(--svg-color--ffb520, #FFB520);
  rx: 2.195px;
}

.luc6otb8q {
  d: path("M20.399 6.831a1.066 1.066 0 0 0-2.132 0v6.641c0 .734.308 1.435.85 1.93l1.092 1.001a1.189 1.189 0 0 0 1.627-1.734l-.918-.882c-.332-.32-.52-.76-.52-1.221z");
}

.opu5b_bed {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
}

.p_14uvbpk {
  cx: 19.349px;
  cy: 3.814px;
  rx: 0.828px;
  ry: 1.134px;
}

.ptvfwgbhs {
  width: 4.39px;
  height: 8.125px;
  x: 12.094px;
  y: 2.223px;
  rx: 2.195px;
}

.q9gpy7bkq {
  stop-color: var(--svg-color--6640a2, #6640A2);
}

.rnyiy3b0d {
  stop-color: var(--svg-color--dd8200, #DD8200);
}

.sq3revbau {
  d: path("M18.69 4.737c1.218 0 2.206.987 2.206 2.205v5.4a2 2 0 0 0 .69 1.512l2.329 2.018l-6.47 7.624l-.654-.635a.96.96 0 0 1-.303-.7v-4.094l-.004-.128V6.942c0-1.218.988-2.205 2.206-2.205");
}

.sspv43s2v {
  stop-color: var(--svg-color--ffd75a, #FFD75A);
}

.t-oc4zkkq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m10.533 16.827l5.034 6.113");
}

.t2er4acdn {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
  stop-opacity: 0;
}

.tyfxpdb0w {
  stop-color: var(--svg-color--6236ae, #6236AE);
}

.vkslctbjc {
  d: path("M13.435 6.66a1.066 1.066 0 1 1 2.132 0v12.503a2.284 2.284 0 0 1-4.272 1.124l-.642-1.137a3 3 0 0 1 .46-3.567l1.757-1.81a2 2 0 0 0 .565-1.393z");
}

.w6o4myf_b {
  stop-color: var(--svg-color--8253ff, #8253FF);
}

.wb4fvkb5s {
  d: path("M14.279 4.737a2.206 2.206 0 0 0-2.206 2.205v5.4a2 2 0 0 1-.69 1.512l-2.33 2.018l6.47 7.624l.654-.635a1 1 0 0 0 .304-.717v-4.077q.003-.063.003-.128V6.942a2.206 2.206 0 0 0-2.205-2.205");
}

.wci41ibjf {
  stop-color: var(--svg-color--9a69fb, #9A69FB);
  stop-opacity: 0;
}

.wseblkogy {
  cx: 15.005px;
  cy: 3.814px;
  fill: var(--svg-color--ffd75c, #FFD75C);
  rx: 0.828px;
  ry: 1.134px;
}

.x4iqcwbbb {
  stop-color: var(--svg-color--c75e4a, #C75E4A);
  stop-opacity: 0;
}

.x8eka5b5x {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.266 17.143v7.92");
}

.xh1qmcchw {
  stop-color: var(--svg-color--dd8200, #DD8200);
  stop-opacity: 0;
}

.yril9lbdq {
  stop-color: var(--svg-color--ffe563, #FFE563);
}

.yzk2qz-6n {
  stop-color: var(--svg-color--c75e4a, #C75E4A);
}

</style>
