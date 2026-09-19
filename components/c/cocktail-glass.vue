<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iClR3mb)" class="e5qeqd9-t"/><path fill="url(#iMjFtJc)" class="e5qeqd9-t"/><path fill="url(#iq81HBq)" class="e5qeqd9-t"/><path fill="url(#iMehvjc)" class="e5qeqd9-t"/><path fill="url(#iPVkahb)" class="e5qeqd9-t"/><path fill="url(#idani3d)" class="e5qeqd9-t"/><path fill="url(#iHggBnd)" class="wet49_hpx"/><path fill="url(#iDBVpfb)" class="wet49_hpx"/><path fill="url(#ixI1Lty)" class="wet49_hpx"/><path fill="url(#ioAptXK)" class="lqhct2byc"/><path class="ynw0_2xyg"/><path fill="url(#ixjsbYc)" class="mjcr6eblv"/><path fill="url(#iT6zNDb)" class="mjcr6eblv"/><path fill="url(#iyLPbNH)" class="mjcr6eblv"/><path fill="url(#iCnThld)" class="mjcr6eblv"/><path fill="url(#iSdMVrd)" class="mjcr6eblv"/><path fill="url(#idSpz9d)" class="mjcr6eblv"/><path stroke="url(#in4UnRd)" class="e_rmnp91r"/><path stroke="url(#iJesOmc)" class="e_rmnp91r"/><path stroke="url(#iKNP06d)" class="pvj5fjbtg"/><path stroke="url(#i3DstZb)" class="pvj5fjbtg"/><path stroke="url(#iVSmuTd)" class="pvj5fjbtg"/><path class="m5we968ha"/><path fill="url(#icmWlDb)" class="trxrui5lc"/><path class="zp-c4kbiu"/><path fill="url(#ipjFjlb)" class="qvmihe18u"/><path fill="url(#iqIk5Xd)" class="qvmihe18u"/><path fill="url(#i6hZ3fe)" class="qvmihe18u"/><path class="z_p253qsr"/><path fill="url(#ivP914g)" class="yahq2lbfk"/><path class="gm_sg0yuh"/><path fill="url(#iEozGwe)" class="y69bsrbyg"/><path fill="url(#iIx4tae)" class="y69bsrbyg"/><path fill="url(#ilZW50c)" class="y69bsrbyg"/><path fill="url(#icbiMwI)" class="c6fz38b6o"/><defs><radialGradient id="iClR3mb" cx="0" cy="0" r="1" gradientTransform="matrix(0 20.845 -13.3929 0 16.018 6.03)" gradientUnits="userSpaceOnUse"><stop class="chh5p7bvl"/><stop offset=".52" class="alkt0d8kh"/><stop offset=".926" class="mgbdyccph"/></radialGradient><radialGradient id="iMjFtJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.9675 -10.9839 0 16.018 19.063)" gradientUnits="userSpaceOnUse"><stop offset=".076" class="hcpzol_bt"/><stop offset="1" class="poy9hmpuc"/></radialGradient><radialGradient id="iPVkahb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42188 -15.625 0 7.25 6.86)" gradientUnits="userSpaceOnUse"><stop class="f76882iqo"/><stop offset="1" class="hnl0m8nsn"/></radialGradient><radialGradient id="idani3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -14.6246 0 23.938 6.688)" gradientUnits="userSpaceOnUse"><stop class="bhv1y4nqv"/><stop offset="1" class="hnl0m8nsn"/></radialGradient><radialGradient id="iDBVpfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78125 -6.84375 0 12.281 28.125)" gradientUnits="userSpaceOnUse"><stop class="m4c428b8b"/><stop offset="1" class="qkyfbug7b"/></radialGradient><radialGradient id="ixI1Lty" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 .71875 -4.21892 .18343 18.563 28.531)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="si7zrwbea"/><stop offset=".763" class="bov16gjyk"/></radialGradient><radialGradient id="ixjsbYc" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 2.836 7.997)scale(3.11906 28.5061)" gradientUnits="userSpaceOnUse"><stop class="yhjo2_bxw"/><stop offset=".111" class="hzsimdqby"/><stop offset=".39" class="k-fw39bwu"/></radialGradient><radialGradient id="iT6zNDb" cx="0" cy="0" r="1" gradientTransform="rotate(34.606 -11.444 40.101)scale(3.79671 34.6994)" gradientUnits="userSpaceOnUse"><stop class="yhjo2_bxw"/><stop offset=".111" class="hzsimdqby"/><stop offset=".297" class="k-fw39bwu"/></radialGradient><radialGradient id="iyLPbNH" cx="0" cy="0" r="1" gradientTransform="matrix(3 3.6875 -4.13433 3.36353 20.875 12.063)" gradientUnits="userSpaceOnUse"><stop class="uq6d7_bcl"/><stop offset="1" class="k-fw39bwu"/></radialGradient><radialGradient id="iSdMVrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .53125 -5.61133 0 10.063 9.719)" gradientUnits="userSpaceOnUse"><stop class="lfpk1ebav"/><stop offset="1" class="ssbjswwqu"/></radialGradient><radialGradient id="idSpz9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .375 -8.59375 0 21.656 9.594)" gradientUnits="userSpaceOnUse"><stop class="lfpk1ebav"/><stop offset="1" class="ssbjswwqu"/></radialGradient><radialGradient id="i3DstZb" cx="0" cy="0" r="1" gradientTransform="rotate(108.434 4.079 12.406)scale(4.1679 3.28572)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="lie8rvooo"/><stop offset=".975" class="l976ap9pk"/></radialGradient><radialGradient id="iVSmuTd" cx="0" cy="0" r="1" gradientTransform="matrix(3.03123 -4.29689 7.02698 4.95717 14.61 16.235)" gradientUnits="userSpaceOnUse"><stop offset=".883" class="lie8rvooo"/><stop offset=".975" class="h-y63o6mk"/></radialGradient><radialGradient id="icmWlDb" cx="0" cy="0" r="1" gradientTransform="rotate(137.663 7.733 8.241)scale(1.9024)" gradientUnits="userSpaceOnUse"><stop class="icjc1tb5q"/><stop offset=".871" class="ox-jd0b9u"/></radialGradient><radialGradient id="ipjFjlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.74997 3.40625 -5.16525 -1.13726 19.094 9.594)" gradientUnits="userSpaceOnUse"><stop class="m0n-_32kx"/><stop offset=".205" class="n1_54zbam"/><stop offset=".515" class="o6yx9x3rx"/><stop offset=".765" class="yxzmlen2a"/></radialGradient><radialGradient id="i6hZ3fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46094 -7.53286 0 18.945 9.578)" gradientUnits="userSpaceOnUse"><stop class="o0qg0xnsw"/><stop offset=".459" class="luzmf9bgg"/></radialGradient><radialGradient id="ivP914g" cx="0" cy="0" r="1" gradientTransform="rotate(111.176 5.929 10.581)scale(1.85964 1.71444)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="n8p37xk-q"/><stop offset=".641" class="ns_fi6x-u"/></radialGradient><radialGradient id="iEozGwe" cx="0" cy="0" r="1" gradientTransform="rotate(125.611 6.459 9.224)scale(1.55638 1.82542)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="yalgzbb7y"/><stop offset=".641" class="y8h2k0b8c"/></radialGradient><linearGradient id="iq81HBq" x1="9.625" x2="10.813" y1="14.438" y2="13.375" gradientUnits="userSpaceOnUse"><stop class="c8uxtob5c"/><stop offset=".66" class="g5j8b0zjh"/></linearGradient><linearGradient id="iMehvjc" x1="22.188" x2="21.125" y1="14.313" y2="13.438" gradientUnits="userSpaceOnUse"><stop class="c8uxtob5c"/><stop offset=".66" class="g5j8b0zjh"/></linearGradient><linearGradient id="iHggBnd" x1="10.021" x2="22.021" y1="29.5" y2="29.5" gradientUnits="userSpaceOnUse"><stop class="lhhgot9np"/><stop offset=".118" class="xili6h4wx"/><stop offset=".514" class="rdue0n1ji"/><stop offset=".769" class="eo2wywt9p"/><stop offset=".907" class="rcszed7zj"/><stop offset=".988" class="c9-medcim"/></linearGradient><linearGradient id="ioAptXK" x1="15.063" x2="17.037" y1="22.938" y2="22.938" gradientUnits="userSpaceOnUse"><stop class="wzjmhub4p"/><stop offset=".1" class="m4c428b8b"/><stop offset=".34" class="eq8m25bpy"/><stop offset=".605" class="ypltp0w4x"/><stop offset=".863" class="lf6c9irqg"/><stop offset=".949" class="zkr2n02sj"/></linearGradient><linearGradient id="iCnThld" x1="16.016" x2="16.016" y1="9.03" y2="10.188" gradientUnits="userSpaceOnUse"><stop class="gorxvntje"/><stop offset="1" class="s42n8m1oj"/></linearGradient><linearGradient id="in4UnRd" x1="18.844" x2="20.063" y1="5.188" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="sbrcfdb7a"/><stop offset=".334" class="kqeh14-8r"/><stop offset=".659" class="q5x3wpqaq"/><stop offset="1" class="n8zn_bu1z"/></linearGradient><linearGradient id="iJesOmc" x1="19.281" x2="19.281" y1="5.313" y2="7.844" gradientUnits="userSpaceOnUse"><stop offset=".398" class="rwo4_gbga"/><stop offset=".543" class="f9die8b6k"/><stop offset=".683" class="g_f405bgu"/></linearGradient><linearGradient id="iKNP06d" x1="16.021" x2="17.023" y1="14.109" y2="14.438" gradientUnits="userSpaceOnUse"><stop offset=".038" class="jtpfb_ngc"/><stop offset=".329" class="xc4sqglkz"/><stop offset=".65" class="c3yg3qbng"/><stop offset=".968" class="epbmch4oe"/></linearGradient><linearGradient id="iqIk5Xd" x1="17.951" x2="17.951" y1="9.06" y2="9.469" gradientUnits="userSpaceOnUse"><stop class="znnlhu2rh"/><stop offset=".464" class="luzmf9bgg"/></linearGradient><linearGradient id="iIx4tae" x1="17.266" x2="17.266" y1="9.063" y2="9.297" gradientUnits="userSpaceOnUse"><stop class="xivn4w9ks"/><stop offset="1" class="ouzz8xb2t"/></linearGradient><linearGradient id="ilZW50c" x1="17.266" x2="17.266" y1="9.266" y2="10.609" gradientUnits="userSpaceOnUse"><stop offset=".07" class="ell8qtbnc"/><stop offset=".233" class="eax49ekit"/><stop offset=".378" class="qjamsibjf"/></linearGradient><linearGradient id="icbiMwI" x1="24.438" x2="17.781" y1="8.547" y2="16.703" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cocktail-glass" /></template>
<style>
.alkt0d8kh {
  stop-color: var(--svg-color--bae8ff, #BAE8FF);
}

.bhv1y4nqv {
  stop-color: var(--svg-color--d2f9ff, #D2F9FF);
}

.bov16gjyk {
  stop-color: var(--svg-color--d2fcff, #D2FCFF);
  stop-opacity: 0;
}

.c3yg3qbng {
  stop-color: var(--svg-color--ffd4b9, #FFD4B9);
}

.c6fz38b6o {
  d: path("M25.019 9.021a.75.75 0 0 0-1.163-.948zM17.2 16.23a.75.75 0 1 0 1.162.948zm6.656-8.156L17.2 16.229l1.162.948l6.657-8.156z");
}

.c8uxtob5c {
  stop-color: var(--svg-color--bbd9f3, #BBD9F3);
}

.c9-medcim {
  stop-color: var(--svg-color--c1e3fb, #C1E3FB);
}

.chh5p7bvl {
  stop-color: var(--svg-color--bef, #BEF);
}

.e_rmnp91r {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("m16.02 15.78l2.236-6.64L20.49 2.5");
}

.e5qeqd9-t {
  d: path("M27.83 7.41c.47-.54.08-1.38-.64-1.38H4.84c-.72 0-1.1.84-.64 1.38l10.81 12.62v7.32h-3.22c-.98 0-1.77.79-1.77 1.77v.91h12v-.91c0-.98-.79-1.77-1.77-1.77h-3.23v-7.32z");
}

.eax49ekit {
  stop-color: var(--svg-color--ff9f71, #FF9F71);
}

.ell8qtbnc {
  stop-color: var(--svg-color--ff9f71, #FF9F71);
  stop-opacity: 0;
}

.eo2wywt9p {
  stop-color: var(--svg-color--cbf8ff, #CBF8FF);
}

.epbmch4oe {
  stop-color: var(--svg-color--ffd0b6, #FFD0B6);
}

.eq8m25bpy {
  stop-color: var(--svg-color--c4efff, #C4EFFF);
}

.f76882iqo {
  stop-color: var(--svg-color--cff0ff, #CFF0FF);
}

.f9die8b6k {
  stop-color: var(--svg-color--ffca9c, #FFCA9C);
}

.ft5dv1b6b {
  fill: none;
}

.g_f405bgu {
  stop-color: var(--svg-color--ffcb9c, #FFCB9C);
  stop-opacity: 0;
}

.g5j8b0zjh {
  stop-color: var(--svg-color--b9daf5, #B9DAF5);
  stop-opacity: 0;
}

.gm_sg0yuh {
  fill: var(--svg-color--fa684c, #FA684C);
  d: path("M18.24 9.81c-.2.6-.8.93-1.34.75s-.81-.81-.61-1.41q.015-.045.034-.088h1.931c.07.23.071.492-.014.748");
}

.gorxvntje {
  stop-color: var(--svg-color--a5e294, #A5E294);
}

.h-y63o6mk {
  stop-color: var(--svg-color--db95ab, #DB95AB);
}

.hcpzol_bt {
  stop-color: var(--svg-color--baedff, #BAEDFF);
}

.hnl0m8nsn {
  stop-color: var(--svg-color--c6edff, #C6EDFF);
  stop-opacity: 0;
}

.hzsimdqby {
  stop-color: var(--svg-color--a2d788, #A2D788);
}

.icjc1tb5q {
  stop-color: var(--svg-color--43a28a, #43A28A);
}

.jtpfb_ngc {
  stop-color: var(--svg-color--ecbfa3, #ECBFA3);
}

.k-fw39bwu {
  stop-color: var(--svg-color--a9e680, #A9E680);
  stop-opacity: 0;
}

.kqeh14-8r {
  stop-color: var(--svg-color--fcb17b, #FCB17B);
}

.l976ap9pk {
  stop-color: var(--svg-color--f19bb8, #F19BB8);
}

.lf6c9irqg {
  stop-color: var(--svg-color--cbf6ff, #CBF6FF);
}

.lfpk1ebav {
  stop-color: var(--svg-color--c6fd91, #C6FD91);
}

.lhhgot9np {
  stop-color: var(--svg-color--bad8f2, #BAD8F2);
}

.lie8rvooo {
  stop-color: var(--svg-color--f09bb9, #F09BB9);
  stop-opacity: 0;
}

.lqhct2byc {
  d: path("M15.01 20.03v7.32h2.01v-7.32z");
}

.luzmf9bgg {
  stop-color: var(--svg-color--66b19f, #66B19F);
  stop-opacity: 0;
}

.m0n-_32kx {
  stop-color: var(--svg-color--6ab3a2, #6AB3A2);
}

.m4c428b8b {
  stop-color: var(--svg-color--c3edff, #C3EDFF);
}

.m5we968ha {
  fill: var(--svg-color--398072, #398072);
  d: path("M17.95 12.16a2.23 2.23 0 1 0 0-4.46a2.23 2.23 0 0 0 0 4.46");
}

.mgbdyccph {
  stop-color: var(--svg-color--b6d9f5, #B6D9F5);
}

.mjcr6eblv {
  d: path("M14.44 18.1L8 10.23a.736.736 0 0 1 .57-1.2h14.89c.62 0 .96.72.57 1.2L17.6 18.1c-.82 1-2.34 1-3.16 0");
}

.n1_54zbam {
  stop-color: var(--svg-color--3c9992, #3C9992);
}

.n8p37xk-q {
  stop-color: var(--svg-color--f96a45, #F96A45);
}

.n8zn_bu1z {
  stop-color: var(--svg-color--fdc094, #FDC094);
}

.ns_fi6x-u {
  stop-color: var(--svg-color--ff7951, #FF7951);
}

.o0qg0xnsw {
  stop-color: var(--svg-color--77beae, #77BEAE);
}

.o6yx9x3rx {
  stop-color: var(--svg-color--398294, #398294);
}

.ouzz8xb2t {
  stop-color: var(--svg-color--e68972, #E68972);
  stop-opacity: 0;
}

.ox-jd0b9u {
  stop-color: var(--svg-color--44a38b, #44A38B);
  stop-opacity: 0;
}

.poy9hmpuc {
  stop-color: var(--svg-color--bef, #BEF);
  stop-opacity: 0;
}

.pvj5fjbtg {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("m16.02 15.78l2.236-6.64");
}

.q5x3wpqaq {
  stop-color: var(--svg-color--ffc991, #FFC991);
}

.qjamsibjf {
  stop-color: var(--svg-color--ff9f72, #FF9F72);
  stop-opacity: 0;
}

.qkyfbug7b {
  stop-color: var(--svg-color--c1ebff, #C1EBFF);
  stop-opacity: 0;
}

.qvmihe18u {
  d: path("M17.95 12.16a2.23 2.23 0 0 0 2.055-3.1h-4.108a2.23 2.23 0 0 0 2.054 3.1");
}

.rcszed7zj {
  stop-color: var(--svg-color--c9f6ff, #C9F6FF);
}

.rdue0n1ji {
  stop-color: var(--svg-color--c0efff, #C0EFFF);
}

.rwo4_gbga {
  stop-color: var(--svg-color--ffcd9f, #FFCD9F);
  stop-opacity: 0;
}

.s42n8m1oj {
  stop-color: var(--svg-color--ace3b0, #ACE3B0);
  stop-opacity: 0;
}

.sbrcfdb7a {
  stop-color: var(--svg-color--e4a671, #E4A671);
}

.si7zrwbea {
  stop-color: var(--svg-color--d0fcff, #D0FCFF);
}

.ssbjswwqu {
  stop-color: var(--svg-color--b9ef82, #B9EF82);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.trxrui5lc {
  d: path("M17.95 12.16a2.23 2.23 0 1 0 0-4.46a2.23 2.23 0 0 0 0 4.46");
}

.uq6d7_bcl {
  stop-color: var(--svg-color--a4e170, #A4E170);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wet49_hpx {
  d: path("M11.79 27.35c-.98 0-1.77.79-1.77 1.77v.91h12v-.91c0-.98-.79-1.77-1.77-1.77z");
}

.wzjmhub4p {
  stop-color: var(--svg-color--b8daf6, #B8DAF6);
}

.xc4sqglkz {
  stop-color: var(--svg-color--fdc1a7, #FDC1A7);
}

.xili6h4wx {
  stop-color: var(--svg-color--bde6ff, #BDE6FF);
}

.xivn4w9ks {
  stop-color: var(--svg-color--e88873, #E88873);
}

.y69bsrbyg {
  d: path("M18.24 9.81c-.2.6-.8.93-1.34.75s-.81-.81-.61-1.41q.015-.045.034-.088h1.931c.07.23.071.492-.014.748");
}

.y8h2k0b8c {
  stop-color: var(--svg-color--ff9563, #FF9563);
}

.yahq2lbfk {
  d: path("M18.24 9.81c-.2.6-.8.93-1.34.75s-.81-.81-.61-1.41s.8-.93 1.34-.75s.81.81.61 1.41");
}

.yalgzbb7y {
  stop-color: var(--svg-color--f6815d, #F6815D);
}

.yhjo2_bxw {
  stop-color: var(--svg-color--a3ca95, #A3CA95);
}

.ynw0_2xyg {
  fill: var(--svg-color--a5eb78, #A5EB78);
  d: path("M14.44 18.1L8 10.23a.736.736 0 0 1 .57-1.2h14.89c.62 0 .96.72.57 1.2L17.6 18.1c-.82 1-2.34 1-3.16 0");
}

.ypltp0w4x {
  stop-color: var(--svg-color--ccf7ff, #CCF7FF);
}

.yxzmlen2a {
  stop-color: var(--svg-color--6b78c2, #6B78C2);
}

.z_p253qsr {
  fill: var(--svg-color--fa684c, #FA684C);
  d: path("M18.24 9.81c-.2.6-.8.93-1.34.75s-.81-.81-.61-1.41s.8-.93 1.34-.75s.81.81.61 1.41");
}

.zkr2n02sj {
  stop-color: var(--svg-color--c3e5fd, #C3E5FD);
}

.znnlhu2rh {
  stop-color: var(--svg-color--8ab4a0, #8AB4A0);
}

.zp-c4kbiu {
  fill: var(--svg-color--398974, #398974);
  d: path("M17.95 12.16a2.23 2.23 0 0 0 2.055-3.1h-4.108a2.23 2.23 0 0 0 2.054 3.1");
}

</style>
