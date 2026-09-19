<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#isDLxNE)" class="ztlpv3ich"/><path fill="url(#iqC20Hd)" class="ztlpv3ich"/><path fill="url(#i23zhzb)" class="ztlpv3ich"/><path fill="url(#i1whAEb)" class="n4vv8zb3h"/><path fill="url(#iTDCCLd)" class="kpsc6b4oe"/><path fill="url(#i8Kc8Rb)" class="kpsc6b4oe"/><path fill="url(#ibrsIXb)" class="kpsc6b4oe"/><path fill="url(#i2x6Ltt)" class="smg9lzkvj"/><path fill="url(#ilNcD2b)" class="uwa-whbjj"/><path fill="url(#iC74k7b)" class="uwa-whbjj"/><path fill="url(#iqQCvyd)" class="uwa-whbjj"/><path fill="url(#i7TqJqz)" class="uwa-whbjj"/><path fill="url(#iKbiuDN)" class="vykazybhm"/><path fill="url(#iApMR6b)" class="vykazybhm"/><path fill="url(#iFkHtJb)" class="vykazybhm"/><path fill="url(#iAiETIo)" class="mv2y2hk9y"/><path fill="url(#iKiTCNe)" class="mv2y2hk9y"/><path fill="url(#i7CA4Wd)" class="mv2y2hk9y"/><path fill="url(#ijnNmic)" class="mv2y2hk9y"/><path fill="url(#iXU7csd)" class="mv2y2hk9y"/><path fill="url(#i59iKke)" class="mv2y2hk9y"/><path fill="url(#iGED0NF)" class="mv2y2hk9y"/><path fill="url(#i13MXGe)" class="mv2y2hk9y"/><path fill="url(#iqNlTne)" class="mv2y2hk9y"/><path fill="url(#isaNM3d)" class="mv2y2hk9y"/><g filter="url(#ilIi0Ym)"><path fill="url(#iOF6Awb)" class="vit7aypzd"/></g><path class="g14ivkydv"/><path fill="url(#i56QQuo)" class="zavs58b1t"/><path fill="url(#iijKvMe)" class="zavs58b1t"/><path fill="url(#is9Didv)" class="zavs58b1t"/><path fill="url(#iPdwXKu)" class="zavs58b1t"/><path fill="url(#ibX879b)" class="zq62q0bmo"/><path fill="url(#idKl5Dd)" class="zq62q0bmo"/><path fill="url(#iYZ0SWb)" class="zq62q0bmo"/><g filter="url(#i7NiDMe)"><path fill="url(#ijPje6d)" class="caa9icb3r"/></g><path fill="url(#iQdrYJd)" class="cmf8_ubbv"/><path fill="url(#iZYibyd)" class="cmf8_ubbv"/><path fill="url(#ijtHvcc)" class="cmf8_ubbv"/><g filter="url(#i1XVnVc)"><rect class="zvrn1gbox"/></g><rect fill="url(#ioTfgDs)" class="nljey87-d"/><rect fill="url(#i2Q8lNO)" class="nljey87-d"/><rect fill="url(#iYS9sJI)" class="nljey87-d"/><g filter="url(#i6gZF0T)"><path class="ne6qyob4f"/></g><g filter="url(#iuNvX6d)"><path stroke="url(#i5Vyf7R)" class="xq7m34buk"/></g><g filter="url(#iyb4ITI)"><circle fill="url(#i612JjT)" class="p02jo4b1h"/></g><g filter="url(#i4incld)"><path class="jbwl9xaaz"/></g><g filter="url(#iTIo8Dd)"><path class="kmzcmqzex"/></g></g><defs><linearGradient id="iqC20Hd" x1="21.643" x2="21.643" y1="30.82" y2="28.675" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="i23zhzb" x1="21.796" x2="21.724" y1="30.367" y2="28.671" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="iTDCCLd" x1="14.258" x2="16.637" y1="30.5" y2="24.213" gradientUnits="userSpaceOnUse"><stop class="buw4dgb_j"/><stop offset="1" class="l7hbqablt"/></linearGradient><linearGradient id="i8Kc8Rb" x1="13.52" x2="13.52" y1="23.688" y2="26.23" gradientUnits="userSpaceOnUse"><stop class="k8y3kowsr"/><stop offset="1" class="hsskl9bju"/></linearGradient><linearGradient id="ibrsIXb" x1="14.195" x2="14.103" y1="30.313" y2="28.832" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="i2x6Ltt" x1="14.205" x2="13.517" y1="25.344" y2="23.293" gradientUnits="userSpaceOnUse"><stop class="fmz_f8qqq"/><stop offset="1" class="qlqq2obzs"/></linearGradient><linearGradient id="ilNcD2b" x1="12" x2="15.231" y1="18.313" y2="24.558" gradientUnits="userSpaceOnUse"><stop class="w7fjl9brj"/><stop offset="1" class="k6jvryyia"/></linearGradient><linearGradient id="iC74k7b" x1="14.359" x2="14.116" y1="24.531" y2="25.716" gradientUnits="userSpaceOnUse"><stop class="bj_1p1bja"/><stop offset="1" class="n_zyj1dkm"/></linearGradient><linearGradient id="iqQCvyd" x1="10.813" x2="11.688" y1="28.125" y2="28.125" gradientUnits="userSpaceOnUse"><stop class="teo6molgj"/><stop offset="1" class="hgxobmb-y"/></linearGradient><linearGradient id="i7TqJqz" x1="13.143" x2="13.143" y1="30.75" y2="28.832" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="iApMR6b" x1="25.063" x2="26.875" y1="23.938" y2="26.719" gradientUnits="userSpaceOnUse"><stop class="bj_1p1bja"/><stop offset="1" class="n_zyj1dkm"/></linearGradient><linearGradient id="iFkHtJb" x1="28.422" x2="28.393" y1="30.245" y2="29.126" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="iAiETIo" x1="16" x2="16" y1="12.875" y2="21.375" gradientUnits="userSpaceOnUse"><stop class="aax035blr"/><stop offset="1" class="dq6us_b-i"/></linearGradient><linearGradient id="iKiTCNe" x1="9.875" x2="9.875" y1=".813" y2="3.688" gradientUnits="userSpaceOnUse"><stop class="yxv_occkk"/><stop offset="1" class="sdcjwitxu"/></linearGradient><linearGradient id="iOF6Awb" x1="13.76" x2="7.693" y1="4.495" y2="7.592" gradientUnits="userSpaceOnUse"><stop class="mmi_gfead"/><stop offset="1" class="zzpvmbbrw"/></linearGradient><linearGradient id="i56QQuo" x1="3.125" x2="3.578" y1="8.172" y2="8.641" gradientUnits="userSpaceOnUse"><stop class="lk251vbhz"/><stop offset="1" class="pof0hibxa"/></linearGradient><linearGradient id="is9Didv" x1="5.125" x2="5.125" y1="11.906" y2="10.125" gradientUnits="userSpaceOnUse"><stop class="jdtrf8bed"/><stop offset="1" class="zsxp-lmcv"/></linearGradient><linearGradient id="iPdwXKu" x1="9.688" x2="7.594" y1="10" y2="10" gradientUnits="userSpaceOnUse"><stop offset=".802" class="w-1u5lrel"/><stop offset="1" class="sihm6eumj"/></linearGradient><linearGradient id="ibX879b" x1="3.37" x2="2.369" y1="10.08" y2="10.08" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="idKl5Dd" x1="3.888" x2="3.888" y1="10.741" y2="10.349" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iYZ0SWb" x1="1.658" x2="2.395" y1="10.146" y2="10.146" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="ijPje6d" x1="23.11" x2="29.776" y1="18.06" y2="19.546" gradientUnits="userSpaceOnUse"><stop class="zzpvmbbrw"/><stop offset="1" class="mmi_gfead"/></linearGradient><linearGradient id="ioTfgDs" x1="5.84" x2="5.232" y1="8.75" y2="8.75" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="i2Q8lNO" x1="6.155" x2="6.155" y1="9.984" y2="9.253" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iYS9sJI" x1="4.8" x2="5.248" y1="8.873" y2="8.873" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="i5Vyf7R" x1="12.875" x2="13.016" y1="29.031" y2="23" gradientUnits="userSpaceOnUse"><stop class="ybgq005nr"/><stop offset="1" class="nme0t5b3v"/></linearGradient><radialGradient id="isDLxNE" cx="0" cy="0" r="1" gradientTransform="matrix(4.0825 -4.90624 2.8865 2.40188 19.187 29.125)" gradientUnits="userSpaceOnUse"><stop class="buw4dgb_j"/><stop offset="1" class="l7hbqablt"/></radialGradient><radialGradient id="i1whAEb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09376 -2.4375 3.68374 1.65298 20.469 24.344)" gradientUnits="userSpaceOnUse"><stop class="fmz_f8qqq"/><stop offset="1" class="qlqq2obzs"/></radialGradient><radialGradient id="iKbiuDN" cx="0" cy="0" r="1" gradientTransform="rotate(40.958 -20.352 44.881)scale(5.17254 3.5038)" gradientUnits="userSpaceOnUse"><stop class="w7fjl9brj"/><stop offset="1" class="k6jvryyia"/></radialGradient><radialGradient id="i7CA4Wd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.0625 -9.92516 0 20.438 7.563)" gradientUnits="userSpaceOnUse"><stop class="yxv_occkk"/><stop offset="1" class="sdcjwitxu"/></radialGradient><radialGradient id="ijnNmic" cx="0" cy="0" r="1" gradientTransform="matrix(3.01562 0 0 2.28125 2.375 4.531)" gradientUnits="userSpaceOnUse"><stop class="vz6nkbhqj"/><stop offset="1" class="cdmpj45uv"/></radialGradient><radialGradient id="iXU7csd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25004 -7.24998 5.39566 -3.90724 18.5 25.438)" gradientUnits="userSpaceOnUse"><stop class="n-j0v00sa"/><stop offset="1" class="tldtf8bjt"/></radialGradient><radialGradient id="i59iKke" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -4.8125 3.32421 3.10835 6.313 25.563)" gradientUnits="userSpaceOnUse"><stop class="n-j0v00sa"/><stop offset="1" class="tldtf8bjt"/></radialGradient><radialGradient id="iGED0NF" cx="0" cy="0" r="1" gradientTransform="rotate(-115.71 22.25 5.372)scale(5.61875 4.82677)" gradientUnits="userSpaceOnUse"><stop class="n-j0v00sa"/><stop offset="1" class="tldtf8bjt"/></radialGradient><radialGradient id="i13MXGe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.06246 -4.78127 2.02716 -1.29842 30.281 19.781)" gradientUnits="userSpaceOnUse"><stop class="n-j0v00sa"/><stop offset=".746" class="tldtf8bjt"/></radialGradient><radialGradient id="iqNlTne" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 -5.47125 2.78136 1.19147 4.625 18.781)" gradientUnits="userSpaceOnUse"><stop class="kwn92lbxp"/><stop offset="1" class="bd0za3fix"/></radialGradient><radialGradient id="isaNM3d" cx="0" cy="0" r="1" gradientTransform="matrix(1.15623 -2.71376 1.36057 .57969 8.813 24.62)" gradientUnits="userSpaceOnUse"><stop class="kwn92lbxp"/><stop offset="1" class="bd0za3fix"/></radialGradient><radialGradient id="iijKvMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 0 0 1.61303 1.688 9.922)" gradientUnits="userSpaceOnUse"><stop class="lk251vbhz"/><stop offset="1" class="pof0hibxa"/></radialGradient><radialGradient id="iQdrYJd" cx="0" cy="0" r="1" gradientTransform="rotate(134.357 4.142 6.284)scale(2.09605 3.58161)" gradientUnits="userSpaceOnUse"><stop class="e5g5vt6cb"/><stop offset="1" class="dggpw784l"/></radialGradient><radialGradient id="iZYibyd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17793 1.32217 -1.82434 -1.62531 11.287 7.96)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="husoikz_p"/><stop offset="1" class="s_bg48blw"/></radialGradient><radialGradient id="ijtHvcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46276 -.11528 .08979 -.36042 12.444 9.368)" gradientUnits="userSpaceOnUse"><stop class="o9c1bzgsh"/><stop offset="1" class="dqyfzxb5t"/></radialGradient><radialGradient id="i612JjT" cx="0" cy="0" r="1" gradientTransform="rotate(128.264 11.43 11.93)scale(5.65167 3.77421)" gradientUnits="userSpaceOnUse"><stop class="mmi_gfead"/><stop offset="1" class="zzpvmbbrw"/></radialGradient><filter id="ilIi0Ym" width="9.221" height="13.239" x="7.198" y="1.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3187" stdDeviation=".6"/></filter><filter id="i7NiDMe" width="7.188" height="13.922" x="22.891" y="11.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3187" stdDeviation=".5"/></filter><filter id="i1XVnVc" width="1.905" height="2.839" x="4.347" y="7.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3187" stdDeviation=".25"/></filter><filter id="i6gZF0T" width="1.5" height="5.247" x="28.703" y="24.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3187" stdDeviation=".3"/></filter><filter id="iuNvX6d" width="1.5" height="5.247" x="11.638" y="24.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3187" stdDeviation=".3"/></filter><filter id="iyb4ITI" width="7.968" height="7.968" x="21.894" y="9.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3187" stdDeviation=".6"/></filter><filter id="i4incld" width="4.279" height="7.442" x="26.168" y="10.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3187" stdDeviation=".5"/></filter><filter id="iTIo8Dd" width="2.141" height="4.375" x="5.797" y="6.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3187" stdDeviation=".25"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ewe" /></template>
<style>
.a9c-4wbgb {
  stop-color: var(--svg-color--b56551, #B56551);
  stop-opacity: 0;
}

.aax035blr {
  stop-color: var(--svg-color--d6d1d5, #D6D1D5);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bd0za3fix {
  stop-color: var(--svg-color--e7e3ea, #E7E3EA);
  stop-opacity: 0;
}

.bj_1p1bja {
  stop-color: var(--svg-color--aa5c48, #AA5C48);
}

.buw4dgb_j {
  stop-color: var(--svg-color--b97654, #B97654);
}

.c_lfom8in {
  stop-color: var(--svg-color--574d50, #574D50);
  stop-opacity: 0;
}

.caa9icb3r {
  d: path("M27.078 21.67v-9.61h-3.187v7.804a3 3 0 0 0 1.877 2.782l3.31 1.336z");
}

.cdmpj45uv {
  stop-color: var(--svg-color--e7e2e9, #E7E2E9);
  stop-opacity: 0;
}

.cmf8_ubbv {
  d: path("M10.19 6.53a.313.313 0 0 0-.48.04c-.52.78-.44 1.84.24 2.53l.01.01c.69.69 1.78.8 2.56.28c.17-.11.19-.34.05-.48z");
}

.co-foyhmg {
  stop-color: var(--svg-color--31232c, #31232C);
}

.dggpw784l {
  stop-color: var(--svg-color--bf7c4d, #BF7C4D);
}

.dq6us_b-i {
  stop-color: var(--svg-color--cbb9dc, #CBB9DC);
}

.dqyfzxb5t {
  stop-color: var(--svg-color--e7a66d, #E7A66D);
  stop-opacity: 0;
}

.e5g5vt6cb {
  stop-color: var(--svg-color--e2a168, #E2A168);
}

.fmz_f8qqq {
  stop-color: var(--svg-color--b197c1, #B197C1);
}

.ft5dv1b6b {
  fill: none;
}

.g14ivkydv {
  fill: var(--svg-color--cd8b49, #CD8B49);
  d: path("M7.92 7.76c0-.68.26-1.3.68-1.76H5.8c-.17 0-.33.07-.44.18L2.33 9.21c-.21.21-.33.5-.33.8c0 .93.75 1.68 1.68 1.68h2.75c.82 0 1.49-.67 1.49-1.49z");
}

.hgxobmb-y {
  stop-color: var(--svg-color--eaa566, #EAA566);
  stop-opacity: 0;
}

.hkmrfsbjj {
  stop-color: var(--svg-color--b56551, #B56551);
}

.hsskl9bju {
  stop-color: var(--svg-color--684234, #684234);
  stop-opacity: 0;
}

.husoikz_p {
  stop-color: var(--svg-color--c07950, #C07950);
  stop-opacity: 0;
}

.jbwl9xaaz {
  stroke: var(--svg-color--ede9f0, #EDE9F0);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M27.266 11.797c1.718 1.469 2.03 3.25 2.03 5.328");
}

.jdtrf8bed {
  stop-color: var(--svg-color--be7550, #BE7550);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.k6jvryyia {
  stop-color: var(--svg-color--d58755, #D58755);
}

.k8y3kowsr {
  stop-color: var(--svg-color--684234, #684234);
}

.kfeabacio {
  stop-color: var(--svg-color--574d50, #574D50);
}

.kmzcmqzex {
  fill: var(--svg-color--d49360, #D49360);
  d: path("m6.297 7.64l1.14-.546v2.828l-1.14.547z");
}

.kpsc6b4oe {
  d: path("M11.96 29.66c0 .19.15.34.34.34h1.36c.19 0 .34-.15.34-.34v-2.61c0-.18.07-.35.2-.48c.56-.56.88-1.33.88-2.12v-1.99h-3.12z");
}

.kwn92lbxp {
  stop-color: var(--svg-color--e7e3ea, #E7E3EA);
}

.l7hbqablt {
  stop-color: var(--svg-color--70423a, #70423A);
}

.lk251vbhz {
  stop-color: var(--svg-color--deac81, #DEAC81);
}

.mmi_gfead {
  stop-color: var(--svg-color--ede9f0, #EDE9F0);
}

.mv2y2hk9y {
  d: path("M14.97 10h9.51c3.05 0 5.52 3.01 5.52 6.06v.91c0 .58-.45 1.03-.93 1.03c-.41 0-.745-.17-.925-.462A1 1 0 0 1 28 17v3.98c0 .26.11.52.3.71l1.21 1.37c.31.32.49.74.49 1.19a.37.37 0 0 1-.37.37h-6.18c-.56 0-1.02-.46-1.02-1.02v-.13a1 1 0 0 0-1-1h-5.41a1 1 0 0 0-1 1v.13c0 .56-.46 1.02-1.02 1.02h-2.98c-.56 0-1.02-.46-1.02-1.02v-.13a1 1 0 0 0-1-1c-1.66 0-3-1.35-3-3v-4.1a.37.37 0 0 0-.37-.37C4.73 15 4 14.27 4 13.37v-1.36a.32.32 0 0 0-.32-.32c-.93 0-1.68-.75-1.68-1.68c0-.3.12-.59.33-.8L5.54 6H5.5C4.67 6 4 5.33 4 4.5S4.67 3 5.5 3h1.12c.17 0 .32-.08.43-.21C7.46 2.31 8.08 2 8.76 2C11.65 2 14 4.35 14 7.24v1.79c0 .54.43.97.97.97");
}

.n_zyj1dkm {
  stop-color: var(--svg-color--b5644f, #B5644F);
  stop-opacity: 0;
}

.n-j0v00sa {
  stop-color: var(--svg-color--a381c0, #A381C0);
}

.n4vv8zb3h {
  d: path("M23.6 24.62h-3.35c-.56 0-1.02-.46-1.02-1.02v-2.54h5.38v2.54c.01.56-.45 1.02-1.01 1.02");
}

.ne6qyob4f {
  stroke: var(--svg-color--f4af6f, #F4AF6F);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M29.453 29.266v-4.047");
}

.nljey87-d {
  width: 0.992px;
  height: 2.016px;
  x: 5.008px;
  y: 7.742px;
  rx: 0.496px;
}

.nme0t5b3v {
  stop-color: var(--svg-color--f4af6f, #F4AF6F);
  stop-opacity: 0;
}

.o9c1bzgsh {
  stop-color: var(--svg-color--e7a66d, #E7A66D);
}

.p02jo4b1h {
  cx: 25.878px;
  cy: 13.748px;
  r: 2.784px;
}

.pof0hibxa {
  stop-color: var(--svg-color--deac81, #DEAC81);
  stop-opacity: 0;
}

.qlqq2obzs {
  stop-color: var(--svg-color--857097, #857097);
}

.s_bg48blw {
  stop-color: var(--svg-color--c07950, #C07950);
}

.sdcjwitxu {
  stop-color: var(--svg-color--c2bdbe, #C2BDBE);
  stop-opacity: 0;
}

.sihm6eumj {
  stop-color: var(--svg-color--c08150, #C08150);
  stop-opacity: 0;
}

.smg9lzkvj {
  d: path("M11.08 23.6c0 .56.46 1.02 1.02 1.02h2.98c.56 0 1.02-.46 1.02-1.02v-1.13h-5.02z");
}

.teo6molgj {
  stop-color: var(--svg-color--eaa566, #EAA566);
}

.tldtf8bjt {
  stop-color: var(--svg-color--ad93c4, #AD93C4);
  stop-opacity: 0;
}

.uwa-whbjj {
  d: path("M11 29.66c0 .19.15.34.34.34h1.36c.19 0 .34-.15.34-.34v-2.61c0-.18.07-.35.2-.48c.56-.56.88-1.33.88-2.12v-1.99H11z");
}

.vit7aypzd {
  d: path("M13.54 7.47c0-4.664-3.784-4.946-5.142-5.105c1.057.382 2.35 1.028 2.35 3.783v4.94c0 1.414 1.199 2.247 2.377 2.1c1.75-.22 1.984-1.67 2.094-2.282c-1.125 0-1.704-.473-1.68-1.232z");
}

.vykazybhm {
  d: path("m24.438 24.328l3.252 2.252c.18.13.28.33.28.55v2.54c0 .19.15.34.34.34h1.35c.19 0 .34-.15.34-.34v-4.842a.5.5 0 0 0-.5-.5z");
}

.vz6nkbhqj {
  stop-color: var(--svg-color--e7e2e9, #E7E2E9);
}

.w-1u5lrel {
  stop-color: var(--svg-color--c08150, #C08150);
}

.w7fjl9brj {
  stop-color: var(--svg-color--b5644f, #B5644F);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xq7m34buk {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M12.388 29.266v-4.047");
}

.ybgq005nr {
  stop-color: var(--svg-color--f4af6f, #F4AF6F);
}

.yxv_occkk {
  stop-color: var(--svg-color--c2bdbe, #C2BDBE);
}

.zavs58b1t {
  d: path("M7.92 7.76c0-.68.26-1.3.68-1.76H5.8c-.17 0-.33.07-.44.18L2.33 9.21c-.21.21-.33.5-.33.8c0 .93.75 1.68 1.68 1.68h2.75c.82 0 1.49-.67 1.49-1.49z");
}

.zq62q0bmo {
  d: path("M3.08 10.62h.06c.69-.04.64-1.08-.05-1.08H2.1c-.06.15-.1.31-.1.47c0 .21.04.42.11.61z");
}

.zsxp-lmcv {
  stop-color: var(--svg-color--be7550, #BE7550);
  stop-opacity: 0;
}

.ztlpv3ich {
  d: path("M20.02 21.39v5.15c0 .16-.04.31-.11.45l-1.8 2.53c-.11.22.05.49.3.49h1.12c.32 0 .55-.16.81-.4l2.59-2.37c.29-.25.34-.65.34-1.01v-4.82z");
}

.zvrn1gbox {
  width: 0.905px;
  height: 1.839px;
  x: 4.847px;
  y: 8.076px;
  fill: var(--svg-color--97633d, #97633D);
  rx: 0.453px;
}

.zzpvmbbrw {
  stop-color: var(--svg-color--ede9f0, #EDE9F0);
  stop-opacity: 0;
}

</style>
