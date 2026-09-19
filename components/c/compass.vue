<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ilO9IDd)" class="cfyjjeuti"/><path fill="url(#i1Elded)" class="cfyjjeuti"/><path fill="url(#i5P6Y7d)" class="cfyjjeuti"/><path fill="url(#ilkyf0d)" class="cfyjjeuti"/><path fill="url(#iRlLjUd)" class="cfyjjeuti"/><path fill="url(#iaXHY5P)" class="cfyjjeuti"/><g filter="url(#iF4kvPc)"><path fill="url(#iTBlxfG)" class="lapqrq16k"/></g><g filter="url(#iTIuJ5b)"><path fill="url(#i5v4hBb)" class="e5v3pibvh"/></g><path fill="url(#iZvFPpb)" clip-rule="evenodd" class="w-56k0eej"/><path fill="url(#izYjMYb)" clip-rule="evenodd" class="w-56k0eej"/><path fill="url(#ilmkMfd)" clip-rule="evenodd" class="w-56k0eej"/><path fill="url(#iYK78Dc)" clip-rule="evenodd" class="w-56k0eej"/><path fill="url(#i8LYYZG)" clip-rule="evenodd" class="w-56k0eej"/><g filter="url(#ilpxZXb)"><path fill="url(#i33k3Jc)" class="s6xqvngsd"/><path fill="url(#izofGUd)" class="s6xqvngsd"/></g><path fill="url(#io43TFd)" class="bmsgvcsts"/><path fill="url(#i9sjOJb)" class="bmsgvcsts"/><path fill="url(#i1LvMqe)" class="t3j6l3bct"/><path fill="url(#iEJFCRc)" class="t3j6l3bct"/><path class="cy639056o"/><g filter="url(#iNFaCac)"><path fill="url(#it3Wksb)" class="mrcdhh2wo"/></g><g filter="url(#i8yGHTd)"><path class="kq40zwudd"/></g><g filter="url(#i1owh6b)"><path fill="url(#iE63K5d)" class="dgq1m3b7g"/></g><g filter="url(#icwoRLd)"><path stroke="url(#i5YuEyO)" class="x2o8cac8d"/></g><g filter="url(#iNJiJid)"><path stroke="url(#isexkJO)" class="p6kf17b-z"/></g><g filter="url(#iipF7ic)"><path stroke="url(#itG8Jsd)" class="fu7sv7wtg"/></g><defs><radialGradient id="i1Elded" cx="0" cy="0" r="1" gradientTransform="rotate(-32.005 24.07 -39.569)scale(6.76952 6.23488)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="vlbukxfda"/><stop offset=".942" class="rb3idpbms"/></radialGradient><radialGradient id="i5P6Y7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.33678 -1.49194 1.51953 1.3615 27.289 4.814)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="wud1aibrx"/><stop offset="1" class="zl4b51beh"/></radialGradient><radialGradient id="ilkyf0d" cx="0" cy="0" r="1" gradientTransform="rotate(134.772 13.214 7.827)scale(4.64777 4.46393)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="q1am7acfz"/><stop offset="1" class="cmz035r2k"/></radialGradient><radialGradient id="iRlLjUd" cx="0" cy="0" r="1" gradientTransform="rotate(-112.148 14.513 -4.905)scale(1.40019 3.90267)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="erpcljb3o"/><stop offset=".736" class="iy5piym3g"/></radialGradient><radialGradient id="iaXHY5P" cx="0" cy="0" r="1" gradientTransform="matrix(.89844 -.06252 .17425 2.50417 25.434 8)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="erpcljb3o"/><stop offset=".736" class="iy5piym3g"/></radialGradient><radialGradient id="iTBlxfG" cx="0" cy="0" r="1" gradientTransform="rotate(-135.277 14.332 -2.26)scale(1.14354 2.65509)" gradientUnits="userSpaceOnUse"><stop class="noia57awg"/><stop offset=".788" class="ofenxib1n"/></radialGradient><radialGradient id="i5v4hBb" cx="0" cy="0" r="1" gradientTransform="matrix(17.14236 6.4991 -8.85744 23.36281 5.207 11.695)" gradientUnits="userSpaceOnUse"><stop class="p6frhhbyb"/><stop offset="1" class="ot6bb7byn"/></radialGradient><radialGradient id="izYjMYb" cx="0" cy="0" r="1" gradientTransform="rotate(-29.785 47.261 3.51)scale(28.2295 22.1446)" gradientUnits="userSpaceOnUse"><stop offset=".873" class="xlbq4wb7y"/><stop offset="1" class="o69avcviw"/></radialGradient><radialGradient id="ilmkMfd" cx="0" cy="0" r="1" gradientTransform="rotate(119.722 6.315 10.533)scale(21.8559 17.2879)" gradientUnits="userSpaceOnUse"><stop offset=".873" class="qruu2xinu"/><stop offset=".975" class="xhwjtzb1o"/></radialGradient><radialGradient id="iYK78Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-45.843 27.07 -11.069)scale(12.0221 12.6674)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="hi0bahbvo"/><stop offset=".939" class="zgeagbcbt"/></radialGradient><radialGradient id="i8LYYZG" cx="0" cy="0" r="1" gradientTransform="matrix(-29.8039 0 0 -19.6734 31.051 16.5)" gradientUnits="userSpaceOnUse"><stop offset=".952" class="tk-0n24qd"/><stop offset="1" class="u-cnxrv7f"/></radialGradient><radialGradient id="izofGUd" cx="0" cy="0" r="1" gradientTransform="rotate(105.642 .637 14.734)scale(1.21695 2.23861)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="hhkr4ccjy"/><stop offset=".983" class="ysv8r2_az"/></radialGradient><radialGradient id="i9sjOJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45575 .55084 -.52343 -1.38331 14.38 17.031)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="hhkr4ccjy"/><stop offset="1" class="ysv8r2_az"/></radialGradient><radialGradient id="iEJFCRc" cx="0" cy="0" r="1" gradientTransform="rotate(129.144 2.849 12.306)scale(.87257 1.3323)" gradientUnits="userSpaceOnUse"><stop offset=".459" class="hhkr4ccjy"/><stop offset="1" class="ysv8r2_az"/></radialGradient><radialGradient id="iE63K5d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41602 3.1532 -3.28745 -3.56145 17.34 15.336)" gradientUnits="userSpaceOnUse"><stop class="gkeavfbau"/><stop offset="1" class="oj5qh7fya"/></radialGradient><linearGradient id="ilO9IDd" x1="25.242" x2="30" y1="7.498" y2="3.042" gradientUnits="userSpaceOnUse"><stop class="y_hu5hblg"/><stop offset="1" class="ca6r6u3rd"/></linearGradient><linearGradient id="iZvFPpb" x1="5.59" x2="24.215" y1="25.813" y2="7.187" gradientUnits="userSpaceOnUse"><stop class="b_2imhb-w"/><stop offset="1" class="w8l-7-koj"/></linearGradient><linearGradient id="i33k3Jc" x1="15.5" x2="15.5" y1="8.002" y2="24.997" gradientUnits="userSpaceOnUse"><stop class="fuuwgtb2l"/><stop offset="1" class="p5jpl1bua"/></linearGradient><linearGradient id="io43TFd" x1="21.148" x2="8.243" y1="15.93" y2="15.93" gradientUnits="userSpaceOnUse"><stop class="pf94eob0y"/><stop offset="1" class="v0u7ltbhh"/></linearGradient><linearGradient id="i1LvMqe" x1="19.635" x2="11.715" y1="12.813" y2="21.188" gradientUnits="userSpaceOnUse"><stop class="jmi6bmb7p"/><stop offset="1" class="qnr7g9bbp"/></linearGradient><linearGradient id="it3Wksb" x1="10.454" x2="14.521" y1="11.802" y2="16.548" gradientUnits="userSpaceOnUse"><stop class="j7mysnooi"/><stop offset="1" class="jd2epeb6q"/></linearGradient><linearGradient id="i5YuEyO" x1="2.465" x2="13.715" y1="14.75" y2="28.906" gradientUnits="userSpaceOnUse"><stop class="ektqrnbkc"/><stop offset=".516" class="ctmnfmbal"/><stop offset="1" class="ektqrnbkc"/></linearGradient><linearGradient id="isexkJO" x1="31.362" x2="19.172" y1="18.355" y2="2.055" gradientUnits="userSpaceOnUse"><stop class="vx-6ngb4w"/><stop offset=".315" class="q2h5b4hok"/><stop offset=".672" class="q2h5b4hok"/><stop offset="1" class="vx-6ngb4w"/></linearGradient><linearGradient id="itG8Jsd" x1="27.856" x2="29.903" y1="2.531" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="rp518mb0d"/><stop offset=".464" class="zpet9yv4t"/><stop offset="1" class="rp518mb0d"/></linearGradient><filter id="iF4kvPc" width="3.148" height="2.998" x="23.99" y="5.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.537255 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4887"/></filter><filter id="iTIuJ5b" width="23.995" height="23.995" x="3.002" y="5.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.482353 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4887"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.431373 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4887" result="effect2_innerShadow_18_4887"/></filter><filter id="ilpxZXb" width="3.21" height="16.995" x="13.92" y="8.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.521569 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4887"/></filter><filter id="iNFaCac" width="7.322" height="7.462" x="9.888" y="10.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.239216 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4887"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_18_4887" result="effect2_innerShadow_18_4887"/></filter><filter id="i8yGHTd" width="7.192" height="7.452" x="13.78" y="14.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.462745 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4887"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_18_4887" result="effect2_innerShadow_18_4887"/></filter><filter id="i1owh6b" width="5.01" height="5.01" x="13.07" y="13.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.368627 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4887"/></filter><filter id="icwoRLd" width="13.496" height="17.438" x="2.782" y="12.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4887" stdDeviation=".25"/></filter><filter id="iNJiJid" width="14.641" height="18.83" x="14.75" y="2.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4887" stdDeviation=".375"/></filter><filter id="iipF7ic" width="2.703" height="3.375" x="27.528" y="2.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4887" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:compass" /></template>
<style>
.b_2imhb-w {
  stop-color: var(--svg-color--de8d39, #DE8D39);
}

.bmsgvcsts {
  d: path("m15.5 18.08l8.25-1.29c.33-.05.33-.53 0-.58l-8.25-1.29l-8.25 1.29c-.33.05-.33.53 0 .58z");
}

.ca6r6u3rd {
  stop-color: var(--svg-color--f6c942, #F6C942);
}

.cfyjjeuti {
  d: path("M27 8c-1.65 0-3-1.35-3-3s1.35-3 3-3s3 1.35 3 3s-1.35 3-3 3m0-4.62a1.609 1.609 0 1 0 0 3.22a1.609 1.609 0 1 0 0-3.22");
}

.cmz035r2k {
  stop-color: var(--svg-color--ca7412, #CA7412);
}

.ctmnfmbal {
  stop-color: var(--svg-color--ffbd6a, #FFBD6A);
}

.cy639056o {
  fill: var(--svg-color--ccc, #CCC);
  d: path("m14.7 17.29l4.51 3.29c.24.18.54-.12.37-.37l-3.29-4.51l-4.51-3.29c-.24-.18-.54.12-.37.37z");
}

.dgq1m3b7g {
  d: path("M15.5 18.93a2.43 2.43 0 1 0 0-4.86a2.43 2.43 0 0 0 0 4.86");
}

.e5v3pibvh {
  d: path("M15.5 27.998c6.35 0 11.497-5.148 11.497-11.498S21.85 5.002 15.5 5.002S4.002 10.15 4.002 16.5S9.15 27.997 15.5 27.997");
}

.ektqrnbkc {
  stop-color: var(--svg-color--ffbd6a, #FFBD6A);
  stop-opacity: 0;
}

.erpcljb3o {
  stop-color: var(--svg-color--7c3d03, #7C3D03);
}

.ft5dv1b6b {
  fill: none;
}

.fu7sv7wtg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M28.028 2.531a2.51 2.51 0 0 1 1.703 2.375");
}

.fuuwgtb2l {
  stop-color: var(--svg-color--b6acb7, #B6ACB7);
}

.gkeavfbau {
  stop-color: var(--svg-color--c0bcbf, #C0BCBF);
}

.hhkr4ccjy {
  stop-color: var(--svg-color--5f4d63, #5F4D63);
}

.hi0bahbvo {
  stop-color: var(--svg-color--b88245, #B88245);
}

.iy5piym3g {
  stop-color: var(--svg-color--7c3d03, #7C3D03);
  stop-opacity: 0;
}

.j7mysnooi {
  stop-color: var(--svg-color--e43465, #E43465);
}

.jd2epeb6q {
  stop-color: var(--svg-color--e6386a, #E6386A);
}

.jmi6bmb7p {
  stop-color: var(--svg-color--b6acb8, #B6ACB8);
}

.kq40zwudd {
  fill: var(--svg-color--6b656e, #6B656E);
  d: path("m17.21 14.78l3.7 6.51c.23.41-.22.86-.63.63l-6.5-3.71z");
}

.lapqrq16k {
  d: path("m25.35 8l-1.36-1.36l1.36-1.36c.37-.37.98-.37 1.36 0c.37.37.37.98 0 1.36z");
}

.mrcdhh2wo {
  d: path("m13.78 18.21l-3.73-6.52c-.23-.41.22-.86.63-.63l6.53 3.72z");
}

.noia57awg {
  stop-color: var(--svg-color--ffe160, #FFE160);
}

.o69avcviw {
  stop-color: var(--svg-color--ffed6a, #FFED6A);
}

.ofenxib1n {
  stop-color: var(--svg-color--f3b535, #F3B535);
}

.oj5qh7fya {
  stop-color: var(--svg-color--856f79, #856F79);
}

.ot6bb7byn {
  stop-color: var(--svg-color--dfd2e2, #DFD2E2);
}

.p5jpl1bua {
  stop-color: var(--svg-color--968c98, #968C98);
}

.p6frhhbyb {
  stop-color: var(--svg-color--b5a7b0, #B5A7B0);
}

.p6kf17b-z {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M15.5 3.437c6.813 0 14.997 6.407 12.205 16.859");
}

.pf94eob0y {
  stop-color: var(--svg-color--b6abb8, #B6ABB8);
}

.q1am7acfz {
  stop-color: var(--svg-color--ca7412, #CA7412);
  stop-opacity: 0;
}

.q2h5b4hok {
  stop-color: var(--svg-color--ffe55a, #FFE55A);
}

.qnr7g9bbp {
  stop-color: var(--svg-color--958b97, #958B97);
}

.qruu2xinu {
  stop-color: var(--svg-color--b66635, #B66635);
  stop-opacity: 0;
}

.rb3idpbms {
  stop-color: var(--svg-color--ffea6a, #FFEA6A);
}

.rp518mb0d {
  stop-color: var(--svg-color--ffe967, #FFE967);
  stop-opacity: 0;
}

.s6xqvngsd {
  d: path("m17.08 16.5l-1.29-8.25c-.05-.33-.53-.33-.58 0l-1.29 8.25l1.29 8.25c.05.33.53.33.58 0z");
}

.t3j6l3bct {
  d: path("m16.29 17.29l3.29-4.51c.18-.24-.12-.54-.37-.37L14.7 15.7l-3.29 4.51c-.18.24.12.54.37.37z");
}

.tk-0n24qd {
  stop-color: var(--svg-color--f58d49, #F58D49);
  stop-opacity: 0;
}

.u-cnxrv7f {
  stop-color: var(--svg-color--f58d49, #F58D49);
}

.v0u7ltbhh {
  stop-color: var(--svg-color--988e9a, #988E9A);
}

.vlbukxfda {
  stop-color: var(--svg-color--ffea6a, #FFEA6A);
  stop-opacity: 0;
}

.vx-6ngb4w {
  stop-color: var(--svg-color--ffe55a, #FFE55A);
  stop-opacity: 0;
}

.w-56k0eej {
  fill-rule: evenodd;
  d: path("M29 16.5C29 23.956 22.956 30 15.5 30S2 23.956 2 16.5S8.044 3 15.5 3S29 9.044 29 16.5m-2.46 0c0 6.097-4.943 11.04-11.04 11.04S4.46 22.597 4.46 16.5S9.403 5.46 15.5 5.46s11.04 4.943 11.04 11.04");
}

.w8l-7-koj {
  stop-color: var(--svg-color--edc14b, #EDC14B);
}

.wud1aibrx {
  stop-color: var(--svg-color--c0813e, #C0813E);
}

.x2o8cac8d {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.778 28.75c-6.813 0-14.25-6.562-11.75-16.125");
}

.xhwjtzb1o {
  stop-color: var(--svg-color--b66635, #B66635);
}

.xlbq4wb7y {
  stop-color: var(--svg-color--ffed6a, #FFED6A);
  stop-opacity: 0;
}

.y_hu5hblg {
  stop-color: var(--svg-color--e2881c, #E2881C);
}

.ysv8r2_az {
  stop-color: var(--svg-color--5f4d63, #5F4D63);
  stop-opacity: 0;
}

.zgeagbcbt {
  stop-color: var(--svg-color--b88245, #B88245);
  stop-opacity: 0;
}

.zl4b51beh {
  stop-color: var(--svg-color--c0813e, #C0813E);
  stop-opacity: 0;
}

.zpet9yv4t {
  stop-color: var(--svg-color--ffe967, #FFE967);
}

</style>
