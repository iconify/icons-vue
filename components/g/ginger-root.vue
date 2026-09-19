<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ix0teGe)" class="rfzikp3bz"/><path fill="url(#ihwDobm)" class="rfzikp3bz"/><path fill="url(#iNfvfWd)" class="rfzikp3bz"/><path fill="url(#i6EmOwe)" class="rfzikp3bz"/><path fill="url(#isV24be)" class="rfzikp3bz"/><path fill="url(#itGYvge)" class="rfzikp3bz"/><path fill="url(#iRXKDEB)" class="rfzikp3bz"/><path fill="url(#iIqkPGc)" class="rfzikp3bz"/><path fill="url(#iu39vUd)" class="rfzikp3bz"/><path fill="url(#iziBJhi)" class="rfzikp3bz"/><path fill="url(#iHddTUb)" class="f1gv1pbaf"/><path fill="url(#igrEXBd)" class="f1gv1pbaf"/><path fill="url(#ijtsduc)" class="f1gv1pbaf"/><path fill="url(#i1Cox7c)" class="f1gv1pbaf"/><path fill="url(#izd3DBd)" class="fvqyelb1o"/><path fill="url(#iv1LoFe)" class="fvqyelb1o"/><path fill="url(#i3b1K9b)" class="fvqyelb1o"/><path fill="url(#itxLilb)" class="d36da5rfu"/><path fill="url(#iAitCrd)" class="d36da5rfu"/><path fill="url(#i8P1AMc)" class="d36da5rfu"/><path fill="url(#ih0jBym)" class="mvhuodbvy"/><path fill="url(#iCEkqBb)" class="cy7rf5brp"/><path fill="url(#iEpeWSn)" class="djezyrbhj"/><path fill="url(#iJwTukd)" class="hsiffo08c"/><path fill="url(#ipgvP5u)" class="vea5fob1x"/><path fill="url(#i1ZKhDd)" class="t738f9aaj"/><ellipse fill="url(#ioTu8ud)" transform="matrix(0 -1 -1 0 6 25)" class="lqb7p89fv"/><ellipse transform="matrix(0 -1 -1 0 6 25)" class="a65kefbgc"/><ellipse transform="matrix(0 -1 -1 0 5 23)" class="wl13lt0wj"/><defs><radialGradient id="ix0teGe" cx="0" cy="0" r="1" gradientTransform="matrix(-19.18738 13.50013 -5.85262 -8.31817 15 11.375)" gradientUnits="userSpaceOnUse"><stop class="jgpgehbsg"/><stop offset=".36" class="k8pj75b7s"/><stop offset=".666" class="fmolaacqd"/><stop offset="1" class="u0kg0ye1h"/></radialGradient><radialGradient id="ihwDobm" cx="0" cy="0" r="1" gradientTransform="matrix(7.03716 31.12499 -50.45928 11.40851 9.687 6.5)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="cbyvk9bqx"/><stop offset=".538" class="ntt5tkbzq"/></radialGradient><radialGradient id="iNfvfWd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.93748 5.50002 -11.3886 -6.08247 22.813 6.875)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="gosgl46wc"/><stop offset="1" class="e8cm3bblu"/></radialGradient><radialGradient id="i6EmOwe" cx="0" cy="0" r="1" gradientTransform="rotate(145.215 4.492 10.638)scale(35.3859 32.1748)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="s1hcrs_9h"/><stop offset=".466" class="a7s0crb5j"/></radialGradient><radialGradient id="isV24be" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 4 -10.24882 9.28798 25.313 19.563)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="bpe0tmbxr"/><stop offset="1" class="ffyczwbwz"/></radialGradient><radialGradient id="itGYvge" cx="0" cy="0" r="1" gradientTransform="rotate(55.939 -6.289 30.423)scale(2.67822 4.86572)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="n4q6zpbzd"/><stop offset=".751" class="i4v-rhbxy"/></radialGradient><radialGradient id="iRXKDEB" cx="0" cy="0" r="1" gradientTransform="rotate(145.38 4.344 6.634)scale(33.113 13.7115)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="bnqhl6bxa"/><stop offset=".259" class="w0u5oabjd"/></radialGradient><radialGradient id="iIqkPGc" cx="0" cy="0" r="1" gradientTransform="matrix(.5 1.5 -7.07514 2.35837 18.5 22.125)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="j_e40w04c"/><stop offset="1" class="j_6pdjhpt"/></radialGradient><radialGradient id="iu39vUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 6.96875 -4.17492 -.28083 2.875 20.656)" gradientUnits="userSpaceOnUse"><stop offset=".763" class="hwms2-gtn"/><stop offset=".916" class="pv44_2bdf"/></radialGradient><radialGradient id="iziBJhi" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 3.71875 -2.13557 .44865 4 17.188)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="y0smrlbxr"/><stop offset=".883" class="q_bz5jmsv"/></radialGradient><radialGradient id="iHddTUb" cx="0" cy="0" r="1" gradientTransform="rotate(105.843 6.089 18.84)scale(4.80763 14.7244)" gradientUnits="userSpaceOnUse"><stop class="ibjvjlbwm"/><stop offset=".479" class="gpxp-cbsd"/><stop offset="1" class="ktldxnn2u"/></radialGradient><radialGradient id="igrEXBd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18752 5.75 -3.21104 -.66316 30 20.938)" gradientUnits="userSpaceOnUse"><stop offset=".338" class="hw4eo-ben"/><stop offset="1" class="ds_8_3xwr"/></radialGradient><radialGradient id="ijtsduc" cx="0" cy="0" r="1" gradientTransform="matrix(.75 2.875 -7.70907 2.01107 27.125 24.25)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="m0mmfqbcn"/><stop offset="1" class="vmtlvegam"/></radialGradient><radialGradient id="i1Cox7c" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 11.50002 -12.51206 8.43203 24.719 22.094)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="i5n-4jpkp"/><stop offset=".41" class="cviya0n3x"/><stop offset=".429" class="xu9lmsb9l"/></radialGradient><radialGradient id="izd3DBd" cx="0" cy="0" r="1" gradientTransform="rotate(114.489 3.136 9.617)scale(13.1176 5.73097)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="dcd9-rbdb"/><stop offset=".433" class="f40t0151y"/><stop offset=".609" class="h3h-1nb-x"/><stop offset="1" class="uvl65x8uv"/></radialGradient><radialGradient id="iv1LoFe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.37502 5.43748 -2.61289 -2.58287 9.813 4.25)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="oq3xlcc-y"/><stop offset="1" class="h21k9fjks"/></radialGradient><radialGradient id="i3b1K9b" cx="0" cy="0" r="1" gradientTransform="rotate(86.112 -4.007 12.138)scale(6.45235 4.7907)" gradientUnits="userSpaceOnUse"><stop class="g0s80bkda"/><stop offset="1" class="v4w87tx_d"/></radialGradient><radialGradient id="itxLilb" cx="0" cy="0" r="1" gradientTransform="rotate(93.979 -2.036 20.602)scale(7.20487 20.8131)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="zt5f8hb4c"/><stop offset=".401" class="d0goqg8qt"/><stop offset=".623" class="skj9sqpsm"/><stop offset=".828" class="m8s9xpc4f"/></radialGradient><radialGradient id="iAitCrd" cx="0" cy="0" r="1" gradientTransform="rotate(114.444 3.31 19.505)scale(3.02076 5.16269)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="fp9m340lx"/><stop offset="1" class="g59zi40jx"/></radialGradient><radialGradient id="i8P1AMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.9629 3.125 -5.34083 3.35472 10.6 23.938)" gradientUnits="userSpaceOnUse"><stop/><stop offset="0" class="ot-edubir"/><stop offset="1" class="co7h6kbga"/></radialGradient><linearGradient id="ih0jBym" x1="9.375" x2="13.313" y1="5.438" y2="8.865" gradientUnits="userSpaceOnUse"><stop class="ess-80abc"/><stop offset=".413" class="rrfsiz3iz"/><stop offset="1" class="uerlukuqd"/></linearGradient><linearGradient id="iCEkqBb" x1="6.5" x2="11.5" y1="11.803" y2="11.803" gradientUnits="userSpaceOnUse"><stop class="nqoev-3qy"/><stop offset=".475" class="r5-9--yki"/><stop offset="1" class="ithxr1vto"/></linearGradient><linearGradient id="iEpeWSn" x1="7.125" x2="12.324" y1="14.875" y2="16.439" gradientUnits="userSpaceOnUse"><stop class="zxkkhpbdb"/><stop offset=".227" class="f29fq35mk"/><stop offset=".613" class="ivq2-5_et"/><stop offset=".838" class="nh_h50ojm"/><stop offset=".984" class="z6zy4uboa"/></linearGradient><linearGradient id="iJwTukd" x1="27" x2="24.375" y1="17" y2="23.316" gradientUnits="userSpaceOnUse"><stop class="gkv640t-r"/><stop offset=".224" class="t4mddlbch"/><stop offset=".61" class="j4r3zob0o"/><stop offset=".858" class="n9fkg9-ib"/><stop offset="1" class="g17jnccne"/></linearGradient><linearGradient id="ipgvP5u" x1="12.91" x2="21.061" y1="12.248" y2="14.736" gradientUnits="userSpaceOnUse"><stop class="y67_f8b2j"/><stop offset=".347" class="ewyocgbfq"/><stop offset=".613" class="cv87cnqaa"/><stop offset=".838" class="c-wf5r4uq"/><stop offset=".984" class="oniyhrllw"/></linearGradient><linearGradient id="i1ZKhDd" x1="16.887" x2="27.365" y1="7.938" y2="15.076" gradientUnits="userSpaceOnUse"><stop class="thap6abzz"/><stop offset=".4" class="g5wp4qb0k"/><stop offset="1" class="iqss2o3ha"/></linearGradient><linearGradient id="ioTu8ud" x1="8.906" x2=".25" y1="2.313" y2="2.813" gradientUnits="userSpaceOnUse"><stop class="hjoxs5bzb"/><stop offset=".367" class="jxkfj9b9k"/><stop offset=".968" class="duidhcbhq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ginger-root" /></template>
<style>
.a65kefbgc {
  cx: 5px;
  cy: 1.906px;
  fill: var(--svg-color--fbba60, #FBBA60);
  rx: 5px;
  ry: 1.906px;
}

.a7s0crb5j {
  stop-color: var(--svg-color--c89066, #C89066);
}

.bnqhl6bxa {
  stop-color: var(--svg-color--d9935e, #D9935E);
}

.bpe0tmbxr {
  stop-color: var(--svg-color--a75d43, #A75D43);
}

.c-wf5r4uq {
  stop-color: var(--svg-color--bf5a60, #BF5A60);
}

.cbyvk9bqx {
  stop-color: var(--svg-color--da6c74, #DA6C74);
  stop-opacity: 0;
}

.co7h6kbga {
  stop-color: var(--svg-color--bd5352, #BD5352);
  stop-opacity: 0;
}

.cv87cnqaa {
  stop-color: var(--svg-color--cb6c50, #CB6C50);
}

.cviya0n3x {
  stop-color: var(--svg-color--d07530, #D07530);
}

.cy7rf5brp {
  d: path("M6.5 12.128v-1.044a6.9 6.9 0 0 1 5 .53v1.153a5.9 5.9 0 0 0-5-.64");
}

.d0goqg8qt {
  stop-color: var(--svg-color--c26745, #C26745);
}

.d36da5rfu {
  d: path("m11.4 26.414l-.8-2.155c2.103-.54 3.314-.93 4.768-1.52l.72 1.937a.5.5 0 0 0 .468.326h4.953a1.5 1.5 0 0 1 1.5 1.5v1.997a1.5 1.5 0 0 1-1.5 1.5h-4.953a5.5 5.5 0 0 1-5.156-3.585");
}

.dcd9-rbdb {
  stop-color: var(--svg-color--cb764d, #CB764D);
}

.djezyrbhj {
  d: path("M10.07 24.376c.457-1.922.424-3.993.001-5.802c-.378-1.615-1.09-3.108-2.116-4.078q-.617.165-1.271.278c1.097.67 1.97 2.133 2.413 4.028c.425 1.817.42 3.91-.115 5.78q.551-.093 1.087-.206");
}

.ds_8_3xwr {
  stop-color: var(--svg-color--d27843, #D27843);
  stop-opacity: 0;
}

.duidhcbhq {
  stop-color: var(--svg-color--d68a61, #D68A61);
}

.e8cm3bblu {
  stop-color: var(--svg-color--ffa469, #FFA469);
  stop-opacity: 0;
}

.ess-80abc {
  stop-color: var(--svg-color--d9946a, #D9946A);
}

.ewyocgbfq {
  stop-color: var(--svg-color--d47a4d, #D47A4D);
}

.f1gv1pbaf {
  d: path("m24.369 23.35l-5.32-2.419c.639-2.994 3.592-5.555 6.053-4.386l.423-.039c2.58-.238 4.556 2.252 3.737 4.71l-.02.056a3.59 3.59 0 0 1-4.873 2.077");
}

.f29fq35mk {
  stop-color: var(--svg-color--cb7a4c, #CB7A4C);
}

.f40t0151y {
  stop-color: var(--svg-color--ec894d, #EC894D);
}

.ffyczwbwz {
  stop-color: var(--svg-color--bf6738, #BF6738);
  stop-opacity: 0;
}

.fmolaacqd {
  stop-color: var(--svg-color--e58453, #E58453);
}

.fp9m340lx {
  stop-color: var(--svg-color--925037, #925037);
}

.ft5dv1b6b {
  fill: none;
}

.fvqyelb1o {
  d: path("m14.146 2.45l.805.804l.61.608a1.5 1.5 0 0 1-.002 2.123l-3.913 3.903a.5.5 0 0 0-.146.354v2.79c-1.672.968-2.516 1.312-5 1.772v-4.561a5.5 5.5 0 0 1 1.61-3.89l3.916-3.905a1.5 1.5 0 0 1 2.12.001");
}

.g0s80bkda {
  stop-color: var(--svg-color--d27b47, #D27B47);
}

.g17jnccne {
  stop-color: var(--svg-color--c05a6e, #C05A6E);
}

.g59zi40jx {
  stop-color: var(--svg-color--925037, #925037);
  stop-opacity: 0;
}

.g5wp4qb0k {
  stop-color: var(--svg-color--da7d52, #DA7D52);
}

.gkv640t-r {
  stop-color: var(--svg-color--c87030, #C87030);
}

.gosgl46wc {
  stop-color: var(--svg-color--ffc17b, #FFC17B);
}

.gpxp-cbsd {
  stop-color: var(--svg-color--de8237, #DE8237);
}

.h21k9fjks {
  stop-color: var(--svg-color--ffc080, #FFC080);
  stop-opacity: 0;
}

.h3h-1nb-x {
  stop-color: var(--svg-color--fb9a64, #FB9A64);
}

.hjoxs5bzb {
  stop-color: var(--svg-color--df8366, #DF8366);
}

.hsiffo08c {
  d: path("M25.992 16.492c-.939.753-1.623 1.79-2.067 2.897a9.1 9.1 0 0 0-.65 3.462l1.022.465c-.093-1.105.086-2.385.556-3.555c.511-1.274 1.343-2.36 2.48-2.957a3.5 3.5 0 0 0-1.34-.312");
}

.hw4eo-ben {
  stop-color: var(--svg-color--b36c49, #B36C49);
}

.hwms2-gtn {
  stop-color: var(--svg-color--d07756, #D07756);
}

.i4v-rhbxy {
  stop-color: var(--svg-color--e48c53, #E48C53);
  stop-opacity: 0;
}

.i5n-4jpkp {
  stop-color: var(--svg-color--d57831, #D57831);
  stop-opacity: 0;
}

.ibjvjlbwm {
  stop-color: var(--svg-color--f19a67, #F19A67);
}

.iqss2o3ha {
  stop-color: var(--svg-color--b56a5d, #B56A5D);
}

.ithxr1vto {
  stop-color: var(--svg-color--b56639, #B56639);
}

.ivq2-5_et {
  stop-color: var(--svg-color--c4684e, #C4684E);
}

.j_6pdjhpt {
  stop-color: var(--svg-color--c85d5a, #C85D5A);
  stop-opacity: 0;
}

.j_e40w04c {
  stop-color: var(--svg-color--c85d5a, #C85D5A);
}

.j4r3zob0o {
  stop-color: var(--svg-color--c56c48, #C56C48);
}

.jgpgehbsg {
  stop-color: var(--svg-color--faab71, #FAAB71);
}

.jxkfj9b9k {
  stop-color: var(--svg-color--c26d48, #C26D48);
}

.k8pj75b7s {
  stop-color: var(--svg-color--fa9b63, #FA9B63);
}

.ktldxnn2u {
  stop-color: var(--svg-color--c65e6a, #C65E6A);
}

.lqb7p89fv {
  cx: 5px;
  cy: 2px;
  rx: 5px;
  ry: 2px;
}

.m0mmfqbcn {
  stop-color: var(--svg-color--d3698d, #D3698D);
}

.m8s9xpc4f {
  stop-color: var(--svg-color--e66483, #E66483);
}

.mvhuodbvy {
  d: path("M9.628 4.842c.283.783.793 1.6 1.456 2.193c.753.673 1.658 1.022 2.647.776l-1.056 1.054c-.863-.106-1.63-.525-2.257-1.085c-.673-.601-1.207-1.382-1.559-2.172z");
}

.n4q6zpbzd {
  stop-color: var(--svg-color--e58c57, #E58C57);
}

.n9fkg9-ib {
  stop-color: var(--svg-color--c05e71, #C05E71);
}

.nh_h50ojm {
  stop-color: var(--svg-color--c25d63, #C25D63);
}

.nqoev-3qy {
  stop-color: var(--svg-color--cc8257, #CC8257);
}

.ntt5tkbzq {
  stop-color: var(--svg-color--e16d8a, #E16D8A);
}

.oniyhrllw {
  stop-color: var(--svg-color--b4525b, #B4525B);
}

.oq3xlcc-y {
  stop-color: var(--svg-color--ffc080, #FFC080);
}

.ot-edubir {
  stop-color: var(--svg-color--bd5352, #BD5352);
}

.pv44_2bdf {
  stop-color: var(--svg-color--d07756, #D07756);
  stop-opacity: 0;
}

.q_bz5jmsv {
  stop-color: var(--svg-color--f0ad7c, #F0AD7C);
  stop-opacity: 0;
}

.r5-9--yki {
  stop-color: var(--svg-color--cb744a, #CB744A);
}

.rfzikp3bz {
  d: path("m14.146 2.45l.805.804l.61.608a1.5 1.5 0 0 1-.002 2.123l-3.913 3.903a.5.5 0 0 0-.146.354v2.79c2.766-1.454 5.656-4.766 7.113-7.622c1.437-2.818 5.667-.835 7.438.488c.644.48 1.21 1.007 1.686 1.55c1.56 1.782 2.14 3.746 1.282 4.895l-.074.093a2.6 2.6 0 0 1-.363.551c-.853 1-2.017 2.248-3.48 3.558l.423-.039c2.58-.238 4.556 2.252 3.736 4.71l-.019.056a3.59 3.59 0 0 1-4.873 2.077l-5.32-2.418a32 32 0 0 1-3.68 1.807l.719 1.937a.5.5 0 0 0 .469.326h4.953a1.5 1.5 0 0 1 1.5 1.5V28.5a1.5 1.5 0 0 1-1.5 1.5h-4.954a5.5 5.5 0 0 1-5.156-3.586l-.8-2.154A29.5 29.5 0 0 1 4 25v-1l.144-.577H4V15c.875 0 1.708-.069 2.5-.196v-4.561a5.5 5.5 0 0 1 1.61-3.89l3.916-3.905a1.5 1.5 0 0 1 2.12.001");
}

.rrfsiz3iz {
  stop-color: var(--svg-color--d0794c, #D0794C);
}

.s1hcrs_9h {
  stop-color: var(--svg-color--e38853, #E38853);
  stop-opacity: 0;
}

.skj9sqpsm {
  stop-color: var(--svg-color--d9636c, #D9636C);
}

.t4mddlbch {
  stop-color: var(--svg-color--db865a, #DB865A);
}

.t738f9aaj {
  d: path("M27.366 14.343c-1.074-1.55-2.62-3.01-4.325-4.224c-1.758-1.252-3.714-2.265-5.548-2.853q-.283.423-.606.86c1.798.53 3.783 1.532 5.573 2.808c1.707 1.216 3.207 2.66 4.195 4.142q.374-.375.711-.733");
}

.thap6abzz {
  stop-color: var(--svg-color--ce8456, #CE8456);
}

.u0kg0ye1h {
  stop-color: var(--svg-color--b66546, #B66546);
}

.uerlukuqd {
  stop-color: var(--svg-color--b35d36, #B35D36);
}

.uvl65x8uv {
  stop-color: var(--svg-color--fca76a, #FCA76A);
}

.v4w87tx_d {
  stop-color: var(--svg-color--d27b47, #D27B47);
  stop-opacity: 0;
}

.vea5fob1x {
  d: path("M18.996 20.963c-.047-2.549-.437-4.713-1.37-6.392c-.826-1.486-2.057-2.56-3.769-3.194q-.453.383-.947.742c1.833.52 3.052 1.516 3.841 2.937c.877 1.578 1.25 3.728 1.25 6.445h.012q.501-.263.983-.538");
}

.vmtlvegam {
  stop-color: var(--svg-color--d3698d, #D3698D);
  stop-opacity: 0;
}

.w0u5oabjd {
  stop-color: var(--svg-color--d9935e, #D9935E);
  stop-opacity: 0;
}

.wl13lt0wj {
  cx: 3px;
  cy: 1px;
  fill: var(--svg-color--fdd389, #FDD389);
  rx: 3px;
  ry: 1px;
}

.xu9lmsb9l {
  stop-color: var(--svg-color--e88f5d, #E88F5D);
}

.y0smrlbxr {
  stop-color: var(--svg-color--f0ad7c, #F0AD7C);
}

.y67_f8b2j {
  stop-color: var(--svg-color--e09463, #E09463);
}

.z6zy4uboa {
  stop-color: var(--svg-color--c85d80, #C85D80);
}

.zt5f8hb4c {
  stop-color: var(--svg-color--985438, #985438);
}

.zxkkhpbdb {
  stop-color: var(--svg-color--c47642, #C47642);
}

</style>
