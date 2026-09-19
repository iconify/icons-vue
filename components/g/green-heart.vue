<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igwHOnb)" class="jeyxs9max"/><path fill="url(#i4T0ZPr)" class="jeyxs9max"/><path fill="url(#iOrCJ9f)" class="jeyxs9max"/><path fill="url(#ieo9ghd)" class="jeyxs9max"/><path fill="url(#isQasTc)" class="jeyxs9max"/><path fill="url(#iPWT4je)" class="jeyxs9max"/><path fill="url(#izwp7Cb)" class="jeyxs9max"/><path fill="url(#iA8DDVc)" class="jeyxs9max"/><path fill="url(#iagkC0j)" class="jeyxs9max"/><g filter="url(#iAXXmLB)"><path class="f1t_u6d4k"/></g><g filter="url(#iRc33Qc)"><path fill="url(#i42XdnC)" class="jbvotob3m"/></g><g filter="url(#ik6OJms)"><path fill="url(#iO6C4Vc)" class="m-g7nzfpm"/></g><g filter="url(#iJxEjJM)"><path stroke="url(#iLXdCWc)" class="oyny_bbpp"/></g><g filter="url(#ipIQzze)"><path stroke="url(#ioYlvTc)" class="nabv_9bzw"/></g><defs><radialGradient id="igwHOnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 25.0559 -26.6012 0 15.77 5.634)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="ogu7p-bve"/><stop offset=".528" class="fywwz6bsh"/><stop offset="1" class="p_cnv6och"/></radialGradient><radialGradient id="i4T0ZPr" cx="0" cy="0" r="1" gradientTransform="rotate(-57.293 33.282 3.665)scale(30.305 28.3828)" gradientUnits="userSpaceOnUse"><stop offset=".801" class="udfox1bay"/><stop offset="1" class="z8ubgsbom"/></radialGradient><radialGradient id="isQasTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 26.6875 -33.0073 0 15.895 6.064)" gradientUnits="userSpaceOnUse"><stop offset=".733" class="tcuq1pbcv"/><stop offset=".895" class="sqbadjp-q"/></radialGradient><radialGradient id="iPWT4je" cx="0" cy="0" r="1" gradientTransform="matrix(-11.74996 10.8126 -15.86844 -17.2441 19.965 13.377)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="tcuq1pbcv"/><stop offset="1" class="sqbadjp-q"/></radialGradient><radialGradient id="izwp7Cb" cx="0" cy="0" r="1" gradientTransform="matrix(-20.12509 -26.99987 27.39507 -20.41966 19.465 27.69)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="b9roqeblx"/><stop offset="1" class="ms2gx5bti"/></radialGradient><radialGradient id="iA8DDVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.499 -19.705 0 15.447 13.815)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="ty4rkq75w"/><stop offset=".934" class="f9x795bms"/></radialGradient><radialGradient id="iagkC0j" cx="0" cy="0" r="1" gradientTransform="scale(17.6425 17.499)rotate(90 .043 .833)" gradientUnits="userSpaceOnUse"><stop offset=".864" class="lgj684bwi"/><stop offset=".934" class="s_fh1vp_g"/></radialGradient><radialGradient id="i42XdnC" cx="0" cy="0" r="1" gradientTransform="rotate(113.398 11.914 11.344)scale(15.0883 5.91581)" gradientUnits="userSpaceOnUse"><stop class="cq41albgj"/><stop offset="1" class="tiw25e7hn"/></radialGradient><radialGradient id="iO6C4Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.68755 -6.56244 11.64945 -11.87155 16.402 11.877)" gradientUnits="userSpaceOnUse"><stop class="vg4denhed"/><stop offset="1" class="t5da73evv"/></radialGradient><filter id="iAXXmLB" width="7.923" height="12.608" x="13.795" y="7.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6094" stdDeviation="1"/></filter><filter id="iRc33Qc" width="14.114" height="17.881" x="15.894" y="5.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6094" stdDeviation=".75"/></filter><filter id="ik6OJms" width="12.852" height="19.394" x="5.192" y="3.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6094" stdDeviation="1.5"/></filter><filter id="iJxEjJM" width="8.292" height="5.6" x="20.706" y="5.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6094" stdDeviation=".5"/></filter><filter id="ipIQzze" width="8.649" height="5.715" x="7.316" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6094" stdDeviation=".5"/></filter><linearGradient id="iOrCJ9f" x1="17.632" x2="25.645" y1="16.133" y2="25.668" gradientUnits="userSpaceOnUse"><stop offset=".694" class="ty4rkq75w"/><stop offset=".934" class="f9x795bms"/></linearGradient><linearGradient id="ieo9ghd" x1="16.639" x2="7.152" y1="16.53" y2="26.439" gradientUnits="userSpaceOnUse"><stop offset=".694" class="ty4rkq75w"/><stop offset=".885" class="ng7qjmgwq"/></linearGradient><linearGradient id="iLXdCWc" x1="26.46" x2="23.806" y1="8.131" y2="6.792" gradientUnits="userSpaceOnUse"><stop class="cq41albgj"/><stop offset="1" class="tiw25e7hn"/></linearGradient><linearGradient id="ioYlvTc" x1="13.069" x2="10.415" y1="8.156" y2="6.818" gradientUnits="userSpaceOnUse"><stop class="cq41albgj"/><stop offset="1" class="tiw25e7hn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:green-heart" /></template>
<style>
.b9roqeblx {
  stop-color: var(--svg-color--409157, #409157);
  stop-opacity: 0;
}

.cq41albgj {
  stop-color: var(--svg-color--48ff90, #48FF90);
}

.f1t_u6d4k {
  fill: var(--svg-color--2ebc6f, #2EBC6F);
  d: path("M15.795 10.54v6.823c0 .905 1.096 1.334 1.66.627c1.745-2.19 3.153-4.851 1.582-7.025c-.602-.834-1.756-1.368-2.699-1.198c-.353.063-.543.415-.543.774");
}

.f9x795bms {
  stop-color: var(--svg-color--8590ce, #8590CE);
}

.ft5dv1b6b {
  fill: none;
}

.fywwz6bsh {
  stop-color: var(--svg-color--40b98a, #40B98A);
}

.jbvotob3m {
  d: path("M25.908 6.91c2.598 1.07 3.38 5.152 1.747 9.12c-1.632 3.966-5.062 6.315-7.66 5.245s-3.38-5.152-1.748-9.118C19.88 8.19 23.31 5.84 25.907 6.91");
}

.jeyxs9max {
  d: path("M15.104 29.202a1.73 1.73 0 0 0 1.71-.023c3.584-2.047 9.81-6.761 12.255-12.884c3.59-7.973-4.838-14.337-10.662-9.76c-.608.478-1.372 1.025-1.897 1.542c-.238.234-.657.258-.904.034c-.69-.63-1.771-1.436-2.465-1.905c-4.965-3.36-14 1.069-10.146 10.52c1.412 4.242 8.14 10.26 12.11 12.476");
}

.lgj684bwi {
  stop-color: var(--svg-color--adb6e8, #ADB6E8);
  stop-opacity: 0;
}

.m-g7nzfpm {
  d: path("m14.84 9.846l.205 10.366C8.17 13.525 6.939 8.734 9.277 7.127c1.67-1.147 4.813 1.156 5.563 2.719");
}

.ms2gx5bti {
  stop-color: var(--svg-color--409157, #409157);
}

.nabv_9bzw {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.44 6.413c1.087-.135 4.025 0 6.4 3.433");
}

.ng7qjmgwq {
  stop-color: var(--svg-color--7e8de2, #7E8DE2);
}

.ogu7p-bve {
  stop-color: var(--svg-color--31c66a, #31C66A);
}

.oyny_bbpp {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.831 6.388c1.087-.135 4.786.121 6.042 3.322");
}

.p_cnv6och {
  stop-color: var(--svg-color--43a395, #43A395);
}

.s_fh1vp_g {
  stop-color: var(--svg-color--adb6e8, #ADB6E8);
}

.sqbadjp-q {
  stop-color: var(--svg-color--408b91, #408B91);
}

.t5da73evv {
  stop-color: var(--svg-color--68ec9c, #68EC9C);
  stop-opacity: 0;
}

.tcuq1pbcv {
  stop-color: var(--svg-color--408b91, #408B91);
  stop-opacity: 0;
}

.tiw25e7hn {
  stop-color: var(--svg-color--48ff90, #48FF90);
  stop-opacity: 0;
}

.ty4rkq75w {
  stop-color: var(--svg-color--8590ce, #8590CE);
  stop-opacity: 0;
}

.udfox1bay {
  stop-color: var(--svg-color--5be689, #5BE689);
  stop-opacity: 0;
}

.vg4denhed {
  stop-color: var(--svg-color--80f2ad, #80F2AD);
}

.z8ubgsbom {
  stop-color: var(--svg-color--5be689, #5BE689);
}

</style>
