<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="g76fzfbpt"/><path fill="url(#iXYj2ke)" class="lcxfwjddl"/><path fill="url(#iIT7bjc)" class="lcxfwjddl"/><path class="qed7hrbbw"/><path fill="url(#ieGv8vb)" class="zfjnozp9d"/><path fill="url(#i5rZaGb)" class="zfjnozp9d"/><g filter="url(#iyGAste)"><path fill="url(#iJ0pjVW)" class="ep9fhkbxm"/><path fill="url(#ifCKSEc)" class="ep9fhkbxm"/><path fill="url(#iHRdmod)" class="ep9fhkbxm"/></g><rect fill="url(#i5CGe7b)" class="rxd6akrtz"/><rect fill="url(#ih7Aadd)" class="rxd6akrtz"/><rect fill="url(#iFrQLBb)" class="rxd6akrtz"/><rect fill="url(#iLS6XFb)" class="rxd6akrtz"/><g filter="url(#iifwuze)"><path fill="url(#ikofWTc)" class="ig8bfkm5c"/></g><g filter="url(#iifwuze)"><path fill="url(#ikofWTc)" class="ig8bfkm5c"/></g><path fill="url(#iW5cMXL)" class="ig8bfkm5c"/><g filter="url(#iGm55md)"><path stroke="url(#icFPUsd)" class="nt_r8bbqc"/></g><g filter="url(#iDm12hb)"><path stroke="url(#i0AbsBd)" class="azf3a7i7s"/></g><defs><linearGradient id="iXYj2ke" x1="10.803" x2="11.51" y1="4.375" y2="4.375" gradientUnits="userSpaceOnUse"><stop class="d534-5bfm"/><stop offset="1" class="jllgvmbaf"/></linearGradient><linearGradient id="ieGv8vb" x1="19.881" x2="20.588" y1="4.375" y2="4.375" gradientUnits="userSpaceOnUse"><stop class="d534-5bfm"/><stop offset="1" class="jllgvmbaf"/></linearGradient><linearGradient id="iJ0pjVW" x1="12.522" x2="18.772" y1="10.594" y2="10.594" gradientUnits="userSpaceOnUse"><stop class="vcsbv4lhy"/><stop offset="1" class="onlfnjfio"/></linearGradient><linearGradient id="ifCKSEc" x1="10.772" x2="15.397" y1="10.063" y2="9.406" gradientUnits="userSpaceOnUse"><stop class="r13wun83b"/><stop offset="1" class="fmpcfgvjg"/></linearGradient><linearGradient id="iHRdmod" x1="21.178" x2="19.272" y1="9.906" y2="9.688" gradientUnits="userSpaceOnUse"><stop class="f1o5j0jjz"/><stop offset="1" class="u8jpe-blw"/></linearGradient><linearGradient id="i5CGe7b" x1="12.178" x2="18.959" y1="12.031" y2="12.031" gradientUnits="userSpaceOnUse"><stop class="s1etbibra"/><stop offset="1" class="emuhwmbsl"/></linearGradient><linearGradient id="iFrQLBb" x1="16.049" x2="16.049" y1="11.031" y2="11.129" gradientUnits="userSpaceOnUse"><stop class="fno5-kksh"/><stop offset="1" class="qm-53ybll"/></linearGradient><linearGradient id="iLS6XFb" x1="16.049" x2="16.049" y1="12.094" y2="11.852" gradientUnits="userSpaceOnUse"><stop class="fno5-kksh"/><stop offset="1" class="qm-53ybll"/></linearGradient><linearGradient id="ikofWTc" x1="22.991" x2="14.803" y1="19.125" y2="21.438" gradientUnits="userSpaceOnUse"><stop class="gbjj51b6f"/><stop offset="1" class="i2p8-ru8p"/></linearGradient><linearGradient id="iW5cMXL" x1="6.366" x2="16.428" y1="20.25" y2="22.813" gradientUnits="userSpaceOnUse"><stop offset=".145" class="cjqy9l0-u"/><stop offset="1" class="mbykkwb0i"/></linearGradient><linearGradient id="icFPUsd" x1="15.741" x2="13.897" y1="6.688" y2="4.906" gradientUnits="userSpaceOnUse"><stop class="i4dxeu_xd"/><stop offset="1" class="h1526gb7z"/></linearGradient><filter id="iyGAste" width="12.149" height="6.959" x="9.974" y="4.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.427451 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16638"/></filter><filter id="iifwuze" width="24.799" height="18.688" x="3.411" y="11.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.627451 0 0 0 0 0.917647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.596078 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_16638" result="effect2_innerShadow_18_16638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.34902 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_16638" result="effect3_innerShadow_18_16638"/></filter><filter id="iGm55md" width="2.649" height="2.719" x="13.51" y="4.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16638" stdDeviation=".075"/></filter><filter id="iDm12hb" width="4.816" height="1.3" x="16.966" y="4.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16638" stdDeviation=".075"/></filter><radialGradient id="iIT7bjc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.117 8.325 -3.872)scale(2.76205 .39166)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="v6d_utbln"/><stop offset="1" class="kjmhz0udv"/></radialGradient><radialGradient id="i5rZaGb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.117 12.864 -8.482)scale(2.76205 .39166)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="v6d_utbln"/><stop offset="1" class="kjmhz0udv"/></radialGradient><radialGradient id="ih7Aadd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .32813 -6.11719 0 19.116 11.031)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="ql46xacuy"/><stop offset="1" class="b-40u0beu"/></radialGradient><radialGradient id="i0AbsBd" cx="0" cy="0" r="1" gradientTransform="rotate(178.534 10.824 2.569)scale(3.97005 1.39234)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="qp5ue84mr"/><stop offset=".755" class="rvjn3c-hj"/><stop offset="1" class="qp5ue84mr"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dress" /></template>
<style>
.azf3a7i7s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.24 5.336c.162-.25.66-.75 1.36-.75h2.117c.167.005.558.06.79.234");
}

