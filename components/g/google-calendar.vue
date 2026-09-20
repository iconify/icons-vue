<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":275};
const content = `<defs><linearGradient id="SVGAUTqNcwQ" x1="83" x2="83" y1="76" gradientUnits="userSpaceOnUse"><stop class="iban0vj3k"/><stop offset="1" class="h_b_e_04y"/></linearGradient><linearGradient id="SVGMJemac7b" x1="89.06" x2="89.06" y1="21.75" y2="96.39" gradientUnits="userSpaceOnUse"><stop class="brbf7obdx"/><stop offset=".8" class="iohm7z9kg"/></linearGradient><filter id="SVGGQyK4bRj" width="152" height="112" x="20" y="-4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_37330_7673" stdDeviation="6"/></filter></defs><mask id="SVGcTVVObIw" width="154" height="152" x="19" y="20" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="pxfan8-cg"/></mask><mask id="SVGBwV4Xb4k" width="154" height="152" x="19" y="20" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="jer0_fhzl"/></mask><path class="d7e7a-whb"/><path class="hjvxbh6xp"/><g mask="url(#SVGcTVVObIw)" transform="translate(-32.775 -13.56)scale(1.67495)"><path fill="url(#SVGAUTqNcwQ)" transform="matrix(1 0 0 -1 13 172)" class="jjt_r1brb"/></g><g mask="url(#SVGBwV4Xb4k)" transform="translate(-32.775 -13.56)scale(1.67495)"><path fill="url(#SVGMJemac7b)" filter="url(#SVGGQyK4bRj)" class="jmc1wdrms"/></g><path class="hc3__ubbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-calendar" /></template>
<style>
.brbf7obdx {
  stop-color: var(--svg-color--a9a8ff, #a9a8ff);
}

.d7e7a-whb {
  fill: var(--svg-color--bbe2ff, #bbe2ff);
  d: path("M20.824 48.078c0-26.641 21.596-48.239 48.238-48.239h117.917c26.641 0 48.238 21.598 48.238 48.239v50.918c0 26.641-21.597 48.239-48.238 48.239H69.062c-26.642 0-48.238-21.598-48.238-48.239z");
}

.h_b_e_04y {
  stop-color: var(--svg-color--3186ff, #3186ff);
}

.hc3__ubbr {
  fill: var(--svg-color--fff, #fff);
  d: path("M93.438 209.77q-10.521 0-18.051-3.421q-7.528-3.422-12.746-9.153q-5.133-5.82-7.273-11.379q-2.137-5.558-1.711-6.758a3.47 3.47 0 0 1 1.711-1.882l9.497-3.765q1.196-.598 2.395-.17q1.196.34 2.822 3.935q1.714 3.592 4.79 7.613a24 24 0 0 0 7.529 6.245q4.368 2.226 10.779 2.225q10.351 0 16.426-5.99q6.16-5.986 6.16-15.226q0-10.01-6.503-15.4q-6.5-5.476-17.195-5.476h-8.981a3.17 3.17 0 0 1-2.225-.853q-.853-.94-.855-2.139v-9.153q0-1.284.854-2.14a3.06 3.06 0 0 1 2.226-.94h7.783q9.583 0 15.4-5.22q5.817-5.218 5.816-13.517q.002-8.21-5.218-13.258t-14.371-5.049q-5.135.001-8.898 1.712a19.3 19.3 0 0 0-6.502 4.791a38.3 38.3 0 0 0-4.705 6.33q-1.964 3.252-3.165 3.593q-1.195.256-2.31-.426l-8.983-4.364q-1.11-.599-1.454-1.882q-.342-1.284 2.055-5.989q2.48-4.788 7.526-9.752a35.2 35.2 0 0 1 11.807-7.7q6.758-2.74 15.741-2.738q16.681.001 26.434 8.81q9.752 8.73 9.753 23.099q0 9.926-4.79 17.196q-4.706 7.27-13.347 10.268v.341q10.438 3.08 16.425 11.291c4.05 5.421 6.075 11.891 6.074 19.419q0 16.17-11.293 26.522q-11.29 10.35-29.429 10.35zm85.841-1.967q-1.452 0-2.567-1.112a3.78 3.78 0 0 1-1.026-2.652v-95.131l-19.249 13.859q-1.026.77-2.396.514a3.3 3.3 0 0 1-2.052-1.283l-5.561-7.871a3.32 3.32 0 0 1-.6-2.397q.258-1.365 1.369-2.136l34.133-24.382q.43-.343.942-.514q.515-.256 1.197-.256h7.188q1.455.001 2.31 1.027q.941.94.941 2.396v116.174q0 1.542-1.112 2.652a3.35 3.35 0 0 1-2.568 1.112z");
}

.hjvxbh6xp {
  fill: var(--svg-color--3c90ff, #3c90ff);
  d: path("M.502 69.169c-3.432-26.082 16.871-49.23 43.177-49.23h168.683c26.306 0 46.609 23.148 43.178 49.23l-10.273 78.066l10.273 78.066c3.431 26.082-16.872 49.23-43.178 49.23H43.679c-26.307 0-46.609-23.148-43.177-49.23l10.272-78.066z");
}

.iban0vj3k {
  stop-color: var(--svg-color--4fa0ff, #4fa0ff);
}

.iohm7z9kg {
  stop-color: var(--svg-color--3c90ff, #3c90ff);
}

.jer0_fhzl {
  fill: var(--svg-color--3186ff, #3186ff);
  d: path("M19.867 49.392C17.818 33.82 29.94 20 45.645 20h100.71c15.706 0 27.827 13.82 25.778 29.392L166 96l6.133 46.608C174.182 158.18 162.061 172 146.355 172H45.645c-15.706 0-27.827-13.82-25.778-29.392L26 96z");
}

.jjt_r1brb {
  d: path("M0 0h166v76H0z");
}

.jmc1wdrms {
  d: path("M32 27.2C32 16.596 40.596 8 51.2 8h89.6c10.604 0 19.2 8.596 19.2 19.2V96H32z");
}

.pxfan8-cg {
  fill: var(--svg-color--3c90ff, #3c90ff);
  d: path("M19.867 49.392C17.818 33.82 29.94 20 45.645 20h100.71c15.706 0 27.827 13.82 25.778 29.392L166 96l6.133 46.608C174.182 158.18 162.061 172 146.355 172H45.645c-15.706 0-27.827-13.82-25.778-29.392L26 96z");
}

</style>
