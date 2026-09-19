<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iE1s6jM)" class="hzhhxobhr"/><circle fill="url(#i2BV3Ee)" class="v4njjjb5c"/><circle fill="url(#ixkzove)" class="z8_6nyb5k"/><circle fill="url(#i7ynmUb)" class="g7e7gkbcp"/><circle fill="url(#iuwxm1b)" class="n7wfd3-1q"/><circle fill="url(#iXwBeqb)" class="ue7k3b0uc"/><g filter="url(#i5hakjS)"><ellipse fill="url(#iYJL89c)" class="q-chsnb8y"/></g><g filter="url(#iPvmNGY)"><ellipse stroke="url(#i9CWxOr)" class="yucabbkpm"/></g><g filter="url(#iJizztd)"><ellipse fill="url(#isDD1Fn)" class="q0-t4opzm"/><ellipse fill="url(#i83VqGc)" class="q0-t4opzm"/></g><g filter="url(#iVcpwsb)"><path class="el0eup0eg"/></g><g filter="url(#ih6iInc)"><path fill="url(#ir4Qnxb)" class="i79w9-4rf"/><path fill="url(#iiZIQmb)" class="i79w9-4rf"/></g><g filter="url(#ifTSMme)"><path fill="url(#i9VQrvc)" class="wjxie-btm"/><path fill="url(#iI932Bj)" class="wjxie-btm"/></g><g filter="url(#i8Tnldc)"><circle fill="url(#iBbffHb)" class="mrqojibgm"/></g><g filter="url(#iTBHsQH)"><circle fill="url(#idOIJid)" class="mr_562b4g"/></g><g filter="url(#iMt54gf)"><circle fill="url(#iFF81jb)" class="qswx5ub2m"/></g><g filter="url(#iTVTZZb)"><circle fill="url(#i82tcMd)" class="ofjeuzd2k"/></g><g filter="url(#iy13bnd)"><path class="oh-7k1b7h"/><path fill="url(#iRNnzHb)" class="elbf_abir"/><path fill="url(#iHla49L)" class="elbf_abir"/></g><defs><radialGradient id="iE1s6jM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5486 2.72657 -1.97443 -1.1214 13.227 26.426)" gradientUnits="userSpaceOnUse"><stop class="wh6gi0bvm"/><stop offset="1" class="mzl4sybet"/></radialGradient><radialGradient id="i2BV3Ee" cx="0" cy="0" r="1" gradientTransform="rotate(165.855 7.514 14.275)scale(1.77427 1.53113)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="wh6gi0bvm"/><stop offset="1" class="mzl4sybet"/></radialGradient><radialGradient id="ixkzove" cx="0" cy="0" r="1" gradientTransform="rotate(150.068 7.48 13.367)scale(2.37993 2.53589)" gradientUnits="userSpaceOnUse"><stop offset=".376" class="wh6gi0bvm"/><stop offset="1" class="mzl4sybet"/></radialGradient><radialGradient id="i7ynmUb" cx="0" cy="0" r="1" gradientTransform="rotate(150.998 4.043 7.589)scale(1.6436 1.1902)" gradientUnits="userSpaceOnUse"><stop class="wh6gi0bvm"/><stop offset="1" class="mzl4sybet"/></radialGradient><radialGradient id="iuwxm1b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8828 1.50782 -1.09188 -1.36343 7.07 13.906)" gradientUnits="userSpaceOnUse"><stop class="wh6gi0bvm"/><stop offset="1" class="mzl4sybet"/></radialGradient><radialGradient id="iXwBeqb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5486 2.72657 -1.97443 -1.1214 4.27 17.469)" gradientUnits="userSpaceOnUse"><stop class="wh6gi0bvm"/><stop offset="1" class="mzl4sybet"/></radialGradient><radialGradient id="i9CWxOr" cx="0" cy="0" r="1" gradientTransform="matrix(.26636 8.48547 -7.2989 .22911 17.359 14.186)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="hllbawbrh"/><stop offset="1" class="byc8z_6ck"/></radialGradient><radialGradient id="i83VqGc" cx="0" cy="0" r="1" gradientTransform="matrix(4.28125 -4.125 6.5579 6.8063 6.82 26.031)" gradientUnits="userSpaceOnUse"><stop class="wviudcr9d"/><stop offset="1" class="x402jqbak"/></radialGradient><radialGradient id="iBbffHb" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 0 0 -.82813 23.617 4.636)" gradientUnits="userSpaceOnUse"><stop class="ol9jz0t8n"/><stop offset="1" class="q5rcpdbvu"/></radialGradient><radialGradient id="idOIJid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 .12781 -.12097 -1.02036 25.086 2.734)" gradientUnits="userSpaceOnUse"><stop class="kfn0g2bvg"/><stop offset="1" class="e_3z3ibak"/></radialGradient><radialGradient id="iFF81jb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 .12781 -.12097 -1.02036 29.797 7.125)" gradientUnits="userSpaceOnUse"><stop class="u2-djxd-d"/><stop offset="1" class="xhthexh3c"/></radialGradient><radialGradient id="i82tcMd" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 0 0 -.82813 27.817 8.503)" gradientUnits="userSpaceOnUse"><stop class="ol9jz0t8n"/><stop offset="1" class="q5rcpdbvu"/></radialGradient><radialGradient id="iRNnzHb" cx="0" cy="0" r="1" gradientTransform="rotate(135.461 13.14 8.217)scale(1.62462 3.47825)" gradientUnits="userSpaceOnUse"><stop class="up5zi985n"/><stop offset="1" class="g0abp1bzn"/></radialGradient><filter id="i5hakjS" width="16.438" height="16.406" x="3.211" y="12.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.192157 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.337255 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18868" result="effect2_innerShadow_18_18868"/></filter><filter id="iPvmNGY" width="16.447" height="16.419" x="3.145" y="12.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18868" stdDeviation=".25"/></filter><filter id="iJizztd" width="14.119" height="14.094" x="4.07" y="13.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_18868"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_18868" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.6 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_18868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.937255 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_18868" result="effect3_innerShadow_18_18868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.690196 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_18868" result="effect4_innerShadow_18_18868"/></filter><filter id="iVcpwsb" width="4.833" height="4.833" x="7.945" y="19.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.701961 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.752941 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18868" result="effect2_innerShadow_18_18868"/></filter><filter id="ih6iInc" width="4.719" height="4.711" x="4.65" y="22.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.741176 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/></filter><filter id="ifTSMme" width="13.245" height="14.007" x="12.7" y="5.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.156863 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18868" result="effect2_innerShadow_18_18868"/></filter><filter id="i8Tnldc" width="1.656" height="1.656" x="22.445" y="3.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.635294 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/></filter><filter id="iTBHsQH" width="1.656" height="1.656" x="23.711" y="2.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.678431 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/></filter><filter id="iMt54gf" width="1.656" height="1.656" x="28.422" y="6.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.678431 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/></filter><filter id="iTVTZZb" width="1.656" height="1.656" x="26.645" y="7.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.635294 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/></filter><filter id="iy13bnd" width="6.053" height="6.402" x="23.39" y="2.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.286275 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18868"/></filter><linearGradient id="iYJL89c" x1="18.227" x2="5.195" y1="14.938" y2="26.313" gradientUnits="userSpaceOnUse"><stop offset=".106" class="c-ysp3n7t"/><stop offset="1" class="g2vlv9bfh"/></linearGradient><linearGradient id="isDD1Fn" x1="14.883" x2="5.258" y1="22.75" y2="19.688" gradientUnits="userSpaceOnUse"><stop class="y__4qo8od"/><stop offset="1" class="sk8q5ibot"/></linearGradient><linearGradient id="ir4Qnxb" x1="8.543" x2="5.156" y1="23.929" y2="26.821" gradientUnits="userSpaceOnUse"><stop class="f1e16d8dl"/><stop offset="1" class="e16aqbsow"/></linearGradient><linearGradient id="iiZIQmb" x1="8.508" x2="8.227" y1="23.891" y2="24.148" gradientUnits="userSpaceOnUse"><stop class="t89koha0p"/><stop offset="1" class="mrh2zexqu"/></linearGradient><linearGradient id="i9VQrvc" x1="15.617" x2="22.334" y1="17.354" y2="10.349" gradientUnits="userSpaceOnUse"><stop class="ac37ogrln"/><stop offset="1" class="ht7l1pbqu"/></linearGradient><linearGradient id="iI932Bj" x1="24.788" x2="23.915" y1="7.499" y2="8.355" gradientUnits="userSpaceOnUse"><stop offset=".179" class="xn1-q8bch"/><stop offset="1" class="lpu2jgp6a"/></linearGradient><linearGradient id="iHla49L" x1="23.39" x2="26.553" y1="3.816" y2="5.553" gradientUnits="userSpaceOnUse"><stop offset=".133" class="t-7intbbv"/><stop offset="1" class="jzedgabbo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:banjo" /></template>
<style>
.ac37ogrln {
  stop-color: var(--svg-color--433e4a, #433E4A);
}

.byc8z_6ck {
  stop-color: var(--svg-color--af837a, #AF837A);
  stop-opacity: 0;
}

.c-ysp3n7t {
  stop-color: var(--svg-color--956457, #956457);
}

.e_3z3ibak {
  stop-color: var(--svg-color--b7adbe, #B7ADBE);
}

.e16aqbsow {
  stop-color: var(--svg-color--b1a3be, #B1A3BE);
}

.el0eup0eg {
  fill: var(--svg-color--cdc5d6, #CDC5D6);
  d: path("M8.69 19.803a.83.83 0 0 1 1.176 0l2.57 2.57a.832.832 0 0 1-1.177 1.176l-2.57-2.57a.83.83 0 0 1 0-1.176");
}

.elbf_abir {
  d: path("M24.923 3.186a1.6 1.6 0 0 1 2.448-.207l1.61 1.629a1.6 1.6 0 0 1-.18 2.406l-1.863 1.393a1 1 0 0 1-1.3-.088l-1.95-1.92a1 1 0 0 1-.116-1.287z");
}

.f1e16d8dl {
  stop-color: var(--svg-color--cbc1d6, #CBC1D6);
}

.ft5dv1b6b {
  fill: none;
}

.g0abp1bzn {
  stop-color: var(--svg-color--a37062, #A37062);
  stop-opacity: 0;
}

.g2vlv9bfh {
  stop-color: var(--svg-color--653747, #653747);
}

.g7e7gkbcp {
  cx: 10.31px;
  cy: 12.801px;
  r: 1.059px;
}

.hllbawbrh {
  stop-color: var(--svg-color--af837a, #AF837A);
}

.ht7l1pbqu {
  stop-color: var(--svg-color--503f60, #503F60);
}

.hzhhxobhr {
  cx: 12.168px;
  cy: 28.891px;
  r: 1.059px;
}

.i79w9-4rf {
  d: path("M6.833 23.076a.5.5 0 0 1 .756-.054l1.635 1.644a.5.5 0 0 1-.06.756l-2.84 2.086a.4.4 0 0 1-.52-.04l-1.036-1.036a.4.4 0 0 1-.039-.522z");
}

.jzedgabbo {
  stop-color: var(--svg-color--7d4e49, #7D4E49);
  stop-opacity: 0;
}

.kfn0g2bvg {
  stop-color: var(--svg-color--d4cfd7, #D4CFD7);
}

.lpu2jgp6a {
  stop-color: var(--svg-color--504060, #504060);
  stop-opacity: 0;
}

.mr_562b4g {
  cx: 24.539px;
  cy: 2.862px;
  r: 0.828px;
}

.mrh2zexqu {
  stop-color: var(--svg-color--d6cedf, #D6CEDF);
  stop-opacity: 0;
}

.mrqojibgm {
  cx: 23.273px;
  cy: 4.636px;
  r: 0.828px;
}

.mzl4sybet {
  stop-color: var(--svg-color--ccaf35, #CCAF35);
}

.n7wfd3-1q {
  cx: 5.677px;
  cy: 15.152px;
  r: 1.059px;
}

.ofjeuzd2k {
  cx: 27.474px;
  cy: 8.503px;
  r: 0.828px;
}

.oh-7k1b7h {
  fill: var(--svg-color--875753, #875753);
  d: path("M24.923 3.186a1.6 1.6 0 0 1 2.448-.207l1.61 1.629a1.6 1.6 0 0 1-.18 2.406l-1.863 1.393a1 1 0 0 1-1.3-.088l-1.95-1.92a1 1 0 0 1-.116-1.287z");
}

.ol9jz0t8n {
  stop-color: var(--svg-color--c2bac7, #C2BAC7);
}

.q-chsnb8y {
  cx: 11.305px;
  cy: 20.813px;
  rx: 8.094px;
  ry: 8.078px;
}

.q0-t4opzm {
  cx: 11.305px;
  cy: 20.813px;
  rx: 6.484px;
  ry: 6.472px;
}

.q5rcpdbvu {
  stop-color: var(--svg-color--b4a8bc, #B4A8BC);
}

.qswx5ub2m {
  cx: 29.25px;
  cy: 7.253px;
  r: 0.828px;
}

.sk8q5ibot {
  stop-color: var(--svg-color--dad1e3, #DAD1E3);
}

.t-7intbbv {
  stop-color: var(--svg-color--562c26, #562C26);
}

.t89koha0p {
  stop-color: var(--svg-color--d6cedf, #D6CEDF);
}

.u2-djxd-d {
  stop-color: var(--svg-color--dbd3e0, #DBD3E0);
}

.ue7k3b0uc {
  cx: 3.211px;
  cy: 19.934px;
  r: 1.059px;
}

.up5zi985n {
  stop-color: var(--svg-color--b08378, #B08378);
}

.v4njjjb5c {
  cx: 17.059px;
  cy: 26.453px;
  r: 1.059px;
}

.wh6gi0bvm {
  stop-color: var(--svg-color--efd453, #EFD453);
}

.wjxie-btm {
  d: path("m23.852 6.086l2.093 2.039l-9.831 11.066a.9.9 0 0 1-1.297.051l-1.84-1.769a.9.9 0 0 1 .01-1.309z");
}

.wviudcr9d {
  stop-color: var(--svg-color--e9dcf8, #E9DCF8);
}

.x402jqbak {
  stop-color: var(--svg-color--e9dcf8, #E9DCF8);
  stop-opacity: 0;
}

.xhthexh3c {
  stop-color: var(--svg-color--c9bdd3, #C9BDD3);
}

.xn1-q8bch {
  stop-color: var(--svg-color--37234a, #37234A);
}

.y__4qo8od {
  stop-color: var(--svg-color--ded4ea, #DED4EA);
}

.yucabbkpm {
  cx: 11.369px;
  cy: 20.734px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  rx: 7.474px;
  ry: 7.459px;
}

.z8_6nyb5k {
  cx: 19.332px;
  cy: 21.793px;
  r: 1.059px;
}

</style>
