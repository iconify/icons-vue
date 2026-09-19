<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iomwzTd)"><path fill="url(#iRG986d)" class="du40r8bbl"/></g><g filter="url(#iLEHMoe)"><path fill="url(#izQridp)" class="ngc131odg"/><path fill="url(#i36hWYd)" class="ngc131odg"/></g><g filter="url(#iWx9XMS)"><path fill="url(#iyDOQEe)" class="g2h2w11kb"/><path fill="url(#iQsvPae)" class="g2h2w11kb"/></g><g filter="url(#iOk7BQb)"><path fill="url(#itXlD2c)" class="p7czy-b9g"/><path fill="url(#iIE0iuc)" class="p7czy-b9g"/></g><g filter="url(#iBB6kJc)"><path fill="url(#i8nBdDc)" class="bb0fj9b9h"/><path fill="url(#iucvWcc)" class="bb0fj9b9h"/></g><g filter="url(#irscKrd)"><path fill="url(#iLM41Sb)" class="cv1-vwbdm"/></g><circle fill="url(#iSJfKcb)" class="jieglacql"/><circle fill="url(#irdhW7b)" class="i_dw80b_l"/><circle fill="url(#iNUTGEc)" class="qj72jlbeh"/><circle fill="url(#iUewj1c)" class="qj72jlbeh"/><circle fill="url(#iIsJuPe)" class="qj72jlbeh"/><circle fill="url(#iZEELEc)" class="p_hgjbcip"/><g filter="url(#iDlkbZb)"><path fill="url(#inzcDdc)" class="c1bw2j83k"/><path fill="url(#icVyTmg)" class="c1bw2j83k"/><path fill="url(#i4DBoMb)" class="c1bw2j83k"/><path fill="url(#isxaX4d)" class="c1bw2j83k"/><path fill="url(#ix76E4c)" class="c1bw2j83k"/><path fill="url(#itFdazb)" class="c1bw2j83k"/></g><circle fill="url(#iUqAibd)" class="viev0sf_r"/><circle fill="url(#i3ne4Wb)" class="viev0sf_r"/><circle fill="url(#iCBgyXc)" class="viev0sf_r"/><g filter="url(#igizD1d)"><path fill="url(#iXa3SHb)" class="j1v1r5drn"/></g><path fill="url(#iTxmSwb)" class="j1v1r5drn"/><path fill="url(#iLYX5Ad)" class="h8z_-g-_s"/><path fill="url(#igMOaAb)" class="h8z_-g-_s"/><path fill="url(#ibJZO2b)" class="h8z_-g-_s"/><path fill="url(#i8s3BKe)" class="zy3jajjuv"/><path fill="url(#iDPPNiQ)" class="zy3jajjuv"/><path fill="url(#iVKlOvk)" class="zy3jajjuv"/><path fill="url(#ilJQufN)" class="zy3jajjuv"/><path fill="url(#iuUhhJe)" class="em_gk8bnz"/><path fill="url(#izvQIjb)" class="em_gk8bnz"/><path fill="url(#iDYeZHj)" class="em_gk8bnz"/><path fill="url(#iArT2Kc)" class="em_gk8bnz"/><defs><radialGradient id="iRG986d" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 4.28125 -3.15681 2.53467 6.39 5.078)" gradientUnits="userSpaceOnUse"><stop class="ofburreiz"/><stop offset=".448" class="tjzk_lkiq"/></radialGradient><radialGradient id="izQridp" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.54733 -6.30244 0 14.607 .573)" gradientUnits="userSpaceOnUse"><stop class="ofburreiz"/><stop offset=".357" class="tjzk_lkiq"/></radialGradient><radialGradient id="i36hWYd" cx="0" cy="0" r="1" gradientTransform="rotate(-100.879 10.418 -3.427)scale(4.42324 2.23338)" gradientUnits="userSpaceOnUse"><stop class="hjmmhkbot"/><stop offset="1" class="wg3z9zbmc"/></radialGradient><radialGradient id="iyDOQEe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5656 4.94129 -3.6435 -3.36648 24.555 5.241)" gradientUnits="userSpaceOnUse"><stop class="ofburreiz"/><stop offset=".357" class="tjzk_lkiq"/></radialGradient><radialGradient id="iQsvPae" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -2.4375 1.3853 1.01233 21.594 9.188)" gradientUnits="userSpaceOnUse"><stop class="d2at_bbdl"/><stop offset="1" class="wg3z9zbmc"/></radialGradient><radialGradient id="iIE0iuc" cx="0" cy="0" r="1" gradientTransform="rotate(-132.737 17.703 7.802)scale(.88549)" gradientUnits="userSpaceOnUse"><stop class="w7gmm3l1d"/><stop offset="1" class="b1csxabjr"/></radialGradient><radialGradient id="iucvWcc" cx="0" cy="0" r="1" gradientTransform="rotate(-90 22.406 7.875)scale(1.125)" gradientUnits="userSpaceOnUse"><stop class="w7gmm3l1d"/><stop offset="1" class="b1csxabjr"/></radialGradient><radialGradient id="iSJfKcb" cx="0" cy="0" r="1" gradientTransform="matrix(.91406 .03906 -.04422 1.0347 3.219 16.719)" gradientUnits="userSpaceOnUse"><stop class="qe7k2vbdf"/><stop offset="1" class="j04vgwbqr"/></radialGradient><radialGradient id="irdhW7b" cx="0" cy="0" r="1" gradientTransform="matrix(.99218 -.23437 .29553 1.25106 3.14 14.992)" gradientUnits="userSpaceOnUse"><stop class="qe7k2vbdf"/><stop offset="1" class="j04vgwbqr"/></radialGradient><radialGradient id="iNUTGEc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.12499 8.87503 -10.14422 -7.0009 20.625 9.813)" gradientUnits="userSpaceOnUse"><stop class="llu-8u1_n"/><stop offset="1" class="jo1t87len"/></radialGradient><radialGradient id="iUewj1c" cx="0" cy="0" r="1" gradientTransform="rotate(-146.926 14.745 7.286)scale(20.9585 17.4114)" gradientUnits="userSpaceOnUse"><stop offset=".873" class="m-a4dcbfn"/><stop offset=".998" class="j2mrz2bol"/></radialGradient><radialGradient id="iIsJuPe" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -4.3125 3.8522 3.04268 15.813 15.063)" gradientUnits="userSpaceOnUse"><stop class="cox409z-b"/><stop offset="1" class="ci4rlebam"/></radialGradient><radialGradient id="iZEELEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26825 -4.63202 5.23434 1.43316 15.45 20.945)" gradientUnits="userSpaceOnUse"><stop class="cgf1ejbpr"/><stop offset="1" class="cffa2xhfw"/></radialGradient><radialGradient id="icVyTmg" cx="0" cy="0" r="1" gradientTransform="rotate(-106.044 17.427 7.125)scale(8.66439 21.1359)" gradientUnits="userSpaceOnUse"><stop class="x59qscb1t"/><stop offset="1" class="y0j9fi_7t"/></radialGradient><radialGradient id="i4DBoMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.164 -14.3046 0 14.5 11.692)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="sqlykc4pm"/><stop offset="1" class="hoi9ce21h"/></radialGradient><radialGradient id="isxaX4d" cx="0" cy="0" r="1" gradientTransform="matrix(8.84585 -4.29951 5.3731 11.05467 5.654 23.883)" gradientUnits="userSpaceOnUse"><stop class="cfilxn3mw"/><stop offset="1" class="oyic528hr"/></radialGradient><radialGradient id="ix76E4c" cx="0" cy="0" r="1" gradientTransform="rotate(75.091 -.164 22.198)scale(4.01898 5.69696)" gradientUnits="userSpaceOnUse"><stop class="ytjwdac7x"/><stop offset="1" class="tz_dj6b2f"/></radialGradient><radialGradient id="itFdazb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 4.5 -6.5923 -.82404 15.063 18.813)" gradientUnits="userSpaceOnUse"><stop class="w6ngq8l7q"/><stop offset="1" class="dwe12sbrw"/></radialGradient><radialGradient id="iUqAibd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 8.619 15.167)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="i3ne4Wb" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 1.384 9.279)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="ibJZO2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 .51562 -.32045 -.29132 18.797 8.922)" gradientUnits="userSpaceOnUse"><stop class="ep4otabei"/><stop offset="1" class="edu4b3bff"/></radialGradient><radialGradient id="iDPPNiQ" cx="0" cy="0" r="1" gradientTransform="rotate(-122.237 9.075 1.73)scale(2.05045 .65625)" gradientUnits="userSpaceOnUse"><stop class="lxb490rtn"/><stop offset="1" class="iqf74db2o"/></radialGradient><radialGradient id="ilJQufN" cx="0" cy="0" r="1" gradientTransform="matrix(.60938 .99219 -.85005 .52208 11 8.344)" gradientUnits="userSpaceOnUse"><stop class="mjsu73m7n"/><stop offset="1" class="p4vp38byl"/></radialGradient><radialGradient id="iuUhhJe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.78125 0 0 -5.46908 30.656 17.06)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="c964n-4ao"/><stop offset="1" class="rdaongbfw"/></radialGradient><radialGradient id="izvQIjb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.0625 0 0 -7.53125 33.031 17.375)" gradientUnits="userSpaceOnUse"><stop offset=".88" class="ir1-q_9_t"/><stop offset="1" class="ij70po60m"/></radialGradient><radialGradient id="iArT2Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4336 3.65625 -1.3346 -.15827 29.152 14.625)" gradientUnits="userSpaceOnUse"><stop class="xrioznb3q"/><stop offset="1" class="n--dpzbtg"/></radialGradient><linearGradient id="itXlD2c" x1="21.766" x2="23.297" y1="24.969" y2="23.922" gradientUnits="userSpaceOnUse"><stop class="p1yh9yyct"/><stop offset="1" class="j9evpdb1z"/></linearGradient><linearGradient id="i8nBdDc" x1="15.625" x2="12.688" y1="27.25" y2="29.562" gradientUnits="userSpaceOnUse"><stop class="frekxybqd"/><stop offset="1" class="fkak-i_iz"/></linearGradient><linearGradient id="iLM41Sb" x1="6.672" x2="5.469" y1="25.797" y2="24.25" gradientUnits="userSpaceOnUse"><stop class="frekxybqd"/><stop offset="1" class="fkak-i_iz"/></linearGradient><linearGradient id="inzcDdc" x1="6.851" x2="25.125" y1="17.842" y2="17.842" gradientUnits="userSpaceOnUse"><stop class="nail__bjf"/><stop offset="1" class="fg05m2bds"/></linearGradient><linearGradient id="iCBgyXc" x1="8.372" x2="8.028" y1="14.935" y2="14.717" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iXa3SHb" x1="16.438" x2="11.094" y1="16.031" y2="16.031" gradientUnits="userSpaceOnUse"><stop class="s6ok07b7w"/><stop offset="1" class="qe723acto"/></linearGradient><linearGradient id="iTxmSwb" x1="11.982" x2="14.281" y1="16.031" y2="16.375" gradientUnits="userSpaceOnUse"><stop class="bm_5h39ad"/><stop offset="1" class="unrra4rkk"/></linearGradient><linearGradient id="iLYX5Ad" x1="18.406" x2="17.438" y1="9.109" y2="10.969" gradientUnits="userSpaceOnUse"><stop class="jiup1fb8t"/><stop offset="1" class="ck6leac-q"/></linearGradient><linearGradient id="igMOaAb" x1="17.977" x2="18.203" y1="8.703" y2="9.062" gradientUnits="userSpaceOnUse"><stop class="no30r3bxv"/><stop offset="1" class="zpv3t__9s"/></linearGradient><linearGradient id="i8s3BKe" x1="11.5" x2="12.156" y1="9.344" y2="11.234" gradientUnits="userSpaceOnUse"><stop class="v8bdm5bix"/><stop offset="1" class="ck6leac-q"/></linearGradient><linearGradient id="iVKlOvk" x1="10.703" x2="11.008" y1="9.437" y2="9.5" gradientUnits="userSpaceOnUse"><stop class="mjsu73m7n"/><stop offset="1" class="p4vp38byl"/></linearGradient><linearGradient id="iDYeZHj" x1="26.344" x2="27.781" y1="21.969" y2="17.844" gradientUnits="userSpaceOnUse"><stop class="myxr_nbdx"/><stop offset="1" class="fngawe6vx"/></linearGradient><filter id="iomwzTd" width="5.693" height="5.794" x="6.026" y="5.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.804167 0 0 0 0 0.609924 0 0 0 0 0.469097 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6023"/></filter><filter id="iLEHMoe" width="7.76" height="6.613" x="10.771" y="1.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.607843 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6023"/></filter><filter id="iWx9XMS" width="6.171" height="5.774" x="18.253" y="6.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.607843 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6023"/></filter><filter id="iOk7BQb" width="5.771" height="5.774" x="18.253" y="20.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.51269 0 0 0 0 0.391111 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6023"/></filter><filter id="iBB6kJc" width="7.36" height="6.613" x="10.771" y="23.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.51269 0 0 0 0 0.391111 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6023"/></filter><filter id="irscKrd" width="5.693" height="5.794" x="4.995" y="20.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.51269 0 0 0 0 0.391111 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6023"/></filter><filter id="iDlkbZb" width="21.25" height="13.468" x="3.875" y="13.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.545098 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6023"/></filter><filter id="igizD1d" width="6.156" height="8.002" x="11.982" y="11.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.833333 0 0 0 0 0.566667 0 0 0 0 0.354167 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6023"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:blowfish" /></template>
<style>
.b1csxabjr {
  stop-color: var(--svg-color--cb867b, #CB867B);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bb0fj9b9h {
  d: path("m13.577 29.484l-2.806-5.903l7.36-.139l-2.74 6.027a1 1 0 0 1-1.814.015");
}

.bm_5h39ad {
  stop-color: var(--svg-color--e9b985, #E9B985);
}

.c1bw2j83k {
  d: path("M14.5 27.188c5.868 0 10.625-4.757 10.625-10.625c0-.93-.12-1.833-.344-2.693c-.506 1.622-1.145 3.58-2.942 4.833c-4.361 3.042-8.453 1.25-10.563-1.531c-2.37-3.125-4.946-3.458-7.076-3.226a10.7 10.7 0 0 0-.325 2.617c0 5.868 4.757 10.625 10.625 10.625");
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.c964n-4ao {
  stop-color: var(--svg-color--eaaf78, #EAAF78);
}

.cffa2xhfw {
  stop-color: var(--svg-color--d5906c, #D5906C);
  stop-opacity: 0;
}

.cfilxn3mw {
  stop-color: var(--svg-color--eda980, #EDA980);
}

.cgf1ejbpr {
  stop-color: var(--svg-color--d5906c, #D5906C);
}

.ci4rlebam {
  stop-color: var(--svg-color--f2ba8b, #F2BA8B);
  stop-opacity: 0;
}

.ck6leac-q {
  stop-color: var(--svg-color--f6bf88, #F6BF88);
  stop-opacity: 0;
}

.cox409z-b {
  stop-color: var(--svg-color--f2ba8b, #F2BA8B);
}

.cv1-vwbdm {
  d: path("m5.023 24.88l1.07-4.563l4.595 3.531L6.448 26a1 1 0 0 1-1.425-1.12");
}

.d2at_bbdl {
  stop-color: var(--svg-color--ffd1ac, #FFD1AC);
}

.du40r8bbl {
  d: path("m6.054 6.25l1.071 4.563l4.594-3.532L7.48 5.13a1 1 0 0 0-1.426 1.12");
}

.dwe12sbrw {
  stop-color: var(--svg-color--eeaa96, #EEAA96);
  stop-opacity: 0;
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.edu4b3bff {
  stop-color: var(--svg-color--fac791, #FAC791);
  stop-opacity: 0;
}

.em_gk8bnz {
  d: path("M29.152 13.798c0-.422-.351-.768-.765-.68c-1.865.394-3.262 2.01-3.262 3.942s1.397 3.549 3.262 3.943c.414.088.765-.258.765-.68z");
}

.ep4otabei {
  stop-color: var(--svg-color--fac791, #FAC791);
}

.fg05m2bds {
  stop-color: var(--svg-color--ffd1c4, #FFD1C4);
}

.fkak-i_iz {
  stop-color: var(--svg-color--e2ab95, #E2AB95);
}

.fngawe6vx {
  stop-color: var(--svg-color--cf8c6f, #CF8C6F);
  stop-opacity: 0;
}

.frekxybqd {
  stop-color: var(--svg-color--cc888a, #CC888A);
}

.ft5dv1b6b {
  fill: none;
}

.g2h2w11kb {
  d: path("m23.977 7.351l-1.395 4.475l-4.33-3.852l4.383-1.842a1 1 0 0 1 1.342 1.22");
}

.h8z_-g-_s {
  d: path("m17.1 9.512l1.048-.846a.45.45 0 0 1 .731.36l-.03 1.365l-.001-.001a1.2 1.2 0 0 1-.132.491c-.29.565-.954.802-1.486.53s-.728-.95-.44-1.515q.121-.231.31-.384");
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hjmmhkbot {
  stop-color: var(--svg-color--fcd0ae, #FCD0AE);
}

.hoi9ce21h {
  stop-color: var(--svg-color--d68a87, #D68A87);
}

.i_dw80b_l {
  cx: 4.055px;
  cy: 14.992px;
  r: 1.055px;
}

.ij70po60m {
  stop-color: var(--svg-color--dd9b59, #DD9B59);
}

.iqf74db2o {
  stop-color: var(--svg-color--f8c593, #F8C593);
  stop-opacity: 0;
}

.ir1-q_9_t {
  stop-color: var(--svg-color--dd9b59, #DD9B59);
  stop-opacity: 0;
}

.j04vgwbqr {
  stop-color: var(--svg-color--d89851, #D89851);
}

.j1v1r5drn {
  d: path("M11.982 13.875v3.75l3.696 2.083a1.65 1.65 0 0 0 2.46-1.438v-4.698a1.65 1.65 0 0 0-2.354-1.492z");
}

.j2mrz2bol {
  stop-color: var(--svg-color--cfa574, #CFA574);
}

.j9evpdb1z {
  stop-color: var(--svg-color--e9b49e, #E9B49E);
}

.jieglacql {
  cx: 4.055px;
  cy: 16.992px;
  r: 1.055px;
}

.jiup1fb8t {
  stop-color: var(--svg-color--f6bf88, #F6BF88);
}

.jo1t87len {
  stop-color: var(--svg-color--e6b480, #E6B480);
}

.llu-8u1_n {
  stop-color: var(--svg-color--ffdca5, #FFDCA5);
}

.lxb490rtn {
  stop-color: var(--svg-color--f8c593, #F8C593);
}

.m-a4dcbfn {
  stop-color: var(--svg-color--cfa574, #CFA574);
  stop-opacity: 0;
}

.mjsu73m7n {
  stop-color: var(--svg-color--e3ad75, #E3AD75);
}

.myxr_nbdx {
  stop-color: var(--svg-color--cf8c6f, #CF8C6F);
}

.n--dpzbtg {
  stop-color: var(--svg-color--eebc84, #EEBC84);
  stop-opacity: 0;
}

.nail__bjf {
  stop-color: var(--svg-color--f5bc92, #F5BC92);
}

.ngc131odg {
  d: path("M13.577 2.516L10.77 8.419l7.36.139l-2.74-6.027a1 1 0 0 0-1.814-.015");
}

.no30r3bxv {
  stop-color: var(--svg-color--edb675, #EDB675);
}

.ofburreiz {
  stop-color: var(--svg-color--d29f72, #D29F72);
}

.oyic528hr {
  stop-color: var(--svg-color--eda980, #EDA980);
  stop-opacity: 0;
}

.p_hgjbcip {
  cx: 14.5px;
  cy: 16.563px;
  r: 10.625px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
}

.p1yh9yyct {
  stop-color: var(--svg-color--cc888c, #CC888C);
}

.p4vp38byl {
  stop-color: var(--svg-color--e3ad75, #E3AD75);
  stop-opacity: 0;
}

.p7czy-b9g {
  d: path("m23.977 24.691l-1.395-4.474l-4.33 3.851l4.383 1.842a1 1 0 0 0 1.342-1.219");
}

.qe723acto {
  stop-color: var(--svg-color--e2aa82, #E2AA82);
  stop-opacity: 0;
}

.qe7k2vbdf {
  stop-color: var(--svg-color--e9aa6e, #E9AA6E);
}

.qj72jlbeh {
  cx: 14.5px;
  cy: 16.563px;
  r: 10.625px;
}

.rdaongbfw {
  stop-color: var(--svg-color--dd995b, #DD995B);
}

.s6ok07b7w {
  stop-color: var(--svg-color--e2a67a, #E2A67A);
}

.sqlykc4pm {
  stop-color: var(--svg-color--d68a87, #D68A87);
  stop-opacity: 0;
}

.tjzk_lkiq {
  stop-color: var(--svg-color--e4b693, #E4B693);
}

.tz_dj6b2f {
  stop-color: var(--svg-color--ffd4c6, #FFD4C6);
  stop-opacity: 0;
}

.unrra4rkk {
  stop-color: var(--svg-color--e9b985, #E9B985);
  stop-opacity: 0;
}

.v8bdm5bix {
  stop-color: var(--svg-color--ecb480, #ECB480);
}

.viev0sf_r {
  cx: 8.47px;
  cy: 15.328px;
  r: 0.5px;
}

.w6ngq8l7q {
  stop-color: var(--svg-color--eeaa96, #EEAA96);
}

.w7gmm3l1d {
  stop-color: var(--svg-color--cb867b, #CB867B);
}

.wg3z9zbmc {
  stop-color: var(--svg-color--fcd0ae, #FCD0AE);
  stop-opacity: 0;
}

.x59qscb1t {
  stop-color: var(--svg-color--f4b3a2, #F4B3A2);
}

.xrioznb3q {
  stop-color: var(--svg-color--eebc84, #EEBC84);
}

.y0j9fi_7t {
  stop-color: var(--svg-color--f4b3a2, #F4B3A2);
  stop-opacity: 0;
}

.ytjwdac7x {
  stop-color: var(--svg-color--ffd4c6, #FFD4C6);
}

.zpv3t__9s {
  stop-color: var(--svg-color--edb675, #EDB675);
  stop-opacity: 0;
}

.zy3jajjuv {
  d: path("m12.536 9.442l-.922-.982a.45.45 0 0 0-.774.256l-.158 1.355h.001c-.015.164.005.336.063.505c.209.599.835.926 1.399.73s.852-.842.644-1.44a1.2 1.2 0 0 0-.253-.424");
}

</style>
