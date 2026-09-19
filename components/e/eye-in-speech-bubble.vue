<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":33};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#iWhb6Dd)"><path fill="url(#iaAOIge)" class="safhatbpj"/><path fill="url(#iDWuGhd)" class="safhatbpj"/><path fill="url(#i41IQwd)" class="safhatbpj"/><circle fill="url(#isaLSbO)" class="y71ragb-b"/><g filter="url(#ioh9d5b)"><circle class="jpu6ek95u"/></g><circle fill="url(#iQ9N7Wc)" class="ryzdhbc3u"/><circle fill="url(#iMx5pAo)" class="gt9n2rb-x"/><g filter="url(#iT8ANQe)"><ellipse fill="url(#ioZHxUd)" class="b4hlmlwqc"/></g><g filter="url(#i4X2AEe)"><path fill="url(#igqi3yd)" class="wkftstd0d"/></g><g filter="url(#iEpR01c)"><path stroke="url(#i4xzdFe)" class="u3s2o6cay"/></g><g filter="url(#iA4NVAc)"><path stroke="url(#iZWNUpb)" class="hgyql7b_v"/></g><g filter="url(#iwOzdTf)"><path class="nmeooibxp"/></g></g><defs><radialGradient id="iaAOIge" cx="0" cy="0" r="1" gradientTransform="matrix(9.375 14.37498 -26.96945 17.58881 9.146 9.751)" gradientUnits="userSpaceOnUse"><stop class="mfvv18_rc"/><stop offset="1" class="bbr1e9b7u"/></radialGradient><radialGradient id="iDWuGhd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.6875 0 0 -14.6875 31.896 20.689)" gradientUnits="userSpaceOnUse"><stop class="mfvv18_rc"/><stop offset="1" class="nzcjz1_ju"/></radialGradient><radialGradient id="i41IQwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -15.375 16.4794 0 16 22.314)" gradientUnits="userSpaceOnUse"><stop offset=".886" class="ixznv_d7y"/><stop offset="1" class="cv8bm4f9o"/></radialGradient><radialGradient id="iQ9N7Wc" cx="0" cy="0" r="1" gradientTransform="matrix(4.25 7.03374 -11.98684 7.24283 12.52 13.967)" gradientUnits="userSpaceOnUse"><stop class="mfvv18_rc"/><stop offset="1" class="bbr1e9b7u"/></radialGradient><radialGradient id="iMx5pAo" cx="0" cy="0" r="1" gradientTransform="rotate(136.052 8.275 10.862)scale(8.01506 5.71056)" gradientUnits="userSpaceOnUse"><stop class="jntpc8b7b"/><stop offset="1" class="ovvoeobvj"/></radialGradient><radialGradient id="ioZHxUd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.79584 0 0 -3.20501 24.315 15.738)" gradientUnits="userSpaceOnUse"><stop class="ftjpyzszu"/><stop offset="1" class="ovvoeobvj"/></radialGradient><filter id="ioh9d5b" width="9.661" height="9.661" x="10.482" y="14.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7161_6142" stdDeviation=".5"/></filter><filter id="iT8ANQe" width="16.593" height="12.969" x="15.521" y="10.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7161_6142" stdDeviation="1.5"/></filter><filter id="i4X2AEe" width="3.75" height="6.078" x="21.677" y="23.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7161_6142" stdDeviation=".5"/></filter><filter id="iEpR01c" width="5.16" height="3.313" x="19.8" y="24.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7161_6142" stdDeviation=".25"/></filter><filter id="iA4NVAc" width="13.655" height="3.344" x="7.498" y="24.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7161_6142" stdDeviation=".25"/></filter><filter id="iwOzdTf" width="2.127" height="1.949" x="23.422" y="23.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7161_6142" stdDeviation=".25"/></filter><linearGradient id="isaLSbO" x1="11.208" x2="18.021" y1="11.814" y2="25.064" gradientUnits="userSpaceOnUse"><stop class="cw8ffmxww"/><stop offset="1" class="yt0sjmb1z"/></linearGradient><linearGradient id="igqi3yd" x1="23.333" x2="24.614" y1="26.032" y2="30.22" gradientUnits="userSpaceOnUse"><stop class="qn8c28egg"/><stop offset="1" class="irvroob3d"/></linearGradient><linearGradient id="i4xzdFe" x1="24.55" x2="20.855" y1="25.536" y2="27.857" gradientUnits="userSpaceOnUse"><stop class="hrf30wbsg"/><stop offset=".292" class="pauktrpwf"/><stop offset=".74" class="pauktrpwf"/><stop offset="1" class="hrf30wbsg"/></linearGradient><linearGradient id="iZWNUpb" x1="19.599" x2="11.177" y1="27.236" y2="27.642" gradientUnits="userSpaceOnUse"><stop class="t4a7m7b2g"/><stop offset="1" class="kaekg9zrt"/></linearGradient><clipPath id="iWhb6Dd"><path class="l3k60l-up"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:eye-in-speech-bubble" /></template>
<style>
.b4hlmlwqc {
  cx: 23.817px;
  cy: 16.704px;
  rx: 5.296px;
  ry: 3.484px;
}

