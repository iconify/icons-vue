<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iOhaiAb)" class="iuzklhbga"/><path fill="url(#iKMzk7K)" class="iuzklhbga"/><path fill="url(#iyrBgJE)" class="r8xbnvblu"/><path fill="url(#iAokrHd)" class="iuzklhbga"/><path fill="url(#iV5jusU)" class="iuzklhbga"/><path fill="url(#iLijqbb)" class="iuzklhbga"/><path fill="url(#i441lvf)" class="iuzklhbga"/><path fill="url(#ijoUyhe)" class="iuzklhbga"/><path fill="url(#iQMx94c)" class="iuzklhbga"/><path fill="url(#ij1DPvc)" class="iuzklhbga"/><path fill="url(#i18qAcd)" class="iuzklhbga"/><path fill="url(#iMyv9ab)" class="iuzklhbga"/><path fill="url(#iRTnomZ)" class="iuzklhbga"/><path fill="url(#i04vTOc)" class="zryx9m45y"/><path fill="url(#iyHwHfe)" class="zryx9m45y"/><path fill="url(#iNVSvib)" class="zryx9m45y"/><path fill="url(#iJSnGVC)" class="qanvorrbe"/><path fill="url(#iipds9j)" class="qanvorrbe"/><path fill="url(#i83sfte)" class="qanvorrbe"/><path fill="url(#i9iY5Vb)" class="qanvorrbe"/><path fill="url(#igNMYfc)" class="xgojpzb8q"/><path fill="url(#iGwB5oc)" class="xgojpzb8q"/><path fill="url(#iEkvZub)" class="xgojpzb8q"/><path fill="url(#iRy4NGe)" class="w84hg4m6o"/><path fill="url(#iBNVeoc)" class="w84hg4m6o"/><path fill="url(#iY5BpNc)" clip-rule="evenodd" class="sk7ea5b4r"/><path fill="url(#iaXHfed)" clip-rule="evenodd" class="sk7ea5b4r"/><path fill="url(#ijeRk0d)" clip-rule="evenodd" class="yv_k_4zau"/><path fill="url(#idRIHFZ)" clip-rule="evenodd" class="yv_k_4zau"/><path fill="url(#i0JyR5b)" clip-rule="evenodd" class="h_psp-b-l"/><path fill="url(#iWWyaEe)" clip-rule="evenodd" class="h_psp-b-l"/><defs><radialGradient id="iOhaiAb" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.518 10.694)scale(38.9518)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iKMzk7K" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5003 17.5014 -22.41597 -4.48322 16.001 13.5)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iyrBgJE" cx="0" cy="0" r="1" gradientTransform="rotate(135 5.894 11.229)scale(41.0155)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="iAokrHd" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -3.176 18.935)scale(28.1492)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="iV5jusU" cx="0" cy="0" r="1" gradientTransform="rotate(76.632 -3.657 18.787)scale(28.2681)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="rbh43lblc"/><stop offset=".784" class="w9_b2xnds"/></radialGradient><radialGradient id="iLijqbb" cx="0" cy="0" r="1" gradientTransform="rotate(55.713 -8.307 24.362)scale(13.3146 9.65109)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="i441lvf" cx="0" cy="0" r="1" gradientTransform="rotate(9.866 -99.827 128.269)scale(11.6735)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="ijoUyhe" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -11.066 29.675)scale(59.0577)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iQMx94c" cx="0" cy="0" r="1" gradientTransform="rotate(118.42 6.566 13.952)scale(11.1109 23.8458)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="zs4j-ebbk"/><stop offset=".206" class="v1k_mhzfg"/></radialGradient><radialGradient id="ij1DPvc" cx="0" cy="0" r="1" gradientTransform="rotate(120.327 6.227 14.025)scale(4.44308 9.9921)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="yl2j1rbpx"/><stop offset=".381" class="c46ymlbbi"/></radialGradient><radialGradient id="i18qAcd" cx="0" cy="0" r="1" gradientTransform="rotate(6.34 -168.165 76.662)scale(3.65587)" gradientUnits="userSpaceOnUse"><stop class="w2ykmubdi"/><stop offset="1" class="luu9z8b7s"/></radialGradient><radialGradient id="iMyv9ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.41282 6.74561 -15.41766 -.94352 21.528 20.517)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="kx5ie-2_g"/><stop offset=".374" class="bzxwh_bwk"/></radialGradient><radialGradient id="iRTnomZ" cx="0" cy="0" r="1" gradientTransform="rotate(91.405 -5.338 14.62)scale(6.10364 14.0126)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="kx5ie-2_g"/><stop offset=".374" class="slu69yble"/></radialGradient><radialGradient id="i04vTOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.5 -8.41855 0 16 23.063)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="rl84unbtp"/><stop offset=".628" class="ixywm0blw"/><stop offset="1" class="opsjn_43s"/><stop offset="1" class="z3hv7yb0c"/></radialGradient><radialGradient id="iyHwHfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.33334 -7.8719 0 16 23.174)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="opsjn_43s"/><stop offset=".703" class="v_yvo_bdr"/><stop offset="1" class="opsjn_43s"/><stop offset="1" class="opsjn_43s"/></radialGradient><radialGradient id="iNVSvib" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.42755 -11.377 0 16 26.181)" gradientUnits="userSpaceOnUse"><stop offset=".646" class="d1yw2ybqf"/><stop offset="1" class="e1n-2pmnp"/></radialGradient><radialGradient id="iipds9j" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3125 -6.00026 0 22 18.105)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="n-bvd1bpq"/><stop offset=".558" class="mx2bekksp"/><stop offset=".868" class="ngji-tbxb"/></radialGradient><radialGradient id="i83sfte" cx="0" cy="0" r="1" gradientTransform="rotate(-177.108 12.242 9.5)scale(6.40942 3.35694)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="v-6q9pt0d"/><stop offset="1" class="c3rlkyimt"/></radialGradient><radialGradient id="i9iY5Vb" cx="0" cy="0" r="1" gradientTransform="rotate(136.043 8.927 14.518)scale(1.0172 2.21752)" gradientUnits="userSpaceOnUse"><stop class="a3x3cvnag"/><stop offset="1" class="bsfs-2stj"/></radialGradient><radialGradient id="igNMYfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3125 -6.00026 0 10 18.105)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="n-bvd1bpq"/><stop offset=".558" class="mx2bekksp"/><stop offset=".868" class="ngji-tbxb"/></radialGradient><radialGradient id="iGwB5oc" cx="0" cy="0" r="1" gradientTransform="rotate(-177.108 6.242 9.651)scale(6.40942 3.35694)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="v-6q9pt0d"/><stop offset="1" class="c3rlkyimt"/></radialGradient><radialGradient id="iEkvZub" cx="0" cy="0" r="1" gradientTransform="rotate(136.043 2.927 12.096)scale(1.0172 2.21752)" gradientUnits="userSpaceOnUse"><stop class="a3x3cvnag"/><stop offset="1" class="bsfs-2stj"/></radialGradient><radialGradient id="iRy4NGe" cx="0" cy="0" r="1" gradientTransform="rotate(-124.747 9.075 5.344)scale(3.41018 4.28513)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="e9kszrbto"/><stop offset=".822" class="xipei47ye"/><stop offset=".891" class="ph-k2-u8j"/><stop offset=".949" class="ph-k2-u8j"/><stop offset="1" class="jp9t1ybnb"/></radialGradient><radialGradient id="iBNVeoc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.169 5.588 6.148)scale(.41398 .77857)" gradientUnits="userSpaceOnUse"><stop class="a6qheewdr"/><stop offset="1" class="ale8fubzv"/></radialGradient><radialGradient id="iY5BpNc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24928 -2.23116 2.04341 -2.97585 22.224 15.53)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="u-u_g1lzh"/><stop offset=".822" class="xipei47ye"/><stop offset=".881" class="zid5bib0z"/><stop offset="1" class="lfb6bfp0s"/></radialGradient><radialGradient id="iaXHfed" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59444 3.11339 -2.51183 -2.09315 23.312 14.031)" gradientUnits="userSpaceOnUse"><stop offset=".646" class="f9hmxbczz"/><stop offset="1" class="zd74ke3mf"/></radialGradient><radialGradient id="ijeRk0d" cx="0" cy="0" r="1" gradientTransform="matrix(6.4923 -.03959 .06715 11.0119 6.44 9.696)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="u63y27bnx"/><stop offset=".589" class="f0ny1pgej"/><stop offset=".764" class="yo6_g40kf"/></radialGradient><radialGradient id="idRIHFZ" cx="0" cy="0" r="1" gradientTransform="matrix(4.98355 6.84921 -6.71474 4.88571 2.682 8.202)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="mu0k9qbeo"/><stop offset=".672" class="c0wky-n6o"/></radialGradient><radialGradient id="i0JyR5b" cx="0" cy="0" r="1" gradientTransform="matrix(5.47263 2.33393 -3.86413 9.06065 10.528 7.667)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="u63y27bnx"/><stop offset=".589" class="f0ny1pgej"/><stop offset=".66" class="f0ny1pgej"/><stop offset=".858" class="k4n7iybtz"/></radialGradient><radialGradient id="iWWyaEe" cx="0" cy="0" r="1" gradientTransform="matrix(6.77485 3.50006 -4.58307 8.87117 9.225 6.5)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="mu0k9qbeo"/><stop offset=".672" class="f7epodh6c"/></radialGradient><linearGradient id="iJSnGVC" x1="23.2" x2="22.965" y1="18.855" y2="20.266" gradientUnits="userSpaceOnUse"><stop class="d-sg2f4zs"/><stop offset="1" class="hvts7mbyo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:head-shaking-vertically" /></template>
<style>
.a3x3cvnag {
  stop-color: var(--svg-color--66515a, #66515A);
}

.a6qheewdr {
  stop-color: var(--svg-color--5a4950, #5A4950);
}

.ale8fubzv {
  stop-color: var(--svg-color--5d4c4f, #5D4C4F);
  stop-opacity: 0;
}

.bsfs-2stj {
  stop-color: var(--svg-color--58464d, #58464D);
  stop-opacity: 0;
}

.bzxwh_bwk {
  stop-color: var(--svg-color--ffb446, #FFB446);
  stop-opacity: 0;
}

.c0wky-n6o {
  stop-color: var(--svg-color--45a8f1, #45A8F1);
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.c3rlkyimt {
  stop-color: var(--svg-color--322020, #322020);
}

.c46ymlbbi {
  stop-color: var(--svg-color--ffb64d, #FFB64D);
  stop-opacity: 0;
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d-sg2f4zs {
  stop-color: var(--svg-color--52383e, #52383E);
}

.d1yw2ybqf {
  stop-color: var(--svg-color--4c2746, #4C2746);
  stop-opacity: 0;
}

.e1n-2pmnp {
  stop-color: var(--svg-color--4e2847, #4E2847);
}

.e9kszrbto {
  stop-color: var(--svg-color--4a2f37, #4A2F37);
}

.f0ny1pgej {
  stop-color: var(--svg-color--60c6ff, #60C6FF);
}

.f7epodh6c {
  stop-color: var(--svg-color--448cbf, #448CBF);
}

.f9hmxbczz {
  stop-color: var(--svg-color--362530, #362530);
  stop-opacity: 0;
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h_psp-b-l {
  fill-rule: evenodd;
  d: path("M11.449 1.684a1 1 0 0 1-.633 1.265c-1.103.367-4.278 2.469-3.82 7.968a1 1 0 1 1-1.993.166c-.541-6.5 3.284-9.4 5.18-10.032a1 1 0 0 1 1.266.633");
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hvts7mbyo {
  stop-color: var(--svg-color--432a35, #432A35);
}

.iuzklhbga {
  d: path("M16 31c9.335 0 14-6.268 14-14S25.335 3 16 3S2 9.268 2 17s4.665 14 14 14");
}

.ixywm0blw {
  stop-color: var(--svg-color--57444a, #57444A);
}

.jp9t1ybnb {
  stop-color: var(--svg-color--4d3635, #4D3635);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k4n7iybtz {
  stop-color: var(--svg-color--2399ed, #2399ED);
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kx5ie-2_g {
  stop-color: var(--svg-color--d77c49, #D77C49);
}

.lfb6bfp0s {
  stop-color: var(--svg-color--442e3e, #442E3E);
}

.luu9z8b7s {
  stop-color: var(--svg-color--d59a13, #D59A13);
  stop-opacity: 0;
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mu0k9qbeo {
  stop-color: var(--svg-color--3394ff, #3394FF);
  stop-opacity: 0;
}

.mx2bekksp {
  stop-color: var(--svg-color--56424d, #56424D);
}

.n-bvd1bpq {
  stop-color: var(--svg-color--4e3225, #4E3225);
}

.ngji-tbxb {
  stop-color: var(--svg-color--502a53, #502A53);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.opsjn_43s {
  stop-color: var(--svg-color--4e2553, #4E2553);
}

.ph-k2-u8j {
  stop-color: var(--svg-color--563e48, #563E48);
}

.qanvorrbe {
  d: path("M19.707 18.398a1 1 0 1 0-1.414 1.414c.525.525 1.847 1.293 3.707 1.293s3.183-.768 3.707-1.293a1 1 0 1 0-1.414-1.414c-.142.142-.953.707-2.293.707s-2.15-.565-2.293-.707");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.r8xbnvblu {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M16 31c9.335 0 14-6.268 14-14S25.335 3 16 3S2 9.268 2 17s4.665 14 14 14");
}

.rbh43lblc {
  stop-color: var(--svg-color--d1671a, #D1671A);
  stop-opacity: 0;
}

.rl84unbtp {
  stop-color: var(--svg-color--241a1a, #241A1A);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.sk7ea5b4r {
  fill-rule: evenodd;
  d: path("M23.93 14.02c.594.562.952 1.24 1.096 1.67a.5.5 0 0 0 .948-.317c-.19-.57-.631-1.392-1.355-2.08c-.732-.694-1.767-1.261-3.119-1.261a.5.5 0 1 0 0 1c1.048 0 1.846.432 2.43.987");
}

.slu69yble {
  stop-color: var(--svg-color--f58843, #F58843);
  stop-opacity: 0;
}

.u-u_g1lzh {
  stop-color: var(--svg-color--2f1f2a, #2F1F2A);
}

.u63y27bnx {
  stop-color: var(--svg-color--3394ff, #3394FF);
}

.v_yvo_bdr {
  stop-color: var(--svg-color--5e425a, #5E425A);
}

.v-6q9pt0d {
  stop-color: var(--svg-color--4d3231, #4D3231);
  stop-opacity: 0;
}

.v1k_mhzfg {
  stop-color: var(--svg-color--ffb34d, #FFB34D);
  stop-opacity: 0;
}

.w2ykmubdi {
  stop-color: var(--svg-color--d59a13, #D59A13);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.w84hg4m6o {
  d: path("M6.974 15.69c.144-.43.502-1.108 1.095-1.67c.585-.556 1.383-.989 2.431-.989a.5.5 0 1 0 0-1c-1.352 0-2.387.568-3.12 1.263c-.723.687-1.164 1.51-1.354 2.08a.5.5 0 0 0 .948.316");
}

.w9_b2xnds {
  stop-color: var(--svg-color--b2753d, #B2753D);
}

.xgojpzb8q {
  d: path("M7.707 18.398a1 1 0 1 0-1.414 1.414c.525.525 1.847 1.293 3.707 1.293s3.183-.768 3.707-1.293a1 1 0 1 0-1.414-1.414c-.142.142-.953.707-2.293.707s-2.15-.565-2.293-.707");
}

.xipei47ye {
  stop-color: var(--svg-color--51394c, #51394C);
}

.yl2j1rbpx {
  stop-color: var(--svg-color--ffb74e, #FFB74E);
}

.yo6_g40kf {
  stop-color: var(--svg-color--1d91e4, #1D91E4);
}

.yv_k_4zau {
  fill-rule: evenodd;
  d: path("M4.055 3.168a1 1 0 0 1 .277 1.387c-.896 1.344-2.243 4.502-.896 8.094a1 1 0 1 1-1.872.702c-1.653-4.408 0-8.25 1.104-9.906a1 1 0 0 1 1.387-.277");
}

.z3hv7yb0c {
  stop-color: var(--svg-color--502a56, #502A56);
}

.zd74ke3mf {
  stop-color: var(--svg-color--342330, #342330);
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zid5bib0z {
  stop-color: var(--svg-color--50394c, #50394C);
}

.zryx9m45y {
  d: path("M11.8 24.463a1 1 0 1 0-1.6 1.2c.69.92 2.688 2.4 5.8 2.4s5.11-1.48 5.8-2.4a1 1 0 1 0-1.6-1.2c-.31.412-1.712 1.6-4.2 1.6s-3.89-1.188-4.2-1.6");
}

.zs4j-ebbk {
  stop-color: var(--svg-color--f49f2b, #F49F2B);
}

</style>
