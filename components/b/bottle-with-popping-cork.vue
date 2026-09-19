<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iTH295u)" class="nnyixubrf"/><path fill="url(#iJWqjLd)" class="nnyixubrf"/><path fill="url(#iS1iXse)" class="nnyixubrf"/><path fill="url(#iKpWXfc)" class="nnyixubrf"/><path fill="url(#ikXvcMe)" class="nnyixubrf"/><path fill="url(#i6ousJb)" class="kol5zdxzk"/><path fill="url(#itiYiUd)" class="kol5zdxzk"/><path fill="url(#ibO30Wc)" class="kol5zdxzk"/><path fill="url(#i3Lqjed)" class="bxsldebec"/><path fill="url(#iF1pmtd)" class="bxsldebec"/><path fill="url(#iJabnzb)" class="bxsldebec"/><path fill="url(#i6JTzVc)" class="kvk-mjthj"/><path fill="url(#i1MugIe)" class="kvk-mjthj"/><path fill="url(#iSbC4lL)" class="dg8kcod6n"/><path fill="url(#iL17Y0O)" class="eeenfvb3x"/><path fill="url(#iAdkpQe)" class="eeenfvb3x"/><path fill="url(#iAD0aTd)" class="g70ju2buh"/><path class="cpe3ezb9o"/><path fill="url(#i6ktvyE)" class="ppwatosqz"/><path fill="url(#iYAJ6ld)" class="ppwatosqz"/><path fill="url(#i4kaffc)" class="ppwatosqz"/><path fill="url(#iEiqAFe)" class="ppwatosqz"/><path fill="url(#iCLXcIb)" class="ppwatosqz"/><path fill="url(#ickXrbc)" class="ppwatosqz"/><g filter="url(#iMpYv7b)"><path class="tprel9dxl"/><path fill="url(#ih2JQmb)" class="vifarx3ko"/><path fill="url(#imsVFeb)" class="vifarx3ko"/><path fill="url(#ixS4A1b)" class="vifarx3ko"/></g><path fill="url(#iiuLNgm)" class="ctg5jsbqh"/><path fill="url(#im6Z0Gc)" class="ctg5jsbqh"/><path fill="url(#icFUlje)" class="ctg5jsbqh"/><defs><radialGradient id="iS1iXse" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 -3.25 1.05814 .9157 21.75 30.813)" gradientUnits="userSpaceOnUse"><stop class="u74s7flnm"/><stop offset="1" class="xxg-kub3b"/></radialGradient><radialGradient id="iKpWXfc" cx="0" cy="0" r="1" gradientTransform="rotate(135 8.81 15.767)scale(4.33103 12.6026)" gradientUnits="userSpaceOnUse"><stop class="kk7d-_b8g"/><stop offset="1" class="rez4j3b7d"/></radialGradient><radialGradient id="ikXvcMe" cx="0" cy="0" r="1" gradientTransform="rotate(135 9.439 16.943)scale(3.88909 .30936)" gradientUnits="userSpaceOnUse"><stop class="fd963-9mn"/><stop offset="1" class="dy9exbbna"/></radialGradient><radialGradient id="ibO30Wc" cx="0" cy="0" r="1" gradientTransform="matrix(1.13814 2.03125 -2.58408 1.4479 10.688 15.969)" gradientUnits="userSpaceOnUse"><stop class="ib3q2ybtr"/><stop offset="1" class="r82rpf4wg"/></radialGradient><radialGradient id="iJabnzb" cx="0" cy="0" r="1" gradientTransform="matrix(.66064 1.625 -.6679 .27153 7.313 5.703)" gradientUnits="userSpaceOnUse"><stop offset=".476" class="jp3-3ac-e"/><stop offset="1" class="r2drccbug"/></radialGradient><radialGradient id="iSbC4lL" cx="0" cy="0" r="1" gradientTransform="rotate(128.797 5.007 5.329)scale(1.02245)" gradientUnits="userSpaceOnUse"><stop class="r3ed_ob6j"/><stop offset=".875" class="zfnmt9iil"/></radialGradient><radialGradient id="iL17Y0O" cx="0" cy="0" r="1" gradientTransform="rotate(128.797 -.065 7.12)scale(1.52605)" gradientUnits="userSpaceOnUse"><stop class="rn0e-2b9y"/><stop offset=".875" class="ibgd5n32p"/></radialGradient><radialGradient id="iAdkpQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09375 -2.62403 0 5 13.172)" gradientUnits="userSpaceOnUse"><stop class="mct920b-x"/><stop offset="1" class="fm4mk-bjs"/></radialGradient><radialGradient id="i4kaffc" cx="0" cy="0" r="1" gradientTransform="rotate(-135 6.885 2.878)scale(2.49697 4.76437)" gradientUnits="userSpaceOnUse"><stop class="to2dje9xb"/><stop offset=".389" class="jtsnikb3r"/><stop offset="1" class="v86q7_h_c"/></radialGradient><radialGradient id="iEiqAFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.42188 -.73438 0 8.938 3.469)" gradientUnits="userSpaceOnUse"><stop class="to2dje9xb"/><stop offset=".764" class="jtsnikb3r"/><stop offset="1" class="v86q7_h_c"/></radialGradient><radialGradient id="iCLXcIb" cx="0" cy="0" r="1" gradientTransform="matrix(3.29687 .01562 -.0074 1.56167 3.328 8.39)" gradientUnits="userSpaceOnUse"><stop class="to2dje9xb"/><stop offset=".673" class="jtsnikb3r"/><stop offset="1" class="v86q7_h_c"/></radialGradient><radialGradient id="ickXrbc" cx="0" cy="0" r="1" gradientTransform="matrix(.625 .92188 -.40206 .27258 8.078 4.734)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="qr8_y9bgj"/><stop offset="1" class="xx5chi1nw"/></radialGradient><radialGradient id="ixS4A1b" cx="0" cy="0" r="1" gradientTransform="rotate(-135 6.81 2.787)scale(2.36002 4.50306)" gradientUnits="userSpaceOnUse"><stop class="to2dje9xb"/><stop offset=".389" class="jtsnikb3r"/><stop offset="1" class="v86q7_h_c"/></radialGradient><radialGradient id="im6Z0Gc" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.637 6.156)scale(2.34229 .46404)" gradientUnits="userSpaceOnUse"><stop class="t9hhuibll"/><stop offset="1" class="qa5hjif_f"/></radialGradient><radialGradient id="icFUlje" cx="0" cy="0" r="1" gradientTransform="rotate(-45 17.72 -3.09)scale(2.20971 .5672)" gradientUnits="userSpaceOnUse"><stop class="f8egrjb5f"/><stop offset="1" class="z730pdbpt"/></radialGradient><linearGradient id="iTH295u" x1="25.938" x2="16.75" y1="16.625" y2="25.875" gradientUnits="userSpaceOnUse"><stop class="o76-iacrf"/><stop offset=".163" class="bv0xdssyv"/><stop offset=".498" class="s6hwe2bpk"/><stop offset=".824" class="dkzmn33mi"/><stop offset="1" class="a_e93n_1f"/></linearGradient><linearGradient id="iJWqjLd" x1="26" x2="25.313" y1="25.531" y2="24.844" gradientUnits="userSpaceOnUse"><stop offset=".386" class="us2qg0b8c"/><stop offset="1" class="nmg3u2bay"/></linearGradient><linearGradient id="i6ousJb" x1="9.563" x2="12.906" y1="12.875" y2="9.531" gradientUnits="userSpaceOnUse"><stop offset=".079" class="ep1z3f67z"/><stop offset=".36" class="zvyakmbzo"/><stop offset=".694" class="hva1haced"/><stop offset=".892" class="eh8fib09n"/></linearGradient><linearGradient id="itiYiUd" x1="14.875" x2="11.625" y1="15.188" y2="12.094" gradientUnits="userSpaceOnUse"><stop class="annm-_-hz"/><stop offset=".531" class="a93kbxblt"/><stop offset=".804" class="n91uxxbdv"/></linearGradient><linearGradient id="i3Lqjed" x1="4.781" x2="7.281" y1="7.281" y2="4.781" gradientUnits="userSpaceOnUse"><stop offset=".006" class="t6rx7dbpg"/><stop offset=".375" class="h2m47nb5t"/><stop offset=".688" class="wlr-6cdlm"/><stop offset="1" class="p0zznp_hc"/></linearGradient><linearGradient id="iF1pmtd" x1="5" x2="6.656" y1="4.813" y2="6.188" gradientUnits="userSpaceOnUse"><stop offset=".169" class="jx5faebvf"/><stop offset=".314" class="q3j2ejynx"/></linearGradient><linearGradient id="i6JTzVc" x1="1.495" x2="5.185" y1="5.12" y2="1.124" gradientUnits="userSpaceOnUse"><stop offset=".006" class="xbf3x459e"/><stop offset=".252" class="v4sx4s8qg"/><stop offset=".495" class="gwoldqbdy"/><stop offset=".731" class="r3q6_mbzd"/><stop offset=".897" class="i3ky28b1a"/><stop offset=".97" class="uirn8bc1v"/></linearGradient><linearGradient id="i1MugIe" x1="4.128" x2="4.815" y1="3.372" y2="4.06" gradientUnits="userSpaceOnUse"><stop class="sltt0b2_u"/><stop offset=".413" class="qnu_54ker"/></linearGradient><linearGradient id="iAD0aTd" x1="25.965" x2="19.895" y1="19.965" y2="26.02" gradientUnits="userSpaceOnUse"><stop class="zlv0dbboy"/><stop offset=".546" class="cipzdnb5j"/><stop offset="1" class="ah2orkuto"/></linearGradient><linearGradient id="i6ktvyE" x1="3.625" x2="3.625" y1="10.008" y2="9.25" gradientUnits="userSpaceOnUse"><stop class="zhod9777g"/><stop offset="1" class="x1dz1vbhz"/></linearGradient><linearGradient id="iYAJ6ld" x1="10.001" x2="9.219" y1="5.406" y2="5.406" gradientUnits="userSpaceOnUse"><stop offset=".381" class="y3cb16dtq"/><stop offset="1" class="uarturgfs"/></linearGradient><linearGradient id="ih2JQmb" x1="3.896" x2="3.896" y1="9.788" y2="9.072" gradientUnits="userSpaceOnUse"><stop class="zhod9777g"/><stop offset="1" class="x1dz1vbhz"/></linearGradient><linearGradient id="imsVFeb" x1="9.922" x2="9.183" y1="5.439" y2="5.439" gradientUnits="userSpaceOnUse"><stop offset=".381" class="y3cb16dtq"/><stop offset="1" class="uarturgfs"/></linearGradient><linearGradient id="iiuLNgm" x1="11.194" x2="7.473" y1="7.881" y2="11.284" gradientUnits="userSpaceOnUse"><stop class="dj8hmi71g"/><stop offset=".482" class="z929aibxr"/><stop offset="1" class="dl5i86g9r"/></linearGradient><filter id="iMpYv7b" width="8.492" height="8.507" x="1.765" y="1.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32608" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bottle-with-popping-cork" /></template>
<style>
.a_e93n_1f {
  stop-color: var(--svg-color--6f7c6f, #6F7C6F);
}

.a93kbxblt {
  stop-color: var(--svg-color--c89d5e, #C89D5E);
}

.ah2orkuto {
  stop-color: var(--svg-color--da8971, #DA8971);
}

.annm-_-hz {
  stop-color: var(--svg-color--cda164, #CDA164);
}

.bv0xdssyv {
  stop-color: var(--svg-color--66af3a, #66AF3A);
}

.bxsldebec {
  d: path("m7.89 5.928l-1.93 1.93c-.11.11-.28.11-.39 0l-1.89-1.9L6 3.638l1.89 1.9c.11.11.11.28 0 .39");
}

.cipzdnb5j {
  stop-color: var(--svg-color--e8ac7b, #E8AC7B);
}

.cpe3ezb9o {
  fill: var(--svg-color--e9d2c1, #E9D2C1);
  d: path("M9.47 2.008c-.27.02-.47.25-.47.52v2.66c0 .25-.32.34-.46.14l-.73-1.12c-.24-.36-.81-.19-.81.24v1.9c0 .37-.29.66-.65.66H5.06c-.39 0-.58.47-.31.75l.82.83c.16.15.05.42-.17.42H2.52c-.27 0-.5.2-.52.47c-.01.29.22.53.5.53h4.78l1.35-1.35L10 7.288v-4.78c0-.29-.24-.52-.53-.5");
}

.ctg5jsbqh {
  d: path("m10.07 7.218l-2.87 2.88c-.3.3-.29.8.02 1.11s.81.33 1.11.02l2.87-2.87c.3-.3.29-.8-.02-1.11c-.32-.32-.81-.33-1.11-.03");
}

.dg8kcod6n {
  d: path("M12 5.688a.67.67 0 1 0 0-1.34a.67.67 0 0 0 0 1.34");
}

.dj8hmi71g {
  stop-color: var(--svg-color--6ea34f, #6EA34F);
}

.dkzmn33mi {
  stop-color: var(--svg-color--567d3d, #567D3D);
}

.dl5i86g9r {
  stop-color: var(--svg-color--577f3c, #577F3C);
}

.dy9exbbna {
  stop-color: var(--svg-color--8dc96f, #8DC96F);
  stop-opacity: 0;
}

.eeenfvb3x {
  d: path("M5 13.008a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.eh8fib09n {
  stop-color: var(--svg-color--ffde8f, #FFDE8F);
}

.ep1z3f67z {
  stop-color: var(--svg-color--c98975, #C98975);
}

.f8egrjb5f {
  stop-color: var(--svg-color--868a93, #868A93);
}

.fd963-9mn {
  stop-color: var(--svg-color--86bd68, #86BD68);
}

.fm4mk-bjs {
  stop-color: var(--svg-color--ddb0ca, #DDB0CA);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g70ju2buh {
  d: path("m26.73 21.028l-5.74 5.75c-.12.12-.32.12-.44 0l-3.31-3.32a.314.314 0 0 1 0-.44l5.74-5.75c.12-.12.32-.12.44 0l3.31 3.32c.12.12.12.32 0 .44");
}

.gwoldqbdy {
  stop-color: var(--svg-color--e6b579, #E6B579);
}

.h2m47nb5t {
  stop-color: var(--svg-color--cb9666, #CB9666);
}

.hva1haced {
  stop-color: var(--svg-color--ffd38e, #FFD38E);
}

.i3ky28b1a {
  stop-color: var(--svg-color--ffe090, #FFE090);
}

.ib3q2ybtr {
  stop-color: var(--svg-color--b3875f, #B3875F);
}

.ibgd5n32p {
  stop-color: var(--svg-color--cdb49c, #CDB49C);
}

.jp3-3ac-e {
  stop-color: var(--svg-color--a97133, #A97133);
}

.jtsnikb3r {
  stop-color: var(--svg-color--c2b399, #C2B399);
}

.jx5faebvf {
  stop-color: var(--svg-color--ae7151, #AE7151);
}

.kk7d-_b8g {
  stop-color: var(--svg-color--7ab95a, #7AB95A);
}

.kol5zdxzk {
  d: path("M15.74 11.328c-.19-.01-.39-.01-.59-.01c-.46 0-.91-.18-1.23-.51L11 7.888l-3.09 3.1l2.91 2.92c.33.33.51.77.51 1.24c0 .2 0 .39.01.59l3.17-.44c.41-.06.73-.38.79-.79z");
}

.kvk-mjthj {
  d: path("M6.89 3.608L3.6 6.898c-.16.16-.41.17-.57.01l-.92-.92a.41.41 0 0 1 .01-.57l3.28-3.29c.16-.16.41-.17.57-.01l.93.93c.15.15.15.4-.01.56");
}

.mct920b-x {
  stop-color: var(--svg-color--dbadc9, #DBADC9);
}

.n91uxxbdv {
  stop-color: var(--svg-color--c89d5e, #C89D5E);
  stop-opacity: 0;
}

.nmg3u2bay {
  stop-color: var(--svg-color--609041, #609041);
  stop-opacity: 0;
}

.nnyixubrf {
  d: path("M29.73 21.768c.36-.36.36-.96 0-1.32l-5.34-5.34a12.97 12.97 0 0 0-9.24-3.8c-.46 0-.91-.18-1.23-.51l-2.58-2.57l-3.09 3.09l2.58 2.58c.33.33.51.77.51 1.24c-.02 3.47 1.34 6.8 3.79 9.25l5.34 5.34c.36.36.95.36 1.32 0z");
}

.o76-iacrf {
  stop-color: var(--svg-color--76b957, #76B957);
}

.p0zznp_hc {
  stop-color: var(--svg-color--e1b06c, #E1B06C);
}

.ppwatosqz {
  d: path("M9.47 2.008c-.27.02-.47.25-.47.52v2.66c0 .25-.32.34-.46.14l-.73-1.12c-.24-.36-.81-.19-.81.24v1.9c0 .37-.29.66-.65.66H5.06c-.39 0-.58.47-.31.75l.82.83c.16.15.05.42-.17.42H2.52c-.27 0-.5.2-.52.47c-.01.29.22.53.5.53h4.78l1.35-1.35L10 7.288v-4.78c0-.29-.24-.52-.53-.5");
}

.q3j2ejynx {
  stop-color: var(--svg-color--b27251, #B27251);
  stop-opacity: 0;
}

.qa5hjif_f {
  stop-color: var(--svg-color--86b669, #86B669);
  stop-opacity: 0;
}

.qnu_54ker {
  stop-color: var(--svg-color--af935d, #AF935D);
  stop-opacity: 0;
}

.qr8_y9bgj {
  stop-color: var(--svg-color--fce7cd, #FCE7CD);
}

.r2drccbug {
  stop-color: var(--svg-color--ad7436, #AD7436);
  stop-opacity: 0;
}

.r3ed_ob6j {
  stop-color: var(--svg-color--fff2d7, #FFF2D7);
}

.r3q6_mbzd {
  stop-color: var(--svg-color--ffdd92, #FFDD92);
}

.r82rpf4wg {
  stop-color: var(--svg-color--b68860, #B68860);
  stop-opacity: 0;
}

.rez4j3b7d {
  stop-color: var(--svg-color--7eb960, #7EB960);
  stop-opacity: 0;
}

.rn0e-2b9y {
  stop-color: var(--svg-color--f3dbc9, #F3DBC9);
}

.s6hwe2bpk {
  stop-color: var(--svg-color--5b9636, #5B9636);
}

.sltt0b2_u {
  stop-color: var(--svg-color--b1965e, #B1965E);
}

.t6rx7dbpg {
  stop-color: var(--svg-color--b4855e, #B4855E);
}

.t9hhuibll {
  stop-color: var(--svg-color--85b569, #85B569);
}

.to2dje9xb {
  stop-color: var(--svg-color--aea182, #AEA182);
}

.tprel9dxl {
  fill: var(--svg-color--e9d2c1, #E9D2C1);
  d: path("M9.5 2.281c-.258 0-.262.163-.262.418v2.515c0 .439-.697.705-.886.314L7.664 4.45c-.227-.34-.46-.166-.46.09v1.706c0 .645-.141.971-.732.971h-1.22c-.238 0-.42.169-.238.35l.775.785c.266.234.396.92-.28.92H2.787c-.255 0-.502-.027-.521.228c-.01.274.303.288.567.288h4.518l1.276-1.276l1.13-1.295V2.7c0-.274 0-.418-.257-.418");
}

.u74s7flnm {
  stop-color: var(--svg-color--6a7866, #6A7866);
}

.uarturgfs {
  stop-color: var(--svg-color--fbe4cd, #FBE4CD);
  stop-opacity: 0;
}

.uirn8bc1v {
  stop-color: var(--svg-color--ecd399, #ECD399);
}

.us2qg0b8c {
  stop-color: var(--svg-color--587d41, #587D41);
}

.v4sx4s8qg {
  stop-color: var(--svg-color--d09568, #D09568);
}

.v86q7_h_c {
  stop-color: var(--svg-color--aea182, #AEA182);
  stop-opacity: 0;
}

.vifarx3ko {
  d: path("M9.5 2.281c-.258 0-.262.163-.262.418v2.515c0 .439-.697.705-.886.314L7.664 4.45c-.227-.34-.46-.166-.46.09v1.706c0 .645-.141.971-.732.971h-1.22c-.238 0-.42.169-.238.35l.775.785c.266.234.396.92-.28.92H2.787c-.255 0-.502-.027-.521.228c-.01.274.303.288.567.288h4.518l1.276-1.276l1.13-1.295V2.7c0-.274 0-.418-.257-.418");
}

.wlr-6cdlm {
  stop-color: var(--svg-color--e9b87f, #E9B87F);
}

.x1dz1vbhz {
  stop-color: var(--svg-color--dfbbbf, #DFBBBF);
  stop-opacity: 0;
}

.xbf3x459e {
  stop-color: var(--svg-color--be8766, #BE8766);
}

.xx5chi1nw {
  stop-color: var(--svg-color--fde8cf, #FDE8CF);
  stop-opacity: 0;
}

.xxg-kub3b {
  stop-color: var(--svg-color--609143, #609143);
  stop-opacity: 0;
}

.y3cb16dtq {
  stop-color: var(--svg-color--ffeed4, #FFEED4);
}

.z730pdbpt {
  stop-color: var(--svg-color--7a7b86, #7A7B86);
  stop-opacity: 0;
}

.z929aibxr {
  stop-color: var(--svg-color--538728, #538728);
}

.zfnmt9iil {
  stop-color: var(--svg-color--d3bba1, #D3BBA1);
}

.zhod9777g {
  stop-color: var(--svg-color--d2a9be, #D2A9BE);
}

.zlv0dbboy {
  stop-color: var(--svg-color--ffde96, #FFDE96);
}

.zvyakmbzo {
  stop-color: var(--svg-color--d89e70, #D89E70);
}

</style>
