<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iQWl79b)" class="gg4bcybux"/><circle fill="url(#iq6xKIe)" class="gg4bcybux"/><circle fill="url(#iSjvYDd)" class="gg4bcybux"/><g filter="url(#iU3szQP)"><path fill="url(#iKjaZPc)" class="jul03jc5v"/><path fill="url(#irgK9cb)" class="jul03jc5v"/><path fill="url(#iziYU3c)" class="jul03jc5v"/><path fill="url(#iN077rb)" class="jul03jc5v"/></g><g filter="url(#ikanUAd)"><path fill="url(#ikyzKRc)" class="c6-xt9bad"/><path fill="url(#iSidcpb)" class="c6-xt9bad"/></g><g filter="url(#isaqy9c)"><path fill="url(#icba4Le)" class="qrs7r6-hf"/><path fill="url(#iMzAWVJ)" class="qrs7r6-hf"/></g><path fill="url(#iID5Kbe)" class="qrs7r6-hf"/><g filter="url(#idgalPo)"><path fill="url(#iJfyLRb)" class="wf6ac5bph"/></g><path fill="url(#i8N6vgc)" class="wf6ac5bph"/><g filter="url(#ikKFNDb)" class="mc2zb0bvp"><circle fill="url(#iGZtaMd)" class="i6tk58rfk"/></g><g filter="url(#iSZhB6c)" class="mc2zb0bvp"><circle fill="url(#iKRkgOd)" class="eexisua8y"/></g><circle fill="url(#iYDejwc)" class="tqkm6nh-n"/><circle fill="url(#iJgndOd)" class="tqkm6nh-n"/><circle fill="url(#iuntsEc)" class="i7y61s8nw"/><circle fill="url(#i7CQ8hd)" class="i7y61s8nw"/><g filter="url(#ijUby9b)"><path fill="url(#iPdRL3c)" class="vqz0r0b9w"/></g><defs><radialGradient id="iQWl79b" cx="0" cy="0" r="1" gradientTransform="rotate(137.517 13.618 7.535)scale(4.02555 3.83366)" gradientUnits="userSpaceOnUse"><stop class="kv_z8ismh"/><stop offset="1" class="uov5nuvbb"/></radialGradient><radialGradient id="iq6xKIe" cx="0" cy="0" r="1" gradientTransform="rotate(-158.106 14.48 -.392)scale(3.60365)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="kio9qjins"/><stop offset="1" class="xz4l-gwqy"/></radialGradient><radialGradient id="iSjvYDd" cx="0" cy="0" r="1" gradientTransform="rotate(82.316 11.41 17.585)scale(3.97318)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="o129u0bmd"/><stop offset=".955" class="qo9zwvpsf"/></radialGradient><radialGradient id="irgK9cb" cx="0" cy="0" r="1" gradientTransform="rotate(86.085 7.41 14.662)scale(8.95403)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="qkjdsl5ds"/><stop offset=".988" class="w-3ba6blh"/></radialGradient><radialGradient id="iziYU3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93748 2.09376 -2.65178 -2.45386 25.969 6.894)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="sw0q2ebnr"/><stop offset="1" class="e4yau3x4e"/></radialGradient><radialGradient id="ikyzKRc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.625 10.5625 -4.39128 -4.41726 11.688 20.613)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="czyng5bqy"/><stop offset="1" class="xwof5jbgv"/></radialGradient><radialGradient id="icba4Le" cx="0" cy="0" r="1" gradientTransform="matrix(11.31647 -.99585 2.22889 25.32832 5.086 26.746)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="i75fy45wg"/><stop offset="1" class="zm7sm_j3o"/></radialGradient><radialGradient id="i8N6vgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.09388 14.3438 -12.93712 -.08467 21.344 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="tnocwt7ts"/><stop offset="1" class="pk34ntblj"/></radialGradient><radialGradient id="iYDejwc" cx="0" cy="0" r="1" gradientTransform="rotate(161.565 10.17 10.946)scale(3.06346 2.46065)" gradientUnits="userSpaceOnUse"><stop offset=".381" class="px78kzh0q"/><stop offset="1" class="t-7d1-b8q"/></radialGradient><radialGradient id="iJgndOd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 .60937 -.53008 -.91066 23.188 18.175)" gradientUnits="userSpaceOnUse"><stop class="xp3dkwb-b"/><stop offset="1" class="kh64sqsdx"/></radialGradient><radialGradient id="iuntsEc" cx="0" cy="0" r="1" gradientTransform="rotate(161.565 6.571 5.951)scale(3.06346 2.46065)" gradientUnits="userSpaceOnUse"><stop offset=".381" class="px78kzh0q"/><stop offset="1" class="t-7d1-b8q"/></radialGradient><radialGradient id="i7CQ8hd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 .60937 -.53008 -.91066 14.594 9.582)" gradientUnits="userSpaceOnUse"><stop class="xp3dkwb-b"/><stop offset="1" class="kh64sqsdx"/></radialGradient><linearGradient id="iKjaZPc" x1="26.281" x2="18.719" y1="6.238" y2="13.176" gradientUnits="userSpaceOnUse"><stop class="dzufet25l"/><stop offset="1" class="qclbir_-i"/></linearGradient><linearGradient id="iN077rb" x1="26.125" x2="25.887" y1="6.332" y2="6.566" gradientUnits="userSpaceOnUse"><stop offset=".23" class="qg5zgfblu"/><stop offset="1" class="hmirut9hf"/></linearGradient><linearGradient id="iSidcpb" x1="15.406" x2="13.551" y1="13.166" y2="15.792" gradientUnits="userSpaceOnUse"><stop offset=".152" class="skli5fbae"/><stop offset="1" class="qqt09pbci"/></linearGradient><linearGradient id="iMzAWVJ" x1="18.983" x2="15.905" y1="17.286" y2="18.327" gradientUnits="userSpaceOnUse"><stop offset=".158" class="v0yqtab1o"/><stop offset="1" class="r3ebbfb_x"/></linearGradient><linearGradient id="iID5Kbe" x1="10.158" x2="10.627" y1="21.734" y2="22.215" gradientUnits="userSpaceOnUse"><stop offset=".236" class="x5-bhg5-n"/><stop offset="1" class="pwx62rxsn"/></linearGradient><linearGradient id="iJfyLRb" x1="18.75" x2="14.875" y1="13.269" y2="17.644" gradientUnits="userSpaceOnUse"><stop class="zq1dcfb_g"/><stop offset="1" class="ibr73x8od"/></linearGradient><linearGradient id="iGZtaMd" x1="14.529" x2="12.09" y1="8.865" y2="11.49" gradientUnits="userSpaceOnUse"><stop class="km6_kbc8h"/><stop offset="1" class="c44nhac9f"/></linearGradient><linearGradient id="iKRkgOd" x1="23.103" x2="20.703" y1="17.479" y2="20.061" gradientUnits="userSpaceOnUse"><stop class="jeesjs3le"/><stop offset="1" class="fneauob5w"/></linearGradient><linearGradient id="iPdRL3c" x1="21.936" x2="28.465" y1="12.881" y2="6.954" gradientUnits="userSpaceOnUse"><stop class="kr40xgbtx"/><stop offset="1" class="vzdv1yyfy"/></linearGradient><filter id="iU3szQP" width="11.651" height="10.651" x="16.817" y="4.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.337255 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23956"/></filter><filter id="ikanUAd" width="17.808" height="17.697" x="2.011" y="12.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.729412 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23956"/></filter><filter id="isaqy9c" width="17.466" height="15.434" x="2.252" y="14.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.439216 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23956"/></filter><filter id="idgalPo" width="14.702" height="14.702" x="10.189" y="7.097" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.666667 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23956"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.35" dy=".35"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.921569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23956" result="effect2_innerShadow_18_23956"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.764706 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23956" result="effect3_innerShadow_18_23956"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.560784 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_23956" result="effect4_innerShadow_18_23956"/></filter><filter id="ikKFNDb" width="4.252" height="4.252" x="11.167" y="7.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23956" stdDeviation=".1"/></filter><filter id="iSZhB6c" width="4.189" height="4.189" x="19.792" y="16.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23956" stdDeviation=".1"/></filter><filter id="ijUby9b" width="7.922" height="7.922" x="19.406" y="5.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23956" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dagger" /></template>
<style>
.c44nhac9f {
  stop-color: var(--svg-color--e98c07, #E98C07);
}

.c6-xt9bad {
  d: path("m14.64 12.254l5.079 5.078l-8.103 8.124a16 16 0 0 1-7.474 4.231l-.854.212c-.827.183-1.48-.102-1.22-1.18l.047-.214a16 16 0 0 1 4.272-7.908z");
}

.czyng5bqy {
  stop-color: var(--svg-color--ddd9e1, #DDD9E1);
}

.dzufet25l {
  stop-color: var(--svg-color--a46a4b, #A46A4B);
}

.e4yau3x4e {
  stop-color: var(--svg-color--af715e, #AF715E);
  stop-opacity: 0;
}

.eexisua8y {
  cx: 21.887px;
  cy: 18.695px;
  r: 1.895px;
}

.fneauob5w {
  stop-color: var(--svg-color--e7901c, #E7901C);
}

.ft5dv1b6b {
  fill: none;
}

.gg4bcybux {
  cx: 27.062px;
  cy: 4.898px;
  r: 2.762px;
}

.hmirut9hf {
  stop-color: var(--svg-color--b56b44, #B56B44);
  stop-opacity: 0;
}

.i6tk58rfk {
  cx: 13.293px;
  cy: 10.101px;
  r: 1.926px;
}

.i75fy45wg {
  stop-color: var(--svg-color--b8adc3, #B8ADC3);
}

.i7y61s8nw {
  cx: 13.293px;
  cy: 10.101px;
  r: 1.684px;
}

.ibr73x8od {
  stop-color: var(--svg-color--f09c3f, #F09C3F);
}

.jeesjs3le {
  stop-color: var(--svg-color--ffb843, #FFB843);
}

.jul03jc5v {
  d: path("M24.26 4.623a.24.24 0 0 0-.166-.072a3 3 0 0 0-2.16.879l-4.238 4.238a3 3 0 0 0 0 4.242l.413.414a3 3 0 0 0 4.243 0l4.238-4.238a3 3 0 0 0 .878-2.16a.24.24 0 0 0-.071-.166z");
}

.kh64sqsdx {
  stop-color: var(--svg-color--f85c94, #F85C94);
  stop-opacity: 0;
}

.kio9qjins {
  stop-color: var(--svg-color--ffb730, #FFB730);
  stop-opacity: 0;
}

.km6_kbc8h {
  stop-color: var(--svg-color--ffc437, #FFC437);
}

.kr40xgbtx {
  stop-color: var(--svg-color--ac6e5b, #AC6E5B);
}

.kv_z8ismh {
  stop-color: var(--svg-color--fff25c, #FFF25C);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.o129u0bmd {
  stop-color: var(--svg-color--feb13b, #FEB13B);
  stop-opacity: 0;
}

.pk34ntblj {
  stop-color: var(--svg-color--db8959, #DB8959);
}

.pwx62rxsn {
  stop-color: var(--svg-color--b1a4bc, #B1A4BC);
  stop-opacity: 0;
}

.px78kzh0q {
  stop-color: var(--svg-color--e7317c, #E7317C);
}

.qclbir_-i {
  stop-color: var(--svg-color--ad5f48, #AD5F48);
}

.qg5zgfblu {
  stop-color: var(--svg-color--b56b44, #B56B44);
}

.qkjdsl5ds {
  stop-color: var(--svg-color--984a63, #984A63);
  stop-opacity: 0;
}

.qo9zwvpsf {
  stop-color: var(--svg-color--d79568, #D79568);
}

.qqt09pbci {
  stop-color: var(--svg-color--d7d0d6, #D7D0D6);
  stop-opacity: 0;
}

.qrs7r6-hf {
  d: path("m17.203 14.816l2.516 2.516l-8.103 8.124a16 16 0 0 1-7.474 4.231l-.854.212c-.425.094-.803.064-1.036-.132z");
}

.r3ebbfb_x {
  stop-color: var(--svg-color--896d89, #896D89);
  stop-opacity: 0;
}

.skli5fbae {
  stop-color: var(--svg-color--c5b4ba, #C5B4BA);
}

.sw0q2ebnr {
  stop-color: var(--svg-color--c28c73, #C28C73);
}

.t-7d1-b8q {
  stop-color: var(--svg-color--db193e, #DB193E);
}

.tnocwt7ts {
  stop-color: var(--svg-color--f4a03a, #F4A03A);
  stop-opacity: 0;
}

.tqkm6nh-n {
  cx: 21.887px;
  cy: 18.695px;
  r: 1.684px;
}

.uov5nuvbb {
  stop-color: var(--svg-color--ffb936, #FFB936);
}

.v0yqtab1o {
  stop-color: var(--svg-color--896d89, #896D89);
}

.vqz0r0b9w {
  d: path("m24.826 6.752l1.502 1.502l-4.127 4.127a1 1 0 0 1-1.414 0l-.088-.088a1 1 0 0 1 0-1.414z");
}

.vzdv1yyfy {
  stop-color: var(--svg-color--ac6e5b, #AC6E5B);
  stop-opacity: 0;
}

.w-3ba6blh {
  stop-color: var(--svg-color--984a63, #984A63);
}

.wf6ac5bph {
  d: path("M14.186 13.08c-.181-.18-.442-.25-.698-.232a2.754 2.754 0 1 1 2.56-2.747c-.001.2.063.397.204.537l5.098 5.098c.14.14.338.205.537.205a2.754 2.754 0 1 1-2.747 2.56c.017-.257-.051-.518-.233-.7z");
}

.x5-bhg5-n {
  stop-color: var(--svg-color--c9c2d0, #C9C2D0);
}

.xp3dkwb-b {
  stop-color: var(--svg-color--f85c94, #F85C94);
}

.xwof5jbgv {
  stop-color: var(--svg-color--d6ced0, #D6CED0);
}

.xz4l-gwqy {
  stop-color: var(--svg-color--daa850, #DAA850);
}

.zm7sm_j3o {
  stop-color: var(--svg-color--a89bb2, #A89BB2);
}

.zq1dcfb_g {
  stop-color: var(--svg-color--ffd847, #FFD847);
}

</style>
