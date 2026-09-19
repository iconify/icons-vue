<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEoSHGd)"><path class="x3qfn4brn"/><path fill="url(#iCpLofb)" class="nqqls644e"/></g><path fill="url(#iGy441b)" class="p0gn42i9s"/><path fill="url(#i0yw0Wc)" class="p0gn42i9s"/><path fill="url(#ikyLHod)" class="p0gn42i9s"/><path fill="url(#i4POuec)" class="p0gn42i9s"/><path fill="url(#ipwiCAe)" class="p0gn42i9s"/><path fill="url(#iy7plSd)" class="cefef_bhx"/><path fill="url(#iO40jwc)" class="cefef_bhx"/><path fill="url(#iH0BOOh)" class="cefef_bhx"/><path fill="url(#i027bId)" class="cefef_bhx"/><path fill="url(#iJbWbfc)" class="tmxgv_crf"/><path fill="url(#i0ejzkc)" class="tmxgv_crf"/><path fill="url(#i9SF6le)" class="tmxgv_crf"/><path fill="url(#iq07Ctb)" class="tmxgv_crf"/><path fill="url(#iv81dac)" class="cjvqupvzp"/><path fill="url(#iYVaGPc)" class="cjvqupvzp"/><path fill="url(#ikqBG7d)" class="cjvqupvzp"/><path fill="url(#iEqA97b)" class="cjvqupvzp"/><g filter="url(#iZxb9zc)"><path class="cegnkhlum"/><path fill="url(#imedwxe)" class="n9k4qm5zs"/></g><path fill="url(#isxKgBT)" class="n9k4qm5zs"/><path fill="url(#idJ1Dzb)" class="n9k4qm5zs"/><path fill="url(#ie9oO7b)" class="n9k4qm5zs"/><rect fill="url(#iktlGUb)" class="m4o-9tbct"/><rect fill="url(#ic13lGJ)" class="m4o-9tbct"/><rect fill="url(#i4cW5od)" class="m4o-9tbct"/><rect fill="url(#iVOn9Vd)" class="m4o-9tbct"/><rect fill="url(#isuptbe)" class="m4o-9tbct"/><rect fill="url(#i1mHLbb)" class="m4o-9tbct"/><rect fill="url(#iL24pQD)" class="m4o-9tbct"/><g filter="url(#i6kekvN)"><path fill="url(#idcjbSd)" class="w8wr8zy1a"/></g><g filter="url(#iEwwxWd)"><rect fill="url(#iqfTmDc)" class="orhnkubkv"/></g><g filter="url(#idxH3xb)"><rect fill="url(#iqDe9yQ)" class="o_d8c0bvx"/></g><g filter="url(#iIPsPBc)"><path class="cqx2tr5zn"/></g><defs><radialGradient id="iCpLofb" cx="0" cy="0" r="1" gradientTransform="matrix(3.22822 9.08798 -11.67443 4.14698 23 10.858)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="i-yav6bxe"/><stop offset="1" class="lt6871bhm"/></radialGradient><radialGradient id="iGy441b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.18707 8.35992 0 12.39 25.924)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i4POuec" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.3466 -6.91977 0 11.63 16.392)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="xl11_eyrk"/><stop offset=".959" class="c5re97b_y"/></radialGradient><radialGradient id="ipwiCAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.74168 6.33423 0 11.63 23.003)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="dy_weab9n"/><stop offset="1" class="me4bdnb9g"/></radialGradient><radialGradient id="iy7plSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.7595 7.31603 0 6.188 26.335)" gradientUnits="userSpaceOnUse"><stop class="i09uzfatx"/><stop offset="1" class="y-499dypd"/></radialGradient><radialGradient id="iH0BOOh" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.42709 -6.45029 0 5.263 17.275)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="x4i-inwif"/><stop offset="1" class="j25mqebcr"/></radialGradient><radialGradient id="i0ejzkc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.66527 0 0 -6.70115 21.267 22.315)" gradientUnits="userSpaceOnUse"><stop class="rzw7qgb7h"/><stop offset="1" class="qlqmhdzrc"/></radialGradient><radialGradient id="iv81dac" cx="0" cy="0" r="1" gradientTransform="rotate(-92.104 24.14 -2.35)scale(13.2673 7.2243)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="g1-86hb9w"/><stop offset=".577" class="rt_b8-x_q"/></radialGradient><radialGradient id="iYVaGPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.46536 1.87897 0 21.252 21.762)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="xipf_fzpq"/><stop offset="1" class="qjptw-bzp"/></radialGradient><radialGradient id="ikqBG7d" cx="0" cy="0" r="1" gradientTransform="matrix(3.2452 3.784 -11.4046 9.78069 20.912 13.966)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="msuafdc6v"/><stop offset="1" class="i7j7-gbni"/></radialGradient><radialGradient id="iEqA97b" cx="0" cy="0" r="1" gradientTransform="matrix(1.7611 -6.01353 6.78822 1.98797 26.324 23.656)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="q-5k2pvgj"/><stop offset=".508" class="gln_yjbnc"/></radialGradient><radialGradient id="imedwxe" cx="0" cy="0" r="1" gradientTransform="matrix(6.04842 0 0 1.15509 23.113 21.034)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="q_43ucc2o"/><stop offset="1" class="ppvm6tumn"/></radialGradient><radialGradient id="isxKgBT" cx="0" cy="0" r="1" gradientTransform="matrix(-11.7592 0 0 -9.5527 26.697 25.107)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="ebuze2bif"/><stop offset="1" class="jjr21icxl"/></radialGradient><radialGradient id="ie9oO7b" cx="0" cy="0" r="1" gradientTransform="matrix(.54129 1.709 -.78538 .24875 15.128 26.57)" gradientUnits="userSpaceOnUse"><stop class="au6cnxbpi"/><stop offset="1" class="vw1567wok"/></radialGradient><radialGradient id="iktlGUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.61197 -8.63989 0 28.234 9.124)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="r3nsh4-st"/><stop offset=".453" class="joo4jbc4c"/></radialGradient><radialGradient id="ic13lGJ" cx="0" cy="0" r="1" gradientTransform="matrix(-9.83928 0 0 -9.61491 28.84 9.506)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="ngsk8pbtg"/><stop offset="1" class="bk9wdr1lp"/></radialGradient><radialGradient id="i4cW5od" cx="0" cy="0" r="1" gradientTransform="rotate(-84.83 20.382 -5.198)scale(6.52837 9.41844)" gradientUnits="userSpaceOnUse"><stop class="dorsn7bwq"/><stop offset="1" class="xi-0glbac"/></radialGradient><radialGradient id="iVOn9Vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.875 -8.86618 0 24.82 5.28)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="fmjcfl2ww"/><stop offset=".872" class="n94gccc0k"/></radialGradient><radialGradient id="isuptbe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46077 0 0 -13.4107 27.11 9.506)" gradientUnits="userSpaceOnUse"><stop offset=".835" class="qsa8nlbls"/><stop offset="1" class="n9fixhbno"/></radialGradient><radialGradient id="i1mHLbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.96323 -2.65156 0 24.82 3.442)" gradientUnits="userSpaceOnUse"><stop class="kqa40dbdw"/><stop offset="1" class="yuso3ab5z"/></radialGradient><radialGradient id="iL24pQD" cx="0" cy="0" r="1" gradientTransform="rotate(-45 26.349 -19.259)scale(11.6673)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="akffx7x9c"/><stop offset="1" class="iew06ky3r"/></radialGradient><linearGradient id="i0yw0Wc" x1="8.511" x2="11.261" y1="20.059" y2="20.059" gradientUnits="userSpaceOnUse"><stop class="n0t_h9nuy"/><stop offset="1" class="ci4z4hbzz"/></linearGradient><linearGradient id="ikyLHod" x1="14.418" x2="13.27" y1="21.051" y2="21.051" gradientUnits="userSpaceOnUse"><stop class="ll0-0nb3t"/><stop offset="1" class="qy7x0bbwj"/></linearGradient><linearGradient id="iO40jwc" x1="8.865" x2="6.582" y1="22.019" y2="22.019" gradientUnits="userSpaceOnUse"><stop class="pmd736bmz"/><stop offset="1" class="sahwhdbbw"/></linearGradient><linearGradient id="i027bId" x1="8.654" x2="8.069" y1="15.54" y2="16.597" gradientUnits="userSpaceOnUse"><stop class="g1hrr4nao"/><stop offset="1" class="vqs4p1uad"/></linearGradient><linearGradient id="iJbWbfc" x1="14.307" x2="18.162" y1="22.611" y2="22.611" gradientUnits="userSpaceOnUse"><stop class="mubwp6b3p"/><stop offset="1" class="r3amml19k"/></linearGradient><linearGradient id="i9SF6le" x1="14.27" x2="15.158" y1="15.577" y2="17.058" gradientUnits="userSpaceOnUse"><stop class="dc_jn4bgr"/><stop offset="1" class="hv_eezh3w"/></linearGradient><linearGradient id="iq07Ctb" x1="15.394" x2="15.394" y1="27.183" y2="23.715" gradientUnits="userSpaceOnUse"><stop class="hhv3sbb9m"/><stop offset="1" class="ij7ku-bxq"/></linearGradient><linearGradient id="idJ1Dzb" x1="21.489" x2="21.489" y1="29.439" y2="27.705" gradientUnits="userSpaceOnUse"><stop class="skglr2n4q"/><stop offset="1" class="nd3i97bys"/></linearGradient><linearGradient id="idcjbSd" x1="25.924" x2="24.712" y1="26.107" y2="22.958" gradientUnits="userSpaceOnUse"><stop offset=".228" class="e5wym_bui"/><stop offset="1" class="h84x_3wve"/></linearGradient><linearGradient id="iqfTmDc" x1="6.514" x2="6.514" y1="14.961" y2="24.365" gradientUnits="userSpaceOnUse"><stop offset=".395" class="uspdh30af"/><stop offset="1" class="wrnrd7b-e"/></linearGradient><linearGradient id="iqDe9yQ" x1="12.359" x2="12.359" y1="14.303" y2="26.335" gradientUnits="userSpaceOnUse"><stop offset=".395" class="byvohqb8x"/><stop offset=".758" class="hnrupt13w"/></linearGradient><filter id="iEoSHGd" width="22.598" height="20.153" x="2.342" y="7.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.603922 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7122"/></filter><filter id="iZxb9zc" width="14.807" height="10.665" x="15.128" y="18.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.517647 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7122"/></filter><filter id="i6kekvN" width="13.325" height="6.947" x="16.434" y="20.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7122" stdDeviation=".75"/></filter><filter id="iEwwxWd" width="3.813" height="11.405" x="4.608" y="13.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7122" stdDeviation=".5"/></filter><filter id="idxH3xb" width="3.813" height="14.032" x="10.453" y="13.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7122" stdDeviation=".5"/></filter><filter id="iIPsPBc" width="7.27" height="6.265" x="7.292" y="8.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7122" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-at-the-viewer-medium-light" /></template>
<style>
.akffx7x9c {
  stop-color: var(--svg-color--f2c299, #F2C299);
  stop-opacity: 0;
}

.au6cnxbpi {
  stop-color: var(--svg-color--ce9486, #CE9486);
}

.bk9wdr1lp {
  stop-color: var(--svg-color--be9679, #BE9679);
}

.byvohqb8x {
  stop-color: var(--svg-color--d8a28c, #D8A28C);
}

.c5re97b_y {
  stop-color: var(--svg-color--b37296, #B37296);
}

.cefef_bhx {
  d: path("m8.602 24.829l.006.02a5 5 0 0 1-.096-1.027V15.54l-6.156.65v6.648c-.04 1.11.734 3.497 3.361 3.497c1.673 0 2.562-.981 2.885-1.506");
}

.cegnkhlum {
  fill: var(--svg-color--e9b18a, #E9B18A);
  d: path("M24.304 21.112c-.614.303-.954.605-1.484.605h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.815 3.81 3.815h4.398c4.586 0 5.738-2.665 5.994-3.815s.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.136");
}

.ci4z4hbzz {
  stop-color: var(--svg-color--b87961, #B87961);
  stop-opacity: 0;
}

.cjvqupvzp {
  d: path("M21.404 24.004c0-3.101-.071-8.177-.152-10.327l7.01-2.18c.752 3.973 1.035 10.013 1.136 12.507z");
}

.cqx2tr5zn {
  fill: var(--svg-color--dba887, #DBA887);
  d: path("M10.973 9.771c-1.005.17-1.878.949-2.18 1.393l2.937 1.787l1.332-2.968c-.757-.363-1.332-.34-2.09-.212");
}

.dc_jn4bgr {
  stop-color: var(--svg-color--c79178, #C79178);
}

.dorsn7bwq {
  stop-color: var(--svg-color--b77579, #B77579);
}

.dy_weab9n {
  stop-color: var(--svg-color--d19d81, #D19D81);
  stop-opacity: 0;
}

.e5wym_bui {
  stop-color: var(--svg-color--ffcdac, #FFCDAC);
}

.ebuze2bif {
  stop-color: var(--svg-color--c0896d, #C0896D);
  stop-opacity: 0;
}

.fmjcfl2ww {
  stop-color: var(--svg-color--b9787d, #B9787D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1-86hb9w {
  stop-color: var(--svg-color--fac19d, #FAC19D);
}

.g1hrr4nao {
  stop-color: var(--svg-color--d09d80, #D09D80);
}

.gln_yjbnc {
  stop-color: var(--svg-color--ffcba2, #FFCBA2);
  stop-opacity: 0;
}

.h84x_3wve {
  stop-color: var(--svg-color--ffcdac, #FFCDAC);
  stop-opacity: 0;
}

.hhv3sbb9m {
  stop-color: var(--svg-color--ad717b, #AD717B);
}

.hnrupt13w {
  stop-color: var(--svg-color--d8a28c, #D8A28C);
  stop-opacity: 0;
}

.hv_eezh3w {
  stop-color: var(--svg-color--c79178, #C79178);
  stop-opacity: 0;
}

.i-yav6bxe {
  stop-color: var(--svg-color--a76553, #A76553);
}

.i09uzfatx {
  stop-color: var(--svg-color--bd7e82, #BD7E82);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i7j7-gbni {
  stop-color: var(--svg-color--b57467, #B57467);
  stop-opacity: 0;
}

.iew06ky3r {
  stop-color: var(--svg-color--edc4a0, #EDC4A0);
}

.ij7ku-bxq {
  stop-color: var(--svg-color--ad717b, #AD717B);
  stop-opacity: 0;
}

.j25mqebcr {
  stop-color: var(--svg-color--b57697, #B57697);
}

.jjr21icxl {
  stop-color: var(--svg-color--be8664, #BE8664);
}

.joo4jbc4c {
  stop-color: var(--svg-color--e3ad8e, #E3AD8E);
}

.kqa40dbdw {
  stop-color: var(--svg-color--d0aa8a, #D0AA8A);
}

.ll0-0nb3t {
  stop-color: var(--svg-color--c68870, #C68870);
}

.lt6871bhm {
  stop-color: var(--svg-color--b37965, #B37965);
  stop-opacity: 0;
}

.m4o-9tbct {
  width: 10.852px;
  height: 12.128px;
  x: 19.394px;
  y: 3.442px;
  rx: 5.426px;
}

.me4bdnb9g {
  stop-color: var(--svg-color--d19d81, #D19D81);
}

.msuafdc6v {
  stop-color: var(--svg-color--b57467, #B57467);
}

.mubwp6b3p {
  stop-color: var(--svg-color--bf8065, #BF8065);
}

.n0t_h9nuy {
  stop-color: var(--svg-color--b87961, #B87961);
}

.n94gccc0k {
  stop-color: var(--svg-color--b77875, #B77875);
}

.n9fixhbno {
  stop-color: var(--svg-color--d0997f, #D0997F);
}

.n9k4qm5zs {
  d: path("M24.304 21.112c-.614.303-.954.605-1.484.605h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.815 3.81 3.815h4.398c4.586 0 5.738-2.665 5.994-3.815s.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.136");
}

.nd3i97bys {
  stop-color: var(--svg-color--c07f85, #C07F85);
  stop-opacity: 0;
}

.ngsk8pbtg {
  stop-color: var(--svg-color--be9679, #BE9679);
  stop-opacity: 0;
}

.nqqls644e {
  d: path("M17.149 7.515c1.114 0 2.569.681 3.043 1.045l3.998.181v18.503l-7.268.174c-1.381 0-1.908-.833-2.226-1.613c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468c-.323.525-1.212 1.506-2.885 1.506c-2.627 0-3.401-2.387-3.361-3.497v-7.071c-.07-.646.085-2.162 1.272-3.059c1.484-1.12 2.15-.832 3.755-1.968C8.844 9.521 9.23 9.256 10.32 8.984c.977-.19 1.978.075 3.407-.265c1.224-.292 2.029-1.204 3.422-1.204");
}

.o_d8c0bvx {
  width: 1.813px;
  height: 12.032px;
  x: 11.453px;
  y: 14.303px;
  rx: 0.906px;
}

.orhnkubkv {
  width: 1.813px;
  height: 9.405px;
  x: 5.608px;
  y: 14.961px;
  rx: 0.906px;
}

.p0gn42i9s {
  d: path("M15.04 26.473a3.7 3.7 0 0 1-.344-.668c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468q-.029.047-.064.098a52 52 0 0 1-.026-1.731V12.97l5.996 2.684v8.46c0 .555.4 1.295.624 1.707c.067.125.118.22.138.27c-.04.098-.119.23-.23.382");
}

.pmd736bmz {
  stop-color: var(--svg-color--c28469, #C28469);
}

.ppvm6tumn {
  stop-color: var(--svg-color--db9c72, #DB9C72);
  stop-opacity: 0;
}

.q_43ucc2o {
  stop-color: var(--svg-color--ce8b61, #CE8B61);
}

.q-5k2pvgj {
  stop-color: var(--svg-color--ffcba2, #FFCBA2);
}

.qjptw-bzp {
  stop-color: var(--svg-color--d39166, #D39166);
  stop-opacity: 0;
}

.qlqmhdzrc {
  stop-color: var(--svg-color--edb289, #EDB289);
  stop-opacity: 0;
}

.qsa8nlbls {
  stop-color: var(--svg-color--d0997f, #D0997F);
  stop-opacity: 0;
}

.qy7x0bbwj {
  stop-color: var(--svg-color--c68870, #C68870);
  stop-opacity: 0;
}

.r3amml19k {
  stop-color: var(--svg-color--bf8065, #BF8065);
  stop-opacity: 0;
}

.r3nsh4-st {
  stop-color: var(--svg-color--ffceaa, #FFCEAA);
}

.rt_b8-x_q {
  stop-color: var(--svg-color--dc9d80, #DC9D80);
}

.rzw7qgb7h {
  stop-color: var(--svg-color--edb289, #EDB289);
}

.sahwhdbbw {
  stop-color: var(--svg-color--c28469, #C28469);
  stop-opacity: 0;
}

.skglr2n4q {
  stop-color: var(--svg-color--b7749b, #B7749B);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.tmxgv_crf {
  d: path("m14.695 25.809l.001-.004l.02.05l.034.056v.023c.324.74.867 1.484 2.172 1.484l7.267-.174V16.19l-9.68-.337v8.755c0 .621.103 1.012.185 1.2");
}

.uspdh30af {
  stop-color: var(--svg-color--e4af95, #E4AF95);
}

.vqs4p1uad {
  stop-color: var(--svg-color--d09d80, #D09D80);
  stop-opacity: 0;
}

.vw1567wok {
  stop-color: var(--svg-color--ce9486, #CE9486);
  stop-opacity: 0;
}

.w8wr8zy1a {
  d: path("M21.773 24.072H18.95a1.017 1.017 0 0 0 0 2.035h5.502c2.68 0 3.875-.778 3.803-2.496s-2.31-2.045-3.803-.249c-.662.796-2.221.667-2.68.71");
}

.wrnrd7b-e {
  stop-color: var(--svg-color--e4af95, #E4AF95);
  stop-opacity: 0;
}

.x3qfn4brn {
  fill: var(--svg-color--d09c80, #D09C80);
  d: path("M17.149 7.515c1.114 0 2.569.681 3.043 1.045l3.998.181v18.503l-7.268.174c-1.381 0-1.908-.833-2.226-1.613c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468c-.323.525-1.212 1.506-2.885 1.506c-2.627 0-3.401-2.387-3.361-3.497v-7.071c-.07-.646.085-2.162 1.272-3.059c1.484-1.12 2.15-.832 3.755-1.968C8.844 9.521 9.23 9.256 10.32 8.984c.977-.19 1.978.075 3.407-.265c1.224-.292 2.029-1.204 3.422-1.204");
}

.x4i-inwif {
  stop-color: var(--svg-color--ba7884, #BA7884);
  stop-opacity: 0;
}

.xi-0glbac {
  stop-color: var(--svg-color--bc7c7f, #BC7C7F);
  stop-opacity: 0;
}

.xipf_fzpq {
  stop-color: var(--svg-color--d39166, #D39166);
}

.xl11_eyrk {
  stop-color: var(--svg-color--ba7686, #BA7686);
  stop-opacity: 0;
}

.y-499dypd {
  stop-color: var(--svg-color--bd7e82, #BD7E82);
  stop-opacity: 0;
}

.yuso3ab5z {
  stop-color: var(--svg-color--d0aa8a, #D0AA8A);
  stop-opacity: 0;
}

</style>
