<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iK0nqDc)"><path class="zweohabwi"/></g><path fill="url(#iX4oVmO)" class="v3svk8boj"/><g filter="url(#iepwybc)"><path class="ytwp-nbnc"/></g><path fill="url(#iV3dKEq)" class="e4yyq3byb"/><g filter="url(#ie6nYpd)"><path class="wbi9_5suk"/></g><g filter="url(#i8mLY1d)"><path class="sf2mpp7cj"/><path fill="url(#ix6oTHd)" class="mv3wyhwvs"/></g><g filter="url(#i2LVdBd)"><path class="khlt47bma"/><path fill="url(#imnkeyc)" class="h-dpxnx9n"/></g><g filter="url(#ionSqGe)"><path fill="url(#iUPE47d)" class="sm4xgpkdb"/><path fill="url(#iGfE2je)" class="sm4xgpkdb"/></g><defs><filter id="iK0nqDc" width="5.35" height="4.5" x="24.9" y="16.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.607843 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.945098 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14846" result="effect2_innerShadow_18_14846"/></filter><filter id="iepwybc" width="5.24" height="5.111" x="20.6" y="2.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.705882 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14846" result="effect2_innerShadow_18_14846"/></filter><filter id="ie6nYpd" width="5.037" height="5.416" x="5.7" y="1.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.658824 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14846" result="effect2_innerShadow_18_14846"/></filter><filter id="i8mLY1d" width="5.048" height="4.179" x="1.75" y="17.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.615686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14846"/></filter><filter id="i2LVdBd" width="4.533" height="4.893" x="13.829" y="24.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.588235 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14846"/></filter><filter id="ionSqGe" width="25.75" height="24.75" x="2.75" y="1.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.494118 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25" dy="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_14846" result="effect2_innerShadow_18_14846"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.619608 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_14846" result="effect3_innerShadow_18_14846"/></filter><radialGradient id="iX4oVmO" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 -1.9375 2.68748 5.20157 26.406 19.524)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="s47dbvbxo"/><stop offset="1" class="cl-tt5b9u"/></radialGradient><radialGradient id="iUPE47d" cx="0" cy="0" r="1" gradientTransform="rotate(132.911 9.484 8.96)scale(16.4664 16.2945)" gradientUnits="userSpaceOnUse"><stop class="jcelcc_ol"/><stop offset="1" class="jiwmxu20n"/></radialGradient><radialGradient id="iGfE2je" cx="0" cy="0" r="1" gradientTransform="rotate(90 .816 14.684)scale(11.5)" gradientUnits="userSpaceOnUse"><stop class="s7287fb-k"/><stop offset="1" class="z-y7i6bgh"/></radialGradient><linearGradient id="iV3dKEq" x1="24.719" x2="24.031" y1="2.836" y2="3.868" gradientUnits="userSpaceOnUse"><stop class="lh3ro3d-g"/><stop offset="1" class="oxqrrnbnp"/></linearGradient><linearGradient id="ix6oTHd" x1="4.399" x2="4.399" y1="17.368" y2="18.368" gradientUnits="userSpaceOnUse"><stop class="w9greouzj"/><stop offset="1" class="smx4sqbxj"/></linearGradient><linearGradient id="imnkeyc" x1="17.625" x2="16.531" y1="27.336" y2="27.805" gradientUnits="userSpaceOnUse"><stop class="typim9vcm"/><stop offset="1" class="qc8wd-lfs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:glowing-star" /></template>
<style>
.cl-tt5b9u {
  stop-color: var(--svg-color--fff055, #FFF055);
}

.e4yyq3byb {
  d: path("m21.75 3.06l-.72 2.9c-.2.78.66 1.41 1.34.98l2.54-1.58c.55-.34.58-1.14.05-1.52l-1.78-1.29a.912.912 0 0 0-1.43.51");
}

.ft5dv1b6b {
  fill: none;
}

.h-dpxnx9n {
  d: path("m17.795 28.372l-1.12-2.77c-.3-.75-1.36-.75-1.66 0l-1.12 2.77c-.24.6.2 1.26.85 1.26h2.2a.92.92 0 0 0 .85-1.26");
}

.jcelcc_ol {
  stop-color: var(--svg-color--fac632, #FAC632);
}

.jiwmxu20n {
  stop-color: var(--svg-color--f7c632, #F7C632);
}

.khlt47bma {
  fill: var(--svg-color--e3b028, #E3B028);
  d: path("m17.795 28.372l-1.12-2.77c-.3-.75-1.36-.75-1.66 0l-1.12 2.77c-.24.6.2 1.26.85 1.26h2.2a.92.92 0 0 0 .85-1.26");
}

.lh3ro3d-g {
  stop-color: var(--svg-color--fff659, #FFF659);
}

.mv3wyhwvs {
  d: path("m4.185 21.08l2.29-1.92c.62-.52.29-1.53-.51-1.58l-2.98-.21a.92.92 0 0 0-.94 1.2l.68 2.09c.2.62.97.84 1.46.42");
}

.oxqrrnbnp {
  stop-color: var(--svg-color--fff659, #FFF659);
  stop-opacity: 0;
}

.qc8wd-lfs {
  stop-color: var(--svg-color--f9c83c, #F9C83C);
  stop-opacity: 0;
}

.s47dbvbxo {
  stop-color: var(--svg-color--fff055, #FFF055);
  stop-opacity: 0;
}

.s7287fb-k {
  stop-color: var(--svg-color--ddba38, #DDBA38);
}

.sf2mpp7cj {
  fill: var(--svg-color--dfad26, #DFAD26);
  d: path("m4.185 21.08l2.29-1.92c.62-.52.29-1.53-.51-1.58l-2.98-.21a.92.92 0 0 0-.94 1.2l.68 2.09c.2.62.97.84 1.46.42");
}

.sm4xgpkdb {
  d: path("m17.565 3.692l1.726 3.72c.326.694.967 1.18 1.717 1.289l4.056.625c1.835.278 2.575 2.53 1.293 3.858l-3.089 3.185a2.28 2.28 0 0 0-.612 1.963l.71 4.375c.307 1.884-1.687 3.293-3.354 2.37l-3.405-1.894a2.25 2.25 0 0 0-2.21 0l-3.404 1.895c-1.668.922-3.661-.487-3.355-2.371l.71-4.375a2.28 2.28 0 0 0-.612-1.963l-3.088-3.184c-1.293-1.34-.543-3.581 1.293-3.86l4.055-.624a2.3 2.3 0 0 0 1.717-1.29l1.727-3.72c.819-1.765 3.306-1.765 4.124 0");
}

.smx4sqbxj {
  stop-color: var(--svg-color--deae2c, #DEAE2C);
  stop-opacity: 0;
}

.typim9vcm {
  stop-color: var(--svg-color--f9c83c, #F9C83C);
}

.v3svk8boj {
  d: path("m28.979 17.37l-3.108.214c-.834.061-1.178 1.08-.542 1.609l2.388 1.955c.521.427 1.314.203 1.523-.428l.709-2.128c.219-.631-.292-1.272-.97-1.221");
}

.w9greouzj {
  stop-color: var(--svg-color--deae2c, #DEAE2C);
}

.wbi9_5suk {
  fill: var(--svg-color--eaba25, #EABA25);
  d: path("m6.43 5.362l2.53 1.58c.68.43 1.54-.19 1.35-.98l-.72-2.9a.92.92 0 0 0-1.43-.52l-1.78 1.29c-.53.4-.5 1.19.05 1.53");
}

.ytwp-nbnc {
  fill: var(--svg-color--f4c226, #F4C226);
  d: path("m21.75 3.06l-.72 2.9c-.2.78.66 1.41 1.34.98l2.54-1.58c.55-.34.58-1.14.05-1.52l-1.78-1.29a.912.912 0 0 0-1.43.51");
}

.z-y7i6bgh {
  stop-color: var(--svg-color--ddba38, #DDBA38);
  stop-opacity: 0;
}

.zweohabwi {
  fill: var(--svg-color--f6c327, #F6C327);
  d: path("m28.979 17.37l-3.108.214c-.834.061-1.178 1.08-.542 1.609l2.388 1.955c.521.427 1.314.203 1.523-.428l.709-2.128c.219-.631-.292-1.272-.97-1.221");
}

</style>
