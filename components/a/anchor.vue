<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iICKVCb)" class="jx3nnhrpd"/><path fill="url(#ifmAVkd)" class="jx3nnhrpd"/><path fill="url(#i3u78Zb)" class="jx3nnhrpd"/><path fill="url(#iwbGiUb)" class="jx3nnhrpd"/><path fill="url(#ihbllle)" class="jx3nnhrpd"/><path fill="url(#imnUErd)" class="ldh-y8byk"/><path fill="url(#i3FYAud)" class="ldh-y8byk"/><g filter="url(#iFTvrhd)"><path fill="url(#iNV14Hd)" class="xkmz0_e1j"/><path fill="url(#iOrTycd)" class="xkmz0_e1j"/></g><g filter="url(#iTmrrJe)"><path fill="url(#icFIyTC)" class="po13k11lc"/></g><g filter="url(#ib4Dikd)"><path fill="url(#igMdmrc)" class="yijhkejvn"/><path fill="url(#iR0g03r)" class="yijhkejvn"/></g><g filter="url(#iAdNArs)"><path fill="url(#i6MDcqe)" class="r8p_f2b0w"/><path fill="url(#i57flle)" class="r8p_f2b0w"/></g><defs><linearGradient id="iICKVCb" x1="23.002" x2="11.631" y1="11.515" y2="11.515" gradientUnits="userSpaceOnUse"><stop class="h0vqh3ahr"/><stop offset="1" class="ppyaw8bro"/></linearGradient><linearGradient id="ifmAVkd" x1="16" x2="16" y1="13.461" y2="12.014" gradientUnits="userSpaceOnUse"><stop class="cblvsls4g"/><stop offset="1" class="j7uxujb0d"/></linearGradient><linearGradient id="i3u78Zb" x1="23" x2="21.625" y1="12.125" y2="12.125" gradientUnits="userSpaceOnUse"><stop class="s_3aabbop"/><stop offset="1" class="qtblbzbyj"/></linearGradient><linearGradient id="iwbGiUb" x1="9" x2="10.338" y1="12.014" y2="12.014" gradientUnits="userSpaceOnUse"><stop class="cblvsls4g"/><stop offset="1" class="j7uxujb0d"/></linearGradient><linearGradient id="imnUErd" x1="17.626" x2="14.308" y1="17.015" y2="17.015" gradientUnits="userSpaceOnUse"><stop class="ko7g6rbvd"/><stop offset="1" class="h0zkv_b7k"/></linearGradient><linearGradient id="iNV14Hd" x1="29.003" x2="23.003" y1="19.015" y2="19.015" gradientUnits="userSpaceOnUse"><stop class="jnfaqrkna"/><stop offset="1" class="n4v4jmbfz"/></linearGradient><linearGradient id="iOrTycd" x1="26.001" x2="26.001" y1="22.013" y2="21.56" gradientUnits="userSpaceOnUse"><stop class="f_n2w87qu"/><stop offset="1" class="hqn4nub9u"/></linearGradient><linearGradient id="icFIyTC" x1="9.002" x2="3.002" y1="19.009" y2="19.009" gradientUnits="userSpaceOnUse"><stop class="jnfaqrkna"/><stop offset="1" class="n4v4jmbfz"/></linearGradient><linearGradient id="igMdmrc" x1="27.312" x2="6.403" y1="26.015" y2="26.015" gradientUnits="userSpaceOnUse"><stop class="ktyekfbiv"/><stop offset="1" class="ztzhcmblr"/></linearGradient><linearGradient id="iR0g03r" x1="7.124" x2="7.749" y1="20.388" y2="23.076" gradientUnits="userSpaceOnUse"><stop offset=".269" class="m-7kglbxg"/><stop offset="1" class="j2rz9wbyw"/></linearGradient><linearGradient id="i6MDcqe" x1="19" x2="14.156" y1="3.5" y2="7.336" gradientUnits="userSpaceOnUse"><stop class="edwnimb-i"/><stop offset="1" class="ly_uoab7e"/></linearGradient><filter id="iFTvrhd" width="6.55" height="6.25" x="22.75" y="16.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.952941 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12108"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.47451 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12108" result="effect2_innerShadow_18_12108"/></filter><filter id="iTmrrJe" width="6.5" height="6.513" x="2.749" y="15.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.952941 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12108"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.47451 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12108" result="effect2_innerShadow_18_12108"/></filter><filter id="ib4Dikd" width="23.12" height="8.5" x="4.69" y="21.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.47451 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12108"/></filter><filter id="iAdNArs" width="6.65" height="6.65" x="12.75" y="1.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.933333 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12108"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.490196 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12108" result="effect2_innerShadow_18_12108"/></filter><radialGradient id="ihbllle" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29946 -3.6013 2.07831 -.74992 14.385 12.014)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="cblvsls4g"/><stop offset="1" class="j7uxujb0d"/></radialGradient><radialGradient id="i3FYAud" cx="0" cy="0" r="1" gradientTransform="matrix(.60171 2.43852 -3.0897 .7624 15.653 6.497)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="k_gbpuf0g"/><stop offset="1" class="z607qkh9u"/></radialGradient><radialGradient id="i57flle" cx="0" cy="0" r="1" gradientTransform="rotate(135.855 9.22 5.103)scale(2.88494)" gradientUnits="userSpaceOnUse"><stop class="k6vg0jbqy"/><stop offset="1" class="g-7bzxkob"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:anchor" /></template>
<style>
.cblvsls4g {
  stop-color: var(--svg-color--3875c8, #3875C8);
}

.edwnimb-i {
  stop-color: var(--svg-color--4fcaff, #4FCAFF);
}

.f_n2w87qu {
  stop-color: var(--svg-color--2884e2, #2884E2);
}

.ft5dv1b6b {
  fill: none;
}

.g-7bzxkob {
  stop-color: var(--svg-color--6ef, #6EF);
  stop-opacity: 0;
}

.h0vqh3ahr {
  stop-color: var(--svg-color--55e3ff, #55E3FF);
}

.h0zkv_b7k {
  stop-color: var(--svg-color--2f80c2, #2F80C2);
}

.hqn4nub9u {
  stop-color: var(--svg-color--2884e2, #2884E2);
  stop-opacity: 0;
}

.j2rz9wbyw {
  stop-color: var(--svg-color--2274d1, #2274D1);
  stop-opacity: 0;
}

.j7uxujb0d {
  stop-color: var(--svg-color--3875c8, #3875C8);
  stop-opacity: 0;
}

.jnfaqrkna {
  stop-color: var(--svg-color--5ad7ff, #5AD7FF);
}

.jx3nnhrpd {
  d: path("M10.5 13.013h11c.83 0 1.5-.67 1.5-1.5s-.67-1.5-1.5-1.5h-11c-.83 0-1.5.67-1.5 1.5s.67 1.5 1.5 1.5");
}

.k_gbpuf0g {
  stop-color: var(--svg-color--287bbd, #287BBD);
}

.k6vg0jbqy {
  stop-color: var(--svg-color--6ef, #6EF);
}

.ko7g6rbvd {
  stop-color: var(--svg-color--53ddff, #53DDFF);
}

.ktyekfbiv {
  stop-color: var(--svg-color--5bdaff, #5BDAFF);
}

.ldh-y8byk {
  d: path("M14 7.013h4v20h-4z");
}

.ly_uoab7e {
  stop-color: var(--svg-color--2ea3ef, #2EA3EF);
}

.m-7kglbxg {
  stop-color: var(--svg-color--2274d1, #2274D1);
}

.n4v4jmbfz {
  stop-color: var(--svg-color--31a5f4, #31A5F4);
}

.po13k11lc {
  d: path("M4.02 22.013h3.96c.87 0 1.34-1.022.77-1.684L5.36 16.36c-.57-.671-1.66-.35-1.78.521l-.57 3.97a1.02 1.02 0 0 0 1.01 1.162");
}

.ppyaw8bro {
  stop-color: var(--svg-color--2890e1, #2890E1);
}

.qtblbzbyj {
  stop-color: var(--svg-color--71fbff, #71FBFF);
  stop-opacity: 0;
}

.r8p_f2b0w {
  d: path("M13 5.013c0 1.66 1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3s-3 1.34-3 3m2 0c0-.55.45-1 1-1s1 .45 1 1s-.45 1-1 1s-1-.45-1-1");
}

.s_3aabbop {
  stop-color: var(--svg-color--71fbff, #71FBFF);
}

.xkmz0_e1j {
  d: path("M27.98 22.013h-3.96c-.87 0-1.34-1.02-.77-1.68l3.39-3.96c.57-.67 1.66-.35 1.78.52l.57 3.96c.09.61-.39 1.16-1.01 1.16");
}

.yijhkejvn {
  d: path("M4.69 22.013c1.64 4.66 6.08 8 11.31 8s9.67-3.34 11.31-8h-3.25a9 9 0 0 1-8.06 5a9 9 0 0 1-8.06-5z");
}

.z607qkh9u {
  stop-color: var(--svg-color--287bbd, #287BBD);
  stop-opacity: 0;
}

.ztzhcmblr {
  stop-color: var(--svg-color--41b2ff, #41B2FF);
}

</style>
