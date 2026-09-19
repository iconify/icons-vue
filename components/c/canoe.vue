<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijUcLtb)"><path fill="url(#iDWaCWc)" class="z6ij54bma"/><path fill="url(#irXxare)" class="z6ij54bma"/><path fill="url(#isnjjbd)" class="z6ij54bma"/><path fill="url(#ioIYccV)" class="z6ij54bma"/></g><path fill="url(#irKMuic)" class="a-zd0lyco"/><g filter="url(#ilmZkCd)"><path fill="url(#iBDOnZb)" class="f9rkgxmdy"/></g><g filter="url(#imJ3KPb)"><path fill="url(#iwKYTcL)" class="mq05th_iz"/></g><path fill="url(#il7UkHh)" class="wu33r3zzs"/><g filter="url(#iGP4xMd)"><path fill="url(#in8TPft)" class="d482o-bno"/></g><defs><linearGradient id="iDWaCWc" x1="15.519" x2="15.519" y1="19.08" y2="26.5" gradientUnits="userSpaceOnUse"><stop class="la1txpbox"/><stop offset="1" class="an_yqybom"/></linearGradient><linearGradient id="irKMuic" x1="16.015" x2="16.015" y1="17.875" y2="19.855" gradientUnits="userSpaceOnUse"><stop class="ivh2ksbah"/><stop offset="1" class="l0expebvn"/></linearGradient><linearGradient id="iBDOnZb" x1="13.488" x2="8.809" y1="22.314" y2="27.038" gradientUnits="userSpaceOnUse"><stop class="zuc7f4usi"/><stop offset="1" class="csu9b7lmh"/><stop offset="1" class="b6iftgbft"/></linearGradient><linearGradient id="iwKYTcL" x1="24.523" x2="25.018" y1="9.149" y2="11.32" gradientUnits="userSpaceOnUse"><stop class="lxeplpbow"/><stop offset="1" class="re_q_w9qz"/></linearGradient><linearGradient id="in8TPft" x1="18.792" x2="18.792" y1="30" y2="24.343" gradientUnits="userSpaceOnUse"><stop class="mtztso4yr"/><stop offset="1" class="l2tc1xykf"/></linearGradient><radialGradient id="irXxare" cx="0" cy="0" r="1" gradientTransform="matrix(24.93752 -.0625 .23467 93.6333 4.691 19.875)" gradientUnits="userSpaceOnUse"><stop offset=".946" class="jcx902lsi"/><stop offset="1" class="kysgp25tr"/></radialGradient><radialGradient id="isnjjbd" cx="0" cy="0" r="1" gradientTransform="rotate(138.211 3.716 12.784)scale(5.03598 .98416)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="mpjvb8b5x"/><stop offset="1" class="j8in2abil"/></radialGradient><radialGradient id="ioIYccV" cx="0" cy="0" r="1" gradientTransform="matrix(-2.22946 1.85396 -.36231 -.4357 10.054 22.609)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="mpjvb8b5x"/><stop offset="1" class="j8in2abil"/></radialGradient><radialGradient id="il7UkHh" cx="0" cy="0" r="1" gradientTransform="rotate(45 -11.923 30.178)scale(.68435 17.3384)" gradientUnits="userSpaceOnUse"><stop class="wd_6ajkuy"/><stop offset="1" class="qy-53zbac"/></radialGradient><filter id="ijUcLtb" width="28.36" height="7.92" x="2.089" y="18.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.301961 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12167"/></filter><filter id="ilmZkCd" width="8.78" height="8.839" x="5.147" y="21.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.941176 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12167"/></filter><filter id="imJ3KPb" width="2.144" height="2.135" x="24.021" y="8.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.560784 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12167"/></filter><filter id="iGP4xMd" width="28.6" height="7.6" x="1.349" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.67451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12167"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12167" result="effect2_innerShadow_18_12167"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:canoe" /></template>
<style>
.a-zd0lyco {
  d: path("M30 18.445c0-.46-.39-.82-.89-.88c-.07 0-.14-.02-.22-.01c-1.52.16-3.07.28-4.64.38c-5.43.35-11.05.35-16.48 0c-1.56-.1-3.12-.22-4.64-.38c-.08-.01-.15.01-.22.01c-.49.05-.88.42-.88.88c0 .1.01.19.02.29c.01.13.02.25.04.37c8.96 1 18.89 1 27.85 0c.01-.12.03-.25.04-.37c.01-.09.02-.19.02-.29");
}

.an_yqybom {
  stop-color: var(--svg-color--fc6d4e, #FC6D4E);
}

.b6iftgbft {
  stop-color: var(--svg-color--efba7a, #EFBA7A);
}

.csu9b7lmh {
  stop-color: var(--svg-color--cd8833, #CD8833);
}

.d482o-bno {
  d: path("M29.949 23c-1.75 0-1.559.96-3.318.96c-1.75 0-1.848-.96-3.607-.96c-1.75 0-1.777.96-3.526.96c-1.75 0-1.951-.96-3.7-.96c-1.613 0-2.02.96-3.77.96S10.216 23 8.468 23c-1.75 0-1.985.96-3.724.96c-1.438 0-1.775-.96-2.795-.96v7h27.99z");
}

.f9rkgxmdy {
  d: path("m8.439 29.663l4.91-4.98c.78-.79.77-2.05-.02-2.83s-2.05-.77-2.83.02l-4.91 4.98c-.39.4-.39 1.03.01 1.42l1.42 1.39c.39.4 1.03.4 1.42 0");
}

.ft5dv1b6b {
  fill: none;
}

.ivh2ksbah {
  stop-color: var(--svg-color--6e5187, #6E5187);
}

.j8in2abil {
  stop-color: var(--svg-color--ca653a, #CA653A);
  stop-opacity: 0;
}

.jcx902lsi {
  stop-color: var(--svg-color--ffaa62, #FFAA62);
  stop-opacity: 0;
}

.kysgp25tr {
  stop-color: var(--svg-color--ffaa62, #FFAA62);
}

.l0expebvn {
  stop-color: var(--svg-color--3f3c42, #3F3C42);
}

.l2tc1xykf {
  stop-color: var(--svg-color--539dfa, #539DFA);
}

.la1txpbox {
  stop-color: var(--svg-color--ff9053, #FF9053);
}

.lxeplpbow {
  stop-color: var(--svg-color--ffa661, #FFA661);
}

.mpjvb8b5x {
  stop-color: var(--svg-color--ca653a, #CA653A);
}

.mq05th_iz {
  d: path("m24.869 9.133l1.01.99c.25.24.14.67-.2.76l-.22.06c-.84.23-1.62-.53-1.4-1.38l.06-.22c.08-.34.5-.46.75-.21");
}

.mtztso4yr {
  stop-color: var(--svg-color--51adff, #51ADFF);
}

.qy-53zbac {
  stop-color: var(--svg-color--fe9c57, #FE9C57);
}

.re_q_w9qz {
  stop-color: var(--svg-color--ff9b56, #FF9B56);
}

.wd_6ajkuy {
  stop-color: var(--svg-color--ffcd8c, #FFCD8C);
}

.wu33r3zzs {
  d: path("M25.559 9.933a.49.49 0 0 0-.49-.49c-.13 0-.25.05-.34.14l-14.44 14.66c-.1.09-.16.22-.16.36c0 .27.23.49.5.49c.14 0 .27-.07.36-.16l14.43-14.65c.09-.1.14-.22.14-.35");
}

.z6ij54bma {
  d: path("M2.089 19.08c.38 4.15 4.22 7.42 8.94 7.42h9.98c4.71 0 8.56-3.27 8.94-7.42c-8.97 1-18.9 1-27.86 0");
}

.zuc7f4usi {
  stop-color: var(--svg-color--ffd18e, #FFD18E);
}

</style>
