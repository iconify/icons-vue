<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijwJICb)"><path fill="url(#ioSXHtb)" class="ynn23ohfc"/><path fill="url(#io6Peed)" class="ynn23ohfc"/></g><g filter="url(#ibVAlec)"><path class="q9ms_db9u"/></g><g filter="url(#iTR23ab)"><path fill="url(#iDl8rzb)" class="lfvq-7q5g"/></g><rect class="u-107_b1v"/><rect class="h-08ajbdk"/><rect class="re5ugug6q"/><rect class="j47sm_ysg"/><g filter="url(#igFAydc)"><path class="jmo6j6akg"/></g><g filter="url(#iA2WNLb)"><path fill="url(#iOPQZ7U)" class="tds-tbamy"/></g><g filter="url(#iUc0Qvv)"><path class="qougpzaqb"/></g><g filter="url(#il3NgAc)"><path fill="url(#iCc9Dre)" clip-rule="evenodd" class="y3f896b-i"/></g><defs><filter id="ijwJICb" width="22.456" height="27.434" x="4.722" y="2.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.376471 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23055"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.329412 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23055" result="effect2_innerShadow_18_23055"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.35" dy=".25"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.760784 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23055" result="effect3_innerShadow_18_23055"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.560784 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_23055" result="effect4_innerShadow_18_23055"/></filter><filter id="ibVAlec" width="18.844" height="23.691" x="6.201" y="5.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23055" stdDeviation=".25"/></filter><filter id="iTR23ab" width="18.144" height="22.991" x="6.918" y="5.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.721569 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23055"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23055" result="effect2_innerShadow_18_23055"/></filter><filter id="igFAydc" width="6.352" height="6.317" x="18.506" y="21.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23055" stdDeviation=".125"/></filter><filter id="iA2WNLb" width="6.126" height="6.041" x="18.936" y="21.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.611765 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23055"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.866667 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23055" result="effect2_innerShadow_18_23055"/></filter><filter id="iUc0Qvv" width="10.488" height="3.956" x="10.379" y="4.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23055" stdDeviation=".2"/></filter><filter id="il3NgAc" width="10.137" height="6.255" x="10.929" y="1.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.501961 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23055"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.65098 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23055" result="effect2_innerShadow_18_23055"/></filter><linearGradient id="ioSXHtb" x1="16" x2="16" y1="3.035" y2="29.969" gradientUnits="userSpaceOnUse"><stop class="miyfpt65j"/><stop offset="1" class="l374fgxug"/></linearGradient><linearGradient id="iDl8rzb" x1="15.99" x2="15.99" y1="5.156" y2="27.848" gradientUnits="userSpaceOnUse"><stop class="n9q6w_buu"/><stop offset="1" class="oyokz3bed"/></linearGradient><linearGradient id="iOPQZ7U" x1="19.342" x2="21.623" y1="22.688" y2="25.156" gradientUnits="userSpaceOnUse"><stop class="tueqk-t5m"/><stop offset="1" class="ylk7n8brw"/></linearGradient><linearGradient id="iCc9Dre" x1="18.717" x2="15.654" y1="3.781" y2="8.219" gradientUnits="userSpaceOnUse"><stop class="vjrkiobzn"/><stop offset="1" class="xtxutlmpp"/></linearGradient><radialGradient id="io6Peed" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 2.02864 0 15.685 5.313)" gradientUnits="userSpaceOnUse"><stop class="th2yoqu3k"/><stop offset="1" class="c3vatlb5j"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clipboard" /></template>
<style>
.c3vatlb5j {
  stop-color: var(--svg-color--d79769, #D79769);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h-08ajbdk {
  width: 13.914px;
  height: 0.977px;
  x: 9.037px;
  y: 15.023px;
  fill: var(--svg-color--9b96a2, #9B96A2);
  rx: 0.488px;
}

.j47sm_ysg {
  width: 8.969px;
  height: 0.977px;
  x: 9.037px;
  y: 21.039px;
  fill: var(--svg-color--9b96a2, #9B96A2);
  rx: 0.488px;
}

.jmo6j6akg {
  fill: var(--svg-color--d0c1e0, #D0C1E0);
  d: path("M24.607 22.03h-.003c0 .219-.123.27-.242.283h-4.306a.98.98 0 0 0-.979.98v4.295c-.03.147-.219.231-.318.256l-.003.004h.072a.73.73 0 0 0 .52-.215l5.044-5.046a.73.73 0 0 0 .215-.519z");
}

.l374fgxug {
  stop-color: var(--svg-color--db925d, #DB925D);
}

.lfvq-7q5g {
  d: path("M8.318 5.156c-.69 0-1.25.56-1.25 1.25v20.192c0 .69.56 1.25 1.25 1.25H19.01a.75.75 0 0 0 .53-.22l5.152-5.153a.75.75 0 0 0 .22-.53V6.406c0-.69-.56-1.25-1.25-1.25z");
}

.miyfpt65j {
  stop-color: var(--svg-color--e8a874, #E8A874);
}

.n9q6w_buu {
  stop-color: var(--svg-color--eae2f4, #EAE2F4);
}

.oyokz3bed {
  stop-color: var(--svg-color--e4daef, #E4DAEF);
}

.q9ms_db9u {
  fill: var(--svg-color--cd7d52, #CD7D52);
  d: path("M7.951 5.531c-.69 0-1.25.56-1.25 1.25v20.192c0 .69.56 1.25 1.25 1.25h10.691a.75.75 0 0 0 .53-.22l5.153-5.153a.75.75 0 0 0 .22-.53V6.781c0-.69-.56-1.25-1.25-1.25z");
}

.qougpzaqb {
  fill: var(--svg-color--cabfd5, #CABFD5);
  d: path("M10.78 5.656a.5.5 0 0 1 .5-.5h9.187v2.657a.5.5 0 0 1-.5.5h-8.688a.5.5 0 0 1-.5-.5z");
}

.re5ugug6q {
  width: 13.914px;
  height: 0.977px;
  x: 9.037px;
  y: 18.031px;
  fill: var(--svg-color--9b96a2, #9B96A2);
  rx: 0.488px;
}

.tds-tbamy {
  d: path("M24.912 21.906h-.004c0 .224-.125.277-.246.29h-4.398a1 1 0 0 0-1 1v4.387c-.03.15-.224.236-.325.26l-.003.005h.073a.75.75 0 0 0 .53-.22l5.153-5.153a.75.75 0 0 0 .22-.53z");
}

.th2yoqu3k {
  stop-color: var(--svg-color--d79769, #D79769);
}

.tueqk-t5m {
  stop-color: var(--svg-color--d6cde1, #D6CDE1);
}

.u-107_b1v {
  width: 13.914px;
  height: 0.977px;
  x: 9.037px;
  y: 12.016px;
  fill: var(--svg-color--9b96a2, #9B96A2);
  rx: 0.488px;
}

.vjrkiobzn {
  stop-color: var(--svg-color--948a94, #948A94);
}

.xtxutlmpp {
  stop-color: var(--svg-color--8d8291, #8D8291);
}

.y3f896b-i {
  fill-rule: evenodd;
  d: path("M15.99 1.984c1.08 0 1.957.862 1.984 1.935c0 .027.023.05.05.05h.943a2 2 0 0 1 2 2v1.566a.504.504 0 0 1-.504.504h-8.93a.504.504 0 0 1-.504-.504V5.97a2 2 0 0 1 2-2h.927a.05.05 0 0 0 .05-.05a1.984 1.984 0 0 1 1.984-1.935m0 2.883a.898.898 0 1 0 0-1.797a.898.898 0 0 0 0 1.797");
}

.ylk7n8brw {
  stop-color: var(--svg-color--c6bad2, #C6BAD2);
}

.ynn23ohfc {
  d: path("M5.072 4.635a1.6 1.6 0 0 1 1.6-1.6h18.656a1.6 1.6 0 0 1 1.6 1.6V28.37a1.6 1.6 0 0 1-1.6 1.6H6.672a1.6 1.6 0 0 1-1.6-1.6z");
}

</style>
