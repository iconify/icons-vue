<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lapnfe-2y"/><g filter="url(#iTpIz2c)"><ellipse fill="url(#icKOIld)" transform="rotate(26.087 17.338 9.08)" class="r4xp77bwq"/></g><g filter="url(#il3O7jQ)"><path fill="url(#i7VhZpe)" class="crbyzbt1f"/><path fill="url(#iYGArtc)" class="crbyzbt1f"/></g><g filter="url(#iWAUZLe)"><circle fill="url(#iNuKMil)" class="yx_4vcb_f"/></g><circle fill="url(#isCJkRO)" class="m7rma2bnk"/><circle fill="url(#i7D429b)" class="m7rma2bnk"/><g filter="url(#icwfK5b)"><circle class="ztt7phbpm"/></g><g filter="url(#igROS4c)"><path fill="url(#isM6nye)" class="o5ihkcskr"/><path fill="url(#iwG905c)" class="o5ihkcskr"/></g><path fill="url(#i2MFXoe)" class="o5ihkcskr"/><path fill="url(#i40Sg4c)" class="o5ihkcskr"/><path fill="url(#isR9CLB)" class="o5ihkcskr"/><path fill="url(#ii8TjKb)" class="o5ihkcskr"/><path fill="url(#iEbOCAd)" class="o5ihkcskr"/><g filter="url(#iiEoL3b)"><path stroke="url(#i0AsELb)" class="qk8scsbaf"/></g><g filter="url(#iQkBnXd)"><path stroke="url(#i2HZCBO)" class="ivry3481r"/></g><defs><radialGradient id="icKOIld" cx="0" cy="0" r="1" gradientTransform="rotate(-90.156 15.517 -1.78)scale(8.19144 14.286)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="a65-qfb3x"/><stop offset=".848" class="nz9u2tjef"/></radialGradient><radialGradient id="i7D429b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10816 1.52067 -1.73662 -2.40753 14.464 20.918)" gradientUnits="userSpaceOnUse"><stop class="ulasi0k-c"/><stop offset="1" class="jkkqseb-y"/></radialGradient><radialGradient id="iwG905c" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 -5.5625 6.22805 4.33864 17.5 10.829)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="i6650-xam"/><stop offset="1" class="b382ogbnr"/></radialGradient><radialGradient id="i2MFXoe" cx="0" cy="0" r="1" gradientTransform="matrix(.14338 -4.62474 6.13434 .19019 23.232 15.266)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="m3x6io8eb"/><stop offset="1" class="u8xbn9b3q"/></radialGradient><radialGradient id="i40Sg4c" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.796 17.183)scale(4.97005 4.84669)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xvrv_6bis"/><stop offset="1" class="n_g-u-lhi"/></radialGradient><radialGradient id="isR9CLB" cx="0" cy="0" r="1" gradientTransform="rotate(-115.896 19.594 6.144)scale(26.3315 19.1931)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="jsn-z3nbv"/><stop offset="1" class="m2pbtey6o"/></radialGradient><radialGradient id="ii8TjKb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.14 21.87883 -17.0804 -2.45134 14.584 7.982)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="c-fn9jb1q"/><stop offset="1" class="poosr8yyu"/></radialGradient><radialGradient id="iEbOCAd" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 3.71875 10.344 22.142)" gradientUnits="userSpaceOnUse"><stop class="z6--pfbwt"/><stop offset="1" class="n1nhqibha"/></radialGradient><linearGradient id="i7VhZpe" x1="12.875" x2="10.121" y1="12.579" y2="18.173" gradientUnits="userSpaceOnUse"><stop class="tm-l66prr"/><stop offset="1" class="ugomiebrb"/></linearGradient><linearGradient id="iYGArtc" x1="13.563" x2="15.563" y1="27.517" y2="21.923" gradientUnits="userSpaceOnUse"><stop offset=".218" class="jp8arbcli"/><stop offset="1" class="jh2_ekbyb"/></linearGradient><linearGradient id="iNuKMil" x1="14.509" x2="12.212" y1="20.489" y2="24.533" gradientUnits="userSpaceOnUse"><stop offset=".34" class="rft_gryci"/><stop offset="1" class="ytqwx-wlz"/></linearGradient><linearGradient id="isCJkRO" x1="11.755" x2="11.755" y1="19.142" y2="25.142" gradientUnits="userSpaceOnUse"><stop class="xfp71u_lw"/><stop offset="1" class="qljl7cbvu"/></linearGradient><linearGradient id="isM6nye" x1="11.563" x2="20" y1="31.517" y2="-.858" gradientUnits="userSpaceOnUse"><stop class="wdlm_ibqi"/><stop offset="1" class="a_2dfi9vb"/></linearGradient><linearGradient id="i0AsELb" x1="24.971" x2="17.565" y1="11.235" y2="3.423" gradientUnits="userSpaceOnUse"><stop class="rzq7xjs3j"/><stop offset=".51" class="y_a1ke75n"/><stop offset="1" class="rzq7xjs3j"/></linearGradient><linearGradient id="i2HZCBO" x1="8.441" x2="21.379" y1="2.017" y2="24.121" gradientUnits="userSpaceOnUse"><stop class="ah975e0ge"/><stop offset=".698" class="v4a2fcceg"/></linearGradient><filter id="iTpIz2c" width="15.705" height="12.527" x="9.486" y="2.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4649" stdDeviation=".5"/></filter><filter id="il3O7jQ" width="12.531" height="17.719" x="7.531" y="11.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4649" stdDeviation=".25"/></filter><filter id="iWAUZLe" width="7.872" height="7.872" x="8.005" y="18.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4649" stdDeviation=".375"/></filter><filter id="icwfK5b" width="6.128" height="6.128" x="8.691" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4649" stdDeviation=".25"/></filter><filter id="igROS4c" width="19.085" height="27.786" x="6.708" y="2.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.380392 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4649"/></filter><filter id="iiEoL3b" width="12.094" height="12.656" x="14.44" y="1.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4649" stdDeviation=".75"/></filter><filter id="iQkBnXd" width="13.063" height="23.361" x="6.941" y="6.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4649" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-medium" /></template>
<style>
.a_2dfi9vb {
  stop-color: var(--svg-color--bc977a, #BC977A);
}

.a65-qfb3x {
  stop-color: var(--svg-color--814a5c, #814A5C);
  stop-opacity: 0;
}

.ah975e0ge {
  stop-color: var(--svg-color--c59e8d, #C59E8D);
  stop-opacity: 0;
}

.b382ogbnr {
  stop-color: var(--svg-color--8d526c, #8D526C);
  stop-opacity: 0;
}

.c-fn9jb1q {
  stop-color: var(--svg-color--915877, #915877);
  stop-opacity: 0;
}

.crbyzbt1f {
  d: path("M12.577 28.735c-3.288-.25-4.546-2.063-4.546-5.304V12.173l2.344-.156l9.188 9.156l-2.938 4.969c-.989 1.845-1.68 2.593-4.049 2.593");
}

.ft5dv1b6b {
  fill: none;
}

.i6650-xam {
  stop-color: var(--svg-color--8d526c, #8D526C);
}

.ivry3481r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.19 9.187v14.705c.022.895.334 3.408 3.063 4.03c2.297.525 3.625-.687 4.276-1.905l1.224-2.125");
}

.jh2_ekbyb {
  stop-color: var(--svg-color--956761, #956761);
  stop-opacity: 0;
}

.jkkqseb-y {
  stop-color: var(--svg-color--c9a28e, #C9A28E);
  stop-opacity: 0;
}

.jp8arbcli {
  stop-color: var(--svg-color--956761, #956761);
}

.jsn-z3nbv {
  stop-color: var(--svg-color--9a7e69, #9A7E69);
  stop-opacity: 0;
}

.lapnfe-2y {
  fill: var(--svg-color--b6897b, #B6897B);
  d: path("M6.708 23.43c0 3.242 2.581 6.18 5.868 6.431c2.37 0 4.459-1.374 5.447-3.22l5.756-10.19a9.292 9.292 0 1 0-17.072-5.084z");
}

.m2pbtey6o {
  stop-color: var(--svg-color--9a7e69, #9A7E69);
}

.m3x6io8eb {
  stop-color: var(--svg-color--b6897b, #B6897B);
}

.m7rma2bnk {
  cx: 11.755px;
  cy: 22.142px;
  r: 3px;
}

.n_g-u-lhi {
  stop-color: var(--svg-color--b78a7d, #B78A7D);
  stop-opacity: 0;
}

.n1nhqibha {
  stop-color: var(--svg-color--b5877c, #B5877C);
  stop-opacity: 0;
}

.nz9u2tjef {
  stop-color: var(--svg-color--814a5c, #814A5C);
}

.o5ihkcskr {
  d: path("M18.167 22.696a1.8 1.8 0 0 0-2.439.69l-.859 1.52l-.018.035c-.366.682-1.156 1.316-2.135 1.316c-1.255 0-2.408-1.428-2.408-2.826V11.367a5.692 5.692 0 1 1 11.315.891c-.147.94.126 1.974.943 2.46c.9.537 2.084.21 2.37-.797a9.292 9.292 0 1 0-18.23-2.554v12.064c.002 3.24 2.583 6.18 5.87 6.43c2.37 0 4.459-1.374 5.447-3.22l.84-1.485a1.8 1.8 0 0 0-.696-2.46");
}

.poosr8yyu {
  stop-color: var(--svg-color--915877, #915877);
}

.qk8scsbaf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.94 3.579c2.291.375 6.919 2.431 7.094 7.656");
}

.qljl7cbvu {
  stop-color: var(--svg-color--a46b71, #A46B71);
}

.r4xp77bwq {
  cx: 17.338px;
  cy: 9.081px;
  rx: 7.28px;
  ry: 4.652px;
}

.rft_gryci {
  stop-color: var(--svg-color--c39986, #C39986);
}

.rzq7xjs3j {
  stop-color: var(--svg-color--c8a28b, #C8A28B);
  stop-opacity: 0;
}

.tm-l66prr {
  stop-color: var(--svg-color--7e3e53, #7E3E53);
}

.u8xbn9b3q {
  stop-color: var(--svg-color--b6897b, #B6897B);
  stop-opacity: 0;
}

.ugomiebrb {
  stop-color: var(--svg-color--7e3e53, #7E3E53);
  stop-opacity: 0;
}

.ulasi0k-c {
  stop-color: var(--svg-color--c9a28e, #C9A28E);
}

.v4a2fcceg {
  stop-color: var(--svg-color--c59e8d, #C59E8D);
}

.wdlm_ibqi {
  stop-color: var(--svg-color--9e716b, #9E716B);
}

.xfp71u_lw {
  stop-color: var(--svg-color--b1896f, #B1896F);
}

.xvrv_6bis {
  stop-color: var(--svg-color--b78a7d, #B78A7D);
}

.y_a1ke75n {
  stop-color: var(--svg-color--c8a28b, #C8A28B);
}

.ytqwx-wlz {
  stop-color: var(--svg-color--884461, #884461);
}

.yx_4vcb_f {
  cx: 11.941px;
  cy: 22.328px;
  r: 3.186px;
}

.z6--pfbwt {
  stop-color: var(--svg-color--b5877c, #B5877C);
}

.ztt7phbpm {
  cx: 11.755px;
  cy: 22.142px;
  r: 2.564px;
  fill: var(--svg-color--b28479, #B28479);
}

</style>
