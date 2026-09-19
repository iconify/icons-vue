<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixreSEe)"><path fill="url(#iHM71Yc)" class="ckivt1d0h"/></g><g filter="url(#iKvqlsH)"><path class="bs0v7vbsl"/></g><g filter="url(#i3kkbZd)"><path class="il02xmrcj"/></g><g filter="url(#isYBxyb)"><path class="vv_cstb0x"/></g><g filter="url(#i0WA7Me)"><path class="u42i5bc2u"/></g><g filter="url(#i8sJ2Fh)"><path class="q1nrm_26j"/></g><g filter="url(#i4kFuin)"><path class="jn674zezi"/></g><g filter="url(#iUIexNe)"><path fill="url(#iTYl63d)" class="mv8n-qbns"/></g><g filter="url(#ii7CbKc)"><path fill="url(#iEOnWuc)" class="vow2q6b4q"/></g><g filter="url(#iFRFDoL)"><path class="jsc0ann9k"/></g><g filter="url(#iPboD9O)"><path fill="url(#i79QyMM)" class="ddzt_s07l"/></g><g filter="url(#iNEu8Gd)"><path fill="url(#imKcCZR)" class="uc5ihqbkv"/></g><defs><filter id="ixreSEe" width="29.029" height="26.295" x="1.561" y="3.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".45" dy=".3"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.647059 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.501961 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4328" result="effect2_innerShadow_18_4328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_4328" result="effect3_innerShadow_18_4328"/></filter><filter id="iKvqlsH" width="5.381" height="5.381" x="5.417" y="10.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4328" stdDeviation=".25"/></filter><filter id="i3kkbZd" width="5.381" height="5.381" x="11.394" y="6.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4328" stdDeviation=".25"/></filter><filter id="isYBxyb" width="5.381" height="5.381" x="10.902" y="22.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4328" stdDeviation=".25"/></filter><filter id="i0WA7Me" width="5.381" height="5.381" x="5.759" y="17.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4328" stdDeviation=".25"/></filter><filter id="i8sJ2Fh" width="5.381" height="5.381" x="5.837" y="10.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4328" stdDeviation=".25"/></filter><filter id="i4kFuin" width="5.381" height="5.381" x="12.009" y="6.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4328" stdDeviation=".25"/></filter><filter id="iUIexNe" width="5.1" height="4.8" x="11.839" y="6.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.490196 0 0 0 0 0.984314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.258824 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4328" result="effect2_innerShadow_18_4328"/></filter><filter id="ii7CbKc" width="5.1" height="4.8" x="5.839" y="10.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.34902 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.172549 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4328" result="effect2_innerShadow_18_4328"/></filter><filter id="iFRFDoL" width="5.381" height="5.381" x="5.417" y="17.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4328" stdDeviation=".25"/></filter><filter id="iPboD9O" width="5.1" height="4.8" x="5.839" y="17.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.894118 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.533333 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4328" result="effect2_innerShadow_18_4328"/></filter><filter id="iNEu8Gd" width="5.1" height="4.8" x="11.339" y="22.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.752941 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.4 0 0 0 0 0.917647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4328" result="effect2_innerShadow_18_4328"/></filter><linearGradient id="iHM71Yc" x1="24.08" x2="13.725" y1="7.184" y2="29.717" gradientUnits="userSpaceOnUse"><stop class="h1fq8mmjd"/><stop offset="1" class="to1sfgbmo"/></linearGradient><linearGradient id="iTYl63d" x1="13.072" x2="15.139" y1="6.781" y2="11.793" gradientUnits="userSpaceOnUse"><stop class="wu14w2jfa"/><stop offset="1" class="mecyfzb-f"/></linearGradient><linearGradient id="iEOnWuc" x1="7.072" x2="9.139" y1="10.781" y2="15.793" gradientUnits="userSpaceOnUse"><stop class="q-4h4f8pm"/><stop offset="1" class="tw7eprbiy"/></linearGradient><linearGradient id="i79QyMM" x1="7.072" x2="9.139" y1="17.781" y2="22.793" gradientUnits="userSpaceOnUse"><stop class="mo9wgmlaj"/><stop offset="1" class="up7x6vgga"/></linearGradient><linearGradient id="imKcCZR" x1="12.572" x2="14.639" y1="22.281" y2="27.293" gradientUnits="userSpaceOnUse"><stop class="ndq7k_b5i"/><stop offset="1" class="ic5dtjbjm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:artist-palette" /></template>
<style>
.bs0v7vbsl {
  fill: var(--svg-color--cb758c, #CB758C);
  d: path("M8.107 15.344a2.19 2.19 0 1 0 0-4.38a2.19 2.19 0 0 0 0 4.38");
}

.ckivt1d0h {
  d: path("M22.053 6.114C15.279 2.734 7.25 4.039 3.592 9.95S2.263 23.73 8.799 27.523c3.211 1.863 8.395 3.766 10.501 1.228c2.065-2.486-.98-4.06-.27-5.437c1.144-2.213 6.262.69 9.61-2.887c3.771-4.034.008-11.021-6.587-14.313m2.027 12.991c-1.763 0-3.03-1.258-3.03-2.965s1.267-2.964 3.03-2.964s3.03 1.258 3.03 2.964c0 1.707-1.268 2.965-3.03 2.965");
}

.ddzt_s07l {
  d: path("M8.39 22.281a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

.ft5dv1b6b {
  fill: none;
}

.h1fq8mmjd {
  stop-color: var(--svg-color--ffb9a1, #FFB9A1);
}

.ic5dtjbjm {
  stop-color: var(--svg-color--4982fe, #4982FE);
}

.il02xmrcj {
  fill: var(--svg-color--cb758c, #CB758C);
  d: path("M14.084 11.32a2.19 2.19 0 1 0 0-4.38a2.19 2.19 0 0 0 0 4.38");
}

.jn674zezi {
  fill: var(--svg-color--edb88b, #EDB88B);
  d: path("M14.699 10.963a2.19 2.19 0 1 0 0-4.38a2.19 2.19 0 0 0 0 4.38");
}

.jsc0ann9k {
  fill: var(--svg-color--cb758c, #CB758C);
  d: path("M8.107 22.443a2.19 2.19 0 1 0 0-4.38a2.19 2.19 0 0 0 0 4.38");
}

.mecyfzb-f {
  stop-color: var(--svg-color--c950fc, #C950FC);
}

.mo9wgmlaj {
  stop-color: var(--svg-color--47cfa8, #47CFA8);
}

.mv8n-qbns {
  d: path("M14.39 11.281a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

.ndq7k_b5i {
  stop-color: var(--svg-color--49b1f1, #49B1F1);
}

.q-4h4f8pm {
  stop-color: var(--svg-color--f9399f, #F9399F);
}

.q1nrm_26j {
  fill: var(--svg-color--edb88b, #EDB88B);
  d: path("M8.527 14.982a2.19 2.19 0 1 0 0-4.38a2.19 2.19 0 0 0 0 4.38");
}

.to1sfgbmo {
  stop-color: var(--svg-color--ffb4ad, #FFB4AD);
}

.tw7eprbiy {
  stop-color: var(--svg-color--fd328c, #FD328C);
}

.u42i5bc2u {
  fill: var(--svg-color--edb88b, #EDB88B);
  d: path("M8.449 21.951a2.19 2.19 0 1 0 0-4.38a2.19 2.19 0 0 0 0 4.38");
}

.uc5ihqbkv {
  d: path("M13.89 26.781a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

.up7x6vgga {
  stop-color: var(--svg-color--48abeb, #48ABEB);
}

.vow2q6b4q {
  d: path("M8.39 15.281a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

.vv_cstb0x {
  fill: var(--svg-color--cb758c, #CB758C);
  d: path("M13.592 26.951a2.19 2.19 0 1 0 0-4.38a2.19 2.19 0 0 0 0 4.38");
}

.wu14w2jfa {
  stop-color: var(--svg-color--cc67f1, #CC67F1);
}

</style>
