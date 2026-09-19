<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuADjqc)"><path fill="url(#iP4iOrd)" class="edy124b4o"/><path fill="url(#iiip31c)" class="edy124b4o"/></g><g filter="url(#iywyhzb)"><path class="i_-bz1pvf"/><path class="d3zndlbrg"/></g><g filter="url(#imqYwCo)"><path fill="url(#ihYlbKZ)" class="idyuke0jn"/></g><g filter="url(#iRe4vfe)"><path class="ahxwg43hk"/><path class="bmwj6cbiq"/></g><g filter="url(#i5sy6vc)"><path fill="url(#ix5TCzW)" class="pwc08lgdd"/></g><g filter="url(#ig5P15b)"><path stroke="url(#iwyNygb)" clip-rule="evenodd" class="x45cqjdej"/><path stroke="url(#iw7EhVb)" clip-rule="evenodd" class="x45cqjdej"/></g><g filter="url(#iJXe0Wb)"><path stroke="url(#iifnxOb)" clip-rule="evenodd" class="yc0w_otgh"/><path stroke="url(#ibBVDwd)" clip-rule="evenodd" class="yc0w_otgh"/></g><ellipse fill="url(#iJlBXAe)" transform="rotate(-39.013 11.504 13.705)" class="tbb26ybib"/><ellipse fill="url(#i27ZkYb)" transform="rotate(-39.013 25.786 13.843)" class="qr9bfybny"/><defs><filter id="iuADjqc" width="28.188" height="11.07" x="2.031" y="10.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16200"/></filter><filter id="iywyhzb" width="11.313" height="9.712" x="17.547" y="10.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16200" stdDeviation=".125"/></filter><filter id="imqYwCo" width="10.963" height="9.362" x="17.747" y="10.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.619608 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16200"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.807843 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_16200" result="effect2_innerShadow_18_16200"/></filter><filter id="iRe4vfe" width="11.313" height="9.712" x="3.14" y="10.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16200" stdDeviation=".125"/></filter><filter id="i5sy6vc" width="10.963" height="9.362" x="3.34" y="10.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.619608 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16200"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.807843 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_16200" result="effect2_innerShadow_18_16200"/></filter><filter id="ig5P15b" width="12.197" height="10.619" x="2.698" y="10.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16200" stdDeviation=".125"/></filter><filter id="iJXe0Wb" width="12.197" height="10.619" x="17.23" y="10.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16200" stdDeviation=".125"/></filter><radialGradient id="iiip31c" cx="0" cy="0" r="1" gradientTransform="matrix(1.20312 .42187 -.81092 2.31265 1.922 10.89)" gradientUnits="userSpaceOnUse"><stop class="ge5t63bbm"/><stop offset="1" class="pj603998u"/></radialGradient><radialGradient id="ihYlbKZ" cx="0" cy="0" r="1" gradientTransform="matrix(-5.1875 -4.34374 4.4704 -5.33878 25.906 17.219)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="c8q6jec8c"/><stop offset="1" class="d_-bxnb6l"/></radialGradient><radialGradient id="ix5TCzW" cx="0" cy="0" r="1" gradientTransform="matrix(-5.1875 -4.34374 4.4704 -5.33878 11.5 17.219)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="c8q6jec8c"/><stop offset="1" class="d_-bxnb6l"/></radialGradient><radialGradient id="iJlBXAe" cx="0" cy="0" r="1" gradientTransform="rotate(-84.827 13.649 1.96)scale(3.31088 3.5043)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="gpoj6mbyn"/><stop offset="1" class="z4rme2y9a"/></radialGradient><radialGradient id="i27ZkYb" cx="0" cy="0" r="1" gradientTransform="rotate(-84.827 20.865 -5.788)scale(3.31088 3.5043)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="gpoj6mbyn"/><stop offset="1" class="z4rme2y9a"/></radialGradient><linearGradient id="iP4iOrd" x1="16" x2="16" y1="10.656" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".219" class="kt-1mjbnn"/><stop offset="1" class="ibky8_tao"/></linearGradient><linearGradient id="iwyNygb" x1="4.407" x2="13.008" y1="18.622" y2="12.652" gradientUnits="userSpaceOnUse"><stop class="ae5rshbms"/><stop offset="1" class="f5yv4cbsu"/></linearGradient><linearGradient id="iw7EhVb" x1="14.736" x2="10.966" y1="15.657" y2="15.657" gradientUnits="userSpaceOnUse"><stop class="fhkd6_ivi"/><stop offset="1" class="r8pgfcbyt"/></linearGradient><linearGradient id="iifnxOb" x1="18.939" x2="27.54" y1="18.622" y2="12.652" gradientUnits="userSpaceOnUse"><stop class="ae5rshbms"/><stop offset="1" class="f5yv4cbsu"/></linearGradient><linearGradient id="ibBVDwd" x1="29.268" x2="25.498" y1="15.657" y2="15.657" gradientUnits="userSpaceOnUse"><stop class="fhkd6_ivi"/><stop offset="1" class="r8pgfcbyt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:glasses" /></template>
<style>
.ae5rshbms {
  stop-color: var(--svg-color--53406a, #53406A);
}

.ahxwg43hk {
  fill: var(--svg-color--403457, #403457);
  d: path("M3.49 13.502a2.5 2.5 0 0 1 2.5-2.5h5.613a2.5 2.5 0 0 1 2.5 2.5v1.762a4.75 4.75 0 0 1-4.75 4.75H8.24a4.75 4.75 0 0 1-4.75-4.75z");
}

.bmwj6cbiq {
  stroke: var(--svg-color--403457, #403457);
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.49 13.502a2.5 2.5 0 0 1 2.5-2.5h5.613a2.5 2.5 0 0 1 2.5 2.5v1.762a4.75 4.75 0 0 1-4.75 4.75H8.24a4.75 4.75 0 0 1-4.75-4.75z");
}

.c8q6jec8c {
  stop-color: var(--svg-color--7fe8ff, #7FE8FF);
}

.d_-bxnb6l {
  stop-color: var(--svg-color--56c1ff, #56C1FF);
}

.d3zndlbrg {
  stroke: var(--svg-color--403457, #403457);
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.897 13.502a2.5 2.5 0 0 1 2.5-2.5h5.612a2.5 2.5 0 0 1 2.5 2.5v1.762a4.75 4.75 0 0 1-4.75 4.75h-1.112a4.75 4.75 0 0 1-4.75-4.75z");
}

.edy124b4o {
  d: path("M14.937 11.336c.22.175.602.385 1.063.385a1.75 1.75 0 0 0 1.074-.392l.01-.004l.765-.643a2.5 2.5 0 0 1 1.61-.588h9.322a1.187 1.187 0 0 1 1.065 1.714q-.061.123-.13.246l-.002.004c-.16.295-.323.594-.323.923v2.751a5.65 5.65 0 0 1-5.631 5.182h-1.113a5.65 5.65 0 0 1-5.531-4.491a5 5 0 0 1-.053-.751v-1.508a1.063 1.063 0 0 0-2.125 0v1.508q0 .383-.054.75a5.65 5.65 0 0 1-5.53 4.492H8.24a5.65 5.65 0 0 1-5.631-5.182v-2.751c0-.33-.163-.628-.324-.923l-.002-.004a7 7 0 0 1-.13-.246a1.187 1.187 0 0 1 1.065-1.714h9.322a2.5 2.5 0 0 1 1.61.588l.764.643l.009.003h.002z");
}

.f5yv4cbsu {
  stop-color: var(--svg-color--53406a, #53406A);
  stop-opacity: 0;
}

.fhkd6_ivi {
  stop-color: var(--svg-color--5d4279, #5D4279);
}

.ft5dv1b6b {
  fill: none;
}

.ge5t63bbm {
  stop-color: var(--svg-color--6c5484, #6C5484);
}

.gpoj6mbyn {
  stop-color: var(--svg-color--faffff, #FAFFFF);
  stop-opacity: 0;
}

.i_-bz1pvf {
  fill: var(--svg-color--403457, #403457);
  d: path("M17.897 13.502a2.5 2.5 0 0 1 2.5-2.5h5.612a2.5 2.5 0 0 1 2.5 2.5v1.762a4.75 4.75 0 0 1-4.75 4.75h-1.112a4.75 4.75 0 0 1-4.75-4.75z");
}

.ibky8_tao {
  stop-color: var(--svg-color--391e54, #391E54);
}

.idyuke0jn {
  d: path("M17.897 13.502a2.5 2.5 0 0 1 2.5-2.5h5.612a2.5 2.5 0 0 1 2.5 2.5v1.762a4.75 4.75 0 0 1-4.75 4.75h-1.112a4.75 4.75 0 0 1-4.75-4.75z");
}

.kt-1mjbnn {
  stop-color: var(--svg-color--57357a, #57357A);
}

.pj603998u {
  stop-color: var(--svg-color--6c5484, #6C5484);
  stop-opacity: 0;
}

.pwc08lgdd {
  d: path("M3.49 13.502a2.5 2.5 0 0 1 2.5-2.5h5.613a2.5 2.5 0 0 1 2.5 2.5v1.762a4.75 4.75 0 0 1-4.75 4.75H8.24a4.75 4.75 0 0 1-4.75-4.75z");
}

.qr9bfybny {
  cx: 25.786px;
  cy: 13.843px;
  rx: 1.352px;
  ry: 1.681px;
}

.r8pgfcbyt {
  stop-color: var(--svg-color--5d4279, #5D4279);
  stop-opacity: 0;
}

.tbb26ybib {
  cx: 11.504px;
  cy: 13.705px;
  rx: 1.352px;
  ry: 1.681px;
}

.x45cqjdej {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.03 10.573h5.533a2.957 2.957 0 0 1 2.957 2.957v1.737a5.175 5.175 0 0 1-5.175 5.175H8.25a5.175 5.175 0 0 1-5.176-5.175V13.53a2.957 2.957 0 0 1 2.958-2.957Z");
}

.yc0w_otgh {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.563 10.573h5.532a2.957 2.957 0 0 1 2.957 2.957v1.737a5.175 5.175 0 0 1-5.175 5.175h-1.096a5.175 5.175 0 0 1-5.175-5.175V13.53a2.957 2.957 0 0 1 2.957-2.957Z");
}

.z4rme2y9a {
  stop-color: var(--svg-color--faffff, #FAFFFF);
}

</style>