.bbr1e9b7u {
  stop-color: var(--svg-color--573561, #573561);
}

.cv8bm4f9o {
  stop-color: var(--svg-color--72667b, #72667B);
}

.cw8ffmxww {
  stop-color: var(--svg-color--dcdbdf, #DCDBDF);
}

.ft5dv1b6b {
  fill: none;
}

.ftjpyzszu {
  stop-color: var(--svg-color--dad8dd, #DAD8DD);
  stop-opacity: 0.5;
}

.gt9n2rb-x {
  cx: 16px;
  cy: 17.798px;
  r: 3.831px;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
}

.hgyql7b_v {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.052 25.126c4 2.563 9.962 2.56 12.562 1.46");
}

.hrf30wbsg {
  stop-color: var(--svg-color--312343, #312343);
  stop-opacity: 0;
}

.irvroob3d {
  stop-color: var(--svg-color--6d5b76, #6D5B76);
  stop-opacity: 0;
}

.ixznv_d7y {
  stop-color: var(--svg-color--72667b, #72667B);
  stop-opacity: 0;
}

.jntpc8b7b {
  stop-color: var(--svg-color--dad8dd, #DAD8DD);
}

.jpu6ek95u {
  cx: 15.313px;
  cy: 18.903px;
  r: 3.831px;
  fill: var(--svg-color--c9c5cc, #C9C5CC);
}

.kaekg9zrt {
  stop-color: var(--svg-color--865994, #865994);
  stop-opacity: 0;
}

.l3k60l-up {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 .001h32v32H0z");
}

.mfvv18_rc {
  stop-color: var(--svg-color--3b3444, #3B3444);
}

.nmeooibxp {
  stroke: var(--svg-color--9d86a5, #9D86A5);
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M24.974 24.267c-.125.14-.578.539-1 .797");
}

.nzcjz1_ju {
  stop-color: var(--svg-color--3d3446, #3D3446);
  stop-opacity: 0;
}

.ovvoeobvj {
  stop-color: var(--svg-color--dad8dd, #DAD8DD);
  stop-opacity: 0;
}

.pauktrpwf {
  stop-color: var(--svg-color--312343, #312343);
}

.qn8c28egg {
  stop-color: var(--svg-color--6d5b76, #6D5B76);
}

.ryzdhbc3u {
  cx: 16px;
  cy: 17.798px;
  r: 3.831px;
}

.safhatbpj {
  d: path("M29.599 16.517C27.88 12.689 23.314 8 16.146 8C8.957 8 4.399 12.202 2.458 16.266c-.47.985-.383 2.514.125 3.375c1.813 3.75 6.347 7.984 13.516 7.984c.96 0 1.934-.106 2.81-.257a2.07 2.07 0 0 1 1.332.2c1.165.624 2.337 1.301 3.831 2.14c.459.257.854-.027.824-.552l-.227-3.416a1.54 1.54 0 0 1 .62-1.327c2.104-1.579 2.888-2.607 4.075-4.522c.529-.851.657-2.328.235-3.375");
}

.t4a7m7b2g {
  stop-color: var(--svg-color--865994, #865994);
}

.u3s2o6cay {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.425 27.126c.458-.215 1.882-.928 3.91-2.062");
}

.wkftstd0d {
  d: path("m22.677 26.439l1.75 2.578l-.25-4.078z");
}

.y71ragb-b {
  cx: 16px;
  cy: 17.798px;
  r: 6.641px;
}

.yt0sjmb1z {
  stop-color: var(--svg-color--d4d0d7, #D4D0D7);
}

</style>
