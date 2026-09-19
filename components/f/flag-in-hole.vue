<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIlSx1b)"><ellipse fill="url(#i0NCope)" class="yrhs_ff0g"/></g><ellipse fill="url(#iPTxeKd)" class="yrhs_ff0g"/><ellipse fill="url(#i3wEMed)" class="t1nvrc1ze"/><g filter="url(#iZOSnYd)"><path fill="url(#itROCle)" class="qov_yu0qd"/><path fill="url(#ibpXCud)" class="qov_yu0qd"/><path fill="url(#im73Y9b)" class="qov_yu0qd"/></g><g filter="url(#ifVYNRc)"><ellipse fill="url(#ias8Ufe)" class="k2ty5gync"/></g><g filter="url(#idlS92c)"><circle fill="url(#i9UMz6d)" class="h4lne7rqb"/><circle fill="url(#ioEfa0b)" class="h4lne7rqb"/></g><circle fill="url(#ilcCzVG)" class="h4lne7rqb"/><g filter="url(#iywHQOQ)"><path fill="url(#iHGcrPe)" class="j105kjb7i"/></g><path fill="url(#ioNshfc)" class="j105kjb7i"/><defs><radialGradient id="iPTxeKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.5625 -15.1177 0 16 23.377)" gradientUnits="userSpaceOnUse"><stop offset=".929" class="x8e4hccxp"/><stop offset="1" class="fidhgub_l"/></radialGradient><radialGradient id="i3wEMed" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.52941 -6.39631 0 11 22.262)" gradientUnits="userSpaceOnUse"><stop class="rj5cscc9m"/><stop offset="1" class="z078ftqhy"/></radialGradient><radialGradient id="ibpXCud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -24.25 2 0 10 24.94)" gradientUnits="userSpaceOnUse"><stop class="ksho_9-if"/><stop offset="1" class="em22d09id"/></radialGradient><radialGradient id="im73Y9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.3198 18.875 -1.60075 -.02712 12.32 1.94)" gradientUnits="userSpaceOnUse"><stop class="e1mqdubtr"/><stop offset="1" class="y-fj9rbyz"/></radialGradient><radialGradient id="ias8Ufe" cx="0" cy="0" r="1" gradientTransform="rotate(179.519 10.722 12.589)scale(3.56882 2.05665)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="cv_6erufa"/><stop offset="1" class="lh5ckubfu"/></radialGradient><radialGradient id="i9UMz6d" cx="0" cy="0" r="1" gradientTransform="rotate(124.032 5.216 17.38)scale(2.90356)" gradientUnits="userSpaceOnUse"><stop class="xic0viuth"/><stop offset="1" class="f5hw_9uzw"/></radialGradient><radialGradient id="ioEfa0b" cx="0" cy="0" r="1" gradientTransform="rotate(25.322 -39.887 52.744)scale(3.06877)" gradientUnits="userSpaceOnUse"><stop class="hnw0tgbsw"/><stop offset="1" class="c8-x66bxo"/></radialGradient><radialGradient id="ilcCzVG" cx="0" cy="0" r="1" gradientTransform="rotate(138.764 7.374 15.395)scale(2.23005 2.03919)" gradientUnits="userSpaceOnUse"><stop class="jl6qsbbwr"/><stop offset="1" class="buaifacel"/></radialGradient><radialGradient id="ioNshfc" cx="0" cy="0" r="1" gradientTransform="rotate(158.199 9.493 4.992)scale(1.7506 1.96192)" gradientUnits="userSpaceOnUse"><stop class="aegg-ab_y"/><stop offset="1" class="r1hui7b0f"/></radialGradient><filter id="iIlSx1b" width="28" height="12.5" x="2" y="17.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.533333 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2762"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.823529 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2762" result="effect2_innerShadow_18_2762"/></filter><filter id="iZOSnYd" width="2.25" height="23" x="10" y="1.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.619608 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2762"/></filter><filter id="ifVYNRc" width="5.177" height="2.638" x="17.923" y="23.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2762" stdDeviation=".3"/></filter><filter id="idlS92c" width="3.6" height="3.6" x="19.75" y="21.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.627451 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2762"/></filter><filter id="iywHQOQ" width="8.095" height="7" x="11.75" y="2.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.235294 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2762"/></filter><linearGradient id="i0NCope" x1="16" x2="16" y1="17.94" y2="29.94" gradientUnits="userSpaceOnUse"><stop class="pmuc2bbea"/><stop offset=".516" class="t8sxsac4e"/><stop offset="1" class="iwc980b0p"/></linearGradient><linearGradient id="itROCle" x1="11" x2="11" y1="1.94" y2="24.94" gradientUnits="userSpaceOnUse"><stop class="kk4drooft"/><stop offset="1" class="gy-pbtbxn"/></linearGradient><linearGradient id="iHGcrPe" x1="12.57" x2="17.257" y1="6.44" y2="6.44" gradientUnits="userSpaceOnUse"><stop class="e3yhjnyzu"/><stop offset="1" class="cu6kgybxe"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flag-in-hole" /></template>
<style>
.aegg-ab_y {
  stop-color: var(--svg-color--ff509a, #FF509A);
}

.buaifacel {
  stop-color: var(--svg-color--f4f2f6, #F4F2F6);
  stop-opacity: 0;
}

.c8-x66bxo {
  stop-color: var(--svg-color--beadb0, #BEADB0);
  stop-opacity: 0;
}

.cu6kgybxe {
  stop-color: var(--svg-color--fe4093, #FE4093);
}

.cv_6erufa {
  stop-color: var(--svg-color--3f693a, #3F693A);
}

.e1mqdubtr {
  stop-color: var(--svg-color--fff6ce, #FFF6CE);
}

.e3yhjnyzu {
  stop-color: var(--svg-color--ff396a, #FF396A);
}

.em22d09id {
  stop-color: var(--svg-color--cc8050, #CC8050);
  stop-opacity: 0;
}

.f5hw_9uzw {
  stop-color: var(--svg-color--aab0b7, #AAB0B7);
}

.fidhgub_l {
  stop-color: var(--svg-color--49885f, #49885F);
}

.ft5dv1b6b {
  fill: none;
}

.gy-pbtbxn {
  stop-color: var(--svg-color--ffc797, #FFC797);
}

.h4lne7rqb {
  cx: 21.5px;
  cy: 23.44px;
  r: 1.75px;
}

.hnw0tgbsw {
  stop-color: var(--svg-color--beadb0, #BEADB0);
}

.iwc980b0p {
  stop-color: var(--svg-color--3d976e, #3D976E);
}

.j105kjb7i {
  d: path("m12 2.94l7.5 3c.46.19.46.82 0 1l-7.5 3z");
}

.jl6qsbbwr {
  stop-color: var(--svg-color--f4f2f6, #F4F2F6);
}

.k2ty5gync {
  cx: 20.512px;
  cy: 24.698px;
  rx: 1.989px;
  ry: 0.719px;
}

.kk4drooft {
  stop-color: var(--svg-color--ffd1b2, #FFD1B2);
}

.ksho_9-if {
  stop-color: var(--svg-color--cc8050, #CC8050);
}

.lh5ckubfu {
  stop-color: var(--svg-color--3f693a, #3F693A);
  stop-opacity: 0;
}

.pmuc2bbea {
  stop-color: var(--svg-color--91cf4d, #91CF4D);
}

.qov_yu0qd {
  d: path("M12 2.94a1 1 0 1 0-2 0v21.952a10.4 10.4 0 0 0 2 0z");
}

.r1hui7b0f {
  stop-color: var(--svg-color--ff509a, #FF509A);
  stop-opacity: 0;
}

.rj5cscc9m {
  stop-color: var(--svg-color--402155, #402155);
}

.t1nvrc1ze {
  cx: 11px;
  cy: 23.44px;
  rx: 4px;
  ry: 1.5px;
}

.t8sxsac4e {
  stop-color: var(--svg-color--6aaa60, #6AAA60);
}

.x8e4hccxp {
  stop-color: var(--svg-color--49885f, #49885F);
  stop-opacity: 0;
}

.xic0viuth {
  stop-color: var(--svg-color--fefaff, #FEFAFF);
}

.y-fj9rbyz {
  stop-color: var(--svg-color--fff6ce, #FFF6CE);
  stop-opacity: 0;
}

.yrhs_ff0g {
  cx: 16px;
  cy: 23.94px;
  rx: 14px;
  ry: 6px;
}

.z078ftqhy {
  stop-color: var(--svg-color--3d254d, #3D254D);
}

</style>
