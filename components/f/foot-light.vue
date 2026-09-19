<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ivnr7Cf)"><path class="du7h7j1zq"/><path fill="url(#inUygxd)" class="wy1mwqbfw"/></g><path fill="url(#iXcHkDc)" class="wy1mwqbfw"/><path fill="url(#iEeUm5b)" class="wy1mwqbfw"/><path fill="url(#ifyu1od)" class="wy1mwqbfw"/><path fill="url(#ie29Crc)" class="wy1mwqbfw"/><g filter="url(#iFrba6c)"><path class="xq0scub1e"/></g><g filter="url(#i3dgvpe)"><circle fill="url(#i0gVdAe)" class="fp3l2wnkq"/></g><g filter="url(#i8izQld)"><path fill="url(#iPTLyfd)" class="pkocu390g"/></g><g filter="url(#ibFOoMc)"><path stroke="url(#iSMgZed)" class="dzcdcdl0b"/></g><defs><linearGradient id="iXcHkDc" x1="31.44" x2="22.855" y1="22.238" y2="23.257" gradientUnits="userSpaceOnUse"><stop class="icd8fhbfu"/><stop offset="1" class="uh7nbdb2t"/></linearGradient><linearGradient id="iEeUm5b" x1="16" x2="16" y1="31.274" y2="26.886" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ehdrf6mib"/><stop offset="1" class="ob9xepb4j"/></linearGradient><linearGradient id="ifyu1od" x1="16" x2="16" y1="30.023" y2="29.578" gradientUnits="userSpaceOnUse"><stop class="wwinqpbpq"/><stop offset="1" class="ej866kzte"/></linearGradient><linearGradient id="iPTLyfd" x1="27.694" x2="20.522" y1="20.819" y2="20.627" gradientUnits="userSpaceOnUse"><stop offset=".289" class="vgx4yo94m"/><stop offset=".592" class="wlxw3fbcf"/><stop offset="1" class="htb-kuf3j"/></linearGradient><linearGradient id="iSMgZed" x1="4.811" x2="15.07" y1="27.368" y2="27.368" gradientUnits="userSpaceOnUse"><stop class="yyl9758et"/><stop offset="1" class="exkrr549u"/></linearGradient><filter id="ivnr7Cf" width="28.334" height="21.361" x="2.083" y="9.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.647059 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_0_56"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.666667 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_0_56" result="effect2_innerShadow_0_56"/></filter><filter id="iFrba6c" width="11.639" height="20.439" x="19.753" y="9.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_56" stdDeviation="1.25"/></filter><filter id="i3dgvpe" width="8.171" height="8.171" x="19.34" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_56" stdDeviation=".5"/></filter><filter id="i8izQld" width="10.428" height="8.854" x="17.75" y="15.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_56" stdDeviation=".625"/></filter><filter id="ibFOoMc" width="20.369" height="6" x="1.557" y="23.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_56" stdDeviation="1"/></filter><radialGradient id="inUygxd" cx="0" cy="0" r="1" gradientTransform="matrix(5.00281 5.34388 -6.1224 5.73165 17.184 14.65)" gradientUnits="userSpaceOnUse"><stop class="qczm2nb0c"/><stop offset="1" class="w9gphcbmi"/></radialGradient><radialGradient id="ie29Crc" cx="0" cy="0" r="1" gradientTransform="rotate(-121.741 21.637 6.363)scale(19.7821 38.1448)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="in3j6b3dx"/><stop offset="1" class="llutqqmas"/><stop offset="1" class="ti7_8cbtd"/></radialGradient><radialGradient id="i0gVdAe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65402 0 0 -5.03515 25.612 19.085)" gradientUnits="userSpaceOnUse"><stop class="zpfp7ccna"/><stop offset="1" class="evyv31bdl"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:foot-light" /></template>
<style>
.du7h7j1zq {
  fill: var(--svg-color--f4c0ab, #F4C0AB);
  d: path("M29.783 24.724c-.618-2.731-1.462-2.726-1.669-6.365c-.207-3.638-.672-8.297-6.016-8.297c-2.437 0-5.642 1.414-5.828 6.594c0 3.702-4.75 5.797-7.145 6.814c-.793.337-2.156.968-2.948.968c-.47 0-.789-.307-1.329-.297c-1.937 0-2.765 1.797-2.765 3.078s.87 2.705 2.872 2.705h20.878c3.011 0 4.569-2.47 3.95-5.2");
}

.dzcdcdl0b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.557 26.931h14.369");
}

.ehdrf6mib {
  stop-color: var(--svg-color--c18497, #C18497);
}

.ej866kzte {
  stop-color: var(--svg-color--b67f9f, #B67F9F);
  stop-opacity: 0;
}

.evyv31bdl {
  stop-color: var(--svg-color--ffe8cb, #FFE8CB);
  stop-opacity: 0;
}

.exkrr549u {
  stop-color: var(--svg-color--fac6b2, #FAC6B2);
  stop-opacity: 0;
}

.fp3l2wnkq {
  cx: 23.426px;
  cy: 19.085px;
  r: 3.086px;
}

.ft5dv1b6b {
  fill: none;
}

.htb-kuf3j {
  stop-color: var(--svg-color--e3ad9c, #E3AD9C);
}

.icd8fhbfu {
  stop-color: var(--svg-color--ffdabe, #FFDABE);
}

.in3j6b3dx {
  stop-color: var(--svg-color--d5a78d, #D5A78D);
  stop-opacity: 0;
}

.llutqqmas {
  stop-color: var(--svg-color--c6a186, #C6A186);
}

.ob9xepb4j {
  stop-color: var(--svg-color--c18497, #C18497);
  stop-opacity: 0;
}

.pkocu390g {
  d: path("M20.055 16.816a.48.48 0 0 0-.4.207a3.964 3.964 0 1 0 6.762.234a3.085 3.085 0 1 1-5.806.41c.107-.389-.152-.85-.556-.85");
}

.qczm2nb0c {
  stop-color: var(--svg-color--d6a88e, #D6A88E);
}

.ti7_8cbtd {
  stop-color: var(--svg-color--d5a78d, #D5A78D);
}

.uh7nbdb2t {
  stop-color: var(--svg-color--ffdabe, #FFDABE);
  stop-opacity: 0;
}

.vgx4yo94m {
  stop-color: var(--svg-color--ffd2bb, #FFD2BB);
}

.w9gphcbmi {
  stop-color: var(--svg-color--ebb6a3, #EBB6A3);
  stop-opacity: 0;
}

.wlxw3fbcf {
  stop-color: var(--svg-color--ecb1a8, #ECB1A8);
}

.wwinqpbpq {
  stop-color: var(--svg-color--b67f9f, #B67F9F);
}

.wy1mwqbfw {
  d: path("M29.783 24.724c-.618-2.731-1.462-2.726-1.669-6.365c-.207-3.638-.672-8.297-6.016-8.297c-2.437 0-5.642 1.414-5.828 6.594c0 3.702-4.75 5.797-7.145 6.814c-.793.337-2.156.968-2.948.968c-.47 0-.789-.307-1.329-.297c-1.937 0-2.765 1.797-2.765 3.078s.87 2.705 2.872 2.705h20.878c3.011 0 4.569-2.47 3.95-5.2");
}

.xq0scub1e {
  fill: var(--svg-color--ffe6c7, #FFE6C7);
  d: path("M24.788 11.84c-.946 0-1.636 1.128-1.386 2.04c.39 1.425.623 3.096.682 4.141c.102 1.781.395 2.472.721 3.24c.207.487.427 1.006.62 1.855c.497 2.186-.754 4.162-3.172 4.162h3.649c.81 0 3.945 0 2.701-3.718c-.223-.474-.473-.94-.692-1.348a14 14 0 0 1-.485-.952c-.326-.767-.393-1.458-.495-3.239c-.082-1.446-.495-4.091-1.2-5.623c-.167-.361-.545-.559-.943-.559");
}

.yyl9758et {
  stop-color: var(--svg-color--fac6b2, #FAC6B2);
}

.zpfp7ccna {
  stop-color: var(--svg-color--ffe8cb, #FFE8CB);
}

</style>
