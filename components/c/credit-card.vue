<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8yW00c)"><rect fill="url(#imnVPnE)" class="b_zfvib2r"/></g><path fill="url(#iPRfmAe)" class="ujbibob_k"/><path fill="url(#i0bssNd)" class="ujbibob_k"/><path fill="url(#iZr39Iz)" class="ujbibob_k"/><g filter="url(#ivC2Cza)"><path class="dfcdevbiu"/></g><g filter="url(#iVcl5Cb)"><rect fill="url(#ieFVt8l)" class="rlpohr8za"/></g><g filter="url(#iTkPicb)"><rect fill="url(#iubrKIe)" class="jl871g_fl"/></g><defs><linearGradient id="imnVPnE" x1="16" x2="16" y1="11.969" y2="29.063" gradientUnits="userSpaceOnUse"><stop class="yklz3ybhx"/><stop offset="1" class="zhbrd5hxj"/></linearGradient><linearGradient id="iPRfmAe" x1="2.031" x2="29.969" y1="17.063" y2="17.063" gradientUnits="userSpaceOnUse"><stop class="jcxjty9fl"/><stop offset=".88" class="b9796ab2x"/></linearGradient><linearGradient id="i0bssNd" x1="2.031" x2="3.535" y1="16.794" y2="16.794" gradientUnits="userSpaceOnUse"><stop offset=".239" class="qno849g2x"/><stop offset=".707" class="mazi73b7u"/></linearGradient><linearGradient id="iZr39Iz" x1="29.969" x2="29.281" y1="16.938" y2="16.938" gradientUnits="userSpaceOnUse"><stop offset=".328" class="hgok_pxna"/><stop offset="1" class="jcopo4bsk"/></linearGradient><linearGradient id="ieFVt8l" x1="6.063" x2="16.938" y1="22" y2="22" gradientUnits="userSpaceOnUse"><stop class="jiqbebc6z"/><stop offset="1" class="gfj-2hbfq"/></linearGradient><linearGradient id="iubrKIe" x1="27.906" x2="25.031" y1="25.719" y2="25.719" gradientUnits="userSpaceOnUse"><stop class="ywxbr5bdi"/><stop offset="1" class="x1nw6obai"/></linearGradient><filter id="i8yW00c" width="28.738" height="18.706" x="1.631" y="11.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.580392 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.419608 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21638" result="effect2_innerShadow_18_21638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.929412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21638" result="effect3_innerShadow_18_21638"/></filter><filter id="ivC2Cza" width="19.181" height="4.4" x="4.669" y="19.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.580392 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_21638"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_21638" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.764706 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_21638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.92549 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21638" result="effect3_innerShadow_18_21638"/></filter><filter id="iVcl5Cb" width="12.012" height="1.3" x="5.963" y="21.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.788235 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_21638"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_21638" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.592157 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_21638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.662745 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21638" result="effect3_innerShadow_18_21638"/></filter><filter id="iTkPicb" width="4.131" height="4.131" x="23.875" y="24.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.596078 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_21638"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_21638" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.905882 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_21638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.694118 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21638" result="effect3_innerShadow_18_21638"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:credit-card" /></template>
<style>
.b_zfvib2r {
  width: 27.938px;
  height: 17.906px;
  x: 2.031px;
  y: 11.969px;
  rx: 2.25px;
}

.b9796ab2x {
  stop-color: var(--svg-color--3d3b3b, #3D3B3B);
}

.dfcdevbiu {
  fill: var(--svg-color--e2ddde, #E2DDDE);
  d: path("M5.719 23.969a.75.75 0 0 1-.75-.75v-2.5a.75.75 0 0 1 .75-.75H23a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75z");
}

.ft5dv1b6b {
  fill: none;
}

.gfj-2hbfq {
  stop-color: var(--svg-color--a6a2a2, #A6A2A2);
}

.hgok_pxna {
  stop-color: var(--svg-color--474646, #474646);
}

.jcopo4bsk {
  stop-color: var(--svg-color--474646, #474646);
  stop-opacity: 0;
}

.jcxjty9fl {
  stop-color: var(--svg-color--5d476d, #5D476D);
}

.jiqbebc6z {
  stop-color: var(--svg-color--a5a0a1, #A5A0A1);
}

.jl871g_fl {
  width: 3.531px;
  height: 3.531px;
  x: 24.375px;
  y: 24.313px;
  rx: 0.75px;
}

.mazi73b7u {
  stop-color: var(--svg-color--513e5f, #513E5F);
  stop-opacity: 0;
}

.qno849g2x {
  stop-color: var(--svg-color--513e5f, #513E5F);
}

.rlpohr8za {
  width: 11.813px;
  height: 1px;
  x: 6.063px;
  y: 21.5px;
  rx: 0.5px;
}

.ujbibob_k {
  d: path("M2.031 17.969v-3.125H29.97v3.125z");
}

.x1nw6obai {
  stop-color: var(--svg-color--eac037, #EAC037);
}

.yklz3ybhx {
  stop-color: var(--svg-color--57d8f2, #57D8F2);
}

.ywxbr5bdi {
  stop-color: var(--svg-color--f9d940, #F9D940);
}

.zhbrd5hxj {
  stop-color: var(--svg-color--36a3e7, #36A3E7);
}

</style>
