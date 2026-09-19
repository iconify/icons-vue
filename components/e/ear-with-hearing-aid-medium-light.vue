<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="u2ven5bnf"/><path class="kizuddckh"/><g filter="url(#iQWiUgb)"><ellipse fill="url(#idMx2Be)" transform="rotate(26.087 16.736 9.304)" class="p07jz0bkj"/></g><g filter="url(#i5noD8c)"><path fill="url(#ict69ab)" class="reyko3bjq"/><path fill="url(#ipcgcXb)" class="reyko3bjq"/></g><g filter="url(#iIaq2le)"><circle fill="url(#iMrtGJe)" class="o_zs0qeiu"/></g><circle fill="url(#itVbcCd)" class="zl2taod9f"/><circle fill="url(#iVeASMe)" class="zl2taod9f"/><g filter="url(#ivfijtd)"><circle class="mfdcdjbxa"/></g><g filter="url(#iu4uAve)"><path fill="url(#iqKSO8c)" class="p537izvvk"/><path fill="url(#i0kKZ8c)" class="p537izvvk"/></g><path fill="url(#iHBfjzc)" class="p537izvvk"/><path fill="url(#iReQMpb)" class="p537izvvk"/><path fill="url(#iCWctGe)" class="p537izvvk"/><path fill="url(#iXLh8Ob)" class="p537izvvk"/><path fill="url(#iUoSLvG)" class="p537izvvk"/><g filter="url(#ipjXmmd)"><path stroke="url(#i3DHw1b)" class="jl0d1ud2w"/></g><g filter="url(#iP8Tahe)"><path stroke="url(#iIqIVab)" class="sxjiylbiz"/></g><rect fill="url(#i4dg7ff)" class="hf5wm2mfe"/><rect fill="url(#i8JT7hd)" class="nnp22abze"/><rect fill="url(#irj2PYb)" class="nnp22abze"/><g filter="url(#ibrhJTd)"><path class="infs38bwt"/><path fill="url(#iJXZ0Rb)" class="fgqhdzbrg"/></g><path class="i2g6mlz6l"/><path fill="url(#iShd0vb)" class="bjp4tgbbt"/><path fill="url(#iEuiVVd)" class="bjp4tgbbt"/><path fill="url(#ioVccre)" class="bjp4tgbbt"/><path fill="url(#iZULrWJ)" class="kq103abhv"/><g filter="url(#iXvMKFe)"><path stroke="url(#irisOtb)" class="ucgxbccuf"/></g><g filter="url(#im0v2Wc)"><path stroke="url(#idPYdzb)" class="jqsrlfe5i"/></g><g filter="url(#i2yZ7Jb)"><path stroke="url(#iptkFKb)" class="qb8dbxb5j"/></g><g filter="url(#iC580Sb)"><path fill="url(#iLuGTld)" class="u1wxr7b2p"/></g><defs><linearGradient id="ict69ab" x1="12.432" x2="9.776" y1="12.678" y2="18.072" gradientUnits="userSpaceOnUse"><stop class="bne7dsbcl"/><stop offset="1" class="lwg_i8b5w"/></linearGradient><linearGradient id="ipcgcXb" x1="13.095" x2="15.023" y1="27.082" y2="21.688" gradientUnits="userSpaceOnUse"><stop offset=".218" class="jl8dr8f0s"/><stop offset="1" class="ckm_w_bgk"/></linearGradient><linearGradient id="iMrtGJe" x1="14.007" x2="11.792" y1="20.306" y2="24.205" gradientUnits="userSpaceOnUse"><stop offset=".34" class="dkjt8_o6m"/><stop offset="1" class="ojom8obgb"/></linearGradient><linearGradient id="itVbcCd" x1="11.351" x2="11.351" y1="19.006" y2="24.792" gradientUnits="userSpaceOnUse"><stop class="trqvfobih"/><stop offset="1" class="khw5u_pgi"/></linearGradient><linearGradient id="iqKSO8c" x1="11.166" x2="19.302" y1="30.939" y2="-.28" gradientUnits="userSpaceOnUse"><stop class="m8zz4squb"/><stop offset="1" class="nnkw3ubao"/></linearGradient><linearGradient id="i3DHw1b" x1="24.096" x2="16.954" y1="11.382" y2="3.848" gradientUnits="userSpaceOnUse"><stop class="u2e_6xu1e"/><stop offset=".51" class="i9tykjb7d"/><stop offset="1" class="u2e_6xu1e"/></linearGradient><linearGradient id="iIqIVab" x1="8.156" x2="20.632" y1="2.492" y2="23.808" gradientUnits="userSpaceOnUse"><stop class="u2e_6xu1e"/><stop offset=".698" class="i9tykjb7d"/></linearGradient><linearGradient id="i4dg7ff" x1="27.056" x2="27.056" y1="10.474" y2="15.429" gradientUnits="userSpaceOnUse"><stop class="kdl2hbbyb"/><stop offset="1" class="p4a1uebzz"/></linearGradient><linearGradient id="i8JT7hd" x1="27.593" x2="27.593" y1="15.688" y2="14.575" gradientUnits="userSpaceOnUse"><stop class="d7eywim1k"/><stop offset="1" class="sqji9tbob"/></linearGradient><linearGradient id="irj2PYb" x1="27.056" x2="27.056" y1="10.397" y2="10.866" gradientUnits="userSpaceOnUse"><stop class="eu-87q5qq"/><stop offset="1" class="e14ccpbpi"/></linearGradient><linearGradient id="ioVccre" x1="22.861" x2="22.861" y1="19.858" y2="17.213" gradientUnits="userSpaceOnUse"><stop class="nf1xib-zk"/><stop offset="1" class="stmsp0bcc"/></linearGradient><linearGradient id="irisOtb" x1="14.833" x2="6.677" y1="1.892" y2="8.939" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="idPYdzb" x1="6.239" x2="10.187" y1="13.249" y2="17.881" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="iptkFKb" x1="16.42" x2="30.608" y1="2.189" y2="7.394" gradientUnits="userSpaceOnUse"><stop class="h5tsjybzx"/><stop offset=".123" class="sd9-1cnwp"/><stop offset=".542" class="iab0nwb4s"/><stop offset=".763" class="borhhobgo"/></linearGradient><linearGradient id="iLuGTld" x1="27.716" x2="27.716" y1="9.624" y2="14.702" gradientUnits="userSpaceOnUse"><stop offset=".152" class="g4udvybro"/><stop offset=".5" class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><radialGradient id="idMx2Be" cx="0" cy="0" r="1" gradientTransform="rotate(-91.906 15.037 -1.2)scale(8.56896 14.9444)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="trcx2qb5r"/><stop offset=".922" class="v05g5nbno"/></radialGradient><radialGradient id="iVeASMe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03287 1.46637 -1.6746 -2.32155 13.964 20.719)" gradientUnits="userSpaceOnUse"><stop class="pk2_uvofd"/><stop offset="1" class="pkzs1bb5w"/></radialGradient><radialGradient id="i0kKZ8c" cx="0" cy="0" r="1" gradientTransform="rotate(-55.138 18.97 -10.682)scale(6.53708 7.31924)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="emwabp4fw"/><stop offset="1" class="grzcxhmih"/></radialGradient><radialGradient id="iHBfjzc" cx="0" cy="0" r="1" gradientTransform="matrix(.13826 -4.4596 5.91528 .1834 22.418 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="d3ikkpb5y"/><stop offset="1" class="sr9kiobma"/></radialGradient><radialGradient id="iReQMpb" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.567 16.848)scale(4.79258 4.67361)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="w4pkpsbkf"/><stop offset="1" class="tuo24kjcb"/></radialGradient><radialGradient id="iCWctGe" cx="0" cy="0" r="1" gradientTransform="matrix(-11.08933 -22.84163 16.64931 -8.08303 21.834 26.057)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="ov2d-rbnh"/><stop offset="1" class="g8y54dbuj"/></radialGradient><radialGradient id="iXLh8Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02787 21.09753 -16.47044 -2.3638 14.08 8.245)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="b7xtxdwgx"/><stop offset="1" class="mxh-2vbgw"/></radialGradient><radialGradient id="iUoSLvG" cx="0" cy="0" r="1" gradientTransform="matrix(2.01898 0 0 3.58595 9.99 21.899)" gradientUnits="userSpaceOnUse"><stop class="kr77r6b7q"/><stop offset="1" class="n1nhqibha"/><stop offset="1" class="y69jgzb9u"/></radialGradient><radialGradient id="iJXZ0Rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.78125 1.10077 0 9.88 18.67)" gradientUnits="userSpaceOnUse"><stop class="cizba4bqb"/><stop offset="1" class="gme4zsb3v"/></radialGradient><radialGradient id="iShd0vb" cx="0" cy="0" r="1" gradientTransform="matrix(6.96874 4.09377 -2.53183 4.30988 16.896 2.874)" gradientUnits="userSpaceOnUse"><stop class="p9rps_sqh"/><stop offset="1" class="bfgxzgb-n"/></radialGradient><radialGradient id="iEuiVVd" cx="0" cy="0" r="1" gradientTransform="rotate(4.645 -171.166 260.769)scale(5.41661 10.3169)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="oniokeg5c"/><stop offset="1" class="wnrg0_btk"/></radialGradient><radialGradient id="iZULrWJ" cx="0" cy="0" r="1" gradientTransform="rotate(157.557 4.27 10.867)scale(2.33294 1.92272)" gradientUnits="userSpaceOnUse"><stop class="bpzyi6xnk"/><stop offset="1" class="w74yu-sct"/></radialGradient><filter id="iQWiUgb" width="15.216" height="12.151" x="9.128" y="3.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".5"/></filter><filter id="i5noD8c" width="12.119" height="17.122" x="7.261" y="11.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".25"/></filter><filter id="iIaq2le" width="7.644" height="7.644" x="7.709" y="18.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".375"/></filter><filter id="ivfijtd" width="5.945" height="5.945" x="8.379" y="18.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".25"/></filter><filter id="iu4uAve" width="18.421" height="26.794" x="6.485" y="2.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.580392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4819"/></filter><filter id="ipjXmmd" width="11.841" height="12.383" x="13.851" y="1.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".75"/></filter><filter id="iP8Tahe" width="12.757" height="22.687" x="6.629" y="7.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".75"/></filter><filter id="ibrhJTd" width="10.696" height="17.149" x="5.614" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4819"/></filter><filter id="iXvMKFe" width="8.725" height="7.879" x="6.127" y="1.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".1"/></filter><filter id="im0v2Wc" width="4.898" height="4.897" x="5.813" y="12.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".1"/></filter><filter id="i2yZ7Jb" width="10.143" height="7.663" x="16.242" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".15"/></filter><filter id="iC580Sb" width=".797" height="4.25" x="27.318" y="10.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4819" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-with-hearing-aid-medium-light" /></template>
<style>
.b7xtxdwgx {
  stop-color: var(--svg-color--bb738e, #BB738E);
  stop-opacity: 0;
}

.bfgxzgb-n {
  stop-color: var(--svg-color--959595, #959595);
  stop-opacity: 0;
}

.bjp4tgbbt {
  d: path("M16.06 2.565c4.482.307 8.086 3.904 8.32 8.403c0 2.076-.219 3.437-1.469 5.515l-1.656 2.938h2.602a3.25 3.25 0 0 0 3.25-3.25v-3.875c0-3.324-3.838-10.45-10.841-10.73a.2.2 0 0 0-.206.197z");
}

.bne7dsbcl {
  stop-color: var(--svg-color--b8694e, #B8694E);
}

.borhhobgo {
  stop-color: var(--svg-color--dadada, #DADADA);
  stop-opacity: 0;
}

.bpzyi6xnk {
  stop-color: var(--svg-color--cec8c7, #CEC8C7);
}

.cizba4bqb {
  stop-color: var(--svg-color--635951, #635951);
}

.ckm_w_bgk {
  stop-color: var(--svg-color--bf8569, #BF8569);
  stop-opacity: 0;
}

.d3ikkpb5y {
  stop-color: var(--svg-color--e9af97, #E9AF97);
}

.d7eywim1k {
  stop-color: var(--svg-color--917ea4, #917EA4);
}

.dkjt8_o6m {
  stop-color: var(--svg-color--fbc19c, #FBC19C);
}

.e14ccpbpi {
  stop-color: var(--svg-color--bbb, #BBB);
  stop-opacity: 0;
}

.emwabp4fw {
  stop-color: var(--svg-color--c17c71, #C17C71);
}

.eu-87q5qq {
  stop-color: var(--svg-color--bbb, #BBB);
}

.fgqhdzbrg {
  d: path("M5.615 10.948v.003q.014 1.125 0 2.251c-.016 1.25.66 2.113.972 2.379c.608.547 1.476.848 2.219 1.105c.437.152 1.152.438 1.152.97v.8l.93-.316c0-.508-.023-.986-.187-1.274c-.367-.644-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.704 4.137-8.429 8.903-8.429q.311 0 .62.021v-.814a.197.197 0 0 0-.197-.198c-5.13-.008-10.227 3.869-10.25 9.391");
}

.fkqbx3b-n {
  stop-color: var(--svg-color--d3cdcf, #D3CDCF);
}

.ft5dv1b6b {
  fill: none;
}

.g4udvybro {
  stop-color: var(--svg-color--ecebed, #ECEBED);
  stop-opacity: 0;
}

.g8y54dbuj {
  stop-color: var(--svg-color--c29a7c, #C29A7C);
}

.gme4zsb3v {
  stop-color: var(--svg-color--635951, #635951);
  stop-opacity: 0;
}

.grzcxhmih {
  stop-color: var(--svg-color--c17c71, #C17C71);
  stop-opacity: 0;
}

.h5tsjybzx {
  stop-color: var(--svg-color--a29f9f, #A29F9F);
  stop-opacity: 0;
}

.hf5wm2mfe {
  width: 2.016px;
  height: 4.955px;
  x: 26.048px;
  y: 10.474px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 0.5px;
}

.i2g6mlz6l {
  fill: var(--svg-color--cecad1, #CECAD1);
  d: path("M16.06 2.565c4.482.307 8.086 3.904 8.32 8.403c0 2.076-.219 3.437-1.469 5.515l-1.656 2.938h2.602a3.25 3.25 0 0 0 3.25-3.25v-3.875c0-3.324-3.838-10.45-10.841-10.73a.2.2 0 0 0-.206.197z");
}

.i9tykjb7d {
  stop-color: var(--svg-color--fdccaa, #FDCCAA);
}

.iab0nwb4s {
  stop-color: var(--svg-color--dadada, #DADADA);
}

.infs38bwt {
  fill: var(--svg-color--bfbdbd, #BFBDBD);
  d: path("M5.615 10.948v.003q.014 1.125 0 2.251c-.016 1.25.66 2.113.972 2.379c.608.547 1.476.848 2.219 1.105c.437.152 1.152.438 1.152.97v.8l.93-.316c0-.508-.023-.986-.187-1.274c-.367-.644-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.704 4.137-8.429 8.903-8.429q.311 0 .62.021v-.814a.197.197 0 0 0-.197-.198c-5.13-.008-10.227 3.869-10.25 9.391");
}

.jl0d1ud2w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.351 4c2.21.36 6.672 2.344 6.84 7.382");
}

.jl8dr8f0s {
  stop-color: var(--svg-color--bf8569, #BF8569);
}

.jqsrlfe5i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.115 13.14c-.021.541.165 1.853 1.578 2.453c1.765.75 2.656.828 2.718 1.843");
}

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.khw5u_pgi {
  stop-color: var(--svg-color--d89485, #D89485);
}

.kizuddckh {
  fill: var(--svg-color--ecb299, #ECB299);
  d: path("M6.485 23.142c0 3.125 2.489 5.959 5.659 6.2c2.284 0 4.299-1.325 5.252-3.104l5.55-9.826a8.96 8.96 0 1 0-16.462-4.903z");
}

.kq103abhv {
  d: path("M9.958 19.363a2.9 2.9 0 0 1 1.393-.357c.883 0 1.674.396 2.205 1.02a2.318 2.318 0 0 0-3.598-1.86z");
}

.kr77r6b7q {
  stop-color: var(--svg-color--ebb19a, #EBB19A);
}

.lwg_i8b5w {
  stop-color: var(--svg-color--b8694e, #B8694E);
  stop-opacity: 0;
}

.m_f0evbyx {
  stop-color: var(--svg-color--ecebed, #ECEBED);
}

.m8zz4squb {
  stop-color: var(--svg-color--d89d8c, #D89D8C);
}

.mfdcdjbxa {
  cx: 11.351px;
  cy: 21.899px;
  r: 2.473px;
  fill: var(--svg-color--eaaf98, #EAAF98);
}

.mxh-2vbgw {
  stop-color: var(--svg-color--bb738e, #BB738E);
}

.n1nhqibha {
  stop-color: var(--svg-color--b5877c, #B5877C);
  stop-opacity: 0;
}

.ne07wgnjt {
  stop-color: var(--svg-color--d3cdcf, #D3CDCF);
  stop-opacity: 0;
}

.nf1xib-zk {
  stop-color: var(--svg-color--7b608b, #7B608B);
}

.nnkw3ubao {
  stop-color: var(--svg-color--e7ba93, #E7BA93);
}

.nnp22abze {
  width: 2.016px;
  height: 4.955px;
  x: 26.048px;
  y: 10.474px;
  rx: 0.5px;
}

.o_zs0qeiu {
  cx: 11.531px;
  cy: 22.078px;
  r: 3.072px;
}

.ojom8obgb {
  stop-color: var(--svg-color--a86540, #A86540);
}

.oniokeg5c {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
}

.ov2d-rbnh {
  stop-color: var(--svg-color--c29a7c, #C29A7C);
  stop-opacity: 0;
}

.p07jz0bkj {
  cx: 16.736px;
  cy: 9.304px;
  rx: 7.02px;
  ry: 4.486px;
}

.p4a1uebzz {
  stop-color: var(--svg-color--a59eae, #A59EAE);
}

.p537izvvk {
  d: path("M17.535 22.433a1.736 1.736 0 0 0-2.352.665l-.828 1.466l-.018.034c-.353.658-1.114 1.27-2.059 1.27c-1.21 0-2.322-1.377-2.322-2.726V11.509a5.489 5.489 0 1 1 10.912.86c-.142.906.121 1.902.909 2.372c.867.517 2.009.202 2.286-.769A8.96 8.96 0 1 0 6.485 11.51v11.633c0 3.125 2.489 5.959 5.659 6.2c2.284 0 4.299-1.325 5.252-3.104l.81-1.433a1.736 1.736 0 0 0-.671-2.372");
}

.p9rps_sqh {
  stop-color: var(--svg-color--797979, #797979);
}

.pk2_uvofd {
  stop-color: var(--svg-color--fdc8a7, #FDC8A7);
}

.pkzs1bb5w {
  stop-color: var(--svg-color--fdc8a7, #FDC8A7);
  stop-opacity: 0;
}

.qb8dbxb5j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.642 2.189c2.44.331 6.964 1.608 9.343 6.863");
}

.reyko3bjq {
  d: path("M12.144 28.257c-3.17-.242-4.383-1.99-4.383-5.115V12.286l2.26-.15l8.86 8.829l-2.833 4.79c-.954 1.78-1.62 2.502-3.904 2.502");
}

.sd9-1cnwp {
  stop-color: var(--svg-color--bebdbc, #BEBDBC);
}

.sqji9tbob {
  stop-color: var(--svg-color--917ea4, #917EA4);
  stop-opacity: 0;
}

.sr9kiobma {
  stop-color: var(--svg-color--e9af97, #E9AF97);
  stop-opacity: 0;
}

.stmsp0bcc {
  stop-color: var(--svg-color--806693, #806693);
  stop-opacity: 0;
}

.sxjiylbiz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.879 9.407v14.18c.02.863.321 3.286 2.953 3.887c2.215.505 3.496-.663 4.123-1.839l1.18-2.049");
}

.trcx2qb5r {
  stop-color: var(--svg-color--b66e6c, #B66E6C);
  stop-opacity: 0;
}

.trqvfobih {
  stop-color: var(--svg-color--efb792, #EFB792);
}

.tuo24kjcb {
  stop-color: var(--svg-color--edb49a, #EDB49A);
  stop-opacity: 0;
}

.u1wxr7b2p {
  d: path("M27.568 10.952h.297v3.75h-.297z");
}

.u2e_6xu1e {
  stop-color: var(--svg-color--fdccaa, #FDCCAA);
  stop-opacity: 0;
}

.u2ven5bnf {
  fill: var(--svg-color--b6897b, #B6897B);
  d: path("M6.485 23.142c0 3.125 2.489 5.959 5.659 6.2c2.284 0 4.299-1.324 5.252-3.104l5.55-9.826A8.96 8.96 0 1 0 6.485 11.51z");
}

.ucgxbccuf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.552 2.189c-1.969.114-7.172 1.747-8.125 7.279");
}

.v05g5nbno {
  stop-color: var(--svg-color--b66e6c, #B66E6C);
}

.w4pkpsbkf {
  stop-color: var(--svg-color--edb49a, #EDB49A);
}

.w74yu-sct {
  stop-color: var(--svg-color--a99d99, #A99D99);
}

.wnrg0_btk {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
  stop-opacity: 0;
}

.y69jgzb9u {
  stop-color: var(--svg-color--ebb19a, #EBB19A);
  stop-opacity: 0;
}

.zl2taod9f {
  cx: 11.351px;
  cy: 21.899px;
  r: 2.893px;
}

</style>
