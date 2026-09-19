<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i2umaye)" class="i-eyivc5o"/><path fill="url(#ihuABIp)" class="i-eyivc5o"/><path fill="url(#ir5d2Ad)" class="i-eyivc5o"/><path fill="url(#iHIpPte)" class="mjoi0zlyv"/><path fill="url(#ioWYaWd)" class="mjoi0zlyv"/><path fill="url(#iIZAuZd)" class="mjoi0zlyv"/><path fill="url(#iwI1alG)" class="mjoi0zlyv"/><path fill="url(#im8vzRx)" class="kpfnqma8k"/><path fill="url(#iGR0rCc)" class="kpfnqma8k"/><path fill="url(#iWbIYde)" class="ar5mg6bff"/><path fill="url(#iZntnJx)" class="ar5mg6bff"/><path fill="url(#iSPJDab)" class="bm_9uv1ob"/><path fill="url(#isIDL7c)" class="p965c5b4h"/><path fill="url(#iYwpyPe)" class="p965c5b4h"/><path fill="url(#i9fmcSb)" class="qhg0gj_ik"/><path fill="url(#iUHyQye)" class="qhg0gj_ik"/><path fill="url(#iftZcmc)" class="b2cwfbc3t"/><path fill="url(#iuf4O9c)" class="b2cwfbc3t"/><defs><linearGradient id="i2umaye" x1="13.125" x2="4.5" y1="4.375" y2="12.938" gradientUnits="userSpaceOnUse"><stop class="re12ppbvb"/><stop offset=".284" class="y4p65pbjf"/><stop offset=".593" class="ub97nqbtb"/><stop offset="1" class="x93y-db6v"/></linearGradient><linearGradient id="ihuABIp" x1="7.375" x2="8" y1="7.938" y2="8.531" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hyhexab3w"/><stop offset="1" class="v7p1v6wkr"/></linearGradient><linearGradient id="ir5d2Ad" x1="8.618" x2="9.173" y1="9.039" y2="9.594" gradientUnits="userSpaceOnUse"><stop class="n42jcxqfj"/><stop offset="1" class="pqqvllgyy"/></linearGradient><linearGradient id="iHIpPte" x1="2.234" x2="8.188" y1="1.797" y2="7.75" gradientUnits="userSpaceOnUse"><stop class="d5427s0ky"/><stop offset=".468" class="j7bn3_b0h"/><stop offset=".597" class="oy50t7b7y"/><stop offset=".801" class="np1x88boa"/><stop offset="1" class="mhnzf1b2h"/></linearGradient><linearGradient id="iIZAuZd" x1="7.438" x2="3.563" y1="7.188" y2="11.063" gradientUnits="userSpaceOnUse"><stop class="xr_g0c4hx"/><stop offset="1" class="h65k8lecm"/></linearGradient><linearGradient id="im8vzRx" x1="29.438" x2="4.005" y1="17.02" y2="17.02" gradientUnits="userSpaceOnUse"><stop class="aevb77_jh"/><stop offset=".57" class="rmo6chb3y"/><stop offset=".84" class="m_afvbcsj"/><stop offset="1" class="mk2-prbpa"/></linearGradient><linearGradient id="iGR0rCc" x1="16.997" x2="13.5" y1="13.063" y2="29.188" gradientUnits="userSpaceOnUse"><stop offset=".207" class="jlix6cbrg"/><stop offset=".743" class="f7qu2db-r"/></linearGradient><linearGradient id="iWbIYde" x1="19.5" x2="7.875" y1="7.5" y2="19.25" gradientUnits="userSpaceOnUse"><stop offset=".038" class="ipepvwb2z"/><stop offset=".199" class="mbd1kjgep"/><stop offset=".375" class="mbd1kjgep"/><stop offset=".687" class="t13fuubzs"/><stop offset="1" class="vzzlahrrd"/></linearGradient><linearGradient id="iZntnJx" x1="15.188" x2="14.063" y1="16.375" y2="14.188" gradientUnits="userSpaceOnUse"><stop offset=".195" class="yh_qrxbgx"/><stop offset="1" class="by828gc2p"/></linearGradient><linearGradient id="iSPJDab" x1="13.625" x2="25.5" y1="25.438" y2="13.25" gradientUnits="userSpaceOnUse"><stop class="x9j5otkqg"/><stop offset=".689" class="wxex9jbyf"/><stop offset="1" class="zr97_pbek"/></linearGradient><linearGradient id="isIDL7c" x1="10.375" x2="11.688" y1="15.313" y2="16.563" gradientUnits="userSpaceOnUse"><stop offset=".078" class="hih46v2-g"/><stop offset=".315" class="gzmvuubcg"/><stop offset=".65" class="o-2-s4rxz"/><stop offset="1" class="zpw-7tbog"/></linearGradient><linearGradient id="i9fmcSb" x1="13.711" x2="15.024" y1="18.585" y2="19.835" gradientUnits="userSpaceOnUse"><stop offset=".078" class="rhxamkbua"/><stop offset=".315" class="aniqhhxhj"/><stop offset=".65" class="q_1gaeqid"/><stop offset="1" class="okmtq6b2b"/></linearGradient><linearGradient id="iftZcmc" x1="16.976" x2="18.286" y1="21.965" y2="23.215" gradientUnits="userSpaceOnUse"><stop offset=".078" class="ngivbxbdb"/><stop offset=".315" class="s7pqihvog"/><stop offset=".65" class="d-v169bwu"/><stop offset="1" class="omgysj11p"/></linearGradient><radialGradient id="ioWYaWd" cx="0" cy="0" r="1" gradientTransform="rotate(45 -.333 13.706)scale(2.56326 7.62351)" gradientUnits="userSpaceOnUse"><stop class="t6rc9ffaf"/><stop offset=".42" class="r6urzjxdn"/><stop offset="1" class="j59325mwl"/></radialGradient><radialGradient id="iwI1alG" cx="0" cy="0" r="1" gradientTransform="rotate(45 -.952 7.73)scale(2.40858)" gradientUnits="userSpaceOnUse"><stop class="brxrt9d7x"/><stop offset=".504" class="sgbazqbvk"/><stop offset="1" class="jeko8g5ml"/></radialGradient><radialGradient id="iYwpyPe" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.15 9.853)scale(1.14905 1.92587)" gradientUnits="userSpaceOnUse"><stop class="xk285bcbq"/><stop offset="1" class="ibe6zr81o"/></radialGradient><radialGradient id="iUHyQye" cx="0" cy="0" r="1" gradientTransform="rotate(135 4.14 12.18)scale(1.14905 1.92587)" gradientUnits="userSpaceOnUse"><stop class="xk285bcbq"/><stop offset="1" class="ibe6zr81o"/></radialGradient><radialGradient id="iuf4O9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 .81063 -1.35867 -1.3618 18.945 21.248)" gradientUnits="userSpaceOnUse"><stop class="xk285bcbq"/><stop offset="1" class="ibe6zr81o"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-bottle" /></template>
<style>
.aevb77_jh {
  stop-color: var(--svg-color--ffd2b5, #FFD2B5);
}

.aniqhhxhj {
  stop-color: var(--svg-color--d88f7c, #D88F7C);
}

.ar5mg6bff {
  d: path("M20.12 27.57a3.223 3.223 0 0 1-4.56 0l-9.28-9.28a.1.1 0 0 1-.03-.04c-1.02-1.05-1-2.75.03-3.79l8.17-8.17a2.71 2.71 0 0 1 3.79-.03c.07.07.14.13.22.18l8.91 8.91c.05.08.12.16.19.23a3.223 3.223 0 0 1 0 4.56z");
}

.b2cwfbc3t {
  d: path("m18.2 20.993l-1.77 1.77c-.29.29-.29.77 0 1.06s.77.29 1.06 0l1.77-1.77c.29-.29.29-.77 0-1.06a.754.754 0 0 0-1.06 0");
}

.bm_9uv1ob {
  d: path("m9.3 21.32l6.25 6.25c1.721 1.721 3.3 1.26 4.56 0l7.43-7.43c1.628-1.628 1.26-3.359 0-4.609c-1.334-1.334-2.654-2.645-3.99-3.981a.62.62 0 0 0-.76-.09l-13.25 7.9c-.69.42-.81 1.38-.24 1.96");
}

.brxrt9d7x {
  stop-color: var(--svg-color--ffde6b, #FFDE6B);
}

.by828gc2p {
  stop-color: var(--svg-color--dfc3b8, #DFC3B8);
  stop-opacity: 0;
}

.d-v169bwu {
  stop-color: var(--svg-color--e79c9b, #E79C9B);
}

.d5427s0ky {
  stop-color: var(--svg-color--d2a852, #D2A852);
}

.f7qu2db-r {
  stop-color: var(--svg-color--dc96a6, #DC96A6);
}

.ft5dv1b6b {
  fill: none;
}

.gzmvuubcg {
  stop-color: var(--svg-color--d68d77, #D68D77);
}

.h65k8lecm {
  stop-color: var(--svg-color--c09764, #C09764);
}

.hih46v2-g {
  stop-color: var(--svg-color--ca7f67, #CA7F67);
}

.hyhexab3w {
  stop-color: var(--svg-color--d4875f, #D4875F);
}

.i-eyivc5o {
  d: path("m11.58 4.05l-7.53 7.53a.99.99 0 0 0 0 1.39l1.62 1.62l8.91-8.91l-1.62-1.62c-.38-.39-1-.39-1.38-.01");
}

.ibe6zr81o {
  stop-color: var(--svg-color--df9788, #DF9788);
  stop-opacity: 0;
}

.ipepvwb2z {
  stop-color: var(--svg-color--dfc2b6, #DFC2B6);
}

.j59325mwl {
  stop-color: var(--svg-color--deb636, #DEB636);
  stop-opacity: 0;
}

.j7bn3_b0h {
  stop-color: var(--svg-color--efca3c, #EFCA3C);
}

.jeko8g5ml {
  stop-color: var(--svg-color--e9bf40, #E9BF40);
  stop-opacity: 0;
}

.jlix6cbrg {
  stop-color: var(--svg-color--da95a5, #DA95A5);
  stop-opacity: 0;
}

.kpfnqma8k {
  d: path("M18.844 5.531c-2.016-2.015-3.75-1.984-5.735 0l-7.616 7.587c-1.6 1.6-2.391 3.405.148 5.945l9.172 9.218c2.843 2.844 4.664 1.696 6.359 0l7.375-7.343c1.758-1.758 2.219-3.422-.39-6.032c-3.104-3.103-6.21-6.271-9.313-9.375");
}

.m_afvbcsj {
  stop-color: var(--svg-color--e49e8b, #E49E8B);
}

.mbd1kjgep {
  stop-color: var(--svg-color--e7cdc5, #E7CDC5);
}

.mhnzf1b2h {
  stop-color: var(--svg-color--cb9f44, #CB9F44);
}

.mjoi0zlyv {
  d: path("m6.27 3.3l-.68-.68a2.1 2.1 0 0 0-2.97 2.97l.68.68c.26.26.36.65.24 1.01L3 8.89c-.24.71-.05 1.49.48 2.01l.62.63l7.43-7.43l-.63-.62c-.52-.53-1.3-.72-2.01-.48l-1.61.54c-.36.12-.75.02-1.01-.24");
}

.mk2-prbpa {
  stop-color: var(--svg-color--d1817b, #D1817B);
}

.n42jcxqfj {
  stop-color: var(--svg-color--d88f74, #D88F74);
  stop-opacity: 0;
}

.ngivbxbdb {
  stop-color: var(--svg-color--d28977, #D28977);
}

.np1x88boa {
  stop-color: var(--svg-color--eeca3f, #EECA3F);
}

.o-2-s4rxz {
  stop-color: var(--svg-color--e09290, #E09290);
}

.okmtq6b2b {
  stop-color: var(--svg-color--e3918e, #E3918E);
}

.omgysj11p {
  stop-color: var(--svg-color--e49496, #E49496);
}

.oy50t7b7y {
  stop-color: var(--svg-color--d4b039, #D4B039);
}

.p965c5b4h {
  d: path("m11.599 14.345l-1.77 1.77c-.29.29-.29.77 0 1.06s.77.29 1.06 0l1.77-1.77c.29-.29.29-.77 0-1.06c-.29-.3-.76-.3-1.06 0");
}

.pqqvllgyy {
  stop-color: var(--svg-color--d18363, #D18363);
}

.q_1gaeqid {
  stop-color: var(--svg-color--e59996, #E59996);
}

.qhg0gj_ik {
  d: path("m14.935 17.618l-1.77 1.77c-.29.29-.29.77 0 1.06s.77.29 1.06 0l1.77-1.77c.29-.29.29-.77 0-1.06c-.29-.3-.76-.3-1.06 0");
}

.r6urzjxdn {
  stop-color: var(--svg-color--ecc73f, #ECC73F);
}

.re12ppbvb {
  stop-color: var(--svg-color--f9b590, #F9B590);
}

.rhxamkbua {
  stop-color: var(--svg-color--cf8572, #CF8572);
}

.rmo6chb3y {
  stop-color: var(--svg-color--ffbe9c, #FFBE9C);
}

.s7pqihvog {
  stop-color: var(--svg-color--dc9384, #DC9384);
}

.sgbazqbvk {
  stop-color: var(--svg-color--f6d146, #F6D146);
}

.t13fuubzs {
  stop-color: var(--svg-color--d4b3b7, #D4B3B7);
}

.t6rc9ffaf {
  stop-color: var(--svg-color--f9d667, #F9D667);
}

.ub97nqbtb {
  stop-color: var(--svg-color--db9a85, #DB9A85);
}

.v7p1v6wkr {
  stop-color: var(--svg-color--cf845d, #CF845D);
  stop-opacity: 0;
}

.vzzlahrrd {
  stop-color: var(--svg-color--d7b5b6, #D7B5B6);
}

.wxex9jbyf {
  stop-color: var(--svg-color--e7e4ed, #E7E4ED);
}

.x93y-db6v {
  stop-color: var(--svg-color--c37f75, #C37F75);
}

.x9j5otkqg {
  stop-color: var(--svg-color--d2c4e3, #D2C4E3);
}

.xk285bcbq {
  stop-color: var(--svg-color--f6b599, #F6B599);
}

.xr_g0c4hx {
  stop-color: var(--svg-color--cda13d, #CDA13D);
  stop-opacity: 0;
}

.y4p65pbjf {
  stop-color: var(--svg-color--eeaf91, #EEAF91);
}

.yh_qrxbgx {
  stop-color: var(--svg-color--d6b5b2, #D6B5B2);
}

.zpw-7tbog {
  stop-color: var(--svg-color--d58577, #D58577);
}

.zr97_pbek {
  stop-color: var(--svg-color--e8e7eb, #E8E7EB);
}

</style>
