<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVlgNcd)"><path class="w7062yahp"/><path fill="url(#iNYpK4A)" class="amzbaq94h"/></g><g filter="url(#iMSKP0b)"><path class="k79ypbosf"/><path fill="url(#irdRKzd)" class="awxiwqa0g"/></g><g filter="url(#iVfCAoG)"><path class="r_jp-95wi"/><path fill="url(#iVV1nqe)" class="c18vygihu"/></g><g filter="url(#iUFbwbd)"><path class="v9y3cwbhi"/><path fill="url(#iaR154d)" class="n8en-gb9k"/></g><path fill="url(#iPueAEb)" class="l85gygxlr"/><g filter="url(#isMGCXd)"><path class="ge76mjbho"/><path fill="url(#i1aaBXc)" class="rq-r99bya"/><path fill="url(#iPCZgIb)" class="rq-r99bya"/></g><path fill="url(#ixCddOE)" class="qd98uhznz"/><path fill="url(#i423m7d)" class="qd98uhznz"/><g filter="url(#iBe01kb)"><path fill="url(#iy3SZGe)" class="gcigw84di"/></g><g filter="url(#ijgY8QX)"><path stroke="url(#i1JxWUb)" class="azf5fnivx"/></g><defs><radialGradient id="iNYpK4A" cx="0" cy="0" r="1" gradientTransform="rotate(145.744 .551 12.076)scale(2.34511 2.04556)" gradientUnits="userSpaceOnUse"><stop class="cnnd41gej"/><stop offset="1" class="yb9mz6k-w"/></radialGradient><radialGradient id="irdRKzd" cx="0" cy="0" r="1" gradientTransform="rotate(145.744 2.643 14.172)scale(2.34511 2.04556)" gradientUnits="userSpaceOnUse"><stop class="cnnd41gej"/><stop offset="1" class="yb9mz6k-w"/></radialGradient><radialGradient id="iVV1nqe" cx="0" cy="0" r="1" gradientTransform="rotate(145.744 8.601 14.557)scale(2.34511 2.04556)" gradientUnits="userSpaceOnUse"><stop class="cnnd41gej"/><stop offset="1" class="yb9mz6k-w"/></radialGradient><radialGradient id="iaR154d" cx="0" cy="0" r="1" gradientTransform="rotate(145.744 10.693 16.653)scale(2.34511 2.04556)" gradientUnits="userSpaceOnUse"><stop class="cnnd41gej"/><stop offset="1" class="yb9mz6k-w"/></radialGradient><radialGradient id="iPueAEb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07567 2.53665 -2.1672 -2.6277 13.437 5.75)" gradientUnits="userSpaceOnUse"><stop class="ygxk8pisy"/><stop offset="1" class="hfeh_12ol"/></radialGradient><radialGradient id="i1aaBXc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79375 6.77898 -4.2607 -3.01295 14.318 19.572)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="n8gwj7wbw"/><stop offset="1" class="n9cycih6m"/></radialGradient><radialGradient id="iPCZgIb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.97516 4.1976 -3.96355 -3.75352 9.819 11.065)" gradientUnits="userSpaceOnUse"><stop class="e0_i6gb8s"/><stop offset="1" class="iqsf78bkf"/></radialGradient><radialGradient id="ixCddOE" cx="0" cy="0" r="1" gradientTransform="rotate(142.503 11.128 7.751)scale(10.9332 11.9987)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="smegbduug"/><stop offset="1" class="y6cndpbec"/></radialGradient><radialGradient id="i423m7d" cx="0" cy="0" r="1" gradientTransform="rotate(170.656 10 6.018)scale(19.0964 16.315)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="i1w9labfr"/><stop offset="1" class="vt77dwb8m"/></radialGradient><filter id="iVlgNcd" width="6.404" height="6.754" x="2" y="20.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.256493 0 0 0 0 0.282719 0 0 0 0 0.741667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15029"/></filter><filter id="iMSKP0b" width="6.404" height="6.754" x="7" y="23.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.256493 0 0 0 0 0.282719 0 0 0 0 0.741667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15029"/></filter><filter id="iVfCAoG" width="6.404" height="6.754" x="18.1" y="20.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.256493 0 0 0 0 0.282719 0 0 0 0 0.741667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15029"/></filter><filter id="iUFbwbd" width="6.404" height="6.754" x="23.1" y="23.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.256493 0 0 0 0 0.282719 0 0 0 0 0.741667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15029"/></filter><filter id="isMGCXd" width="29" height="19.876" x="1.957" y=".127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.12549 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15029"/></filter><filter id="iBe01kb" width="7.832" height="13.586" x="12.278" y="13.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.908333 0 0 0 0 0.312137 0 0 0 0 0.0454167 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15029"/></filter><filter id="ijgY8QX" width="4.34" height="7.487" x="10.707" y="7.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15029" stdDeviation=".5"/></filter><linearGradient id="iy3SZGe" x1="16.035" x2="16.035" y1="12.613" y2="25.811" gradientUnits="userSpaceOnUse"><stop offset=".354" class="l8mma5brs"/><stop offset="1" class="nybym1b4j"/></linearGradient><linearGradient id="i1JxWUb" x1="12.284" x2="14.124" y1="10.323" y2="15.843" gradientUnits="userSpaceOnUse"><stop class="u28ir3caf"/><stop offset="1" class="jqxw1h_mj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cloud-with-lightning-and-rain" /></template>
<style>
.amzbaq94h {
  d: path("m7.467 23.473l-2.31 3.16c-.57.78-1.66.95-2.44.38s-.95-1.66-.38-2.44l2.31-3.16c.57-.78 1.66-.95 2.44-.38s.95 1.66.38 2.44");
}

.awxiwqa0g {
  d: path("m12.467 26.123l-2.31 3.16c-.57.78-1.66.95-2.44.38s-.95-1.66-.38-2.44l2.31-3.16c.57-.78 1.66-.95 2.44-.38c.78.56.95 1.66.38 2.44");
}

.azf5fnivx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.957 9.113c.597.694 1.801 2.663 1.84 4.987");
}

