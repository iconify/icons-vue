<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNxSaAe)"><path fill="url(#i37Anbb)" class="i9kveuxvm"/></g><g filter="url(#i3iXigb)"><path class="hmcmztgxb"/></g><g filter="url(#irzpxgd)"><path fill="url(#iAetl4b)" class="jl5j13liz"/></g><g filter="url(#iJN7lge)"><path fill="url(#ijRpzwd)" class="cb598vb7l"/></g><g filter="url(#iDyzmbb)"><path fill="url(#iLQMePd)" class="dezzd1jqo"/></g><g filter="url(#irbIB4d)"><path fill="url(#i2aZnKc)" class="rb7j11brh"/></g><g filter="url(#i4UlO1b)"><rect fill="url(#ins2Jrd)" class="p9k025bnu"/></g><defs><filter id="iNxSaAe" width="28.757" height="28.722" x="1.621" y="1.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.447059 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.227451 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19812" result="effect2_innerShadow_18_19812"/></filter><filter id="i3iXigb" width="19.666" height="14.186" x="5.837" y="15.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19812" stdDeviation=".25"/></filter><filter id="irzpxgd" width="19.494" height="13.861" x="6.328" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.607843 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19812" result="effect2_innerShadow_18_19812"/></filter><filter id="iJN7lge" width="19.444" height="3.031" x="6.378" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.368627 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.0784314 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19812" result="effect2_innerShadow_18_19812"/></filter><filter id="iDyzmbb" width="19.994" height="12.074" x="5.828" y="1.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.247059 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19812"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19812" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.223529 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.054902 0 0 0 0 0.0823529 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19812" result="effect3_innerShadow_18_19812"/></filter><filter id="irbIB4d" width="13.281" height="10.736" x="10.969" y="1.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.101961 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19812"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19812" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.596078 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.956863 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19812" result="effect3_innerShadow_18_19812"/></filter><filter id="i4UlO1b" width="4.112" height="8.347" x="18.85" y="2.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.196078 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.117647 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19812" result="effect2_innerShadow_18_19812"/></filter><linearGradient id="i37Anbb" x1="16" x2="16" y1="4.125" y2="29.861" gradientUnits="userSpaceOnUse"><stop class="wpbtuuseh"/><stop offset="1" class="ozj-p_k1c"/></linearGradient><linearGradient id="iAetl4b" x1="16" x2="16" y1="16" y2="29.861" gradientUnits="userSpaceOnUse"><stop class="knkdr4bvk"/><stop offset="1" class="k6ev-ubbh"/></linearGradient><linearGradient id="ijRpzwd" x1="6.578" x2="25.422" y1="17.875" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="wfydr1c5j"/><stop offset="1" class="v68fyhbdr"/></linearGradient><linearGradient id="iLQMePd" x1="16" x2="16" y1="2.139" y2="13.063" gradientUnits="userSpaceOnUse"><stop class="mqjyu-o1v"/><stop offset="1" class="et1vvqbzk"/></linearGradient><linearGradient id="i2aZnKc" x1="17.734" x2="17.734" y1="2.139" y2="12.125" gradientUnits="userSpaceOnUse"><stop class="irviv0cev"/><stop offset="1" class="f2m2u_bfv"/></linearGradient><linearGradient id="ins2Jrd" x1="20.906" x2="20.906" y1="3.031" y2="11.078" gradientUnits="userSpaceOnUse"><stop offset=".109" class="hku08jbmi"/><stop offset="1" class="mfcmutbgk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:floppy-disk" /></template>
<style>
.cb598vb7l {
  d: path("M25.422 19.031H6.578V17.5a1.5 1.5 0 0 1 1.5-1.5h15.844a1.5 1.5 0 0 1 1.5 1.5z");
}

.dezzd1jqo {
  d: path("M25.422 2.374v9.189a1.5 1.5 0 0 1-1.5 1.5H8.078a1.5 1.5 0 0 1-1.5-1.5V2.139h17.68a3 3 0 0 1 1.164.235");
}

.et1vvqbzk {
  stop-color: var(--svg-color--33285a, #33285A);
}

.f2m2u_bfv {
  stop-color: var(--svg-color--d0c6dc, #D0C6DC);
}

.ft5dv1b6b {
  fill: none;
}

.hku08jbmi {
  stop-color: var(--svg-color--491c4f, #491C4F);
}

.hmcmztgxb {
  fill: var(--svg-color--402360, #402360);
  d: path("M25.003 29.524H6.337v-11.76c0-.788.665-1.427 1.486-1.427h15.694c.821 0 1.486.64 1.486 1.428z");
}

.i9kveuxvm {
  d: path("M24.259 2.139a3 3 0 0 1 2.121.879L29 5.638a3 3 0 0 1 .879 2.12v18.853a3.25 3.25 0 0 1-3.25 3.25H5.37a3.25 3.25 0 0 1-3.25-3.25V5.39a3.25 3.25 0 0 1 3.25-3.25z");
}

.irviv0cev {
  stop-color: var(--svg-color--e8dff2, #E8DFF2);
}

.jl5j13liz {
  d: path("M25.422 29.861H6.578V17.5a1.5 1.5 0 0 1 1.5-1.5h15.844a1.5 1.5 0 0 1 1.5 1.5z");
}

.k6ev-ubbh {
  stop-color: var(--svg-color--d4c4e4, #D4C4E4);
}

.knkdr4bvk {
  stop-color: var(--svg-color--ddd1eb, #DDD1EB);
}

.mfcmutbgk {
  stop-color: var(--svg-color--222c60, #222C60);
}

.mqjyu-o1v {
  stop-color: var(--svg-color--3d2456, #3D2456);
}

.ozj-p_k1c {
  stop-color: var(--svg-color--563675, #563675);
}

.p9k025bnu {
  width: 3.813px;
  height: 8.047px;
  x: 19px;
  y: 3.031px;
  rx: 0.9px;
}

.rb7j11brh {
  d: path("M11.469 3.139a1 1 0 0 1 1-1H24v8.736c0 .69-.56 1.25-1.25 1.25H12.469a1 1 0 0 1-1-1z");
}

.v68fyhbdr {
  stop-color: var(--svg-color--c92e7f, #C92E7F);
}

.wfydr1c5j {
  stop-color: var(--svg-color--ea242b, #EA242B);
}

.wpbtuuseh {
  stop-color: var(--svg-color--5c60ad, #5C60AD);
}

</style>
