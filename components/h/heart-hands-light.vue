<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#igFZHld)" class="d2kvgvbvc"><path fill="url(#i3HDeEd)" class="gp35pvt9b"/><path fill="url(#isZtnrc)" class="gp35pvt9b"/></g><g filter="url(#iGgHNCe)"><path fill="url(#iJpn3hc)" class="rwvbtrt3r"/><path fill="url(#iBnfZBc)" class="rwvbtrt3r"/><path fill="url(#ip71sfn)" class="rwvbtrt3r"/></g><path fill="url(#ipTSY5b)" class="rwvbtrt3r"/><path clip-rule="evenodd" class="vigqr0bfo"/><path fill="url(#imv29Zb)" clip-rule="evenodd" class="dghky8b2n"/><path fill="url(#i6lbmee)" clip-rule="evenodd" class="dghky8b2n"/><g filter="url(#isOwWmb)"><path class="wo7dp5bps"/></g><g filter="url(#iuOydtk)"><path stroke="url(#iSfIsxe)" class="jj9r0xb-q"/></g><g filter="url(#izuUFfe)"><path stroke="url(#iDCt4vI)" class="hq7o_ibdo"/></g><g filter="url(#iQGXYje)"><path stroke="url(#ip4M2Pe)" class="x3ivw6b7n"/></g><g filter="url(#iJSfu7b)"><path stroke="url(#iBughVk)" class="b2mk9ib2w"/></g><defs><radialGradient id="i3HDeEd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.34381 6.31243 -6.97483 -9.21937 14.969 11.474)" gradientUnits="userSpaceOnUse"><stop class="xyf75tc5l"/><stop offset="1" class="vklozqj4q"/></radialGradient><radialGradient id="isZtnrc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.78128 3.62228 -2.66505 -2.0463 9.781 15.445)" gradientUnits="userSpaceOnUse"><stop offset=".532" class="fxxbvlbns"/><stop offset="1" class="qh_uvdsfh"/></radialGradient><radialGradient id="iJpn3hc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.5 5.0001 -4.29369 -8.15785 12.094 20.008)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="b-ucw5bgc"/><stop offset="1" class="ily6j2bos"/></radialGradient><radialGradient id="iBnfZBc" cx="0" cy="0" r="1" gradientTransform="rotate(-161.777 9.692 13.765)scale(7.76442 5.36053)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="tbaevx4ax"/><stop offset="1" class="u333yhbox"/></radialGradient><radialGradient id="ip71sfn" cx="0" cy="0" r="1" gradientTransform="rotate(-128.919 14.229 8.73)scale(6.46664 2.55443)" gradientUnits="userSpaceOnUse"><stop class="dwtns-qve"/><stop offset="1" class="yve1c-cxy"/></radialGradient><radialGradient id="ipTSY5b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.40628 3.7698 -2.87778 -2.60028 14.469 15.866)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="h5aohemuj"/><stop offset="1" class="frpb4sbas"/></radialGradient><radialGradient id="imv29Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-10.37497 -9.90623 3.07089 -3.2162 26.938 16.724)" gradientUnits="userSpaceOnUse"><stop offset=".381" class="ihm0e2byf"/><stop offset="1" class="pjxtg5xpu"/></radialGradient><radialGradient id="i6lbmee" cx="0" cy="0" r="1" gradientTransform="matrix(3.3125 2.82814 -1.66164 1.94621 22.688 14.351)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="hyq2eekpw"/><stop offset="1" class="gyc1dyb-u"/></radialGradient><radialGradient id="iDCt4vI" cx="0" cy="0" r="1" gradientTransform="matrix(-6.37496 4.62505 -3.3986 -4.68448 30.844 19.505)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="l9oj6kntc"/><stop offset="1" class="t4pwfjbte"/></radialGradient><filter id="igFZHld" width="11.192" height="9.903" x="4.983" y="10.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.698039 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7191"/></filter><filter id="iGgHNCe" width="16.207" height="19.776" x="1.74" y="10.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.615686 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.501961 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7191" result="effect2_innerShadow_20020_7191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.741176 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_7191" result="effect3_innerShadow_20020_7191"/></filter><filter id="isOwWmb" width="16.957" height="19.832" x="13.178" y="10.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.627451 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.588235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_7191" result="effect2_innerShadow_20020_7191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.501961 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_7191" result="effect3_innerShadow_20020_7191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.839216 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_20020_7191" result="effect4_innerShadow_20020_7191"/></filter><filter id="iuOydtk" width="9.25" height="8.72" x="17.031" y="10.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7191" stdDeviation=".5"/></filter><filter id="izuUFfe" width="6.406" height="11.906" x="23.781" y="16.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7191" stdDeviation=".5"/></filter><filter id="iQGXYje" width="8.094" height="7.844" x="13.469" y="22.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7191" stdDeviation=".5"/></filter><filter id="iJSfu7b" width="9.398" height="10.094" x="6.427" y="17.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7191" stdDeviation=".5"/></filter><linearGradient id="iSfIsxe" x1="24.281" x2="15.375" y1="17.224" y2="11.286" gradientUnits="userSpaceOnUse"><stop class="iqk_b94ku"/><stop offset="1" class="j_li4o9eq"/></linearGradient><linearGradient id="ip4M2Pe" x1="15.906" x2="19.499" y1="28.161" y2="23.048" gradientUnits="userSpaceOnUse"><stop class="su8iaacob"/><stop offset="1" class="qfrj4dqxn"/></linearGradient><linearGradient id="iBughVk" x1="11.813" x2="9.606" y1="20.82" y2="24.566" gradientUnits="userSpaceOnUse"><stop class="hduadmbbp"/><stop offset="1" class="ysdv9obxg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:heart-hands-light" /></template>
<style>
.b-ucw5bgc {
  stop-color: var(--svg-color--fbc4b3, #FBC4B3);
}

.b2mk9ib2w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.45 19.099c-.105.802.093 2.606 1.718 3.406c1.676 1.063 3.115 2.125 3.657 2.688");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dghky8b2n {
  fill-rule: evenodd;
  d: path("M21.141 14.586c-.749-.46-1.716-.381-2.349-.065a2.1 2.1 0 1 1-1.878-3.756c1.62-.81 4.17-1.142 6.424.242c3.087 1.894 3.357 4.894 3.357 6.858a2.1 2.1 0 1 1-4.2 0c0-1.636-.24-2.595-1.354-3.279");
}

