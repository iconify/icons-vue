<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.57 .1)scale(.96413)"><defs><linearGradient id="SVGhBRJKALx" x1="15.7" x2="15.5" y1="102" y2="107" gradientTransform="rotate(6.54 714.85 146.08)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="vdtrmtbrd"/><stop offset=".7" class="vdtrmtbrd"/></linearGradient><linearGradient id="SVG1O1b9bTv" x1="15.3" x2="15.3" y1="104" y2="106" gradientTransform="rotate(6.54 714.85 146.08)" gradientUnits="userSpaceOnUse"><stop offset=".33" class="b3e25-sbi"/><stop offset=".82" class="b3e25-sbi"/></linearGradient><linearGradient id="SVGGT2Kxc3b" x1="-3311" x2="-3311" y1="804" y2="808" gradientTransform="matrix(-1.07 .315 .248 .986 -3724 274)" href="#SVGhBRJKALx"/><linearGradient id="SVGa3pSPb4l" x1="-3311" x2="-3311" y1="805" y2="807" gradientTransform="matrix(-1.07 .315 .248 .986 -3724 274)" href="#SVG1O1b9bTv"/><linearGradient id="SVG6F9FKj1u" x1="22.9" x2="22.9" y1="23.8" y2="14.9" gradientUnits="userSpaceOnUse"><stop offset="0" class="p7usmobpj"/><stop offset=".05" class="phz_znelb"/><stop offset=".46" class="ov6dpt_sk"/><stop offset=".79" class="lv3xdocya"/><stop offset="1" class="b28eqpblm"/></linearGradient><linearGradient id="SVGJ1G2UPhf" x1="24.3" x2="21.3" y1="22.4" y2="16.3" gradientUnits="userSpaceOnUse"><stop offset=".01" class="v-c7v3amm"/><stop offset=".42" class="b3e25-sbi"/><stop offset="1" class="gz4b-kutc"/></linearGradient><linearGradient id="SVGdEMufeOz" x1="24.1" x2="21.5" y1="22" y2="16.6" gradientUnits="userSpaceOnUse"><stop offset=".01" class="v-c7v3amm"/><stop offset=".42" class="b3e25-sbi"/><stop offset="1" class="p7usmobpj"/></linearGradient><linearGradient id="SVG7uM9zdHQ" x1="24.3" x2="21.2" y1="22.6" y2="16.2" gradientUnits="userSpaceOnUse"><stop offset=".02" class="vnttfnpsy"/><stop offset=".1" class="yv53qpbqe"/><stop offset=".99" class="p7usmobpj"/></linearGradient><linearGradient id="SVG4AdrIdSc" x1="383" x2="383" y1="-41.1" y2="-64.6" gradientTransform="matrix(1 0 0 -1 -367 -37.7)" gradientUnits="userSpaceOnUse"><stop offset="0" class="hgvdry2az"/><stop offset="1" class="zs_l3iwth"/></linearGradient><linearGradient id="SVGzoKTtb6W" x1="383" x2="382" y1="-58.6" y2="-58.6" gradientTransform="matrix(1 0 0 -1 -367 -37.7)" gradientUnits="userSpaceOnUse"><stop offset="0" class="nrluuib3w"/><stop offset="1" class="zbd3civgx"/></linearGradient><linearGradient id="SVGW9JgxeAI" x1="206" x2="198" y1="-131" y2="-123" gradientTransform="rotate(45 249.38 -155.9)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zs_l3iwth"/><stop offset=".5" class="zs_l3iwth"/><stop offset="1" class="zs_l3iwth"/></linearGradient><linearGradient id="SVGORiQ492t" x1="-723" x2="-728" y1="-710" y2="-710" gradientTransform="matrix(0 -1.19 1.19 0 859 -852)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><radialGradient id="SVGpP8DddTD" cx="131" cy="24.5" r="173" gradientTransform="translate(19.1 18.9)scale(.028)" gradientUnits="userSpaceOnUse"><stop offset=".48" class="of_hn-czv"/><stop offset=".78" class="vdtrmtbrd"/><stop offset="1" class="yv53qpbqe"/></radialGradient><radialGradient id="SVGd9putcCO" cx="138" cy="51" r="170" gradientTransform="translate(19 18.9)scale(.027)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="y4xoqgx3j"/><stop offset=".99" class="vnttfnpsy"/></radialGradient><radialGradient id="SVGRcPcVcYx" cx="-128" cy="14.6" r="121" gradientTransform="translate(19.3 19.7)scale(-.027)" gradientUnits="userSpaceOnUse"><stop offset=".88" class="b3e25-sbi"/><stop offset="1" class="wu1ghvbzh"/></radialGradient><radialGradient id="SVGjW9dZXOk" cx="-95.7" cy="89.9" r="192" gradientTransform="translate(19.3 19.7)scale(-.027)" gradientUnits="userSpaceOnUse"><stop offset="0" class="evfty-l4p"/><stop offset="1" class="cd78-mmrt"/></radialGradient></defs><path class="bx1x4dbdr"/><path class="be32n9bsk"/><path class="m_f7_acns"/><path fill="url(#SVGhBRJKALx)" class="b_o8nub7f"/><path class="nzsy9e08c"/><path fill="url(#SVG1O1b9bTv)" class="i7yvebb8y"/><path fill="url(#SVGGT2Kxc3b)" class="hll-2vkoj"/><path class="fla3tn2yv"/><path fill="url(#SVGa3pSPb4l)" class="ki4klcc_f"/><path fill="url(#SVG6F9FKj1u)" class="rsqa_q3xd"/><path fill="url(#SVGpP8DddTD)" class="ef-p8p5vc"/><circle fill="url(#SVGJ1G2UPhf)" class="ihtq42bhd"/><path fill="url(#SVGd9putcCO)" class="cal9rc0hd"/><circle fill="url(#SVGRcPcVcYx)" class="lffq13bgx"/><circle fill="url(#SVGdEMufeOz)" class="y3tm7z9wh"/><circle fill="url(#SVGjW9dZXOk)" class="s4osvzbyq"/><path fill="url(#SVG7uM9zdHQ)" class="s6ptcvbbp"/><path class="bct43zbrf"/><path class="uusljxola"/><path class="cr2655bzb"/><path class="v4sbk-ezf"/><path class="s_dkhters"/><path class="x-3nj3f9f"/><path class="onj9y3b7r"/><path class="xzbfxlbzh"/><path class="u3752-kvj"/><path class="u7ud6kw8w"/><path class="fadez1g1k"/><path class="h4mganb3j"/><path class="x783mccth"/><path fill="url(#SVG4AdrIdSc)" class="jvjh6yo6g"/><path fill="url(#SVGzoKTtb6W)" class="c70854bbd"/><path fill="url(#SVGW9JgxeAI)" class="v5avk9m2e"/><path fill="url(#SVGORiQ492t)" class="etpzyndxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-key" /></template>
<style>
.b_o8nub7f {
  d: path("m22.53 21.04l.45 3.3l.04.24a3 3 0 0 1 .12.93l.03.24l.24 1.73l.1.96l.04.32l.01.62l.43-.55l.1-.12a8 8 0 0 1 .86-.95l.12-.17l.12-.14l.32.22l.1.07q.3.13.58.3l.16.1l.15.09l.88.5c-.1-.14-.13-.29-.22-.42l-.12-.27l-.05-.17a9 9 0 0 0-.34-.97l-.04-.16l-.19-.61l-.06-.21l-.33-1.1l-.07-.23l-1.37-4.54Z");
}

