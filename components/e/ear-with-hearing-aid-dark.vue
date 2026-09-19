<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l_38xnb4s"/><g filter="url(#iErezce)"><ellipse fill="url(#ixw8lFd)" transform="rotate(26.087 16.721 9.27)" class="g_vtlrblm"/></g><g filter="url(#iIGiN7c)"><path fill="url(#i1v0mLO)" class="fcd9knbbv"/><path fill="url(#iH3rrPe)" class="fcd9knbbv"/></g><g filter="url(#ibsiubd)"><circle fill="url(#iq32sid)" class="vb23wybky"/></g><circle fill="url(#ij6SQlW)" class="a8rziglmk"/><circle fill="url(#ibQRlKe)" class="a8rziglmk"/><g filter="url(#irInUAd)"><circle class="zsa09zbyw"/></g><g filter="url(#imILIkb)"><path fill="url(#ihWOuhb)" class="g2hex4b-s"/><path fill="url(#iiNJtod)" class="g2hex4b-s"/></g><path fill="url(#idMYYub)" class="g2hex4b-s"/><path fill="url(#ijEpDxe)" class="g2hex4b-s"/><path fill="url(#iut9jyd)" class="g2hex4b-s"/><path fill="url(#i1Q9d9b)" class="g2hex4b-s"/><path fill="url(#igJTQDc)" class="g2hex4b-s"/><g filter="url(#igh41Xc)"><path stroke="url(#inUomac)" class="hf-qmhz6v"/></g><g filter="url(#ioL0dAT)"><path stroke="url(#inwsdZd)" class="ndouhpw3m"/></g><rect fill="url(#i4dg7ff)" class="hf5wm2mfe"/><rect fill="url(#i8JT7hd)" class="nnp22abze"/><rect fill="url(#irj2PYb)" class="nnp22abze"/><g filter="url(#iStNU9s)"><path class="infs38bwt"/><path fill="url(#iJXZ0Rb)" class="fgqhdzbrg"/></g><path class="i2g6mlz6l"/><path fill="url(#iShd0vb)" class="bjp4tgbbt"/><path fill="url(#iEuiVVd)" class="bjp4tgbbt"/><path fill="url(#ioVccre)" class="bjp4tgbbt"/><path fill="url(#iZULrWJ)" class="kq103abhv"/><g filter="url(#iJq7Ztc)"><path stroke="url(#irisOtb)" class="ucgxbccuf"/></g><g filter="url(#iiLp9md)"><path stroke="url(#idPYdzb)" class="jqsrlfe5i"/></g><g filter="url(#ipDYire)"><path stroke="url(#iptkFKb)" class="qb8dbxb5j"/></g><g filter="url(#iFG1xQb)"><path fill="url(#iLuGTld)" class="u1wxr7b2p"/></g><defs><linearGradient id="i1v0mLO" x1="12.41" x2="9.75" y1="12.649" y2="18.053" gradientUnits="userSpaceOnUse"><stop class="tyevozbbh"/><stop offset="1" class="idsvehz4j"/></linearGradient><linearGradient id="iH3rrPe" x1="13.074" x2="15.006" y1="27.078" y2="21.675" gradientUnits="userSpaceOnUse"><stop offset=".218" class="g5e3vv_5y"/><stop offset="1" class="why2-ob4q"/></linearGradient><linearGradient id="iq32sid" x1="13.988" x2="11.769" y1="20.29" y2="24.196" gradientUnits="userSpaceOnUse"><stop offset=".34" class="rfc_0qb7j"/><stop offset="1" class="c79pyv5gn"/></linearGradient><linearGradient id="ij6SQlW" x1="11.328" x2="11.328" y1="18.988" y2="24.784" gradientUnits="userSpaceOnUse"><stop class="mfsy38r1n"/><stop offset="1" class="b7j8ktbah"/></linearGradient><linearGradient id="ihWOuhb" x1="11.142" x2="19.292" y1="30.942" y2="-.331" gradientUnits="userSpaceOnUse"><stop class="ytkrke56o"/><stop offset="1" class="x4eddproi"/></linearGradient><linearGradient id="inUomac" x1="24.094" x2="16.94" y1="11.351" y2="3.805" gradientUnits="userSpaceOnUse"><stop class="iv9_edb6r"/><stop offset=".51" class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></linearGradient><linearGradient id="inwsdZd" x1="8.127" x2="20.625" y1="2.446" y2="23.799" gradientUnits="userSpaceOnUse"><stop class="iv9_edb6r"/><stop offset=".698" class="w-iwpvbqx"/></linearGradient><linearGradient id="i4dg7ff" x1="27.056" x2="27.056" y1="10.474" y2="15.429" gradientUnits="userSpaceOnUse"><stop class="kdl2hbbyb"/><stop offset="1" class="p4a1uebzz"/></linearGradient><linearGradient id="i8JT7hd" x1="27.593" x2="27.593" y1="15.688" y2="14.575" gradientUnits="userSpaceOnUse"><stop class="d7eywim1k"/><stop offset="1" class="sqji9tbob"/></linearGradient><linearGradient id="irj2PYb" x1="27.056" x2="27.056" y1="10.397" y2="10.866" gradientUnits="userSpaceOnUse"><stop class="eu-87q5qq"/><stop offset="1" class="e14ccpbpi"/></linearGradient><linearGradient id="ioVccre" x1="22.861" x2="22.861" y1="19.858" y2="17.213" gradientUnits="userSpaceOnUse"><stop class="nf1xib-zk"/><stop offset="1" class="stmsp0bcc"/></linearGradient><linearGradient id="irisOtb" x1="14.833" x2="6.677" y1="1.892" y2="8.939" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="idPYdzb" x1="6.239" x2="10.187" y1="13.249" y2="17.881" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="iptkFKb" x1="16.42" x2="30.608" y1="2.189" y2="7.394" gradientUnits="userSpaceOnUse"><stop class="h5tsjybzx"/><stop offset=".123" class="sd9-1cnwp"/><stop offset=".542" class="iab0nwb4s"/><stop offset=".763" class="borhhobgo"/></linearGradient><linearGradient id="iLuGTld" x1="27.716" x2="27.716" y1="9.624" y2="14.702" gradientUnits="userSpaceOnUse"><stop offset=".152" class="g4udvybro"/><stop offset=".5" class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><radialGradient id="ixw8lFd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.156 15.224 -1.456)scale(7.91248 13.7995)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="i6846hprv"/><stop offset=".848" class="eshz-rb6k"/></radialGradient><radialGradient id="ibQRlKe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03636 1.46888 -1.67748 -2.32554 13.945 20.704)" gradientUnits="userSpaceOnUse"><stop class="fin8ibbyo"/><stop offset="1" class="srtg8pbrk"/></radialGradient><radialGradient id="iiNJtod" cx="0" cy="0" r="1" gradientTransform="rotate(-55.138 18.934 -10.684)scale(6.54829 7.33179)" gradientUnits="userSpaceOnUse"><stop offset=".478" class="ivxtnnbrb"/><stop offset="1" class="eqlbbmb2a"/></radialGradient><radialGradient id="idMYYub" cx="0" cy="0" r="1" gradientTransform="matrix(.1385 -4.46724 5.92543 .1837 22.414 15.245)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="ggie7lb5u"/><stop offset="1" class="cp6_4jb6w"/></radialGradient><radialGradient id="ijEpDxe" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.564 16.839)scale(4.8008 4.68163)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="q46v90bmy"/><stop offset="1" class="f2kyhsbtr"/></radialGradient><radialGradient id="iut9jyd" cx="0" cy="0" r="1" gradientTransform="rotate(-115.896 19.07 6.192)scale(25.4348 18.5395)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="t_j3ms0ce"/><stop offset="1" class="x9yb4jxqn"/></radialGradient><radialGradient id="i1Q9d9b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03307 21.13376 -16.49875 -2.36787 14.06 8.209)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="boz64bi3p"/><stop offset="1" class="h74grvbep"/></radialGradient><radialGradient id="igJTQDc" cx="0" cy="0" r="1" gradientTransform="matrix(2.02245 0 0 3.59211 9.965 21.886)" gradientUnits="userSpaceOnUse"><stop class="bbuj36b9c"/><stop offset="1" class="n06-_je0v"/></radialGradient><radialGradient id="iJXZ0Rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.78125 1.10077 0 9.88 18.67)" gradientUnits="userSpaceOnUse"><stop class="cizba4bqb"/><stop offset="1" class="gme4zsb3v"/></radialGradient><radialGradient id="iShd0vb" cx="0" cy="0" r="1" gradientTransform="matrix(6.96874 4.09377 -2.53183 4.30988 16.896 2.874)" gradientUnits="userSpaceOnUse"><stop class="p9rps_sqh"/><stop offset="1" class="bfgxzgb-n"/></radialGradient><radialGradient id="iEuiVVd" cx="0" cy="0" r="1" gradientTransform="rotate(4.645 -171.166 260.769)scale(5.41661 10.3169)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="oniokeg5c"/><stop offset="1" class="wnrg0_btk"/></radialGradient><radialGradient id="iZULrWJ" cx="0" cy="0" r="1" gradientTransform="rotate(157.557 4.27 10.867)scale(2.33294 1.92272)" gradientUnits="userSpaceOnUse"><stop class="bpzyi6xnk"/><stop offset="1" class="w74yu-sct"/></radialGradient><filter id="iErezce" width="15.238" height="12.168" x="9.102" y="3.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".5"/></filter><filter id="iIGiN7c" width="12.139" height="17.149" x="7.231" y="11.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".25"/></filter><filter id="ibsiubd" width="7.655" height="7.655" x="7.68" y="18.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".375"/></filter><filter id="irInUAd" width="5.954" height="5.954" x="8.351" y="18.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".25"/></filter><filter id="imILIkb" width="18.452" height="26.84" x="6.453" y="2.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.220833 0 0 0 0 0.142622 0 0 0 0 0.193629 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4735"/></filter><filter id="igh41Xc" width="11.852" height="12.396" x="13.836" y="1.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".75"/></filter><filter id="ioL0dAT" width="12.771" height="22.719" x="6.601" y="7.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".75"/></filter><filter id="iStNU9s" width="10.696" height="17.149" x="5.614" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4735"/></filter><filter id="iJq7Ztc" width="8.725" height="7.879" x="6.127" y="1.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".1"/></filter><filter id="iiLp9md" width="4.898" height="4.897" x="5.813" y="12.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".1"/></filter><filter id="ipDYire" width="10.143" height="7.663" x="16.242" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".15"/></filter><filter id="iFG1xQb" width=".797" height="4.25" x="27.318" y="10.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4735" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-with-hearing-aid-dark" /></template>
<style>
.a8rziglmk {
  cx: 11.328px;
  cy: 21.886px;
  r: 2.898px;
}

.b7j8ktbah {
  stop-color: var(--svg-color--351920, #351920);
}

.bbuj36b9c {
  stop-color: var(--svg-color--50373a, #50373A);
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

.boz64bi3p {
  stop-color: var(--svg-color--432a42, #432A42);
  stop-opacity: 0;
}

.bpzyi6xnk {
  stop-color: var(--svg-color--cec8c7, #CEC8C7);
}

.c79pyv5gn {
  stop-color: var(--svg-color--150706, #150706);
}

.cizba4bqb {
  stop-color: var(--svg-color--635951, #635951);
}

.cp6_4jb6w {
  stop-color: var(--svg-color--51393b, #51393B);
  stop-opacity: 0;
}

.d7eywim1k {
  stop-color: var(--svg-color--917ea4, #917EA4);
}

.e14ccpbpi {
  stop-color: var(--svg-color--bbb, #BBB);
  stop-opacity: 0;
}

.eqlbbmb2a {
  stop-color: var(--svg-color--351c24, #351C24);
  stop-opacity: 0;
}

.eshz-rb6k {
  stop-color: var(--svg-color--2a1521, #2A1521);
}

.eu-87q5qq {
  stop-color: var(--svg-color--bbb, #BBB);
}

.f2kyhsbtr {
  stop-color: var(--svg-color--533b3d, #533B3D);
  stop-opacity: 0;
}

.fcd9knbbv {
  d: path("M12.122 28.255c-3.176-.242-4.39-1.993-4.39-5.124V12.257l2.263-.151l8.875 8.844l-2.838 4.8c-.955 1.782-1.622 2.505-3.91 2.505");
}

.fgqhdzbrg {
  d: path("M5.615 10.948v.003q.014 1.125 0 2.251c-.016 1.25.66 2.113.972 2.379c.608.547 1.476.848 2.219 1.105c.437.152 1.152.438 1.152.97v.8l.93-.316c0-.508-.023-.986-.187-1.274c-.367-.644-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.704 4.137-8.429 8.903-8.429q.311 0 .62.021v-.814a.197.197 0 0 0-.197-.198c-5.13-.008-10.227 3.869-10.25 9.391");
}

.fin8ibbyo {
  stop-color: var(--svg-color--725a58, #725A58);
}

.fkqbx3b-n {
  stop-color: var(--svg-color--d3cdcf, #D3CDCF);
}

.ft5dv1b6b {
  fill: none;
}

.g_vtlrblm {
  cx: 16.721px;
  cy: 9.27px;
  rx: 7.032px;
  ry: 4.493px;
}

.g2hex4b-s {
  d: path("M17.522 22.422a1.74 1.74 0 0 0-2.356.666l-.83 1.468l-.018.034c-.353.659-1.115 1.271-2.062 1.271c-1.212 0-2.326-1.379-2.326-2.73V11.48a5.498 5.498 0 1 1 10.93.86c-.141.908.122 1.907.911 2.377c.869.518 2.013.202 2.29-.77A8.976 8.976 0 1 0 6.453 11.48v11.65c0 3.131 2.493 5.97 5.669 6.212c2.288 0 4.306-1.328 5.261-3.11l.81-1.435a1.74 1.74 0 0 0-.671-2.376");
}

.g4udvybro {
  stop-color: var(--svg-color--ecebed, #ECEBED);
  stop-opacity: 0;
}

.g5e3vv_5y {
  stop-color: var(--svg-color--392828, #392828);
}

.ggie7lb5u {
  stop-color: var(--svg-color--51393b, #51393B);
}

.gme4zsb3v {
  stop-color: var(--svg-color--635951, #635951);
  stop-opacity: 0;
}

.h5tsjybzx {
  stop-color: var(--svg-color--a29f9f, #A29F9F);
  stop-opacity: 0;
}

.h74grvbep {
  stop-color: var(--svg-color--432a42, #432A42);
}

.hf-qmhz6v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.336 3.956c2.214.362 6.684 2.348 6.853 7.395");
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

.i6846hprv {
  stop-color: var(--svg-color--2a1521, #2A1521);
  stop-opacity: 0;
}

.iab0nwb4s {
  stop-color: var(--svg-color--dadada, #DADADA);
}

.idsvehz4j {
  stop-color: var(--svg-color--18080b, #18080B);
  stop-opacity: 0;
}

.infs38bwt {
  fill: var(--svg-color--bfbdbd, #BFBDBD);
  d: path("M5.615 10.948v.003q.014 1.125 0 2.251c-.016 1.25.66 2.113.972 2.379c.608.547 1.476.848 2.219 1.105c.437.152 1.152.438 1.152.97v.8l.93-.316c0-.508-.023-.986-.187-1.274c-.367-.644-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.704 4.137-8.429 8.903-8.429q.311 0 .62.021v-.814a.197.197 0 0 0-.197-.198c-5.13-.008-10.227 3.869-10.25 9.391");
}

.iv9_edb6r {
  stop-color: var(--svg-color--634f4d, #634F4D);
  stop-opacity: 0;
}

.ivxtnnbrb {
  stop-color: var(--svg-color--351c24, #351C24);
}

.jqsrlfe5i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.115 13.14c-.021.541.165 1.853 1.578 2.453c1.765.75 2.656.828 2.718 1.843");
}

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.kq103abhv {
  d: path("M9.958 19.363a2.9 2.9 0 0 1 1.393-.357c.883 0 1.674.396 2.205 1.02a2.318 2.318 0 0 0-3.598-1.86z");
}

.l_38xnb4s {
  fill: var(--svg-color--51393b, #51393B);
  d: path("M6.453 23.131c0 3.131 2.493 5.97 5.669 6.212c2.288 0 4.306-1.328 5.261-3.11l5.56-9.843a8.976 8.976 0 1 0-16.49-4.911z");
}

.m_f0evbyx {
  stop-color: var(--svg-color--ecebed, #ECEBED);
}

.mfsy38r1n {
  stop-color: var(--svg-color--432a26, #432A26);
}

.n06-_je0v {
  stop-color: var(--svg-color--50373a, #50373A);
  stop-opacity: 0;
}

.ndouhpw3m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.851 9.373v14.204c.021.865.322 3.292 2.958 3.893c2.22.507 3.502-.664 4.13-1.84l1.183-2.053");
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

.oniokeg5c {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
}

.p4a1uebzz {
  stop-color: var(--svg-color--a59eae, #A59EAE);
}

.p6wb4qngy {
  stop-color: var(--svg-color--634f4d, #634F4D);
}

.p9rps_sqh {
  stop-color: var(--svg-color--797979, #797979);
}

.q46v90bmy {
  stop-color: var(--svg-color--533b3d, #533B3D);
}

.qb8dbxb5j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.642 2.189c2.44.331 6.964 1.608 9.343 6.863");
}

.rfc_0qb7j {
  stop-color: var(--svg-color--5d4b49, #5D4B49);
}

.sd9-1cnwp {
  stop-color: var(--svg-color--bebdbc, #BEBDBC);
}

.sqji9tbob {
  stop-color: var(--svg-color--917ea4, #917EA4);
  stop-opacity: 0;
}

.srtg8pbrk {
  stop-color: var(--svg-color--65504e, #65504E);
  stop-opacity: 0;
}

.stmsp0bcc {
  stop-color: var(--svg-color--806693, #806693);
  stop-opacity: 0;
}

.t_j3ms0ce {
  stop-color: var(--svg-color--605654, #605654);
  stop-opacity: 0;
}

.tyevozbbh {
  stop-color: var(--svg-color--18080b, #18080B);
}

.u1wxr7b2p {
  d: path("M27.568 10.952h.297v3.75h-.297z");
}

.ucgxbccuf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.552 2.189c-1.969.114-7.172 1.747-8.125 7.279");
}

.vb23wybky {
  cx: 11.508px;
  cy: 22.066px;
  r: 3.077px;
}

.w-iwpvbqx {
  stop-color: var(--svg-color--6f5552, #6F5552);
}

.w74yu-sct {
  stop-color: var(--svg-color--a99d99, #A99D99);
}

.why2-ob4q {
  stop-color: var(--svg-color--392828, #392828);
  stop-opacity: 0;
}

.wnrg0_btk {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
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

.zsa09zbyw {
  cx: 11.328px;
  cy: 21.886px;
  r: 2.477px;
  fill: var(--svg-color--4e3538, #4E3538);
}

</style>
