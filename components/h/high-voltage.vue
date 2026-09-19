<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iK3Dsyd)" class="eucyqibrl"/><g filter="url(#iotWnBd)"><path fill="url(#iVDMuwd)" class="yu9ommb9t"/></g><path fill="url(#iEtrSCe)" class="yu9ommb9t"/><path fill="url(#iFFnvPd)" class="yu9ommb9t"/><path fill="url(#iM1gebb)" class="yu9ommb9t"/><path fill="url(#iBdd3tX)" class="yu9ommb9t"/><defs><linearGradient id="iK3Dsyd" x1="18.407" x2="18.407" y1="7.966" y2="23.712" gradientUnits="userSpaceOnUse"><stop class="rmyusqn3l"/><stop offset="1" class="ye48tppfg"/></linearGradient><linearGradient id="iVDMuwd" x1="15.072" x2="15.072" y1="11.05" y2="26.586" gradientUnits="userSpaceOnUse"><stop class="v80r0r6-p"/><stop offset="1" class="ivq57fb2f"/></linearGradient><linearGradient id="iEtrSCe" x1="15.072" x2="15.072" y1="2.696" y2="13.761" gradientUnits="userSpaceOnUse"><stop class="erglgdc8a"/><stop offset="1" class="jkg2xab0t"/></linearGradient><linearGradient id="iM1gebb" x1="13.063" x2="13.493" y1="8.372" y2="8.63" gradientUnits="userSpaceOnUse"><stop class="mubvo2bzb"/><stop offset="1" class="w5hr24buu"/></linearGradient><radialGradient id="iFFnvPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45595 -1.40857 0 17.1 7.924)" gradientUnits="userSpaceOnUse"><stop class="ug-juxb-t"/><stop offset="1" class="ft-8t4bgx"/></radialGradient><radialGradient id="iBdd3tX" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.6875 -2.4375 0 17.157 7.716)" gradientUnits="userSpaceOnUse"><stop class="iqgchdc3x"/><stop offset="1" class="o4j4zbc9a"/></radialGradient><filter id="iotWnBd" width="14.78" height="26.875" x="7.682" y="2.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.431373 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15539"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:high-voltage" /></template>
<style>
.erglgdc8a {
  stop-color: var(--svg-color--df9844, #DF9844);
}

.eucyqibrl {
  d: path("m16.725 3.803l-8.158 13.53a.464.464 0 0 0 .398.703h4.127c.307 0 .557.25.557.557v8.638h-.491v2.34h.752a.27.27 0 0 0 .255-.134l9.073-14.865a.279.279 0 0 0-.237-.424h-4.709a.464.464 0 0 1-.464-.464V2.975a.276.276 0 0 0-.262-.278l-.841-.001z");
}

.ft-8t4bgx {
  stop-color: var(--svg-color--fe9052, #FE9052);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.iqgchdc3x {
  stop-color: var(--svg-color--ffb54b, #FFB54B);
}

.ivq57fb2f {
  stop-color: var(--svg-color--f14b49, #F14B49);
}

.jkg2xab0t {
  stop-color: var(--svg-color--df9844, #DF9844);
  stop-opacity: 0;
}

.mubvo2bzb {
  stop-color: var(--svg-color--c76c38, #C76C38);
}

.o4j4zbc9a {
  stop-color: var(--svg-color--ffb54b, #FFB54B);
  stop-opacity: 0;
}

.rmyusqn3l {
  stop-color: var(--svg-color--ffbd61, #FFBD61);
}

.ug-juxb-t {
  stop-color: var(--svg-color--fe9052, #FE9052);
}

.v80r0r6-p {
  stop-color: var(--svg-color--ffa547, #FFA547);
}

.w5hr24buu {
  stop-color: var(--svg-color--c76c38, #C76C38);
  stop-opacity: 0;
}

.ye48tppfg {
  stop-color: var(--svg-color--eb5c74, #EB5C74);
}

.yu9ommb9t {
  d: path("M16.493 2.831L7.75 17.332a.464.464 0 0 0 .397.704h4.127c.308 0 .557.25.557.557v10.7c0 .28.37.384.516.144l9.074-14.865a.279.279 0 0 0-.238-.424h-4.709a.464.464 0 0 1-.464-.464V2.975c0-.282-.371-.385-.517-.144");
}

</style>
