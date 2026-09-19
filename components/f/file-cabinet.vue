<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iB7U8Ic)"><rect fill="url(#iXO4e7b)" class="ru6iejbko"/></g><g filter="url(#ia4DQKP)"><rect fill="url(#iYtGELc)" class="yaqim-c3k"/></g><g filter="url(#i4aZgyb)"><rect fill="url(#iYtGELc)" class="yaqim-c3k"/></g><g filter="url(#ilcVgSc)"><rect class="r3x1dsbid"/></g><g filter="url(#irVEfYZ)"><rect class="zjhpz-6ti"/><rect fill="url(#i3x1BIc)" class="fa9r4abau"/></g><g filter="url(#il2xVke)"><path fill="url(#i4cRR2d)" clip-rule="evenodd" class="f8_p_x71q"/></g><g filter="url(#ieml2ad)"><rect fill="url(#isf24lc)" class="njqf4bzoz"/></g><g filter="url(#iZg3BFd)"><rect class="mv4_c4b4g"/></g><g filter="url(#iAIAv5d)"><rect class="ikr109bob"/><rect fill="url(#ix6P6Td)" class="o7natqbrl"/></g><rect fill="url(#iKoay4c)" class="ikou51bjl"/><g filter="url(#iHojm8d)"><path fill="url(#i30S06c)" clip-rule="evenodd" class="bcrwwemoy"/></g><g filter="url(#iz2MMbe)" class="ji_0vbnnl"><rect stroke="url(#igUsvWb)" class="z92u_ccxl"/><rect stroke="url(#iasPUje)" class="z92u_ccxl"/></g><g filter="url(#iktRmce)" class="ji_0vbnnl"><rect stroke="url(#iVup6Ed)" class="to1o2ub5g"/><rect stroke="url(#iJlbPzD)" class="to1o2ub5g"/></g><rect fill="url(#iYKEfyi)" class="gmcgqnnjk"/><defs><filter id="iB7U8Ic" width="18.3" height="28.144" x="6.823" y="1.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.12549 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23414"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.403922 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23414" result="effect2_innerShadow_18_23414"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.247059 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23414" result="effect3_innerShadow_18_23414"/></filter><filter id="ia4DQKP" width="16.094" height="12.731" x="7.926" y="2.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.176471 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23414"/></filter><filter id="i4aZgyb" width="16.894" height="13.381" x="7.276" y="2.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.141176 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_23414"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_23414" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_23414"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.52549 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23414" result="effect3_innerShadow_18_23414"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.176471 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_23414" result="effect4_innerShadow_18_23414"/></filter><filter id="ilcVgSc" width="8.195" height="2.625" x="11.863" y="10.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23414" stdDeviation=".25"/></filter><filter id="irVEfYZ" width="7.445" height="2.125" x="12.113" y="10.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".6"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.352941 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23414"/></filter><filter id="il2xVke" width="7.695" height="4.709" x="12.013" y="4.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.247059 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_23414"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_23414" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.294118 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_23414"/></filter><filter id="ieml2ad" width="16.894" height="13.381" x="7.276" y="16.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.141176 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_23414"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_23414" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_23414"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.52549 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23414" result="effect3_innerShadow_18_23414"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.176471 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_23414" result="effect4_innerShadow_18_23414"/></filter><filter id="iZg3BFd" width="8.195" height="2.625" x="11.863" y="23.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23414" stdDeviation=".25"/></filter><filter id="iAIAv5d" width="7.445" height="2.125" x="12.113" y="23.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".6"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.352941 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23414"/></filter><filter id="iHojm8d" width="7.695" height="4.709" x="12.013" y="18.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.247059 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_23414"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_23414" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.294118 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_23414"/></filter><filter id="iz2MMbe" width="7.058" height="3.909" x="12.471" y="5.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23414" stdDeviation=".075"/></filter><filter id="iktRmce" width="7.058" height="3.909" x="12.471" y="18.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23414" stdDeviation=".075"/></filter><linearGradient id="iXO4e7b" x1="15.973" x2="15.973" y1="2.078" y2="29.922" gradientUnits="userSpaceOnUse"><stop class="ql4r54egv"/><stop offset="1" class="a6lyw0sit"/></linearGradient><linearGradient id="iYtGELc" x1="15.973" x2="15.973" y1="3.047" y2="15.578" gradientUnits="userSpaceOnUse"><stop class="u-6sgsaox"/><stop offset="1" class="cgvg0acnd"/></linearGradient><linearGradient id="i4cRR2d" x1="15.961" x2="15.961" y1="5.016" y2="9.125" gradientUnits="userSpaceOnUse"><stop class="pvv9lqo2b"/><stop offset="1" class="eibd44bbj"/></linearGradient><linearGradient id="isf24lc" x1="15.973" x2="15.973" y1="16.422" y2="28.953" gradientUnits="userSpaceOnUse"><stop class="u-6sgsaox"/><stop offset="1" class="cgvg0acnd"/></linearGradient><linearGradient id="i30S06c" x1="15.961" x2="15.961" y1="18.391" y2="22.5" gradientUnits="userSpaceOnUse"><stop class="pvv9lqo2b"/><stop offset="1" class="eibd44bbj"/></linearGradient><linearGradient id="igUsvWb" x1="19.254" x2="16.93" y1="5.681" y2="7.589" gradientUnits="userSpaceOnUse"><stop offset=".123" class="agi6d1ogq"/><stop offset="1" class="gv_facb_z"/></linearGradient><linearGradient id="iasPUje" x1="12.973" x2="14.976" y1="8.516" y2="7.344" gradientUnits="userSpaceOnUse"><stop offset=".123" class="agi6d1ogq"/><stop offset="1" class="gv_facb_z"/></linearGradient><linearGradient id="iVup6Ed" x1="19.254" x2="16.93" y1="19.103" y2="21.011" gradientUnits="userSpaceOnUse"><stop offset=".123" class="agi6d1ogq"/><stop offset="1" class="gv_facb_z"/></linearGradient><linearGradient id="iJlbPzD" x1="12.973" x2="14.976" y1="21.938" y2="20.766" gradientUnits="userSpaceOnUse"><stop offset=".123" class="agi6d1ogq"/><stop offset="1" class="gv_facb_z"/></linearGradient><radialGradient id="i3x1BIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23438 -.48437 .40124 1.02253 12.566 11.844)" gradientUnits="userSpaceOnUse"><stop class="l41jpynop"/><stop offset="1" class="x_9ncezan"/></radialGradient><radialGradient id="ix6P6Td" cx="0" cy="0" r="1" gradientTransform="matrix(1.23438 -.48437 .40124 1.02253 12.566 25.219)" gradientUnits="userSpaceOnUse"><stop class="l41jpynop"/><stop offset="1" class="x_9ncezan"/></radialGradient><radialGradient id="iKoay4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.27344 -2.82422 0 15.96 20.445)" gradientUnits="userSpaceOnUse"><stop class="dv2bmqwom"/><stop offset="1" class="vfwwryj-b"/></radialGradient><radialGradient id="iYKEfyi" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.27344 -2.82422 0 15.96 7.07)" gradientUnits="userSpaceOnUse"><stop class="dv2bmqwom"/><stop offset="1" class="vfwwryj-b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:file-cabinet" /></template>
<style>
.a6lyw0sit {
  stop-color: var(--svg-color--41354f, #41354F);
}

.agi6d1ogq {
  stop-color: var(--svg-color--a187d4, #A187D4);
}

.bcrwwemoy {
  fill-rule: evenodd;
  d: path("M13.563 18.39a1.2 1.2 0 0 0-1.2 1.2v1.71a1.2 1.2 0 0 0 1.2 1.2h4.796a1.2 1.2 0 0 0 1.2-1.2v-1.71a1.2 1.2 0 0 0-1.2-1.2zm-.026.782a.4.4 0 0 0-.4.4v1.747c0 .22.179.4.4.4h4.848a.4.4 0 0 0 .4-.4v-1.747a.4.4 0 0 0-.4-.4z");
}

.cgvg0acnd {
  stop-color: var(--svg-color--654986, #654986);
}

.dv2bmqwom {
  stop-color: var(--svg-color--dbd1e8, #DBD1E8);
}

.eibd44bbj {
  stop-color: var(--svg-color--8466be, #8466BE);
}

.f8_p_x71q {
  fill-rule: evenodd;
  d: path("M13.563 5.016a1.2 1.2 0 0 0-1.2 1.2v1.709a1.2 1.2 0 0 0 1.2 1.2h4.796a1.2 1.2 0 0 0 1.2-1.2v-1.71a1.2 1.2 0 0 0-1.2-1.2zm-.026.78a.4.4 0 0 0-.4.4v1.748c0 .22.179.4.4.4h4.848a.4.4 0 0 0 .4-.4V6.197a.4.4 0 0 0-.4-.4z");
}

.fa9r4abau {
  width: 7.195px;
  height: 1.625px;
  x: 12.363px;
  y: 10.547px;
  rx: 0.813px;
}

.ft5dv1b6b {
  fill: none;
}

.gmcgqnnjk {
  width: 5.648px;
  height: 2.547px;
  x: 13.137px;
  y: 5.797px;
  rx: 0.4px;
}

.gv_facb_z {
  stop-color: var(--svg-color--a187d4, #A187D4);
  stop-opacity: 0;
}

.ikou51bjl {
  width: 5.648px;
  height: 2.547px;
  x: 13.137px;
  y: 19.172px;
  rx: 0.4px;
}

.ikr109bob {
  width: 7.195px;
  height: 1.625px;
  x: 12.363px;
  y: 23.922px;
  fill: var(--svg-color--906dcf, #906DCF);
  rx: 0.813px;
}

.ji_0vbnnl {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  opacity: var(--svg-opacity--0-6, 0.6);
}

.l41jpynop {
  stop-color: var(--svg-color--9d7fd8, #9D7FD8);
}

.mv4_c4b4g {
  width: 7.195px;
  height: 1.625px;
  x: 12.363px;
  y: 23.922px;
  fill: var(--svg-color--664e8b, #664E8B);
  rx: 0.813px;
}

.njqf4bzoz {
  width: 16.094px;
  height: 12.531px;
  x: 7.926px;
  y: 16.422px;
  rx: 1px;
}

.o7natqbrl {
  width: 7.195px;
  height: 1.625px;
  x: 12.363px;
  y: 23.922px;
  rx: 0.813px;
}

.pvv9lqo2b {
  stop-color: var(--svg-color--8b6dc5, #8B6DC5);
}

.ql4r54egv {
  stop-color: var(--svg-color--55406c, #55406C);
}

.r3x1dsbid {
  width: 7.195px;
  height: 1.625px;
  x: 12.363px;
  y: 10.547px;
  fill: var(--svg-color--664e8b, #664E8B);
  rx: 0.813px;
}

.ru6iejbko {
  width: 18px;
  height: 27.844px;
  x: 6.973px;
  y: 2.078px;
  rx: 1.4px;
}

.to1o2ub5g {
  width: 6.508px;
  height: 3.359px;
  x: 12.746px;
  y: 18.766px;
  rx: 0.8px;
}

.u-6sgsaox {
  stop-color: var(--svg-color--6e6bae, #6E6BAE);
}

.vfwwryj-b {
  stop-color: var(--svg-color--d2c2e5, #D2C2E5);
}

.x_9ncezan {
  stop-color: var(--svg-color--9d7fd8, #9D7FD8);
  stop-opacity: 0;
}

.yaqim-c3k {
  width: 16.094px;
  height: 12.531px;
  x: 7.926px;
  y: 3.047px;
  rx: 1px;
}

.z92u_ccxl {
  width: 6.508px;
  height: 3.359px;
  x: 12.746px;
  y: 5.344px;
  rx: 0.8px;
}

.zjhpz-6ti {
  width: 7.195px;
  height: 1.625px;
  x: 12.363px;
  y: 10.547px;
  fill: var(--svg-color--906dcf, #906DCF);
  rx: 0.813px;
}

</style>
