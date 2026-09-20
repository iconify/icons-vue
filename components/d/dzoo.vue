<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGlNUqzdjP)" class="rlctw3o0z"/><path class="vdrqohb7f"/><path fill="url(#SVGAnhFFeBc)" class="am-e6ybcq"/><path class="vqlh0rbyo"/><path fill="url(#SVGSOmHZgCQ)" class="m-x9yiboc"/><path fill="url(#SVGuOOahcHz)" class="o3dyly15g"/><path fill="url(#SVGikAvVdZy)" class="n_vv0sboz"/><path fill="url(#SVG5Dv3gcFV)" class="ksv2hub7x"/><path fill="url(#SVGPhAqbcxP)" class="k-itgdc6y"/><path fill="url(#SVGKUdzgeGl)" class="qup6ksdrx"/><path fill="url(#SVGkjcxCeBf)" class="piecvvm6k"/><path fill="url(#SVG6Fu60dmQ)" class="erp9-cc0j"/><path fill="url(#SVGasS48HBd)" class="oxnok3bkw"/><path fill="url(#SVG5NAjsbbK)" class="aopail87m"/><path fill="url(#SVGy5kc2d5G)" class="lk60fqb0n"/><path fill="url(#SVGwb1RCd5b)" class="pl5enqqlk"/><path fill="url(#SVGb6cc0dKx)" class="rp3zldwpu"/><path fill="url(#SVG4vok6Bkd)" class="qn811-mcf"/><path fill="url(#SVGf5cSRd3t)" class="uabkfbd2z"/><path fill="url(#SVG4vok6Bkd)" class="vpo5y7b6t"/><path fill="url(#SVGlmrWicEj)" class="h8lel9bfa"/><path fill="url(#SVG8ZrxxeTk)" class="srqf-ebyw"/><path fill="url(#SVGTomcEcMs)" class="nvn0e1tpb"/><path fill="url(#SVG7V5lW49N)" class="s52o8nd8j"/><path fill="url(#SVGsKe0eegM)" class="mezo3jb8h"/><path fill="url(#SVGgtr15NyZ)" class="ogf5lebvo"/><path fill="url(#SVGpW8i6cNt)" class="u5vhrp22c"/><path fill="url(#SVGp00DudRj)" class="k34-64bko"/><path fill="url(#SVGW10rrcIj)" class="iuot8tpcw"/><path fill="url(#SVGTzHEvd9y)" class="nmo2w3b_z"/><path fill="url(#SVGkBLnWdBv)" class="esd95bcyo"/><path fill="url(#SVGqUknVd3Y)" class="rxtnevjhh"/><path fill="url(#SVGaTKBFblj)" class="lerw5lbbo"/><path fill="url(#SVGakF7bUgs)" class="ld19cc3vm"/><path fill="url(#SVGVDkG7dVl)" class="ytf1mac0d"/><path fill="url(#SVGVDkG7dVl)" class="tz610ab8z"/><path fill="url(#SVGMLOZoIAw)" class="u0i3ggt4c"/><path fill="url(#SVGku1XFYYN)" class="kj03ylbvt"/><path class="lbvev1e5a"/><defs><linearGradient id="SVGlNUqzdjP" x1="16.963" x2="12.812" y1="4.287" y2="21.599" gradientUnits="userSpaceOnUse"><stop class="zd_oy2bcr"/><stop offset="1" class="sjwpadc1w"/></linearGradient><linearGradient id="SVGAnhFFeBc" x1="7.037" x2="11.188" y1="4.287" y2="21.599" gradientUnits="userSpaceOnUse"><stop class="zd_oy2bcr"/><stop offset="1" class="sjwpadc1w"/></linearGradient><linearGradient id="SVGSOmHZgCQ" x1="11.976" x2="11.976" y1="3" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="gg6-d6d7t"/><stop offset="1" class="g10mofb-v"/></linearGradient><linearGradient id="SVGuOOahcHz" x1="7.308" x2="8.035" y1="3.692" y2="21.171" gradientUnits="userSpaceOnUse"><stop class="cfuxozbaa"/><stop offset="1" class="uen05e_tz"/></linearGradient><linearGradient id="SVGikAvVdZy" x1="12.557" x2="12.557" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="ar-rekq5g"/><stop offset="1" class="stmc-f_0k"/></linearGradient><linearGradient id="SVG5Dv3gcFV" x1="12" x2="12" y1="3" y2="20.95" gradientUnits="userSpaceOnUse"><stop class="q71ze8c3q"/><stop offset="1" class="qk9r03bjd"/></linearGradient><linearGradient id="SVGPhAqbcxP" x1="15.614" x2="15.614" y1="2.052" y2="20.053" gradientUnits="userSpaceOnUse"><stop class="ar-rekq5g"/><stop offset="1" class="stmc-f_0k"/></linearGradient><linearGradient id="SVGKUdzgeGl" x1="15.644" x2="15.644" y1="2.055" y2="20.005" gradientUnits="userSpaceOnUse"><stop class="q71ze8c3q"/><stop offset="1" class="qk9r03bjd"/></linearGradient><linearGradient id="SVGkjcxCeBf" x1="5.007" x2="9.381" y1="4.126" y2="22.655" gradientUnits="userSpaceOnUse"><stop class="go__dabhm"/><stop offset="1" class="qr1dcfdvd"/></linearGradient><linearGradient id="SVG6Fu60dmQ" x1="12.001" x2="12.001" y1="3.001" y2="21.002" gradientUnits="userSpaceOnUse"><stop class="e75cwpepz"/><stop offset=".57" class="dhqver70j"/><stop offset="1" class="k-ro4xbwj"/></linearGradient><linearGradient id="SVGasS48HBd" x1="12" x2="12" y1="2.999" y2="21" gradientUnits="userSpaceOnUse"><stop class="qb3t1zgzw"/><stop offset="1" class="pvxcglwsz"/></linearGradient><linearGradient id="SVG5NAjsbbK" x1="11.985" x2="11.985" y1="2.999" y2="21" gradientUnits="userSpaceOnUse"><stop class="qb3t1zgzw"/><stop offset="1" class="pvxcglwsz"/></linearGradient><linearGradient id="SVGy5kc2d5G" x1="22.8" x2="18.43" y1="3.001" y2="21.532" gradientUnits="userSpaceOnUse"><stop class="go__dabhm"/><stop offset="1" class="qr1dcfdvd"/></linearGradient><linearGradient id="SVGwb1RCd5b" x1="16.717" x2="16.717" y1="2.183" y2="20.184" gradientUnits="userSpaceOnUse"><stop class="e75cwpepz"/><stop offset=".57" class="dhqver70j"/><stop offset="1" class="k-ro4xbwj"/></linearGradient><linearGradient id="SVGb6cc0dKx" x1="12.56" x2="12.56" y1="21.001" y2="3" gradientUnits="userSpaceOnUse"><stop class="ar-rekq5g"/><stop offset="1" class="stmc-f_0k"/></linearGradient><linearGradient id="SVG4vok6Bkd" x1="12.001" x2="12.001" y1="21.002" y2="3.051" gradientUnits="userSpaceOnUse"><stop class="q71ze8c3q"/><stop offset="1" class="qk9r03bjd"/></linearGradient><linearGradient id="SVGf5cSRd3t" x1="11.438" x2="11.438" y1="21.001" y2="3" gradientUnits="userSpaceOnUse"><stop class="ar-rekq5g"/><stop offset="1" class="stmc-f_0k"/></linearGradient><linearGradient id="SVGlmrWicEj" x1="5.008" x2="9.381" y1="19.876" y2="1.347" gradientUnits="userSpaceOnUse"><stop class="go__dabhm"/><stop offset="1" class="qr1dcfdvd"/></linearGradient><linearGradient id="SVG8ZrxxeTk" x1="8.314" x2="8.314" y1="21.001" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="e75cwpepz"/><stop offset=".57" class="dhqver70j"/><stop offset="1" class="k-ro4xbwj"/></linearGradient><linearGradient id="SVGTomcEcMs" x1="18.992" x2="14.601" y1="19.876" y2="1.338" gradientUnits="userSpaceOnUse"><stop class="go__dabhm"/><stop offset="1" class="qr1dcfdvd"/></linearGradient><linearGradient id="SVG7V5lW49N" x1="16.028" x2="16.028" y1="21" y2="3.782" gradientUnits="userSpaceOnUse"><stop class="e75cwpepz"/><stop offset=".57" class="dhqver70j"/><stop offset="1" class="k-ro4xbwj"/></linearGradient><linearGradient id="SVGsKe0eegM" x1="6.277" x2="8.615" y1="5.249" y2="20.562" gradientUnits="userSpaceOnUse"><stop class="s42fl-rge"/><stop offset="1" class="gubra6bru"/></linearGradient><linearGradient id="SVGgtr15NyZ" x1="3.881" x2="10.569" y1="2.999" y2="21.218" gradientUnits="userSpaceOnUse"><stop class="vzdaiw3gp"/><stop offset="1" class="cwv022bmm"/></linearGradient><linearGradient id="SVGpW8i6cNt" x1="22.431" x2="20.472" y1="5.251" y2="20.672" gradientUnits="userSpaceOnUse"><stop class="s42fl-rge"/><stop offset="1" class="gubra6bru"/></linearGradient><linearGradient id="SVGp00DudRj" x1="26.228" x2="19.564" y1="3.001" y2="21.208" gradientUnits="userSpaceOnUse"><stop class="vzdaiw3gp"/><stop offset="1" class="cwv022bmm"/></linearGradient><linearGradient id="SVGW10rrcIj" x1="12.077" x2="12.76" y1="4.424" y2="20.998" gradientUnits="userSpaceOnUse"><stop class="zlnb847tl"/><stop offset="1" class="nuge_62tr"/></linearGradient><linearGradient id="SVGTzHEvd9y" x1="11.625" x2="15.36" y1="5.251" y2="18.86" gradientUnits="userSpaceOnUse"><stop class="soz6-2b8n"/><stop offset="1" class="y42wg_70z"/></linearGradient><linearGradient id="SVGkBLnWdBv" x1="17.894" x2="6.751" y1="3" y2="22.698" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGqUknVd3Y" x1="17.893" x2="6.75" y1="3" y2="22.698" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGaTKBFblj" x1="13.651" x2="5.007" y1="9" y2="23.262" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGakF7bUgs" x1="13.65" x2="5.006" y1="9" y2="23.262" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGVDkG7dVl" x1="16.125" x2="6.849" y1="9" y2="21.755" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGMLOZoIAw" x1="12" x2="12" y1="3.001" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="oxiqkcc3j"/><stop offset="1" class="pawc61baq"/></linearGradient><linearGradient id="SVGku1XFYYN" x1="15.894" x2="15.894" y1="0" y2="15.001" gradientUnits="userSpaceOnUse"><stop class="lo6mxgbwa"/><stop offset="1" class="zsyheeapr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dzoo" /></template>
<style>
.am-e6ybcq {
  d: path("M4.814 11.501c.615 0 1.065.335 1.065.5c-.445 0-1.33.2-1.33 1s1.24 1.665 1.86 2c-1.06 0-2.66-.75-2.66-2c0-.94.53-1.5 1.065-1.5");
}

.aopail87m {
  d: path("M13.866 19.75c.54-.51.975-2 1.065-2.75H12.8l-.535 4c.535-.75 1.065-.75 1.6-1.25");
}

.ar-rekq5g {
  stop-color: var(--svg-color--0d827c, #0d827c);
}

.btkh0pb0v {
  stop-color: var(--svg-color--394f51, #394f51);
}

.cfuxozbaa {
  stop-color: var(--svg-color--8ecb63, #8ecb63);
}

.cwv022bmm {
  stop-color: var(--svg-color--42a77f, #42a77f);
}

.dhqver70j {
  stop-color: var(--svg-color--4ab67c, #4ab67c);
}

.e75cwpepz {
  stop-color: var(--svg-color--6eb374, #6eb374);
}

.erp9-cc0j {
  d: path("M6.945 11.002c-1.92-1.6-.8-4.335 0-5.5c-.425 2.4.35 3.665.8 4z");
}

.esd95bcyo {
  d: path("M7.25 13.25v-.5L8.5 11H9z");
}

.ev6eq1min {
  stop-color: var(--svg-color--374d50, #374d50);
  stop-opacity: 0.08;
}

.ft5dv1b6b {
  fill: none;
}

.g10mofb-v {
  stop-color: var(--svg-color--76be62, #76be62);
}

.gg6-d6d7t {
  stop-color: var(--svg-color--0e9284, #0e9284);
}

.go__dabhm {
  stop-color: var(--svg-color--199584, #199584);
}

.gubra6bru {
  stop-color: var(--svg-color--1d9b85, #1d9b85);
}

.h8lel9bfa {
  d: path("M9.065 15.501c-.85.6-1.775 2.585-2.125 3.5c-.64-1.8.62-3.415 1.33-4l.8.5z");
}

.iuot8tpcw {
  d: path("M7 10.975c0-.975.916-2.9 2.986-2.9L9.41 7.5c.865.1 2.015.5 2.84 1c.675-.5 1.62-.77 3-1l-.5.58a3.17 3.17 0 0 1 2.75 2.895c0 .675-.15 2.2-1.765 2.895c.385.095 1.015.47 1.015 1.63c0 1.45-2.25 3-4.5 3c-1.725 0-4-.974-4-3c0-1.385.45-1.665.82-1.655c-.96-.17-2.305-.97-2.07-2.87");
}

.k-itgdc6y {
  d: path("M13.33 8.5c.85-1 1.24-3.25 1.33-4.25c1.6 1.75.354 3.835-.266 4.75z");
}

.k-ro4xbwj {
  stop-color: var(--svg-color--74b960, #74b960);
}

.k34-64bko {
  d: path("M16.791 9.752a6.75 6.75 0 0 0 2.13-2a3.85 3.85 0 0 1-1.6 3.5z");
}

.kj03ylbvt {
  d: path("M12.285 15.5c-.35 0-.96.585-1.105.75c.215.5.64.75 1.07.75s.855-.25 1.07-.75c-.15-.165-.68-.75-1.035-.75");
}

.ksv2hub7x {
  d: path("M7.475 7c.215-1.4 1.685-2.415 2.4-2.75c-1.495 1.6-.8 3.835-.27 4.75c0 0-.325.03-.535 0c-1.025-.14-1.595-2-1.595-2");
}

.lbvev1e5a {
  fill: var(--svg-color--020207, #020207);
  d: path("M11.516 14.501h.535s-.355-.5-.536-.5c-.174 0-.264.11-.264.25s.09.25.264.25m1.515 0h-.53s.355-.5.53-.5c.18 0 .27.11.27.25s-.09.25-.27.25");
}

.ld19cc3vm {
  d: path("M14.25 14v-.5l2-2.5h.5z");
}

.lerw5lbbo {
  d: path("M7.25 14v-.5l2-2.5h.5z");
}

.lk60fqb0n {
  d: path("M15.46 9.002c.85-.6 1.775-2.585 2.13-3.5c.636 1.8-.62 3.415-1.33 4z");
}

.lo6mxgbwa {
  stop-color: var(--svg-color--5c1b15, #5c1b15);
}

.m-x9yiboc {
  d: path("M9.87 5.75c.425-.4 1.775-2 2.4-2.75v2l-.8 4.5c-.71-1.085-2.025-3.35-1.6-3.75");
}

.mezo3jb8h {
  d: path("M5.35 8c-1.92 3.2.53 6 2.125 6l-.53-1.5c-1.28-.4-1.6-3.165-1.6-4.5z");
}

.n_vv0sboz {
  d: path("M11.2 8.5c-.85-1-1.24-3.25-1.33-4.25C8.27 6 9.52 8.085 10.135 9z");
}

.nmo2w3b_z {
  d: path("M7.75 10.5c-.88 0-1 .501-1 .751c0 1.4 0 3.25.825 3.25h1.65c1.375 0 1.925-2.25 3.025-2.25c1.27 0 1.29 1.985 2.75 2.25h1.65c1.1 0 1.1-2.5 1.1-3.25c0-.6-.635-.75-1-.75H14.5c-.5 0-1.59 1-2.25 1s-1.5-1-2.2-1z");
}

.nuge_62tr {
  stop-color: var(--svg-color--af888b, #af888b);
}

.nvn0e1tpb {
  d: path("M15.46 15.501c.85.6 1.775 2.585 2.13 3.5c.64-1.8-.62-3.415-1.33-4z");
}

.o3dyly15g {
  d: path("M14.66 5.75c-.424-.4-1.774-2-2.394-2.75v2l.8 4.5c.71-1.085 2.02-3.35 1.6-3.75z");
}

.ogf5lebvo {
  d: path("M7.474 10a6.75 6.75 0 0 1-2.13-2a3.85 3.85 0 0 0 1.6 3.5z");
}

.oxiqkcc3j {
  stop-color: var(--svg-color--021b1f, #021b1f);
}

.oxnok3bkw {
  d: path("M10.67 19.75c-.545-.51-.975-2-1.065-2.75h2.13l.53 4c-.53-.75-1.065-.75-1.595-1.25");
}

.pawc61baq {
  stop-color: var(--svg-color--0b1110, #0b1110);
}

.piecvvm6k {
  d: path("M9.069 9.002c-.85-.6-1.77-2.585-2.125-3.5c-.64 1.8.62 3.415 1.33 4l.8-.5z");
}

.pl5enqqlk {
  d: path("M17.591 11.002c1.915-1.6.8-4.335 0-5.5c.425 2.4-.355 3.665-.8 4z");
}

.pvxcglwsz {
  stop-color: var(--svg-color--acda5f, #acda5f);
}

.q71ze8c3q {
  stop-color: var(--svg-color--70ab6b, #70ab6b);
}

.qb3t1zgzw {
  stop-color: var(--svg-color--12837f, #12837f);
}

.qk9r03bjd {
  stop-color: var(--svg-color--2ea881, #2ea881);
}

.qn811-mcf {
  d: path("M7.47 17.501c.21 1.4 1.686 2.416 2.396 2.75c-1.49-1.6-.8-3.835-.265-4.75c0 0-.33-.03-.535 0c-1.03.14-1.6 2-1.6 2z");
}

.qr1dcfdvd {
  stop-color: var(--svg-color--6ab562, #6ab562);
}

.qup6ksdrx {
  d: path("M17.056 7c-.21-1.4-1.685-2.415-2.395-2.75c1.49 1.6.8 3.835.264 4.75c0 0 .33.03.536 0c1.03-.14 1.6-2 1.6-2z");
}

.rlctw3o0z {
  d: path("M19.186 11.501c-.615 0-1.065.335-1.065.5c.445 0 1.33.2 1.33 1s-1.24 1.665-1.86 2c1.06 0 2.66-.75 2.66-2c0-.94-.53-1.5-1.065-1.5");
}

.rp3zldwpu {
  d: path("M11.194 16c-.85 1-1.24 3.25-1.33 4.25c-1.6-1.75-.355-3.834.265-4.75z");
}

.rxtnevjhh {
  d: path("M14.25 13.25v-.5L15.5 11h.5z");
}

.s42fl-rge {
  stop-color: var(--svg-color--84ba5d, #84ba5d);
}

.s52o8nd8j {
  d: path("M17 13.25c1.915 1.6 1.385 4.585.59 5.75c.425-2.4-1.15-4.665-1.59-5z");
}

.sjwpadc1w {
  stop-color: var(--svg-color--158885, #158885);
}

.soz6-2b8n {
  stop-color: var(--svg-color--041d21, #041d21);
}

.srqf-ebyw {
  d: path("M7.25 13c-1.915 1.6-1.11 4.836-.315 6c-.425-2.4 1.37-4.664 1.815-5z");
}

.stmc-f_0k {
  stop-color: var(--svg-color--58b56e, #58b56e);
}

.tz610ab8z {
  d: path("M15 14h-.5l2.5-3h.5z");
}

.u0i3ggt4c {
  d: path("M13.25 15.001h-2c-.5 0-.5.285-.5.57s.5 1.43 1.5 1.43s1.5-.855 1.5-1.43c0-.455-.335-.57-.5-.57");
}

.u5vhrp22c {
  d: path("M18.92 7.752c1.915 3.2-.265 5.335-1.6 6v-1.5c1.28-.4 1.6-3.165 1.6-4.5");
}

.uabkfbd2z {
  d: path("M13.33 16c.85 1 1.24 3.25 1.33 4.25c1.6-1.75.354-3.834-.266-4.75z");
}

.uen05e_tz {
  stop-color: var(--svg-color--4dba76, #4dba76);
}

.vdrqohb7f {
  fill: var(--svg-color--bba1a2, #bba1a2);
  d: path("M19.45 13c0-1-.884-1.084-1.33-1v1.25c.641 0 .8.166.8.25h-.264c-.215.4-.8.666-1.065.75V15c.62-.25 1.86-1 1.86-2");
}

.vpo5y7b6t {
  d: path("M17.056 17.501c-.21 1.4-1.685 2.416-2.395 2.75c1.49-1.6.8-3.835.264-4.75c0 0 .33-.03.536 0c1.03.14 1.6 2 1.6 2z");
}

.vqlh0rbyo {
  fill: var(--svg-color--bba1a2, #bba1a2);
  d: path("M4.549 13c0-1 .885-1.084 1.33-1v1.25c-.64 0-.8.166-.8.25h.265c.215.4.8.666 1.065.75V15c-.62-.25-1.86-1-1.86-2");
}

.vzdaiw3gp {
  stop-color: var(--svg-color--108a82, #108a82);
}

.y42wg_70z {
  stop-color: var(--svg-color--050306, #050306);
}

.ytf1mac0d {
  d: path("M8 14h-.5l2.5-3h.5z");
}

.zd_oy2bcr {
  stop-color: var(--svg-color--7bcc73, #7bcc73);
}

.zlnb847tl {
  stop-color: var(--svg-color--efe6e7, #efe6e7);
}

.zsyheeapr {
  stop-color: var(--svg-color--2e0002, #2e0002);
}

</style>
