<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="igd1lkc" class="i-9wdrbdh"/><path id="idBpJCd" class="pv5wpfbxv"/></defs><g class="ft5dv1b6b"><g filter="url(#i2u8n1c)"><rect fill="url(#irrtIyd)" class="jw37a2btn"/><rect fill="url(#iv3ivJd)" class="jw37a2btn"/></g><g filter="url(#i3hWQ3U)"><path stroke="url(#iFMethc)" class="wc3s2d61j"/></g><g filter="url(#iGrbkgb)"><path stroke="url(#iYm0zec)" class="nh8ncbcye"/></g><g filter="url(#iBxOJER)" class="mzeqhufrl"><use href="#igd1lkc"/><use href="#idBpJCd"/></g><g filter="url(#izXtlGd)" class="b-c38gb2l"><use href="#igd1lkc"/><use href="#idBpJCd"/></g><defs><filter id="i2u8n1c" width="29.875" height="28.875" x="2.512" y="1.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1123"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1123" result="effect2_innerShadow_18590_1123"/></filter><filter id="i3hWQ3U" width="5.5" height="28.375" x="25.95" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1123" stdDeviation="1"/></filter><filter id="iGrbkgb" width="27.281" height="5.5" x="3.226" y="1.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1123" stdDeviation="1"/></filter><filter id="iBxOJER" width="19.591" height="22" x="6.651" y="5.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1123" stdDeviation=".5"/></filter><filter id="izXtlGd" width="18.392" height="20.8" x="7.251" y="5.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1123"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1123" result="effect2_innerShadow_18590_1123"/></filter><linearGradient id="irrtIyd" x1="16.45" x2="16.45" y1="5.887" y2="39.14" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="iFMethc" x1="29.2" x2="29.2" y1="4.813" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iYm0zec" x1="28.914" x2="3.382" y1="4.375" y2="4.375" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="iv3ivJd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.169 4.406)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dotted-six-pointed-star" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.fitiklbqp {
  stop-color: var(--svg-color--7764c6, #7764C6);
}

.ft5dv1b6b {
  fill: none;
}

.i-9wdrbdh {
  d: path("M16.446 17.25a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.jlbvuvbtx {
  stop-color: var(--svg-color--9a6ceb, #9A6CEB);
}

.jw37a2btn {
  width: 27.875px;
  height: 27.875px;
  x: 2.512px;
  y: 2.313px;
  rx: 3.6px;
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
}

.mzeqhufrl {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
}

.nh8ncbcye {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.976 4.125h21.781");
}

.pv5wpfbxv {
  d: path("M15.58 6.75L13.3 10.7a.1.1 0 0 1-.087.05H8.652a1 1 0 0 0-.866 1.5l2.28 3.95a.1.1 0 0 1 0 .1l-2.28 3.95a1 1 0 0 0 .866 1.5h4.561a.1.1 0 0 1 .087.05l2.28 3.95a1 1 0 0 0 1.732 0l2.28-3.95a.1.1 0 0 1 .087-.05h4.562a1 1 0 0 0 .866-1.5l-2.281-3.95a.1.1 0 0 1 0-.1l2.28-3.95a1 1 0 0 0-.866-1.5h-4.56a.1.1 0 0 1-.087-.05l-2.28-3.95a1 1 0 0 0-1.733 0m.78 1.65a.1.1 0 0 1 .173 0l1.27 2.2a.1.1 0 0 1-.087.15h-2.54a.1.1 0 0 1-.087-.15zm-6.755 4a.1.1 0 0 1 .086-.15h2.54a.1.1 0 0 1 .087.15l-1.27 2.2a.1.1 0 0 1-.173 0zm4.503-.1a.1.1 0 0 1 .087-.05h4.503a.1.1 0 0 1 .087.05l2.251 3.9a.1.1 0 0 1 0 .1l-2.251 3.9a.1.1 0 0 1-.087.05h-4.503a.1.1 0 0 1-.087-.05l-2.252-3.9a.1.1 0 0 1 0-.1zm-4.417 7.95a.1.1 0 0 1-.086-.15l1.27-2.2a.1.1 0 0 1 .173 0l1.27 2.2a.1.1 0 0 1-.086.15zm6.842 3.85a.1.1 0 0 1-.173 0l-1.27-2.2a.1.1 0 0 1 .086-.15h2.54a.1.1 0 0 1 .087.15zm5.311-6.2a.1.1 0 0 1 .174 0l1.27 2.2a.1.1 0 0 1-.087.15h-2.54a.1.1 0 0 1-.087-.15zm1.357-5.65a.1.1 0 0 1 .087.15l-1.27 2.2a.1.1 0 0 1-.174 0l-1.27-2.2a.1.1 0 0 1 .087-.15z");
}

.s-kusnt3y {
  stop-color: var(--svg-color--8777d6, #8777D6);
}

.sefcefa1m {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
  stop-opacity: 0;
}

.sn77b5ppw {
  stop-color: var(--svg-color--9865ee, #9865EE);
}

.wc3s2d61j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.7 4.813v22.875");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

</style>
