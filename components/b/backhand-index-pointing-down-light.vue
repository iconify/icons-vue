<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixNqa3S)"><path fill="url(#iYsIP8c)" class="g3t7s-kgf"/><path fill="url(#iZEHMks)" class="g3t7s-kgf"/><path fill="url(#ifcWF7d)" class="g3t7s-kgf"/><path fill="url(#iYb01Wb)" class="g3t7s-kgf"/><path fill="url(#iyu2SnT)" class="g3t7s-kgf"/></g><path fill="url(#imo7yFe)" class="g3t7s-kgf"/><path fill="url(#ivm20mb)" class="g3t7s-kgf"/><path fill="url(#iGGMsud)" class="vlmmw3b4b"/><path fill="url(#iS9a7kc)" class="vlmmw3b4b"/><g filter="url(#iImRSqb)"><rect fill="url(#irEv0xc)" class="r4e1i-c9p"/></g><g filter="url(#iw8y0Xd)"><rect fill="url(#iaKmLhd)" transform="rotate(-51.165 22.317 12.946)" class="yri2ekbvr"/></g><g filter="url(#iR95uYc)"><rect class="m4kywcbow"/></g><g filter="url(#iHnX4DW)"><rect class="id4azpb5y"/></g><g filter="url(#igB5iWc)"><rect class="uft9ztbei"/></g><defs><radialGradient id="iYsIP8c" cx="0" cy="0" r="1" gradientTransform="matrix(-7.26582 11.28256 -16.62332 -10.7052 21.64 7.53)" gradientUnits="userSpaceOnUse"><stop class="zxf8fbvkt"/><stop offset="1" class="imr3p_brm"/></radialGradient><radialGradient id="iZEHMks" cx="0" cy="0" r="1" gradientTransform="matrix(-4.903 5.2104 -12.28143 -11.55686 24.7 8.575)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ffl45kbxe"/><stop offset="1" class="s324mt5bd"/></radialGradient><radialGradient id="ifcWF7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.19151 2.37896 0 8.08 22.57)" gradientUnits="userSpaceOnUse"><stop class="m_g_d8vdw"/><stop offset="1" class="f5hz6_b9e"/></radialGradient><radialGradient id="iYb01Wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.94495 2.95871 0 12.724 23.598)" gradientUnits="userSpaceOnUse"><stop class="m_g_d8vdw"/><stop offset="1" class="f5hz6_b9e"/></radialGradient><radialGradient id="iyu2SnT" cx="0" cy="0" r="1" gradientTransform="matrix(-5.41712 -5.281 2.2329 -2.29045 27.275 19.886)" gradientUnits="userSpaceOnUse"><stop class="q70qn9y-n"/><stop offset="1" class="b9-83hb2y"/></radialGradient><radialGradient id="ivm20mb" cx="0" cy="0" r="1" gradientTransform="rotate(-136.118 18.467 7.458)scale(30.9142 28.4421)" gradientUnits="userSpaceOnUse"><stop offset=".848" class="y1-ru4g2h"/><stop offset="1" class="xciu6wzut"/></radialGradient><filter id="ixNqa3S" width="26.537" height="28.714" x="3.801" y="1.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.494118 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5472"/></filter><filter id="iImRSqb" width="4.47" height="15.258" x="18.779" y="14.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5472" stdDeviation=".75"/></filter><filter id="iw8y0Xd" width="8.571" height="7.842" x="21.188" y="10.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5472" stdDeviation=".75"/></filter><filter id="iR95uYc" width="3.788" height="5.164" x="5.149" y="16.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5472" stdDeviation=".5"/></filter><filter id="iHnX4DW" width="3.788" height="5.636" x="9.791" y="17.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5472" stdDeviation=".5"/></filter><filter id="igB5iWc" width="3.788" height="5.584" x="14.106" y="18.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5472" stdDeviation=".5"/></filter><linearGradient id="imo7yFe" x1="3.8" x2="8.875" y1="13.864" y2="14.316" gradientUnits="userSpaceOnUse"><stop class="xciu6wzut"/><stop offset="1" class="y1-ru4g2h"/></linearGradient><linearGradient id="iGGMsud" x1="16.663" x2="19.98" y1="24.736" y2="24.54" gradientUnits="userSpaceOnUse"><stop class="s7o4ibb-i"/><stop offset="1" class="uhg2ibcvi"/></linearGradient><linearGradient id="iS9a7kc" x1="19.025" x2="19.025" y1="19.063" y2="22.55" gradientUnits="userSpaceOnUse"><stop class="q3305mbzy"/><stop offset="1" class="uj-nym00r"/></linearGradient><linearGradient id="irEv0xc" x1="21.014" x2="21.014" y1="12.667" y2="28.258" gradientUnits="userSpaceOnUse"><stop class="nwt8glb0m"/><stop offset="1" class="qpkqxibzk"/></linearGradient><linearGradient id="iaKmLhd" x1="23.231" x2="23.231" y1="11.142" y2="19.579" gradientUnits="userSpaceOnUse"><stop class="j_li4o9eq"/><stop offset="1" class="iqk_b94ku"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-down-light" /></template>
<style>
.b9-83hb2y {
  stop-color: var(--svg-color--e4a89e, #E4A89E);
  stop-opacity: 0;
}

.f5hz6_b9e {
  stop-color: var(--svg-color--cb9190, #CB9190);
  stop-opacity: 0;
}

.ffl45kbxe {
  stop-color: var(--svg-color--ffe8c8, #FFE8C8);
}

.ft5dv1b6b {
  fill: none;
}

.g3t7s-kgf {
  d: path("M28.042 13.88c1.24.86 1.702 2.597.888 3.849a2.657 2.657 0 0 1-3.702.781l-2.61-1.695v10.53a2.637 2.637 0 1 1-5.274 0v-4.284a2.493 2.493 0 0 1-4.564-.344a2.724 2.724 0 0 1-4.487-.884a2.723 2.723 0 0 1-4.493-2.07v-3.102l.002-.104v-4.859c0-1.431.849-3.878 2.51-6.022q.25-.33.527-.637l.01-.013a9.2 9.2 0 0 1 6.833-3.008a9.2 9.2 0 0 1 7.577 3.945c.603.832.892 1.506 1.178 2.175c.22.513.438 1.023.797 1.601c.566.913 1.4 1.59 1.865 1.969l.098.08h-.002z");
}

.id4azpb5y {
  width: 1.788px;
  height: 3.636px;
  x: 10.791px;
  y: 18.493px;
  fill: var(--svg-color--ffc0b6, #FFC0B6);
  rx: 0.894px;
}

.imr3p_brm {
  stop-color: var(--svg-color--f2bcab, #F2BCAB);
}

.iqk_b94ku {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
}

.j_li4o9eq {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
  stop-opacity: 0;
}

.m_g_d8vdw {
  stop-color: var(--svg-color--cb9190, #CB9190);
}

.m4kywcbow {
  width: 1.788px;
  height: 3.164px;
  x: 6.149px;
  y: 17.968px;
  fill: var(--svg-color--ffc0b6, #FFC0B6);
  rx: 0.894px;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.q3305mbzy {
  stop-color: var(--svg-color--f4c0ae, #F4C0AE);
}

.q70qn9y-n {
  stop-color: var(--svg-color--e4a89e, #E4A89E);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.r4e1i-c9p {
  width: 1.47px;
  height: 12.258px;
  x: 20.279px;
  y: 16px;
  rx: 0.735px;
}

.s324mt5bd {
  stop-color: var(--svg-color--ffe8c8, #FFE8C8);
  stop-opacity: 0;
}

.s7o4ibb-i {
  stop-color: var(--svg-color--d99d90, #D99D90);
}

.uft9ztbei {
  width: 1.788px;
  height: 3.584px;
  x: 15.106px;
  y: 19.49px;
  fill: var(--svg-color--ffc0b6, #FFC0B6);
  rx: 0.894px;
}

.uhg2ibcvi {
  stop-color: var(--svg-color--d99d90, #D99D90);
  stop-opacity: 0;
}

.uj-nym00r {
  stop-color: var(--svg-color--f4c0ae, #F4C0AE);
  stop-opacity: 0;
}

.vlmmw3b4b {
  d: path("M17.344 19.49v7.855a2.637 2.637 0 1 0 5.273 0V19.49z");
}

.xciu6wzut {
  stop-color: var(--svg-color--e1a992, #E1A992);
}

.y1-ru4g2h {
  stop-color: var(--svg-color--e1a992, #E1A992);
  stop-opacity: 0;
}

.yri2ekbvr {
  width: 1.828px;
  height: 6.633px;
  x: 22.317px;
  y: 12.946px;
  rx: 0.914px;
}

.zxf8fbvkt {
  stop-color: var(--svg-color--ffdcbf, #FFDCBF);
}

</style>
