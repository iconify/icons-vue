<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dxkbkwbsa"/><path class="ta235obem"/><path class="ew5-hzb7p"/><path class="j6xh-wbbl"/><path class="o64lodh6y"/><path class="ovnr52bhr"/><path class="y4087xbms"/><path class="iifzr8gdx"/><path class="au2xmgbes"/><path class="jzo6ay7hd"/><path class="jpjwk02wy"/><path class="fs5wsncqs"/><path class="x0dwd-9bi"/><path class="jtvcqfbgb"/><path class="nldma369v"/><path class="qxwfgoq1j"/><path class="r7y5tmbdi"/><path class="r74s3-bjk"/><path class="suxcgdbve"/><path class="qu9zn_xgn"/><path class="h08_-ccbj"/><path class="ngq3w9w_p"/><path class="cmhil1bab"/><path class="sk1q7h9nw"/><path class="r6a6-7b2q"/><path class="swviciyob"/><path class="u_fospbfa"/><path class="kb2olhbsv"/><path class="hcgv30ljq"/><path class="mp9a_dk5l"/><path class="jnm2wnbds"/><path class="b8ma45b_x"/><path class="dqqku8bat"/><path class="zf3b9etdk"/><path class="v4md3vcey"/><path class="pve3v2btl"/><path class="tou63vbhq"/><path class="twbugrbxt"/><path class="labxtcb_b"/><path class="kp_8sfbcf"/><path class="jwict6bbh"/><path class="obkhgebke"/><path class="ksujwtbvf"/><path class="o2wqtub1g"/><path class="llf-qbclr"/><path class="jz2oj12ie"/><path class="bgygfw4zg"/><path class="u203bvb1e"/><path class="t4l4z3bxy"/><path class="wz39kgb2g"/><path class="qn6axib_p"/><path class="dzl18ccol"/><path class="s_shsvy-m"/><path class="l2k9m9hne"/><path class="y-akubc7x"/><path class="fdj4r10oq"/><path class="zlow1tc6u"/><path class="mz84niyfv"/><path class="i4lgfb7sy"/><path class="vt02zqfnn"/><path class="zezxguy1f"/><path class="seikwzbvq"/><path class="g-omcjb1r"/><path class="j47e7vbxn"/><path class="f4nc7s2ao"/><path class="s2fdezl-d"/><path class="lbounfbed"/><path class="g0ghmebko"/><path class="vglev63rh"/><path class="yyryvunzs"/><path class="pw1_-ccts"/><path class="t-93jr2mo"/><path class="vtn8gwbmk"/><path class="ric2gzt4u"/><path class="xrhxq-h0a"/><path class="cguq1rq-g"/><path class="en605g-mw"/><path class="htkkv5k3i"/><path class="x3at3ge3p"/><path class="n2lf9dbpf"/><path class="wf7183b4p"/><path class="t9qngz6kb"/><path class="g2wfw3bxk"/><path class="d1yt88bxd"/><path class="l5ph9-bov"/><path class="kddrcpnrq"/><path class="a5wbkvkey"/><path class="rq0bz6b6u"/><path class="gjayoxb7z"/><path class="sqwx2xb2i"/><path class="jrazrm0bx"/><path class="h8-p3ybue"/><path class="igioiobgx"/><path class="xi5rm6bzu"/><path class="bbxaueb_y"/><path class="ztgrh2bmb"/><path class="mb_cq7bya"/><path class="i_r1xac0x"/><path class="epcxkkb8a"/><path class="ito_babts"/><path class="n385y2gvr"/><path class="w54340bzx"/><path class="br-aitpay"/><path class="johsztb3a"/><path class="zxqf97bzw"/><path class="w6ydv626s"/><path class="ijdf1x3by"/><path class="a5hagfx6y"/><path class="jhwv6kbsa"/><path class="ka1cz_ulv"/><path class="oefvsxb_i"/><path class="ol-xhbbvd"/><path class="mz85_nbwo"/><path class="jfcjbjk3d"/><path class="bh55od7hg"/><path class="s71x_ybio"/><path class="ctk5pgaxl"/><path class="qij1aya4l"/><path class="m_j0v_j_r"/><path class="zkrjszb_o"/><path class="hiywg4b9l"/><path class="hcil2_91y"/><path class="bk40u0hux"/><path class="vrrqu0ttt"/><path class="kenfz7baa"/><path class="g9jsm514s"/><path class="qegc3qb1n"/><path class="nz4xx9qss"/><path class="khbn5gbdf"/><path class="v1nb3z7ao"/><path class="g11c40bxn"/><path class="mbh18kb6k"/><path class="uyjv3ob5n"/><path class="g4p0slb2u"/><path class="imnqplbmj"/><path class="b04dvob3h"/><path class="f0fi4ml8e"/><path class="n7e7sebce"/><path class="j_90fpbus"/><path class="gqncf1byz"/><path class="d3bnlzw2q"/><path class="j--yclbgr"/><path class="d0zu_ubow"/><path class="e93wc5v8n"/><path class="g2mhuibed"/><path class="tflvq53xw"/><path class="sv7nv4bhx"/><path class="f71sjl0_c"/><path class="ndk--5biw"/><path class="u8a1ajbbu"/><path class="bmh-u1biv"/><path class="b7nnn-bcf"/><path class="pr7w89boq"/><path class="swwbmhb1y"/><path class="q9ykfxb0t"/><path class="io76gybhy"/><path class="wzvng7bjo"/><path class="vwq54irsn"/><path class="ydukktb7u"/><path class="ysfa3tmjg"/><path class="y9110rgvc"/><path class="jt6bs-dad"/><path class="yewmk-ori"/><path class="yirggobog"/><path class="l4-cc5bfj"/><path class="mrjmwcc_s"/><path class="o4hbaf17k"/><path class="d-kzztbte"/><path class="noj6tqmha"/><path class="iz0mubcgw"/><path class="ozwfo_hyj"/><path class="q47ko4yaf"/><path class="s30873vsr"/><path class="gjf7hdn5x"/><path class="qlyai4blt"/><path class="dkfpy9bgd"/><path class="akamp3v1w"/><path class="c1705d1of"/><path class="m3_2rdvub"/><path class="ilfgmgbtb"/><path class="tgz-u5bng"/><path class="vo9vg7sui"/><path class="i__xq_bdt"/><path class="i73n_bvyl"/><path class="j4z7iccpj"/><path class="mog5np96u"/><path class="riddgxbsv"/><path class="bkh4wmbey"/><path class="lgltfibwl"/><path class="qgyynh75f"/><path class="abpwmolvl"/><path class="nx94frvua"/><path class="lqv42abke"/><path class="fyzo7njbz"/><path class="dsg-z5bae"/><path class="vmg-12rpy"/><path class="l11a-0q7r"/><path class="ua_wvvbyx"/><path class="ca2vs_mag"/><path class="t2ms3eb3u"/><path class="jw-5nacrt"/><path class="b4xt7c-sr"/><path class="wgnam4biw"/><path class="v4s-sebxe"/><path class="yok9crkjg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:canton-background" /></template>
<style>
.a5hagfx6y {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.124 10.608l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.a5wbkvkey {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.517 7.763L9.524 9.77l-2.007 2.008l-2.01-2.008zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.abpwmolvl {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.354 15.274l2.007 2.007l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.akamp3v1w {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.583 15.811l2.008 2.01l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.au2xmgbes {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.278 5.283l2.007 2.007l-2.008 2.007L14.27 7.29zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.b04dvob3h {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.705 14.023L6.646 16.08l2.059 2.06l2.059-2.06z");
}

.b4xt7c-sr {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.707 14.289l-2.059 2.059l2.06 2.058l2.058-2.058z");
}

.b7nnn-bcf {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.493 15.3l-2.06 2.06l2.06 2.059l2.059-2.06z");
}

.b8ma45b_x {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.32 4.092l-2.058 2.06L13.32 8.21l2.06-2.059z");
}

.bbxaueb_y {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.207 8.795l2.007 2.007l-2.007 2.01l-2.007-2.01zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.bgygfw4zg {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.494 4.285l2.008 2.007L11.494 8.3L9.487 6.292zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.bh55od7hg {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.266 11.451l2.008 2.007l-2.008 2.008l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.bk40u0hux {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.623 12.47l2.007 2.008l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.bkh4wmbey {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.11 15.337l-2.059 2.059l2.06 2.059l2.058-2.059z");
}

.bmh-u1biv {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.249 15.233l2.01 2.01l-2.008 2.007l-2.01-2.008zm0-.1l-2.108 2.11l2.11 2.11l2.11-2.11z");
}

.br-aitpay {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.11 9.858l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.1L5 11.868l2.11 2.11l2.11-2.11z");
}

.c1705d1of {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.843 15.721l-2.059 2.06l2.06 2.058l2.058-2.059z");
}

.ca2vs_mag {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.278 14.7l2.007 2.007l-2.008 2.01l-2.007-2.007zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.cguq1rq-g {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.171 6.51L6.113 8.57l2.058 2.058l2.06-2.059z");
}

.cmhil1bab {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.611 4.406l2.008 2.007L14.61 8.42l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.109l2.11-2.11z");
}

.ctk5pgaxl {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.337 11.711l2.007 2.008l-2.007 2.01L5.33 13.72zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.d-kzztbte {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.535 15.804l-2.059 2.058l2.059 2.06l2.059-2.06z");
}

.d0zu_ubow {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.332 14.642l2.007 2.008l-2.007 2.01l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.d1yt88bxd {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.622 7.461l-2.058 2.06l2.058 2.058l2.06-2.059z");
}

.d3bnlzw2q {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.117 14.466l2.007 2.008l-2.007 2.007l-2.007-2.007zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.dkfpy9bgd {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.584 15.762l-2.06 2.059l2.06 2.059l2.058-2.06z");
}

.dqqku8bat {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.321 4.143l2.007 2.007l-2.007 2.01l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.dsg-z5bae {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.826 15.011l2.007 2.007l-2.007 2.008l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.dxkbkwbsa {
  fill: var(--svg-color--1b1b1b, #1b1b1b);
  d: path("M24 0H0v24h24z");
}

.dzl18ccol {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.738 4.476l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.e93wc5v8n {
  fill: var(--svg-color--030206, #030206);
  d: path("m9.552 14.76l-2.059 2.059l2.06 2.058l2.058-2.058z");
}

.en605g-mw {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.171 6.56l2.008 2.008l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.epcxkkb8a {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.125 9.323l2.007 2.007l-2.007 2.007l-2.008-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.ew5-hzb7p {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.89 5.842l2.007 2.007l-2.007 2.008l-2.007-2.008zm0-.103l-2.11 2.11l2.11 2.11L19 7.85z");
}

.f0fi4ml8e {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.706 14.074l2.007 2.007l-2.007 2.01l-2.008-2.008zm0-.1l-2.11 2.11l2.11 2.109l2.11-2.11z");
}

.f4nc7s2ao {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.332 5.34l2.007 2.008l-2.007 2.01L7.325 7.35zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.f71sjl0_c {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.012 15.053l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.fdj4r10oq {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.249 4.7l-2.06 2.058l2.06 2.06l2.059-2.06z");
}

.fs5wsncqs {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.825 4.92l-2.059 2.06l2.06 2.058l2.058-2.059z");
}

.ft5dv1b6b {
  fill: none;
}

.fyzo7njbz {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.827 14.961l-2.06 2.06l2.06 2.058l2.059-2.059z");
}

.g-omcjb1r {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.552 5.174l2.007 2.008l-2.007 2.007l-2.008-2.007zm0-.102l-2.108 2.11l2.11 2.11l2.11-2.11z");
}

.g0ghmebko {
  fill: var(--svg-color--030206, #030206);
  d: path("m8.907 5.658l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.g11c40bxn {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.171 13.423l2.008 2.007l-2.008 2.01l-2.007-2.008zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.g2mhuibed {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.552 14.809l2.007 2.007l-2.007 2.007l-2.008-2.007zm0-.1l-2.108 2.11l2.11 2.109l2.11-2.11z");
}

.g2wfw3bxk {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.741 7.267L9.75 9.274L7.74 11.28L5.734 9.274zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.g4p0slb2u {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.516 13.812L6.457 15.87l2.059 2.06l2.059-2.06z");
}

.g9jsm514s {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.873 12.906l-2.059 2.059l2.06 2.058l2.058-2.058z");
}

.gjayoxb7z {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.422 8.016l2.008 2.007l-2.008 2.008l-2.01-2.008zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.gjf7hdn5x {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.322 15.791l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.gqncf1byz {
  fill: var(--svg-color--030206, #030206);
  d: path("m9.116 14.414l-2.059 2.059l2.06 2.059l2.058-2.059z");
}

.h08_-ccbj {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.862 4.495l2.007 2.007l-2.007 2.01l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.h8-p3ybue {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.266 8.48l-2.06 2.06l2.06 2.059l2.059-2.06z");
}

.hcgv30ljq {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.843 4.213l2.008 2.007l-2.008 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.hcil2_91y {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.624 12.421l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.hiywg4b9l {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.517 12.222l2.007 2.008l-2.007 2.007l-2.01-2.007zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.htkkv5k3i {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.015 6.74L5.956 8.8l2.06 2.059l2.058-2.06z");
}

.i__xq_bdt {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.359 15.655l2.007 2.007l-2.008 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.i_r1xac0x {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.125 9.273l-2.06 2.059l2.06 2.058l2.059-2.058z");
}

.i4lgfb7sy {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.013 4.878l2.007 2.007l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.i73n_bvyl {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.61 15.526l-2.058 2.059l2.058 2.059l2.06-2.059z");
}

.igioiobgx {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.266 8.532l2.008 2.007l-2.008 2.008l-2.007-2.008zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.iifzr8gdx {
  fill: var(--svg-color--030206, #030206);
  d: path("M16.278 5.234L14.22 7.293l2.06 2.059l2.058-2.06z");
}

.ijdf1x3by {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.11 10.393L9.117 12.4L7.11 14.407L5.103 12.4zm0-.1L5 12.403l2.11 2.11l2.11-2.11z");
}

.ilfgmgbtb {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.1 15.669l-2.058 2.059l2.059 2.058l2.059-2.058z");
}

.imnqplbmj {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.517 13.864l2.007 2.007l-2.007 2.007l-2.008-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.io76gybhy {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.987 15.5l-2.06 2.059l2.06 2.059l2.059-2.06z");
}

.ito_babts {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.101 9.54l-2.058 2.059L7.1 13.658l2.06-2.06z");
}

.iz0mubcgw {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.797 15.811l-2.06 2.059l2.06 2.059l2.059-2.06z");
}

.j_90fpbus {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.906 14.276l2.008 2.007l-2.008 2.01L6.9 16.286zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.j--yclbgr {
  fill: var(--svg-color--030206, #030206);
  d: path("m9.332 14.592l-2.06 2.06l2.06 2.058l2.059-2.059z");
}

.j47e7vbxn {
  fill: var(--svg-color--030206, #030206);
  d: path("M9.331 5.289L7.272 7.347l2.06 2.06l2.058-2.06z");
}

.j4z7iccpj {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.611 15.578l2.008 2.007l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.107l2.11 2.11l2.11-2.11z");
}

.j6xh-wbbl {
  fill: var(--svg-color--030206, #030206);
  d: path("M16.707 5.592L14.648 7.65l2.06 2.059l2.058-2.06z");
}

.jfcjbjk3d {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.267 11.402L5.208 13.46l2.059 2.059l2.059-2.06z");
}

.jhwv6kbsa {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.125 10.66l2.007 2.008l-2.007 2.007l-2.008-2.007zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.jnm2wnbds {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.583 4.172l2.008 2.007l-2.008 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.johsztb3a {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.09 10.075l-2.06 2.059l2.06 2.059l2.058-2.059z");
}

.jpjwk02wy {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.055 5.121l2.008 2.008l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.jrazrm0bx {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.337 8.272l2.007 2.007l-2.007 2.007L5.33 10.28zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.jt6bs-dad {
  fill: var(--svg-color--030206, #030206);
  d: path("m11.752 15.705l-2.06 2.06l2.06 2.058l2.058-2.059z");
}

.jtvcqfbgb {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.591 4.783l-2.059 2.059l2.06 2.059l2.058-2.06z");
}

.jw-5nacrt {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.495 14.527l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.jwict6bbh {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.274 4.15l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.jz2oj12ie {
  fill: var(--svg-color--030206, #030206);
  d: path("m11.494 4.234l-2.059 2.06l2.06 2.058l2.058-2.059z");
}

.jzo6ay7hd {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.056 5.072l-2.06 2.058l2.06 2.06l2.059-2.06z");
}

.ka1cz_ulv {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.16 10.874L5.1 12.933l2.06 2.059l2.058-2.06z");
}

.kb2olhbsv {
  fill: var(--svg-color--030206, #030206);
  d: path("M13.843 4.161L11.784 6.22l2.06 2.059l2.058-2.06z");
}

.kddrcpnrq {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.517 7.711l-2.06 2.06l2.06 2.058L9.576 9.77z");
}

.kenfz7baa {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.741 12.716l2.008 2.008L7.74 16.73l-2.007-2.007zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.khbn5gbdf {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.016 13.191l2.007 2.007l-2.007 2.008l-2.008-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.kp_8sfbcf {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.274 4.1l-2.059 2.06l2.06 2.059l2.058-2.059z");
}

.ksujwtbvf {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.012 4.184l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.l11a-0q7r {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.055 14.862l2.008 2.007l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.l2k9m9hne {
  fill: var(--svg-color--030206, #030206);
  d: path("M10.491 4.58L8.432 6.64l2.06 2.058L12.55 6.64z");
}

.l4-cc5bfj {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.012 15.8l2.007 2.006l-2.007 2.008l-2.007-2.008zm0-.1l-2.11 2.109l2.11 2.11l2.11-2.11z");
}

.l5ph9-bov {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.623 7.512L9.63 9.52l-2.007 2.007L5.616 9.52zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.labxtcb_b {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.534 4.13l2.007 2.008l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.lbounfbed {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.117 5.52l2.007 2.006l-2.007 2.008L7.11 7.526zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.lgltfibwl {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.11 15.387l2.007 2.007l-2.007 2.008l-2.007-2.008zm0-.1L13 17.397l2.11 2.11l2.11-2.11z");
}

.llf-qbclr {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.752 4.227l2.007 2.007l-2.007 2.008l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.lqv42abke {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.592 15.148l2.007 2.008l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.m_j0v_j_r {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.422 11.967l2.008 2.007l-2.008 2.007l-2.01-2.004zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.m3_2rdvub {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.843 15.773l2.008 2.007l-2.008 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.mb_cq7bya {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.16 9.058l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.109l2.11-2.11z");
}

.mbh18kb6k {
  fill: var(--svg-color--030206, #030206);
  d: path("m8.337 13.595l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.mog5np96u {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.863 15.439l-2.06 2.059l2.06 2.059l2.058-2.06z");
}

.mp9a_dk5l {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.583 4.12l-2.059 2.06l2.059 2.059l2.059-2.059z");
}

.mrjmwcc_s {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.273 15.781l-2.059 2.059l2.06 2.059l2.058-2.06z");
}

.mz84niyfv {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.013 4.828l-2.06 2.06l2.06 2.058l2.059-2.059z");
}

.mz85_nbwo {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.207 11.188l2.007 2.007l-2.007 2.008L5.2 13.198zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.n2lf9dbpf {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.874 6.976l-2.06 2.059l2.06 2.059l2.059-2.06z");
}

.n385y2gvr {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.11 9.59l2.007 2.007l-2.007 2.01L5.103 11.6zm0-.1L5 11.6l2.11 2.11l2.11-2.11z");
}

.n7e7sebce {
  fill: var(--svg-color--030206, #030206);
  d: path("m8.906 14.225l-2.059 2.059l2.06 2.059l2.058-2.059z");
}

.ndk--5biw {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.013 15.105l2.007 2.007l-2.008 2.008l-2.007-2.008zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.ngq3w9w_p {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.612 4.356l-2.059 2.059l2.06 2.059l2.058-2.06z");
}

.nldma369v {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M15.592 4.834L17.6 6.842l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.noj6tqmha {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.534 15.852l2.007 2.008l-2.007 2.007l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.nx94frvua {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.592 15.099l-2.059 2.058l2.06 2.06l2.058-2.06z");
}

.nz4xx9qss {
  fill: var(--svg-color--030206, #030206);
  d: path("m8.016 13.142l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.o2wqtub1g {
  fill: var(--svg-color--030206, #030206);
  d: path("m11.753 4.178l-2.06 2.06l2.06 2.058l2.059-2.059z");
}

.o4hbaf17k {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.274 15.833l2.007 2.007l-2.007 2.01l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.o64lodh6y {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.708 5.644l2.007 2.008l-2.007 2.007L14.7 7.652zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.obkhgebke {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.012 4.133l-2.06 2.059l2.06 2.059l2.058-2.06z");
}

.oefvsxb_i {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.16 10.926l2.007 2.007L7.16 14.94l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.ol-xhbbvd {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.207 11.139l-2.059 2.059l2.06 2.059l2.058-2.06z");
}

.ovnr52bhr {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.495 5.408l-2.059 2.059l2.06 2.058l2.058-2.058z");
}

.ozwfo_hyj {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.796 15.88l2.008 2.008l-2.008 2.007l-2.007-2.005zm0-.1l-2.107 2.11l2.11 2.11l2.107-2.11z");
}

.pr7w89boq {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.492 15.351l2.007 2.007l-2.007 2.01l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.pve3v2btl {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.797 4.073l-2.06 2.059l2.06 2.059l2.058-2.06z");
}

.pw1_-ccts {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.706 5.91l2.007 2.007l-2.007 2.007l-2.008-2.007zm0-.1l-2.11 2.11l2.11 2.109l2.11-2.11z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q47ko4yaf {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.06 15.805l-2.059 2.059l2.06 2.059l2.058-2.06z");
}

.q9ykfxb0t {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.738 15.457l2.007 2.007l-2.007 2.008l-2.007-2.008zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.qegc3qb1n {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.874 12.958l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.qgyynh75f {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.354 15.224l-2.06 2.059l2.06 2.059l2.059-2.06z");
}

.qij1aya4l {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.422 11.917l-2.059 2.059l2.06 2.058l2.058-2.058z");
}

.qlyai4blt {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.321 15.84l2.007 2.008l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.qn6axib_p {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.986 4.434l2.007 2.008l-2.007 2.01L8.98 6.443zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.qu9zn_xgn {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.861 4.443l-2.059 2.06l2.06 2.058l2.058-2.059z");
}

.qxwfgoq1j {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.352 4.657l-2.059 2.06l2.06 2.058l2.058-2.059z");
}

.r6a6-7b2q {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.359 4.329l2.007 2.007l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.109l2.11-2.11z");
}

.r74s3-bjk {
  fill: var(--svg-color--030206, #030206);
  d: path("M15.109 4.544L13.05 6.603l2.059 2.059l2.059-2.059z");
}

.r7y5tmbdi {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.354 4.71l2.007 2.006l-2.008 2.008l-2.007-2.008zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.ric2gzt4u {
  fill: var(--svg-color--030206, #030206);
  d: path("m8.337 6.287l-2.059 2.06l2.059 2.058l2.059-2.059z");
}

.riddgxbsv {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.862 15.488l2.007 2.008l-2.007 2.01l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.rq0bz6b6u {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.422 7.964l-2.06 2.059l2.06 2.059l2.059-2.06z");
}

.s_shsvy-m {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.738 4.526l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.s2fdezl-d {
  fill: var(--svg-color--030206, #030206);
  d: path("m9.117 5.467l-2.06 2.059l2.06 2.059l2.058-2.06z");
}

.s30873vsr {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.061 15.857l2.007 2.007l-2.007 2.01l-2.007-2.007zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.s71x_ybio {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.337 11.66l-2.06 2.06l2.06 2.058l2.059-2.059z");
}

.seikwzbvq {
  fill: var(--svg-color--030206, #030206);
  d: path("M9.551 5.124L7.492 7.183l2.06 2.059l2.058-2.06z");
}

.sk1q7h9nw {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.359 4.278l-2.06 2.06l2.06 2.058l2.059-2.059z");
}

.sqwx2xb2i {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.338 8.223L5.28 10.282l2.06 2.059l2.058-2.06z");
}

.suxcgdbve {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.11 4.596l2.007 2.007L15.11 8.61l-2.007-2.007zm0-.1L13 6.606l2.11 2.11l2.11-2.11z");
}

.sv7nv4bhx {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.78 14.963l2.008 2.007l-2.007 2.01l-2.007-2.008zm0-.1l-2.109 2.11l2.11 2.11l2.11-2.11z");
}

.swviciyob {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.101 4.214l-2.059 2.06l2.06 2.058l2.058-2.059z");
}

.swwbmhb1y {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.738 15.405l-2.06 2.059l2.06 2.059l2.058-2.059z");
}

.t-93jr2mo {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.516 6.07L6.458 8.127l2.058 2.06l2.06-2.06z");
}

.t2ms3eb3u {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.495 14.476l-2.06 2.059l2.06 2.058l2.058-2.058z");
}

.t4l4z3bxy {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.239 4.353l2.007 2.007l-2.007 2.007L9.232 6.36zm0-.1l-2.11 2.11l2.11 2.109l2.11-2.11z");
}

.t9qngz6kb {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.742 7.218L5.683 9.277l2.06 2.059L9.8 9.276z");
}

.ta235obem {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.91 5.79l-2.059 2.06l2.06 2.058l2.058-2.059z");
}

.tflvq53xw {
  fill: var(--svg-color--030206, #030206);
  d: path("m9.78 14.91l-2.06 2.06l2.06 2.059l2.059-2.06z");
}

.tgz-u5bng {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.101 15.72l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.tou63vbhq {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.796 4.103l2.008 2.007l-2.008 2.007L10.79 6.11zm0-.103L10.69 6.11l2.11 2.11l2.107-2.11z");
}

.twbugrbxt {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.534 4.08l-2.06 2.06l2.06 2.058l2.058-2.059z");
}

.u_fospbfa {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.101 4.263l2.007 2.008l-2.007 2.01l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.u203bvb1e {
  fill: var(--svg-color--030206, #030206);
  d: path("M11.24 4.304L9.18 6.363l2.06 2.059l2.059-2.06z");
}

.u8a1ajbbu {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.25 15.184l-2.06 2.06l2.06 2.058l2.058-2.059z");
}

.ua_wvvbyx {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.277 14.65l-2.059 2.058l2.059 2.06l2.059-2.06z");
}

.uyjv3ob5n {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.337 13.647l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.v1nb3z7ao {
  fill: var(--svg-color--030206, #030206);
  d: path("m8.17 13.37l-2.058 2.06l2.059 2.058l2.059-2.058z");
}

.v4md3vcey {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.061 4.126l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.v4s-sebxe {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.91 14.091l-2.058 2.06l2.059 2.058l2.059-2.059z");
}

.vglev63rh {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.906 5.707l2.008 2.007l-2.008 2.01L6.9 7.717zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.vmg-12rpy {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.054 14.81l-2.059 2.059l2.06 2.059l2.058-2.059z");
}

.vo9vg7sui {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.358 15.603l-2.06 2.059l2.06 2.059l2.058-2.06z");
}

.vrrqu0ttt {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.741 12.666l-2.059 2.059l2.06 2.059l2.058-2.06z");
}

.vt02zqfnn {
  fill: var(--svg-color--030206, #030206);
  d: path("M9.781 4.97L7.722 7.029l2.06 2.059l2.058-2.06z");
}

.vtn8gwbmk {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.517 6.12l2.007 2.007l-2.007 2.01l-2.008-2.008zm0-.101l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.vwq54irsn {
  fill: var(--svg-color--030206, #030206);
  d: path("m11.239 15.58l-2.06 2.059l2.06 2.059l2.058-2.06z");
}

.w54340bzx {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.088 9.806l-2.059 2.059l2.059 2.059l2.059-2.06z");
}

.w6ydv626s {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.1 10.34L5.04 12.4l2.06 2.059l2.059-2.06z");
}

.wf7183b4p {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.874 7.026L9.88 9.033L7.874 11.04L5.867 9.033zm0-.1l-2.11 2.11l2.11 2.109l2.11-2.11z");
}

.wgnam4biw {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.708 14.341l2.007 2.007l-2.007 2.008l-2.008-2.008zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.wz39kgb2g {
  fill: var(--svg-color--030206, #030206);
  d: path("M10.986 4.384L8.927 6.443l2.059 2.059l2.059-2.06z");
}

.wzvng7bjo {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.986 15.549l2.007 2.007l-2.007 2.01l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.x0dwd-9bi {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.826 4.972l2.007 2.007l-2.007 2.007L13.82 6.98zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.x3at3ge3p {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.016 6.792l2.007 2.007l-2.007 2.007L6.008 8.8zm0-.103L5.906 8.8l2.11 2.11l2.11-2.11z");
}

.xi5rm6bzu {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.207 8.743l-2.059 2.059l2.06 2.059l2.058-2.06z");
}

.xrhxq-h0a {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.337 6.339l2.007 2.007l-2.007 2.007L6.33 8.346zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.y-akubc7x {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M10.492 4.632L12.5 6.64l-2.007 2.008L8.486 6.64zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.y4087xbms {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.495 5.456l2.007 2.008l-2.007 2.007l-2.007-2.005zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.y9110rgvc {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.494 15.698l2.008 2.007l-2.008 2.007l-2.007-2.007zm0-.1l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.ydukktb7u {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.239 15.63l2.007 2.008l-2.007 2.007l-2.007-2.007zm0-.102l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.yewmk-ori {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.752 15.756l2.007 2.007l-2.007 2.007l-2.007-2.007zm0-.103l-2.11 2.11l2.11 2.11l2.11-2.11z");
}

.yirggobog {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.012 15.75l-2.059 2.06l2.06 2.058l2.058-2.059z");
}

.yok9crkjg {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.89 14.141l2.007 2.007l-2.007 2.008l-2.007-2.008zm0-.1l-2.11 2.11l2.11 2.11L19 16.15z");
}

.ysfa3tmjg {
  fill: var(--svg-color--030206, #030206);
  d: path("m11.495 15.65l-2.06 2.058l2.06 2.06l2.059-2.06z");
}

.yyryvunzs {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.706 5.86L6.647 7.92l2.06 2.058l2.058-2.059z");
}

.zezxguy1f {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.78 5.02l2.008 2.007l-2.007 2.01L7.774 7.03zm0-.1L7.672 7.03l2.11 2.11l2.11-2.11z");
}

.zf3b9etdk {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.061 4.076l-2.059 2.059l2.06 2.059l2.058-2.06z");
}

.zkrjszb_o {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.517 12.17l-2.06 2.06l2.06 2.058l2.059-2.059z");
}

.zlow1tc6u {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.249 4.75l2.01 2.007l-2.008 2.008l-2.01-2.008zm0-.103L8.14 6.757l2.11 2.11l2.11-2.11z");
}

.ztgrh2bmb {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.16 9.008l-2.058 2.059l2.058 2.059l2.06-2.06z");
}

.zxqf97bzw {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.11 10.125l2.007 2.008L7.11 14.14l-2.007-2.007zm0-.1L5 12.135l2.11 2.11l2.11-2.11z");
}

</style>