.c18vygihu {
  d: path("m23.567 23.473l-2.31 3.16c-.57.78-1.66.95-2.44.38s-.95-1.66-.38-2.44l2.31-3.16c.57-.78 1.66-.95 2.44-.38s.95 1.66.38 2.44");
}

.cnnd41gej {
  stop-color: var(--svg-color--627afe, #627AFE);
}

.e0_i6gb8s {
  stop-color: var(--svg-color--574adf, #574ADF);
}

.ft5dv1b6b {
  fill: none;
}

.gcigw84di {
  d: path("m19.542 19.625l-4.852 7.279a.4.4 0 0 1-.733-.222v-5.28a.4.4 0 0 0-.4-.4h-.878a.4.4 0 0 1-.34-.611l3.879-6.205c.213-.341.739-.19.739.212v4.205c0 .22.18.4.4.4h1.853a.4.4 0 0 1 .332.622");
}

.ge76mjbho {
  fill: var(--svg-color--3124c5, #3124C5);
  d: path("M29.957 10.994c0 4.976-4.03 9.009-9 9.009H8.561c-3.648 0-6.604-3.072-6.604-6.506s2.897-6.432 6.545-6.432c.733 0 1.822.266 2.723.614c.67.258 1.57-.064 1.89-.706c1.386-2.773 4.27-4.846 7.868-4.846c4.97 0 8.974 3.892 8.974 8.867");
}

.hfeh_12ol {
  stop-color: var(--svg-color--35209b, #35209B);
}

.i1w9labfr {
  stop-color: var(--svg-color--35209a, #35209A);
  stop-opacity: 0;
}

.iqsf78bkf {
  stop-color: var(--svg-color--574adf, #574ADF);
  stop-opacity: 0;
}

.jqxw1h_mj {
  stop-color: var(--svg-color--554bd3, #554BD3);
  stop-opacity: 0;
}

.k79ypbosf {
  fill: var(--svg-color--535dff, #535DFF);
  d: path("m12.467 26.123l-2.31 3.16c-.57.78-1.66.95-2.44.38s-.95-1.66-.38-2.44l2.31-3.16c.57-.78 1.66-.95 2.44-.38c.78.56.95 1.66.38 2.44");
}

.l85gygxlr {
  d: path("M12.457 12.003a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.l8mma5brs {
  stop-color: var(--svg-color--ff9b49, #FF9B49);
}

.n8en-gb9k {
  d: path("m28.567 26.123l-2.31 3.16c-.57.78-1.66.95-2.44.38s-.95-1.66-.38-2.44l2.31-3.16c.57-.78 1.66-.95 2.44-.38c.78.56.95 1.66.38 2.44");
}

.n8gwj7wbw {
  stop-color: var(--svg-color--381b90, #381B90);
}

.n9cycih6m {
  stop-color: var(--svg-color--381b90, #381B90);
  stop-opacity: 0;
}

.nybym1b4j {
  stop-color: var(--svg-color--ff4e4b, #FF4E4B);
}

.qd98uhznz {
  d: path("M30 10.994c0 4.976-4.03 9.009-9 9.009H8.604C4.956 20.003 2 16.93 2 13.497s2.897-6.432 6.545-6.432c.733 0 1.822.266 2.723.614c.67.258 1.57-.064 1.89-.706c1.386-2.773 4.27-4.846 7.867-4.846c4.971 0 8.975 3.892 8.975 8.867");
}

.r_jp-95wi {
  fill: var(--svg-color--535dff, #535DFF);
  d: path("m23.567 23.473l-2.31 3.16c-.57.78-1.66.95-2.44.38s-.95-1.66-.38-2.44l2.31-3.16c.57-.78 1.66-.95 2.44-.38s.95 1.66.38 2.44");
}

.rq-r99bya {
  d: path("M29.957 10.994c0 4.976-4.03 9.009-9 9.009H8.561c-3.648 0-6.604-3.072-6.604-6.506s2.897-6.432 6.545-6.432c.733 0 1.822.266 2.723.614c.67.258 1.57-.064 1.89-.706c1.386-2.773 4.27-4.846 7.868-4.846c4.97 0 8.974 3.892 8.974 8.867");
}

.smegbduug {
  stop-color: var(--svg-color--6051ff, #6051FF);
}

.u28ir3caf {
  stop-color: var(--svg-color--554bd3, #554BD3);
}

.v9y3cwbhi {
  fill: var(--svg-color--535dff, #535DFF);
  d: path("m28.567 26.123l-2.31 3.16c-.57.78-1.66.95-2.44.38s-.95-1.66-.38-2.44l2.31-3.16c.57-.78 1.66-.95 2.44-.38c.78.56.95 1.66.38 2.44");
}

.vt77dwb8m {
  stop-color: var(--svg-color--35209a, #35209A);
}

.w7062yahp {
  fill: var(--svg-color--535dff, #535DFF);
  d: path("m7.467 23.473l-2.31 3.16c-.57.78-1.66.95-2.44.38s-.95-1.66-.38-2.44l2.31-3.16c.57-.78 1.66-.95 2.44-.38s.95 1.66.38 2.44");
}

.y6cndpbec {
  stop-color: var(--svg-color--6051ff, #6051FF);
  stop-opacity: 0;
}

.yb9mz6k-w {
  stop-color: var(--svg-color--627afe, #627AFE);
  stop-opacity: 0;
}

.ygxk8pisy {
  stop-color: var(--svg-color--4c42d7, #4C42D7);
}

</style>
