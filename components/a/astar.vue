<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGTUK6fdHP)" clip-rule="evenodd" class="uz67c8t0l"/><path fill="url(#SVG2CcoAdyc)" class="ojnazebly"/><path fill="url(#SVGFQ93BYfd)" class="m1-jhx1zp"/><path fill="url(#SVG7dcHPbNO)" class="q9coi2b2c"/><path fill="url(#SVGEyeJNdMk)" class="lu3mkebpc"/><path fill="url(#SVG4rePLeoT)" class="go_olhb0u"/><path fill="url(#SVGtkSzVbOW)" class="dtslimb9p"/><path fill="url(#SVGsEdVPeym)" class="cqwqdxbbs"/><path fill="url(#SVGpynu7d1r)" class="b400nychy"/><path fill="url(#SVG24InRdFP)" class="c1auczbst"/><path fill="url(#SVG3AMICeAF)" class="f9hxil8zc"/><path fill="url(#SVGexhovH8N)" class="z859etbxu"/><path fill="url(#SVGz7NtldRD)" class="zb_hefbfd"/><path fill="url(#SVGsa8dwbOH)" clip-rule="evenodd" class="ti2pvi7yk"/><path fill="url(#SVGYr4m3bhj)" clip-rule="evenodd" class="ko-aos55g"/><path fill="url(#SVGbDUpxb3b)" clip-rule="evenodd" class="exmy55bvu"/><defs><linearGradient id="SVGTUK6fdHP" x1="18.753" x2="5.81" y1="6.365" y2="18.63" gradientUnits="userSpaceOnUse"><stop class="g9qqoxbbc"/><stop offset=".189" class="yfbb_wqqs"/><stop offset=".278" class="g_85n9b6v"/><stop offset=".42" class="hkyzs9swy"/><stop offset=".553" class="lb0b7rb4s"/><stop offset=".744" class="zx3rqcsyy"/><stop offset=".873" class="aesetp_pi"/><stop offset="1" class="s30t6abbp"/></linearGradient><linearGradient id="SVG2CcoAdyc" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="md8kb0b5s"/><stop offset="1" class="oyfzknbrj"/></linearGradient><linearGradient id="SVGFQ93BYfd" x1="19.761" x2="15.07" y1="6.044" y2="21.909" gradientUnits="userSpaceOnUse"><stop class="m6lnmsgum"/><stop offset=".269" class="tzfupcbvx"/><stop offset=".483" class="z-k-x-ejz"/><stop offset=".795" class="gsbybyuxy"/><stop offset="1" class="g8z697p5o"/></linearGradient><linearGradient id="SVG7dcHPbNO" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="vbsy3zyyb"/><stop offset="1" class="ihq0f-b-o"/></linearGradient><linearGradient id="SVGEyeJNdMk" x1="14.892" x2="1.429" y1="20.552" y2="9.718" gradientUnits="userSpaceOnUse"><stop class="cneyifbqi"/><stop offset=".131" class="q10wn619r"/><stop offset=".463" class="nz-1apxrd"/><stop offset=".81" class="vf0zpvxew"/><stop offset="1" class="ypqn3xp4n"/></linearGradient><linearGradient id="SVG4rePLeoT" x1="3.609" x2="19.157" y1="6.959" y2="16.3" gradientUnits="userSpaceOnUse"><stop class="t_xlbzb-j"/><stop offset="1" class="u5ejejcuq"/></linearGradient><linearGradient id="SVGtkSzVbOW" x1="4.183" x2="21.947" y1="17.192" y2="7.657" gradientUnits="userSpaceOnUse"><stop class="sp9e5flhz"/><stop offset=".528" class="m1hppqbdz"/><stop offset=".76" class="uo6hp4bma"/><stop offset="1" class="j_b06sboq"/></linearGradient><linearGradient id="SVGsEdVPeym" x1="20.597" x2="9.186" y1="9.748" y2="13.635" gradientUnits="userSpaceOnUse"><stop class="jbo6d8v2l"/><stop offset=".33" class="wx29wybad"/><stop offset="1" class="pegujb2dm"/></linearGradient><linearGradient id="SVGpynu7d1r" x1="5.601" x2="11.199" y1="18.127" y2="6.027" gradientUnits="userSpaceOnUse"><stop class="gnzxqq5jt"/><stop offset="1" class="nmc0obbju"/></linearGradient><linearGradient id="SVG24InRdFP" x1="3.428" x2="10.434" y1="5.462" y2="7.755" gradientUnits="userSpaceOnUse"><stop class="dpokc-kna"/><stop offset=".244" class="ikx-5q1kx"/><stop offset=".585" class="jovxxkbat"/><stop offset="1" class="p0jlyrzgo"/></linearGradient><linearGradient id="SVG3AMICeAF" x1="14.604" x2="9.019" y1="3.011" y2="21.501" gradientUnits="userSpaceOnUse"><stop class="r-drmvphv"/><stop offset="1" class="xtbe48bhn"/></linearGradient><linearGradient id="SVGexhovH8N" x1="3.646" x2="20.393" y1="18.122" y2="18.201" gradientUnits="userSpaceOnUse"><stop class="hqfxdri7x"/><stop offset=".179" class="m4gzu4m4v"/><stop offset="1" class="rm73elkhd"/></linearGradient><linearGradient id="SVGz7NtldRD" x1="8.39" x2="13.451" y1="3.629" y2="21.91" gradientUnits="userSpaceOnUse"><stop class="to7s7sivv"/><stop offset=".312" class="yq7r__91g"/><stop offset=".577" class="eai_bp96t"/><stop offset="1" class="kp5lckp5g"/></linearGradient><linearGradient id="SVGsa8dwbOH" x1="18.7" x2="2.582" y1="10.161" y2="10.996" gradientUnits="userSpaceOnUse"><stop class="f9rx58bvu"/><stop offset=".424" class="lwjj23boh"/><stop offset="1" class="qaryfwpim"/></linearGradient><linearGradient id="SVGYr4m3bhj" x1="12.098" x2="12.098" y1="3.116" y2="20.833" gradientUnits="userSpaceOnUse"><stop class="zjponvb_k"/><stop offset="1" class="f2rk200il"/></linearGradient><linearGradient id="SVGbDUpxb3b" x1="7.967" x2="15.616" y1="16.388" y2="8.942" gradientUnits="userSpaceOnUse"><stop class="x8n1g1mxz"/><stop offset=".672" class="g517c4tbq"/><stop offset="1" class="o9cxw5byu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:astar" /></template>
<style>
.aesetp_pi {
  stop-color: var(--svg-color--910659, #910659);
}

.b400nychy {
  d: path("M15.057 19.72c3.264-2.1 2.722-4.751 2.071-5.87c1.05 2.906-1.378 4.355-2.72 4.707z");
}

.c1auczbst {
  d: path("M3.82 10.617c.04 3.882 2.472 4.874 3.881 4.907c-3.016-.658-2.84-3.477-2.585-4.818z");
}

.cneyifbqi {
  stop-color: var(--svg-color--3458d8, #3458d8);
}

.cqwqdxbbs {
  d: path("M17.022 5.428c-3.386-1.668-5.406.221-5.993 1.373c1.874-2.455 4.389-1.195 5.41-.259z");
}

.dpokc-kna {
  stop-color: var(--svg-color--4c46c3, #4c46c3);
}

.dtslimb9p {
  d: path("M3.497 14.625c-.664-1.312-.528-3.494-.338-4.406l.354-1.231c.186 1.748.272 3.403 1.22 4.895c.947 1.492 3.65 2.516 6.422.647s2.998-5.007 2.567-6.912c-.346-1.524-1.03-1.285-1.311-.962c.672-1.168 2.113-1.048 2.882.018c.614.852.663 2.417.611 3.094c-.127 1.808-1.26 5.767-4.77 7.143c-4.39 1.72-6.804-.648-7.637-2.286");
}

.eai_bp96t {
  stop-color: var(--svg-color--066de9, #066de9);
}

.exmy55bvu {
  fill-rule: evenodd;
  d: path("M12.165 15.35c-1.878 1.515-4.346 1.403-5.348 1.158l.05-.206c.967.236 3.358.34 5.164-1.116c2.09-1.684 3.392-5.263 2.246-8.234a2.2 2.2 0 0 0-.317-.505c-.151-.186-.315-.346-.446-.411l.094-.19c.172.087.363.276.518.469c.155.194.29.409.349.562c1.183 3.066-.159 6.738-2.31 8.474");
}

.f2rk200il {
  stop-color: var(--svg-color--00c2f9, #00c2f9);
}

.f9hxil8zc {
  d: path("M13.582 5.846c.75.647 1.783 2.524.87 5.838c-1.23 4.449-5.191 5.075-7.185 4.82l.091-1.02c1.12.18 2.45-.046 3.796-.954c2.772-1.87 2.998-5.008 2.567-6.913c-.346-1.524-1.029-1.275-1.31-.952c.317-.575.726-.756 1.17-.82");
}

.f9rx58bvu {
  stop-color: var(--svg-color--03b0fb, #03b0fb);
}

.ft5dv1b6b {
  fill: none;
}

.g_85n9b6v {
  stop-color: var(--svg-color--0279c2, #0279c2);
}

.g517c4tbq {
  stop-color: var(--svg-color--02e8fd, #02e8fd);
}

.g8z697p5o {
  stop-color: var(--svg-color--086ee8, #086ee8);
}

.g9qqoxbbc {
  stop-color: var(--svg-color--0ae2ff, #0ae2ff);
}

.gnzxqq5jt {
  stop-color: var(--svg-color--2660de, #2660de);
}

.go_olhb0u {
  d: path("M15.09 6.58a1.537 1.537 0 1 0-2.634 1.584A1.537 1.537 0 0 0 15.09 6.58");
}

.gsbybyuxy {
  stop-color: var(--svg-color--3aa7f7, #3aa7f7);
}

.hkyzs9swy {
  stop-color: var(--svg-color--018af6, #018af6);
}

.hqfxdri7x {
  stop-color: var(--svg-color--6340c6, #6340c6);
}

.ihq0f-b-o {
  stop-color: var(--svg-color--392470, #392470);
}

.ikx-5q1kx {
  stop-color: var(--svg-color--4250d3, #4250d3);
}

.j_b06sboq {
  stop-color: var(--svg-color--06c1fd, #06c1fd);
}

.jbo6d8v2l {
  stop-color: var(--svg-color--08cded, #08cded);
}

.jovxxkbat {
  stop-color: var(--svg-color--3b54d6, #3b54d6);
}

.ko-aos55g {
  fill-rule: evenodd;
  d: path("M9.09 10.404c-.332-2.39 1.037-4.447 1.762-5.18l.15.149c-.7.708-2.022 2.702-1.703 5.001c.37 2.659 2.766 5.618 5.902 6.165c.132.024.362.025.597-.002c.237-.028.457-.084.579-.162l.114.178c-.165.106-.425.165-.668.194q-.328.045-.66 0c-3.235-.563-5.694-3.604-6.073-6.343");
}

.kp5lckp5g {
  stop-color: var(--svg-color--007aef, #007aef);
}

.lb0b7rb4s {
  stop-color: var(--svg-color--0076ed, #0076ed);
}

.lu3mkebpc {
  d: path("M18.527 18.029c-.79 1.24-2.757 2.198-3.639 2.499l-1.24.32c1.41-1.048 2.81-1.93 3.613-3.505c.804-1.575.313-4.422-2.706-5.86s-5.838-.037-7.258 1.303c-1.137 1.073-.606 1.53-.186 1.609c-1.284 0-1.954-1.279-1.426-2.482c.422-.962 1.745-1.8 2.354-2.1c1.622-.809 5.607-1.845 8.576.478c3.712 2.906 2.9 6.189 1.912 7.738");
}

.lwjj23boh {
  stop-color: var(--svg-color--02dffc, #02dffc);
}

.m1-jhx1zp {
  d: path("M14.177 3.349c1.466.105 3.199 1.396 3.883 2.03l.872.938c-1.593-.742-2.989-1.571-4.755-1.528s-4.038 1.833-3.863 5.172c.174 3.338 2.75 5.15 4.604 5.76c1.483.49 1.634-.183 1.503-.59c.598 1.163-.194 2.314-1.503 2.423c-1.048.087-2.415-.677-2.967-1.07c-1.485-1.04-4.295-4.049-3.666-7.767c.785-4.648 4.059-5.499 5.892-5.368");
}

.m1hppqbdz {
  stop-color: var(--svg-color--005ab9, #005ab9);
}

.m4gzu4m4v {
  stop-color: var(--svg-color--1f61e0, #1f61e0);
}

.m6lnmsgum {
  stop-color: var(--svg-color--09defc, #09defc);
}

.md8kb0b5s {
  stop-color: var(--svg-color--016fd8, #016fd8);
}

.nmc0obbju {
  stop-color: var(--svg-color--004988, #004988);
}

.nz-1apxrd {
  stop-color: var(--svg-color--0271c2, #0271c2);
}

.o9cxw5byu {
  stop-color: var(--svg-color--08ddfe, #08ddfe);
}

.ojnazebly {
  d: path("M15.088 17.403a1.524 1.524 0 1 0 0-3.048a1.524 1.524 0 0 0 0 3.048");
}

.oyfzknbrj {
  stop-color: var(--svg-color--003a72, #003a72);
}

.p0jlyrzgo {
  stop-color: var(--svg-color--4f1964, #4f1964);
}

.pegujb2dm {
  stop-color: var(--svg-color--03618e, #03618e);
}

.q10wn619r {
  stop-color: var(--svg-color--0187f5, #0187f5);
}

.q9coi2b2c {
  d: path("M5.706 12.134a1.537 1.537 0 1 0 2.678 1.51a1.537 1.537 0 0 0-2.678-1.51");
}

.qaryfwpim {
  stop-color: var(--svg-color--af75f4, #af75f4);
}

.r-drmvphv {
  stop-color: var(--svg-color--05b2fc, #05b2fc);
}

.rm73elkhd {
  stop-color: var(--svg-color--0184ef, #0184ef);
}

.s30t6abbp {
  stop-color: var(--svg-color--cb006d, #cb006d);
}

.sp9e5flhz {
  stop-color: var(--svg-color--bd1493, #bd1493);
}

.t_xlbzb-j {
  stop-color: var(--svg-color--027ed5, #027ed5);
}

.ti2pvi7yk {
  fill-rule: evenodd;
  d: path("M14.749 10.197c2.258.846 3.415 3.029 3.714 4.017l-.204.061c-.287-.953-1.411-3.065-3.584-3.88c-2.514-.943-6.257-.246-8.233 2.25q-.17.24-.28.513c-.086.215-.14.427-.129.571l-.211.017c-.015-.196.055-.445.144-.668c.092-.223.21-.438.31-.564c2.039-2.577 5.884-3.288 8.473-2.317");
}

.to7s7sivv {
  stop-color: var(--svg-color--04a9f0, #04a9f0);
}

.tzfupcbvx {
  stop-color: var(--svg-color--028df7, #028df7);
}

.u5ejejcuq {
  stop-color: var(--svg-color--02517b, #02517b);
}

.uo6hp4bma {
  stop-color: var(--svg-color--03defe, #03defe);
}

.uz67c8t0l {
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-17.999A9 9 0 0 0 12 21m0-2.03a6.97 6.97 0 1 0 0-13.94a6.97 6.97 0 0 0 0 13.94");
}

.vbsy3zyyb {
  stop-color: var(--svg-color--344abe, #344abe);
}

.vf0zpvxew {
  stop-color: var(--svg-color--01bcf8, #01bcf8);
}

.wx29wybad {
  stop-color: var(--svg-color--06accf, #06accf);
}

.x8n1g1mxz {
  stop-color: var(--svg-color--bb46d6, #bb46d6);
}

.xtbe48bhn {
  stop-color: var(--svg-color--7e2b9f, #7e2b9f);
}

.yfbb_wqqs {
  stop-color: var(--svg-color--047da5, #047da5);
}

.ypqn3xp4n {
  stop-color: var(--svg-color--534bcf, #534bcf);
}

.yq7r__91g {
  stop-color: var(--svg-color--0167c3, #0167c3);
}

.z-k-x-ejz {
  stop-color: var(--svg-color--0056af, #0056af);
}

.z859etbxu {
  d: path("M17.32 14.303c-.41-1.068-1.283-2.113-2.765-2.82c-3.018-1.436-5.838-.036-7.258 1.304c-1.137 1.072-.59 1.534-.168 1.613a1.58 1.58 0 0 1-1.258-.566c.048-.857.865-2.5 3.945-3.588c4.193-1.482 7.416 1.122 8.358 3.392z");
}

.zb_hefbfd {
  d: path("M11.605 6.009c-.826.87-1.383 2.202-1.29 3.952c.174 3.337 2.75 5.15 4.603 5.76c1.484.489 1.635-.178 1.504-.586c.274.494.25.959.081 1.37c-1.19.336-3.578.138-5.875-2.839c-2.973-3.854-.674-7.065.1-8.145l.136-.196z");
}

.zjponvb_k {
  stop-color: var(--svg-color--03affa, #03affa);
}

.zx3rqcsyy {
  stop-color: var(--svg-color--4350d3, #4350d3);
}

</style>
