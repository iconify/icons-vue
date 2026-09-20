<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":326};
const content = `<defs><linearGradient id="SVGSFuzrdRn" x1="71.83" x2="156.83" y1="148" y2="8" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ovzu8acsw"/><stop offset=".48" class="ec3_jrqjm"/><stop offset=".86" class="zl05wtblf"/></linearGradient><linearGradient id="SVGHMZrMdqY" x1="96" x2="96" y1="140.04" y2="8" gradientUnits="userSpaceOnUse"><stop offset=".16" class="ovzu8acsw"/><stop offset=".64" class="s5swet9dp"/><stop offset=".96" class="zl05wtblf"/></linearGradient><linearGradient id="SVGPFCCTc3o" x1="96" x2="96" y1="51.19" y2="142.89" gradientUnits="userSpaceOnUse"><stop offset=".11" class="izd448b_p"/><stop offset=".68" class="oh10ogb5s"/></linearGradient><filter id="SVG5GnBoe9J" width="203.2" height="235.2" x="-5.6" y="6.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_37487_16896" stdDeviation="28.8"/></filter><filter id="SVGjLHLue4y" width="88" height="140" x="52" y="58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_37487_16896" stdDeviation="6"/></filter></defs><mask id="SVGBYXnUdIs" width="140" height="140" x="26" y="8" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path fill="url(#SVGSFuzrdRn)" class="u3jhowmsd"/></mask><g mask="url(#SVGBYXnUdIs)" transform="translate(-47.543 -14.629)scale(1.82857)"><circle fill="url(#SVGHMZrMdqY)" class="ywj5b4b-q"/><g filter="url(#SVG5GnBoe9J)"><path class="bmr5_ccey"/></g><g filter="url(#SVGjLHLue4y)"><path fill="url(#SVGPFCCTc3o)" class="zc_jdjbig"/></g><path class="quihk6s6u"/></g><g mask="url(#SVGIRatfbNq)" transform="translate(-47.543 -14.629)scale(1.82857)"><path class="itlg5wbqi"/></g><mask id="SVGIRatfbNq" width="80" height="46" x="56" y="140" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="q6vnxhtol"/></mask>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-keep" /></template>
<style>
.bmr5_ccey {
  fill: var(--svg-color--fdfd6d, #fdfd6d);
  d: path("M52 124c0-38.137 14.81-60 44-60s44 21.863 44 60c0 33.137-19.699 60-44 60s-44-26.863-44-60");
}

.ec3_jrqjm {
  stop-color: var(--svg-color--fdd313, #fdd313);
}

.itlg5wbqi {
  fill: var(--svg-color--f6a100, #f6a100);
  d: path("M96 56c-18.4 0-32 14.4-32 33.6v62.8c0 19.2 13.6 33.6 32 33.6s32-14.4 32-33.6V89.6C128 70.4 114.4 56 96 56");
}

.izd448b_p {
  stop-color: var(--svg-color--ffb8dd, #ffb8dd);
  stop-opacity: 0;
}

.oh10ogb5s {
  stop-color: var(--svg-color--ffb5e8, #ffb5e8);
}

.ovzu8acsw {
  stop-color: var(--svg-color--ffe921, #ffe921);
}

.q6vnxhtol {
  fill: var(--svg-color--ffbe00, #ffbe00);
  d: path("M56 140h80v46H56z");
}

.quihk6s6u {
  fill: var(--svg-color--fff, #fff);
  d: path("M78 127c0-7.18 5.82-13 13-13h10c7.18 0 13 5.82 13 13s-5.82 13-13 13H91c-7.18 0-13-5.82-13-13");
}

.s5swet9dp {
  stop-color: var(--svg-color--fec700, #fec700);
}

.u3jhowmsd {
  d: path("M166 78c0 27.13-15.434 50.381-38 62c-9.591 4.938-20.47 8-32 8s-22.41-3.062-32-8c-22.566-11.619-38-34.87-38-62C26 39.34 57.34 8 96 8s70 31.34 70 70");
}

.ywj5b4b-q {
  cx: 96px;
  cy: 78px;
  r: 70px;
}

.zc_jdjbig {
  d: path("M64 102c0-17.673 14.327-32 32-32s32 14.327 32 32v52c0 17.673-14.327 32-32 32s-32-14.327-32-32z");
}

.zl05wtblf {
  stop-color: var(--svg-color--ffbe00, #ffbe00);
}

</style>
