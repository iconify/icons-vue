<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZteMEv)" class="h-y5mybxe"/><path fill="url(#ieFFkMc)" class="jin-m3n_n"/><path fill="url(#iFHbp1c)" class="jin-m3n_n"/><path fill="url(#iaHLErd)" class="nn-t19qzp"/><path fill="url(#ie53Sfc)" class="nn-t19qzp"/><g filter="url(#icgUspb)"><path fill="url(#iAqNejc)" clip-rule="evenodd" class="ygi3i0bgp"/></g><path fill="url(#isgVWpK)" class="ncqa0sm6y"/><path fill="url(#i7YgWsb)" class="v8p1eh8av"/><g filter="url(#itNA4Td)"><rect fill="url(#igAq0ac)" class="mt2pn1beg"/></g><g filter="url(#iHsC7Pc)"><path class="d58lxcbyz"/></g><g filter="url(#ik1Jk2b)"><path fill="url(#iXV3Qxi)" class="yn2w0xbak"/><path fill="url(#iEAgCkb)" class="yn2w0xbak"/></g><g filter="url(#iRvMEDb)"><path fill="url(#iG7rqIe)" class="oaor_gi7t"/><path fill="url(#ixZV7gW)" class="oaor_gi7t"/></g><g filter="url(#iJhUcLe)"><path fill="url(#iDWWFIc)" class="mdfrotwbe"/><path fill="url(#iyyI41N)" class="mdfrotwbe"/></g><g filter="url(#impy0Ne)"><path fill="url(#igt4e5d)" class="sct4pp6kx"/></g><g filter="url(#iYfXezd)"><path stroke="url(#ib2M69F)" class="t9wty9bcy"/></g><defs><linearGradient id="iZteMEv" x1="16.035" x2="16.035" y1="5.024" y2="6.024" gradientUnits="userSpaceOnUse"><stop class="tmioq6epx"/><stop offset="1" class="ped_jgbyi"/></linearGradient><linearGradient id="ieFFkMc" x1="13.035" x2="14.035" y1="5.002" y2="5.002" gradientUnits="userSpaceOnUse"><stop class="khzsm9bwn"/><stop offset=".206" class="a-d1kbbno"/><stop offset=".831" class="a-d1kbbno"/><stop offset="1" class="uwaoh2bgw"/></linearGradient><linearGradient id="iFHbp1c" x1="14.035" x2="14.035" y1="6.214" y2="4.793" gradientUnits="userSpaceOnUse"><stop class="qoafqfnbp"/><stop offset="1" class="rhu_uib1p"/></linearGradient><linearGradient id="iaHLErd" x1="18.035" x2="19.035" y1="5.002" y2="5.002" gradientUnits="userSpaceOnUse"><stop class="khzsm9bwn"/><stop offset=".206" class="a-d1kbbno"/><stop offset=".831" class="a-d1kbbno"/><stop offset="1" class="uwaoh2bgw"/></linearGradient><linearGradient id="ie53Sfc" x1="19.035" x2="19.035" y1="6.214" y2="4.793" gradientUnits="userSpaceOnUse"><stop class="qoafqfnbp"/><stop offset="1" class="rhu_uib1p"/></linearGradient><linearGradient id="iAqNejc" x1="16.035" x2="16.035" y1="2.002" y2="4.002" gradientUnits="userSpaceOnUse"><stop class="wzhmsobyt"/><stop offset="1" class="ecp-thbxv"/></linearGradient><linearGradient id="iXV3Qxi" x1="11.039" x2="11.039" y1="8.972" y2="26.559" gradientUnits="userSpaceOnUse"><stop class="t4n20cbeu"/><stop offset="1" class="mhm8sfb1r"/></linearGradient><linearGradient id="iG7rqIe" x1="16.039" x2="16.039" y1="8.972" y2="26.559" gradientUnits="userSpaceOnUse"><stop class="t4n20cbeu"/><stop offset="1" class="mhm8sfb1r"/></linearGradient><linearGradient id="iDWWFIc" x1="21.039" x2="21.039" y1="8.972" y2="26.559" gradientUnits="userSpaceOnUse"><stop class="t4n20cbeu"/><stop offset="1" class="mhm8sfb1r"/></linearGradient><linearGradient id="igt4e5d" x1="15.873" x2="19.872" y1="8.074" y2="12.074" gradientUnits="userSpaceOnUse"><stop class="bjzrswbib"/><stop offset="1" class="vvl9-sbta"/></linearGradient><linearGradient id="ib2M69F" x1="23.826" x2="22.28" y1="6.518" y2="8.884" gradientUnits="userSpaceOnUse"><stop class="czxim4blq"/><stop offset="1" class="kxwpilbfz"/></linearGradient><filter id="icgUspb" width="6.3" height="2.15" x="12.885" y="1.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.180392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13192"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.168627 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13192" result="effect2_innerShadow_18_13192"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.34902 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_13192" result="effect3_innerShadow_18_13192"/></filter><filter id="itNA4Td" width="18.23" height="23.242" x="7.07" y="5.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.317647 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13192"/></filter><filter id="iHsC7Pc" width="7.228" height="7.235" x="13.929" y="6.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13192" stdDeviation=".25"/></filter><filter id="ik1Jk2b" width="3" height="20" x="9.435" y="7.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.372549 0 0 0 0 0.701961 0 0 0 0.5 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13192"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13192" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.396078 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13192"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.972549 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_13192" result="effect3_innerShadow_18_13192"/></filter><filter id="iRvMEDb" width="3" height="20" x="14.435" y="7.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.372549 0 0 0 0 0.701961 0 0 0 0.5 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13192"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13192" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.396078 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13192"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.972549 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_13192" result="effect3_innerShadow_18_13192"/></filter><filter id="iJhUcLe" width="3" height="20" x="19.435" y="7.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.372549 0 0 0 0 0.701961 0 0 0 0.5 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13192"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13192" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.396078 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13192"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.972549 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_13192" result="effect3_innerShadow_18_13192"/></filter><filter id="impy0Ne" width="6.813" height="6.57" x="14.455" y="6.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.945098 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13192"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13192" result="effect2_innerShadow_18_13192"/></filter><filter id="iYfXezd" width="13.663" height="4.986" x="11.488" y="5.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13192" stdDeviation=".2"/></filter><radialGradient id="isgVWpK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28144 1.86841 0 12.035 30.1)" gradientUnits="userSpaceOnUse"><stop class="o6fa8snez"/><stop offset="1" class="a5mf7sbrz"/></radialGradient><radialGradient id="i7YgWsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28144 1.86841 0 20.035 30.1)" gradientUnits="userSpaceOnUse"><stop class="o6fa8snez"/><stop offset="1" class="a5mf7sbrz"/></radialGradient><radialGradient id="igAq0ac" cx="0" cy="0" r="1" gradientTransform="rotate(119.982 8.234 10.8)scale(25.0913 19.6101)" gradientUnits="userSpaceOnUse"><stop class="lvxm8oxke"/><stop offset="1" class="b0bir5hbf"/></radialGradient><radialGradient id="iEAgCkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.82806 1.32522 -1.53924 -.96179 12.035 7.748)" gradientUnits="userSpaceOnUse"><stop class="mcmlzyb0f"/><stop offset="1" class="zmpxmkm4o"/></radialGradient><radialGradient id="ixZV7gW" cx="0" cy="0" r="1" gradientTransform="matrix(-.82806 1.32522 -1.53924 -.96179 17.035 7.748)" gradientUnits="userSpaceOnUse"><stop class="mcmlzyb0f"/><stop offset="1" class="zmpxmkm4o"/></radialGradient><radialGradient id="iyyI41N" cx="0" cy="0" r="1" gradientTransform="matrix(-.82806 1.32522 -1.53924 -.96179 22.035 7.748)" gradientUnits="userSpaceOnUse"><stop class="mcmlzyb0f"/><stop offset="1" class="zmpxmkm4o"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:luggage" /></template>
<style>
.a-d1kbbno {
  stop-color: var(--svg-color--a5a6b3, #A5A6B3);
}

.a5mf7sbrz {
  stop-color: var(--svg-color--27262c, #27262C);
}

.b0bir5hbf {
  stop-color: var(--svg-color--2b62b7, #2B62B7);
}

.bjzrswbib {
  stop-color: var(--svg-color--d0c5d6, #D0C5D6);
}

.czxim4blq {
  stop-color: var(--svg-color--5aabf7, #5AABF7);
}

.d58lxcbyz {
  fill: var(--svg-color--3375ca, #3375CA);
  d: path("m20.49 11.53l-1.69 1.69a.575.575 0 0 1-.826 0l-3.37-3.37a.575.575 0 0 1 0-.826l1.69-1.69a.575.575 0 0 1 .826 0l3.37 3.37a.59.59 0 0 1 0 .825");
}

.ecp-thbxv {
  stop-color: var(--svg-color--3b3641, #3B3641);
}

.ft5dv1b6b {
  fill: none;
}

.h-y5mybxe {
  d: path("M18.313 5.024h-4.547a.41.41 0 0 0-.401.415v.171a.41.41 0 0 0 .4.414h4.538a.41.41 0 0 0 .401-.414v-.17a.395.395 0 0 0-.39-.415");
}

.jin-m3n_n {
  d: path("M14.035 3.502h-1v3h1z");
}

.khzsm9bwn {
  stop-color: var(--svg-color--6c7481, #6C7481);
}

.kxwpilbfz {
  stop-color: var(--svg-color--5aabf7, #5AABF7);
  stop-opacity: 0;
}

.lvxm8oxke {
  stop-color: var(--svg-color--469aeb, #469AEB);
}

.mcmlzyb0f {
  stop-color: var(--svg-color--6bfbff, #6BFBFF);
}

.mdfrotwbe {
  d: path("M21.035 27c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1s1 .45 1 1v17c0 .55-.44 1-1 1");
}

.mhm8sfb1r {
  stop-color: var(--svg-color--48a7f0, #48A7F0);
}

.mt2pn1beg {
  width: 17.93px;
  height: 22.942px;
  x: 7.07px;
  y: 6.024px;
  rx: 3.25px;
}

.ncqa0sm6y {
  d: path("M12.035 30.1c-.55 0-1-.45-1-1V28h2v1.1c0 .55-.44 1-1 1");
}

.nn-t19qzp {
  d: path("M19.035 3.502h-1v3h1z");
}

.o6fa8snez {
  stop-color: var(--svg-color--432959, #432959);
}

.oaor_gi7t {
  d: path("M16.035 27c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1s1 .45 1 1v17c0 .55-.44 1-1 1");
}

.ped_jgbyi {
  stop-color: var(--svg-color--383643, #383643);
}

.qoafqfnbp {
  stop-color: var(--svg-color--666b75, #666B75);
}

.rhu_uib1p {
  stop-color: var(--svg-color--666b75, #666B75);
  stop-opacity: 0;
}

.sct4pp6kx {
  d: path("m20.845 11.308l-1.74 1.74c-.24.24-.62.24-.85 0l-3.47-3.47a.59.59 0 0 1 0-.85l1.74-1.74c.24-.24.62-.24.85 0l3.47 3.47c.23.23.23.61 0 .85");
}

.t4n20cbeu {
  stop-color: var(--svg-color--5fdef9, #5FDEF9);
}

.t9wty9bcy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.088 6.518h9.446c.838 0 1.638.348 2.208.96v0c.52.56.81 1.294.81 2.057v.769");
}

.tmioq6epx {
  stop-color: var(--svg-color--5c4872, #5C4872);
}

.uwaoh2bgw {
  stop-color: var(--svg-color--bfc0ca, #BFC0CA);
}

.v8p1eh8av {
  d: path("M20.035 30.1c-.55 0-1-.45-1-1V28h2v1.1c0 .55-.44 1-1 1");
}

.vvl9-sbta {
  stop-color: var(--svg-color--cec3d5, #CEC3D5);
}

.wzhmsobyt {
  stop-color: var(--svg-color--5a446f, #5A446F);
}

.ygi3i0bgp {
  fill-rule: evenodd;
  d: path("M13.035 3.201c0-.655.527-1.2 1.19-1.2h3.62c.662 0 1.19.545 1.19 1.2v.8h-1v-.8c0-.115-.093-.2-.19-.2h-3.62a.196.196 0 0 0-.19.2v.8h-1z");
}

.yn2w0xbak {
  d: path("M11.035 27c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1s1 .45 1 1v17c0 .55-.44 1-1 1");
}

.zmpxmkm4o {
  stop-color: var(--svg-color--6bfbff, #6BFBFF);
  stop-opacity: 0;
}

</style>
