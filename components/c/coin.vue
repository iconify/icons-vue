<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iAjFfXx)"><circle fill="url(#i6PeFWd)" class="tmpu47bnw"/></g><g filter="url(#iouJTNe)"><path fill="url(#i2C546d)" clip-rule="evenodd" class="r52nfgbvk"/></g><g filter="url(#ipWHWSi)"><path clip-rule="evenodd" class="yxpdw5fax"/></g><g filter="url(#iiB72gd)"><path class="s0nj6v9vq"/></g><path fill="url(#iAvbCdp)" class="o14016bxf"/><path fill="url(#iBbIFqd)" class="meaod-v1b"/><path fill="url(#isw5ceb)" class="meaod-v1b"/><path fill="url(#izwpI3d)" class="hpg3n_vpv"/><path fill="url(#i8WXOKe)" class="hpg3n_vpv"/><path fill="url(#iQycaOd)" class="l0fd6-6iy"/><path fill="url(#ij90kmb)" class="l0fd6-6iy"/><path fill="url(#iiyv3De)" class="y_y1a7b6u"/><path fill="url(#iHzNxce)" class="y_y1a7b6u"/><g filter="url(#iy0scMd)"><path class="ph6tx9bpw"/></g><defs><linearGradient id="i6PeFWd" x1="11.563" x2="23.313" y1="21.852" y2="7.039" gradientUnits="userSpaceOnUse"><stop class="j5aeyiqkf"/><stop offset="1" class="pk6l4uqys"/></linearGradient><linearGradient id="i2C546d" x1="16" x2="16" y1="2.445" y2="30.383" gradientUnits="userSpaceOnUse"><stop class="ccmnchber"/><stop offset="1" class="nlatcjbue"/></linearGradient><linearGradient id="iAvbCdp" x1="19.313" x2="18.906" y1="9.289" y2="9.906" gradientUnits="userSpaceOnUse"><stop offset=".459" class="ell555b-a"/><stop offset="1" class="gx806ib7y"/></linearGradient><linearGradient id="iBbIFqd" x1="10.531" x2="11.313" y1="15.059" y2="15.059" gradientUnits="userSpaceOnUse"><stop offset=".167" class="rrsd1sbjs"/><stop offset="1" class="jer5pacxb"/></linearGradient><linearGradient id="isw5ceb" x1="11.995" x2="11.609" y1="16.686" y2="16.686" gradientUnits="userSpaceOnUse"><stop offset=".067" class="y2r152b0f"/><stop offset="1" class="r7-1ozt8j"/></linearGradient><linearGradient id="izwpI3d" x1="13.75" x2="14.531" y1="15.059" y2="15.059" gradientUnits="userSpaceOnUse"><stop offset=".167" class="rrsd1sbjs"/><stop offset="1" class="jer5pacxb"/></linearGradient><linearGradient id="i8WXOKe" x1="15.213" x2="14.828" y1="16.686" y2="16.686" gradientUnits="userSpaceOnUse"><stop offset=".067" class="y2r152b0f"/><stop offset="1" class="r7-1ozt8j"/></linearGradient><linearGradient id="iQycaOd" x1="16.969" x2="17.75" y1="15.059" y2="15.059" gradientUnits="userSpaceOnUse"><stop offset=".167" class="rrsd1sbjs"/><stop offset="1" class="jer5pacxb"/></linearGradient><linearGradient id="ij90kmb" x1="18.432" x2="18.047" y1="16.686" y2="16.686" gradientUnits="userSpaceOnUse"><stop offset=".067" class="y2r152b0f"/><stop offset="1" class="r7-1ozt8j"/></linearGradient><linearGradient id="iiyv3De" x1="20.188" x2="20.969" y1="15.059" y2="15.059" gradientUnits="userSpaceOnUse"><stop offset=".167" class="rrsd1sbjs"/><stop offset="1" class="jer5pacxb"/></linearGradient><linearGradient id="iHzNxce" x1="21.651" x2="21.266" y1="16.686" y2="16.686" gradientUnits="userSpaceOnUse"><stop offset=".067" class="y2r152b0f"/><stop offset="1" class="r7-1ozt8j"/></linearGradient><filter id="iAjFfXx" width="22" height="22" x="4.875" y="5.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.45098 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21332"/></filter><filter id="iouJTNe" width="28.538" height="28.538" x="1.731" y="2.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.662745 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.607843 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21332" result="effect2_innerShadow_18_21332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.607843 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21332" result="effect3_innerShadow_18_21332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.882353 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_21332" result="effect4_innerShadow_18_21332"/></filter><filter id="ipWHWSi" width="14.651" height="15.959" x="8.362" y="7.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21332" stdDeviation=".3"/></filter><filter id="iiB72gd" width="12.275" height="5.33" x="9.948" y="7.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.647059 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.647059 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21332" result="effect2_innerShadow_18_21332"/></filter><filter id="iy0scMd" width="13.951" height="2.836" x="9.024" y="19.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.658824 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.8 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21332" result="effect2_innerShadow_18_21332"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:coin" /></template>
<style>
.ccmnchber {
  stop-color: var(--svg-color--ffc444, #FFC444);
}

.ell555b-a {
  stop-color: var(--svg-color--ffca3f, #FFCA3F);
}

.ft5dv1b6b {
  fill: none;
}

.gx806ib7y {
  stop-color: var(--svg-color--ffca3f, #FFCA3F);
  stop-opacity: 0;
}

.hpg3n_vpv {
  d: path("M13.604 11.867h1.609v8.266h-1.609z");
}

.j5aeyiqkf {
  stop-color: var(--svg-color--f19d48, #F19D48);
}

.jer5pacxb {
  stop-color: var(--svg-color--ffc047, #FFC047);
}

.l0fd6-6iy {
  d: path("M16.823 11.867h1.609v8.266h-1.609z");
}

.meaod-v1b {
  d: path("M10.385 12.117a.25.25 0 0 1 .25-.25h1.11a.25.25 0 0 1 .25.25v8.016h-1.61z");
}

.nlatcjbue {
  stop-color: var(--svg-color--ffc24b, #FFC24B);
}

.o14016bxf {
  d: path("M9.948 11.54a.6.6 0 0 1 .277-.506l5.383-3.426a.75.75 0 0 1 .805 0l5.382 3.426a.6.6 0 0 1 .278.506v.28a.5.5 0 0 1-.5.5H10.448a.5.5 0 0 1-.5-.5z");
}

.ph6tx9bpw {
  fill: var(--svg-color--ffc248, #FFC248);
  d: path("M9.6 20.437a.7.7 0 0 1 .678-.523h11.48a.7.7 0 0 1 .682.543l.273 1.18a.5.5 0 0 1-.488.613H9.775a.5.5 0 0 1-.484-.626z");
}

.pk6l4uqys {
  stop-color: var(--svg-color--e89a44, #E89A44);
}

.r52nfgbvk {
  fill-rule: evenodd;
  d: path("M16 30.383c7.715 0 13.969-6.254 13.969-13.969S23.715 2.445 16 2.445S2.031 8.7 2.031 16.415c0 7.714 6.254 13.968 13.969 13.968m0-3.094c6.006 0 10.875-4.869 10.875-10.875S22.006 5.54 16 5.54S5.125 10.408 5.125 16.414S9.994 27.29 16 27.29");
}

.r7-1ozt8j {
  stop-color: var(--svg-color--ffc34c, #FFC34C);
  stop-opacity: 0;
}

.rrsd1sbjs {
  stop-color: var(--svg-color--ffb33b, #FFB33B);
}

.s0nj6v9vq {
  fill: var(--svg-color--ffc546, #FFC546);
  d: path("M9.948 11.54a.6.6 0 0 1 .277-.506l5.383-3.426a.75.75 0 0 1 .805 0l5.382 3.426a.6.6 0 0 1 .278.506v.28a.5.5 0 0 1-.5.5H10.448a.5.5 0 0 1-.5-.5z");
}

.tmpu47bnw {
  cx: 16px;
  cy: 16.414px;
  r: 10.875px;
}

.y_y1a7b6u {
  d: path("M20.041 11.867h1.609v8.266h-1.609z");
}

.y2r152b0f {
  stop-color: var(--svg-color--ffc34c, #FFC34C);
}

.yxpdw5fax {
  fill: var(--svg-color--dc7b3c, #DC7B3C);
  fill-rule: evenodd;
  d: path("M9.913 11.315a.6.6 0 0 0-.278.507v.28a.5.5 0 0 0 .438.496v7.597h-.108a.7.7 0 0 0-.677.524l-.31 1.186a.5.5 0 0 0 .484.626h12.45a.5.5 0 0 0 .488-.612l-.272-1.181a.7.7 0 0 0-.683-.543h-.107v-7.6a.5.5 0 0 0 .422-.493v-.28a.6.6 0 0 0-.277-.507L16.1 7.89a.75.75 0 0 0-.806 0zm9.816 8.88v-7.593h-1.61v7.593zm-3.219 0v-7.593H14.9v7.593zm-3.219 0v-7.593h-1.609v7.593z");
}

</style>