.b28eqpblm {
  stop-color: var(--svg-color--b02328, #b02328);
}

.b3e25-sbi {
  stop-color: var(--svg-color--c0272d, #c0272d);
}

.bct43zbrf {
  fill: var(--svg-color--f48e84, #f48e84);
  d: path("M20.07 15.25s.33-.22 1.04.06a2 2 0 0 0 .58.17a.8.8 0 0 1-.72-.02a2 2 0 0 0-.9-.2");
}

.be32n9bsk {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M22 2H6.3a1.76 1.76 0 0 0-1.75 1.75v24.5A1.76 1.76 0 0 0 6.3 30h19.3a1.76 1.76 0 0 0 1.75-1.75V6.85zm.53 2.84l1.65 1.53h-1.66zm-16.2 23.4V3.74h14.4v4.37h4.8v20.1z");
}

.bx1x4dbdr {
  fill: var(--svg-color--gray, gray);
  d: path("M6.35 3.75v24.5h19.3V8.15h-4.8V3.78zm16.2 1.08l.01 1.54h1.67z");
}

.c70854bbd {
  d: path("M16 15.23a.7.7 0 0 0-.66.44a1 1 0 0 0-.06.28v10.03l.15.13l.19.16l.27.23l.28-.23l.4-.34l.15-.13v-9.86a1 1 0 0 0-.06-.28a.7.7 0 0 0-.38-.38a1 1 0 0 0-.28-.05");
}

.cal9rc0hd {
  d: path("M26.33 18.3c-.05-.17-.05-.34-.1-.52a2 2 0 0 0-.36-.54a2 2 0 0 0-.53-.59c-.2-.16-.35-.41-.58-.51a4 4 0 0 1-.53-.24a4 4 0 0 0-.53-.35a4 4 0 0 0-1.42.03c-.93.14-2.04.14-2.56.9a9 9 0 0 0-.52 1.46a5 5 0 0 0-.23 1.12a5 5 0 0 0 .07 1.48c.16.64.74.99 1.16 1.47a4 4 0 0 0 1.03.84c.38.26.86.69 1.3.69a5 5 0 0 0 1.18-.26a3 3 0 0 0 1.2-.72c.38-.27.78-.2 1-.57s-.07-.56.45-1.66a2 2 0 0 0 .26-.95a3 3 0 0 0-.3-1.09m-3.53 4.58a3.5 3.5 0 1 1 3.53-3.5a3.5 3.5 0 0 1-3.53 3.5");
}

.cd78-mmrt {
  stop-color: var(--svg-color--910d10, #910d10);
}

.cr2655bzb {
  fill: var(--svg-color--9b1d20, #9b1d20);
  d: path("M19.5 17.3a2 2 0 0 1 .39-.89a2 2 0 0 1 1.2-.59a6 6 0 0 0-1.02.52a1.4 1.4 0 0 0-.37.48z");
}

.ef-p8p5vc {
  d: path("M21.83 23.3a1.8 1.8 0 0 0 1.81.31c.76-.18.84-.66 1.38-1.02c.44-.27.93-.04 1.15-.58c.13-.4-.18-.89.08-1.29c.31-.57.85-.57.89-1.33c.05-.8-.57-.89-.8-1.42c-.26-.49.09-.8-.31-1.29a6 6 0 0 0-2.17-1.55c-.66-.14-1.15.44-1.86.4s-1.24-.58-1.95-.31c-1.28.53-.66 2.04-1.06 3.06a2.35 2.35 0 0 0 .13 2.67a11 11 0 0 0 .62 1.46c.45.71.93.4 1.6.58a1 1 0 0 1 .49.31");
}

.etpzyndxr {
  d: path("M15.9 6.33a4.2 4.2 0 0 0-4.09 4.2c0 2.32 1.88.93 4.2.93s4.2 1.38 4.2-.93a4.2 4.2 0 0 0-4.2-4.2zm.09.64a2.1 2.1 0 0 1 2.34 1.79a2.1 2.1 0 0 1-2.34 1.79a2.1 2.1 0 0 1-2.34-1.8a2.1 2.1 0 0 1 2.34-1.78");
}

.evfty-l4p {
  stop-color: var(--svg-color--c5263b, #c5263b);
}

.fadez1g1k {
  fill: var(--svg-color--db726f, #db726f);
  d: path("M23.2 23.6a2 2 0 0 0 .92-.34a3 3 0 0 1-.52.23c-.1 0-.39.07-.4.11");
}

.fla3tn2yv {
  fill: var(--svg-color--961b1e, #961b1e);
  d: path("M20.73 21.39s-1.14 5.9-1.2 6.3l-.04.23l-.13.66l-.03.17a10 10 0 0 0-.24 1.06l-.06.34c-.1.2-.14.4-.23.6c.27-.17.49-.4.74-.57l.15-.14a8 8 0 0 1 .89-.64l.1-.1l.32-.28l.14.12l.16.14a9 9 0 0 1 .86.62l.23.22c.2.2.44.37.64.59q-.02-.34-.08-.68V28.5l.03-1.62l.03-1.46l.08-3.45l-.16-.04l-.15 3.37l-.08 1.68l-.07 1.52v.15a8 8 0 0 1 .03 1.16c-.28-.37-.73-.51-1.07-.81l-.1-.1l-.42-.39l-.56.45l-.12.1c-.3.24-.68.4-1 .64l.27-.93l.02-.14l.16-.97l.23-1.36l.83-4.88Z");
}

.gz4b-kutc {
  stop-color: var(--svg-color--730b0d, #730b0d);
}

.h4mganb3j {
  fill: var(--svg-color--f8c9dd, #f8c9dd);
  d: path("M23 22.9a2.6 2.6 0 0 0 1.28-.34a3 3 0 0 1-1.28.34");
}

.hgvdry2az {
  stop-color: var(--svg-color--ffe800, #ffe800);
}

.hll-2vkoj {
  d: path("m23.1 21.98l-.08 3.45l-.01.24a3 3 0 0 0-.02.97v.25l-.04 1.62v.18l.02 1l-.01.34q.05.32.08.68l-.64-.6l-.23-.21a9 9 0 0 0-.86-.62l-.16-.14l-.14-.13l-.32.3l-.1.08a8 8 0 0 0-.89.65l-.15.14c-.25.17-.5.4-.74.6l.22-.63l.06-.34a10 10 0 0 1 .25-1.06l.03-.17l.13-.65l.04-.23l.22-1.18l.05-.25l.93-4.88Z");
}

.i7yvebb8y {
  d: path("m22.58 21.02l.5 3.18l.26 1.6l.23 1.43l.02.15a13 13 0 0 0 .14 1.35c.2-.52.66-.75.98-1.14l.08-.1l.34-.45l-.1.02l.53.34l.11.07a8 8 0 0 1 1.14.58a11 11 0 0 0-.4-1.1l-.06-.26l-.17-.59l-.44-1.6l-1.21-4.38l-.17.06l1.2 4.38l.45 1.6l.16.6l.08.25l.33.86l.13-.12c-.27-.17-.58-.21-.84-.4l-.11-.06l-.65-.41l-.07-.04l-.04.05l-.34.45l-.08.1a10 10 0 0 0-.88.98l.13.04c-.04-.36.02-.75-.06-1.12l-.02-.14l-.23-1.44l-.22-1.37l-.54-3.4Z");
}

.ihtq42bhd {
  cx: 22.8px;
  cy: 19.3px;
  r: 3.38px;
}

.jvjh6yo6g {
  d: path("M16 5.5a5.1 5.1 0 0 0-2.6 9.48v1.34l1.05 1.34l-1.05 1.35l1.05 1.34l-1.05 1.34l1.05 1.35l-1.05 1.35l2.3 1.95l.19.16l.4-.34l2.09-1.75v-9.3A5.1 5.1 0 0 0 16 5.5m0 1.46a2.1 2.1 0 0 1 2.34 1.79A2.1 2.1 0 0 1 16 10.54a2.1 2.1 0 0 1-2.34-1.79A2.1 2.1 0 0 1 16 6.96");
}

.ki4klcc_f {
  d: path("m23.05 21.96l-.16 3.34l-.08 1.67l-.07 1.5v.15a13 13 0 0 1 .02 1.4c-.29-.49-.82-.62-1.22-.95l-.1-.1l-.43-.38h.12l-.55.46l-.1.09a10 10 0 0 0-1.18.82a12 12 0 0 1 .3-1.2l.04-.28l.1-.64l.04-.22a7 7 0 0 1 .24-1.5l.78-4.68l.2.02l-.78 4.7c-.01.08-.22 1.05-.24 1.48l-.04.23l-.1.63l-.05.28q-.11.48-.26.94l-.15-.1c.28-.22.6-.32.86-.56l.12-.1l.66-.55l.06-.05l.06.05l.43.38l.1.1a10 10 0 0 1 1.08.81l-.14.07c0-.38-.1-.76-.07-1.15v-.15l.08-1.5l.01-.23a9 9 0 0 1 .06-1.2l.16-3.58Z");
}

.lffq13bgx {
  cx: 22.8px;
  cy: 19.3px;
  r: 3.31px;
}

.lv3xdocya {
  stop-color: var(--svg-color--a72126, #a72126);
}

.m_f7_acns {
  fill: var(--svg-color--d7d8da, #d7d8da);
  d: path("M27.05 28.75c-.07-.12-.1-.17-.13-.25l-.05-.15a8 8 0 0 0-.34-.89l-.05-.14l-.18-.56l-.01-.02l-.06-.17l-.17-.51l-.15-.45l-.01-.04l-.07-.2l-1.4-4.14l-.15.06l-1.87.81h-.02l-.04.02v.06l.1.7l-1.77-.4l-.17-.05l-1.1 5.18l-.1.49l-.02.09l-.05.2l-.12.6l-.04.16a8 8 0 0 0-.25.96l-.06.32l-.18.45l-.04.1v-.01v.02l.24-.18l.5-.35l.01-.01l.13-.1l.03-.03a8 8 0 0 1 .9-.59l.1-.08l.33-.26l.14.11l.16.13a10 10 0 0 1 .87.56l.23.2c.2.18.45.34.66.54l-.09-.62l.01-.3l-.01-.92v-.16l.03-1.48l.01-.22l.03-1.11l.01-.62l.11.7l.01.1l.07.45l.16 1.04v.05l.03.15l.1.88l.04.3q.03.28.02.56l.43-.5l.1-.11a8 8 0 0 1 .87-.87l.13-.15l.11-.13l.33.2l.1.06q.3.12.6.27l.16.09l.15.08l.89.46z");
}

.nrluuib3w {
  stop-color: var(--svg-color--ffe800, #ffe800);
  stop-opacity: 0.39;
}

.nzsy9e08c {
  fill: var(--svg-color--961b1e, #961b1e);
  d: path("m24.59 20.05l1.37 4.54l.46 1.54l.18.6l.05.17a9 9 0 0 1 .34.97l.05.17l.12.27l.2.4l-.86-.49l-.15-.09l-.16-.1l-.58-.3l-.1-.06l-.33-.23l-.11.15l-.12.16a8 8 0 0 0-.87.96l-.1.11l-.42.56l-.01-.62l-.05-.32l-.1-.97l-.02-.17l-.85-6.26l.14-.07l.5 3.21l.27 1.61l.22 1.45l.03.14a9 9 0 0 0 .09 1.13c.21-.41.6-.62.87-.97l.08-.11l.34-.45l.55.34l.1.07c.3.17.67.27.97.44l-.33-.85l-.04-.12l-.25-.91l-.36-1.27l-1.27-4.56Z");
}

.of_hn-czv {
  stop-color: var(--svg-color--ec1c24, #ec1c24);
}

.onj9y3b7r {
  fill: var(--svg-color--f9d0e2, #f9d0e2);
  d: path("M19.8 22.4a1 1 0 0 0 .83.47a.7.7 0 0 1-.84-.47");
}

.ov6dpt_sk {
  stop-color: var(--svg-color--901b20, #901b20);
}

.p7usmobpj {
  stop-color: var(--svg-color--651116, #651116);
}

.phz_znelb {
  stop-color: var(--svg-color--6a1217, #6a1217);
}

.rsqa_q3xd {
  d: path("M21.84 23.42a1.8 1.8 0 0 0 1.86.32c.77-.18.86-.68 1.4-1.04c.45-.27.95-.05 1.18-.6c.13-.4-.19-.9.09-1.3c.31-.6.86-.6.9-1.37c.05-.81-.59-.9-.81-1.45c-.27-.5.09-.81-.32-1.31a6 6 0 0 0-2.17-1.65c-.68-.14-1.23.51-1.95.47s-1.32-.64-2.05-.37c-1.31.54-.62 2.14-1.03 3.18a2.4 2.4 0 0 0 .04 2.73a11 11 0 0 0 .73 1.49c.45.72.95.4 1.63.59a1 1 0 0 1 .5.31");
}

.s_dkhters {
  fill: var(--svg-color--ca4849, #ca4849);
  d: path("M26.19 21.5s.11.6-.26.82s-.41.11-.41.11a.7.7 0 0 0 .5-.27a1 1 0 0 0 .17-.66");
}

.s4osvzbyq {
  cx: 22.8px;
  cy: 19.3px;
  r: 2.95px;
}

.s6ptcvbbp {
  d: path("M26.07 18.32c-.05-.14-.05-.3-.1-.47a1.4 1.4 0 0 0-.32-.5a2 2 0 0 0-.5-.56c-.19-.15-.32-.39-.53-.48l-.5-.22a4 4 0 0 0-.48-.33a4 4 0 0 0-1.31-.03A3 3 0 0 0 20.18 17a7 7 0 0 0-.71 1a4 4 0 0 0-.21 1.04a4 4 0 0 0 .06 1.39c.15.6.68.92 1.07 1.37a4 4 0 0 0 .95.79a2 2 0 0 0 1.13.45a6 6 0 0 0 1.24-.14a3 3 0 0 0 1.12-.65c.35-.24.73-.16 1.23-1.52a6 6 0 0 0 .27-1.39a3 3 0 0 0-.26-1.02m-3.28 4.28a3.27 3.27 0 1 1 3.27-3.27a3.27 3.27 0 0 1-3.27 3.27");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.u3752-kvj {
  fill: var(--svg-color--fadae8, #fadae8);
  d: path("M26.6 18.4a1 1 0 0 1 .5.84a1.3 1.3 0 0 0-.4-.7s-.22-.16-.1-.14m-.4-1a.8.8 0 0 0-.3-.75a1 1 0 0 1 .3.75");
}

.u7ud6kw8w {
  fill: var(--svg-color--b12328, #b12328);
  d: path("M26.54 19.6c-.04.24-.13.58-.13.58a2 2 0 0 0 .17-.85c-.03-.16-.01 0-.04.26");
}

.uusljxola {
  fill: var(--svg-color--fadae8, #fadae8);
  d: path("M22.7 15.4s.8-.44 1.21-.21a1 1 0 0 0-.66.03a2 2 0 0 1-.55.18");
}

.v-c7v3amm {
  stop-color: var(--svg-color--ca4849, #ca4849);
}

.v4sbk-ezf {
  fill: var(--svg-color--54000d, #54000d);
  d: path("M21.5 16a4 4 0 0 1 2.16-.2s.38.21 0 .14a2.4 2.4 0 0 0-1.01-.14a4 4 0 0 0-1.12.25s-.1 0-.03-.05");
}

.v5avk9m2e {
  d: path("m15.92 6.33l-.43.03l.53-.04Zm.21 0a4 4 0 0 1 .74.08a4 4 0 0 0-.74-.08m-.75.04l-.2.04zm-.4.09l-.4.12zm1.99-.02l.2.04zm.4.1l.2.08zm.75.34l.17.1zm.17.1l.17.12zm-4.61.06l-.08.06Zm-.08.06l-.09.06Zm-.17.12l-.07.06Zm-.15.13l-.08.07Zm5.57.07l.11.1zm.15.14l.07.07Zm-6.15.22l-.13.15zm6.48.15l.12.16zm-6.73.16l-.06.09Zm-.06.09l-.05.08zm-.16.26l-.05.08zm-.1.17l-.04.1zm-.04.1l-.05.08Zm-.09.18l-.04.1zm-.04.1l-.03.1zm-.03.1l-.04.1zm-.07.2l-.03.1l.03-.11Zm-.08.29l-.02.1zm-.1 1.16a4.2 4.2 0 0 0 8.39 0c-.12 2.02-1.96.72-4.2.72s-4.07 1.3-4.19-.72");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vdtrmtbrd {
  stop-color: var(--svg-color--961b1e, #961b1e);
}

.vnttfnpsy {
  stop-color: var(--svg-color--b12328, #b12328);
}

.wu1ghvbzh {
  stop-color: var(--svg-color--831416, #831416);
}

.x-3nj3f9f {
  fill: var(--svg-color--f8cce0, #f8cce0);
  d: path("M18.8 19a2 2 0 0 0 .2 1.67s-.15-.55-.2-.7a2 2 0 0 1 0-.97");
}

.x783mccth {
  fill: var(--svg-color--651116, #651116);
  d: path("M23.6 23.15a3 3 0 0 1-.76.11c-.16 0-.63-.15-.02-.15a7 7 0 0 0 .99-.13s.34-.14.34-.13c.2.04-.16.2-.54.3");
}

.xzbfxlbzh {
  fill: var(--svg-color--651116, #651116);
  d: path("M25.06 22.18s.1.02.34-.18a3 3 0 0 0 .42-.53a5 5 0 0 1-.4.57c-.07.06-.25.19-.36.14");
}

.y3tm7z9wh {
  cx: 22.8px;
  cy: 19.3px;
  r: 3.01px;
}

.y4xoqgx3j {
  stop-color: var(--svg-color--6c0607, #6c0607);
}

.yv53qpbqe {
  stop-color: var(--svg-color--d9383c, #d9383c);
}

.zbd3civgx {
  stop-color: var(--svg-color--dfb300, #dfb300);
  stop-opacity: 0.39;
}

.zs_l3iwth {
  stop-color: var(--svg-color--dfb300, #dfb300);
}

</style>
