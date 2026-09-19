<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="n49f3nbxe"/><g filter="url(#iW9acge)"><ellipse fill="url(#i8Z5ghc)" transform="rotate(26.087 17.338 9.08)" class="r4xp77bwq"/></g><g filter="url(#iekilJb)"><path fill="url(#iFARlrD)" class="crbyzbt1f"/><path fill="url(#irrG7gc)" class="crbyzbt1f"/></g><g filter="url(#ioFY16A)"><circle fill="url(#iR7w9Ab)" class="yx_4vcb_f"/></g><circle fill="url(#i7P2Y8d)" class="m7rma2bnk"/><circle fill="url(#i5AD8uc)" class="m7rma2bnk"/><g filter="url(#i2fezyb)"><circle class="v7zggzlfz"/></g><g filter="url(#in36pZP)"><path fill="url(#ix3ohqc)" class="o5ihkcskr"/><path fill="url(#idYasub)" class="o5ihkcskr"/></g><path fill="url(#iK8qGAh)" class="o5ihkcskr"/><path fill="url(#iuqIhKc)" class="o5ihkcskr"/><path fill="url(#i4UMSXg)" class="o5ihkcskr"/><path fill="url(#iH0bl8c)" class="o5ihkcskr"/><path fill="url(#i4vHp8d)" class="o5ihkcskr"/><g filter="url(#iuqxQ1T)"><path stroke="url(#iDCog5b)" class="qk8scsbaf"/></g><g filter="url(#ietqvOc)"><path stroke="url(#iD6EQJe)" class="ivry3481r"/></g><defs><radialGradient id="i8Z5ghc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.156 15.517 -1.78)scale(8.19144 14.286)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="weqkr_gez"/><stop offset=".848" class="k1fta1k0h"/></radialGradient><radialGradient id="i5AD8uc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10816 1.52067 -1.73662 -2.40753 14.464 20.918)" gradientUnits="userSpaceOnUse"><stop class="b7dt6bces"/><stop offset="1" class="lk54okbbk"/></radialGradient><radialGradient id="idYasub" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 -5.5625 6.22805 4.33864 17.5 10.829)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="wexl8hbrp"/><stop offset="1" class="u0ai40brw"/></radialGradient><radialGradient id="iK8qGAh" cx="0" cy="0" r="1" gradientTransform="matrix(.14338 -4.62474 6.13434 .19019 23.232 15.266)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="nk0yk6bpo"/><stop offset="1" class="wo1l5vlld"/></radialGradient><radialGradient id="iuqIhKc" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.796 17.183)scale(4.97005 4.84669)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="j213y8b_z"/><stop offset="1" class="s6hodnclx"/></radialGradient><radialGradient id="i4UMSXg" cx="0" cy="0" r="1" gradientTransform="rotate(-115.896 19.594 6.144)scale(26.3315 19.1931)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="geiohvc-k"/><stop offset="1" class="wv520pb2j"/></radialGradient><radialGradient id="iH0bl8c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.14 21.87883 -17.0804 -2.45134 14.584 7.982)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="slqm18afk"/><stop offset="1" class="krm_xyb7b"/></radialGradient><radialGradient id="i4vHp8d" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 3.71875 10.344 22.142)" gradientUnits="userSpaceOnUse"><stop class="ed9he7b7j"/><stop offset="1" class="n0ir8cc2b"/></radialGradient><linearGradient id="iFARlrD" x1="12.875" x2="10.121" y1="12.579" y2="18.173" gradientUnits="userSpaceOnUse"><stop class="cv682bwyn"/><stop offset="1" class="obx-byr_k"/></linearGradient><linearGradient id="irrG7gc" x1="13.563" x2="15.563" y1="27.517" y2="21.923" gradientUnits="userSpaceOnUse"><stop offset=".218" class="t0pfiyv6j"/><stop offset="1" class="yjavyd1fm"/></linearGradient><linearGradient id="iR7w9Ab" x1="14.509" x2="12.212" y1="20.489" y2="24.533" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ezawixn4c"/><stop offset="1" class="b6dteyiyz"/></linearGradient><linearGradient id="i7P2Y8d" x1="11.755" x2="11.755" y1="19.142" y2="25.142" gradientUnits="userSpaceOnUse"><stop class="jm3s2ob9f"/><stop offset="1" class="nj54hy1xi"/></linearGradient><linearGradient id="ix3ohqc" x1="11.563" x2="20" y1="31.517" y2="-.858" gradientUnits="userSpaceOnUse"><stop class="w2-x-bk1j"/><stop offset="1" class="yl4u8mmhw"/></linearGradient><linearGradient id="iDCog5b" x1="24.971" x2="17.565" y1="11.235" y2="3.423" gradientUnits="userSpaceOnUse"><stop class="sicchzd0u"/><stop offset=".51" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iD6EQJe" x1="8.441" x2="21.379" y1="2.017" y2="24.121" gradientUnits="userSpaceOnUse"><stop class="sicchzd0u"/><stop offset=".698" class="eqmylox_y"/></linearGradient><filter id="iW9acge" width="15.705" height="12.527" x="9.486" y="2.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4638" stdDeviation=".5"/></filter><filter id="iekilJb" width="12.531" height="17.719" x="7.531" y="11.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4638" stdDeviation=".25"/></filter><filter id="ioFY16A" width="7.872" height="7.872" x="8.005" y="18.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4638" stdDeviation=".375"/></filter><filter id="i2fezyb" width="6.128" height="6.128" x="8.691" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4638" stdDeviation=".25"/></filter><filter id="in36pZP" width="19.085" height="27.786" x="6.708" y="2.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.301961 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4638"/></filter><filter id="iuqxQ1T" width="12.094" height="12.656" x="14.44" y="1.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4638" stdDeviation=".75"/></filter><filter id="ietqvOc" width="13.063" height="23.361" x="6.941" y="6.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4638" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-medium-dark" /></template>
<style>
.b6dteyiyz {
  stop-color: var(--svg-color--432218, #432218);
}

.b7dt6bces {
  stop-color: var(--svg-color--a27d74, #A27D74);
}

.crbyzbt1f {
  d: path("M12.577 28.735c-3.288-.25-4.546-2.063-4.546-5.304V12.173l2.344-.156l9.188 9.156l-2.938 4.969c-.989 1.845-1.68 2.593-4.049 2.593");
}

.cv682bwyn {
  stop-color: var(--svg-color--4d2123, #4D2123);
}

.ed9he7b7j {
  stop-color: var(--svg-color--906260, #906260);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.ezawixn4c {
  stop-color: var(--svg-color--947267, #947267);
}

.ft5dv1b6b {
  fill: none;
}

.geiohvc-k {
  stop-color: var(--svg-color--795e52, #795E52);
  stop-opacity: 0;
}

.ivry3481r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.19 9.187v14.705c.022.895.334 3.408 3.063 4.03c2.297.525 3.625-.687 4.276-1.905l1.224-2.125");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.jm3s2ob9f {
  stop-color: var(--svg-color--835b4b, #835B4B);
}

.k1fta1k0h {
  stop-color: var(--svg-color--603147, #603147);
}

.krm_xyb7b {
  stop-color: var(--svg-color--7d426e, #7D426E);
}

.lk54okbbk {
  stop-color: var(--svg-color--a27d74, #A27D74);
  stop-opacity: 0;
}

.m7rma2bnk {
  cx: 11.755px;
  cy: 22.142px;
  r: 3px;
}

.n0ir8cc2b {
  stop-color: var(--svg-color--906260, #906260);
  stop-opacity: 0;
}

.n49f3nbxe {
  fill: var(--svg-color--906461, #906461);
  d: path("M6.708 23.43c0 3.242 2.581 6.18 5.868 6.431c2.37 0 4.459-1.374 5.447-3.22l5.756-10.19a9.292 9.292 0 1 0-17.072-5.084z");
}

.nj54hy1xi {
  stop-color: var(--svg-color--7f4b58, #7F4B58);
}

.nk0yk6bpo {
  stop-color: var(--svg-color--906461, #906461);
}

.o5ihkcskr {
  d: path("M18.167 22.696a1.8 1.8 0 0 0-2.439.69l-.859 1.52l-.018.035c-.366.682-1.156 1.316-2.135 1.316c-1.255 0-2.408-1.428-2.408-2.826V11.367a5.692 5.692 0 1 1 11.315.891c-.147.94.126 1.974.943 2.46c.9.537 2.084.21 2.37-.797a9.292 9.292 0 1 0-18.23-2.554v12.064c.002 3.24 2.583 6.18 5.87 6.43c2.37 0 4.459-1.374 5.447-3.22l.84-1.485a1.8 1.8 0 0 0-.696-2.46");
}

.obx-byr_k {
  stop-color: var(--svg-color--4d2123, #4D2123);
  stop-opacity: 0;
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

.s6hodnclx {
  stop-color: var(--svg-color--926763, #926763);
  stop-opacity: 0;
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.slqm18afk {
  stop-color: var(--svg-color--7d426e, #7D426E);
  stop-opacity: 0;
}

.t0pfiyv6j {
  stop-color: var(--svg-color--5b4136, #5B4136);
}

.u0ai40brw {
  stop-color: var(--svg-color--813462, #813462);
  stop-opacity: 0;
}

.v7zggzlfz {
  cx: 11.755px;
  cy: 22.142px;
  r: 2.564px;
  fill: var(--svg-color--8e605f, #8E605F);
}

.w2-x-bk1j {
  stop-color: var(--svg-color--825259, #825259);
}

.weqkr_gez {
  stop-color: var(--svg-color--603147, #603147);
  stop-opacity: 0;
}

.wexl8hbrp {
  stop-color: var(--svg-color--653440, #653440);
}

.wo1l5vlld {
  stop-color: var(--svg-color--906461, #906461);
  stop-opacity: 0;
}

.wv520pb2j {
  stop-color: var(--svg-color--795e52, #795E52);
}

.yjavyd1fm {
  stop-color: var(--svg-color--5b4136, #5B4136);
  stop-opacity: 0;
}

.yl4u8mmhw {
  stop-color: var(--svg-color--906b5b, #906B5B);
}

.yx_4vcb_f {
  cx: 11.941px;
  cy: 22.328px;
  r: 3.186px;
}

</style>