.b-40u0beu {
  stop-color: var(--svg-color--673c6a, #673C6A);
  stop-opacity: 0;
}

.cjqy9l0-u {
  stop-color: var(--svg-color--3e639c, #3E639C);
}

.d534-5bfm {
  stop-color: var(--svg-color--2a5fa6, #2A5FA6);
}

.emuhwmbsl {
  stop-color: var(--svg-color--642f67, #642F67);
}

.ep9fhkbxm {
  d: path("m10.006 5.634l1.25 5.284a.15.15 0 0 0 .149.11h9.277a.15.15 0 0 0 .145-.115l1.265-5.28a1.15 1.15 0 0 0-1.12-1.414H19.11a3 3 0 0 0-2.647 1.588l-.37.694a.05.05 0 0 1-.088 0l-.37-.694a3 3 0 0 0-2.647-1.588h-1.863a1.15 1.15 0 0 0-1.12 1.415");
}

.f1o5j0jjz {
  stop-color: var(--svg-color--3e8ded, #3E8DED);
}

.fmpcfgvjg {
  stop-color: var(--svg-color--2a6ddd, #2A6DDD);
  stop-opacity: 0;
}

.fno5-kksh {
  stop-color: var(--svg-color--331b3b, #331B3B);
}

.ft5dv1b6b {
  fill: none;
}

.g76fzfbpt {
  fill: var(--svg-color--2d83cb, #2D83CB);
  d: path("M10.908 2.494a.4.4 0 0 1 .4-.4h.403a.4.4 0 0 1 .4.4v2.123h-1.203z");
}

.gbjj51b6f {
  stop-color: var(--svg-color--59a4fe, #59A4FE);
}

.h1526gb7z {
  stop-color: var(--svg-color--5e93eb, #5E93EB);
  stop-opacity: 0;
}

.i2p8-ru8p {
  stop-color: var(--svg-color--2b7ee5, #2B7EE5);
}

.i4dxeu_xd {
  stop-color: var(--svg-color--5e93eb, #5E93EB);
}

.ig8bfkm5c {
  d: path("M11.36 12.087L4.4 26.03c-.44.719-.896 2.14.142 3.18c1.188 1.188 2.573.67 3.297 0q.25-.232.432-.391c.25-.221.681-.155.901.097c.44.504 1.117 1.052 1.869 1.052c1.04 0 1.585-.55 1.838-.807l.003-.003l.278-.293c.253-.266.61-.273.87-.015l.512.505c.275.294.779.59 1.518.59c.74 0 1.239-.296 1.514-.59l.51-.505c.262-.258.623-.25.876.015l.279.293l.003.003c.253.256.797.807 1.837.807c.752 0 1.43-.548 1.87-1.052c.219-.252.65-.318.9-.097q.182.16.433.39c.723.67 2.109 1.189 3.296 0c1.039-1.038.582-2.46.142-3.179l-6.96-13.943a.1.1 0 0 0-.09-.056h-9.222a.1.1 0 0 0-.09.056");
}

.jllgvmbaf {
  stop-color: var(--svg-color--2a5fa6, #2A5FA6);
  stop-opacity: 0;
}

.kjmhz0udv {
  stop-color: var(--svg-color--2e84cc, #2E84CC);
  stop-opacity: 0;
}

.lcxfwjddl {
  d: path("M10.908 2.494a.4.4 0 0 1 .4-.4h.403a.4.4 0 0 1 .4.4v2.123h-1.203z");
}

.mbykkwb0i {
  stop-color: var(--svg-color--2979da, #2979DA);
  stop-opacity: 0;
}

.nt_r8bbqc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.785 4.617c.349.096 1.147.466 1.545 1.183s.535.957.554.986");
}

.onlfnjfio {
  stop-color: var(--svg-color--418ffb, #418FFB);
}

.qed7hrbbw {
  fill: var(--svg-color--2d83cb, #2D83CB);
  d: path("M19.986 2.494a.4.4 0 0 1 .4-.4h.404a.4.4 0 0 1 .4.4v2.123h-1.204z");
}

.ql46xacuy {
  stop-color: var(--svg-color--673c6a, #673C6A);
}

.qm-53ybll {
  stop-color: var(--svg-color--331b3b, #331B3B);
  stop-opacity: 0;
}

.qp5ue84mr {
  stop-color: var(--svg-color--5fa0f4, #5FA0F4);
  stop-opacity: 0;
}

.r13wun83b {
  stop-color: var(--svg-color--385baa, #385BAA);
}

.rvjn3c-hj {
  stop-color: var(--svg-color--5fa0f4, #5FA0F4);
}

.rxd6akrtz {
  width: 9.57px;
  height: 1px;
  x: 11.264px;
  y: 11.031px;
  rx: 0.1px;
}

.s1etbibra {
  stop-color: var(--svg-color--3e2242, #3E2242);
}

.u8jpe-blw {
  stop-color: var(--svg-color--3f8ce3, #3F8CE3);
  stop-opacity: 0;
}

.v6d_utbln {
  stop-color: var(--svg-color--5d9cdb, #5D9CDB);
}

.vcsbv4lhy {
  stop-color: var(--svg-color--2e71e2, #2E71E2);
}

.zfjnozp9d {
  d: path("M19.986 2.494a.4.4 0 0 1 .4-.4h.404a.4.4 0 0 1 .4.4v2.123h-1.204z");
}

</style>
