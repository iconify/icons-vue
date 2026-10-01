<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wjcuhexbz"/><path class="t1ducdbwf"/><path class="wkrn8ccfq"/><path class="ijt1iub3r"/><path class="lu-n4fcnt"/><path class="s9ud62lij"/><path class="rbuho0ums"/><path class="v_3i-1blz"/><path class="v6thgbchv"/><path class="rx4yvouas"/><path class="ibvv7gbnx"/><path class="o-iu-ha1t"/><path class="q9-10sv7o"/><path class="pmyi-yb8h"/><path class="z5d1xu1gf"/><path class="kaepo-dza"/><path class="ha8eymbsd"/><path class="n1i1prv7o"/><path class="tg5ic9kmg"/><path class="h3p8b-3ps"/><path class="n5_qb4bqc"/><path class="f2zjczbtt"/><path class="tim5tkbyx"/><path class="sj-opsbzi"/><path class="izh-dgp5d"/><path class="u6bokp7ww"/><path class="mkjkwbb5x"/><path class="akcm2941f"/><path class="ouguklxmi"/><path class="l2bm5wbee"/><path class="m9tqu2bmv"/><path class="bv05-ln6i"/><path class="v8s5gxb9b"/><path class="qjgeqw3hg"/><path class="g3wh7jb2v"/><path class="uefc7sbmz"/><path class="qzr09_b_t"/><path class="kbp8jzbnq"/><path class="ne0gvdb3x"/><path class="e9aywib7y"/><path class="huhon8bog"/><path class="c3ef18vkc"/><path class="xbw9sgfet"/><path class="q27mgkb2x"/><path class="fq0vw7ddq"/><path class="m8g43lb9k"/><path class="n9jqtxbzd"/><path class="vzjkdubrg"/><path class="p8dq6bo1q"/><path class="uhixzqfrn"/><path class="wa9m5rbob"/><path class="ahk-e3-hi"/><path class="b46_l62pm"/><path class="h_6usi62s"/><path class="us3ne3s9f"/><path class="zgrs9pkxp"/><path class="vtt2lrb3x"/><path class="kzy17p_yg"/><path class="ipo7f516u"/><path class="s4nlrtbbe"/><path class="jhenp5b4u"/><path class="o9tcb1b_w"/><path class="ygeojmvnm"/><path class="tcus_gbsb"/><path class="o41s4p8wq"/><path class="bwcc1j4fj"/><path class="q8t_8-bak"/><path class="ahh--6bum"/><path class="aeby3jbcn"/><path class="i4hituu0z"/><path class="h6lrbwbdg"/><path class="r2mtsr5wh"/><path class="pfqkd81qx"/><path class="ebk_hbcpi"/><path class="be37n0csd"/><path class="cpyuqjb4d"/><path class="fe9gdgfhk"/><path class="lq6pgcqwz"/><path class="j1tphbcos"/><path class="d30v47g-u"/><path class="w-x1ifboc"/><path class="u8pm2rbkh"/><path class="ql8pq1osd"/><path class="grltd6pbg"/><path class="ah_xembha"/><path class="ric_15baw"/><path class="veou1ub9v"/><path class="x3c38kb5n"/><path class="fv9f4p2ou"/><path class="v9xuw3b3k"/><path class="nyw_stbkh"/><path class="n7s63ow0j"/><path class="mj4sup1bh"/><path class="ut0lcl_bi"/><path class="brn46qb3p"/><path class="thm5u5vdl"/><path class="eov9aabak"/><path class="iz6a6hbyr"/><path class="e093gbcma"/><path class="fvz7zze2z"/><path class="w5l1d3b5p"/><path class="pap0nsbym"/><path class="zkma1ub8b"/><path class="p0myz8ayi"/><path class="o64h1dbzw"/><path class="f3p0yzbyh"/><path class="wcy0he4mu"/><path class="el0fmhbpe"/><path class="raxncn4fw"/><path class="diu0gjbla"/><path class="b7y9z98qz"/><path class="nol51z_8x"/><path class="d5uzxg-yv"/><path class="cwvok1boe"/><path class="so9g-7vsk"/><path class="ba0nv_bcy"/><path class="yh844c5eo"/><path class="aphkujpqi"/><path class="ggpiwtbar"/><path class="t6f9m6baq"/><path class="hl6wgwbdo"/><path class="v9mt9jbkp"/><path class="t2k34wcyd"/><path class="jgy6djb4n"/><path class="dx_vqlbdc"/><path class="ld9jcrbxw"/><path class="ei71p06sy"/><path class="afpbkmg0u"/><path class="ei_m18bno"/><path class="wtn7po7po"/><path class="b06j3eipy"/><path class="dzuhm78jo"/><path class="i-braac-l"/><path class="vgaev3bwe"/><path class="xi6beel2m"/><path class="dqop75b9o"/><path class="lfi7p3o9h"/><path class="axyk8ur6d"/><path class="lquzynjtl"/><path class="u-pn5ekmc"/><path class="bpwxcvb4e"/><path class="pji5qq9nw"/><path class="vwwjklboj"/><path class="uc-0mcccj"/><path class="kvwfw5b5b"/><path class="s_fsx-byz"/><path class="vx3rweggb"/><path class="h6i5ivh1k"/><path class="esztr49wr"/><path class="l0eeowbmf"/><path class="sqnoh4btk"/><path class="xxh6ubzxm"/><path class="ef5f7gb4w"/><path class="hxmao4brq"/><path class="prmjd8bvk"/><path class="tv_9sbcue"/><path class="q17nyz8vk"/><path class="mgsu6-bmd"/><path class="uq2j07ypm"/><path class="mo6c1abxv"/><path class="h0eqmvvhg"/><path class="m4_ptnbhm"/><path class="gso1e2bps"/><path class="z0qnlcblp"/><path class="quu0e4yyb"/><path class="c0v61ubkb"/><path class="nlf4q81ci"/><path class="csndv7xjt"/><path class="etyk1_bnc"/><path class="c8tvgubba"/><path class="ik5aehezr"/><path class="moy0vab5m"/><path class="evudorbzr"/><path class="wyt8o-6ma"/><path class="myxv36kee"/><path class="fnz4po8pg"/><path class="cq59t994t"/><path class="vsjco9y-i"/><path class="gm6a8vbby"/><path class="jhiwyf4mc"/><path class="y5rxjdbsy"/><path class="ns4c8nl3i"/><path class="n72xkebfy"/><path class="flta8nbcx"/><path class="f-oxm_bui"/><path class="toac4zfzm"/><path class="l6o1w8f2n"/><path class="ysot_2fqz"/><path class="kqfufntxm"/><path class="ccrilhb1z"/><path class="win8-9d-t"/><path class="fgt1pdtez"/><path class="szs7itbjt"/><path class="xk0l29bgm"/><path class="nmlqx9bmq"/><path class="l6q2pbc8u"/><path class="ydzz19bmb"/><path class="wvuy4cznj"/><path class="godd1ab3g"/><path class="vn_89cbwl"/><path class="qjb9oiwvf"/><path class="g-x_chbfo"/><path class="lq2_bj9pl"/><path class="stj4wzlne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:canton" /></template>
<style>
.aeby3jbcn {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.236 5.075L5.9 7.409l2.335 2.335l2.334-2.335z");
}

