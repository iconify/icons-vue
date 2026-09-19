<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iaHaZnc" class="a4jrq6b-j"/></defs><g class="ft5dv1b6b"><path fill="url(#i6waHsf)" class="kqxl2hkqc"/><path fill="url(#iHMpble)" class="kqxl2hkqc"/><g filter="url(#igByPgh)"><path class="arf0ribny"/><path fill="url(#i2IZqgb)" class="j8isrxrsp"/></g><g filter="url(#iJRp16b)"><path class="pwl1_27iu"/><path fill="url(#ic5Dxse)" class="x8w3wsxhm"/></g><g filter="url(#itfua1c)"><path fill="url(#iMrk5eb)" class="stdwivold"/><path fill="url(#ieRS1Fc)" class="stdwivold"/></g><g filter="url(#ih2lpFd)"><use href="#iaHaZnc"/></g><g filter="url(#i5lrGPd)"><use href="#iaHaZnc"/><path fill="url(#i3Zh2Km)" class="u73dmpbhj"/><path fill="url(#idHhmPb)" class="u73dmpbhj"/><path fill="url(#i2X2RDd)" class="u73dmpbhj"/><path fill="url(#iaUKqcc)" class="u73dmpbhj"/></g><defs><radialGradient id="i6waHsf" cx="0" cy="0" r="1" gradientTransform="rotate(-110.468 8.676 -.406)scale(3.57025 3.46764)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="r02t0tqck"/><stop offset="1" class="nh9jgyb1q"/></radialGradient><radialGradient id="iHMpble" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23828 -.7496 2.49269 -4.1177 13.605 6.683)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="xwn2jnbkx"/><stop offset="1" class="o70hz4bsj"/></radialGradient><radialGradient id="i2IZqgb" cx="0" cy="0" r="1" gradientTransform="rotate(142.938 1.301 11.974)scale(3.03715 2.64919)" gradientUnits="userSpaceOnUse"><stop class="cnnd41gej"/><stop offset="1" class="yb9mz6k-w"/></radialGradient><radialGradient id="ic5Dxse" cx="0" cy="0" r="1" gradientTransform="rotate(142.938 4.574 13.07)scale(3.03715 2.64919)" gradientUnits="userSpaceOnUse"><stop class="cnnd41gej"/><stop offset="1" class="yb9mz6k-w"/></radialGradient><radialGradient id="ieRS1Fc" cx="0" cy="0" r="1" gradientTransform="rotate(142.938 7.847 14.168)scale(3.03715 2.64919)" gradientUnits="userSpaceOnUse"><stop class="cnnd41gej"/><stop offset="1" class="yb9mz6k-w"/></radialGradient><radialGradient id="i3Zh2Km" cx="0" cy="0" r="1" gradientTransform="matrix(-3.78308 -12.40873 6.9718 -2.1255 16.395 13.277)" gradientUnits="userSpaceOnUse"><stop class="vuekx_bhg"/><stop offset="1" class="ufq42fb7e"/></radialGradient><radialGradient id="idHhmPb" cx="0" cy="0" r="1" gradientTransform="rotate(147.006 13.079 7.761)scale(12.0883 13.5028)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="dkaaooa7z"/><stop offset="1" class="q8r289j7a"/></radialGradient><radialGradient id="i2X2RDd" cx="0" cy="0" r="1" gradientTransform="rotate(147.319 3.003 6.529)scale(9.52873 11.6115)" gradientUnits="userSpaceOnUse"><stop class="dkaaooa7z"/><stop offset=".696" class="q8r289j7a"/></radialGradient><radialGradient id="iaUKqcc" cx="0" cy="0" r="1" gradientTransform="matrix(2.49688 7.64197 -2.84897 .93085 11.25 6.392)" gradientUnits="userSpaceOnUse"><stop class="dkaaooa7z"/><stop offset="1" class="q8r289j7a"/></radialGradient><filter id="igByPgh" width="6.606" height="7.086" x="3.131" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.152941 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15159"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.529412 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_15159" result="effect2_innerShadow_18_15159"/></filter><filter id="iJRp16b" width="6.606" height="7.086" x="9.678" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.152941 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15159"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.529412 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_15159" result="effect2_innerShadow_18_15159"/></filter><filter id="itfua1c" width="6.606" height="7.086" x="16.224" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.152941 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15159"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.529412 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_15159" result="effect2_innerShadow_18_15159"/></filter><filter id="ih2lpFd" width="27.899" height="17.938" x="2" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15159"/></filter><filter id="i5lrGPd" width="27.899" height="17.938" x="2" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="3.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15159"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.698039 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_15159" result="effect2_innerShadow_18_15159"/></filter><linearGradient id="iMrk5eb" x1="22.23" x2="17.066" y1="20.873" y2="27.748" gradientUnits="userSpaceOnUse"><stop class="yfxbhhvvc"/><stop offset="1" class="i-6d3fbbt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cloud-with-rain" /></template>
<style>
.a4jrq6b-j {
  fill: var(--svg-color--e0d3ff, #E0D3FF);
  d: path("M27.202 4.55c-3.544-3.454-9.216-3.394-12.67.15a8.9 8.9 0 0 0-2.014 3.196a.268.268 0 0 1-.398.13a6 6 0 0 0-.984-.53A6.447 6.447 0 0 0 2 13.357a6.46 6.46 0 0 0 1.408 4.024a6.47 6.47 0 0 0 5.162 2.557h12.671a8.36 8.36 0 0 0 6.82-3.515c2.716-3.555 2.416-8.667-.859-11.872");
}

.arf0ribny {
  fill: var(--svg-color--3239ff, #3239FF);
  d: path("m8.789 22.994l-2.39 3.27a1.805 1.805 0 0 1-2.526.393a1.805 1.805 0 0 1-.393-2.524l2.39-3.27a1.805 1.805 0 0 1 2.526-.394c.807.58.983 1.718.393 2.525");
}

.cnnd41gej {
  stop-color: var(--svg-color--627afe, #627AFE);
}

.dkaaooa7z {
  stop-color: var(--svg-color--f2f0ff, #F2F0FF);
}

.ft5dv1b6b {
  fill: none;
}

.i-6d3fbbt {
  stop-color: var(--svg-color--3749ff, #3749FF);
}

.j8isrxrsp {
  d: path("m8.789 22.994l-2.39 3.27a1.805 1.805 0 0 1-2.526.393a1.805 1.805 0 0 1-.393-2.524l2.39-3.27a1.805 1.805 0 0 1 2.526-.394c.807.58.983 1.718.393 2.525");
}

.kqxl2hkqc {
  d: path("M12.367 12.303a4.034 4.034 0 1 0 0-8.068a4.034 4.034 0 0 0 0 8.068");
}

.nh9jgyb1q {
  stop-color: var(--svg-color--b7b6fa, #B7B6FA);
}

.o70hz4bsj {
  stop-color: var(--svg-color--b8b7ff, #B8B7FF);
  stop-opacity: 0;
}

.pwl1_27iu {
  fill: var(--svg-color--3239ff, #3239FF);
  d: path("m15.335 22.994l-2.39 3.27a1.805 1.805 0 0 1-2.525.393a1.805 1.805 0 0 1-.393-2.524l2.39-3.27a1.805 1.805 0 0 1 2.525-.394c.807.58.983 1.718.393 2.525");
}

.q8r289j7a {
  stop-color: var(--svg-color--f2f0ff, #F2F0FF);
  stop-opacity: 0;
}

.r02t0tqck {
  stop-color: var(--svg-color--cecdff, #CECDFF);
}

.stdwivold {
  d: path("m21.881 22.994l-2.39 3.27a1.805 1.805 0 0 1-2.525.393a1.805 1.805 0 0 1-.393-2.524l2.39-3.27a1.805 1.805 0 0 1 2.525-.394c.807.58.983 1.718.393 2.525");
}

.u73dmpbhj {
  d: path("M27.202 4.55c-3.544-3.454-9.216-3.394-12.67.15a8.9 8.9 0 0 0-2.014 3.196a.268.268 0 0 1-.398.13a6 6 0 0 0-.984-.53A6.447 6.447 0 0 0 2 13.357a6.46 6.46 0 0 0 1.408 4.024a6.47 6.47 0 0 0 5.162 2.557h12.671a8.36 8.36 0 0 0 6.82-3.515c2.716-3.555 2.416-8.667-.859-11.872");
}

.ufq42fb7e {
  stop-color: var(--svg-color--d6ccff, #D6CCFF);
  stop-opacity: 0;
}

.vuekx_bhg {
  stop-color: var(--svg-color--d6ccff, #D6CCFF);
}

.x8w3wsxhm {
  d: path("m15.335 22.994l-2.39 3.27a1.805 1.805 0 0 1-2.525.393a1.805 1.805 0 0 1-.393-2.524l2.39-3.27a1.805 1.805 0 0 1 2.525-.394c.807.58.983 1.718.393 2.525");
}

.xwn2jnbkx {
  stop-color: var(--svg-color--b8b7ff, #B8B7FF);
}

.yb9mz6k-w {
  stop-color: var(--svg-color--627afe, #627AFE);
  stop-opacity: 0;
}

.yfxbhhvvc {
  stop-color: var(--svg-color--3364fe, #3364FE);
}

</style>
