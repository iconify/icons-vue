<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iMfF6ue)"><path fill="url(#iPjcRpq)" class="yl2v64bqm"/></g><g filter="url(#i8hZGBe)"><path clip-rule="evenodd" class="c-_mxpb-m"/></g><g filter="url(#iKPaWod)"><rect class="skhxjquge"/><rect fill="url(#iUO9Hsb)" class="k84muwbcu"/></g><g filter="url(#iHljDJd)"><rect class="fundv1bbk"/><rect fill="url(#iUzE6ea)" class="acpm5xbsx"/></g><g filter="url(#icKv9eu)"><rect class="h3ub5_88u"/><rect fill="url(#iJfH09h)" class="ld2o8l48f"/></g><g filter="url(#iJQNdkb)"><rect transform="matrix(-1 0 0 1 19.975 17.203)" class="m9-1j9v4o"/><rect fill="url(#iRWwSgb)" transform="matrix(-1 0 0 1 19.975 17.203)" class="tnobp9mnm"/></g><path fill="url(#iXPZDYc)" class="yg3b_1skz"/><path fill="url(#iTeyIuo)" class="yg3b_1skz"/><path fill="url(#igsXP0b)" class="yg3b_1skz"/><path fill="url(#imqlFjf)" class="yg3b_1skz"/><path fill="url(#iHZgNXc)" class="xr7ogq79v"/><path fill="url(#ipylXAe)" class="xr7ogq79v"/><path fill="url(#i2TMcWd)" class="xr7ogq79v"/><path fill="url(#i7t7HFv)" class="xr7ogq79v"/><defs><linearGradient id="iPjcRpq" x1="16.354" x2="16.354" y1="18.813" y2="25.938" gradientUnits="userSpaceOnUse"><stop class="oltvrh6sp"/><stop offset=".925" class="vtjfuqb9g"/></linearGradient><linearGradient id="iUO9Hsb" x1="12.823" x2="13.198" y1="12.875" y2="12.875" gradientUnits="userSpaceOnUse"><stop class="w3of42byc"/><stop offset="1" class="gynp_n4ki"/></linearGradient><linearGradient id="iUzE6ea" x1="13.543" x2="13.833" y1="15.34" y2="15.34" gradientUnits="userSpaceOnUse"><stop class="w3of42byc"/><stop offset="1" class="gynp_n4ki"/></linearGradient><linearGradient id="iJfH09h" x1="12.053" x2="12.219" y1="17.805" y2="17.805" gradientUnits="userSpaceOnUse"><stop class="w3of42byc"/><stop offset="1" class="gynp_n4ki"/></linearGradient><linearGradient id="iRWwSgb" x1=".143" x2=".389" y1=".602" y2=".602" gradientUnits="userSpaceOnUse"><stop class="w3of42byc"/><stop offset="1" class="gynp_n4ki"/></linearGradient><linearGradient id="iXPZDYc" x1="20.354" x2="4.979" y1="26.077" y2="26.077" gradientUnits="userSpaceOnUse"><stop class="o-91zc1hj"/><stop offset="1" class="nxnpsybtk"/></linearGradient><linearGradient id="iTeyIuo" x1="26.088" x2="23.479" y1="26.625" y2="26.563" gradientUnits="userSpaceOnUse"><stop class="q3o7qj9he"/><stop offset=".991" class="g5dkov7rr"/></linearGradient><linearGradient id="igsXP0b" x1="15.991" x2="15.991" y1="24.5" y2="25.313" gradientUnits="userSpaceOnUse"><stop offset=".115" class="tbsk4xk2d"/><stop offset="1" class="cx--hubeb"/></linearGradient><linearGradient id="iHZgNXc" x1="29.968" x2="1.354" y1="30.125" y2="30.125" gradientUnits="userSpaceOnUse"><stop class="onh-139ou"/><stop offset="1" class="ap5dourhx"/></linearGradient><linearGradient id="ipylXAe" x1=".104" x2="6.854" y1="29.83" y2="29.83" gradientUnits="userSpaceOnUse"><stop class="up-kk62qi"/><stop offset="1" class="fsopqyblt"/></linearGradient><linearGradient id="i2TMcWd" x1="19.104" x2="19.166" y1="31.375" y2="28.273" gradientUnits="userSpaceOnUse"><stop offset=".173" class="a23ukyb4x"/><stop offset="1" class="mhyd-jb-x"/></linearGradient><filter id="iMfF6ue" width="16.808" height="24.944" x="7.712" y="2.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.909804 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26637"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.513726 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26637" result="effect2_innerShadow_18_26637"/></filter><filter id="i8hZGBe" width="13.163" height="22.526" x="9.281" y="4.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.380392 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26637"/></filter><filter id="iKPaWod" width="7.041" height="1.037" x="12.354" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.380392 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26637"/></filter><filter id="iHljDJd" width="5.501" height="1.037" x="13.124" y="14.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.380392 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26637"/></filter><filter id="icKv9eu" width="3.269" height="1.037" x="11.706" y="17.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.380392 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26637"/></filter><filter id="iJQNdkb" width="4.705" height="1.037" x="15.27" y="17.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.380392 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26637"/></filter><radialGradient id="imqlFjf" cx="0" cy="0" r="1" gradientTransform="matrix(-8.07812 0 0 -.39063 22.026 25.516)" gradientUnits="userSpaceOnUse"><stop offset=".067" class="n96m7mb5y"/><stop offset="1" class="smpas28qk"/></radialGradient><radialGradient id="i7t7HFv" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.21875 -14.5324 0 22.916 28.063)" gradientUnits="userSpaceOnUse"><stop class="balwi0bhx"/><stop offset="1" class="yj3hrnm_p"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:headstone" /></template>
<style>
.a23ukyb4x {
  stop-color: var(--svg-color--5a936e, #5A936E);
}

.acpm5xbsx {
  width: 5.251px;
  height: 0.787px;
  x: 13.374px;
  y: 14.738px;
  rx: 0.394px;
}

.ap5dourhx {
  stop-color: var(--svg-color--73b056, #73B056);
}

.balwi0bhx {
  stop-color: var(--svg-color--a9f2a1, #A9F2A1);
}

.c-_mxpb-m {
  fill: var(--svg-color--929299, #929299);
  fill-rule: evenodd;
  d: path("M15.99 5.218a2.55 2.55 0 0 0-2.464 1.902c-.09.344-.392.653-.8.653h-2.27a.375.375 0 0 0-.375.375V26.42c0 .124.1.225.225.225h11.363c.124 0 .225-.1.225-.225V8.148a.375.375 0 0 0-.375-.375h-2.263c-.408 0-.71-.31-.8-.653a2.55 2.55 0 0 0-2.465-1.902M12.995 6.98a3.099 3.099 0 0 1 5.994 0c.04.155.16.243.268.243h2.263c.51 0 .925.414.925.925V26.42a.775.775 0 0 1-.775.775H10.306a.775.775 0 0 1-.775-.775V8.148c0-.511.414-.925.925-.925h2.27c.107 0 .227-.088.268-.243");
}

.cx--hubeb {
  stop-color: var(--svg-color--b5b4b9, #B5B4B9);
  stop-opacity: 0;
}

.fsopqyblt {
  stop-color: var(--svg-color--699860, #699860);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fundv1bbk {
  width: 5.251px;
  height: 0.787px;
  x: 13.374px;
  y: 14.738px;
  fill: var(--svg-color--929299, #929299);
  rx: 0.394px;
}

.g5dkov7rr {
  stop-color: var(--svg-color--d4d6d8, #D4D6D8);
  stop-opacity: 0;
}

.gynp_n4ki {
  stop-color: var(--svg-color--9b9ba1, #9B9BA1);
  stop-opacity: 0;
}

.h3ub5_88u {
  width: 3.019px;
  height: 0.787px;
  x: 11.956px;
  y: 17.203px;
  fill: var(--svg-color--929299, #929299);
  rx: 0.394px;
}

.k84muwbcu {
  width: 6.791px;
  height: 0.787px;
  x: 12.604px;
  y: 12.273px;
  rx: 0.394px;
}

.ld2o8l48f {
  width: 3.019px;
  height: 0.787px;
  x: 11.956px;
  y: 17.203px;
  rx: 0.394px;
}

.m9-1j9v4o {
  width: 4.455px;
  height: 0.787px;
  fill: var(--svg-color--929299, #929299);
  rx: 0.394px;
}

.mhyd-jb-x {
  stop-color: var(--svg-color--92baa3, #92BAA3);
  stop-opacity: 0;
}

.n96m7mb5y {
  stop-color: var(--svg-color--ddd9e4, #DDD9E4);
}

.nxnpsybtk {
  stop-color: var(--svg-color--7d7b89, #7D7B89);
}

.o-91zc1hj {
  stop-color: var(--svg-color--dddbe5, #DDDBE5);
}

.oltvrh6sp {
  stop-color: var(--svg-color--c1c1c7, #C1C1C7);
}

.onh-139ou {
  stop-color: var(--svg-color--9be173, #9BE173);
}

.q3o7qj9he {
  stop-color: var(--svg-color--d4d6d8, #D4D6D8);
}

.skhxjquge {
  width: 6.791px;
  height: 0.787px;
  x: 12.604px;
  y: 12.273px;
  fill: var(--svg-color--929299, #929299);
  rx: 0.394px;
}

.smpas28qk {
  stop-color: var(--svg-color--ddd9e4, #DDD9E4);
  stop-opacity: 0;
}

.tbsk4xk2d {
  stop-color: var(--svg-color--b5b4b9, #B5B4B9);
}

.tnobp9mnm {
  width: 4.455px;
  height: 0.787px;
  rx: 0.394px;
}

.up-kk62qi {
  stop-color: var(--svg-color--699860, #699860);
}

.vtjfuqb9g {
  stop-color: var(--svg-color--a4a2ad, #A4A2AD);
}

.w3of42byc {
  stop-color: var(--svg-color--9b9ba1, #9B9BA1);
}

.xr7ogq79v {
  d: path("M2.014 29.216a2.5 2.5 0 0 1 2.5-2.5h22.954a2.5 2.5 0 0 1 2.5 2.5v.614H2.014z");
}

.yg3b_1skz {
  d: path("M5.894 25.8a1 1 0 0 1 1-1h18.194a1 1 0 0 1 1 1v1.554H5.894z");
}

.yj3hrnm_p {
  stop-color: var(--svg-color--8fd99f, #8FD99F);
  stop-opacity: 0;
}

.yl2v64bqm {
  d: path("M19.938 5.327c.091.18.271.301.473.301h1.609a2 2 0 0 1 2 2v19.726H7.962V7.628a2 2 0 0 1 2-2h1.61a.54.54 0 0 0 .472-.301a4.43 4.43 0 0 1 7.894 0");
}

</style>
