<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ise2Nwc)"><path class="oqpa-3bdd"/></g><path stroke="url(#ivZTsRd)" class="uw5y5_u7g"/><g filter="url(#i7W2bHb)"><path stroke="url(#izaFoTb)" class="ojp4zxqmj"/><path stroke="url(#iCaj97c)" class="ojp4zxqmj"/></g><g filter="url(#iDPkbCk)"><rect fill="url(#ieu8ede)" class="nd2ykhmzx"/></g><rect fill="url(#iM4pvne)" class="nd2ykhmzx"/><rect fill="url(#i5yX8Ae)" class="nd2ykhmzx"/><rect fill="url(#iFXIn5b)" class="nd2ykhmzx"/><g filter="url(#id6v26M)" class="c7knmzboe"><path stroke="url(#isVklNb)" class="py0s45b6f"/><path stroke="url(#iXYGv1c)" class="py0s45b6f"/></g><path fill="url(#irScKqd)" class="py0s45b6f"/><g filter="url(#irquiCe)"><path fill="url(#izv6jhd)" class="t880dnbnc"/></g><g filter="url(#iL6YKwc)"><path fill="url(#iRm14Fd)" class="twp0rxo-m"/></g><path fill="url(#iInS4mb)" class="twp0rxo-m"/><path fill="url(#iylxozd)" class="twp0rxo-m"/><path class="iog24tbmc"/><path fill="url(#iqfetJe)" class="kebgn923f"/><path fill="url(#id6z6kb)" class="kebgn923f"/><path fill="url(#i6UFUxb)" class="kebgn923f"/><g filter="url(#i0zCjec)"><rect class="b8vrkjbvb"/></g><rect fill="url(#i8cvpZd)" class="b0hl7gblz"/><g filter="url(#ir2oavd)"><path stroke="url(#ikVSdTb)" class="v0zjfhb4p"/></g><defs><radialGradient id="ivZTsRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 5.28858 0 14.344 7.586)" gradientUnits="userSpaceOnUse"><stop offset=".531" class="ic4s5xbvn"/><stop offset="1" class="zw343dbjx"/></radialGradient><radialGradient id="izaFoTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.81893 3.59375 -4.9365 -5.24582 20.274 4.523)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="f_yy7pxnt"/><stop offset="1" class="bdorqcccj"/></radialGradient><radialGradient id="iCaj97c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.125 5.16319 0 10.925 12.586)" gradientUnits="userSpaceOnUse"><stop class="f_yy7pxnt"/><stop offset="1" class="bdorqcccj"/></radialGradient><radialGradient id="iM4pvne" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18751 -2.40624 5.60574 -5.09619 24.781 29.898)" gradientUnits="userSpaceOnUse"><stop class="ol_x1zd0x"/><stop offset="1" class="wyhbviwvc"/></radialGradient><radialGradient id="iFXIn5b" cx="0" cy="0" r="1" gradientTransform="rotate(126.254 9.715 11.87)scale(2.32513 5.25171)" gradientUnits="userSpaceOnUse"><stop class="otx6b2qss"/><stop offset="1" class="kp53krb3m"/></radialGradient><radialGradient id="irScKqd" cx="0" cy="0" r="1" gradientTransform="rotate(34.061 -24.512 28.495)scale(5.69121 7.82719)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="p0s2a-btm"/><stop offset="1" class="vzphlmk8b"/></radialGradient><radialGradient id="iqfetJe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96094 0 0 -4.4375 26.125 26.344)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="gvrqdd_ra"/><stop offset="1" class="g1fgbdius"/></radialGradient><radialGradient id="id6z6kb" cx="0" cy="0" r="1" gradientTransform="matrix(4.40625 -4.0371 4.6308 5.05424 22.219 24.88)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="ml-zd-bco"/><stop offset=".886" class="l0fyolrnp"/></radialGradient><radialGradient id="i6UFUxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.64063 4.8322 0 24.766 29.438)" gradientUnits="userSpaceOnUse"><stop offset=".89" class="vml-_hiru"/><stop offset="1" class="zh7bx9nsc"/></radialGradient><radialGradient id="i8cvpZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09374 .875 -.80488 -1.0061 30 14.75)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="wtycgybtf"/><stop offset="1" class="c7ccps3-l"/></radialGradient><radialGradient id="ikVSdTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.96875 -.35938 .29841 1.63477 23.594 22.61)" gradientUnits="userSpaceOnUse"><stop class="oaulj8byt"/><stop offset="1" class="tt_g5nbxf"/></radialGradient><linearGradient id="ieu8ede" x1="8.531" x2="15.469" y1="14.117" y2="29.898" gradientUnits="userSpaceOnUse"><stop class="gkbwn2d_k"/><stop offset="1" class="ltuow0bom"/></linearGradient><linearGradient id="i5yX8Ae" x1="14.375" x2="14.375" y1="10.742" y2="12.242" gradientUnits="userSpaceOnUse"><stop class="oy1zi6b-t"/><stop offset="1" class="r8k5v-b5l"/></linearGradient><linearGradient id="isVklNb" x1="17.5" x2="13.625" y1="21.68" y2="21.68" gradientUnits="userSpaceOnUse"><stop offset=".331" class="z0qt9gb0h"/><stop offset="1" class="ew96f-mrq"/></linearGradient><linearGradient id="iXYGv1c" x1="11.25" x2="13.969" y1="20.742" y2="20.742" gradientUnits="userSpaceOnUse"><stop class="h80w1obxx"/><stop offset="1" class="k_9_8y67b"/></linearGradient><linearGradient id="izv6jhd" x1="23.502" x2="23.502" y1="14.817" y2="29.233" gradientUnits="userSpaceOnUse"><stop class="hi7fvlqdu"/><stop offset="1" class="xclgecc_f"/></linearGradient><linearGradient id="iRm14Fd" x1="22.656" x2="29.227" y1="21.25" y2="21.25" gradientUnits="userSpaceOnUse"><stop class="p3zchdnez"/><stop offset="1" class="v9mt15ugy"/></linearGradient><linearGradient id="iInS4mb" x1="22.469" x2="24.125" y1="27.625" y2="26.906" gradientUnits="userSpaceOnUse"><stop class="wgkw-9e3q"/><stop offset="1" class="rgmpu91-o"/></linearGradient><linearGradient id="iylxozd" x1="24.766" x2="24.766" y1="16.719" y2="17.438" gradientUnits="userSpaceOnUse"><stop offset=".273" class="q2_fveb5q"/><stop offset="1" class="p5jx9j6_q"/></linearGradient><filter id="ise2Nwc" width="13.781" height="11.953" x="7.953" y="2.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.556863 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23598"/></filter><filter id="i7W2bHb" width="12.75" height="12.953" x="8.469" y="1.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23598" stdDeviation=".375"/></filter><filter id="iDPkbCk" width="23.438" height="20.344" x="2.656" y="10.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23598"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.772549 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23598" result="effect2_innerShadow_18_23598"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23598" result="effect3_innerShadow_18_23598"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.478431 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_23598" result="effect4_innerShadow_18_23598"/></filter><filter id="id6v26M" width="7.965" height="12.26" x="10.379" y="14.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23598" stdDeviation=".25"/></filter><filter id="irquiCe" width="12.384" height="16.816" x="17.309" y="13.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23598" stdDeviation=".6"/></filter><filter id="iL6YKwc" width="10.422" height="15.768" x="19.555" y="14.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.509804 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23598"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.827451 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23598" result="effect2_innerShadow_18_23598"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.796078 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23598" result="effect3_innerShadow_18_23598"/></filter><filter id="i0zCjec" width="11.613" height="3.612" x="18.959" y="13.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.643137 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23598"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.411765 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23598" result="effect2_innerShadow_18_23598"/></filter><filter id="ir2oavd" width="1.858" height="3.625" x="23.127" y="20.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23598" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:locked-with-pen" /></template>
<style>
.b0hl7gblz {
  width: 10.813px;
  height: 2.813px;
  x: 19.359px;
  y: 14.219px;
  rx: 1.406px;
}

.b8vrkjbvb {
  width: 10.813px;
  height: 2.813px;
  x: 19.359px;
  y: 14.219px;
  fill: var(--svg-color--339aef, #339AEF);
  rx: 1.406px;
}

.bdorqcccj {
  stop-color: var(--svg-color--edecf3, #EDECF3);
  stop-opacity: 0;
}

.c7ccps3-l {
  stop-color: var(--svg-color--2faae9, #2FAAE9);
  stop-opacity: 0;
}

.c7knmzboe {
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
}

.ew96f-mrq {
  stop-color: var(--svg-color--d98a40, #D98A40);
  stop-opacity: 0;
}

.f_yy7pxnt {
  stop-color: var(--svg-color--edecf3, #EDECF3);
}

.ft5dv1b6b {
  fill: none;
}

.g1fgbdius {
  stop-color: var(--svg-color--4f3f5e, #4F3F5E);
  stop-opacity: 0;
}

.gkbwn2d_k {
  stop-color: var(--svg-color--ffc74e, #FFC74E);
}

.gvrqdd_ra {
  stop-color: var(--svg-color--4f3f5e, #4F3F5E);
}

.h80w1obxx {
  stop-color: var(--svg-color--ffcd63, #FFCD63);
}

.hi7fvlqdu {
  stop-color: var(--svg-color--aa6d3b, #AA6D3B);
}

.ic4s5xbvn {
  stop-color: var(--svg-color--ab83c0, #AB83C0);
}

.iog24tbmc {
  fill: var(--svg-color--766c81, #766C81);
  d: path("M25.266 23.343c0-.173.113-.322.265-.405a1.601 1.601 0 1 0-1.53 0c.15.083.265.232.265.405v5.989a.5.5 0 1 0 1 0z");
}

.k_9_8y67b {
  stop-color: var(--svg-color--ffcd63, #FFCD63);
  stop-opacity: 0;
}

.kebgn923f {
  d: path("M25.266 23.343c0-.173.113-.322.265-.405a1.601 1.601 0 1 0-1.53 0c.15.083.265.232.265.405v5.989a.5.5 0 1 0 1 0z");
}

.kp53krb3m {
  stop-color: var(--svg-color--fff760, #FFF760);
  stop-opacity: 0;
}

.l0fyolrnp {
  stop-color: var(--svg-color--53485e, #53485E);
}

.ltuow0bom {
  stop-color: var(--svg-color--f7864e, #F7864E);
}

.ml-zd-bco {
  stop-color: var(--svg-color--776b82, #776B82);
  stop-opacity: 0;
}

.nd2ykhmzx {
  width: 21.938px;
  height: 18.844px;
  x: 3.406px;
  y: 11.055px;
  rx: 3px;
}

.oaulj8byt {
  stop-color: var(--svg-color--949197, #949197);
}

.ojp4zxqmj {
  d: path("M9.719 14.07V8.31c0-2.868 2.294-5.193 5.125-5.193s5.125 2.325 5.125 5.194v5.76");
}

.ol_x1zd0x {
  stop-color: var(--svg-color--ff8650, #FF8650);
}

.oqpa-3bdd {
  stroke: var(--svg-color--c2c2c6, #C2C2C6);
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M9.328 14.07V8.508a5.016 5.016 0 0 1 10.031 0v5.562");
}

.otx6b2qss {
  stop-color: var(--svg-color--fff760, #FFF760);
}

.oy1zi6b-t {
  stop-color: var(--svg-color--f3d04e, #F3D04E);
}

.p0s2a-btm {
  stop-color: var(--svg-color--564f80, #564F80);
}

.p3zchdnez {
  stop-color: var(--svg-color--bdacd1, #BDACD1);
}

.p5jx9j6_q {
  stop-color: var(--svg-color--9d8bc2, #9D8BC2);
  stop-opacity: 0;
}

.py0s45b6f {
  d: path("M15.773 20.392a2.607 2.607 0 1 0-2.797.017v3.294a1.398 1.398 0 0 0 2.797 0z");
}

.q2_fveb5q {
  stop-color: var(--svg-color--9d8bc2, #9D8BC2);
}

.r8k5v-b5l {
  stop-color: var(--svg-color--f3d04e, #F3D04E);
  stop-opacity: 0;
}

.rgmpu91-o {
  stop-color: var(--svg-color--a97cc9, #A97CC9);
  stop-opacity: 0;
}

.t880dnbnc {
  d: path("M19.808 14.817a1.298 1.298 0 0 0-.426 2.525v4.49c0 .471.12.934.349 1.346l3.165 5.698a.693.693 0 0 0 1.211 0l3.165-5.698a2.8 2.8 0 0 0 .349-1.346v-4.49a1.3 1.3 0 0 0-.426-2.525z");
}

.tt_g5nbxf {
  stop-color: var(--svg-color--949197, #949197);
  stop-opacity: 0;
}

.twp0rxo-m {
  d: path("M20.305 15.563h8.922v6.254a3 3 0 0 1-.378 1.456l-3.428 6.172a.75.75 0 0 1-1.311 0l-3.428-6.172a3 3 0 0 1-.377-1.456z");
}

.uw5y5_u7g {
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M9.328 14.07V8.508a5.016 5.016 0 0 1 10.031 0v5.562");
}

.v0zjfhb4p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.547 21.172c-.115.374-.079 1.194.926 1.591c.08.032.136.108.136.194v1.09");
}

.v9mt15ugy {
  stop-color: var(--svg-color--b8a8cf, #B8A8CF);
}

.vml-_hiru {
  stop-color: var(--svg-color--64437e, #64437E);
  stop-opacity: 0;
}

.vzphlmk8b {
  stop-color: var(--svg-color--473154, #473154);
}

.wgkw-9e3q {
  stop-color: var(--svg-color--a97cc9, #A97CC9);
}

.wtycgybtf {
  stop-color: var(--svg-color--5cbeff, #5CBEFF);
}

.wyhbviwvc {
  stop-color: var(--svg-color--ff8650, #FF8650);
  stop-opacity: 0;
}

.xclgecc_f {
  stop-color: var(--svg-color--be5343, #BE5343);
}

.z0qt9gb0h {
  stop-color: var(--svg-color--d98a40, #D98A40);
}

.zh7bx9nsc {
  stop-color: var(--svg-color--64437e, #64437E);
}

.zw343dbjx {
  stop-color: var(--svg-color--cbbbdc, #CBBBDC);
  stop-opacity: 0;
}

</style>
