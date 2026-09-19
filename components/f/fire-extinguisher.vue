<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7E6EZc)"><path fill="url(#iJgK8gb)" class="kpncccbrl"/><path fill="url(#iHFnu3b)" class="kpncccbrl"/><path fill="url(#iZV0Dld)" class="kpncccbrl"/></g><path fill="url(#ikudppb)" class="kpncccbrl"/><g filter="url(#imhddsc)"><path fill="url(#iGly3He)" class="m9k1q08ek"/></g><path stroke="url(#inEmRsc)" class="jyrldwl_x"/><path fill="url(#i3JqaWT)" class="o49zkrbzi"/><path fill="url(#iMSvJxd)" class="o49zkrbzi"/><g filter="url(#ilEevPd)"><path stroke="url(#iUrvPnV)" class="wexctjbho"/></g><path fill="url(#iwW31Ib)" class="ob-uthm4l"/><path fill="url(#ivHW0Hx)" class="ob-uthm4l"/><g clip-rule="evenodd" filter="url(#ipvAbRc)" class="d2kvgvbvc"><path class="qhnfatn7v"/><path fill="url(#isGTAHd)" class="kz7zd8bel"/></g><path class="c_a26hb8m"/><path fill="url(#iIGitIc)" class="fbgzmj6lc"/><path fill="url(#ickHmKd)" class="fbgzmj6lc"/><g filter="url(#idcgWZc)"><path class="uaik7rrhs"/><path fill="url(#ixiyVpe)" class="z5royyuob"/></g><g filter="url(#icMfaHQ)"><circle fill="url(#icMRqdb)" class="yxpjxqbyu"/></g><g filter="url(#iMHxLcc)"><circle stroke="url(#iv9uZ9b)" class="kvbtov0ff"/></g><g filter="url(#iQ8KLWb)"><path fill="url(#i0qtr8b)" class="ch4puk6hv"/></g><g filter="url(#idgLLmz)"><path fill="url(#iwdK0gc)" class="e_o82de5o"/><path fill="url(#im7wXKc)" class="e_o82de5o"/></g><g filter="url(#ilrhxHb)"><path stroke="url(#iKLpKJd)" class="ti-tedcyq"/></g><path fill="url(#ioai1zb)" class="i2_t8xepl"/><path fill="url(#i6soSPe)" class="i2_t8xepl"/><path fill="url(#idmFFec)" class="cuj1blboo"/><path fill="url(#i2JtVdx)" class="cuj1blboo"/><g filter="url(#iZAyize)"><rect fill="url(#ix0NxGc)" class="qdx_-4bam"/></g><defs><linearGradient id="iJgK8gb" x1="16.608" x2="16.608" y1="6.988" y2="29.954" gradientUnits="userSpaceOnUse"><stop class="jjg_rq_6b"/><stop offset="1" class="podzq3y4e"/></linearGradient><linearGradient id="iHFnu3b" x1="18.233" x2="18.233" y1="30.563" y2="27.75" gradientUnits="userSpaceOnUse"><stop class="emng1z5pz"/><stop offset="1" class="y4jidbp6w"/></linearGradient><linearGradient id="ikudppb" x1="19.171" x2="19.171" y1="29.954" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="eqjx09bkt"/><stop offset="1" class="uvo57y5hu"/></linearGradient><linearGradient id="iGly3He" x1="18.921" x2="15.202" y1="12.066" y2="15.563" gradientUnits="userSpaceOnUse"><stop class="pe_-szspe"/><stop offset="1" class="ffl4lpxzl"/></linearGradient><linearGradient id="inEmRsc" x1="19.639" x2="19.639" y1="8.785" y2="26.875" gradientUnits="userSpaceOnUse"><stop class="iingmp-db"/><stop offset="1" class="f0vnljbad"/></linearGradient><linearGradient id="i3JqaWT" x1="19.64" x2="19.233" y1="4.969" y2="5.906" gradientUnits="userSpaceOnUse"><stop class="rqmah7orc"/><stop offset="1" class="zi5rzb3wg"/></linearGradient><linearGradient id="iUrvPnV" x1="21.827" x2="16.671" y1="6.344" y2="4.266" gradientUnits="userSpaceOnUse"><stop class="v2gsoyblx"/><stop offset="1" class="v0aks_dwp"/></linearGradient><linearGradient id="iwW31Ib" x1="19.421" x2="19.421" y1="2.109" y2="4.063" gradientUnits="userSpaceOnUse"><stop class="nfigu9w1r"/><stop offset="1" class="xh862j9fu"/></linearGradient><linearGradient id="ivHW0Hx" x1="20.374" x2="20.374" y1="4.141" y2="3.484" gradientUnits="userSpaceOnUse"><stop class="h3v_sl0gm"/><stop offset="1" class="bgd_gpbxp"/></linearGradient><linearGradient id="iIGitIc" x1="5.796" x2="7.296" y1="28.375" y2="28.656" gradientUnits="userSpaceOnUse"><stop class="lgyocbb-f"/><stop offset="1" class="rs1kx9bht"/></linearGradient><linearGradient id="ickHmKd" x1="10.483" x2="10.483" y1="29.954" y2="29.313" gradientUnits="userSpaceOnUse"><stop offset=".019" class="qwtc2naik"/><stop offset="1" class="bg8ritipw"/></linearGradient><linearGradient id="ixiyVpe" x1="17.765" x2="16.921" y1="7.04" y2="7.04" gradientUnits="userSpaceOnUse"><stop class="ea-k5ft_f"/><stop offset="1" class="o4y7bg65l"/></linearGradient><linearGradient id="iv9uZ9b" x1="16.206" x2="15.136" y1="4.313" y2="5.449" gradientUnits="userSpaceOnUse"><stop class="nos1hqb_m"/><stop offset="1" class="ephwx-bog"/></linearGradient><linearGradient id="iwdK0gc" x1="9.421" x2="9.421" y1="21.469" y2="29.563" gradientUnits="userSpaceOnUse"><stop class="p2u-v2bwq"/><stop offset="1" class="a3p800bjf"/></linearGradient><linearGradient id="im7wXKc" x1="9.421" x2="9.421" y1="21.469" y2="23.627" gradientUnits="userSpaceOnUse"><stop offset=".078" class="hbja3ssgq"/><stop offset="1" class="j01iprjhx"/></linearGradient><linearGradient id="iKLpKJd" x1="8.879" x2="14.191" y1="18.063" y2="2.1" gradientUnits="userSpaceOnUse"><stop offset=".613" class="wr5fjt6oz"/><stop offset="1" class="lbgyg1bgb"/></linearGradient><linearGradient id="ioai1zb" x1="7.921" x2="9.686" y1="20.102" y2="20.102" gradientUnits="userSpaceOnUse"><stop class="gacl-z-dg"/><stop offset=".697" class="b51b1xkdy"/></linearGradient><linearGradient id="i6soSPe" x1="10.03" x2="9.421" y1="21.047" y2="21.047" gradientUnits="userSpaceOnUse"><stop class="m5578pspf"/><stop offset="1" class="c83p7bcdu"/></linearGradient><linearGradient id="idmFFec" x1="18.327" x2="18.046" y1="20.656" y2="23.063" gradientUnits="userSpaceOnUse"><stop class="bmr_tmqjg"/><stop offset="1" class="ax9xi6bai"/></linearGradient><linearGradient id="i2JtVdx" x1="7.327" x2="9.108" y1="21.719" y2="21.719" gradientUnits="userSpaceOnUse"><stop class="xb4z-dnuf"/><stop offset="1" class="wdq_vnjsh"/></linearGradient><linearGradient id="ix0NxGc" x1="23.343" x2="16.811" y1="2.9" y2="2.9" gradientUnits="userSpaceOnUse"><stop class="c__yvsbrn"/><stop offset="1" class="s3ppnnw5i"/></linearGradient><filter id="i7E6EZc" width="15.014" height="22.967" x="9.601" y="6.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.105882 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26380"/></filter><filter id="imhddsc" width="6.009" height="4.084" x="13.529" y="12.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.901961 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26380"/></filter><filter id="ilEevPd" width="5.469" height="2.828" x="17.03" y="3.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26380" stdDeviation=".125"/></filter><filter id="ipvAbRc" width="9.314" height="19.291" x="7.686" y="2.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.2 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26380"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.337255 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26380" result="effect2_innerShadow_18_26380"/></filter><filter id="idcgWZc" width="3.289" height="5.031" x="14.804" y="2.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.662745 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26380"/></filter><filter id="icMfaHQ" width="4.178" height="4.178" x="12.608" y="3.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.505882 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26380"/></filter><filter id="iMHxLcc" width="4.217" height="4.217" x="12.539" y="3.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26380" stdDeviation=".15"/></filter><filter id="iQ8KLWb" width="2.128" height="2.128" x="13.608" y="4.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.47451 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26380"/></filter><filter id="idgLLmz" width="3.834" height="9.694" x="7.808" y="20.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26380" stdDeviation=".4"/></filter><filter id="ilrhxHb" width="4.831" height="16.208" x="8.343" y="3.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26380" stdDeviation=".225"/></filter><filter id="iZAyize" width="6.75" height="1.612" x="17.093" y="2.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26380" stdDeviation=".25"/></filter><radialGradient id="iZV0Dld" cx="0" cy="0" r="1" gradientTransform="matrix(-7.75 0 0 -5.5 22.483 11.063)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="d5vnls7lu"/><stop offset="1" class="h43jh6_dl"/></radialGradient><radialGradient id="iMSvJxd" cx="0" cy="0" r="1" gradientTransform="matrix(2.21875 1.0625 -.36587 .76403 17.67 3.906)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="xpzymxb_s"/><stop offset="1" class="gmj6z5bkg"/></radialGradient><radialGradient id="isGTAHd" cx="0" cy="0" r="1" gradientTransform="rotate(131.222 5.296 5.538)scale(1.68265 1.15082)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="scinacc_a"/><stop offset="1" class="f26yntb9l"/></radialGradient><radialGradient id="icMRqdb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75002 3.25 -3.81277 -2.05305 15.827 4.031)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="e2sumdpne"/><stop offset="1" class="w99sd3l1g"/></radialGradient><radialGradient id="i0qtr8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09374 1.8008 -1.56342 -.94956 15.436 4.688)" gradientUnits="userSpaceOnUse"><stop offset=".549" class="ovw06trhu"/><stop offset="1" class="h2sbzjb4j"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fire-extinguisher" /></template>
<style>
.a3p800bjf {
  stop-color: var(--svg-color--5b575f, #5B575F);
}

.ax9xi6bai {
  stop-color: var(--svg-color--4e3765, #4E3765);
}

.b51b1xkdy {
  stop-color: var(--svg-color--e4d1ee, #E4D1EE);
}

.bg8ritipw {
  stop-color: var(--svg-color--4b2c63, #4B2C63);
  stop-opacity: 0;
}

.bgd_gpbxp {
  stop-color: var(--svg-color--bea3c4, #BEA3C4);
  stop-opacity: 0;
}

.bmr_tmqjg {
  stop-color: var(--svg-color--6f5b85, #6F5B85);
}

.c__yvsbrn {
  stop-color: var(--svg-color--ddd6e3, #DDD6E3);
}

.c_a26hb8m {
  fill: var(--svg-color--373034, #373034);
  d: path("m5.944 29.338l1.77-7.385h1.953l1.77 7.385a.5.5 0 0 1-.486.616H6.43a.5.5 0 0 1-.486-.616");
}

.c83p7bcdu {
  stop-color: var(--svg-color--ceb2cb, #CEB2CB);
  stop-opacity: 0;
}

.ch4puk6hv {
  d: path("M14.64 4.41v1.043l.73-.75a1.04 1.04 0 1 1-.73-.292");
}

.cuj1blboo {
  d: path("M7.686 21.044h15.949v1.021H7.686z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d5vnls7lu {
  stop-color: var(--svg-color--ff649b, #FF649B);
}

.e_o82de5o {
  d: path("m8.796 29.563l-.188-8.094h.688l1.547 8.093z");
}

.e2sumdpne {
  stop-color: var(--svg-color--d4c9de, #D4C9DE);
}

.ea-k5ft_f {
  stop-color: var(--svg-color--e0dbe4, #E0DBE4);
}

.emng1z5pz {
  stop-color: var(--svg-color--e22360, #E22360);
}

.ephwx-bog {
  stop-color: var(--svg-color--eae2f1, #EAE2F1);
  stop-opacity: 0;
}

.eqjx09bkt {
  stop-color: var(--svg-color--eb2260, #EB2260);
}

.f0vnljbad {
  stop-color: var(--svg-color--ffe9ff, #FFE9FF);
  stop-opacity: 0;
}

.f26yntb9l {
  stop-color: var(--svg-color--3c1e48, #3C1E48);
  stop-opacity: 0;
}

.fbgzmj6lc {
  d: path("m5.944 29.338l1.77-7.385h1.953l1.77 7.385a.5.5 0 0 1-.486.616H6.43a.5.5 0 0 1-.486-.616");
}

.ffl4lpxzl {
  stop-color: var(--svg-color--d7c3ea, #D7C3EA);
}

.ft5dv1b6b {
  fill: none;
}

.gacl-z-dg {
  stop-color: var(--svg-color--c5b1cc, #C5B1CC);
}

.gmj6z5bkg {
  stop-color: var(--svg-color--9d8d9c, #9D8D9C);
  stop-opacity: 0;
}

.h2sbzjb4j {
  stop-color: var(--svg-color--93859f, #93859F);
}

.h3v_sl0gm {
  stop-color: var(--svg-color--a28ea1, #A28EA1);
}

.h43jh6_dl {
  stop-color: var(--svg-color--ff649b, #FF649B);
  stop-opacity: 0;
}

.hbja3ssgq {
  stop-color: var(--svg-color--59545d, #59545D);
}

.i2_t8xepl {
  d: path("M9.686 18.734v2.735h-2v-2.735z");
}

.iingmp-db {
  stop-color: var(--svg-color--ffe9ff, #FFE9FF);
}

.j01iprjhx {
  stop-color: var(--svg-color--59545d, #59545D);
  stop-opacity: 0;
}

.jjg_rq_6b {
  stop-color: var(--svg-color--f6367c, #F6367C);
}

.jyrldwl_x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-15px, 1.15px);
  d: path("M17.188 8.785c1.634-.035 4.901 1.084 4.901 5.358v10.899");
}

.kpncccbrl {
  d: path("M9.601 12.988a6 6 0 0 1 6-6h2.014a6 6 0 0 1 6 6v15.166a1.8 1.8 0 0 1-1.8 1.8H11.401a1.8 1.8 0 0 1-1.8-1.8z");
}

.kvbtov0ff {
  cx: 14.647px;
  cy: 5.449px;
  r: 1.559px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.kz7zd8bel {
  d: path("M10.748 4.307c1.693-1.425 3.699-1.981 5.031-2.129L16 4.166c-1.059.117-2.654.569-3.965 1.671c-1.271 1.07-2.349 2.812-2.349 5.694v9.938h-2V11.53c0-3.461 1.33-5.767 3.062-7.224");
}

.lbgyg1bgb {
  stop-color: var(--svg-color--5d4675, #5D4675);
  stop-opacity: 0;
}

.lgyocbb-f {
  stop-color: var(--svg-color--5c544f, #5C544F);
}

.m5578pspf {
  stop-color: var(--svg-color--ceb2cb, #CEB2CB);
}

.m9k1q08ek {
  d: path("M13.679 12.966a.9.9 0 0 1 .9-.9h4.059a.9.9 0 0 1 .9.9V15.1a.9.9 0 0 1-.9.9h-4.059a.9.9 0 0 1-.9-.9z");
}

.nfigu9w1r {
  stop-color: var(--svg-color--c2bcc5, #C2BCC5);
}

.nos1hqb_m {
  stop-color: var(--svg-color--eae2f1, #EAE2F1);
}

.o49zkrbzi {
  d: path("M15.515 3.617a.53.53 0 0 1 .7-.273l6.036 2.651a.53.53 0 1 1-.427.972l-6.037-2.65a.53.53 0 0 1-.272-.7");
}

.o4y7bg65l {
  stop-color: var(--svg-color--e0dbe4, #E0DBE4);
  stop-opacity: 0;
}

.ob-uthm4l {
  d: path("M15.272 3.086c0-.54.438-.977.977-.977h6.344a.977.977 0 0 1 0 1.954h-6.344a.977.977 0 0 1-.977-.977");
}

.ovw06trhu {
  stop-color: var(--svg-color--9a8ea7, #9A8EA7);
}

.p2u-v2bwq {
  stop-color: var(--svg-color--57535c, #57535C);
}

.pe_-szspe {
  stop-color: var(--svg-color--f1e4fc, #F1E4FC);
}

.podzq3y4e {
  stop-color: var(--svg-color--ff3d5d, #FF3D5D);
}

.qdx_-4bam {
  width: 5.75px;
  height: 0.612px;
  x: 17.593px;
  y: 2.594px;
  rx: 0.306px;
}

.qhnfatn7v {
  fill: var(--svg-color--542e65, #542E65);
  d: path("M10.748 4.307c1.693-1.425 3.699-1.981 5.031-2.129L16 4.166c-1.059.117-2.654.569-3.965 1.671c-1.271 1.07-2.349 2.812-2.349 5.694v9.938h-2V11.53c0-3.461 1.33-5.767 3.062-7.224");
}

.qwtc2naik {
  stop-color: var(--svg-color--4b2c63, #4B2C63);
}

.rqmah7orc {
  stop-color: var(--svg-color--c1b5c2, #C1B5C2);
}

.rs1kx9bht {
  stop-color: var(--svg-color--5c544f, #5C544F);
  stop-opacity: 0;
}

.s3ppnnw5i {
  stop-color: var(--svg-color--ddd6e3, #DDD6E3);
  stop-opacity: 0;
}

.scinacc_a {
  stop-color: var(--svg-color--3c1e48, #3C1E48);
}

.ti-tedcyq {
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M12.608 4.344c-1.172.49-3.515 2.406-3.515 6.156v8.875");
}

.uaik7rrhs {
  fill: var(--svg-color--c8becd, #C8BECD);
  d: path("M15.554 2.11a.75.75 0 0 0-.75.75v4.18q.391-.051.797-.052h1.992V3.109a1 1 0 0 0-1-1z");
}

.uvo57y5hu {
  stop-color: var(--svg-color--ff4c66, #FF4C66);
  stop-opacity: 0;
}

.v0aks_dwp {
  stop-color: var(--svg-color--d7cad9, #D7CAD9);
  stop-opacity: 0;
}

.v2gsoyblx {
  stop-color: var(--svg-color--d7cad9, #D7CAD9);
}

.w99sd3l1g {
  stop-color: var(--svg-color--b89bc9, #B89BC9);
}

.wdq_vnjsh {
  stop-color: var(--svg-color--5e4f5c, #5E4F5C);
  stop-opacity: 0;
}

.wexctjbho {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m17.405 4.266l4.719 2.078");
}

.wr5fjt6oz {
  stop-color: var(--svg-color--645871, #645871);
}

.xb4z-dnuf {
  stop-color: var(--svg-color--5e4f5c, #5E4F5C);
}

.xh862j9fu {
  stop-color: var(--svg-color--bb9cc2, #BB9CC2);
}

.xpzymxb_s {
  stop-color: var(--svg-color--9d8d9c, #9D8D9C);
}

.y4jidbp6w {
  stop-color: var(--svg-color--e22360, #E22360);
  stop-opacity: 0;
}

.yxpjxqbyu {
  cx: 14.647px;
  cy: 5.449px;
  r: 2.039px;
}

.z5royyuob {
  d: path("M15.554 2.11a.75.75 0 0 0-.75.75v4.18q.391-.051.797-.052h1.992V3.109a1 1 0 0 0-1-1z");
}

.zi5rzb3wg {
  stop-color: var(--svg-color--b090a9, #B090A9);
}

</style>
