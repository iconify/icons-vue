<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="eff-ob0-d"/><g filter="url(#iURtVIc)"><ellipse fill="url(#irWWcgd)" transform="rotate(26.087 17.338 9.08)" class="r4xp77bwq"/></g><g filter="url(#ivcKDFe)"><path fill="url(#iTWfEdc)" class="crbyzbt1f"/><path fill="url(#idXMLWE)" class="crbyzbt1f"/></g><g filter="url(#iJVUIjb)"><circle fill="url(#itPXKle)" class="yx_4vcb_f"/></g><circle fill="url(#iTmJ6pb)" class="m7rma2bnk"/><circle fill="url(#ikC4ggb)" class="m7rma2bnk"/><g filter="url(#iRs1hJc)"><circle class="n2fhh1biq"/></g><g filter="url(#ibSiQ3t)"><path fill="url(#iy3uhee)" class="o5ihkcskr"/><path fill="url(#i3QI26m)" class="o5ihkcskr"/></g><path fill="url(#i3v9B8b)" class="o5ihkcskr"/><path fill="url(#iYke1jb)" class="o5ihkcskr"/><path fill="url(#ioV5PFD)" class="o5ihkcskr"/><path fill="url(#iZJ5EBb)" class="o5ihkcskr"/><path fill="url(#iASa70c)" class="o5ihkcskr"/><g filter="url(#iInFGhd)"><path stroke="url(#ifX8odc)" class="qk8scsbaf"/></g><g filter="url(#iE1jEqh)"><path stroke="url(#i8i7Swb)" class="ivry3481r"/></g><defs><radialGradient id="irWWcgd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.156 15.517 -1.78)scale(8.19144 14.286)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="i6846hprv"/><stop offset=".848" class="eshz-rb6k"/></radialGradient><radialGradient id="ikC4ggb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10816 1.52067 -1.73662 -2.40753 14.464 20.918)" gradientUnits="userSpaceOnUse"><stop class="fin8ibbyo"/><stop offset="1" class="srtg8pbrk"/></radialGradient><radialGradient id="i3QI26m" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 -5.5625 6.22805 4.33864 17.5 10.829)" gradientUnits="userSpaceOnUse"><stop offset=".478" class="ivxtnnbrb"/><stop offset="1" class="eqlbbmb2a"/></radialGradient><radialGradient id="i3v9B8b" cx="0" cy="0" r="1" gradientTransform="matrix(.14338 -4.62474 6.13434 .19019 23.232 15.266)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="ggie7lb5u"/><stop offset="1" class="cp6_4jb6w"/></radialGradient><radialGradient id="iYke1jb" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.796 17.183)scale(4.97005 4.84669)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="q46v90bmy"/><stop offset="1" class="f2kyhsbtr"/></radialGradient><radialGradient id="ioV5PFD" cx="0" cy="0" r="1" gradientTransform="rotate(-115.896 19.594 6.144)scale(26.3315 19.1931)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="t_j3ms0ce"/><stop offset="1" class="x9yb4jxqn"/></radialGradient><radialGradient id="iZJ5EBb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.14 21.87883 -17.0804 -2.45134 14.584 7.982)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="boz64bi3p"/><stop offset="1" class="h74grvbep"/></radialGradient><radialGradient id="iASa70c" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 3.71875 10.344 22.142)" gradientUnits="userSpaceOnUse"><stop class="bbuj36b9c"/><stop offset="1" class="n06-_je0v"/></radialGradient><linearGradient id="iTWfEdc" x1="12.875" x2="10.121" y1="12.579" y2="18.173" gradientUnits="userSpaceOnUse"><stop class="tyevozbbh"/><stop offset="1" class="idsvehz4j"/></linearGradient><linearGradient id="idXMLWE" x1="13.563" x2="15.563" y1="27.517" y2="21.923" gradientUnits="userSpaceOnUse"><stop offset=".218" class="g5e3vv_5y"/><stop offset="1" class="why2-ob4q"/></linearGradient><linearGradient id="itPXKle" x1="14.509" x2="12.212" y1="20.489" y2="24.533" gradientUnits="userSpaceOnUse"><stop offset=".34" class="rfc_0qb7j"/><stop offset="1" class="c79pyv5gn"/></linearGradient><linearGradient id="iTmJ6pb" x1="11.755" x2="11.755" y1="19.142" y2="25.142" gradientUnits="userSpaceOnUse"><stop class="mfsy38r1n"/><stop offset="1" class="b7j8ktbah"/></linearGradient><linearGradient id="iy3uhee" x1="11.563" x2="20" y1="31.517" y2="-.858" gradientUnits="userSpaceOnUse"><stop class="ytkrke56o"/><stop offset="1" class="x4eddproi"/></linearGradient><linearGradient id="ifX8odc" x1="24.971" x2="17.565" y1="11.235" y2="3.423" gradientUnits="userSpaceOnUse"><stop class="iv9_edb6r"/><stop offset=".51" class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></linearGradient><linearGradient id="i8i7Swb" x1="8.441" x2="21.379" y1="2.017" y2="24.121" gradientUnits="userSpaceOnUse"><stop class="iv9_edb6r"/><stop offset=".698" class="w-iwpvbqx"/></linearGradient><filter id="iURtVIc" width="15.705" height="12.527" x="9.486" y="2.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4627" stdDeviation=".5"/></filter><filter id="ivcKDFe" width="12.531" height="17.719" x="7.531" y="11.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4627" stdDeviation=".25"/></filter><filter id="iJVUIjb" width="7.872" height="7.872" x="8.005" y="18.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4627" stdDeviation=".375"/></filter><filter id="iRs1hJc" width="6.128" height="6.128" x="8.691" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4627" stdDeviation=".25"/></filter><filter id="ibSiQ3t" width="19.085" height="27.786" x="6.708" y="2.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.220833 0 0 0 0 0.142622 0 0 0 0 0.193629 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4627"/></filter><filter id="iInFGhd" width="12.094" height="12.656" x="14.44" y="1.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4627" stdDeviation=".75"/></filter><filter id="iE1jEqh" width="13.063" height="23.361" x="6.941" y="6.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4627" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-dark" /></template>
<style>
.b7j8ktbah {
  stop-color: var(--svg-color--351920, #351920);
}

.bbuj36b9c {
  stop-color: var(--svg-color--50373a, #50373A);
}

.boz64bi3p {
  stop-color: var(--svg-color--432a42, #432A42);
  stop-opacity: 0;
}

.c79pyv5gn {
  stop-color: var(--svg-color--150706, #150706);
}

.cp6_4jb6w {
  stop-color: var(--svg-color--51393b, #51393B);
  stop-opacity: 0;
}

.crbyzbt1f {
  d: path("M12.577 28.735c-3.288-.25-4.546-2.063-4.546-5.304V12.173l2.344-.156l9.188 9.156l-2.938 4.969c-.989 1.845-1.68 2.593-4.049 2.593");
}

.eff-ob0-d {
  fill: var(--svg-color--51393b, #51393B);
  d: path("M6.708 23.43c0 3.242 2.581 6.18 5.868 6.431c2.37 0 4.459-1.374 5.447-3.22l5.756-10.19a9.292 9.292 0 1 0-17.072-5.084z");
}

.eqlbbmb2a {
  stop-color: var(--svg-color--351c24, #351C24);
  stop-opacity: 0;
}

.eshz-rb6k {
  stop-color: var(--svg-color--2a1521, #2A1521);
}

.f2kyhsbtr {
  stop-color: var(--svg-color--533b3d, #533B3D);
  stop-opacity: 0;
}

.fin8ibbyo {
  stop-color: var(--svg-color--725a58, #725A58);
}

.ft5dv1b6b {
  fill: none;
}

.g5e3vv_5y {
  stop-color: var(--svg-color--392828, #392828);
}

.ggie7lb5u {
  stop-color: var(--svg-color--51393b, #51393B);
}

.h74grvbep {
  stop-color: var(--svg-color--432a42, #432A42);
}

.i6846hprv {
  stop-color: var(--svg-color--2a1521, #2A1521);
  stop-opacity: 0;
}

.idsvehz4j {
  stop-color: var(--svg-color--18080b, #18080B);
  stop-opacity: 0;
}

.iv9_edb6r {
  stop-color: var(--svg-color--634f4d, #634F4D);
  stop-opacity: 0;
}

.ivry3481r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.19 9.187v14.705c.022.895.334 3.408 3.063 4.03c2.297.525 3.625-.687 4.276-1.905l1.224-2.125");
}

.ivxtnnbrb {
  stop-color: var(--svg-color--351c24, #351C24);
}

.m7rma2bnk {
  cx: 11.755px;
  cy: 22.142px;
  r: 3px;
}

.mfsy38r1n {
  stop-color: var(--svg-color--432a26, #432A26);
}

.n06-_je0v {
  stop-color: var(--svg-color--50373a, #50373A);
  stop-opacity: 0;
}

.n2fhh1biq {
  cx: 11.755px;
  cy: 22.142px;
  r: 2.564px;
  fill: var(--svg-color--4e3538, #4E3538);
}

.o5ihkcskr {
  d: path("M18.167 22.696a1.8 1.8 0 0 0-2.439.69l-.859 1.52l-.018.035c-.366.682-1.156 1.316-2.135 1.316c-1.255 0-2.408-1.428-2.408-2.826V11.367a5.692 5.692 0 1 1 11.315.891c-.147.94.126 1.974.943 2.46c.9.537 2.084.21 2.37-.797a9.292 9.292 0 1 0-18.23-2.554v12.064c.002 3.24 2.583 6.18 5.87 6.43c2.37 0 4.459-1.374 5.447-3.22l.84-1.485a1.8 1.8 0 0 0-.696-2.46");
}

.p6wb4qngy {
  stop-color: var(--svg-color--634f4d, #634F4D);
}

.q46v90bmy {
  stop-color: var(--svg-color--533b3d, #533B3D);
}

.qk8scsbaf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.94 3.579c2.291.375 6.919 2.431 7.094 7.656");
}

.r4xp77bwq {
  cx: 17.338px;
  cy: 9.081px;
  rx: 7.28px;
  ry: 4.652px;
}

.rfc_0qb7j {
  stop-color: var(--svg-color--5d4b49, #5D4B49);
}

.srtg8pbrk {
  stop-color: var(--svg-color--65504e, #65504E);
  stop-opacity: 0;
}

.t_j3ms0ce {
  stop-color: var(--svg-color--605654, #605654);
  stop-opacity: 0;
}

.tyevozbbh {
  stop-color: var(--svg-color--18080b, #18080B);
}

.w-iwpvbqx {
  stop-color: var(--svg-color--6f5552, #6F5552);
}

.why2-ob4q {
  stop-color: var(--svg-color--392828, #392828);
  stop-opacity: 0;
}

.x4eddproi {
  stop-color: var(--svg-color--56403d, #56403D);
}

.x9yb4jxqn {
  stop-color: var(--svg-color--605654, #605654);
}

.ytkrke56o {
  stop-color: var(--svg-color--462934, #462934);
}

.yx_4vcb_f {
  cx: 11.941px;
  cy: 22.328px;
  r: 3.186px;
}

</style>
