<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itP4wJe)" class="g7dg_hb-e"/><path fill="url(#i6Duuac)" class="g7dg_hb-e"/><path fill="url(#iScsX0J)" class="g7dg_hb-e"/><g filter="url(#ibTzdpr)"><path stroke="url(#in3ZXRd)" class="a7rt79bgx"/></g><path fill="url(#isUfTub)" class="uns7topkc"/><path fill="url(#isWNiRb)" class="wt6wpr8gk"/><path fill="url(#i1mlc4u)" class="wt6wpr8gk"/><path fill="url(#icXaBac)" class="wt6wpr8gk"/><path fill="url(#iP1G0de)" class="wt6wpr8gk"/><path fill="url(#iko1qLe)" class="wt6wpr8gk"/><path fill="url(#iDLAOvS)" class="wt6wpr8gk"/><path fill="url(#i91tfLe)" class="wt6wpr8gk"/><path fill="url(#i1GuNDc)" class="wt6wpr8gk"/><path fill="url(#iRXHeOe)" class="wt6wpr8gk"/><g filter="url(#ifMh6zC)"><path fill="url(#iPZ3CFd)" class="g9x6zccyg"/></g><g filter="url(#idOABoc)"><path stroke="url(#iZwX8rb)" class="b1qifes7s"/></g><g filter="url(#iTelzze)"><path stroke="url(#ihbg2bd)" class="al20i_b1d"/></g><g filter="url(#i56O3wb)"><path class="i8iqcsbov"/></g><path fill="url(#i7wkxxb)" class="y9e5tjbii"/><path fill="url(#iHlvK5b)" class="deicx7byz"/><path fill="url(#iytL4md)" class="deicx7byz"/><path fill="url(#ijFuoSd)" class="gyw7l0b0f"/><path fill="url(#iBGweVX)" class="cphsz9buq"/><path fill="url(#iRTRi0c)" class="cphsz9buq"/><path fill="url(#iwm5zfb)" class="cphsz9buq"/><path fill="url(#i5KD08c)" class="gav72bxhr"/><path fill="url(#iwR13kd)" class="gav72bxhr"/><path fill="url(#iNCuS5d)" class="gav72bxhr"/><path fill="url(#i5FXIYb)" class="gav72bxhr"/><path stroke="url(#imBFAJe)" class="csdp96byc"/><path stroke="url(#ikExiNe)" class="csdp96byc"/><g filter="url(#iJTCsps)"><path stroke="url(#iEPLcCe)" class="f2w7uzirh"/></g><path fill="url(#iuJElhc)" class="vndbscczr"/><path fill="url(#iHH9Ynd)" class="vndbscczr"/><path fill="url(#i4olJOb)" class="vndbscczr"/><rect fill="url(#ivoqsvd)" class="db9p_tz-p"/><rect fill="url(#i8U0L8b)" class="db9p_tz-p"/><g filter="url(#ie0kuve)"><path stroke="url(#iAHjHSz)" class="ne_wpacnw"/></g><g filter="url(#it0dwub)"><path class="r2nz2bclh"/></g><path fill="url(#i58b1Jc)" class="tbtpchpvw"/><g filter="url(#iQcN2zL)"><path stroke="url(#iquboPa)" class="e6u9h_btk"/></g><defs><linearGradient id="in3ZXRd" x1="29.054" x2="30.592" y1="16.848" y2="21.675" gradientUnits="userSpaceOnUse"><stop class="sf4ccx8mv"/><stop offset="1" class="qf9031xau"/></linearGradient><linearGradient id="isUfTub" x1="20.598" x2="20.598" y1="29.839" y2="21.536" gradientUnits="userSpaceOnUse"><stop class="s_kfmocrz"/><stop offset=".271" class="mj1lbccfd"/><stop offset=".994" class="l2hj6g1rl"/></linearGradient><linearGradient id="isWNiRb" x1="15.63" x2="15.63" y1="11.351" y2="25.645" gradientUnits="userSpaceOnUse"><stop class="s9mpcpxhg"/><stop offset=".309" class="l3vc0lcuq"/><stop offset="1" class="ovd3hup4k"/></linearGradient><linearGradient id="i91tfLe" x1=".443" x2="6.446" y1="7.762" y2="13.471" gradientUnits="userSpaceOnUse"><stop class="h_avyzaqk"/><stop offset="1" class="ns_ocfb2c"/></linearGradient><linearGradient id="iZwX8rb" x1="27.912" x2="24.694" y1="22.311" y2="30.332" gradientUnits="userSpaceOnUse"><stop class="v6orbzbuk"/><stop offset="1" class="w1gg0unfz"/></linearGradient><linearGradient id="ihbg2bd" x1="11.596" x2="13.409" y1="10.001" y2="14.495" gradientUnits="userSpaceOnUse"><stop class="j_6z93m2j"/><stop offset="1" class="w1gg0unfz"/></linearGradient><linearGradient id="i7wkxxb" x1="14.9" x2="14.9" y1="29.849" y2="21.536" gradientUnits="userSpaceOnUse"><stop class="s_kfmocrz"/><stop offset=".271" class="mj1lbccfd"/><stop offset=".994" class="l2hj6g1rl"/></linearGradient><linearGradient id="iHlvK5b" x1="3.849" x2="2.599" y1="11.599" y2="11.599" gradientUnits="userSpaceOnUse"><stop offset=".225" class="mp43u-g5l"/><stop offset="1" class="vzlnlu3vr"/></linearGradient><linearGradient id="iytL4md" x1="4.443" x2="4.443" y1="12.611" y2="11.346" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ijFuoSd" x1="16.625" x2="16.625" y1="20.359" y2="21.859" gradientUnits="userSpaceOnUse"><stop class="rchblb2th"/><stop offset="1" class="ut9t04d2s"/></linearGradient><linearGradient id="iBGweVX" x1="9.818" x2="11.818" y1="7.49" y2="10.584" gradientUnits="userSpaceOnUse"><stop class="cpg0vp_yn"/><stop offset=".313" class="dowtrkbmj"/><stop offset="1" class="s9mpcpxhg"/></linearGradient><linearGradient id="iwm5zfb" x1="9.646" x2="10.958" y1="11.109" y2="10.719" gradientUnits="userSpaceOnUse"><stop class="h_avyzaqk"/><stop offset="1" class="ns_ocfb2c"/></linearGradient><linearGradient id="iwR13kd" x1="14.63" x2="14.63" y1="12.156" y2="14.313" gradientUnits="userSpaceOnUse"><stop class="fu3sgebmt"/><stop offset="1" class="zkm6yny6o"/></linearGradient><linearGradient id="iNCuS5d" x1="7.599" x2="11.2" y1="16.156" y2="16.594" gradientUnits="userSpaceOnUse"><stop class="fu3sgebmt"/><stop offset=".613" class="zkm6yny6o"/></linearGradient><linearGradient id="i5FXIYb" x1="13.568" x2="13.568" y1="21.873" y2="18.688" gradientUnits="userSpaceOnUse"><stop class="p4x-dfwxs"/><stop offset=".613" class="mewsk_bou"/></linearGradient><linearGradient id="imBFAJe" x1="14.63" x2="7.443" y1="12.349" y2="16.569" gradientUnits="userSpaceOnUse"><stop class="ytdw6svci"/><stop offset="1" class="a5mcaysqs"/></linearGradient><linearGradient id="ikExiNe" x1="9.661" x2="10.765" y1="18.406" y2="15.844" gradientUnits="userSpaceOnUse"><stop class="nmws8q3vf"/><stop offset="1" class="md9ucccro"/></linearGradient><linearGradient id="iEPLcCe" x1="8.599" x2="14.864" y1="15.25" y2="11.75" gradientUnits="userSpaceOnUse"><stop class="mcej0ybhp"/><stop offset=".59" class="fdlfjeiox"/><stop offset="1" class="mcej0ybhp"/></linearGradient><linearGradient id="iuJElhc" x1="12.318" x2="22.255" y1="10.969" y2="6.431" gradientUnits="userSpaceOnUse"><stop class="go54d-j5c"/><stop offset="1" class="q4s3-k6ho"/></linearGradient><linearGradient id="iHH9Ynd" x1="13.38" x2="14.568" y1="10.406" y2="11.094" gradientUnits="userSpaceOnUse"><stop class="qblwj6lmz"/><stop offset="1" class="sw5x1ry7d"/></linearGradient><linearGradient id="ivoqsvd" x1="7.978" x2="7.353" y1="10.849" y2="10.849" gradientUnits="userSpaceOnUse"><stop offset=".225" class="mp43u-g5l"/><stop offset="1" class="vzlnlu3vr"/></linearGradient><linearGradient id="i8U0L8b" x1="8.275" x2="8.275" y1="12.199" y2="10.511" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iAHjHSz" x1="12.936" x2="12.465" y1="9.544" y2="11.305" gradientUnits="userSpaceOnUse"><stop class="v6orbzbuk"/><stop offset="1" class="w1gg0unfz"/></linearGradient><linearGradient id="i58b1Jc" x1="4.628" x2="4.628" y1="15.585" y2="13.746" gradientUnits="userSpaceOnUse"><stop class="x3zw5bcxe"/><stop offset="1" class="kazkw750e"/></linearGradient><linearGradient id="iquboPa" x1="23.521" x2="13.913" y1="7.834" y2="7.692" gradientUnits="userSpaceOnUse"><stop class="eubufg7eo"/><stop offset="1" class="qe-d67btz"/></linearGradient><radialGradient id="itP4wJe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22745 -6.81254 6.82285 -5.23536 30.567 21.969)" gradientUnits="userSpaceOnUse"><stop class="tc_lbd7by"/><stop offset="1" class="pnibiqbec"/></radialGradient><radialGradient id="i6Duuac" cx="0" cy="0" r="1" gradientTransform="matrix(1.82125 -2.625 3.94568 2.73755 25.34 19.281)" gradientUnits="userSpaceOnUse"><stop class="jxryhm5yf"/><stop offset="1" class="kd7wheb1u"/></radialGradient><radialGradient id="iScsX0J" cx="0" cy="0" r="1" gradientTransform="matrix(.0111 -1.40962 1.97367 .01554 29.72 23.74)" gradientUnits="userSpaceOnUse"><stop class="tkqclqbzn"/><stop offset="1" class="ws2p3fb5s"/></radialGradient><radialGradient id="i1mlc4u" cx="0" cy="0" r="1" gradientTransform="matrix(5.49792 -5.37738 8.31716 8.5036 22.248 27.02)" gradientUnits="userSpaceOnUse"><stop class="ovd3hup4k"/><stop offset="1" class="j6tdy5ydd"/></radialGradient><radialGradient id="icXaBac" cx="0" cy="0" r="1" gradientTransform="rotate(-32.451 44.01 7.79)scale(13.4009 19.6181)" gradientUnits="userSpaceOnUse"><stop class="ovd3hup4k"/><stop offset="1" class="j6tdy5ydd"/></radialGradient><radialGradient id="iP1G0de" cx="0" cy="0" r="1" gradientTransform="matrix(2.40536 -2.68867 3.80738 3.4062 22.435 27.208)" gradientUnits="userSpaceOnUse"><stop class="n8v7ws_-j"/><stop offset="1" class="zsnoq_buv"/></radialGradient><radialGradient id="iko1qLe" cx="0" cy="0" r="1" gradientTransform="matrix(.375 -4.0625 13.14422 1.21331 8.005 32.531)" gradientUnits="userSpaceOnUse"><stop class="n8v7ws_-j"/><stop offset="1" class="zsnoq_buv"/></radialGradient><radialGradient id="iDLAOvS" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.4375 11.12206 .20221 26.817 32.094)" gradientUnits="userSpaceOnUse"><stop class="n8v7ws_-j"/><stop offset="1" class="zsnoq_buv"/></radialGradient><radialGradient id="i1GuNDc" cx="0" cy="0" r="1" gradientTransform="rotate(170.53 9.339 6.523)scale(5.89062 1.54856)" gradientUnits="userSpaceOnUse"><stop class="h_avyzaqk"/><stop offset="1" class="ns_ocfb2c"/></radialGradient><radialGradient id="iRXHeOe" cx="0" cy="0" r="1" gradientTransform="matrix(3.31127 2.3135 -2.81004 4.02195 3.754 21.643)" gradientUnits="userSpaceOnUse"><stop class="qtr_-gj2q"/><stop offset="1" class="puy1rrb4z"/></radialGradient><radialGradient id="iPZ3CFd" cx="0" cy="0" r="1" gradientTransform="rotate(134.525 9.64 12.397)scale(9.33634 4.48114)" gradientUnits="userSpaceOnUse"><stop class="v6orbzbuk"/><stop offset="1" class="k1g7agbrm"/></radialGradient><radialGradient id="iRTRi0c" cx="0" cy="0" r="1" gradientTransform="matrix(.0469 4.14062 -4.67157 .05292 11.66 8.74)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="ns_ocfb2c"/><stop offset="1" class="h_avyzaqk"/></radialGradient><radialGradient id="i5KD08c" cx="0" cy="0" r="1" gradientTransform="rotate(-165.118 8.641 7.556)scale(2.31192 1.99291)" gradientUnits="userSpaceOnUse"><stop class="m60_bp8oc"/><stop offset="1" class="cr3r28bcb"/></radialGradient><radialGradient id="i4olJOb" cx="0" cy="0" r="1" gradientTransform="rotate(131.402 10.35 8.205)scale(3.59118 3.15823)" gradientUnits="userSpaceOnUse"><stop class="c7-gcwbqf"/><stop offset="1" class="yhqt9mbik"/></radialGradient><filter id="ibTzdpr" width="4.268" height="7.348" x="25.977" y="14.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation=".375"/></filter><filter id="ifMh6zC" width="8.906" height="8.438" x="19.13" y="10.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation="1"/></filter><filter id="idOABoc" width="7.313" height="18.344" x="22.769" y="12.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation="1"/></filter><filter id="iTelzze" width="6.907" height="9.569" x="9.408" y="8.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation=".75"/></filter><filter id="i56O3wb" width="6.013" height="6.433" x="7.744" y="6.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation=".5"/></filter><filter id="iJTCsps" width="6.913" height="4.053" x="7.392" y="12.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation=".1"/></filter><filter id="ie0kuve" width="3.125" height="5.391" x="10.882" y="6.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation=".5"/></filter><filter id="it0dwub" width="1.855" height="1.978" x="21.227" y="5.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation=".25"/></filter><filter id="iQcN2zL" width="4.503" height=".8" x="17.449" y="6.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1751" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:guide-dog" /></template>
<style>
.a5mcaysqs {
  stop-color: var(--svg-color--3e62dc, #3E62DC);
}

.a7rt79bgx {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m26.802 15.11l2.594 2.906v2.875");
}

.al20i_b1d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11.909 10.558l1.906 4.568");
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b1qifes7s {
  stroke-linecap: round;
  d: path("M25.27 15.186v7.201c0 .088.046.17.122.215l2.068 1.23a.25.25 0 0 1 .122.215v4.482");
}

.c7-gcwbqf {
  stop-color: var(--svg-color--c7c5c7, #C7C5C7);
}

.cpg0vp_yn {
  stop-color: var(--svg-color--e89a49, #E89A49);
}

.cphsz9buq {
  d: path("M9.286 7.48a.5.5 0 0 1 .485-.621h2.919c.73 0 1.27.69 1.09 1.4l-.6 2.39c-.18.71-.82 1.21-1.55 1.21s-1.38-.5-1.55-1.21z");
}

.cr3r28bcb {
  stop-color: var(--svg-color--8d4d40, #8D4D40);
}

.csdp96byc {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("m6.9 16.569l7.73-4.22");
}

.db9p_tz-p {
  width: 1px;
  height: 2px;
  x: 7.119px;
  y: 9.849px;
  rx: 0.5px;
}

.deicx7byz {
  d: path("M3.38 12.349h-.5a.749.749 0 1 1 0-1.5h.5a.749.749 0 1 1 0 1.5");
}

.dowtrkbmj {
  stop-color: var(--svg-color--eaa054, #EAA054);
}

.e6u9h_btk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M17.849 6.617h3.703");
}

.eubufg7eo {
  stop-color: var(--svg-color--96668b, #96668B);
}

.f2w7uzirh {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-opacity: 0.8;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m7.693 16.172l6.312-3.453");
}

.fdlfjeiox {
  stop-color: var(--svg-color--7dc7ff, #7DC7FF);
}

.ft5dv1b6b {
  fill: none;
}

.fu3sgebmt {
  stop-color: var(--svg-color--773c26, #773C26);
}

.g7dg_hb-e {
  d: path("m26.17 13.389l3.26 3.67c.45.51.7 1.17.7 1.85v3.62c0 .24-.27.38-.46.24a3.57 3.57 0 0 1-1.54-2.95v-.63c0-.2-.08-.39-.22-.53l-2.57-2.49z");
}

.g9x6zccyg {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M26.036 16.248c-.2-2.65-2.15-3.375-3.234-3.406l-1.672 4.437z");
}

.gav72bxhr {
  d: path("M14.13 12.349c0-.28.22-.5.5-.5s.5.23.5.5v2.844a1.37 1.37 0 0 1 0 2.552v4.128h-1v-4.128a1.38 1.38 0 0 1-.732-.676H6.9c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h6.42c.122-.401.423-.724.81-.876z");
}

.go54d-j5c {
  stop-color: var(--svg-color--75707c, #75707C);
}

.gyw7l0b0f {
  d: path("m12.46 20.459l-.34 1.4h6.85c.77 0 1.51-.17 2.16-.48c0-.84-.68-1.53-1.53-1.53h-6.37a.8.8 0 0 0-.77.61");
}

.h_avyzaqk {
  stop-color: var(--svg-color--ca9068, #CA9068);
}

.i8iqcsbov {
  fill: var(--svg-color--d68e5d, #D68E5D);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M8.76 7.96a.5.5 0 0 1 .484-.622h2.516a.998.998 0 0 1 .966 1.24l-.532 2.12a1.406 1.406 0 0 1-1.374 1.073a1.42 1.42 0 0 1-1.374-1.073z");
}

.j_6z93m2j {
  stop-color: var(--svg-color--ffdaad, #FFDAAD);
}

.j6tdy5ydd {
  stop-color: var(--svg-color--ff8b68, #FF8B68);
  stop-opacity: 0;
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jxryhm5yf {
  stop-color: var(--svg-color--c46116, #C46116);
}

.k1g7agbrm {
  stop-color: var(--svg-color--ffdaad, #FFDAAD);
  stop-opacity: 0;
}

.kazkw750e {
  stop-color: var(--svg-color--eb8d98, #EB8D98);
  stop-opacity: 0;
}

.kd7wheb1u {
  stop-color: var(--svg-color--c36116, #C36116);
  stop-opacity: 0;
}

.l2hj6g1rl {
  stop-color: var(--svg-color--cf6247, #CF6247);
}

.l3vc0lcuq {
  stop-color: var(--svg-color--f7bc86, #F7BC86);
}

.m60_bp8oc {
  stop-color: var(--svg-color--aa6354, #AA6354);
}

.mcej0ybhp {
  stop-color: var(--svg-color--80c8ff, #80C8FF);
  stop-opacity: 0;
}

.md9ucccro {
  stop-color: var(--svg-color--4361d6, #4361D6);
  stop-opacity: 0;
}

.mewsk_bou {
  stop-color: var(--svg-color--903f51, #903F51);
  stop-opacity: 0;
}

.mj1lbccfd {
  stop-color: var(--svg-color--e99974, #E99974);
}

.mp43u-g5l {
  stop-color: var(--svg-color--6b5e60, #6B5E60);
}

.n8v7ws_-j {
  stop-color: var(--svg-color--c734c1, #C734C1);
}

.ne_wpacnw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m12.757 7.914l-.625 2.89");
}

.nmws8q3vf {
  stop-color: var(--svg-color--4361d6, #4361D6);
}

.ns_ocfb2c {
  stop-color: var(--svg-color--ca9068, #CA9068);
  stop-opacity: 0;
}

.ovd3hup4k {
  stop-color: var(--svg-color--ff8b68, #FF8B68);
}

.p4x-dfwxs {
  stop-color: var(--svg-color--903f51, #903F51);
}

.pnibiqbec {
  stop-color: var(--svg-color--e99a5c, #E99A5C);
}

.puy1rrb4z {
  stop-color: var(--svg-color--ffc531, #FFC531);
  stop-opacity: 0;
}

.q4s3-k6ho {
  stop-color: var(--svg-color--a19997, #A19997);
}

.qblwj6lmz {
  stop-color: var(--svg-color--847971, #847971);
}

.qe-d67btz {
  stop-color: var(--svg-color--96668b, #96668B);
  stop-opacity: 0;
}

.qf9031xau {
  stop-color: var(--svg-color--ffdeab, #FFDEAB);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.r2nz2bclh {
  fill: var(--svg-color--c7c5c7, #C7C5C7);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m22.352 6.36l.23.18l-.624.798l-.23-.18z");
}

.rchblb2th {
  stop-color: var(--svg-color--ffc4c7, #FFC4C7);
}

.s_kfmocrz {
  stop-color: var(--svg-color--eb8d98, #EB8D98);
}

.s9mpcpxhg {
  stop-color: var(--svg-color--f5bf86, #F5BF86);
}

.sf4ccx8mv {
  stop-color: var(--svg-color--ffdeab, #FFDEAB);
}

.sw5x1ry7d {
  stop-color: var(--svg-color--847971, #847971);
  stop-opacity: 0;
}

.tbtpchpvw {
  d: path("M7.126 7.44v7.686a.31.31 0 0 0-.306-.26H5.13c-1.66 0-3-1.34-3-3v-.24c0-.42.34-.76.76-.76H4.4c.43 0 .81-.29.91-.71l.09-.36a3.87 3.87 0 0 1 1.726-2.357");
}

.tc_lbd7by {
  stop-color: var(--svg-color--fec494, #FEC494);
}

.tkqclqbzn {
  stop-color: var(--svg-color--d878d4, #D878D4);
}

.uns7topkc {
  d: path("M23.08 20.849h-3l-1.95 8.69c-.04.16.08.3.24.3h2.44c.15 0 .27-.1.3-.24z");
}

.ut9t04d2s {
  stop-color: var(--svg-color--f595be, #F595BE);
}

.v6orbzbuk {
  stop-color: var(--svg-color--ffe39b, #FFE39B);
}

.vndbscczr {
  d: path("M13.66 10.869c.1.25.23.66.46 1.02l3.87-4.93c.05-.06.12-.1.2-.1h3.34l-7.29 9.29c-.17.22-.13.53.08.7a.493.493 0 0 0 .7-.08l7.61-9.69c.18-.23.21-.53.08-.79a.73.73 0 0 0-.67-.42h-3.85c-.39 0-.74.17-.98.48z");
}

.vzlnlu3vr {
  stop-color: var(--svg-color--433338, #433338);
}

.w1gg0unfz {
  stop-color: var(--svg-color--ffdaac, #FFDAAC);
  stop-opacity: 0;
}

.ws2p3fb5s {
  stop-color: var(--svg-color--d878d4, #D878D4);
  stop-opacity: 0;
}

.wt6wpr8gk {
  d: path("m28.44 22.389l-1.17-.78a.31.31 0 0 1-.14-.25v-5.28c0-2.46-2.09-4.4-4.54-4.21l-6.82.84c-1.47.19-1.87-1.24-2.11-1.84l-1.25-3.12c-.22-.54-.74-.9-1.32-.9H9.15a3.85 3.85 0 0 0-3.74 2.92l-.1.38c-.1.41-.48.71-.91.71H2.89c-.42 0-.76.33-.76.75v.25c0 1.66 1.34 3 3 3h1.69c.17-.01.31.13.31.31v1.88c0 1.79.71 3.51 1.98 4.77l-1.73 7.74c-.04.16.08.3.24.3h2.44c.15 0 .27-.1.3-.24l1.74-7.77h.3v.01h6.56c.77 0 1.51-.17 2.16-.48a3.75 3.75 0 0 0 2.36 3.42l2.45.98c.12.05.2.16.2.29v3.48c0 .17.14.31.31.31h2.38c.17 0 .31-.14.31-.31v-5.85c0-.53-.26-1.02-.69-1.31");
}

.x3zw5bcxe {
  stop-color: var(--svg-color--bd44b1, #BD44B1);
}

.y9e5tjbii {
  d: path("M12.67 20.849h3l1.46 8.71c.03.15-.09.29-.25.29h-2.44a.32.32 0 0 1-.31-.26z");
}

.yhqt9mbik {
  stop-color: var(--svg-color--c7c5c7, #C7C5C7);
  stop-opacity: 0;
}

.ytdw6svci {
  stop-color: var(--svg-color--58b1fc, #58B1FC);
}

.zkm6yny6o {
  stop-color: var(--svg-color--773c26, #773C26);
  stop-opacity: 0;
}

.zsnoq_buv {
  stop-color: var(--svg-color--c734c1, #C734C1);
  stop-opacity: 0;
}

</style>
