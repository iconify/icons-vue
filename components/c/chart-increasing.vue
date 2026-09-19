<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iO5XN5k)" class="a45xzhm6h"/><path fill="url(#iIDnu9Z)" class="a45xzhm6h"/><path fill="url(#ipHAL8c)" class="a45xzhm6h"/><path fill="url(#itzip7b)" class="a45xzhm6h"/><path fill="url(#iVQOr7c)" class="a45xzhm6h"/><path fill="url(#iTsQvJd)" class="a45xzhm6h"/><path fill="url(#iMeZnKc)" class="a45xzhm6h"/><path fill="url(#i8Dwufd)" class="a45xzhm6h"/><path fill="url(#i527Xqb)" class="a45xzhm6h"/><path fill="url(#iXUBTod)" class="a45xzhm6h"/><path fill="url(#iZIYBfb)" class="a45xzhm6h"/><path fill="url(#iZW4CFe)" class="a45xzhm6h"/><path fill="url(#iaNIhqc)" class="a45xzhm6h"/><path fill="url(#iQWdt6d)" class="a45xzhm6h"/><path fill="url(#iJ1lzWc)" class="a45xzhm6h"/><path fill="url(#irNIOPe)" class="ng6g1exia"/><path fill="url(#iEPBRIc)" class="ng6g1exia"/><path fill="url(#iCPAb1n)" clip-rule="evenodd" class="rvc99rlma"/><path fill="url(#ie6zl2b)" clip-rule="evenodd" class="rvc99rlma"/><path fill="url(#ieAYYsT)" clip-rule="evenodd" class="rvc99rlma"/><path fill="url(#iLf5ZIb)" clip-rule="evenodd" class="rvc99rlma"/><path fill="url(#iu13lPc)" clip-rule="evenodd" class="rvc99rlma"/><path fill="url(#it0g4sT)" clip-rule="evenodd" class="rvc99rlma"/><path fill="url(#i03h54c)" clip-rule="evenodd" class="rvc99rlma"/><path fill="url(#i4foOPb)" clip-rule="evenodd" class="rvc99rlma"/><path fill="url(#i0xGkSb)" class="n11pl_nkc"/><path fill="url(#icWUf2d)" class="n11pl_nkc"/><path fill="url(#iGUsolc)" class="n11pl_nkc"/><path fill="url(#iOpNkfc)" class="n11pl_nkc"/><path fill="url(#i8wLFLc)" class="ye8ntnb-m"/><path fill="url(#i7sctlc)" class="n11pl_nkc"/><path fill="url(#i6zytFe)" class="n11pl_nkc"/><path fill="url(#ic6FwTb)" class="n11pl_nkc"/><path fill="url(#ilSnrpb)" class="n11pl_nkc"/><path fill="url(#iTwjeme)" class="n11pl_nkc"/><path fill="url(#iLi7vgb)" class="n11pl_nkc"/><path fill="url(#ixXw1zc)" class="n11pl_nkc"/><defs><radialGradient id="ipHAL8c" cx="0" cy="0" r="1" gradientTransform="rotate(135.828 12.912 6.659)scale(22.2227)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="zqqjoby9b"/><stop offset=".976" class="b1kqsxs2k"/><stop offset=".992" class="yb2s_2bki"/></radialGradient><radialGradient id="iVQOr7c" cx="0" cy="0" r="1" gradientTransform="matrix(4.07344 -14.44525 8.07135 2.27605 11.73 34.59)" gradientUnits="userSpaceOnUse"><stop offset=".925" class="tx-ejek8w"/><stop offset=".992" class="u0v84ib2i"/></radialGradient><radialGradient id="iTsQvJd" cx="0" cy="0" r="1" gradientTransform="rotate(62.475 -9.395 22.708)scale(2.24303)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="q8qa88bqf"/><stop offset=".711" class="uwc9_rx1f"/><stop offset=".883" class="sopze1bhx"/><stop offset="1" class="xsmw_p9dw"/></radialGradient><radialGradient id="iMeZnKc" cx="0" cy="0" r="1" gradientTransform="rotate(131.987 1.89 12.581)scale(1.50766 3.40824)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="q8qa88bqf"/><stop offset=".711" class="uwc9_rx1f"/><stop offset=".883" class="sopze1bhx"/><stop offset="1" class="xsmw_p9dw"/></radialGradient><radialGradient id="i8Dwufd" cx="0" cy="0" r="1" gradientTransform="rotate(64.252 4.857 12.14)scale(16.3731 11.7951)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="uyh48sl0l"/><stop offset="1" class="u0v84ib2i"/></radialGradient><radialGradient id="iQWdt6d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.58858 .20883 -.81418 -21.7886 29.977 16.395)" gradientUnits="userSpaceOnUse"><stop class="x4aqjrs3p"/><stop offset="1" class="nfy4fkukk"/></radialGradient><radialGradient id="iJ1lzWc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.69009 3.2723 -3.38707 -3.81951 29.61 2.888)" gradientUnits="userSpaceOnUse"><stop class="iar3vjb-g"/><stop offset="1" class="vdus3ubud"/></radialGradient><radialGradient id="irNIOPe" cx="0" cy="0" r="1" gradientTransform="matrix(.62323 .65163 -1.98673 1.90013 9.47 19.55)" gradientUnits="userSpaceOnUse"><stop class="tri8ehb3f"/><stop offset=".677" class="l1mbf_zde"/><stop offset=".846" class="lqikt0b_t"/><stop offset="1" class="f8-7h4bpw"/></radialGradient><radialGradient id="iEPBRIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61304 .63325 -1.71478 -1.66005 12.428 19.516)" gradientUnits="userSpaceOnUse"><stop class="tri8ehb3f"/><stop offset=".677" class="l1mbf_zde"/><stop offset=".798" class="lqikt0b_t"/><stop offset="1" class="f8-7h4bpw"/></radialGradient><radialGradient id="iu13lPc" cx="0" cy="0" r="1" gradientTransform="matrix(.8321 .80437 -1.8813 1.94616 8.53 20.32)" gradientUnits="userSpaceOnUse"><stop class="op-2beb1i"/><stop offset=".783" class="l1mbf_zde"/><stop offset=".92" class="lqikt0b_t"/><stop offset="1" class="f8-7h4bpw"/></radialGradient><radialGradient id="it0g4sT" cx="0" cy="0" r="1" gradientTransform="matrix(.35639 .93553 -2.43102 .9261 10.527 18.656)" gradientUnits="userSpaceOnUse"><stop class="rw7hd_bjy"/><stop offset=".728" class="l1mbf_zde"/><stop offset=".92" class="lqikt0b_t"/><stop offset="1" class="f8-7h4bpw"/></radialGradient><radialGradient id="i03h54c" cx="0" cy="0" r="1" gradientTransform="matrix(-.41208 .8687 -2.25737 -1.07081 11.574 18.678)" gradientUnits="userSpaceOnUse"><stop class="rw7hd_bjy"/><stop offset=".728" class="l1mbf_zde"/><stop offset=".92" class="lqikt0b_t"/><stop offset="1" class="f8-7h4bpw"/></radialGradient><radialGradient id="i4foOPb" cx="0" cy="0" r="1" gradientTransform="rotate(121.862 1.204 13.98)scale(1.11326 1.9038)" gradientUnits="userSpaceOnUse"><stop class="ybhq_qdnw"/><stop offset=".849" class="l1mbf_zde"/><stop offset=".92" class="lqikt0b_t"/><stop offset="1" class="f8-7h4bpw"/></radialGradient><radialGradient id="i7sctlc" cx="0" cy="0" r="1" gradientTransform="rotate(89.876 -2.655 13.7)scale(1.45912 3.5966)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="ghwcshb9l"/><stop offset="1" class="bg7g-oboq"/></radialGradient><radialGradient id="i6zytFe" cx="0" cy="0" r="1" gradientTransform="rotate(-100.204 16.677 4.476)scale(1.85051 4.56135)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="d8gc-acal"/><stop offset="1" class="yu1y94b5c"/></radialGradient><radialGradient id="ic6FwTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.4905 1.03652 0 14.955 20.342)" gradientUnits="userSpaceOnUse"><stop class="pnb4jhc6g"/><stop offset=".526" class="loao44xaq"/><stop offset=".931" class="yv31k_btx"/></radialGradient><radialGradient id="ilSnrpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3599 -.41257 2.19949 -1.91873 16.477 19.475)" gradientUnits="userSpaceOnUse"><stop class="zr33rzn5z"/><stop offset=".308" class="loao44xaq"/><stop offset=".931" class="yv31k_btx"/></radialGradient><radialGradient id="iTwjeme" cx="0" cy="0" r="1" gradientTransform="matrix(.12513 -.48422 1.53962 .39786 14.617 20.435)" gradientUnits="userSpaceOnUse"><stop class="dhb2txbes"/><stop offset=".543" class="loao44xaq"/><stop offset=".931" class="yv31k_btx"/></radialGradient><radialGradient id="iLi7vgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23761 -.40482 1.28718 -.75552 15.711 20.337)" gradientUnits="userSpaceOnUse"><stop class="dhb2txbes"/><stop offset=".543" class="loao44xaq"/><stop offset=".931" class="yv31k_btx"/></radialGradient><radialGradient id="ixXw1zc" cx="0" cy="0" r="1" gradientTransform="matrix(4.48737 -4.42036 5.4869 5.57007 18.407 18.029)" gradientUnits="userSpaceOnUse"><stop class="s2og5zz1e"/><stop offset=".771" class="oggm7ju-d"/><stop offset="1" class="jve1ubcfp"/></radialGradient><linearGradient id="iO5XN5k" x1="27.148" x2="11.898" y1="3.875" y2="23.313" gradientUnits="userSpaceOnUse"><stop class="uyh48sl0l"/><stop offset="1" class="tx-ejek8w"/></linearGradient><linearGradient id="iIDnu9Z" x1="6.94" x2="7.888" y1="21.669" y2="22.609" gradientUnits="userSpaceOnUse"><stop offset=".075" class="xsmw_p9dw"/><stop offset=".425" class="q8qa88bqf"/><stop offset=".86" class="uwc9_rx1f"/><stop offset="1" class="xsmw_p9dw"/></linearGradient><linearGradient id="itzip7b" x1="20.972" x2="21.653" y1="16.032" y2="16.714" gradientUnits="userSpaceOnUse"><stop offset=".075" class="xsmw_p9dw"/><stop offset=".198" class="q8qa88bqf"/><stop offset=".514" class="phq-sacul"/><stop offset=".79" class="uwc9_rx1f"/><stop offset="1" class="xsmw_p9dw"/></linearGradient><linearGradient id="i527Xqb" x1="16.023" x2="16.023" y1="1.896" y2="4.36" gradientUnits="userSpaceOnUse"><stop class="z-_9w3ido"/><stop offset="1" class="elwkdipcw"/></linearGradient><linearGradient id="iXUBTod" x1="16.023" x2="16.023" y1="1.014" y2="2.565" gradientUnits="userSpaceOnUse"><stop offset=".494" class="b9oyvne2s"/><stop offset=".797" class="apw2goc_s"/><stop offset="1" class="hm6m9s-po"/></linearGradient><linearGradient id="iZIYBfb" x1="2.07" x2="6.223" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="dz_4e0b_d"/><stop offset="1" class="ugyez9b1z"/></linearGradient><linearGradient id="iZW4CFe" x1="16.023" x2="16.023" y1="30.366" y2="26.42" gradientUnits="userSpaceOnUse"><stop class="ha165cbhx"/><stop offset="1" class="cd1wm0_6r"/></linearGradient><linearGradient id="iaNIhqc" x1="21.499" x2="21.499" y1="30.216" y2="26.971" gradientUnits="userSpaceOnUse"><stop offset=".122" class="zj8kg6brj"/><stop offset="1" class="jbzt1quqs"/></linearGradient><linearGradient id="iCPAb1n" x1="16.023" x2="16.023" y1="4.359" y2="29.953" gradientUnits="userSpaceOnUse"><stop class="av2-vqbow"/><stop offset="1" class="ny3yfgb0o"/></linearGradient><linearGradient id="ie6zl2b" x1="21.742" x2="21.742" y1="30.668" y2="27.187" gradientUnits="userSpaceOnUse"><stop class="h8su5dx7m"/><stop offset="1" class="nklmu6d-u"/></linearGradient><linearGradient id="ieAYYsT" x1="1.102" x2="6.414" y1="17.359" y2="17.359" gradientUnits="userSpaceOnUse"><stop class="lfsn49ywy"/><stop offset="1" class="c27919bru"/></linearGradient><linearGradient id="iLf5ZIb" x1="30.789" x2="26.977" y1="18.047" y2="18.047" gradientUnits="userSpaceOnUse"><stop class="vsb_wlbyi"/><stop offset="1" class="bnoc2wb_b"/></linearGradient><linearGradient id="i0xGkSb" x1="27.664" x2="4.102" y1="13.422" y2="23.172" gradientUnits="userSpaceOnUse"><stop class="rrjte8pka"/><stop offset="1" class="u9-wqrbfu"/></linearGradient><linearGradient id="icWUf2d" x1="23.205" x2="21.666" y1="14.255" y2="12.682" gradientUnits="userSpaceOnUse"><stop class="twng9ubfm"/><stop offset=".201" class="d4ngt6erw"/><stop offset=".346" class="lz9er8egf"/><stop offset=".42" class="wba28c0op"/><stop offset=".526" class="tw6t-hb8u"/><stop offset=".562" class="tw6t-hb8u"/><stop offset=".687" class="fxsjo5bks"/><stop offset=".931" class="twng9ubfm"/></linearGradient><linearGradient id="iGUsolc" x1="7.45" x2="9.025" y1="19.566" y2="21.212" gradientUnits="userSpaceOnUse"><stop class="ron2w4gef"/><stop offset=".344" class="y-r3pwbri"/><stop offset=".406" class="jbpdf5bji"/><stop offset=".484" class="gr3xp5iyr"/><stop offset=".741" class="ron2w4gef"/></linearGradient><linearGradient id="iOpNkfc" x1="14.226" x2="12.032" y1="18.138" y2="20.331" gradientUnits="userSpaceOnUse"><stop class="fj8syabjc"/><stop offset=".311" class="pquivpbkn"/><stop offset=".386" class="n-1s8dc_d"/><stop offset=".437" class="n-1s8dc_d"/><stop offset=".517" class="i2j1w7dya"/><stop offset=".741" class="fj8syabjc"/></linearGradient><linearGradient id="i8wLFLc" x1="9.558" x2="3.515" y1="18.922" y2="24.154" gradientUnits="userSpaceOnUse"><stop class="teyi3ntqi"/><stop offset="0" class="prn_s_6ik"/><stop offset="1" class="qc2y5o0ny"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chart-increasing" /></template>
<style>
.a45xzhm6h {
  d: path("M2.07 5.847a3.8 3.8 0 0 1 3.8-3.8h20.307a3.8 3.8 0 0 1 3.8 3.8v20.306a3.8 3.8 0 0 1-3.8 3.8H5.87a3.8 3.8 0 0 1-3.8-3.8z");
}

.apw2goc_s {
  stop-color: var(--svg-color--bababa, #BABABA);
  stop-opacity: 0.267;
}

.av2-vqbow {
  stop-color: var(--svg-color--c2bec6, #C2BEC6);
}

.b1kqsxs2k {
  stop-color: var(--svg-color--d7cde1, #D7CDE1);
  stop-opacity: 0.458;
}

.b9oyvne2s {
  stop-color: var(--svg-color--bababa, #BABABA);
}

.bg7g-oboq {
  stop-color: var(--svg-color--4799d3, #4799D3);
  stop-opacity: 0;
}

.bnoc2wb_b {
  stop-color: var(--svg-color--d6d1da, #D6D1DA);
  stop-opacity: 0;
}

.c27919bru {
  stop-color: var(--svg-color--96909c, #96909C);
  stop-opacity: 0;
}

.cd1wm0_6r {
  stop-color: var(--svg-color--b9b2bf, #B9B2BF);
  stop-opacity: 0;
}

.d4ngt6erw {
  stop-color: var(--svg-color--34a3e8, #34A3E8);
  stop-opacity: 0.218;
}

.d8gc-acal {
  stop-color: var(--svg-color--2f6fce, #2F6FCE);
}

.dhb2txbes {
  stop-color: var(--svg-color--5bb3f7, #5BB3F7);
  stop-opacity: 0.61;
}

.dz_4e0b_d {
  stop-color: var(--svg-color--a9a2b0, #A9A2B0);
}

.elwkdipcw {
  stop-color: var(--svg-color--e0dfe2, #E0DFE2);
  stop-opacity: 0;
}

.f8-7h4bpw {
  stop-color: var(--svg-color--814f7c, #814F7C);
  stop-opacity: 0;
}

.fj8syabjc {
  stop-color: var(--svg-color--55adf0, #55ADF0);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxsjo5bks {
  stop-color: var(--svg-color--34a3e8, #34A3E8);
  stop-opacity: 0.281;
}

.ghwcshb9l {
  stop-color: var(--svg-color--4799d3, #4799D3);
}

.gr3xp5iyr {
  stop-color: var(--svg-color--4498e7, #4498E7);
  stop-opacity: 0.867;
}

.h8su5dx7m {
  stop-color: var(--svg-color--9e83b7, #9E83B7);
}

.ha165cbhx {
  stop-color: var(--svg-color--b9b2bf, #B9B2BF);
}

.hm6m9s-po {
  stop-color: var(--svg-color--bababa, #BABABA);
  stop-opacity: 0;
}

.i2j1w7dya {
  stop-color: var(--svg-color--55adf0, #55ADF0);
  stop-opacity: 0.867;
}

.iar3vjb-g {
  stop-color: var(--svg-color--f7f4f7, #F7F4F7);
}

.jbpdf5bji {
  stop-color: var(--svg-color--4498e7, #4498E7);
}

.jbzt1quqs {
  stop-color: var(--svg-color--cdbce0, #CDBCE0);
  stop-opacity: 0;
}

.jve1ubcfp {
  stop-color: var(--svg-color--2c89d4, #2C89D4);
  stop-opacity: 0;
}

.l1mbf_zde {
  stop-color: var(--svg-color--814f7c, #814F7C);
  stop-opacity: 0.091;
}

.lfsn49ywy {
  stop-color: var(--svg-color--96909c, #96909C);
}

.loao44xaq {
  stop-color: var(--svg-color--5bb3f7, #5BB3F7);
  stop-opacity: 0.27;
}

.lqikt0b_t {
  stop-color: var(--svg-color--814f7c, #814F7C);
  stop-opacity: 0.024;
}

.lz9er8egf {
  stop-color: var(--svg-color--34a3e8, #34A3E8);
  stop-opacity: 0.763;
}

.n-1s8dc_d {
  stop-color: var(--svg-color--5ab3f6, #5AB3F6);
}

.n11pl_nkc {
  d: path("M2.235 27.265a3.8 3.8 0 0 1-.165-1.112v-1.552l7.083-7.083a2.5 2.5 0 0 1 3.497-.038l1.927 1.845a.5.5 0 0 0 .7-.007L29.825 4.783q.148.507.15 1.064v1.612L16.69 20.733a2.5 2.5 0 0 1-3.496.037l-1.927-1.845a.5.5 0 0 0-.7.007z");
}

.nfy4fkukk {
  stop-color: var(--svg-color--ded3e7, #DED3E7);
  stop-opacity: 0;
}

.ng6g1exia {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M2.07 5.847a3.8 3.8 0 0 1 3.8-3.8h20.307a3.8 3.8 0 0 1 3.8 3.8v20.306a3.8 3.8 0 0 1-3.8 3.8H5.87a3.8 3.8 0 0 1-3.8-3.8z");
}

.nklmu6d-u {
  stop-color: var(--svg-color--9e83b7, #9E83B7);
  stop-opacity: 0;
}

.ny3yfgb0o {
  stop-color: var(--svg-color--baacc6, #BAACC6);
}

.oggm7ju-d {
  stop-color: var(--svg-color--2c89d4, #2C89D4);
  stop-opacity: 0.179;
}

.op-2beb1i {
  stop-color: var(--svg-color--814f7c, #814F7C);
  stop-opacity: 0.71;
}

.phq-sacul {
  stop-color: var(--svg-color--b19aa4, #B19AA4);
  stop-opacity: 0.405;
}

.pnb4jhc6g {
  stop-color: var(--svg-color--5bb3f7, #5BB3F7);
}

.pquivpbkn {
  stop-color: var(--svg-color--55adf0, #55ADF0);
  stop-opacity: 0.906;
}

.prn_s_6ik {
  stop-color: var(--svg-color--2c7dc5, #2C7DC5);
  stop-opacity: 0;
}

.q8qa88bqf {
  stop-color: var(--svg-color--b19aa4, #B19AA4);
}

.qc2y5o0ny {
  stop-color: var(--svg-color--2c7dc5, #2C7DC5);
}

.ron2w4gef {
  stop-color: var(--svg-color--4498e7, #4498E7);
  stop-opacity: 0;
}

.rrjte8pka {
  stop-color: var(--svg-color--3191d1, #3191D1);
}

.rvc99rlma {
  fill-rule: evenodd;
  d: path("M11.547 2.047h-1v8.39H2.07v1h8.477v8.97H2.07v1h8.477v8.546h1v-8.547h9v8.547h1v-8.547h8.43v-1h-8.43v-8.968h8.43v-1h-8.43V2.047h-1v8.39h-9zm9 9.39v8.97h-9v-8.97z");
}

.rw7hd_bjy {
  stop-color: var(--svg-color--814f7c, #814F7C);
  stop-opacity: 0.67;
}

.s2og5zz1e {
  stop-color: var(--svg-color--2c89d4, #2C89D4);
  stop-opacity: 0.89;
}

.sopze1bhx {
  stop-color: var(--svg-color--b19aa4, #B19AA4);
  stop-opacity: 0.032;
}

.teyi3ntqi {
  stop-color: var(--svg-color--da267d, #DA267D);
  stop-opacity: 0;
}

.tri8ehb3f {
  stop-color: var(--svg-color--814f7c, #814F7C);
  stop-opacity: 0.43;
}

.tw6t-hb8u {
  stop-color: var(--svg-color--34a3e8, #34A3E8);
  stop-opacity: 0.788;
}

.twng9ubfm {
  stop-color: var(--svg-color--34a3e8, #34A3E8);
  stop-opacity: 0;
}

.tx-ejek8w {
  stop-color: var(--svg-color--d5c9e3, #D5C9E3);
}

.u0v84ib2i {
  stop-color: var(--svg-color--d5c9e3, #D5C9E3);
  stop-opacity: 0;
}

.u9-wqrbfu {
  stop-color: var(--svg-color--4182bd, #4182BD);
}

.ugyez9b1z {
  stop-color: var(--svg-color--dad3e2, #DAD3E2);
  stop-opacity: 0;
}

.uwc9_rx1f {
  stop-color: var(--svg-color--b19aa4, #B19AA4);
  stop-opacity: 0.141;
}

.uyh48sl0l {
  stop-color: var(--svg-color--d8d1e0, #D8D1E0);
}

.vdus3ubud {
  stop-color: var(--svg-color--e2dce5, #E2DCE5);
  stop-opacity: 0;
}

.vsb_wlbyi {
  stop-color: var(--svg-color--d6d1da, #D6D1DA);
}

.wba28c0op {
  stop-color: var(--svg-color--34a3e8, #34A3E8);
}

.x4aqjrs3p {
  stop-color: var(--svg-color--f2edf5, #F2EDF5);
}

.xsmw_p9dw {
  stop-color: var(--svg-color--b19aa4, #B19AA4);
  stop-opacity: 0;
}

.y-r3pwbri {
  stop-color: var(--svg-color--4498e7, #4498E7);
  stop-opacity: 0.906;
}

.yb2s_2bki {
  stop-color: var(--svg-color--d7cde1, #D7CDE1);
  stop-opacity: 0;
}

.ybhq_qdnw {
  stop-color: var(--svg-color--814f7c, #814F7C);
  stop-opacity: 0.8;
}

.ye8ntnb-m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.235 27.265a3.8 3.8 0 0 1-.165-1.112v-1.552l7.083-7.083a2.5 2.5 0 0 1 3.497-.038l1.927 1.845a.5.5 0 0 0 .7-.007L29.825 4.783q.148.507.15 1.064v1.612L16.69 20.733a2.5 2.5 0 0 1-3.496.037l-1.927-1.845a.5.5 0 0 0-.7.007z");
}

.yu1y94b5c {
  stop-color: var(--svg-color--2f6fce, #2F6FCE);
  stop-opacity: 0;
}

.yv31k_btx {
  stop-color: var(--svg-color--5bb3f7, #5BB3F7);
  stop-opacity: 0;
}

.z-_9w3ido {
  stop-color: var(--svg-color--e0dfe2, #E0DFE2);
}

.zj8kg6brj {
  stop-color: var(--svg-color--a88ac4, #A88AC4);
}

.zqqjoby9b {
  stop-color: var(--svg-color--d7cde1, #D7CDE1);
}

.zr33rzn5z {
  stop-color: var(--svg-color--5bb3f7, #5BB3F7);
  stop-opacity: 0.5;
}

</style>