.afpbkmg0u {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.446 13.322l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.113L5.054 15.6l2.392 2.392L9.839 15.6z");
}

.ah_xembha {
  fill: var(--svg-color--030206, #030206);
  d: path("M6.876 7.157L4.542 9.49l2.334 2.335L9.211 9.49z");
}

.ahh--6bum {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.465 4.903l2.276 2.276l-2.276 2.278l-2.276-2.276zm0-.114L6.072 7.18l2.393 2.393l2.392-2.393z");
}

.ahk-e3-hi {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.558 3.574l2.276 2.276l-2.276 2.276L8.282 5.85zm0-.114L8.165 5.853l2.393 2.392l2.392-2.392z");
}

.akcm2941f {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.107 3.221l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116l-2.393 2.392l2.393 2.393l2.392-2.393z");
}

.aphkujpqi {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.768 11.945l2.276 2.276l-2.276 2.276l-2.278-2.274zm0-.114l-2.392 2.393l2.392 2.392l2.393-2.392z");
}

.axyk8ur6d {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.465 14.543l2.276 2.275l-2.276 2.28l-2.276-2.277zm0-.117l-2.393 2.392l2.393 2.393l2.392-2.393z");
}

.b06j3eipy {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.814 13.776l-2.335 2.335l2.335 2.334l2.334-2.334z");
}

.b46_l62pm {
  fill: var(--svg-color--030206, #030206);
  d: path("M10.276 3.635L7.94 5.969l2.335 2.335l2.334-2.335z");
}

.b7y9z98qz {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.523 11.013l-2.335 2.335l2.335 2.334l2.334-2.335z");
}

.ba0nv_bcy {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.671 11.658l2.276 2.275l-2.276 2.28l-2.276-2.277zm0-.114L4.28 13.936l2.392 2.392l2.392-2.392z");
}

.be37n0csd {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.625 5.806L5.29 8.141l2.335 2.334l2.334-2.334z");
}

.bpwxcvb4e {
  fill: var(--svg-color--030206, #030206);
  d: path("m8.95 14.898l-2.334 2.335l2.335 2.334l2.334-2.334z");
}

.brn46qb3p {
  fill: var(--svg-color--030206, #030206);
  d: path("M6.47 8.615L4.133 10.95l2.335 2.335l2.335-2.335z");
}

.bv05-ln6i {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.51 3.143l2.276 2.276l-2.276 2.278l-2.276-2.276zm0-.114L11.118 5.42l2.392 2.393l2.392-2.393z");
}

.bwcc1j4fj {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.705 4.691l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116L6.313 6.967l2.392 2.392l2.392-2.392z");
}

.c0v61ubkb {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.313 16.294l2.276 2.276l-2.276 2.279l-2.276-2.276zm0-.116L9.921 18.57l2.392 2.393l2.393-2.393z");
}

.c3ef18vkc {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.014 3.189l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.117L9.62 5.465l2.393 2.392l2.392-2.392z");
}

.c8tvgubba {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.91 16.33l2.276 2.275l-2.276 2.276l-2.276-2.273zm0-.114l-2.39 2.392L12.914 21l2.39-2.392z");
}

.ccrilhb1z {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.833 15.665l2.275 2.276l-2.276 2.276l-2.275-2.276zm0-.113l-2.393 2.392l2.393 2.392l2.392-2.392z");
}

.cpyuqjb4d {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.625 5.863L9.9 8.139l-2.276 2.276l-2.276-2.276zm0-.114L5.232 8.14l2.393 2.393l2.392-2.393z");
}

.cq59t994t {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.106 16.168l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.csndv7xjt {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.61 16.316l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114l-2.392 2.393l2.392 2.392l2.393-2.392z");
}

.cwvok1boe {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.59 11.365l2.276 2.275l-2.276 2.276l-2.276-2.276zm0-.114l-2.392 2.392l2.392 2.392l2.392-2.392z");
}

.d30v47g-u {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.284 6.386L9.56 8.662l-2.276 2.276l-2.276-2.276zm0-.114L4.892 8.664l2.392 2.393l2.393-2.393z");
}

.d5uzxg-yv {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.59 11.309l-2.334 2.334l2.335 2.335l2.334-2.335z");
}

.diu0gjbla {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.469 10.773l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116l-2.393 2.392l2.393 2.393l2.392-2.393z");
}

.dqop75b9o {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.235 14.315l2.276 2.276l-2.276 2.278l-2.276-2.276zm0-.114l-2.392 2.392l2.392 2.393l2.392-2.393z");
}

.dx_vqlbdc {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.284 13l-2.335 2.335l2.335 2.335l2.334-2.335z");
}

.dzuhm78jo {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.814 13.835l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.117L5.42 16.111l2.393 2.392l2.392-2.392z");
}

.e093gbcma {
  fill: var(--svg-color--030206, #030206);
  d: path("M6.402 9.214L4.067 11.55l2.335 2.334l2.334-2.334z");
}

.e9aywib7y {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.313 3.15l2.276 2.277l-2.276 2.276l-2.276-2.276zm0-.113L9.921 5.43l2.392 2.392l2.393-2.392z");
}

.ebk_hbcpi {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.814 5.613L10.09 7.89l-2.276 2.276L5.538 7.89zm0-.116L5.42 7.889l2.393 2.392l2.392-2.392z");
}

.ef5f7gb4w {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.557 15.812l-2.334 2.335l2.334 2.335l2.335-2.335z");
}

.ei_m18bno {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.624 13.524l-2.335 2.334l2.335 2.335l2.335-2.335z");
}

.ei71p06sy {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.447 13.267L5.112 15.6l2.335 2.335L9.78 15.6z");
}

.el0fmhbpe {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.428 10.475l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116L4.036 12.75l2.392 2.393L8.82 12.75z");
}

.eov9aabak {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.428 8.913l-2.334 2.335l2.334 2.335l2.335-2.335z");
}

.esztr49wr {
  fill: var(--svg-color--030206, #030206);
  d: path("m10 15.564l-2.336 2.334L10 20.234l2.335-2.335z");
}

.etyk1_bnc {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.91 16.269l-2.334 2.335l2.335 2.334l2.334-2.334z");
}

.evudorbzr {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.51 16.247l-2.334 2.335l2.335 2.334l2.334-2.334z");
}

.f-oxm_bui {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.271 15.85l-2.334 2.335l2.334 2.335l2.335-2.335z");
}

.f2zjczbtt {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.984 3.438l2.276 2.276l-2.276 2.276l-2.275-2.276zm0-.113l-2.392 2.392l2.392 2.392l2.393-2.392z");
}

.f3p0yzbyh {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.411 10.174l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114L4.02 12.453l2.392 2.392l2.393-2.392z");
}

.fe9gdgfhk {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.446 6.065L5.111 8.4l2.335 2.334L9.781 8.4z");
}

.fgt1pdtez {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.105 15.524l2.276 2.276l-2.276 2.276L13.83 17.8zm0-.114l-2.392 2.393l2.392 2.392l2.393-2.392z");
}

.flta8nbcx {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.984 16.007l2.276 2.276l-2.276 2.276l-2.275-2.276zm0-.114l-2.392 2.39l2.392 2.392l2.393-2.392z");
}

.fnz4po8pg {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.81 16.27l2.275 2.279l-2.275 2.276l-2.276-2.276zm0-.114l-2.393 2.393l2.393 2.392l2.392-2.392z");
}

.fq0vw7ddq {
  fill: var(--svg-color--030206, #030206);
  d: path("M11.422 3.245L9.087 5.58l2.335 2.334l2.335-2.334z");
}

.ft5dv1b6b {
  fill: none;
}

.fv9f4p2ou {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.672 7.732l-2.335 2.335l2.335 2.335l2.335-2.335z");
}

.fvz7zze2z {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.392 9.271l2.276 2.276l-2.276 2.279l-2.276-2.276zm0-.114L4 11.55l2.392 2.392l2.393-2.392z");
}

.g-x_chbfo {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m17.38 14.616l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.117l-2.392 2.393l2.392 2.392l2.392-2.392z");
}

.g3wh7jb2v {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.91 3.063l-2.334 2.335l2.334 2.335l2.335-2.335z");
}

.ggpiwtbar {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.876 12.173l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.gm6a8vbby {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.4 16.109l-2.334 2.334l2.335 2.335l2.334-2.334z");
}

.godd1ab3g {
  fill: var(--svg-color--030206, #030206);
  d: path("M17.137 14.767L14.802 17.1l2.335 2.335l2.334-2.335z");
}

.grltd6pbg {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M6.998 6.934L9.274 9.21l-2.276 2.275L4.722 9.21zm0-.114L4.606 9.212l2.392 2.393L9.39 9.212z");
}

.gso1e2bps {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.014 16.2l-2.335 2.335l2.335 2.335l2.335-2.335z");
}

.h_6usi62s {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.277 3.693l2.276 2.276l-2.276 2.276L8 5.97zm0-.113L7.885 5.972l2.392 2.392l2.392-2.392z");
}

.h0eqmvvhg {
  fill: var(--svg-color--030206, #030206);
  d: path("m11.716 16.15l-2.335 2.335l2.335 2.334l2.335-2.334z");
}

.h3p8b-3ps {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.27 3.539l2.277 2.276l-2.276 2.278l-2.276-2.276zm0-.114l-2.392 2.392l2.393 2.393l2.392-2.393z");
}

.h6i5ivh1k {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.729 15.475l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116L7.336 17.75l2.393 2.393l2.392-2.393z");
}

.h6lrbwbdg {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.019 5.31L5.684 7.644L8.02 9.98l2.334-2.335z");
}

.ha8eymbsd {
  fill: var(--svg-color--030206, #030206);
  d: path("M15.553 3.594L13.22 5.928l2.334 2.335l2.335-2.335z");
}

.hl6wgwbdo {
  fill: var(--svg-color--030206, #030206);
  d: path("M6.999 12.456L4.664 14.79L7 17.125l2.334-2.335z");
}

.huhon8bog {
  fill: var(--svg-color--030206, #030206);
  d: path("M12.013 3.131L9.68 5.466L12.013 7.8l2.335-2.334z");
}

.hxmao4brq {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.558 15.871l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116l-2.393 2.392l2.393 2.393l2.392-2.393z");
}

.i-braac-l {
  fill: var(--svg-color--030206, #030206);
  d: path("m8.018 14.02l-2.334 2.334l2.334 2.335l2.335-2.335z");
}

.i4hituu0z {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.235 5.13l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.113L5.843 7.409l2.392 2.392l2.392-2.392z");
}

.ibvv7gbnx {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.372 4.017l-2.335 2.335l2.335 2.334l2.334-2.334z");
}

.ijt1iub3r {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m17.38 4.832l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116l-2.392 2.392L17.38 9.5l2.392-2.392z");
}

.ik5aehezr {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.212 16.262l-2.335 2.335l2.335 2.334l2.334-2.334z");
}

.ipo7f516u {
  fill: var(--svg-color--030206, #030206);
  d: path("M9.464 4.073L7.13 6.407l2.334 2.335L11.8 6.407z");
}

.iz6a6hbyr {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.428 8.97l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114L4.036 11.25l2.392 2.392L8.82 11.25z");
}

.izh-dgp5d {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.402 3.223l-2.335 2.335l2.335 2.334l2.334-2.334z");
}

.j1tphbcos {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.284 6.33L4.95 8.664L7.284 11L9.62 8.664z");
}

.jgy6djb4n {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.133 12.788l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116l-2.392 2.392l2.392 2.392l2.392-2.392z");
}

.jhenp5b4u {
  fill: var(--svg-color--030206, #030206);
  d: path("M9.201 4.246L6.867 6.58L9.2 8.915l2.335-2.335z");
}

.jhiwyf4mc {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.401 16.167l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.117l-2.392 2.393l2.392 2.392l2.392-2.392z");
}

.kaepo-dza {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.833 3.78l2.275 2.276l-2.276 2.276l-2.275-2.276zm0-.116L13.44 6.056l2.393 2.392l2.392-2.392z");
}

.kbp8jzbnq {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.61 3.13l2.276 2.275l-2.276 2.276l-2.276-2.276zm0-.115l-2.392 2.393L12.61 7.8l2.393-2.392z");
}

.kqfufntxm {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.833 15.608l-2.335 2.335l2.335 2.335l2.334-2.335z");
}

.kvwfw5b5b {
  fill: var(--svg-color--030206, #030206);
  d: path("m9.462 15.256l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.kzy17p_yg {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.729 3.97l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114L7.336 6.248L9.73 8.641l2.392-2.393z");
}

.l0eeowbmf {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.999 15.619l2.278 2.279l-2.276 2.276l-2.278-2.276zm0-.114l-2.39 2.393l2.392 2.392l2.393-2.392z");
}

.l2bm5wbee {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.81 3.175l2.275 2.276l-2.275 2.276l-2.276-2.276zm0-.116l-2.393 2.392l2.393 2.393l2.392-2.393z");
}

.l6o1w8f2n {
  fill: var(--svg-color--030206, #030206);
  d: path("M15.555 15.736L13.22 18.07l2.335 2.335l2.334-2.335z");
}

.l6q2pbc8u {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.635 15.202l2.276 2.275l-2.276 2.276l-2.276-2.276zm0-.114l-2.393 2.392l2.393 2.392l2.392-2.392z");
}

.ld9jcrbxw {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.284 13.06l2.276 2.275l-2.276 2.276l-2.276-2.276zm0-.117l-2.392 2.392l2.392 2.393l2.393-2.393z");
}

.lfi7p3o9h {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.464 14.485L6.13 16.819l2.334 2.335l2.335-2.335z");
}

.lq2_bj9pl {
  fill: var(--svg-color--030206, #030206);
  d: path("m17.612 14.334l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.lq6pgcqwz {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.446 6.123l2.276 2.276l-2.276 2.276L5.17 8.399zm0-.116L5.054 8.399l2.392 2.392L9.84 8.4z");
}

.lquzynjtl {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.704 14.698L6.37 17.032l2.334 2.335l2.335-2.335z");
}

.lu-n4fcnt {
  fill: var(--svg-color--030206, #030206);
  d: path("M17.138 4.565L14.802 6.9l2.334 2.334L19.473 6.9z");
}

.m4_ptnbhm {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.716 16.208l2.276 2.276l-2.276 2.275l-2.276-2.276zm0-.117l-2.392 2.392l2.392 2.393l2.393-2.393z");
}

.m8g43lb9k {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.422 3.303l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.117L9.03 5.58l2.392 2.392l2.392-2.392z");
}

.m9tqu2bmv {
  fill: var(--svg-color--030206, #030206);
  d: path("M13.51 3.085L11.174 5.42l2.334 2.334l2.335-2.334z");
}

.mgsu6-bmd {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.13 16.066l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116l-2.392 2.392l2.392 2.393l2.393-2.393z");
}

.mj4sup1bh {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.522 8.318l-2.334 2.334l2.334 2.335l2.335-2.335z");
}

.mkjkwbb5x {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.107 3.163l-2.335 2.334l2.335 2.335l2.334-2.335z");
}

.mo6c1abxv {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.422 16.142l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.113L9.03 18.42l2.392 2.392l2.392-2.392z");
}

.moy0vab5m {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.213 16.321l2.276 2.276l-2.276 2.279l-2.276-2.276zm0-.116l-2.393 2.392l2.393 2.393l2.392-2.393z");
}

.myxv36kee {
  fill: var(--svg-color--030206, #030206);
  d: path("m13.81 16.214l-2.335 2.335l2.335 2.334l2.334-2.334z");
}

.n1i1prv7o {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.554 3.653l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114L13.162 5.93l2.392 2.393l2.393-2.393z");
}

.n5_qb4bqc {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.985 3.382l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.n72xkebfy {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.983 15.949l-2.334 2.334l2.334 2.335l2.335-2.335z");
}

.n7s63ow0j {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.59 8.08l2.276 2.277l-2.276 2.276l-2.276-2.276zm0-.116l-2.392 2.393l2.392 2.392l2.392-2.392z");
}

.n9jqtxbzd {
  fill: var(--svg-color--030206, #030206);
  d: path("M11.131 3.323L8.796 5.658l2.335 2.335l2.335-2.335z");
}

.ne0gvdb3x {
  fill: var(--svg-color--030206, #030206);
  d: path("M12.313 3.094L9.98 5.43l2.334 2.334l2.335-2.334z");
}

.nlf4q81ci {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.611 16.26l-2.334 2.335l2.334 2.335l2.335-2.335z");
}

.nmlqx9bmq {
  fill: var(--svg-color--030206, #030206);
  d: path("M16.633 15.143L14.3 17.477l2.334 2.335l2.335-2.335z");
}

.nol51z_8x {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.523 11.069l2.276 2.276l-2.276 2.276l-2.276-2.274zm0-.114L4.13 13.348l2.393 2.392l2.392-2.392z");
}

.ns4c8nl3i {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.696 16.094l2.275 2.275l-2.276 2.276l-2.276-2.276zm0-.117l-2.393 2.392l2.392 2.393l2.393-2.393z");
}

.nyw_stbkh {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.59 8.023l-2.335 2.334l2.335 2.335l2.334-2.335z");
}

.o-iu-ha1t {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.373 4.076l2.276 2.276l-2.276 2.275l-2.276-2.275zm0-.114L13.98 6.354l2.393 2.393l2.392-2.393z");
}

.o41s4p8wq {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.705 4.632L6.37 6.966l2.335 2.335l2.334-2.335z");
}

.o64h1dbzw {
  fill: var(--svg-color--030206, #030206);
  d: path("M6.4 10.115L4.065 12.45L6.4 14.784l2.334-2.334z");
}

.o9tcb1b_w {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.202 4.303l2.276 2.276l-2.276 2.276L6.926 6.58zm0-.116l-2.39 2.392l2.393 2.393l2.392-2.393z");
}

.ouguklxmi {
  fill: var(--svg-color--030206, #030206);
  d: path("M13.809 3.117L11.474 5.45l2.335 2.335l2.335-2.335z");
}

.p0myz8ayi {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.411 9.873l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.113L4.02 12.152l2.392 2.392l2.393-2.392z");
}

.p8dq6bo1q {
  fill: var(--svg-color--030206, #030206);
  d: path("M10.841 3.413L8.506 5.748l2.335 2.335l2.335-2.335z");
}

.pap0nsbym {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.411 9.572l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.113L4.02 11.85l2.392 2.392l2.393-2.392z");
}

.pfqkd81qx {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.814 5.555L5.479 7.889l2.335 2.335l2.334-2.335z");
}

.pji5qq9nw {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.95 14.955l2.277 2.276l-2.276 2.278l-2.276-2.276zm0-.114l-2.392 2.392l2.393 2.393l2.392-2.393z");
}

.pmyi-yb8h {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.105 3.92l2.276 2.277l-2.276 2.276l-2.276-2.276zm0-.113L13.713 6.2l2.392 2.392L18.498 6.2z");
}

.prmjd8bvk {
  fill: var(--svg-color--030206, #030206);
  d: path("m10.842 15.919l-2.335 2.335l2.335 2.334l2.335-2.334z");
}

.q17nyz8vk {
  fill: var(--svg-color--030206, #030206);
  d: path("m11.13 16.009l-2.335 2.334l2.335 2.335l2.334-2.335z");
}

.q27mgkb2x {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.716 3.238l2.276 2.276l-2.276 2.276L9.44 5.514zm0-.114L9.324 5.516l2.392 2.393l2.393-2.393z");
}

.q8t_8-bak {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.465 4.847L6.13 7.182l2.335 2.334L10.8 7.182z");
}

.q9-10sv7o {
  fill: var(--svg-color--030206, #030206);
  d: path("M16.104 3.862L13.77 6.197l2.334 2.335l2.335-2.335z");
}

.qjb9oiwvf {
  fill: var(--svg-color--030206, #030206);
  d: path("m17.38 14.556l-2.335 2.335l2.335 2.335l2.334-2.335z");
}

.qjgeqw3hg {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M13.213 3.124L15.489 5.4l-2.276 2.276L10.937 5.4zm0-.114L10.82 5.402l2.393 2.393l2.392-2.393z");
}

.ql8pq1osd {
  fill: var(--svg-color--030206, #030206);
  d: path("M6.997 6.876L4.663 9.21l2.334 2.335L9.332 9.21z");
}

.quu0e4yyb {
  fill: var(--svg-color--030206, #030206);
  d: path("M12.313 16.235L9.978 18.57l2.335 2.334l2.334-2.334z");
}

.qzr09_b_t {
  fill: var(--svg-color--030206, #030206);
  d: path("m12.61 3.072l-2.335 2.334l2.335 2.335l2.334-2.335z");
}

.r2mtsr5wh {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.019 5.366l2.276 2.276l-2.276 2.279l-2.276-2.276zm0-.113L5.627 7.645l2.392 2.392l2.392-2.392z");
}

.raxncn4fw {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.468 10.715l-2.335 2.334l2.335 2.335l2.334-2.335z");
}

.rbuho0ums {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.89 4.37l-2.335 2.335l2.334 2.334l2.335-2.334z");
}

.ric_15baw {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.876 7.216l2.276 2.276l-2.276 2.276l-2.278-2.276zm0-.117L4.484 9.492l2.392 2.392L9.27 9.492z");
}

.rx4yvouas {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M16.635 4.244L18.91 6.52l-2.276 2.276l-2.276-2.276zm0-.114l-2.393 2.392l2.393 2.393l2.392-2.393z");
}

.s_fsx-byz {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.464 15.315l2.276 2.276l-2.276 2.279l-2.276-2.276zm0-.113l-2.392 2.392l2.392 2.392l2.392-2.392z");
}

.s4nlrtbbe {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.464 4.13l2.276 2.276l-2.276 2.278l-2.276-2.276zm0-.114L7.072 6.408l2.392 2.393l2.392-2.393z");
}

.s9ud62lij {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m17.137 4.62l2.276 2.277l-2.276 2.276l-2.276-2.274zm0-.113l-2.392 2.392l2.392 2.393l2.392-2.393z");
}

.sj-opsbzi {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.696 3.352l2.275 2.276l-2.276 2.276l-2.276-2.276zm0-.114L12.302 5.63l2.392 2.393l2.393-2.393z");
}

.so9g-7vsk {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.67 11.6l-2.334 2.334l2.335 2.335l2.334-2.335z");
}

.sqnoh4btk {
  fill: var(--svg-color--030206, #030206);
  d: path("M10.277 15.695L7.943 18.03l2.334 2.334l2.335-2.334z");
}

.stj4wzlne {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m17.608 14.39l2.276 2.277l-2.276 2.276l-2.276-2.276zm0-.113l-2.393 2.392l2.393 2.393L20 16.669z");
}

.szs7itbjt {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.373 15.313l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.t1ducdbwf {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m17.589 5.054l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116L15.196 7.33l2.393 2.393L19.98 7.33z");
}

.t2k34wcyd {
  fill: var(--svg-color--030206, #030206);
  d: path("m7.133 12.73l-2.335 2.335L7.133 17.4l2.334-2.335z");
}

.t6f9m6baq {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.876 12.232l2.276 2.276l-2.276 2.276l-2.278-2.276zm0-.116l-2.392 2.392L6.876 16.9l2.393-2.392z");
}

.tcus_gbsb {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.95 4.49l2.277 2.276l-2.276 2.28l-2.276-2.277zm0-.116L6.559 6.766L8.951 9.16l2.392-2.393z");
}

.tg5ic9kmg {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.27 3.48l-2.335 2.335L15.27 8.15l2.334-2.335z");
}

.thm5u5vdl {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.469 8.672l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114L4.076 10.95l2.393 2.393L8.86 10.95z");
}

.tim5tkbyx {
  fill: var(--svg-color--030206, #030206);
  d: path("M14.696 3.295L12.36 5.63l2.335 2.334L17.03 5.63z");
}

.toac4zfzm {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.27 15.907l2.277 2.276l-2.276 2.278l-2.276-2.276zm0-.114l-2.392 2.392l2.393 2.393l2.392-2.393z");
}

.tv_9sbcue {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.841 15.974l2.276 2.276l-2.276 2.279l-2.276-2.276zm0-.113L8.45 18.253l2.392 2.392l2.393-2.392z");
}

.u-pn5ekmc {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.705 14.757l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.117l-2.392 2.393l2.392 2.392l2.392-2.392z");
}

.u6bokp7ww {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.401 3.278l2.276 2.276l-2.276 2.279l-2.276-2.276zm0-.113L12.01 5.557l2.39 2.392l2.392-2.392z");
}

.u8pm2rbkh {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m7.133 6.657l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114L4.741 8.936l2.392 2.392l2.392-2.392z");
}

.uc-0mcccj {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.202 15.142l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114l-2.39 2.392l2.393 2.393l2.392-2.393z");
}

.uefc7sbmz {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.91 3.116l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.116l-2.39 2.392l2.393 2.393l2.39-2.393z");
}

.uhixzqfrn {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.841 3.47l2.276 2.277l-2.276 2.278L8.565 5.75zm0-.116L8.45 5.747l2.392 2.392l2.393-2.392z");
}

.uq2j07ypm {
  fill: var(--svg-color--030206, #030206);
  d: path("m11.423 16.087l-2.335 2.335l2.335 2.334l2.334-2.334z");
}

.us3ne3s9f {
  fill: var(--svg-color--030206, #030206);
  d: path("M9.999 3.768L7.664 6.103l2.335 2.335l2.334-2.335z");
}

.ut0lcl_bi {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.523 8.376l2.276 2.276l-2.276 2.279l-2.276-2.279zm0-.116L4.13 10.652l2.393 2.393l2.392-2.393z");
}

.v_3i-1blz {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.889 4.425l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.113l-2.393 2.392l2.393 2.392l2.392-2.392z");
}

.v6thgbchv {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.635 4.187l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.v8s5gxb9b {
  fill: var(--svg-color--030206, #030206);
  d: path("M13.213 3.067L10.878 5.4l2.335 2.335L15.547 5.4z");
}

.v9mt9jbkp {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.998 12.512l2.276 2.275l-2.276 2.276l-2.276-2.276zm0-.114L4.606 14.79l2.392 2.393L9.39 14.79z");
}

.v9xuw3b3k {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.671 7.788l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114L4.28 10.066l2.39 2.394l2.392-2.393z");
}

.veou1ub9v {
  fill: var(--svg-color--030206, #030206);
  d: path("M6.768 7.441L4.433 9.776l2.335 2.334l2.334-2.334z");
}

.vgaev3bwe {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m8.019 14.079l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.117l-2.392 2.393l2.392 2.392l2.392-2.392z");
}

.vn_89cbwl {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m17.137 14.825l2.276 2.276l-2.276 2.275l-2.276-2.276zm0-.117l-2.392 2.393l2.392 2.392l2.392-2.392z");
}

.vsjco9y-i {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m14.107 16.227l2.276 2.276l-2.276 2.275l-2.276-2.275zm0-.117l-2.393 2.393l2.393 2.392l2.392-2.392z");
}

.vtt2lrb3x {
  fill: var(--svg-color--030206, #030206);
  d: path("M9.729 3.914L7.394 6.248L9.73 8.583l2.334-2.335z");
}

.vwwjklboj {
  fill: var(--svg-color--030206, #030206);
  d: path("m9.203 15.086l-2.335 2.335l2.335 2.334l2.334-2.334z");
}

.vx3rweggb {
  fill: var(--svg-color--030206, #030206);
  d: path("M9.728 15.417L7.393 17.75l2.335 2.335l2.335-2.335z");
}

.vzjkdubrg {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m11.13 3.379l2.276 2.276L11.13 7.93L8.854 5.655zm0-.114L8.738 5.657L11.13 8.05l2.393-2.393z");
}

.w-x1ifboc {
  fill: var(--svg-color--030206, #030206);
  d: path("M7.134 6.602L4.799 8.937l2.335 2.334l2.334-2.335z");
}

.w5l1d3b5p {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.386 9.513l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.wa9m5rbob {
  fill: var(--svg-color--030206, #030206);
  d: path("M10.558 3.518L8.223 5.852l2.335 2.335l2.334-2.335z");
}

.wcy0he4mu {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.427 10.416l-2.334 2.335l2.334 2.334l2.335-2.334z");
}

.win8-9d-t {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.106 15.468l-2.335 2.334l2.335 2.335l2.334-2.335z");
}

.wjcuhexbz {
  fill: var(--svg-color--030206, #030206);
  d: path("M17.612 4.996L15.277 7.33l2.335 2.335l2.334-2.335z");
}

.wkrn8ccfq {
  fill: var(--svg-color--030206, #030206);
  d: path("m17.38 4.773l-2.335 2.334l2.335 2.335l2.334-2.335z");
}

.wtn7po7po {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("M7.625 13.583L9.9 15.858l-2.276 2.28l-2.276-2.277zm0-.117L5.232 15.86l2.393 2.392l2.392-2.393z");
}

.wvuy4cznj {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.889 15.02l2.276 2.276l-2.276 2.278l-2.276-2.276zm0-.117l-2.393 2.393l2.393 2.392l2.392-2.392z");
}

.wyt8o-6ma {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m13.51 16.302l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.113l-2.392 2.392l2.392 2.392l2.392-2.392z");
}

.x3c38kb5n {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m6.768 7.5l2.276 2.276l-2.276 2.276L4.49 9.776zm0-.116L4.376 9.776l2.392 2.393l2.393-2.393z");
}

.xbw9sgfet {
  fill: var(--svg-color--030206, #030206);
  d: path("M11.717 3.183L9.383 5.517l2.334 2.335l2.335-2.335z");
}

.xi6beel2m {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.234 14.257L5.9 16.592l2.334 2.334l2.335-2.334z");
}

.xk0l29bgm {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m16.373 15.37l2.276 2.275l-2.276 2.277l-2.276-2.277zm0-.114l-2.393 2.392l2.393 2.393l2.392-2.393z");
}

.xxh6ubzxm {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m10.277 15.752l2.276 2.276l-2.276 2.279L8 18.03zm0-.114l-2.392 2.393l2.392 2.392l2.392-2.392z");
}

.y5rxjdbsy {
  fill: var(--svg-color--030206, #030206);
  d: path("m14.694 16.035l-2.334 2.334l2.334 2.335l2.335-2.335z");
}

.ydzz19bmb {
  fill: var(--svg-color--030206, #030206);
  d: path("m16.888 14.962l-2.335 2.335l2.335 2.334l2.335-2.334z");
}

.ygeojmvnm {
  fill: var(--svg-color--030206, #030206);
  d: path("M8.95 4.431L6.616 6.766L8.95 9.1l2.335-2.334z");
}

.yh844c5eo {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.768 11.888l-2.334 2.334l2.334 2.335l2.335-2.335z");
}

.ysot_2fqz {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m15.554 15.793l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.114l-2.392 2.392l2.392 2.392l2.393-2.392z");
}

.z0qnlcblp {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m12.014 16.256l2.276 2.276l-2.276 2.276l-2.276-2.276zm0-.113L9.62 18.535l2.393 2.392l2.392-2.392z");
}

.z5d1xu1gf {
  fill: var(--svg-color--030206, #030206);
  d: path("m15.831 3.721l-2.334 2.335L15.83 8.39l2.335-2.334z");
}

.zgrs9pkxp {
  fill: var(--svg-color--f3ff97, #f3ff97);
  d: path("m9.999 3.826l2.278 2.276l-2.276 2.276l-2.278-2.276zm0-.116l-2.39 2.392l2.392 2.392l2.393-2.392z");
}

.zkma1ub8b {
  fill: var(--svg-color--030206, #030206);
  d: path("m6.388 9.816l-2.335 2.335l2.335 2.334l2.335-2.334z");
}

</style>
