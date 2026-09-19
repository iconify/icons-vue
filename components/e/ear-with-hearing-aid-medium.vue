<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="u2ven5bnf"/><g filter="url(#i8DxP4b)"><ellipse fill="url(#itMWdoc)" transform="rotate(26.087 16.736 9.304)" class="p07jz0bkj"/></g><g filter="url(#iaGvCIe)"><path fill="url(#i4qc7kc)" class="la2cwabqx"/><path fill="url(#iGio6Tc)" class="la2cwabqx"/></g><g filter="url(#i9aPCsR)"><circle fill="url(#iapatrc)" class="o_zs0qeiu"/></g><circle fill="url(#iDOfL9L)" class="zl2taod9f"/><circle fill="url(#iM95fND)" class="zl2taod9f"/><g filter="url(#iyTvpJQ)"><circle class="qjxk5cbpm"/></g><g filter="url(#ikqHzKM)"><path fill="url(#iyK44se)" class="zwfcdqbaj"/><path fill="url(#iWoULic)" class="zwfcdqbaj"/></g><path fill="url(#i1XEL7c)" class="zwfcdqbaj"/><path fill="url(#iOJdZLb)" class="zwfcdqbaj"/><path fill="url(#irgJB1c)" class="zwfcdqbaj"/><path fill="url(#iHZuLhe)" class="zwfcdqbaj"/><path fill="url(#iFOlXBd)" class="zwfcdqbaj"/><g filter="url(#iiZdDve)"><path stroke="url(#i8BNGJc)" class="jl0d1ud2w"/></g><g filter="url(#izlQOhV)"><path stroke="url(#i1XIyrd)" class="e1h0abc2q"/></g><rect fill="url(#i4dg7ff)" class="hf5wm2mfe"/><rect fill="url(#i8JT7hd)" class="nnp22abze"/><rect fill="url(#irj2PYb)" class="nnp22abze"/><g filter="url(#idJQ3Xd)"><path class="infs38bwt"/><path fill="url(#iJXZ0Rb)" class="fgqhdzbrg"/></g><path class="i2g6mlz6l"/><path fill="url(#iShd0vb)" class="bjp4tgbbt"/><path fill="url(#iEuiVVd)" class="bjp4tgbbt"/><path fill="url(#ioVccre)" class="bjp4tgbbt"/><path fill="url(#iZULrWJ)" class="kq103abhv"/><g filter="url(#iC7kfye)"><path stroke="url(#irisOtb)" class="ucgxbccuf"/></g><g filter="url(#iHjrkXE)"><path stroke="url(#idPYdzb)" class="jqsrlfe5i"/></g><g filter="url(#iPyKHuC)"><path stroke="url(#iptkFKb)" class="qb8dbxb5j"/></g><g filter="url(#iQ6WOjr)"><path fill="url(#iLuGTld)" class="u1wxr7b2p"/></g><defs><linearGradient id="i4qc7kc" x1="12.432" x2="9.776" y1="12.678" y2="18.072" gradientUnits="userSpaceOnUse"><stop class="tm-l66prr"/><stop offset="1" class="ugomiebrb"/></linearGradient><linearGradient id="iGio6Tc" x1="13.095" x2="15.023" y1="27.082" y2="21.688" gradientUnits="userSpaceOnUse"><stop offset=".218" class="jp8arbcli"/><stop offset="1" class="jh2_ekbyb"/></linearGradient><linearGradient id="iapatrc" x1="14.007" x2="11.792" y1="20.306" y2="24.205" gradientUnits="userSpaceOnUse"><stop offset=".34" class="rft_gryci"/><stop offset="1" class="ytqwx-wlz"/></linearGradient><linearGradient id="iDOfL9L" x1="11.351" x2="11.351" y1="19.006" y2="24.792" gradientUnits="userSpaceOnUse"><stop class="xfp71u_lw"/><stop offset="1" class="qljl7cbvu"/></linearGradient><linearGradient id="iyK44se" x1="11.166" x2="19.302" y1="30.939" y2="-.28" gradientUnits="userSpaceOnUse"><stop class="wdlm_ibqi"/><stop offset="1" class="a_2dfi9vb"/></linearGradient><linearGradient id="i8BNGJc" x1="24.096" x2="16.954" y1="11.382" y2="3.848" gradientUnits="userSpaceOnUse"><stop class="rzq7xjs3j"/><stop offset=".51" class="y_a1ke75n"/><stop offset="1" class="rzq7xjs3j"/></linearGradient><linearGradient id="i1XIyrd" x1="8.156" x2="20.632" y1="2.492" y2="23.808" gradientUnits="userSpaceOnUse"><stop class="ah975e0ge"/><stop offset=".698" class="v4a2fcceg"/></linearGradient><linearGradient id="i4dg7ff" x1="27.056" x2="27.056" y1="10.474" y2="15.429" gradientUnits="userSpaceOnUse"><stop class="kdl2hbbyb"/><stop offset="1" class="p4a1uebzz"/></linearGradient><linearGradient id="i8JT7hd" x1="27.593" x2="27.593" y1="15.688" y2="14.575" gradientUnits="userSpaceOnUse"><stop class="d7eywim1k"/><stop offset="1" class="sqji9tbob"/></linearGradient><linearGradient id="irj2PYb" x1="27.056" x2="27.056" y1="10.397" y2="10.866" gradientUnits="userSpaceOnUse"><stop class="eu-87q5qq"/><stop offset="1" class="e14ccpbpi"/></linearGradient><linearGradient id="ioVccre" x1="22.861" x2="22.861" y1="19.858" y2="17.213" gradientUnits="userSpaceOnUse"><stop class="nf1xib-zk"/><stop offset="1" class="stmsp0bcc"/></linearGradient><linearGradient id="irisOtb" x1="14.833" x2="6.677" y1="1.892" y2="8.939" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="idPYdzb" x1="6.239" x2="10.187" y1="13.249" y2="17.881" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="iptkFKb" x1="16.42" x2="30.608" y1="2.189" y2="7.394" gradientUnits="userSpaceOnUse"><stop class="h5tsjybzx"/><stop offset=".123" class="sd9-1cnwp"/><stop offset=".542" class="iab0nwb4s"/><stop offset=".763" class="borhhobgo"/></linearGradient><linearGradient id="iLuGTld" x1="27.716" x2="27.716" y1="9.624" y2="14.702" gradientUnits="userSpaceOnUse"><stop offset=".152" class="g4udvybro"/><stop offset=".5" class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><radialGradient id="itMWdoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0215 -7.89891 13.77585 -.0375 16.735 13.79)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="a65-qfb3x"/><stop offset=".848" class="nz9u2tjef"/></radialGradient><radialGradient id="iM95fND" cx="0" cy="0" r="1" gradientTransform="rotate(144.196 3.636 12.615)scale(2.50656 2.86251)" gradientUnits="userSpaceOnUse"><stop class="ulasi0k-c"/><stop offset="1" class="jkkqseb-y"/></radialGradient><radialGradient id="iWoULic" cx="0" cy="0" r="1" gradientTransform="matrix(3.73663 -5.36387 6.00566 4.18372 16.892 10.99)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="i6650-xam"/><stop offset="1" class="b382ogbnr"/></radialGradient><radialGradient id="i1XEL7c" cx="0" cy="0" r="1" gradientTransform="matrix(.13826 -4.4596 5.9153 .1834 22.418 15.27)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="m3x6io8eb"/><stop offset="1" class="u8xbn9b3q"/></radialGradient><radialGradient id="iOJdZLb" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.567 16.848)scale(4.79259 4.67362)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xvrv_6bis"/><stop offset="1" class="n_g-u-lhi"/></radialGradient><radialGradient id="irgJB1c" cx="0" cy="0" r="1" gradientTransform="matrix(-11.08937 -22.84172 16.6494 -8.08308 21.834 26.057)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="jsn-z3nbv"/><stop offset="1" class="m2pbtey6o"/></radialGradient><radialGradient id="iHZuLhe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02789 21.09763 -16.47054 -2.36382 14.08 8.245)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="c-fn9jb1q"/><stop offset="1" class="poosr8yyu"/></radialGradient><radialGradient id="iFOlXBd" cx="0" cy="0" r="1" gradientTransform="matrix(2.01899 0 0 3.58596 9.99 21.899)" gradientUnits="userSpaceOnUse"><stop class="z6--pfbwt"/><stop offset="1" class="n1nhqibha"/></radialGradient><radialGradient id="iJXZ0Rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.78125 1.10077 0 9.88 18.67)" gradientUnits="userSpaceOnUse"><stop class="cizba4bqb"/><stop offset="1" class="gme4zsb3v"/></radialGradient><radialGradient id="iShd0vb" cx="0" cy="0" r="1" gradientTransform="matrix(6.96874 4.09377 -2.53183 4.30988 16.896 2.874)" gradientUnits="userSpaceOnUse"><stop class="p9rps_sqh"/><stop offset="1" class="bfgxzgb-n"/></radialGradient><radialGradient id="iEuiVVd" cx="0" cy="0" r="1" gradientTransform="rotate(4.645 -171.166 260.769)scale(5.41661 10.3169)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="oniokeg5c"/><stop offset="1" class="wnrg0_btk"/></radialGradient><radialGradient id="iZULrWJ" cx="0" cy="0" r="1" gradientTransform="rotate(157.557 4.27 10.867)scale(2.33294 1.92272)" gradientUnits="userSpaceOnUse"><stop class="bpzyi6xnk"/><stop offset="1" class="w74yu-sct"/></radialGradient><filter id="i8DxP4b" width="15.216" height="12.151" x="9.128" y="3.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".5"/></filter><filter id="iaGvCIe" width="12.12" height="17.122" x="7.261" y="11.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".25"/></filter><filter id="i9aPCsR" width="7.644" height="7.644" x="7.708" y="18.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".375"/></filter><filter id="iyTvpJQ" width="5.945" height="5.945" x="8.379" y="18.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".25"/></filter><filter id="ikqHzKM" width="18.421" height="26.794" x="6.485" y="2.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.380392 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4791"/></filter><filter id="iiZdDve" width="11.841" height="12.383" x="13.851" y="1.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".75"/></filter><filter id="izlQOhV" width="12.757" height="22.688" x="6.629" y="7.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".75"/></filter><filter id="idJQ3Xd" width="10.696" height="17.149" x="5.614" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4791"/></filter><filter id="iC7kfye" width="8.725" height="7.879" x="6.127" y="1.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".1"/></filter><filter id="iHjrkXE" width="4.898" height="4.897" x="5.813" y="12.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".1"/></filter><filter id="iPyKHuC" width="10.143" height="7.663" x="16.242" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".15"/></filter><filter id="iQ6WOjr" width=".797" height="4.25" x="27.318" y="10.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4791" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-with-hearing-aid-medium" /></template>
<style>
.a_2dfi9vb {
  stop-color: var(--svg-color--bc977a, #BC977A);
}

.a65-qfb3x {
  stop-color: var(--svg-color--814a5c, #814A5C);
  stop-opacity: 0;
}

.ah975e0ge {
  stop-color: var(--svg-color--c59e8d, #C59E8D);
  stop-opacity: 0;
}

.b382ogbnr {
  stop-color: var(--svg-color--8d526c, #8D526C);
  stop-opacity: 0;
}

.bfgxzgb-n {
  stop-color: var(--svg-color--959595, #959595);
  stop-opacity: 0;
}

.bjp4tgbbt {
  d: path("M16.06 2.565c4.482.307 8.086 3.904 8.32 8.403c0 2.076-.219 3.437-1.469 5.515l-1.656 2.938h2.602a3.25 3.25 0 0 0 3.25-3.25v-3.875c0-3.324-3.838-10.45-10.841-10.73a.2.2 0 0 0-.206.197z");
}

.borhhobgo {
  stop-color: var(--svg-color--dadada, #DADADA);
  stop-opacity: 0;
}

.bpzyi6xnk {
  stop-color: var(--svg-color--cec8c7, #CEC8C7);
}

.c-fn9jb1q {
  stop-color: var(--svg-color--915877, #915877);
  stop-opacity: 0;
}

.cizba4bqb {
  stop-color: var(--svg-color--635951, #635951);
}

.d7eywim1k {
  stop-color: var(--svg-color--917ea4, #917EA4);
}

.e14ccpbpi {
  stop-color: var(--svg-color--bbb, #BBB);
  stop-opacity: 0;
}

.e1h0abc2q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.879 9.407v14.18c.02.863.321 3.286 2.953 3.887c2.215.505 3.496-.663 4.123-1.838l1.18-2.05");
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

.gme4zsb3v {
  stop-color: var(--svg-color--635951, #635951);
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

.i6650-xam {
  stop-color: var(--svg-color--8d526c, #8D526C);
}

.iab0nwb4s {
  stop-color: var(--svg-color--dadada, #DADADA);
}

.infs38bwt {
  fill: var(--svg-color--bfbdbd, #BFBDBD);
  d: path("M5.615 10.948v.003q.014 1.125 0 2.251c-.016 1.25.66 2.113.972 2.379c.608.547 1.476.848 2.219 1.105c.437.152 1.152.438 1.152.97v.8l.93-.316c0-.508-.023-.986-.187-1.274c-.367-.644-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.704 4.137-8.429 8.903-8.429q.311 0 .62.021v-.814a.197.197 0 0 0-.197-.198c-5.13-.008-10.227 3.869-10.25 9.391");
}

.jh2_ekbyb {
  stop-color: var(--svg-color--956761, #956761);
  stop-opacity: 0;
}

.jkkqseb-y {
  stop-color: var(--svg-color--c9a28e, #C9A28E);
  stop-opacity: 0;
}

.jl0d1ud2w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.351 4c2.21.36 6.672 2.344 6.84 7.382");
}

.jp8arbcli {
  stop-color: var(--svg-color--956761, #956761);
}

.jqsrlfe5i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.115 13.14c-.021.541.165 1.853 1.578 2.453c1.765.75 2.656.828 2.718 1.843");
}

.jsn-z3nbv {
  stop-color: var(--svg-color--9a7e69, #9A7E69);
  stop-opacity: 0;
}

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.kq103abhv {
  d: path("M9.958 19.363a2.9 2.9 0 0 1 1.393-.357c.883 0 1.674.396 2.205 1.02a2.318 2.318 0 0 0-3.598-1.86z");
}

.la2cwabqx {
  d: path("M12.144 28.257c-3.17-.242-4.383-1.99-4.383-5.115V12.286l2.26-.15l8.86 8.829l-2.833 4.791c-.954 1.78-1.62 2.501-3.904 2.501");
}

.m_f0evbyx {
  stop-color: var(--svg-color--ecebed, #ECEBED);
}

.m2pbtey6o {
  stop-color: var(--svg-color--9a7e69, #9A7E69);
}

.m3x6io8eb {
  stop-color: var(--svg-color--b6897b, #B6897B);
}

.n_g-u-lhi {
  stop-color: var(--svg-color--b78a7d, #B78A7D);
  stop-opacity: 0;
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

.nnp22abze {
  width: 2.016px;
  height: 4.955px;
  x: 26.048px;
  y: 10.474px;
  rx: 0.5px;
}

.nz9u2tjef {
  stop-color: var(--svg-color--814a5c, #814A5C);
}

.o_zs0qeiu {
  cx: 11.531px;
  cy: 22.078px;
  r: 3.072px;
}

.oniokeg5c {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
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

.p9rps_sqh {
  stop-color: var(--svg-color--797979, #797979);
}

.poosr8yyu {
  stop-color: var(--svg-color--915877, #915877);
}

.qb8dbxb5j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.642 2.189c2.44.331 6.964 1.608 9.343 6.863");
}

.qjxk5cbpm {
  cx: 11.351px;
  cy: 21.899px;
  r: 2.473px;
  fill: var(--svg-color--b28479, #B28479);
}

.qljl7cbvu {
  stop-color: var(--svg-color--a46b71, #A46B71);
}

.rft_gryci {
  stop-color: var(--svg-color--c39986, #C39986);
}

.rzq7xjs3j {
  stop-color: var(--svg-color--c8a28b, #C8A28B);
  stop-opacity: 0;
}

.sd9-1cnwp {
  stop-color: var(--svg-color--bebdbc, #BEBDBC);
}

.sqji9tbob {
  stop-color: var(--svg-color--917ea4, #917EA4);
  stop-opacity: 0;
}

.stmsp0bcc {
  stop-color: var(--svg-color--806693, #806693);
  stop-opacity: 0;
}

.tm-l66prr {
  stop-color: var(--svg-color--7e3e53, #7E3E53);
}

.u1wxr7b2p {
  d: path("M27.568 10.952h.297v3.75h-.297z");
}

.u2ven5bnf {
  fill: var(--svg-color--b6897b, #B6897B);
  d: path("M6.485 23.142c0 3.125 2.489 5.959 5.659 6.2c2.284 0 4.299-1.324 5.252-3.104l5.55-9.826A8.96 8.96 0 1 0 6.485 11.51z");
}

.u8xbn9b3q {
  stop-color: var(--svg-color--b6897b, #B6897B);
  stop-opacity: 0;
}

.ucgxbccuf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.552 2.189c-1.969.114-7.172 1.747-8.125 7.279");
}

.ugomiebrb {
  stop-color: var(--svg-color--7e3e53, #7E3E53);
  stop-opacity: 0;
}

.ulasi0k-c {
  stop-color: var(--svg-color--c9a28e, #C9A28E);
}

.v4a2fcceg {
  stop-color: var(--svg-color--c59e8d, #C59E8D);
}

.w74yu-sct {
  stop-color: var(--svg-color--a99d99, #A99D99);
}

.wdlm_ibqi {
  stop-color: var(--svg-color--9e716b, #9E716B);
}

.wnrg0_btk {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
  stop-opacity: 0;
}

.xfp71u_lw {
  stop-color: var(--svg-color--b1896f, #B1896F);
}

.xvrv_6bis {
  stop-color: var(--svg-color--b78a7d, #B78A7D);
}

.y_a1ke75n {
  stop-color: var(--svg-color--c8a28b, #C8A28B);
}

.ytqwx-wlz {
  stop-color: var(--svg-color--884461, #884461);
}

.z6--pfbwt {
  stop-color: var(--svg-color--b5877c, #B5877C);
}

.zl2taod9f {
  cx: 11.351px;
  cy: 21.899px;
  r: 2.893px;
}

.zwfcdqbaj {
  d: path("M17.535 22.433a1.736 1.736 0 0 0-2.352.665l-.828 1.466l-.018.034c-.353.658-1.114 1.27-2.059 1.27c-1.21 0-2.322-1.377-2.322-2.726V11.509a5.489 5.489 0 1 1 10.912.86c-.142.906.121 1.903.909 2.372c.867.517 2.009.202 2.286-.769A8.96 8.96 0 1 0 6.485 11.51v11.633c0 3.125 2.489 5.959 5.659 6.2c2.284 0 4.299-1.324 5.252-3.104l.81-1.432a1.736 1.736 0 0 0-.671-2.373");
}

</style>
