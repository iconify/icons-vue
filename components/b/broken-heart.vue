<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iOsiCkc)" class="nlcb38bpp"/><path fill="url(#ijeQ6gc)" class="nlcb38bpp"/><path fill="url(#iXwv3mc)" class="nlcb38bpp"/><path fill="url(#iNQCaoe)" class="nlcb38bpp"/><path fill="url(#i1HWN8b)" class="vpwfny5mj"/><path fill="url(#i6gqirT)" class="vpwfny5mj"/><path fill="url(#i1v8CBc)" class="vpwfny5mj"/><path fill="url(#ioxCtGc)" class="vpwfny5mj"/><g filter="url(#i87Oogq)"><ellipse fill="url(#iEolPLe)" transform="rotate(41.528 24.453 12.672)" class="id0-6-b7y"/></g><g filter="url(#isb001c)"><ellipse fill="url(#iG3JQVd)" transform="rotate(150.611 12.11 11.281)" class="xox8j76se"/></g><g filter="url(#i02nmpe)"><path stroke="url(#iRxyRFd)" class="fo1au8bke"/></g><g filter="url(#il7mqkN)"><path stroke="url(#i47zAin)" class="tcwnis4ri"/></g></g><defs><radialGradient id="iXwv3mc" cx="0" cy="0" r="1" gradientTransform="rotate(-138.643 11.823 5.79)scale(23.9312 14.1578)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".785" class="poroirbmk"/></radialGradient><radialGradient id="iNQCaoe" cx="0" cy="0" r="1" gradientTransform="rotate(178.046 10.034 10.148)scale(25.1878 31.5353)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="fi0s2ac3w"/><stop offset=".814" class="utan509ld"/></radialGradient><radialGradient id="i1v8CBc" cx="0" cy="0" r="1" gradientTransform="matrix(39.74996 -6.5 3.74657 22.9117 2.972 16.136)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="qudiit10p"/><stop offset=".735" class="poroirbmk"/></radialGradient><radialGradient id="ioxCtGc" cx="0" cy="0" r="1" gradientTransform="matrix(-16.37517 -20.43737 54.0988 -43.34597 25.66 24.948)" gradientUnits="userSpaceOnUse"><stop offset=".607" class="fi0s2ac3w"/><stop offset=".814" class="utan509ld"/></radialGradient><radialGradient id="iEolPLe" cx="0" cy="0" r="1" gradientTransform="rotate(99.933 9.313 14.79)scale(9.0832 29.5242)" gradientUnits="userSpaceOnUse"><stop class="wud1hbcyo"/><stop offset="1" class="gltfveblc"/></radialGradient><radialGradient id="iG3JQVd" cx="0" cy="0" r="1" gradientTransform="rotate(96.854 2.12 10.142)scale(8.73812 23.3563)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="jvm-ff-mo"/><stop offset="1" class="k_a581bun"/></radialGradient><linearGradient id="iOsiCkc" x1="9.765" x2="9.765" y1="29.266" y2="5.164" gradientUnits="userSpaceOnUse"><stop offset=".026" class="uojyabbji"/><stop offset=".198" class="r1esfgxdr"/><stop offset=".536" class="nuo1eib2l"/><stop offset="1" class="uojyabbji"/></linearGradient><linearGradient id="ijeQ6gc" x1="17.784" x2="14.329" y1="14.744" y2="14.744" gradientUnits="userSpaceOnUse"><stop class="dxabo793d"/><stop offset="1" class="hryn-e39k"/></linearGradient><linearGradient id="i1HWN8b" x1="23.302" x2="23.302" y1="29.26" y2="5.156" gradientUnits="userSpaceOnUse"><stop class="bkf2l06yx"/><stop offset=".444" class="ie-5pgb7s"/><stop offset="1" class="uojyabbji"/></linearGradient><linearGradient id="i6gqirT" x1="16.284" x2="19.097" y1="14.728" y2="14.728" gradientUnits="userSpaceOnUse"><stop class="h0phxk14d"/><stop offset="1" class="tdaaarbfr"/></linearGradient><linearGradient id="iRxyRFd" x1="14.597" x2="12.803" y1="19.262" y2="16.218" gradientUnits="userSpaceOnUse"><stop class="l75t95b0x"/><stop offset="1" class="gfac7zbup"/></linearGradient><linearGradient id="i47zAin" x1="15.675" x2="13.659" y1="14.573" y2="9.039" gradientUnits="userSpaceOnUse"><stop class="w-grqjbuq"/><stop offset="1" class="pla7liblw"/></linearGradient><filter id="i87Oogq" width="15.144" height="15.416" x="16.881" y="4.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7133_6142" stdDeviation="1.5"/></filter><filter id="isb001c" width="12.906" height="14.633" x="5.657" y="3.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7133_6142" stdDeviation="1.5"/></filter><filter id="i02nmpe" width="3.7" height="6.388" x="13.184" y="16.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7133_6142" stdDeviation=".175"/></filter><filter id="il7mqkN" width="3.547" height="7.944" x="13.39" y="8.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7133_6142" stdDeviation=".175"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:broken-heart" /></template>
<style>
.bkf2l06yx {
  stop-color: var(--svg-color--ff2657, #FF2657);
}

.dxabo793d {
  stop-color: var(--svg-color--c6162a, #C6162A);
}

.fi0s2ac3w {
  stop-color: var(--svg-color--ab1f51, #AB1F51);
  stop-opacity: 0;
}

.fo1au8bke {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m16.41 22.606l-2.75-5.438");
}

.ft5dv1b6b {
  fill: none;
}

.gfac7zbup {
  stop-color: var(--svg-color--ff757b, #FF757B);
  stop-opacity: 0;
}

.gltfveblc {
  stop-color: var(--svg-color--ef6e9d, #EF6E9D);
  stop-opacity: 0;
}

.h0phxk14d {
  stop-color: var(--svg-color--c01567, #C01567);
}

.hryn-e39k {
  stop-color: var(--svg-color--c6162a, #C6162A);
  stop-opacity: 0;
}

.id0-6-b7y {
  cx: 24.453px;
  cy: 12.672px;
  rx: 4.04px;
  ry: 5.171px;
}

.ie-5pgb7s {
  stop-color: var(--svg-color--ff2f67, #FF2F67);
}

.jvm-ff-mo {
  stop-color: var(--svg-color--ec5a8f, #EC5A8F);
}

.k_a581bun {
  stop-color: var(--svg-color--ec5a8f, #EC5A8F);
  stop-opacity: 0;
}

.l75t95b0x {
  stop-color: var(--svg-color--ff757b, #FF757B);
}

.nlcb38bpp {
  d: path("M15.269 25.734a.9.9 0 0 1 .187-.555l1.211-1.855c.245-.316.256-.647.063-.993l-2.485-4.914c-.214-.386-.067-.592.086-.765c.45-.509 1.344-1.696 1.69-2.139l.633-.803c.225-.274.276-.65.153-.986c-.497-1.329-1.078-2.919-1.624-4.408c-.185-.504-.35-1.079-.735-1.438c-.74-.691-2.076-1.416-3.099-1.594C4.27 3.777 1.577 9.98 2.534 14.94c1.39 6.086 7.969 12.148 11.961 14.16c.45.226.75.06.75-.309z");
}

.nuo1eib2l {
  stop-color: var(--svg-color--ff2868, #FF2868);
}

.pla7liblw {
  stop-color: var(--svg-color--ff989d, #FF989D);
  stop-opacity: 0;
}

.poroirbmk {
  stop-color: var(--svg-color--ff96d7, #FF96D7);
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r1esfgxdr {
  stop-color: var(--svg-color--ff1f50, #FF1F50);
}

.tcwnis4ri {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m13.815 16.511l2.688-3.312l-1.375-3.782");
}

.tdaaarbfr {
  stop-color: var(--svg-color--c01567, #C01567);
  stop-opacity: 0;
}

.uojyabbji {
  stop-color: var(--svg-color--ec008c, #EC008C);
}

.utan509ld {
  stop-color: var(--svg-color--ab1f51, #AB1F51);
}

.vpwfny5mj {
  d: path("M21.815 5.09c-1.64.283-3.489 1.394-4.428 2.377c0 0-.123.102-.123.254c0 .06.02.142.03.152l1.943 5.341a.66.66 0 0 1-.07.703c-.725.898-1.524 1.969-2.227 2.871c-.31.315-.341.681-.125 1.067l2.422 4.676c.196.354.117.593-.043.828l-1.554 2.37c-.135.173-.266.516-.266.731l-.027 2.524c0 .316.482.348.875.074c3.828-2.094 10.411-7.917 11.78-14.063c1.126-5.047-1.75-10.78-8.187-9.906");
}

.w-grqjbuq {
  stop-color: var(--svg-color--ff989d, #FF989D);
}

.wud1hbcyo {
  stop-color: var(--svg-color--ef6e9d, #EF6E9D);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xox8j76se {
  cx: 12.11px;
  cy: 11.281px;
  rx: 2.968px;
  ry: 4.662px;
}

</style>