.dwtns-qve {
  stop-color: var(--svg-color--ce967d, #CE967D);
}

.frpb4sbas {
  stop-color: var(--svg-color--d0908a, #D0908A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxxbvlbns {
  stop-color: var(--svg-color--dba486, #DBA486);
}

.gp35pvt9b {
  d: path("M10.537 14.586c.749-.46 1.716-.381 2.348-.065a2.1 2.1 0 1 0 1.879-3.756c-1.62-.81-4.17-1.142-6.424.242C5.253 12.9 4.983 15.9 4.983 17.865a2.1 2.1 0 1 0 4.2 0c0-1.636.24-2.595 1.354-3.279");
}

.gyc1dyb-u {
  stop-color: var(--svg-color--ffc4a1, #FFC4A1);
  stop-opacity: 0;
}

.h5aohemuj {
  stop-color: var(--svg-color--c5837e, #C5837E);
}

.hduadmbbp {
  stop-color: var(--svg-color--ffd3bc, #FFD3BC);
}

.hq7o_ibdo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M25.781 18.193c.802.375 2.407 1.637 2.407 3.687v4.22");
}

.hyq2eekpw {
  stop-color: var(--svg-color--ffc4a1, #FFC4A1);
}

.ihm0e2byf {
  stop-color: var(--svg-color--ffe3c2, #FFE3C2);
}

.ily6j2bos {
  stop-color: var(--svg-color--d89e89, #D89E89);
}

.iqk_b94ku {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
}

.j_li4o9eq {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
  stop-opacity: 0;
}

.jj9r0xb-q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.031 12.505c1.375-.042 4.275.844 5.25 4.719");
}

.l9oj6kntc {
  stop-color: var(--svg-color--ffe4c7, #FFE4C7);
}

.pjxtg5xpu {
  stop-color: var(--svg-color--ffe3c2, #FFE3C2);
  stop-opacity: 0;
}

.qfrj4dqxn {
  stop-color: var(--svg-color--efbcb1, #EFBCB1);
  stop-opacity: 0;
}

.qh_uvdsfh {
  stop-color: var(--svg-color--dba486, #DBA486);
  stop-opacity: 0;
}

.rwvbtrt3r {
  d: path("m13.995 16.066l-.015-.016l-.044-.042a2 2 0 0 0-.158-.123a2.3 2.3 0 0 0-.49-.259a1.9 1.9 0 0 0-1.248-.051c-.975.294-1.536 1.073-1.895 2.207c-.16.897-.145 2.623.676 3.434c.24.269.764.61 1.435 1.046c1.412.918 3.475 2.26 4.936 4.25c1.044 1.332-.01 2.617-.528 2.9c-.719.392-1.423.665-2.262 0c-.839-.666-2.18-1.624-3.636-1.368s-2.03.352-2.88.352H3.54a1.8 1.8 0 0 1-1.8-1.8v-4.513c0-1.957 1.231-4.44 3.197-5.122c.638-.221 1.243-.634 1.5-1.258c.682-1.649 1.943-3.41 4.389-4.149c2.983-.9 5.437.692 6.373 1.796a2.1 2.1 0 0 1-3.204 2.716");
}

.su8iaacob {
  stop-color: var(--svg-color--efbcb1, #EFBCB1);
}

.t4pwfjbte {
  stop-color: var(--svg-color--ffe4c7, #FFE4C7);
  stop-opacity: 0;
}

.tbaevx4ax {
  stop-color: var(--svg-color--cc8e92, #CC8E92);
}

.u333yhbox {
  stop-color: var(--svg-color--cc8e92, #CC8E92);
  stop-opacity: 0;
}

.vigqr0bfo {
  fill: var(--svg-color--e2b498, #E2B498);
  fill-rule: evenodd;
  d: path("M21.141 14.586c-.749-.46-1.716-.381-2.349-.065a2.1 2.1 0 1 1-1.878-3.756c1.62-.81 4.17-1.142 6.424.242c3.087 1.894 3.357 4.894 3.357 6.858a2.1 2.1 0 1 1-4.2 0c0-1.636-.24-2.595-1.354-3.279");
}

.vklozqj4q {
  stop-color: var(--svg-color--eab195, #EAB195);
}

.wo7dp5bps {
  fill: var(--svg-color--f4beae, #F4BEAE);
  d: path("m17.38 16.066l.015-.016l.044-.042a2 2 0 0 1 .158-.123c.133-.094.3-.187.49-.259c.37-.14.789-.19 1.248-.051c.975.294 1.536 1.073 1.895 2.207c.16.897.145 2.623-.676 3.434c-.24.269-.764.61-1.435 1.046c-1.412.918-3.475 2.26-4.936 4.25c-1.044 1.332-.095 2.742.423 3.024c.72.393 1.528.54 2.367-.125s2.18-1.623 3.636-1.367s2.03.352 2.88.352h4.346a1.8 1.8 0 0 0 1.8-1.8v-4.513c0-1.957-1.231-4.44-3.197-5.122c-.638-.221-1.243-.634-1.5-1.258c-.682-1.649-1.943-3.41-4.389-4.149c-2.982-.9-5.437.692-6.373 1.796a2.1 2.1 0 0 0 3.204 2.716");
}

.x3ivw6b7n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.469 27.849c.52-.854 2.493-2.669 4.094-3.844");
}

.xyf75tc5l {
  stop-color: var(--svg-color--fcd0b3, #FCD0B3);
}

.ysdv9obxg {
  stop-color: var(--svg-color--ffd3bc, #FFD3BC);
  stop-opacity: 0;
}

.yve1c-cxy {
  stop-color: var(--svg-color--ce967d, #CE967D);
  stop-opacity: 0;
}

</style>
