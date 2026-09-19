<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ie8mnve)"><rect fill="url(#iJWkeCb)" class="ureja0nlo"/><rect fill="url(#is7lbIb)" class="ureja0nlo"/></g><g filter="url(#iI9Fltb)"><path stroke="url(#iJmo6zO)" class="fvhakib9z"/></g><g filter="url(#iqBBrLi)"><path stroke="url(#iv9KSJb)" class="o311fobps"/></g><g filter="url(#ikMHtjb)"><path clip-rule="evenodd" class="ta6ca0iii"/></g><g filter="url(#itKKlHd)"><path class="l91bfohca"/></g><g filter="url(#iy656im)"><path clip-rule="evenodd" class="ur52e6bho"/></g><g filter="url(#iCITfae)"><path clip-rule="evenodd" class="i4lgtw65w"/></g><g filter="url(#i7glf0b)"><path class="zxoct2bvm"/></g><g filter="url(#ihw99wb)"><path clip-rule="evenodd" class="s_2rllbzb"/></g><defs><filter id="ie8mnve" width="28.875" height="28.875" x="2.066" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_346"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_346" result="effect2_innerShadow_18590_346"/></filter><filter id="iI9Fltb" width="5.5" height="28.375" x="25.503" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_346" stdDeviation="1"/></filter><filter id="iqBBrLi" width="27.281" height="5.5" x="2.78" y="1.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_346" stdDeviation="1"/></filter><filter id="ikMHtjb" width="8.91" height="8.936" x="3.877" y="11.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_346" stdDeviation=".5"/></filter><filter id="itKKlHd" width="8.98" height="8.952" x="10.426" y="11.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_346" stdDeviation=".5"/></filter><filter id="iy656im" width="9.407" height="8.954" x="18.715" y="11.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_346" stdDeviation=".5"/></filter><filter id="iCITfae" width="7.31" height="7.336" x="4.477" y="12.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.741176 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_346"/></filter><filter id="i7glf0b" width="7.38" height="7.352" x="11.026" y="12.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.741176 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_346"/></filter><filter id="ihw99wb" width="7.807" height="7.354" x="19.315" y="12.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.741176 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_346"/></filter><linearGradient id="iJWkeCb" x1="16.003" x2="16.003" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iJmo6zO" x1="28.753" x2="28.753" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iv9KSJb" x1="28.467" x2="2.936" y1="4.125" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="is7lbIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 4.156)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:atm-sign" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fvhakib9z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.254 4.563v22.875");
}

.i4lgtw65w {
  fill: var(--svg-color--e3dfeb, #E3DFEB);
  fill-rule: evenodd;
  d: path("M9.915 17.946a.1.1 0 0 1 .09.057l.353.75a.75.75 0 0 0 1.358-.638l-2.472-5.263c-.38-.81-1.535-.803-1.906.012l-2.393 5.26a.75.75 0 0 0 1.365.62l.337-.74a.1.1 0 0 1 .091-.058zm-.798-1.5a.1.1 0 0 0 .09-.143l-.815-1.736a.1.1 0 0 0-.181 0l-.79 1.737a.1.1 0 0 0 .09.142z");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.l91bfohca {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M12.176 12.249a.75.75 0 1 0 0 1.5h1.89a.1.1 0 0 1 .1.1v4.602a.75.75 0 0 0 1.5 0v-4.603a.1.1 0 0 1 .1-.1h1.89a.75.75 0 0 0 0-1.5z");
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.o311fobps {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 3.875h21.78");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.s_2rllbzb {
  fill: var(--svg-color--e3dfeb, #E3DFEB);
  fill-rule: evenodd;
  d: path("M20.194 12.3a.75.75 0 0 1 .825.193l2.27 2.485a.1.1 0 0 0 .146.002l2.396-2.5a.75.75 0 0 1 1.292.519v5.454a.75.75 0 0 1-1.5 0v-3.339a.1.1 0 0 0-.173-.07l-1.56 1.63a.75.75 0 0 1-1.096-.013l-1.405-1.539a.1.1 0 0 0-.174.068v3.263a.75.75 0 0 1-1.5 0v-5.454c0-.31.19-.588.479-.7");
}

.ta6ca0iii {
  fill: var(--svg-color--579fff, #579FFF);
  fill-rule: evenodd;
  d: path("M9.915 17.946a.1.1 0 0 1 .09.057l.353.75a.75.75 0 0 0 1.358-.638l-2.472-5.263c-.38-.81-1.535-.803-1.906.012l-2.393 5.26a.75.75 0 0 0 1.365.62l.337-.74a.1.1 0 0 1 .091-.058zm-.798-1.5a.1.1 0 0 0 .09-.143l-.815-1.736a.1.1 0 0 0-.181 0l-.79 1.737a.1.1 0 0 0 .09.142z");
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.ur52e6bho {
  fill: var(--svg-color--579fff, #579FFF);
  fill-rule: evenodd;
  d: path("M20.194 12.3a.75.75 0 0 1 .825.193l2.27 2.485a.1.1 0 0 0 .146.002l2.396-2.5a.75.75 0 0 1 1.292.519v5.454a.75.75 0 0 1-1.5 0v-3.339a.1.1 0 0 0-.173-.07l-1.56 1.63a.75.75 0 0 1-1.096-.013l-1.405-1.539a.1.1 0 0 0-.174.068v3.263a.75.75 0 0 1-1.5 0v-5.454c0-.31.19-.588.479-.7");
}

.ureja0nlo {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 2.063px;
  rx: 3.6px;
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

.zxoct2bvm {
  fill: var(--svg-color--e3dfeb, #E3DFEB);
  d: path("M12.176 12.249a.75.75 0 1 0 0 1.5h1.89a.1.1 0 0 1 .1.1v4.602a.75.75 0 0 0 1.5 0v-4.603a.1.1 0 0 1 .1-.1h1.89a.75.75 0 0 0 0-1.5z");
}

</style>
