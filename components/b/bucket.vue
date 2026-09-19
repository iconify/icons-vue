<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i904VGd)" class="x7dywu7fn"/><path fill="url(#imOGHZb)" class="x7dywu7fn"/><path fill="url(#i5dd3fe)" class="x7dywu7fn"/><path fill="url(#ix9TwOe)" class="x7dywu7fn"/><path fill="url(#iailhfO)" class="x7dywu7fn"/><path fill="url(#iYTz5PW)" class="x7dywu7fn"/><path fill="url(#iNz9eEb)" class="x7dywu7fn"/><g filter="url(#iyeqKjc)"><circle fill="url(#i6PyRvs)" class="ipm1p01jg"/><circle fill="url(#iKLHLbe)" class="ipm1p01jg"/><circle fill="url(#itNN1Me)" class="ipm1p01jg"/><circle stroke="url(#i21u7PS)" class="ifzitun9p"/><circle stroke="url(#iX0KMFF)" class="ifzitun9p"/></g><g filter="url(#ikHfKoc)"><path fill="url(#irO0xhc)" class="d0s-36h4d"/></g><path fill="url(#i9fWqpd)" class="d0s-36h4d"/><path fill="url(#imXSsrc)" class="d0s-36h4d"/><path fill="url(#ivDpNve)" class="d0s-36h4d"/><path fill="url(#itv1t5c)" class="d0s-36h4d"/><path fill="url(#iyBSEQb)" class="ykrfrdb1d"/><path fill="url(#iSb7Rcd)" class="ykrfrdb1d"/><path fill="url(#iUVoYpY)" class="ykrfrdb1d"/><path fill="url(#i5IqjDb)" class="ykrfrdb1d"/><path fill="url(#iriGIef)" class="ykrfrdb1d"/><g filter="url(#i4Zzopp)" class="v09t0acpz"><path stroke="url(#iLVVhBE)" class="va2euhb0j"/><path stroke="url(#iJ3vD7b)" class="va2euhb0j"/></g><defs><radialGradient id="i5dd3fe" cx="0" cy="0" r="1" gradientTransform="matrix(4.21875 8.375 -2.48865 1.25361 5.293 19.75)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="lovgvbcbq"/><stop offset="1" class="m5g3dobbn"/></radialGradient><radialGradient id="iailhfO" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6454 8.22986 -2.17181 -1.75369 15.418 17.125)" gradientUnits="userSpaceOnUse"><stop class="egf1zjdye"/><stop offset="1" class="p-auv6bht"/></radialGradient><radialGradient id="iNz9eEb" cx="0" cy="0" r="1" gradientTransform="matrix(5.27856 8.51417 -2.34385 1.45312 4.065 12.532)" gradientUnits="userSpaceOnUse"><stop class="rushe8jfz"/><stop offset="1" class="mjhq21byl"/></radialGradient><radialGradient id="i6PyRvs" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46877 3.03123 -3.56503 -2.90353 21.074 11.25)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="p-wer_eks"/><stop offset="1" class="ib83n2bcu"/></radialGradient><radialGradient id="iKLHLbe" cx="0" cy="0" r="1" gradientTransform="rotate(90 3.232 16.076)scale(2.14062)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="mj8feub6u"/><stop offset="1" class="qwo639bjv"/></radialGradient><radialGradient id="itNN1Me" cx="0" cy="0" r="1" gradientTransform="rotate(140.262 7.886 9.775)scale(3.37297)" gradientUnits="userSpaceOnUse"><stop offset=".592" class="j98d2bb8c"/><stop offset="1" class="tadzkz4ch"/></radialGradient><radialGradient id="i9fWqpd" cx="0" cy="0" r="1" gradientTransform="rotate(106.699 -2.167 9.09)scale(5.96218 4.37591)" gradientUnits="userSpaceOnUse"><stop class="bcbl3s2cy"/><stop offset="1" class="x-y2vpb3a"/></radialGradient><radialGradient id="imXSsrc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.241 13.806 6.051)scale(6.58476 3.04753)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ho__rxavr"/><stop offset="1" class="zags87bpt"/></radialGradient><radialGradient id="ivDpNve" cx="0" cy="0" r="1" gradientTransform="rotate(154.006 4.096 13.642)scale(6.98879 2.36829)" gradientUnits="userSpaceOnUse"><stop class="je5umu5ww"/><stop offset="1" class="x1on7acif"/></radialGradient><radialGradient id="itv1t5c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.60818 5.47708 -1.5167 -.99917 18.247 11.571)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="tt54gdcvp"/><stop offset="1" class="cr3lnab5u"/></radialGradient><radialGradient id="i5IqjDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .5625 -13.8938 0 23.793 6.406)" gradientUnits="userSpaceOnUse"><stop class="u16ju7bgj"/><stop offset="1" class="x0zbfnbpp"/></radialGradient><radialGradient id="iLVVhBE" cx="0" cy="0" r="1" gradientTransform="matrix(-4.36087 6.43758 -1.55781 -1.05527 18.48 16.113)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="zczxe8lov"/><stop offset="1" class="v6sdjlmlv"/></radialGradient><radialGradient id="iJ3vD7b" cx="0" cy="0" r="1" gradientTransform="matrix(.69873 3.488 -1.75437 .35144 3.505 21.513)" gradientUnits="userSpaceOnUse"><stop class="faza11b7e"/><stop offset="1" class="sh5x2wr6e"/></radialGradient><linearGradient id="i904VGd" x1="24.605" x2="6.543" y1="28" y2="28" gradientUnits="userSpaceOnUse"><stop offset=".104" class="kn1h6u-ky"/><stop offset="1" class="n8beuf6fs"/></linearGradient><linearGradient id="imOGHZb" x1="4.065" x2="9.543" y1="21.063" y2="19.563" gradientUnits="userSpaceOnUse"><stop class="e0586ybai"/><stop offset="1" class="kvn5fd7bt"/></linearGradient><linearGradient id="ix9TwOe" x1="16.168" x2="16.168" y1="29.344" y2="28.406" gradientUnits="userSpaceOnUse"><stop class="z7ditublr"/><stop offset="1" class="q_8_58b-v"/></linearGradient><linearGradient id="iYTz5PW" x1="15.979" x2="15.979" y1="9.001" y2="10.663" gradientUnits="userSpaceOnUse"><stop offset=".063" class="e8ybr3bdt"/><stop offset="1" class="ll5116jqa"/></linearGradient><linearGradient id="i21u7PS" x1="22.043" x2="18.512" y1="9.719" y2="14.984" gradientUnits="userSpaceOnUse"><stop class="f-crfhrey"/><stop offset=".582" class="yh4e0rbrt"/></linearGradient><linearGradient id="iX0KMFF" x1="16.512" x2="19.762" y1="15.781" y2="13.375" gradientUnits="userSpaceOnUse"><stop class="ugp0k5kpd"/><stop offset="1" class="q9-383bco"/></linearGradient><linearGradient id="irO0xhc" x1="5.346" x2="19.727" y1="23.382" y2="13.829" gradientUnits="userSpaceOnUse"><stop class="c_mx1uvmc"/><stop offset="1" class="n10iogblz"/></linearGradient><linearGradient id="iyBSEQb" x1="23.23" x2="2.903" y1="8.438" y2="8.438" gradientUnits="userSpaceOnUse"><stop class="twvkh3bia"/><stop offset=".886" class="kk77ybcyj"/></linearGradient><linearGradient id="iSb7Rcd" x1="29.512" x2="26.73" y1="9.406" y2="9.406" gradientUnits="userSpaceOnUse"><stop class="dgeo-e2bd"/><stop offset="1" class="otf8wpbkl"/></linearGradient><linearGradient id="iUVoYpY" x1="17.949" x2="17.949" y1="10.406" y2="9.281" gradientUnits="userSpaceOnUse"><stop class="y3880cmpe"/><stop offset="1" class="bgfad1bzg"/></linearGradient><linearGradient id="iriGIef" x1="2.48" x2="6.73" y1="8.438" y2="8.008" gradientUnits="userSpaceOnUse"><stop class="ljbmyrbnx"/><stop offset="1" class="lnf5nevcj"/></linearGradient><filter id="iyeqKjc" width="5.281" height="5.281" x="16.668" y="10.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26231" stdDeviation=".125"/></filter><filter id="ikHfKoc" width="18.515" height="14.979" x="1.994" y="11.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.439216 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26231"/></filter><filter id="i4Zzopp" width="18.365" height="14.329" x="2.38" y="11.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26231" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bucket" /></template>
<style>
.bcbl3s2cy {
  stop-color: var(--svg-color--938ea0, #938EA0);
}

.bgfad1bzg {
  stop-color: var(--svg-color--357fd3, #357FD3);
  stop-opacity: 0;
}

.c_mx1uvmc {
  stop-color: var(--svg-color--a7a3ae, #A7A3AE);
}

.cr3lnab5u {
  stop-color: var(--svg-color--7d8fb1, #7D8FB1);
  stop-opacity: 0;
}

.d0s-36h4d {
  d: path("m4.802 13.454l-.093.175c-.324.61-.856 1.613-1.357 2.756c-.562 1.279-1.127 2.823-1.312 4.276c-.203 1.595.282 2.868 1.12 3.772c.804.868 1.867 1.332 2.777 1.51q.081.016.185.039c.681.145 2.092.446 3.842-.075c1.939-.577 4.122-2.092 6.369-5.405c2.79-4.113 3.683-6.19 3.993-6.912l.076-.175a1.2 1.2 0 0 0-2.187-.987l-.07.162c-.285.666-1.116 2.61-3.798 6.565c-2.034 2.999-3.806 4.076-5.067 4.452c-1.145.34-2.012.16-2.67.024l-.212-.043c-.527-.103-1.212-.32-1.597-.736c-1.02-1.102-.114-3.89.538-5.336z");
}

.dgeo-e2bd {
  stop-color: var(--svg-color--5cc6f8, #5CC6F8);
}

.e0586ybai {
  stop-color: var(--svg-color--607cb1, #607CB1);
}

.e8ybr3bdt {
  stop-color: var(--svg-color--285fd8, #285FD8);
}

.egf1zjdye {
  stop-color: var(--svg-color--2469c3, #2469C3);
}

.f-crfhrey {
  stop-color: var(--svg-color--64d5ff, #64D5FF);
}

.faza11b7e {
  stop-color: var(--svg-color--a3a1ae, #A3A1AE);
}

.ft5dv1b6b {
  fill: none;
}

.ho__rxavr {
  stop-color: var(--svg-color--615d90, #615D90);
}

.ib83n2bcu {
  stop-color: var(--svg-color--66d7ff, #66D7FF);
  stop-opacity: 0;
}

.ifzitun9p {
  cx: 19.308px;
  cy: 12.844px;
  r: 2.266px;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.ipm1p01jg {
  cx: 19.308px;
  cy: 12.844px;
  r: 2.141px;
}

.j98d2bb8c {
  stop-color: var(--svg-color--2ca2ff, #2CA2FF);
  stop-opacity: 0;
}

.je5umu5ww {
  stop-color: var(--svg-color--ab83d0, #AB83D0);
}

.kk77ybcyj {
  stop-color: var(--svg-color--3374cb, #3374CB);
}

.kn1h6u-ky {
  stop-color: var(--svg-color--3ac7ff, #3AC7FF);
}

.kvn5fd7bt {
  stop-color: var(--svg-color--607cb1, #607CB1);
  stop-opacity: 0;
}

.ljbmyrbnx {
  stop-color: var(--svg-color--6c84b1, #6C84B1);
}

.ll5116jqa {
  stop-color: var(--svg-color--3b75c6, #3B75C6);
  stop-opacity: 0;
}

.lnf5nevcj {
  stop-color: var(--svg-color--6c84b1, #6C84B1);
  stop-opacity: 0;
}

.lovgvbcbq {
  stop-color: var(--svg-color--3962a3, #3962A3);
}

.m5g3dobbn {
  stop-color: var(--svg-color--3873c6, #3873C6);
  stop-opacity: 0;
}

.mj8feub6u {
  stop-color: var(--svg-color--2ea2f8, #2EA2F8);
}

.mjhq21byl {
  stop-color: var(--svg-color--637caa, #637CAA);
  stop-opacity: 0;
}

.n10iogblz {
  stop-color: var(--svg-color--b4b9cc, #B4B9CC);
}

.n8beuf6fs {
  stop-color: var(--svg-color--3872c5, #3872C5);
}

.otf8wpbkl {
  stop-color: var(--svg-color--5cc6f8, #5CC6F8);
  stop-opacity: 0;
}

.p-auv6bht {
  stop-color: var(--svg-color--398dd8, #398DD8);
  stop-opacity: 0;
}

.p-wer_eks {
  stop-color: var(--svg-color--66d7ff, #66D7FF);
}

.q_8_58b-v {
  stop-color: var(--svg-color--3c60e2, #3C60E2);
  stop-opacity: 0;
}

.q9-383bco {
  stop-color: var(--svg-color--2769c5, #2769C5);
  stop-opacity: 0;
}

.qwo639bjv {
  stop-color: var(--svg-color--2ea2f8, #2EA2F8);
  stop-opacity: 0;
}

.rushe8jfz {
  stop-color: var(--svg-color--637caa, #637CAA);
}

.sh5x2wr6e {
  stop-color: var(--svg-color--a3a1ae, #A3A1AE);
  stop-opacity: 0;
}

.tadzkz4ch {
  stop-color: var(--svg-color--296ec5, #296EC5);
}

.tt54gdcvp {
  stop-color: var(--svg-color--7d8fb1, #7D8FB1);
}

.twvkh3bia {
  stop-color: var(--svg-color--38c1ff, #38C1FF);
}

.u16ju7bgj {
  stop-color: var(--svg-color--6df, #6DF);
}

.ugp0k5kpd {
  stop-color: var(--svg-color--2769c5, #2769C5);
}

.v09t0acpz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.v6sdjlmlv {
  stop-color: var(--svg-color--dcd5e4, #DCD5E4);
  stop-opacity: 0;
}

.va2euhb0j {
  d: path("M6.198 13.968c-.614 1.167-2.33 4.281-2.656 6.844c-.318 2.492 1.5 3.672 2.937 3.953c1.263.247 4.891 1.375 9.172-4.937c3.006-4.433 3.75-6.422 3.969-6.907");
}

.x-y2vpb3a {
  stop-color: var(--svg-color--938ea0, #938EA0);
  stop-opacity: 0;
}

.x0zbfnbpp {
  stop-color: var(--svg-color--6df, #6DF);
  stop-opacity: 0;
}

.x1on7acif {
  stop-color: var(--svg-color--ab83d0, #AB83D0);
  stop-opacity: 0;
}

.x7dywu7fn {
  d: path("M4.07 7.929a.6.6 0 0 1 .595-.679h22.629a.6.6 0 0 1 .594.68L25.16 28.103a1 1 0 0 1-.991.866H7.732a1 1 0 0 1-.992-.869z");
}

.y3880cmpe {
  stop-color: var(--svg-color--2d72e5, #2D72E5);
}

.yh4e0rbrt {
  stop-color: var(--svg-color--64d5ff, #64D5FF);
  stop-opacity: 0;
}

.ykrfrdb1d {
  d: path("M2.91 6.578a.6.6 0 0 1 .594-.687h24.992a.6.6 0 0 1 .593.694l-.455 2.865a.8.8 0 0 1-.79.675H4.124a.8.8 0 0 1-.791-.683z");
}

.z7ditublr {
  stop-color: var(--svg-color--3c60e2, #3C60E2);
}

.zags87bpt {
  stop-color: var(--svg-color--88839b, #88839B);
  stop-opacity: 0;
}

.zczxe8lov {
  stop-color: var(--svg-color--dcd5e4, #DCD5E4);
}

</style>
