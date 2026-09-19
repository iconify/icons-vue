<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inLEbFb)"><path class="brq7roble"/><path fill="url(#iLXw0ld)" class="rn9v5ebwz"/><path fill="url(#iSQFEAc)" class="rn9v5ebwz"/></g><g filter="url(#iSO6HfN)"><path fill="url(#igSUcdc)" class="er6z23uga"/><path fill="url(#imrIoSb)" class="er6z23uga"/></g><g filter="url(#iik32nb)"><path class="g1900_bmt"/><path fill="url(#i1Dup3c)" class="pqzezbbuu"/><path fill="url(#iTsdvBb)" class="pqzezbbuu"/><path fill="url(#inPf1Ud)" class="pqzezbbuu"/><path fill="url(#iCQPzRb)" class="pqzezbbuu"/></g><g filter="url(#iE5SGmc)"><path class="aiskrc8br"/></g><path fill="url(#iRgu5eJ)" class="fjei-3fux"/><path fill="url(#iSnhCLe)" class="fjei-3fux"/><path fill="url(#iew7G3Q)" class="fjei-3fux"/><g filter="url(#iezrdpb)"><path fill="url(#iypqZle)" transform="rotate(-45 6.928 12.39)" class="k_9b8oqsz"/><path fill="url(#iMXPaee)" transform="rotate(-45 6.928 12.39)" class="k_9b8oqsz"/></g><defs><radialGradient id="imrIoSb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78126 -1.28124 1.64014 -2.28022 28.662 26.406)" gradientUnits="userSpaceOnUse"><stop class="m627u5g2x"/><stop offset="1" class="c-_9o7psl"/></radialGradient><radialGradient id="i1Dup3c" cx="0" cy="0" r="1" gradientTransform="matrix(2.15627 -2.20266 2.20324 2.15683 5.444 16.334)" gradientUnits="userSpaceOnUse"><stop class="q7_ufs0ub"/><stop offset="1" class="m09cfzbmf"/></radialGradient><radialGradient id="iTsdvBb" cx="0" cy="0" r="1" gradientTransform="rotate(-47.332 20.26 2.453)scale(4.8875 11.3328)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="qh-rxvbzu"/><stop offset=".776" class="ap8oqin0f"/></radialGradient><radialGradient id="inPf1Ud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 1.4375 -4.40954 -3.83437 6.537 13.688)" gradientUnits="userSpaceOnUse"><stop class="y5y7fdbtn"/><stop offset="1" class="na31ucalb"/></radialGradient><radialGradient id="iCQPzRb" cx="0" cy="0" r="1" gradientTransform="rotate(-177.818 3.99 6.676)scale(6.56726 8.47243)" gradientUnits="userSpaceOnUse"><stop offset=".547" class="n1pmm6bhx"/><stop offset="1" class="kxkwn6bek"/></radialGradient><radialGradient id="iSnhCLe" cx="0" cy="0" r="1" gradientTransform="rotate(136.759 7.278 5.026)scale(1.67855 .33786)" gradientUnits="userSpaceOnUse"><stop class="h0gm66blm"/><stop offset="1" class="xx6311btn"/></radialGradient><radialGradient id="iew7G3Q" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49836 2.39699 -1.91507 -2.795 15.763 8.754)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="a9zy8cc4w"/><stop offset="1" class="fasfrhbko"/></radialGradient><linearGradient id="iLXw0ld" x1="30.506" x2="26.162" y1="27.688" y2="23.344" gradientUnits="userSpaceOnUse"><stop offset=".065" class="kgv3yxbue"/><stop offset="1" class="e31_17snh"/></linearGradient><linearGradient id="iSQFEAc" x1="17.881" x2="21.444" y1="21.406" y2="17.719" gradientUnits="userSpaceOnUse"><stop offset=".058" class="m1mq_hbaa"/><stop offset="1" class="g8jajs8rt"/></linearGradient><linearGradient id="igSUcdc" x1="17.85" x2="27.037" y1="17.125" y2="26.156" gradientUnits="userSpaceOnUse"><stop class="i8baiqb6e"/><stop offset="1" class="cb2eqtb2u"/></linearGradient><linearGradient id="iRgu5eJ" x1="14.403" x2="14.306" y1="3.086" y2="4.316" gradientUnits="userSpaceOnUse"><stop class="z5j-t0xuy"/><stop offset="1" class="ev28ay-9m"/></linearGradient><linearGradient id="iypqZle" x1="14.111" x2="6.859" y1="15.388" y2="15.819" gradientUnits="userSpaceOnUse"><stop class="fddknwbru"/><stop offset="1" class="zd_66jbuq"/></linearGradient><linearGradient id="iMXPaee" x1="10.541" x2="10.563" y1="12.39" y2="13.672" gradientUnits="userSpaceOnUse"><stop offset=".111" class="o2vd8exeu"/><stop offset="1" class="ozlqh76_i"/></linearGradient><filter id="inLEbFb" width="21.374" height="21.523" x="8.049" y="8.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.384314 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23767"/></filter><filter id="iSO6HfN" width="18.428" height="18.428" x="10.938" y="9.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23767" stdDeviation=".5"/></filter><filter id="iik32nb" width="7.773" height="7.771" x="1.633" y="10.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.541176 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23767"/></filter><filter id="iE5SGmc" width="12.121" height="13.21" x="4.731" y="2.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.52549 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23767"/></filter><filter id="iezrdpb" width="10.134" height="10.134" x="5.928" y="6.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23767" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hammer" /></template>
<style>
.a9zy8cc4w {
  stop-color: var(--svg-color--eceaf4, #ECEAF4);
}

.aiskrc8br {
  fill: var(--svg-color--cac3da, #CAC3DA);
  d: path("M13.16 7.167a.5.5 0 0 0 0 .707l2.141 2.14a.4.4 0 0 1 0 .566l-5.145 5.145a.4.4 0 0 1-.566 0l-4.64-4.64a.75.75 0 0 1 0-1.06l6.557-6.557a2 2 0 0 1 1.579-.58l3.148.26a.4.4 0 0 1 .25.68z");
}

.ap8oqin0f {
  stop-color: var(--svg-color--8c889a, #8C889A);
}

.brq7roble {
  fill: var(--svg-color--a3796e, #A3796E);
  d: path("m12.201 8.46l16.362 16.362a2.936 2.936 0 1 1-4.153 4.153L8.05 12.613z");
}

.c-_9o7psl {
  stop-color: var(--svg-color--9b7775, #9B7775);
  stop-opacity: 0;
}

.cb2eqtb2u {
  stop-color: var(--svg-color--8f6969, #8F6969);
}

.e31_17snh {
  stop-color: var(--svg-color--7f494f, #7F494F);
  stop-opacity: 0;
}

.er6z23uga {
  d: path("M12.162 11.718a.766.766 0 0 1 1.083-1.082L28.14 25.532a.766.766 0 0 1-1.083 1.083z");
}

.ev28ay-9m {
  stop-color: var(--svg-color--ccccd3, #CCCCD3);
  stop-opacity: 0;
}

.fasfrhbko {
  stop-color: var(--svg-color--eceaf4, #ECEAF4);
  stop-opacity: 0;
}

.fddknwbru {
  stop-color: var(--svg-color--edeaf7, #EDEAF7);
}

.fjei-3fux {
  d: path("M13.16 7.167a.5.5 0 0 0 0 .707l2.141 2.14a.4.4 0 0 1 0 .566l-5.145 5.145a.4.4 0 0 1-.566 0l-4.64-4.64a.75.75 0 0 1 0-1.06l6.557-6.557a2 2 0 0 1 1.579-.58l3.148.26a.4.4 0 0 1 .25.68z");
}

.ft5dv1b6b {
  fill: none;
}

.g1900_bmt {
  fill: var(--svg-color--ada9b9, #ADA9B9);
  d: path("M2.74 11.281c.714-.713 1.571-.508 2.495-.05c.176.088.334.207.473.346l2.843 2.843c.1.1.19.21.261.331c.568.98.604 1.964.03 2.538l-1.105 1.073a.25.25 0 0 1-.353 0l-5.678-5.677a.25.25 0 0 1 0-.354z");
}

.g8jajs8rt {
  stop-color: var(--svg-color--7c425a, #7C425A);
  stop-opacity: 0;
}

.h0gm66blm {
  stop-color: var(--svg-color--dfdde8, #DFDDE8);
}

.i8baiqb6e {
  stop-color: var(--svg-color--a77975, #A77975);
}

.k_9b8oqsz {
  d: path("M6.928 12.39h7.225v4.278H6.928z");
}

.kgv3yxbue {
  stop-color: var(--svg-color--7f494f, #7F494F);
}

.kxkwn6bek {
  stop-color: var(--svg-color--8f8c98, #8F8C98);
}

.m09cfzbmf {
  stop-color: var(--svg-color--cabfdd, #CABFDD);
  stop-opacity: 0;
}

.m1mq_hbaa {
  stop-color: var(--svg-color--733464, #733464);
}

.m627u5g2x {
  stop-color: var(--svg-color--9b7775, #9B7775);
}

.n1pmm6bhx {
  stop-color: var(--svg-color--8f8c98, #8F8C98);
  stop-opacity: 0;
}

.na31ucalb {
  stop-color: var(--svg-color--cac1dc, #CAC1DC);
  stop-opacity: 0;
}

.o2vd8exeu {
  stop-color: var(--svg-color--b2adc0, #B2ADC0);
}

.ozlqh76_i {
  stop-color: var(--svg-color--b2adc0, #B2ADC0);
  stop-opacity: 0;
}

.pqzezbbuu {
  d: path("M2.74 11.281c.714-.713 1.571-.508 2.495-.05c.176.088.334.207.473.346l2.843 2.843c.1.1.19.21.261.331c.568.98.604 1.964.03 2.538l-1.105 1.073a.25.25 0 0 1-.353 0l-5.678-5.677a.25.25 0 0 1 0-.354z");
}

.q7_ufs0ub {
  stop-color: var(--svg-color--cabfdd, #CABFDD);
}

.qh-rxvbzu {
  stop-color: var(--svg-color--bbb9c3, #BBB9C3);
  stop-opacity: 0;
}

.rn9v5ebwz {
  d: path("m12.201 8.46l16.362 16.362a2.936 2.936 0 1 1-4.153 4.153L8.05 12.613z");
}

.xx6311btn {
  stop-color: var(--svg-color--ccc9d6, #CCC9D6);
  stop-opacity: 0;
}

.y5y7fdbtn {
  stop-color: var(--svg-color--ded9ea, #DED9EA);
}

.z5j-t0xuy {
  stop-color: var(--svg-color--ccccd3, #CCCCD3);
}

.zd_66jbuq {
  stop-color: var(--svg-color--a89abe, #A89ABE);
}

</style>
