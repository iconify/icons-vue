<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="o0xvzdi3v"/><g filter="url(#iZfI4ng)"><ellipse fill="url(#i66Un9c)" transform="rotate(26.087 17.338 9.08)" class="r4xp77bwq"/></g><g filter="url(#iSEWX7d)"><path fill="url(#i8pOP2d)" class="crbyzbt1f"/><path fill="url(#iuNx2KH)" class="crbyzbt1f"/></g><g filter="url(#iXxuhjb)"><circle fill="url(#icrJvyh)" class="yx_4vcb_f"/></g><circle fill="url(#ipcGiJe)" class="m7rma2bnk"/><circle fill="url(#iBJzZ7u)" class="m7rma2bnk"/><g filter="url(#iv2MQhb)"><circle class="q2cbiab2g"/></g><g filter="url(#ipRcBrc)"><path fill="url(#ijvvKxb)" class="rmjstgber"/><path fill="url(#iHgXtmc)" class="rmjstgber"/></g><path fill="url(#itRXcmc)" class="o5ihkcskr"/><path fill="url(#ilRcCGq)" class="o5ihkcskr"/><path fill="url(#i5ORo6c)" class="o5ihkcskr"/><path fill="url(#itshlNb)" class="o5ihkcskr"/><path fill="url(#ibedLub)" class="o5ihkcskr"/><g filter="url(#iZLOx3Y)"><path stroke="url(#iXKxj4c)" class="qk8scsbaf"/></g><g filter="url(#iNMmHze)"><path stroke="url(#iPHjxKd)" class="ivry3481r"/></g><defs><radialGradient id="i66Un9c" cx="0" cy="0" r="1" gradientTransform="rotate(-91.906 15.31 -1.52)scale(8.88629 15.4978)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="hcgem_45j"/><stop offset=".922" class="ax09vvzzy"/></radialGradient><radialGradient id="iBJzZ7u" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10816 1.52067 -1.73662 -2.40753 14.464 20.918)" gradientUnits="userSpaceOnUse"><stop class="xvxnt3n-k"/><stop offset="1" class="ns22v9t-w"/></radialGradient><radialGradient id="iHgXtmc" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 -5.5625 6.22805 4.33864 17.5 10.83)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="emwabp4fw"/><stop offset="1" class="grzcxhmih"/></radialGradient><radialGradient id="itRXcmc" cx="0" cy="0" r="1" gradientTransform="matrix(.14338 -4.62474 6.13434 .19019 23.232 15.266)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="uw0wzsn6p"/><stop offset="1" class="fmyqnxbcv"/></radialGradient><radialGradient id="ilRcCGq" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.796 17.183)scale(4.97005 4.84669)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="vhxzwb5vo"/><stop offset="1" class="w9v04g5wl"/></radialGradient><radialGradient id="i5ORo6c" cx="0" cy="0" r="1" gradientTransform="rotate(-115.896 19.594 6.144)scale(26.3315 19.1931)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="mfxftxb2v"/><stop offset="1" class="x23elq47e"/></radialGradient><radialGradient id="itshlNb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.14 21.87883 -17.0804 -2.45134 14.584 7.982)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="ho66e2gez"/><stop offset="1" class="oagukf04h"/></radialGradient><radialGradient id="ibedLub" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 3.71875 10.344 22.142)" gradientUnits="userSpaceOnUse"><stop class="fkd_ifb4y"/><stop offset="1" class="n1nhqibha"/><stop offset="1" class="zqvmn0t-z"/></radialGradient><linearGradient id="i8pOP2d" x1="12.875" x2="10.121" y1="12.579" y2="18.173" gradientUnits="userSpaceOnUse"><stop class="a5-5f3bjl"/><stop offset="1" class="c8hqtvbke"/></linearGradient><linearGradient id="iuNx2KH" x1="13.563" x2="15.563" y1="27.517" y2="21.923" gradientUnits="userSpaceOnUse"><stop offset=".218" class="cp6t-lt6u"/><stop offset="1" class="zc_tl-b2g"/></linearGradient><linearGradient id="icrJvyh" x1="14.509" x2="12.212" y1="20.489" y2="24.533" gradientUnits="userSpaceOnUse"><stop offset=".34" class="vkm05yehh"/><stop offset="1" class="dl5923bfb"/></linearGradient><linearGradient id="ipcGiJe" x1="11.755" x2="11.755" y1="19.142" y2="25.142" gradientUnits="userSpaceOnUse"><stop class="u5e9-9bjf"/><stop offset="1" class="e95bxobvz"/></linearGradient><linearGradient id="ijvvKxb" x1="11.563" x2="20" y1="31.517" y2="-.858" gradientUnits="userSpaceOnUse"><stop class="npfpicb6j"/><stop offset="1" class="m8ss-00uh"/></linearGradient><linearGradient id="iXKxj4c" x1="24.971" x2="17.565" y1="11.235" y2="3.423" gradientUnits="userSpaceOnUse"><stop class="j_li4o9eq"/><stop offset=".51" class="iqk_b94ku"/><stop offset="1" class="j_li4o9eq"/></linearGradient><linearGradient id="iPHjxKd" x1="8.441" x2="21.379" y1="2.017" y2="24.121" gradientUnits="userSpaceOnUse"><stop class="x6wmc3bjj"/><stop offset=".698" class="ve370msop"/></linearGradient><filter id="iZfI4ng" width="15.705" height="12.527" x="9.486" y="2.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4671" stdDeviation=".5"/></filter><filter id="iSEWX7d" width="12.531" height="17.719" x="7.531" y="11.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4671" stdDeviation=".25"/></filter><filter id="iXxuhjb" width="7.872" height="7.872" x="8.005" y="18.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4671" stdDeviation=".375"/></filter><filter id="iv2MQhb" width="6.128" height="6.128" x="8.691" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4671" stdDeviation=".25"/></filter><filter id="ipRcBrc" width="19.085" height="27.796" x="6.708" y="2.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.623529 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4671"/></filter><filter id="iZLOx3Y" width="12.094" height="12.656" x="14.44" y="1.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4671" stdDeviation=".75"/></filter><filter id="iNMmHze" width="13.063" height="23.361" x="6.941" y="6.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4671" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-light" /></template>
<style>
.a5-5f3bjl {
  stop-color: var(--svg-color--da8467, #DA8467);
}

.ax09vvzzy {
  stop-color: var(--svg-color--ca827d, #CA827D);
}

.c8hqtvbke {
  stop-color: var(--svg-color--da8467, #DA8467);
  stop-opacity: 0;
}

.cp6t-lt6u {
  stop-color: var(--svg-color--e19a7f, #E19A7F);
}

.crbyzbt1f {
  d: path("M12.577 28.735c-3.288-.25-4.546-2.063-4.546-5.304V12.173l2.344-.156l9.188 9.156l-2.938 4.969c-.989 1.845-1.68 2.593-4.049 2.593");
}

.dl5923bfb {
  stop-color: var(--svg-color--ca7a56, #CA7A56);
}

.e95bxobvz {
  stop-color: var(--svg-color--eeaa9a, #EEAA9A);
}

.emwabp4fw {
  stop-color: var(--svg-color--c17c71, #C17C71);
}

.fkd_ifb4y {
  stop-color: var(--svg-color--fdc5b4, #FDC5B4);
}

.fmyqnxbcv {
  stop-color: var(--svg-color--ffc8b5, #FFC8B5);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.grzcxhmih {
  stop-color: var(--svg-color--c17c71, #C17C71);
  stop-opacity: 0;
}

.hcgem_45j {
  stop-color: var(--svg-color--ca827d, #CA827D);
  stop-opacity: 0;
}

.ho66e2gez {
  stop-color: var(--svg-color--c28296, #C28296);
  stop-opacity: 0;
}

.iqk_b94ku {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
}

.ivry3481r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.19 9.187v14.705c.022.895.334 3.408 3.063 4.03c2.297.525 3.625-.687 4.276-1.905l1.224-2.125");
}

.j_li4o9eq {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
  stop-opacity: 0;
}

.m7rma2bnk {
  cx: 11.755px;
  cy: 22.142px;
  r: 3px;
}

.m8ss-00uh {
  stop-color: var(--svg-color--fcccaf, #FCCCAF);
}

.mfxftxb2v {
  stop-color: var(--svg-color--d8b49f, #D8B49F);
  stop-opacity: 0;
}

.n1nhqibha {
  stop-color: var(--svg-color--b5877c, #B5877C);
  stop-opacity: 0;
}

.npfpicb6j {
  stop-color: var(--svg-color--f1baac, #F1BAAC);
}

.ns22v9t-w {
  stop-color: var(--svg-color--ffddc6, #FFDDC6);
  stop-opacity: 0;
}

.o0xvzdi3v {
  fill: var(--svg-color--ffc8b5, #FFC8B5);
  d: path("M6.708 23.43c0 3.242 2.581 6.18 5.868 6.431c2.37 0 4.459-1.374 5.447-3.22l5.756-10.19a9.292 9.292 0 1 0-17.072-5.084z");
}

.o5ihkcskr {
  d: path("M18.167 22.696a1.8 1.8 0 0 0-2.439.69l-.859 1.52l-.018.035c-.366.682-1.156 1.316-2.135 1.316c-1.255 0-2.408-1.428-2.408-2.826V11.367a5.692 5.692 0 1 1 11.315.891c-.147.94.126 1.974.943 2.46c.9.537 2.084.21 2.37-.797a9.292 9.292 0 1 0-18.23-2.554v12.064c.002 3.24 2.583 6.18 5.87 6.43c2.37 0 4.459-1.374 5.447-3.22l.84-1.485a1.8 1.8 0 0 0-.696-2.46");
}

.oagukf04h {
  stop-color: var(--svg-color--c28296, #C28296);
}

.q2cbiab2g {
  cx: 11.755px;
  cy: 22.142px;
  r: 2.564px;
  fill: var(--svg-color--fcc4b3, #FCC4B3);
}

.qk8scsbaf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.94 3.579c2.291.375 6.919 2.431 7.094 7.656");
}

.r4xp77bwq {
  cx: 17.338px;
  cy: 9.081px;
  rx: 7.28px;
  ry: 4.652px;
}

.rmjstgber {
  d: path("M18.167 22.696a1.8 1.8 0 0 0-2.439.69l-.859 1.52l-.018.035c-.366.682-1.156 1.316-2.135 1.316c-1.255 0-2.408-1.428-2.408-2.826V11.367a5.692 5.692 0 1 1 11.315.891c-.147.94.126 1.974.943 2.46c.9.537 2.084.21 2.37-.797a9.292 9.292 0 1 0-18.23-2.554v12.064c.002 3.24 2.583 6.18 5.87 6.43c2.322.148 4.459-1.374 5.447-3.22l.84-1.485a1.8 1.8 0 0 0-.696-2.46");
}

.u5e9-9bjf {
  stop-color: var(--svg-color--ffc7ab, #FFC7AB);
}

.uw0wzsn6p {
  stop-color: var(--svg-color--ffc8b5, #FFC8B5);
}

.ve370msop {
  stop-color: var(--svg-color--ffdcc7, #FFDCC7);
}

.vhxzwb5vo {
  stop-color: var(--svg-color--ffc9b6, #FFC9B6);
}

.vkm05yehh {
  stop-color: var(--svg-color--ffdabd, #FFDABD);
}

.w9v04g5wl {
  stop-color: var(--svg-color--ffc9b6, #FFC9B6);
  stop-opacity: 0;
}

.x23elq47e {
  stop-color: var(--svg-color--d8b49f, #D8B49F);
}

.x6wmc3bjj {
  stop-color: var(--svg-color--ffdcc7, #FFDCC7);
  stop-opacity: 0;
}

.xvxnt3n-k {
  stop-color: var(--svg-color--ffddc6, #FFDDC6);
}

.yx_4vcb_f {
  cx: 11.941px;
  cy: 22.328px;
  r: 3.186px;
}

.zc_tl-b2g {
  stop-color: var(--svg-color--e19a7f, #E19A7F);
  stop-opacity: 0;
}

.zqvmn0t-z {
  stop-color: var(--svg-color--fdc5b4, #FDC5B4);
  stop-opacity: 0;
}

</style>
