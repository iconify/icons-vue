<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ivFtRYp)"><path class="hcyoloshc"/></g><path fill="url(#iVSZTHc)" class="vu2f16bpy"/><path fill="url(#iYIlCGe)" class="vu2f16bpy"/><path fill="url(#iu1ta4b)" class="vu2f16bpy"/><path fill="url(#iythjzd)" class="vu2f16bpy"/><path fill="url(#ihMxYUc)" class="vu2f16bpy"/><path fill="url(#iPaKs9b)" class="vu2f16bpy"/><g filter="url(#igtrZNe)"><path class="h5mpx6dkr"/></g><g filter="url(#iAqyLyd)"><path class="p37th9bna"/></g><g filter="url(#ibYmFid)"><path class="jr8v6oblj"/></g><g filter="url(#iMOJaQc)"><path fill="url(#iekQK0c)" class="x32ai7b6d"/><path fill="url(#iH9M0Kd)" class="x32ai7b6d"/></g><path fill="url(#indnc0c)" class="x32ai7b6d"/><path fill="url(#iWu52wd)" class="x32ai7b6d"/><path fill="url(#i1uLBtb)" class="x32ai7b6d"/><g filter="url(#inw2ggc)"><rect transform="rotate(-3.35 8.302 14.061)" class="e02dy6brc"/></g><g filter="url(#iPOPREe)"><path fill="url(#i23c3Hb)" class="inh5-xb7q"/><path fill="url(#i48f1zN)" class="inh5-xb7q"/><path fill="url(#ix7yLxe)" class="inh5-xb7q"/><path fill="url(#iU1rapd)" class="inh5-xb7q"/><path fill="url(#ict2xye)" class="inh5-xb7q"/></g><g filter="url(#iQQnAyd)"><rect fill="url(#iAsLNbe)" transform="rotate(-1.407 12.867 11.807)" class="ha9pd0-sq"/></g><g filter="url(#ic0rOze)"><path fill="url(#i0NzSzd)" class="mp7-bha1d"/></g><g filter="url(#i5FMxFd)"><rect transform="rotate(-1.407 18.129 11.489)" class="o4n7hx8xk"/></g><path fill="url(#i9tnVWb)" class="toyule75s"/><path fill="url(#isGKZZd)" class="toyule75s"/><path fill="url(#ieFP9Ob)" class="toyule75s"/><path fill="url(#iLiZTkb)" class="toyule75s"/><g filter="url(#iO9oPIb)"><path stroke="url(#ixNRoFc)" class="d5xlfib-d"/></g><g filter="url(#iEe9ehO)"><rect class="b1u3jxb_l"/></g><defs><radialGradient id="iVSZTHc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56216 -6.90397 4.82919 -4.5901 25.445 17.248)" gradientUnits="userSpaceOnUse"><stop class="h0sa9ub_m"/><stop offset="1" class="f7nbv1kde"/></radialGradient><radialGradient id="iYIlCGe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86066 3.08361 -3.55273 -3.29586 20.43 21.186)" gradientUnits="userSpaceOnUse"><stop class="cno7slrzv"/><stop offset="1" class="hvge-mpql"/></radialGradient><radialGradient id="iythjzd" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.28124 -1.43471 -1.1198 24.164 3.875)" gradientUnits="userSpaceOnUse"><stop class="zr6pv9g_d"/><stop offset="1" class="rr0-jacwj"/></radialGradient><radialGradient id="ihMxYUc" cx="0" cy="0" r="1" gradientTransform="matrix(2.61097 0 0 5.50045 20.023 13.017)" gradientUnits="userSpaceOnUse"><stop class="iao9-jmir"/><stop offset="1" class="u8du71z5l"/></radialGradient><radialGradient id="iPaKs9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.5119 -15.2373 0 15.862 12.2)" gradientUnits="userSpaceOnUse"><stop offset=".878" class="w6rbvxb_f"/><stop offset=".979" class="np7uh2bmw"/></radialGradient><radialGradient id="indnc0c" cx="0" cy="0" r="1" gradientTransform="matrix(.22676 -2.36686 3.52277 .3375 7.592 20.23)" gradientUnits="userSpaceOnUse"><stop class="gxd41yb8c"/><stop offset="1" class="u_186nbmy"/></radialGradient><radialGradient id="iWu52wd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05924 .64915 -1.06456 -1.73707 11.115 13.026)" gradientUnits="userSpaceOnUse"><stop class="azi9tge3n"/><stop offset="1" class="fn84-acoh"/></radialGradient><radialGradient id="ix7yLxe" cx="0" cy="0" r="1" gradientTransform="matrix(.1227 -3.11745 7.27464 .28632 12.84 19.585)" gradientUnits="userSpaceOnUse"><stop class="d8145cclf"/><stop offset="1" class="ma0or8biv"/></radialGradient><radialGradient id="iU1rapd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67768 .30875 -.56066 -1.2306 15.803 12.7)" gradientUnits="userSpaceOnUse"><stop class="k3opuobue"/><stop offset="1" class="v9596vb_s"/></radialGradient><radialGradient id="ict2xye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68416 -.7271 .95657 -2.2157 15.804 18.249)" gradientUnits="userSpaceOnUse"><stop class="d_mtak5xp"/><stop offset="1" class="c5nfprq8m"/></radialGradient><radialGradient id="iAsLNbe" cx="0" cy="0" r="1" gradientTransform="rotate(91.407 .111 13.737)scale(7.23413 3.88646)" gradientUnits="userSpaceOnUse"><stop class="ac-4el-7j"/><stop offset="1" class="lqgh_cb9k"/></radialGradient><radialGradient id="isGKZZd" cx="0" cy="0" r="1" gradientTransform="matrix(3.40306 3.0913 -2.37051 2.60958 19.62 21.933)" gradientUnits="userSpaceOnUse"><stop class="aae5f3v5e"/><stop offset="1" class="x-j9p-xeb"/></radialGradient><filter id="ivFtRYp" width="20.934" height="28.788" x="5.684" y="1.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.392157 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5612"/></filter><filter id="igtrZNe" width="14.516" height="10.203" x="12.258" y="13.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5612" stdDeviation="1.25"/></filter><filter id="iAqyLyd" width="9.153" height="11.219" x="4.823" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5612" stdDeviation="1.25"/></filter><filter id="ibYmFid" width="9.825" height="12.747" x="8.675" y="10.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5612" stdDeviation="1.25"/></filter><filter id="iMOJaQc" width="5.431" height="8.136" x="5.684" y="12.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.462745 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5612"/></filter><filter id="inw2ggc" width="4.869" height="7.227" x="6.851" y="12.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5612" stdDeviation=".75"/></filter><filter id="iPOPREe" width="5.272" height="8.719" x="10.532" y="10.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5612"/></filter><filter id="iQQnAyd" width="5.019" height="8.302" x="11.391" y="10.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5612" stdDeviation=".75"/></filter><filter id="ic0rOze" width="5.414" height="9.427" x="15.662" y="10.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.247059 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5612"/></filter><filter id="i5FMxFd" width="5.045" height="9.019" x="16.652" y="9.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5612" stdDeviation=".75"/></filter><filter id="iO9oPIb" width="8.894" height="7.704" x="17.114" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5612" stdDeviation=".625"/></filter><filter id="iEe9ehO" width="5.688" height="15.594" x="21.195" y="1.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5612" stdDeviation="1"/></filter><linearGradient id="iu1ta4b" x1="26.82" x2="23.086" y1="12.219" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="br5n8vaug"/><stop offset="1" class="jnfp_o9hi"/></linearGradient><linearGradient id="iekQK0c" x1="10.694" x2="3.81" y1="14.37" y2="14.924" gradientUnits="userSpaceOnUse"><stop class="vn4put3qq"/><stop offset="1" class="eucwrjbls"/><stop offset="1" class="zho6d19aw"/></linearGradient><linearGradient id="iH9M0Kd" x1="11.445" x2="9.683" y1="15.721" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gml9ws7sb"/><stop offset="1" class="avrjni9rw"/></linearGradient><linearGradient id="i1uLBtb" x1="5.684" x2="6.154" y1="16.391" y2="16.406" gradientUnits="userSpaceOnUse"><stop class="lo-w5o_9q"/><stop offset="1" class="s6drurbps"/></linearGradient><linearGradient id="i23c3Hb" x1="15.559" x2="10.809" y1="14.438" y2="14.906" gradientUnits="userSpaceOnUse"><stop class="taes6yb2c"/><stop offset="1" class="cce6ltb4c"/></linearGradient><linearGradient id="i48f1zN" x1="16.124" x2="14.546" y1="14.753" y2="14.756" gradientUnits="userSpaceOnUse"><stop class="g7tzf_b0v"/><stop offset="1" class="n1i303bed"/></linearGradient><linearGradient id="i0NzSzd" x1="16.653" x2="20.72" y1="13.868" y2="13.868" gradientUnits="userSpaceOnUse"><stop class="ynjt47vdk"/><stop offset="1" class="efnqmmb9h"/></linearGradient><linearGradient id="i9tnVWb" x1="24.175" x2="20.542" y1="17.178" y2="21.929" gradientUnits="userSpaceOnUse"><stop class="ja9sd94xm"/><stop offset="1" class="lpvay9bxx"/></linearGradient><linearGradient id="ieFP9Ob" x1="22.555" x2="22.519" y1="26.284" y2="22.217" gradientUnits="userSpaceOnUse"><stop offset=".382" class="ht-hbotup"/><stop offset="1" class="rz4uti6-d"/></linearGradient><linearGradient id="iLiZTkb" x1="15.758" x2="19.4" y1="19.192" y2="19.192" gradientUnits="userSpaceOnUse"><stop class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="ixNRoFc" x1="21.039" x2="24.547" y1="17.781" y2="20.397" gradientUnits="userSpaceOnUse"><stop offset=".452" class="mrfveub7y"/><stop offset="1" class="z38fdfbha"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-up-medium" /></template>
<style>
.aae5f3v5e {
  stop-color: var(--svg-color--90536c, #90536C);
}

.ac-4el-7j {
  stop-color: var(--svg-color--c9a18a, #C9A18A);
}

.avrjni9rw {
  stop-color: var(--svg-color--7b5742, #7B5742);
  stop-opacity: 0;
}

.azi9tge3n {
  stop-color: var(--svg-color--573b2a, #573B2A);
}

.b1u3jxb_l {
  width: 1.688px;
  height: 11.594px;
  x: 23.195px;
  y: 3.531px;
  fill: var(--svg-color--c9a28b, #C9A28B);
  rx: 0.844px;
}

.br5n8vaug {
  stop-color: var(--svg-color--c39b81, #C39B81);
}

.c5nfprq8m {
  stop-color: var(--svg-color--5f3436, #5F3436);
  stop-opacity: 0;
}

.cce6ltb4c {
  stop-color: var(--svg-color--8a6755, #8A6755);
}

.cno7slrzv {
  stop-color: var(--svg-color--9d6d70, #9D6D70);
}

.d_mtak5xp {
  stop-color: var(--svg-color--5f3436, #5F3436);
}

.d5xlfib-d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M18.989 17.11c1.201 0 3.21 0 3.946.944c1.075 1.052 1.137 2.589 1.198 3.009");
}

.d8145cclf {
  stop-color: var(--svg-color--945b70, #945B70);
}

.e02dy6brc {
  width: 1.722px;
  height: 4.231px;
  x: 8.302px;
  y: 14.061px;
  fill: var(--svg-color--caa18d, #CAA18D);
  rx: 0.861px;
}

.efnqmmb9h {
  stop-color: var(--svg-color--c29878, #C29878);
}

.eucwrjbls {
  stop-color: var(--svg-color--78524d, #78524D);
}

.f7nbv1kde {
  stop-color: var(--svg-color--cba387, #CBA387);
  stop-opacity: 0;
}

.fn84-acoh {
  stop-color: var(--svg-color--573b2a, #573B2A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0a9imbkr {
  stop-color: var(--svg-color--866253, #866253);
}

.g7tzf_b0v {
  stop-color: var(--svg-color--654034, #654034);
}

.gml9ws7sb {
  stop-color: var(--svg-color--7b5742, #7B5742);
}

.gv_f6obqq {
  stop-color: var(--svg-color--866253, #866253);
  stop-opacity: 0;
}

.gxd41yb8c {
  stop-color: var(--svg-color--8f5571, #8F5571);
}

.h0sa9ub_m {
  stop-color: var(--svg-color--cba387, #CBA387);
}

.h5mpx6dkr {
  fill: var(--svg-color--653546, #653546);
  d: path("M14.758 18.875c0-1.433 1.124-2.594 2.512-2.594l2.315.11c.346.042.69.14 1.008.288c1.91.805 3.389 2.644 3.68 4.805h-6.585a3 3 0 0 0-.313-.015h-.105c-1.388 0-2.512-1.162-2.512-2.594");
}

.ha9pd0-sq {
  width: 1.936px;
  height: 5.303px;
  x: 12.867px;
  y: 11.807px;
  rx: 0.968px;
}

.hcyoloshc {
  fill: var(--svg-color--a27270, #A27270);
  d: path("M23.136 1.906a2.656 2.656 0 0 0-2.656 2.657v11.25H5.684v4.227c0 5.553 4.502 10.054 10.054 10.054c4.243 0 7.873-2.629 9.348-6.347l.003.003c1.016-2.39 1.016-6.703.844-7.86a12 12 0 0 1-.14-1.496V4.563a2.656 2.656 0 0 0-2.657-2.657");
}

.ht-hbotup {
  stop-color: var(--svg-color--a27270, #A27270);
}

.hvge-mpql {
  stop-color: var(--svg-color--9d6d70, #9D6D70);
  stop-opacity: 0;
}

.iao9-jmir {
  stop-color: var(--svg-color--714b35, #714B35);
}

.inh5-xb7q {
  d: path("M10.532 13.502a2.636 2.636 0 0 1 5.272 0v3.447a2.636 2.636 0 0 1-2.636 2.636c-1.456 0-2.424-.756-2.424-2.345z");
}

.ja9sd94xm {
  stop-color: var(--svg-color--bd9473, #BD9473);
}

.jnfp_o9hi {
  stop-color: var(--svg-color--c39b81, #C39B81);
  stop-opacity: 0;
}

.jr8v6oblj {
  fill: var(--svg-color--653546, #653546);
  d: path("M11.175 15.658c0-1.294 1.08-2.343 2.412-2.343c1.333 0 2.413 1.049 2.413 2.343v3.062c0 1.294-1.08 2.343-2.413 2.343s-2.218-.672-2.218-2.084z");
}

.k3opuobue {
  stop-color: var(--svg-color--6c4c38, #6C4C38);
}

.lo-w5o_9q {
  stop-color: var(--svg-color--9c7869, #9C7869);
}

.lpvay9bxx {
  stop-color: var(--svg-color--a87777, #A87777);
}

.lqgh_cb9k {
  stop-color: var(--svg-color--c9a18a, #C9A18A);
  stop-opacity: 0;
}

.ma0or8biv {
  stop-color: var(--svg-color--945b70, #945B70);
  stop-opacity: 0;
}

.mp7-bha1d {
  d: path("M15.662 13.008c0-1.574 1.212-2.85 2.707-2.85s2.707 1.276 2.707 2.85v3.727c0 1.574-1.212 2.85-2.707 2.85s-2.707-.732-2.707-2.45z");
}

.mrfveub7y {
  stop-color: var(--svg-color--cda38d, #CDA38D);
}

.n1i303bed {
  stop-color: var(--svg-color--654034, #654034);
  stop-opacity: 0;
}

.np7uh2bmw {
  stop-color: var(--svg-color--9a597f, #9A597F);
}

.o4n7hx8xk {
  width: 1.945px;
  height: 6.02px;
  x: 18.129px;
  y: 11.489px;
  fill: var(--svg-color--d0a78f, #D0A78F);
  rx: 0.973px;
}

.p37th9bna {
  fill: var(--svg-color--653546, #653546);
  d: path("M7.323 16.103c0-1.057.843-1.844 1.914-1.913c.996-.048 1.986.563 2.07 1.776l.165 2.303c.083 1.155-.994 2.137-2.153 2.137a1.996 1.996 0 0 1-1.996-1.995z");
}

.rr0-jacwj {
  stop-color: var(--svg-color--caa288, #CAA288);
  stop-opacity: 0;
}

.rz4uti6-d {
  stop-color: var(--svg-color--a27270, #A27270);
  stop-opacity: 0;
}

.s6drurbps {
  stop-color: var(--svg-color--9c7869, #9C7869);
  stop-opacity: 0;
}

.taes6yb2c {
  stop-color: var(--svg-color--b79477, #B79477);
}

.toyule75s {
  d: path("M18.27 15.281c-1.388 0-2.512 1.161-2.512 2.594s1.124 2.594 2.512 2.594h.105c.821 0 1.64.317 2.067 1.02a6 6 0 0 1 .874 3.136c0 .878-.186 1.712-.521 2.463c2.598-.625 4.531-2.995 4.531-5.822c0-2.492-1.597-4.686-3.733-5.587a3.4 3.4 0 0 0-1.008-.288z");
}

.u_186nbmy {
  stop-color: var(--svg-color--8f5571, #8F5571);
  stop-opacity: 0;
}

.u8du71z5l {
  stop-color: var(--svg-color--714b35, #714B35);
  stop-opacity: 0;
}

.v9596vb_s {
  stop-color: var(--svg-color--6c4c38, #6C4C38);
  stop-opacity: 0;
}

.vn4put3qq {
  stop-color: var(--svg-color--ba9578, #BA9578);
}

.vu2f16bpy {
  d: path("M23.136 1.906a2.656 2.656 0 0 0-2.656 2.657v11.25H5.684v4.227c0 5.553 4.502 10.054 10.054 10.054c4.243 0 7.873-2.629 9.348-6.347l.003.003c1.016-2.39 1.016-6.703.844-7.86a12 12 0 0 1-.14-1.496V4.563a2.656 2.656 0 0 0-2.657-2.657");
}

.w6rbvxb_f {
  stop-color: var(--svg-color--9a597f, #9A597F);
  stop-opacity: 0;
}

.x-j9p-xeb {
  stop-color: var(--svg-color--90536c, #90536C);
  stop-opacity: 0;
}

.x32ai7b6d {
  d: path("M5.684 14.6c0-1.382 1.102-2.412 2.503-2.502c1.302-.063 2.596.735 2.707 2.323l.215 3.013c.108 1.51-1.3 2.796-2.815 2.796a2.61 2.61 0 0 1-2.61-2.61z");
}

.ynjt47vdk {
  stop-color: var(--svg-color--8d6a58, #8D6A58);
}

.z38fdfbha {
  stop-color: var(--svg-color--cda38d, #CDA38D);
  stop-opacity: 0;
}

.zho6d19aw {
  stop-color: var(--svg-color--936f5e, #936F5E);
}

.zr6pv9g_d {
  stop-color: var(--svg-color--caa288, #CAA288);
}

</style>
