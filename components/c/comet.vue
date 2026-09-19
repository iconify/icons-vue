<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1LNpSb)"><path fill="url(#iYIvr9u)" class="qtcmx-_pn"/></g><g filter="url(#iuMPmpb)"><path fill="url(#iF9Op4d)" class="u-2lfmboj"/></g><g filter="url(#i9rB7ib)"><path fill="url(#iEs3l2R)" class="srrgz-bdi"/></g><g filter="url(#im3lqBG)"><path fill="url(#iZhak7d)" class="wpkuy6auk"/></g><g filter="url(#iohHENe)"><path fill="url(#iL0KCTd)" class="t3a6o75vi"/></g><g filter="url(#iCl5Gye)"><path fill="url(#iPg8vPb)" class="cnogkdbmi"/></g><g filter="url(#iA2n0Ee)"><path fill="url(#iQ9SOYc)" class="ltpt1lb2s"/></g><g filter="url(#iHCIkzd)"><path fill="url(#iFrchob)" class="wy2_u5b4y"/></g><g filter="url(#iFHj7jc)"><path fill="url(#iRyoSvc)" class="kjjascdnj"/></g><g filter="url(#iucVs3d)"><path fill="url(#ibjqyDc)" class="lk8dth11o"/></g><g filter="url(#iHShopb)"><path fill="url(#iQZDlpe)" class="waio3ibmx"/></g><g filter="url(#i9Yk6Ke)"><path fill="url(#isIRahe)" class="pefczkbul"/></g><g filter="url(#iAuNpmd)"><path fill="url(#i9XCndc)" class="jbj18qbos"/></g><g filter="url(#iV7z1Dd)"><path fill="url(#iSjfOnb)" class="tv801v4nc"/></g><g filter="url(#iccFnDd)"><path fill="url(#iPN1jYb)" class="g7op27bpd"/></g><g filter="url(#i1rkzZA)"><path fill="url(#i80JS7b)" class="ru87ycbcs"/></g><g filter="url(#i0VEyKd)"><path fill="url(#i2OqXub)" class="ntocwxbby"/></g><defs><filter id="i1LNpSb" width="25.336" height="25.34" x="2.9" y="2.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_18_15793" result="effect2_innerShadow_18_15793"/></filter><filter id="iuMPmpb" width="11.64" height="11.64" x="4.198" y="15.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15793" stdDeviation=".25"/></filter><filter id="i9rB7ib" width="1.836" height="1.837" x="10.599" y="13.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15793" stdDeviation=".1"/></filter><filter id="im3lqBG" width="1.754" height="1.754" x="15.64" y="18.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15793" stdDeviation=".1"/></filter><filter id="iohHENe" width="2.815" height="2.815" x="13.61" y="14.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15793" stdDeviation=".1"/></filter><filter id="iCl5Gye" width="1.789" height="1.789" x="13.623" y="11.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15793" stdDeviation=".125"/></filter><filter id="iA2n0Ee" width="1.783" height="1.783" x="19.626" y="9.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15793" stdDeviation=".125"/></filter><filter id="iHCIkzd" width="2.402" height="2.402" x="16.816" y="10.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15793" stdDeviation=".125"/></filter><filter id="iFHj7jc" width="2.402" height="2.402" x="16.816" y="13.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15793" stdDeviation=".125"/></filter><filter id="iucVs3d" width="10.2" height="10.2" x="5.018" y="15.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.725 0 0 0 0 0.117813 0 0 0 0 0.394506 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/></filter><filter id="iHShopb" width="1.2" height="1.2" x="20.018" y="9.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.725 0 0 0 0 0.117813 0 0 0 0 0.394506 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/></filter><filter id="i9Yk6Ke" width="1.2" height="1.2" x="14.018" y="11.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.725 0 0 0 0 0.117813 0 0 0 0 0.394506 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/></filter><filter id="iAuNpmd" width="1.2" height="1.2" x="16.018" y="18.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.725 0 0 0 0 0.117813 0 0 0 0 0.394506 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/></filter><filter id="iV7z1Dd" width="1.2" height="1.2" x="11.018" y="13.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.725 0 0 0 0 0.117813 0 0 0 0 0.394506 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/></filter><filter id="iccFnDd" width="2.18" height="2.18" x="14.027" y="14.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.725 0 0 0 0 0.117813 0 0 0 0 0.394506 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/></filter><filter id="i1rkzZA" width="1.7" height="1.7" x="17.268" y="11.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.725 0 0 0 0 0.117813 0 0 0 0 0.394506 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/></filter><filter id="i0VEyKd" width="1.7" height="1.7" x="17.268" y="14.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.725 0 0 0 0 0.117813 0 0 0 0 0.394506 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15793"/></filter><linearGradient id="iYIvr9u" x1="5.281" x2="28.036" y1="25.799" y2="3.217" gradientUnits="userSpaceOnUse"><stop class="ke2vpcz6q"/><stop offset=".813" class="ve3cs3j_h"/><stop offset=".96" class="o3bw_5bwb"/></linearGradient><linearGradient id="iF9Op4d" x1="14.156" x2="6.277" y1="17.039" y2="25.743" gradientUnits="userSpaceOnUse"><stop class="x8srzht5w"/><stop offset="1" class="e-hccd-_n"/></linearGradient><linearGradient id="iEs3l2R" x1="12.076" x2="11.013" y1="13.985" y2="15.16" gradientUnits="userSpaceOnUse"><stop class="yfdrgd96v"/><stop offset="1" class="itqmn5ahf"/></linearGradient><linearGradient id="iZhak7d" x1="17.044" x2="16.041" y1="19.016" y2="20.124" gradientUnits="userSpaceOnUse"><stop class="yfdrgd96v"/><stop offset="1" class="itqmn5ahf"/></linearGradient><linearGradient id="iL0KCTd" x1="15.957" x2="14.169" y1="15.119" y2="17.094" gradientUnits="userSpaceOnUse"><stop class="yfdrgd96v"/><stop offset="1" class="itqmn5ahf"/></linearGradient><linearGradient id="iPg8vPb" x1="15.019" x2="14.065" y1="12.04" y2="13.095" gradientUnits="userSpaceOnUse"><stop class="a2trsgbfe"/><stop offset="1" class="vzf90zbap"/></linearGradient><linearGradient id="iQ9SOYc" x1="21.017" x2="20.067" y1="10.043" y2="11.092" gradientUnits="userSpaceOnUse"><stop class="y-_zoibly"/><stop offset="1" class="gmc76e8nc"/></linearGradient><linearGradient id="iFrchob" x1="18.758" x2="17.349" y1="11.311" y2="12.867" gradientUnits="userSpaceOnUse"><stop class="ytnm0cr0k"/><stop offset="1" class="w9sa87kky"/></linearGradient><linearGradient id="iRyoSvc" x1="18.758" x2="17.349" y1="14.311" y2="15.867" gradientUnits="userSpaceOnUse"><stop class="yxfpcybio"/><stop offset="1" class="h8xb0iqts"/></linearGradient><radialGradient id="ibjqyDc" cx="0" cy="0" r="1" gradientTransform="rotate(135.764 2.495 12.137)scale(6.62972 9.64172)" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="pkxhlwy0g"/></radialGradient><radialGradient id="iQZDlpe" cx="0" cy="0" r="1" gradientTransform="rotate(134.931 8.252 9.478)scale(.77928 1.1333)" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="pkxhlwy0g"/></radialGradient><radialGradient id="isIRahe" cx="0" cy="0" r="1" gradientTransform="rotate(134.931 4.837 9.233)scale(.77928 1.1333)" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="pkxhlwy0g"/></radialGradient><radialGradient id="i9XCndc" cx="0" cy="0" r="1" gradientTransform="rotate(134.931 4.385 13.148)scale(.77928 1.1333)" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="pkxhlwy0g"/></radialGradient><radialGradient id="iSjfOnb" cx="0" cy="0" r="1" gradientTransform="rotate(134.931 2.923 9.611)scale(.77928 1.1333)" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="pkxhlwy0g"/></radialGradient><radialGradient id="iPN1jYb" cx="0" cy="0" r="1" gradientTransform="rotate(134.931 4.534 11.048)scale(1.54296 2.24396)" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="pkxhlwy0g"/></radialGradient><radialGradient id="i80JS7b" cx="0" cy="0" r="1" gradientTransform="rotate(134.931 6.78 9.69)scale(1.16891 1.69997)" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="pkxhlwy0g"/></radialGradient><radialGradient id="i2OqXub" cx="0" cy="0" r="1" gradientTransform="rotate(134.931 6.157 11.19)scale(1.16891 1.69997)" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="pkxhlwy0g"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:comet" /></template>
<style>
.a2trsgbfe {
  stop-color: var(--svg-color--ead6d8, #EAD6D8);
}

.cnogkdbmi {
  d: path("M14.518 13.167a.644.644 0 1 0 0-1.288a.644.644 0 0 0 0 1.288");
}

.e-hccd-_n {
  stop-color: var(--svg-color--e77980, #E77980);
}

.ft5dv1b6b {
  fill: none;
}

.g7op27bpd {
  d: path("M15.018 17.013a.99.99 0 1 0 0-1.98a.99.99 0 0 0 0 1.98");
}

.ghzd3_bys {
  stop-color: var(--svg-color--ee3124, #EE3124);
}

.gmc76e8nc {
  stop-color: var(--svg-color--c4c3cf, #C4C3CF);
}

.h8xb0iqts {
  stop-color: var(--svg-color--d2b2bf, #D2B2BF);
}

.itqmn5ahf {
  stop-color: var(--svg-color--d5a5ae, #D5A5AE);
}

.jbj18qbos {
  d: path("M16.518 20.023a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.ke2vpcz6q {
  stop-color: var(--svg-color--ff8684, #FF8684);
}

.kjjascdnj {
  d: path("M18.018 15.974a.951.951 0 1 0 0-1.902a.951.951 0 0 0 0 1.902");
}

.lk8dth11o {
  d: path("M10.018 26.023a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

.ltpt1lb2s {
  d: path("M20.518 11.164a.641.641 0 1 0 0-1.282a.641.641 0 0 0 0 1.282");
}

.ntocwxbby {
  d: path("M18.018 15.773a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.o3bw_5bwb {
  stop-color: var(--svg-color--81eaff, #81EAFF);
}

.pefczkbul {
  d: path("M14.518 13.023a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.pkxhlwy0g {
  stop-color: var(--svg-color--c51071, #C51071);
}

.qtcmx-_pn {
  d: path("m27.148 3.123l-4.41 3.41v-1.03c0-.53-.64-.8-1.02-.42l-3.94 3.94v-1.39c0-.53-.64-.8-1.02-.42l-4.64 4.64v-1.39c0-.53-.64-.8-1.02-.42l-6.05 6.05a7.007 7.007 0 0 0 0 9.9a7.007 7.007 0 0 0 9.9 0l6.06-6.06c.37-.37.11-1.02-.42-1.02h-1.39l4.64-4.64c.37-.37.11-1.02-.42-1.02h-1.39l3.93-3.93c.37-.37.11-1.02-.42-1.02h-1.03l3.4-4.4c.41-.52-.25-1.18-.76-.78");
}

.ru87ycbcs {
  d: path("M18.018 12.773a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.srrgz-bdi {
  d: path("M11.518 15.241a.718.718 0 1 0 0-1.436a.718.718 0 0 0 0 1.436");
}

.t3a6o75vi {
  d: path("M15.018 17.23a1.207 1.207 0 1 0 0-2.414a1.207 1.207 0 0 0 0 2.414");
}

.tv801v4nc {
  d: path("M11.518 15.023a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.u-2lfmboj {
  d: path("M10.018 26.343a5.32 5.32 0 1 0 0-10.64a5.32 5.32 0 0 0 0 10.64");
}

.ve3cs3j_h {
  stop-color: var(--svg-color--cbecf3, #CBECF3);
}

.vzf90zbap {
  stop-color: var(--svg-color--d0b2bb, #D0B2BB);
}

.w9sa87kky {
  stop-color: var(--svg-color--cbbac5, #CBBAC5);
}

.waio3ibmx {
  d: path("M20.518 11.023a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.wpkuy6auk {
  d: path("M16.518 20.2a.677.677 0 1 0 0-1.354a.677.677 0 0 0 0 1.354");
}

.wy2_u5b4y {
  d: path("M18.018 12.974a.951.951 0 1 0 0-1.902a.951.951 0 0 0 0 1.902");
}

.x8srzht5w {
  stop-color: var(--svg-color--f4c0c2, #F4C0C2);
}

.y-_zoibly {
  stop-color: var(--svg-color--deeaec, #DEEAEC);
}

.yfdrgd96v {
  stop-color: var(--svg-color--eecdcf, #EECDCF);
}

.ytnm0cr0k {
  stop-color: var(--svg-color--dfdde0, #DFDDE0);
}

.yxfpcybio {
  stop-color: var(--svg-color--e9dadb, #E9DADB);
}

</style>
