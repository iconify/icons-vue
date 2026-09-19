<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNsIrjb)" class="amm16bywl"/><path fill="url(#i1Kmw0d)" class="amm16bywl"/><path fill="url(#iYi45gd)" class="amm16bywl"/><path fill="url(#iZlGbjc)" class="amm16bywl"/><path fill="url(#i4yZnAe)" class="amm16bywl"/><path fill="url(#itVrkBG)" class="amm16bywl"/><path fill="url(#iKuIl5c)" class="amm16bywl"/><path fill="url(#iepPRue)" class="amm16bywl"/><path fill="url(#iCFYAhA)" class="amm16bywl"/><path fill="url(#iRnKXoc)" class="amm16bywl"/><path fill="url(#i0EaaUc)" class="ld4vde_8c"/><path fill="url(#iCp8Ewf)" class="ld4vde_8c"/><path fill="url(#ihH51Jd)" class="ld4vde_8c"/><path fill="url(#iy7wbZb)" class="ld4vde_8c"/><path fill="url(#iMySsOc)" class="ld4vde_8c"/><path fill="url(#iACR7Ne)" class="ld4vde_8c"/><rect class="ppwkvcc5j"/><rect fill="url(#ioWrB9b)" class="gh4_nt9wv"/><rect fill="url(#imWrhOc)" class="gh4_nt9wv"/><rect fill="url(#i9Q3qfb)" class="gh4_nt9wv"/><rect fill="url(#iGiywxd)" class="gh4_nt9wv"/><rect fill="url(#iTW2PbX)" class="gh4_nt9wv"/><path fill="url(#ifoZasb)" clip-rule="evenodd" class="ueicrbwle"/><rect fill="url(#i5sYBbd)" class="uq42vn4qs"/><rect fill="url(#i1DZtad)" class="cgfq02iec"/><path class="e0jr20b4b"/><path fill="url(#itEBE2b)" class="jzjnfc1lu"/><path fill="url(#ickDvQc)" class="jzjnfc1lu"/><path class="iwfdd3peh"/><path fill="url(#i90h1ee)" class="cnxnu3lal"/><path fill="url(#i3lIYid)" class="cnxnu3lal"/><path class="tbu7381fl"/><path fill="url(#igfEIub)" class="zcng_izvy"/><path fill="url(#ic0PuSd)" class="zcng_izvy"/><path fill="url(#iaaz6bc)" class="zcng_izvy"/><defs><linearGradient id="iNsIrjb" x1="4.267" x2="26.226" y1="14.5" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="l2q5mpb7e"/><stop offset="1" class="rbj9qiess"/></linearGradient><linearGradient id="iYi45gd" x1="28.973" x2="20.618" y1="12.158" y2="12.158" gradientUnits="userSpaceOnUse"><stop class="r57oo7wbl"/><stop offset="1" class="rpha1cbbn"/></linearGradient><linearGradient id="itVrkBG" x1="4.478" x2="6.282" y1="19.374" y2="19.374" gradientUnits="userSpaceOnUse"><stop class="ekkyfe3qm"/><stop offset="1" class="kadhbmbgl"/></linearGradient><linearGradient id="iKuIl5c" x1="15.083" x2="15.083" y1="2.141" y2="4.42" gradientUnits="userSpaceOnUse"><stop class="puqfsbwbl"/><stop offset="1" class="y3pjvlb_t"/></linearGradient><linearGradient id="i0EaaUc" x1="10.165" x2="29.165" y1="23.685" y2="23.685" gradientUnits="userSpaceOnUse"><stop class="bsgil814o"/><stop offset="1" class="uku8a1opo"/></linearGradient><linearGradient id="iCp8Ewf" x1="29.165" x2="27.014" y1="25.674" y2="25.674" gradientUnits="userSpaceOnUse"><stop class="h3duidb2n"/><stop offset="1" class="yn6sod7kz"/></linearGradient><linearGradient id="ihH51Jd" x1="19.665" x2="19.665" y1="19" y2="20.977" gradientUnits="userSpaceOnUse"><stop class="cu7x8qbvf"/><stop offset="1" class="r8vjjmbsd"/></linearGradient><linearGradient id="iy7wbZb" x1="10.165" x2="12.163" y1="26.859" y2="26.859" gradientUnits="userSpaceOnUse"><stop class="vl7-j4qgm"/><stop offset="1" class="g41rv1hkg"/></linearGradient><linearGradient id="iMySsOc" x1="9.92" x2="10.555" y1="27.028" y2="27.028" gradientUnits="userSpaceOnUse"><stop class="i_rjs9b5m"/><stop offset="1" class="jp31yzc1t"/></linearGradient><linearGradient id="ioWrB9b" x1="13.665" x2="13.665" y1="11" y2="10.158" gradientUnits="userSpaceOnUse"><stop class="s59syw-fe"/><stop offset="1" class="s9dg_7x2k"/></linearGradient><linearGradient id="imWrhOc" x1="18.602" x2="16.915" y1="6" y2="6" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="krh1j1bey"/></linearGradient><linearGradient id="i9Q3qfb" x1="8.652" x2="10.326" y1="7.181" y2="7.181" gradientUnits="userSpaceOnUse"><stop offset=".538" class="s59syw-fe"/><stop offset="1" class="d42qxdb1o"/></linearGradient><linearGradient id="iTW2PbX" x1="13.665" x2="13.665" y1="2" y2="3.109" gradientUnits="userSpaceOnUse"><stop class="eb5ls61ge"/><stop offset="1" class="pvd-yfbie"/></linearGradient><linearGradient id="ifoZasb" x1="13.665" x2="13.665" y1="3.5" y2="9.5" gradientUnits="userSpaceOnUse"><stop class="v_h1m12iz"/><stop offset="1" class="xzgrzacsv"/></linearGradient><linearGradient id="i5sYBbd" x1="19.665" x2="19.665" y1="21" y2="22.5" gradientUnits="userSpaceOnUse"><stop class="vdg0tzser"/><stop offset="1" class="s05kpdb0e"/><stop offset="1" class="vubgjzbom"/></linearGradient><linearGradient id="i1DZtad" x1="19.665" x2="19.665" y1="23.344" y2="25" gradientUnits="userSpaceOnUse"><stop class="vdg0tzser"/><stop offset="1" class="vubgjzbom"/><stop offset="1" class="s05kpdb0e"/></linearGradient><linearGradient id="itEBE2b" x1="24.165" x2="24.165" y1="27.276" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".119" class="p-axe3bsi"/><stop offset=".572" class="laqgpacky"/></linearGradient><linearGradient id="ickDvQc" x1="27.596" x2="20.734" y1="29.123" y2="29.123" gradientUnits="userSpaceOnUse"><stop offset=".055" class="du6g03b5u"/><stop offset=".122" class="bja6dobdl"/><stop offset=".874" class="bja6dobdl"/><stop offset=".956" class="du6g03b5u"/></linearGradient><linearGradient id="i90h1ee" x1="17.415" x2="17.415" y1="27.276" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".119" class="p-axe3bsi"/><stop offset=".572" class="laqgpacky"/></linearGradient><linearGradient id="i3lIYid" x1="18.845" x2="15.985" y1="29.123" y2="29.123" gradientUnits="userSpaceOnUse"><stop offset=".029" class="du6g03b5u"/><stop offset=".122" class="bja6dobdl"/><stop offset=".874" class="bja6dobdl"/><stop offset=".994" class="du6g03b5u"/></linearGradient><linearGradient id="igfEIub" x1="12.165" x2="12.568" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="l0yn0nv4x"/><stop offset="1" class="dk3essbsz"/></linearGradient><linearGradient id="ic0PuSd" x1="13.415" x2="13.415" y1="27.276" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".119" class="p-axe3bsi"/><stop offset=".572" class="laqgpacky"/></linearGradient><linearGradient id="iaaz6bc" x1="11.986" x2="14.845" y1="29.123" y2="29.123" gradientUnits="userSpaceOnUse"><stop class="du6g03b5u"/><stop offset=".122" class="bja6dobdl"/><stop offset=".874" class="bja6dobdl"/><stop offset=".956" class="du6g03b5u"/></linearGradient><radialGradient id="i1Kmw0d" cx="0" cy="0" r="1" gradientTransform="matrix(10.4912 0 0 6.78348 14.21 21.272)" gradientUnits="userSpaceOnUse"><stop class="hy86vxtmt"/><stop offset="1" class="vf-wddbzo"/></radialGradient><radialGradient id="iZlGbjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3829 4.68745 0 8.348 30)" gradientUnits="userSpaceOnUse"><stop class="zzqshubrh"/><stop offset="1" class="ye6s6p0-w"/></radialGradient><radialGradient id="i4yZnAe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.87952 8.02268 -5.53316 -2.67567 12.077 4.99)" gradientUnits="userSpaceOnUse"><stop class="kx44tf-4t"/><stop offset="1" class="b8u_6z-9p"/></radialGradient><radialGradient id="iepPRue" cx="0" cy="0" r="1" gradientTransform="matrix(-.44124 9.42643 -1.33272 -.06238 9.068 6.765)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="ctys1cbfk"/><stop offset=".481" class="b8u_6z-9p"/></radialGradient><radialGradient id="iCFYAhA" cx="0" cy="0" r="1" gradientTransform="matrix(-5.96533 -.0481 .00532 -.66 13.545 11.195)" gradientUnits="userSpaceOnUse"><stop class="eon1lxbtd"/><stop offset=".758" class="b8u_6z-9p"/></radialGradient><radialGradient id="iRnKXoc" cx="0" cy="0" r="1" gradientTransform="rotate(126.061 2.672 7.481)scale(2.71326 3.15841)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="lpyq49bqx"/><stop offset=".758" class="b8u_6z-9p"/></radialGradient><radialGradient id="iACR7Ne" cx="0" cy="0" r="1" gradientTransform="rotate(44.828 -17.346 21.573)scale(2.19066 2.77661)" gradientUnits="userSpaceOnUse"><stop class="l81kz3bxg"/><stop offset="1" class="cas7u92oz"/></radialGradient><radialGradient id="iGiywxd" cx="0" cy="0" r="1" gradientTransform="rotate(126.591 2.166 7.75)scale(1.26205 2.7966)" gradientUnits="userSpaceOnUse"><stop class="yz1x8xtan"/><stop offset="1" class="d42qxdb1o"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hospital" /></template>
<style>
.amm16bywl {
  d: path("M5 5a2 2 0 0 1 2-2h16.165a2 2 0 0 1 2 2v14L10.5 30H5z");
}

.b8u_6z-9p {
  stop-color: var(--svg-color--7f6796, #7F6796);
  stop-opacity: 0;
}

.bja6dobdl {
  stop-color: var(--svg-color--dd2fb6, #DD2FB6);
  stop-opacity: 0;
}

.bsgil814o {
  stop-color: var(--svg-color--ceaff2, #CEAFF2);
}

.cas7u92oz {
  stop-color: var(--svg-color--868390, #868390);
  stop-opacity: 0;
}

.cgfq02iec {
  width: 15px;
  height: 1.5px;
  x: 12.165px;
  y: 23.5px;
  rx: 0.75px;
}

.cnxnu3lal {
  d: path("M16.165 28h2a.5.5 0 0 1 .5.5V30h-2.5z");
}

.ctys1cbfk {
  stop-color: var(--svg-color--6e5883, #6E5883);
  stop-opacity: 0.4;
}

.cu7x8qbvf {
  stop-color: var(--svg-color--b6b5bd, #B6B5BD);
}

.d42qxdb1o {
  stop-color: var(--svg-color--f2e4ff, #F2E4FF);
  stop-opacity: 0;
}

.dk3essbsz {
  stop-color: var(--svg-color--ee2fba, #EE2FBA);
  stop-opacity: 0;
}

.du6g03b5u {
  stop-color: var(--svg-color--871371, #871371);
}

.e0jr20b4b {
  fill: var(--svg-color--df30b8, #DF30B8);
  d: path("M21.165 28.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5V30h-6z");
}

.eb5ls61ge {
  stop-color: var(--svg-color--e8e6e8, #E8E6E8);
}

.ekkyfe3qm {
  stop-color: var(--svg-color--6d6277, #6D6277);
}

.eon1lxbtd {
  stop-color: var(--svg-color--6e5883, #6E5883);
  stop-opacity: 0.66;
}

.ft5dv1b6b {
  fill: none;
}

.g41rv1hkg {
  stop-color: var(--svg-color--a185c2, #A185C2);
  stop-opacity: 0;
}

.gh4_nt9wv {
  width: 9px;
  height: 9px;
  x: 9.165px;
  y: 2px;
  rx: 1px;
}

.h3duidb2n {
  stop-color: var(--svg-color--dfd8ee, #DFD8EE);
}

.hy86vxtmt {
  stop-color: var(--svg-color--938f98, #938F98);
}

.i_rjs9b5m {
  stop-color: var(--svg-color--8f7da5, #8F7DA5);
}

.iwfdd3peh {
  fill: var(--svg-color--df30b8, #DF30B8);
  d: path("M16.165 28h2a.5.5 0 0 1 .5.5V30h-2.5z");
}

.jp31yzc1t {
  stop-color: var(--svg-color--8f7da5, #8F7DA5);
  stop-opacity: 0;
}

.jzjnfc1lu {
  d: path("M21.165 28.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5V30h-6z");
}

.kadhbmbgl {
  stop-color: var(--svg-color--6d6277, #6D6277);
  stop-opacity: 0;
}

.krh1j1bey {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
  stop-opacity: 0;
}

.kx44tf-4t {
  stop-color: var(--svg-color--7f6796, #7F6796);
}

.l0yn0nv4x {
  stop-color: var(--svg-color--ee2fba, #EE2FBA);
}

.l2q5mpb7e {
  stop-color: var(--svg-color--826f96, #826F96);
}

.l81kz3bxg {
  stop-color: var(--svg-color--868390, #868390);
}

.laqgpacky {
  stop-color: var(--svg-color--de30b8, #DE30B8);
  stop-opacity: 0;
}

.ld4vde_8c {
  d: path("M10.165 21a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2v9H27l-2.75-1l-2.75 1h-3l-1-1l-1 1h-2l-1.168-1l-1.167 1h-2z");
}

.lpyq49bqx {
  stop-color: var(--svg-color--6e5883, #6E5883);
  stop-opacity: 0.85;
}

.p-axe3bsi {
  stop-color: var(--svg-color--361530, #361530);
  stop-opacity: 0.72;
}

.ppwkvcc5j {
  width: 9px;
  height: 9px;
  x: 9.165px;
  y: 2px;
  fill: var(--svg-color--f1e3ff, #F1E3FF);
  rx: 1px;
}

.puqfsbwbl {
  stop-color: var(--svg-color--8f8e8f, #8F8E8F);
}

.pvd-yfbie {
  stop-color: var(--svg-color--e8e6e8, #E8E6E8);
  stop-opacity: 0;
}

.r57oo7wbl {
  stop-color: var(--svg-color--bab5bf, #BAB5BF);
}

.r8vjjmbsd {
  stop-color: var(--svg-color--b6b5bd, #B6B5BD);
  stop-opacity: 0;
}

.rbj9qiess {
  stop-color: var(--svg-color--bbb5c4, #BBB5C4);
}

.rpha1cbbn {
  stop-color: var(--svg-color--bab5bf, #BAB5BF);
  stop-opacity: 0;
}

.s05kpdb0e {
  stop-color: var(--svg-color--f3eef8, #F3EEF8);
}

.s59syw-fe {
  stop-color: var(--svg-color--ddc9f3, #DDC9F3);
}

.s9dg_7x2k {
  stop-color: var(--svg-color--ddc9f3, #DDC9F3);
  stop-opacity: 0;
}

.tbu7381fl {
  fill: var(--svg-color--e839bd, #E839BD);
  d: path("M14.665 28h-2a.5.5 0 0 0-.5.5V30h2.5z");
}

.ueicrbwle {
  fill-rule: evenodd;
  d: path("M13.665 4a.5.5 0 0 0-.5.5V6h-1.5a.5.5 0 0 0 0 1h1.5v1.5a.5.5 0 0 0 1 0V7h1.5a.5.5 0 1 0 0-1h-1.5V4.5a.5.5 0 0 0-.5-.5m-1.5.5a1.5 1.5 0 0 1 3 0V5h.5a1.5 1.5 0 1 1 0 3h-.5v.5a1.5 1.5 0 1 1-3 0V8h-.5a1.5 1.5 0 0 1 0-3h.5z");
}

.uku8a1opo {
  stop-color: var(--svg-color--d4b8f6, #D4B8F6);
}

.uq42vn4qs {
  width: 15px;
  height: 1.5px;
  x: 12.165px;
  y: 21px;
  rx: 0.75px;
}

.v_h1m12iz {
  stop-color: var(--svg-color--e41653, #E41653);
}

.vdg0tzser {
  stop-color: var(--svg-color--e3caff, #E3CAFF);
}

.vf-wddbzo {
  stop-color: var(--svg-color--938f98, #938F98);
  stop-opacity: 0;
}

.vl7-j4qgm {
  stop-color: var(--svg-color--a185c2, #A185C2);
}

.vubgjzbom {
  stop-color: var(--svg-color--f3edf9, #F3EDF9);
}

.xzgrzacsv {
  stop-color: var(--svg-color--db1e6a, #DB1E6A);
}

.y3pjvlb_t {
  stop-color: var(--svg-color--8f8e8f, #8F8E8F);
  stop-opacity: 0;
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.ye6s6p0-w {
  stop-color: var(--svg-color--8665a3, #8665A3);
  stop-opacity: 0;
}

.yn6sod7kz {
  stop-color: var(--svg-color--dfd8ee, #DFD8EE);
  stop-opacity: 0;
}

.yz1x8xtan {
  stop-color: var(--svg-color--decaf4, #DECAF4);
}

.zcng_izvy {
  d: path("M14.665 28h-2a.5.5 0 0 0-.5.5V30h2.5z");
}

.zzqshubrh {
  stop-color: var(--svg-color--8665a3, #8665A3);
}

</style>
