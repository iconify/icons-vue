<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iMrsKub)" class="vhnxmobgz"/><path fill="url(#iJIXnmc)" class="vhnxmobgz"/><g filter="url(#idZ04OO)"><path class="syvezt4qk"/><path fill="url(#iT8iFUb)" class="uw1fi1e8b"/><path fill="url(#iw2Szvb)" class="uw1fi1e8b"/></g><path fill="url(#iRwB8me)" class="uw1fi1e8b"/><path fill="url(#iG20lKe)" class="uw1fi1e8b"/><g filter="url(#id1qoOi)"><path stroke="url(#icGIvjc)" class="u7cti_gpz"/></g><g filter="url(#i5IFPRb)"><path fill="url(#i8u74ae)" class="r5-4zb_bz"/></g><g filter="url(#iS0RWDd)"><path fill="url(#iPDVpKU)" class="b2j57zxmt"/></g><path fill="url(#iAPhHbd)" class="b2j57zxmt"/><path fill="url(#iQvKn8c)" class="b2j57zxmt"/><defs><radialGradient id="iMrsKub" cx="0" cy="0" r="1" gradientTransform="rotate(153.208 6.475 4.51)scale(4.20461 3.59222)" gradientUnits="userSpaceOnUse"><stop class="yxmdsacnw"/><stop offset="1" class="xxwblcbbb"/></radialGradient><radialGradient id="iJIXnmc" cx="0" cy="0" r="1" gradientTransform="matrix(1.87912 -3.02965 2.94766 1.82827 13.756 8.091)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="z9mp0kg_y"/><stop offset="1" class="vzcsvxb7h"/></radialGradient><radialGradient id="iT8iFUb" cx="0" cy="0" r="1" gradientTransform="rotate(111.609 1.39 14.11)scale(10.3526 6.47339)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="n8gwj7wbw"/><stop offset="1" class="n9cycih6m"/></radialGradient><radialGradient id="iw2Szvb" cx="0" cy="0" r="1" gradientTransform="rotate(137.466 3.172 7.558)scale(4.74976 4.48072)" gradientUnits="userSpaceOnUse"><stop class="cs1t-84ed"/><stop offset="1" class="iqsf78bkf"/></radialGradient><radialGradient id="iRwB8me" cx="0" cy="0" r="1" gradientTransform="matrix(-8.58713 6.58842 -7.2305 -9.42399 24.728 7.22)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="smegbduug"/><stop offset="1" class="y6cndpbec"/></radialGradient><radialGradient id="iG20lKe" cx="0" cy="0" r="1" gradientTransform="rotate(170.656 10.043 6.052)scale(18.9046 16.1511)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="i1w9labfr"/><stop offset="1" class="vt77dwb8m"/></radialGradient><radialGradient id="iQvKn8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.47652 -.75851 0 16.792 16.185)" gradientUnits="userSpaceOnUse"><stop class="ug-juxb-t"/><stop offset="1" class="ft-8t4bgx"/></radialGradient><linearGradient id="icGIvjc" x1="13.189" x2="15.056" y1="10.162" y2="15.764" gradientUnits="userSpaceOnUse"><stop class="u28ir3caf"/><stop offset="1" class="jqxw1h_mj"/></linearGradient><linearGradient id="i8u74ae" x1="17.496" x2="17.496" y1="17.576" y2="24.687" gradientUnits="userSpaceOnUse"><stop class="ony8whing"/><stop offset="1" class="ye48tppfg"/></linearGradient><linearGradient id="iPDVpKU" x1="15.7" x2="15.7" y1="14.828" y2="26.234" gradientUnits="userSpaceOnUse"><stop class="vb7mfsbfz"/><stop offset="1" class="ivq57fb2f"/></linearGradient><linearGradient id="iAPhHbd" x1="15.7" x2="15.7" y1="13.37" y2="19.328" gradientUnits="userSpaceOnUse"><stop class="erglgdc8a"/><stop offset="1" class="jkg2xab0t"/></linearGradient><filter id="idZ04OO" width="28.719" height="19.966" x="2.281" y="0" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.12549 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15216"/></filter><filter id="id1qoOi" width="4.367" height="7.561" x="11.607" y="7.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15216" stdDeviation=".5"/></filter><filter id="i5IFPRb" width="8.059" height="14.473" x="12.061" y="13.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.478431 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15216"/></filter><filter id="iS0RWDd" width="7.959" height="14.472" x="11.721" y="13.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.203922 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15216"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cloud-with-lightning" /></template>
<style>
.b2j57zxmt {
  d: path("m16.466 13.443l-4.709 7.808c-.1.167.02.38.214.38h2.223a.3.3 0 0 1 .3.3v5.76c0 .152.199.208.277.079l4.886-8.005a.15.15 0 0 0-.128-.229h-2.535a.25.25 0 0 1-.25-.25V13.52c0-.152-.2-.208-.279-.077");
}

.cs1t-84ed {
  stop-color: var(--svg-color--534add, #534ADD);
}

.erglgdc8a {
  stop-color: var(--svg-color--df9844, #DF9844);
}

.ft-8t4bgx {
  stop-color: var(--svg-color--fe9052, #FE9052);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.i1w9labfr {
  stop-color: var(--svg-color--35209a, #35209A);
  stop-opacity: 0;
}

.iqsf78bkf {
  stop-color: var(--svg-color--574adf, #574ADF);
  stop-opacity: 0;
}

.ivq57fb2f {
  stop-color: var(--svg-color--f14b49, #F14B49);
}

.jkg2xab0t {
  stop-color: var(--svg-color--df9844, #DF9844);
  stop-opacity: 0;
}

.jqxw1h_mj {
  stop-color: var(--svg-color--554bd3, #554BD3);
  stop-opacity: 0;
}

.n8gwj7wbw {
  stop-color: var(--svg-color--381b90, #381B90);
}

.n9cycih6m {
  stop-color: var(--svg-color--381b90, #381B90);
  stop-opacity: 0;
}

.ony8whing {
  stop-color: var(--svg-color--ea9b4c, #EA9B4C);
}

.r5-4zb_bz {
  d: path("m16.59 13.966l-4.392 7.285a.25.25 0 0 0 .214.38h2.222a.3.3 0 0 1 .3.3v4.65h-.264v1.26h.405a.15.15 0 0 0 .137-.071l4.886-8.005a.15.15 0 0 0-.128-.229h-2.536a.25.25 0 0 1-.25-.25V13.52a.15.15 0 0 0-.14-.15h-.454z");
}

.smegbduug {
  stop-color: var(--svg-color--6051ff, #6051FF);
}

.syvezt4qk {
  fill: var(--svg-color--3124c5, #3124C5);
  d: path("M30 11.048c0 4.926-3.989 8.918-8.91 8.918H8.82c-3.611 0-6.538-3.04-6.538-6.44s2.834-6.197 6.445-6.197c.725 0 1.694.186 2.586.53c.893.345 1.558-.37 1.875-1.004C14.559 4.109 17.564 2 21.125 2C26.045 2 30 6.123 30 11.048");
}

.u28ir3caf {
  stop-color: var(--svg-color--554bd3, #554BD3);
}

.u7cti_gpz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.857 8.934c.607.704 1.828 2.703 1.868 5.061");
}

.ug-juxb-t {
  stop-color: var(--svg-color--fe9052, #FE9052);
}

.uw1fi1e8b {
  d: path("M30 11.048c0 4.926-3.989 8.918-8.91 8.918H8.82c-3.611 0-6.538-3.04-6.538-6.44s2.834-6.197 6.445-6.197c.725 0 1.694.186 2.586.53c.893.345 1.558-.37 1.875-1.004C14.559 4.109 17.564 2 21.125 2C26.045 2 30 6.123 30 11.048");
}

.vb7mfsbfz {
  stop-color: var(--svg-color--f39445, #F39445);
}

.vhnxmobgz {
  d: path("M12.988 12.461a4.2 4.2 0 1 0 0-8.399a4.2 4.2 0 0 0 0 8.399");
}

.vt77dwb8m {
  stop-color: var(--svg-color--35209a, #35209A);
}

.vzcsvxb7h {
  stop-color: var(--svg-color--281ea4, #281EA4);
  stop-opacity: 0;
}

.xxwblcbbb {
  stop-color: var(--svg-color--3831b0, #3831B0);
}

.y6cndpbec {
  stop-color: var(--svg-color--6051ff, #6051FF);
  stop-opacity: 0;
}

.ye48tppfg {
  stop-color: var(--svg-color--eb5c74, #EB5C74);
}

.yxmdsacnw {
  stop-color: var(--svg-color--5347d7, #5347D7);
}

.z9mp0kg_y {
  stop-color: var(--svg-color--281ea4, #281EA4);
}

</style>
