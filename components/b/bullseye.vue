<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZ6oKdb)"><circle fill="url(#iKpWZEe)" class="gi1a_-lym"/><circle fill="url(#itutVEA)" class="gi1a_-lym"/></g><circle fill="url(#iBljB7b)" class="gt4gznl5k"/><circle fill="url(#iT6AeQd)" class="gt4gznl5k"/><circle fill="url(#iMnYjGb)" class="gt4gznl5k"/><circle fill="url(#imwolHR)" class="slid2obwi"/><circle fill="url(#ip51rmc)" class="slid2obwi"/><circle class="v9uymzbjf"/><circle fill="url(#i7O7y6g)" class="naoshoiib"/><circle fill="url(#iIaR18c)" class="naoshoiib"/><g filter="url(#inxS6po)"><path stroke="url(#iVzquie)" class="asubuva2n"/></g><path class="kam7xkbvd"/><path fill="url(#iLH4HNc)" class="itrnkhb_c"/><path fill="url(#isJ7TVc)" class="itrnkhb_c"/><path class="qkwft0brk"/><path fill="url(#iYzIAKd)" class="basdxyyxl"/><path fill="url(#iVFG26c)" class="basdxyyxl"/><path class="dawa74bme"/><path fill="url(#i4QPORB)" class="ig5g4nbnm"/><path fill="url(#iIa7KLc)" class="ig5g4nbnm"/><g filter="url(#iLKrwLb)"><rect fill="url(#i6x5yVb)" transform="rotate(-20.523 21.323 2.624)" class="p0t_23bre"/></g><g filter="url(#iFGrixd)"><rect fill="url(#i6UFLDb)" transform="rotate(110.612 29.642 9.72)" class="dy7t9czup"/></g><g filter="url(#iKqC1oc)"><path class="bmq58_b1f"/></g><path fill="url(#iNhRe7b)" class="id9_mxbjq"/><path fill="url(#iTBASse)" class="id9_mxbjq"/><path fill="url(#ivXZkoc)" class="id9_mxbjq"/><g filter="url(#iNnSOJk)"><rect transform="rotate(45 26.024 4.742)" class="a-59tvb1p"/></g><rect fill="url(#iV4We9d)" transform="rotate(45 26.024 4.742)" class="be2zijbkt"/><defs><radialGradient id="itutVEA" cx="0" cy="0" r="1" gradientTransform="matrix(-3.04648 4.37923 -6.36862 -4.43043 19.972 10.33)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="em648ji_o"/><stop offset="1" class="lr3--bb6k"/></radialGradient><radialGradient id="iT6AeQd" cx="0" cy="0" r="1" gradientTransform="translate(11.214 17.96)scale(11.63)" gradientUnits="userSpaceOnUse"><stop offset=".861" class="n9cydob1o"/><stop offset="1" class="jrgo1vboe"/></radialGradient><radialGradient id="iMnYjGb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.79254 5.20435 -2.84857 -1.52848 18.195 9.759)" gradientUnits="userSpaceOnUse"><stop class="dx9xvsbvx"/><stop offset="1" class="pge-jripl"/></radialGradient><radialGradient id="ip51rmc" cx="0" cy="0" r="1" gradientTransform="rotate(131.253 5.263 10.981)scale(4.47426)" gradientUnits="userSpaceOnUse"><stop class="z2nha7qtr"/><stop offset=".947" class="wqy00kbqm"/></radialGradient><radialGradient id="i7O7y6g" cx="0" cy="0" r="1" gradientTransform="rotate(67.204 -6.039 18.655)scale(4.75032)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="s_1mvibms"/><stop offset="1" class="cgxsrsbqd"/></radialGradient><radialGradient id="iIaR18c" cx="0" cy="0" r="1" gradientTransform="rotate(103.843 1.754 13.56)scale(3.71373)" gradientUnits="userSpaceOnUse"><stop class="y199zgb4v"/><stop offset="1" class="t05dh3k9x"/></radialGradient><radialGradient id="iYzIAKd" cx="0" cy="0" r="1" gradientTransform="rotate(-157.278 11.408 .91)scale(2.71034 4.92096)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="pf9m8xbxo"/><stop offset="1" class="hrhgqmbdv"/></radialGradient><radialGradient id="iIa7KLc" cx="0" cy="0" r="1" gradientTransform="matrix(.75 4.07813 -5.25336 .96613 25.626 9.234)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="uxw098arq"/><stop offset=".926" class="x4-gcab1a"/></radialGradient><radialGradient id="i6x5yVb" cx="0" cy="0" r="1" gradientTransform="matrix(.268 4.98873 -1.0533 .05658 21.826 2.948)" gradientUnits="userSpaceOnUse"><stop class="hk8tf6gyc"/><stop offset="1" class="isc1zgb4l"/></radialGradient><radialGradient id="i6UFLDb" cx="0" cy="0" r="1" gradientTransform="rotate(86.925 9.774 20.926)scale(4.99592 1.05482)" gradientUnits="userSpaceOnUse"><stop class="hk8tf6gyc"/><stop offset="1" class="isc1zgb4l"/></radialGradient><radialGradient id="iNhRe7b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.93751 2.18748 -2.25408 -3.02695 27.157 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="zasaeub2s"/><stop offset="1" class="b_90w6att"/></radialGradient><radialGradient id="iTBASse" cx="0" cy="0" r="1" gradientTransform="matrix(-8.02067 7.30234 -7.39753 -8.12522 24.007 8.546)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="k94a3fbrk"/><stop offset="1" class="afwru2bhm"/></radialGradient><radialGradient id="ivXZkoc" cx="0" cy="0" r="1" gradientTransform="rotate(134.318 8.106 9.959)scale(1.97052 1.03686)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="rz-rafmzj"/><stop offset="1" class="lp2hr985w"/></radialGradient><radialGradient id="iV4We9d" cx="0" cy="0" r="1" gradientTransform="matrix(.0221 -2.93892 1.11949 .00842 26.831 5.626)" gradientUnits="userSpaceOnUse"><stop class="p81kwlbxu"/><stop offset="1" class="ob7bs3bsh"/></radialGradient><linearGradient id="iKpWZEe" x1="19.534" x2="9.433" y1="7.121" y2="27.666" gradientUnits="userSpaceOnUse"><stop class="z11g_ebou"/><stop offset="1" class="urygrvbqt"/></linearGradient><linearGradient id="iBljB7b" x1="20.353" x2="7.279" y1="22.389" y2="8.806" gradientUnits="userSpaceOnUse"><stop class="ao57vibop"/><stop offset="1" class="pnr0qq85k"/></linearGradient><linearGradient id="imwolHR" x1="17.878" x2="11.087" y1="14.074" y2="23.214" gradientUnits="userSpaceOnUse"><stop class="wggdumbnf"/><stop offset="1" class="dotqg7uaw"/></linearGradient><linearGradient id="iVzquie" x1="23.42" x2="16.829" y1="10.783" y2="17.524" gradientUnits="userSpaceOnUse"><stop class="q2o5m7ady"/><stop offset="1" class="nntr-kbtb"/></linearGradient><linearGradient id="iLH4HNc" x1="16.148" x2="15.507" y1="17.281" y2="16.622" gradientUnits="userSpaceOnUse"><stop class="gxossuuwb"/><stop offset="1" class="xhua-ub8s"/></linearGradient><linearGradient id="isJ7TVc" x1="14.901" x2="15.139" y1="15.823" y2="16.047" gradientUnits="userSpaceOnUse"><stop class="kie2atbzu"/><stop offset="1" class="fj7rh9bxn"/></linearGradient><linearGradient id="iVFG26c" x1="23.47" x2="21.876" y1="4.313" y2="4.875" gradientUnits="userSpaceOnUse"><stop class="piki7f1-n"/><stop offset="1" class="cyhu6zhjm"/></linearGradient><linearGradient id="i4QPORB" x1="28.126" x2="27.532" y1="8.531" y2="9.812" gradientUnits="userSpaceOnUse"><stop class="mf94qu4xf"/><stop offset="1" class="a1rh2ry5z"/></linearGradient><filter id="iZ6oKdb" width="24.578" height="25.078" x="2" y="5.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.160784 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3225"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.341176 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3225" result="effect2_innerShadow_18_3225"/></filter><filter id="inxS6po" width="23.887" height="23.887" x="2.338" y="6.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3225" stdDeviation=".325"/></filter><filter id="iLKrwLb" width="3.458" height="5.984" x="20.958" y="1.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3225" stdDeviation=".25"/></filter><filter id="iFGrixd" width="5.982" height="3.464" x="24.024" y="7.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3225" stdDeviation=".25"/></filter><filter id="iKqC1oc" width="11.715" height="11.71" x="15.313" y="5.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.65098 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3225"/></filter><filter id="iNnSOJk" width="7.208" height="7.208" x="19.85" y="4.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.521569 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3225"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.435294 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3225" result="effect2_innerShadow_18_3225"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bullseye" /></template>
<style>
.a-59tvb1p {
  width: 1.768px;
  height: 9.038px;
  x: 26.024px;
  y: 4.742px;
  fill: var(--svg-color--2984e4, #2984E4);
  rx: 0.884px;
}

.a1rh2ry5z {
  stop-color: var(--svg-color--49b6ff, #49B6FF);
  stop-opacity: 0;
}

.afwru2bhm {
  stop-color: var(--svg-color--5e9bdb, #5E9BDB);
}

.ao57vibop {
  stop-color: var(--svg-color--cec3df, #CEC3DF);
}

.asubuva2n {
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M14.282 28.93c6.057 0 10.968-4.911 10.968-10.97c0-6.057-4.91-10.968-10.968-10.968S3.313 11.903 3.313 17.961s4.911 10.968 10.969 10.968Z");
}

.b_90w6att {
  stop-color: var(--svg-color--6bffff, #6BFFFF);
  stop-opacity: 0;
}

.basdxyyxl {
  d: path("m22.664 2.772l1.227 3.244l-4.484 3.14c-1.335-3.531.298-5.617 1.814-6.826c.497-.396 1.218-.153 1.443.442");
}

.be2zijbkt {
  width: 1.768px;
  height: 9.038px;
  x: 26.024px;
  y: 4.742px;
  rx: 0.884px;
}

.bmq58_b1f {
  fill: var(--svg-color--52bcf0, #52BCF0);
  d: path("m16.68 10.71l6.626-4.91c.88-.657 2.194-.486 2.857.197c.737.791.824 1.956.192 2.816l-4.89 6.645a3.407 3.407 0 1 1-4.785-4.748");
}

.cgxsrsbqd {
  stop-color: var(--svg-color--c9bed9, #C9BED9);
}

.cyhu6zhjm {
  stop-color: var(--svg-color--58c3ff, #58C3FF);
  stop-opacity: 0;
}

.dawa74bme {
  fill: var(--svg-color--2980eb, #2980EB);
  d: path("m29.197 9.311l-3.259-1.187l-3.085 4.523c3.548 1.292 5.613-.367 6.803-1.897c.39-.502.138-1.221-.46-1.439");
}

.dotqg7uaw {
  stop-color: var(--svg-color--ed3963, #ED3963);
}

.dx9xvsbvx {
  stop-color: var(--svg-color--9da8b4, #9DA8B4);
}

.dy7t9czup {
  width: 0.946px;
  height: 5.258px;
  x: 29.642px;
  y: 9.72px;
  rx: 0.473px;
}

.em648ji_o {
  stop-color: var(--svg-color--b82974, #B82974);
}

.fj7rh9bxn {
  stop-color: var(--svg-color--746d7c, #746D7C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gi1a_-lym {
  cx: 14.039px;
  cy: 17.961px;
  r: 12.039px;
}

.gt4gznl5k {
  cx: 14.039px;
  cy: 17.961px;
  r: 8.805px;
}

.gxossuuwb {
  stop-color: var(--svg-color--7e5f8a, #7E5F8A);
}

.hk8tf6gyc {
  stop-color: var(--svg-color--61ceff, #61CEFF);
}

.hrhgqmbdv {
  stop-color: var(--svg-color--6897c2, #6897C2);
}

.id9_mxbjq {
  d: path("m16.68 10.71l6.626-4.91c.88-.657 2.194-.486 2.857.197c.737.791.824 1.956.192 2.816l-4.89 6.645a3.407 3.407 0 1 1-4.785-4.748");
}

.ig5g4nbnm {
  d: path("m29.197 9.311l-3.259-1.187l-3.085 4.523c3.548 1.292 5.613-.367 6.803-1.897c.39-.502.138-1.221-.46-1.439");
}

.isc1zgb4l {
  stop-color: var(--svg-color--3cb8ff, #3CB8FF);
  stop-opacity: 0;
}

.itrnkhb_c {
  d: path("M14.134 17.875c-.338-.339-.463-.723-.125-1.062l1.715-1.723a.867.867 0 1 1 1.226 1.226l-1.715 1.723c-.338.339-.762.174-1.1-.164");
}

.jrgo1vboe {
  stop-color: var(--svg-color--cbc4df, #CBC4DF);
}

.k94a3fbrk {
  stop-color: var(--svg-color--5e9bdb, #5E9BDB);
  stop-opacity: 0;
}

.kam7xkbvd {
  fill: var(--svg-color--7c7088, #7C7088);
  d: path("M14.134 17.875c-.338-.339-.463-.723-.125-1.062l1.715-1.723a.867.867 0 1 1 1.226 1.226l-1.715 1.723c-.338.339-.762.174-1.1-.164");
}

.kie2atbzu {
  stop-color: var(--svg-color--746d7c, #746D7C);
}

.lp2hr985w {
  stop-color: var(--svg-color--49a0e1, #49A0E1);
  stop-opacity: 0;
}

.lr3--bb6k {
  stop-color: var(--svg-color--b82974, #B82974);
  stop-opacity: 0;
}

.mf94qu4xf {
  stop-color: var(--svg-color--49b6ff, #49B6FF);
}

.n9cydob1o {
  stop-color: var(--svg-color--cbc4df, #CBC4DF);
  stop-opacity: 0;
}

.naoshoiib {
  cx: 14.039px;
  cy: 17.961px;
  r: 2.859px;
}

.nntr-kbtb {
  stop-color: var(--svg-color--ff6aa2, #FF6AA2);
  stop-opacity: 0;
}

.ob7bs3bsh {
  stop-color: var(--svg-color--60caff, #60CAFF);
  stop-opacity: 0;
}

.p0t_23bre {
  width: 0.946px;
  height: 5.258px;
  x: 21.323px;
  y: 2.624px;
  rx: 0.473px;
}

.p81kwlbxu {
  stop-color: var(--svg-color--60caff, #60CAFF);
}

.pf9m8xbxo {
  stop-color: var(--svg-color--6897c2, #6897C2);
  stop-opacity: 0;
}

.pge-jripl {
  stop-color: var(--svg-color--9da8b4, #9DA8B4);
  stop-opacity: 0;
}

.piki7f1-n {
  stop-color: var(--svg-color--58c3ff, #58C3FF);
}

.pnr0qq85k {
  stop-color: var(--svg-color--c5bcd3, #C5BCD3);
}

.q2o5m7ady {
  stop-color: var(--svg-color--ff6aa2, #FF6AA2);
}

.qkwft0brk {
  fill: var(--svg-color--2983df, #2983DF);
  d: path("m22.664 2.772l1.227 3.244l-4.484 3.14c-1.335-3.531.298-5.617 1.814-6.826c.497-.396 1.218-.153 1.443.442");
}

.rz-rafmzj {
  stop-color: var(--svg-color--49a0e1, #49A0E1);
}

.s_1mvibms {
  stop-color: var(--svg-color--c9bed9, #C9BED9);
  stop-opacity: 0;
}

.slid2obwi {
  cx: 14.039px;
  cy: 17.961px;
  r: 5.758px;
}

.t05dh3k9x {
  stop-color: var(--svg-color--857d97, #857D97);
  stop-opacity: 0;
}

.urygrvbqt {
  stop-color: var(--svg-color--ef3a5c, #EF3A5C);
}

.uxw098arq {
  stop-color: var(--svg-color--5066d2, #5066D2);
  stop-opacity: 0;
}

.v9uymzbjf {
  cx: 14.039px;
  cy: 17.961px;
  r: 2.859px;
  fill: var(--svg-color--b7abc8, #B7ABC8);
}

.wggdumbnf {
  stop-color: var(--svg-color--d2347a, #D2347A);
}

.wqy00kbqm {
  stop-color: var(--svg-color--962359, #962359);
  stop-opacity: 0;
}

.x4-gcab1a {
  stop-color: var(--svg-color--5066d2, #5066D2);
}

.xhua-ub8s {
  stop-color: var(--svg-color--7e5f8a, #7E5F8A);
  stop-opacity: 0;
}

.y199zgb4v {
  stop-color: var(--svg-color--857d97, #857D97);
}

.z11g_ebou {
  stop-color: var(--svg-color--e6378b, #E6378B);
}

.z2nha7qtr {
  stop-color: var(--svg-color--962359, #962359);
}

.zasaeub2s {
  stop-color: var(--svg-color--6bffff, #6BFFFF);
}

</style>
