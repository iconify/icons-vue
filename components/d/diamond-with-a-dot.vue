<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iS0rCce)"><rect transform="scale(-1 1)rotate(-45 15.314 36.97)" class="lkds2fbzs"/><rect fill="url(#i0aO2jd)" transform="scale(-1 1)rotate(-45 15.314 36.97)" class="w3iaxgb-f"/></g><g filter="url(#ijT5Krc)"><rect transform="scale(-1 1)rotate(-45 11.314 27.314)" class="lkds2fbzs"/><rect fill="url(#i0aO2jd)" transform="scale(-1 1)rotate(-45 11.314 27.314)" class="w3iaxgb-f"/></g><rect fill="url(#id5NdRn)" transform="scale(-1 1)rotate(-45 11.314 27.314)" class="w3iaxgb-f"/><rect fill="url(#idsOeSw)" transform="scale(-1 1)rotate(-45 11.314 27.314)" class="w3iaxgb-f"/><g filter="url(#iFlyVac)"><rect transform="scale(-1 1)rotate(-45 5.657 40.97)" class="lkds2fbzs"/><rect fill="url(#i4PmNHX)" transform="scale(-1 1)rotate(-45 5.657 40.97)" class="w3iaxgb-f"/></g><g filter="url(#iaLvVIb)"><rect transform="scale(-1 1)rotate(-45 1.657 31.314)" class="lkds2fbzs"/><rect fill="url(#ircbuFY)" transform="scale(-1 1)rotate(-45 1.657 31.314)" class="w3iaxgb-f"/></g><rect fill="url(#iThAbMe)" transform="scale(-1 1)rotate(-45 1.657 31.314)" class="w3iaxgb-f"/><rect fill="url(#idsOeSw)" transform="scale(-1 1)rotate(-45 1.657 31.314)" class="w3iaxgb-f"/><g filter="url(#i5FJHOc)"><circle fill="url(#iV6IhTc)" class="z9shncc0q"/><circle fill="url(#iVjPRwe)" class="z9shncc0q"/></g><defs><linearGradient id="i0aO2jd" x1="4" x2="3.87" y1="0" y2="2.877" gradientUnits="userSpaceOnUse"><stop class="t35gc2b2b"/><stop offset="1" class="n2i1i6b1b"/></linearGradient><linearGradient id="id5NdRn" x1="-.904" x2="1.461" y1="3.981" y2="3.871" gradientUnits="userSpaceOnUse"><stop offset=".192" class="rf3i29b2p"/><stop offset="1" class="y7daw87_c"/></linearGradient><linearGradient id="idsOeSw" x1="9.539" x2="7.118" y1="3.825" y2="3.998" gradientUnits="userSpaceOnUse"><stop class="ws-jvxb_h"/><stop offset="1" class="m8ciho6ea"/></linearGradient><linearGradient id="i4PmNHX" x1="4" x2="4.18" y1="0" y2="3.231" gradientUnits="userSpaceOnUse"><stop offset=".176" class="t35gc2b2b"/><stop offset="1" class="n2i1i6b1b"/></linearGradient><linearGradient id="ircbuFY" x1="3.825" x2="3.825" y1=".491" y2="3.231" gradientUnits="userSpaceOnUse"><stop offset=".03" class="t35gc2b2b"/><stop offset="1" class="n2i1i6b1b"/></linearGradient><linearGradient id="iThAbMe" x1="-.639" x2="1.461" y1="3.938" y2="3.871" gradientUnits="userSpaceOnUse"><stop offset=".192" class="rf3i29b2p"/><stop offset="1" class="y7daw87_c"/></linearGradient><filter id="iS0rCce" width="11.322" height="11.322" x="11.089" y="15.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.737255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2928"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.560784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2928" result="effect2_innerShadow_18590_2928"/></filter><filter id="ijT5Krc" width="11.322" height="11.322" x="5.432" y="9.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.737255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2928"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.560784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2928" result="effect2_innerShadow_18590_2928"/></filter><filter id="iFlyVac" width="11.322" height="11.322" x="16.746" y="9.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.737255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2928"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.560784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2928" result="effect2_innerShadow_18590_2928"/></filter><filter id="iaLvVIb" width="11.322" height="11.322" x="11.089" y="3.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.737255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2928"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.560784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2928" result="effect2_innerShadow_18590_2928"/></filter><filter id="i5FJHOc" width="5" height="5" x="13.25" y="13.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.611765 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18590_2928"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18590_2928" result="shape"/></filter><radialGradient id="iV6IhTc" cx="0" cy="0" r="1" gradientTransform="rotate(144.705 5.88 10.435)scale(2.56047)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="il9esbc0i"/><stop offset="1" class="s-kvklbhr"/></radialGradient><radialGradient id="iVjPRwe" cx="0" cy="0" r="1" gradientTransform="rotate(-90 16.501 .501)scale(3.00285)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="c4yxllshi"/><stop offset="1" class="tzmyqz_qh"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:diamond-with-a-dot" /></template>
<style>
.c4yxllshi {
  stop-color: var(--svg-color--44b5ff, #44B5FF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.il9esbc0i {
  stop-color: var(--svg-color--74c9ff, #74C9FF);
}

.lkds2fbzs {
  width: 8px;
  height: 8px;
  fill: var(--svg-color--5db4ff, #5DB4FF);
  rx: 1.8px;
}

.m8ciho6ea {
  stop-color: var(--svg-color--84d0ff, #84D0FF);
  stop-opacity: 0;
}

.n2i1i6b1b {
  stop-color: var(--svg-color--5eb5ff, #5EB5FF);
  stop-opacity: 0;
}

.rf3i29b2p {
  stop-color: var(--svg-color--0f7bff, #0F7BFF);
}

.s-kvklbhr {
  stop-color: var(--svg-color--4294ff, #4294FF);
}

.t35gc2b2b {
  stop-color: var(--svg-color--71dbff, #71DBFF);
}

.tzmyqz_qh {
  stop-color: var(--svg-color--44b5ff, #44B5FF);
}

.w3iaxgb-f {
  width: 8px;
  height: 8px;
  rx: 1.8px;
}

.ws-jvxb_h {
  stop-color: var(--svg-color--84d0ff, #84D0FF);
}

.y7daw87_c {
  stop-color: var(--svg-color--309bff, #309BFF);
  stop-opacity: 0;
}

.z9shncc0q {
  cx: 16px;
  cy: 16px;
  r: 2px;
}

</style>
