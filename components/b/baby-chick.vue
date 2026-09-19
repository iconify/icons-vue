<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ibe3EJd)" class="kn5wtootj"/><path fill="url(#iPGvxPc)" class="kn5wtootj"/><path fill="url(#i1BVdsg)" class="kn5wtootj"/><path fill="url(#iFlyksc)" class="kn5wtootj"/><path fill="url(#i0XU8re)" class="x9c9s_vea"/><path fill="url(#iS3bHtP)" class="x9c9s_vea"/><path fill="url(#iF2xu8d)" class="x9c9s_vea"/><path fill="url(#i147ciV)" class="x9c9s_vea"/><path fill="url(#iqoQcrb)" class="lhchj2cjw"/><path fill="url(#iYMAs4d)" class="lhchj2cjw"/><path fill="url(#i8wrP3b)" class="s6s2xhvkv"/><path fill="url(#i7uQqFc)" class="s6s2xhvkv"/><path fill="url(#ipuVOMc)" class="s6s2xhvkv"/><path fill="url(#iouFE4j)" class="s6s2xhvkv"/><path fill="url(#ik2kNcc)" class="s6s2xhvkv"/><path fill="url(#iPevJDc)" class="s6s2xhvkv"/><path fill="url(#iCTYmle)" class="bo3l8rtas"/><path fill="url(#i7eDgtb)" class="bo3l8rtas"/><path fill="url(#i5gvotb)" class="bo3l8rtas"/><path fill="url(#iUSJEfg)" class="jmcpz2b_h"/><path fill="url(#iC3AVab)" class="jmcpz2b_h"/><path fill="url(#iwh8bUb)" class="jmcpz2b_h"/><g filter="url(#ii3F4Sc)"><path fill="url(#iUX2Hwe)" class="pkd70wjnk"/></g><g filter="url(#inJtL1c)"><path stroke="url(#iq6byki)" class="onpnqw4yn"/></g><defs><radialGradient id="i1BVdsg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.29365 0 0 -2.34945 15.035 29.17)" gradientUnits="userSpaceOnUse"><stop class="dgq40ga3c"/><stop offset="1" class="xir1dwxgq"/></radialGradient><radialGradient id="iFlyksc" cx="0" cy="0" r="1" gradientTransform="rotate(41.926 -31.69 27.458)scale(4.32621 4.88319)" gradientUnits="userSpaceOnUse"><stop class="iwzyq_met"/><stop offset="1" class="gryo57x6u"/></radialGradient><radialGradient id="iF2xu8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.63027 -1.39717 1.1243 -1.31189 21.506 30.272)" gradientUnits="userSpaceOnUse"><stop class="cxtlk-bre"/><stop offset="1" class="lam99wdso"/></radialGradient><radialGradient id="iqoQcrb" cx="0" cy="0" r="1" gradientTransform="matrix(4.03125 0 0 2.28893 2.438 10.969)" gradientUnits="userSpaceOnUse"><stop class="gu3v40bru"/><stop offset="1" class="u9m2j0bdc"/></radialGradient><radialGradient id="i8wrP3b" cx="0" cy="0" r="1" gradientTransform="rotate(59.637 -2.82 13.278)scale(19.4126 28.4213)" gradientUnits="userSpaceOnUse"><stop class="sbvu292xv"/><stop offset="1" class="r8pt_dbos"/></radialGradient><radialGradient id="i7uQqFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.4375 -17.6875 0 17 7.875)" gradientUnits="userSpaceOnUse"><stop offset=".916" class="yiwommhny"/><stop offset="1" class="zgyip0bcy"/></radialGradient><radialGradient id="ipuVOMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 6.13769 0 17 27.969)" gradientUnits="userSpaceOnUse"><stop class="ons_9-qyy"/><stop offset=".975" class="n7tx1xrrh"/></radialGradient><radialGradient id="iouFE4j" cx="0" cy="0" r="1" gradientTransform="rotate(129.12 10.47 7.395)scale(13.3728 13.4634)" gradientUnits="userSpaceOnUse"><stop class="iyetbac0l"/><stop offset="1" class="slmxs-v9r"/></radialGradient><radialGradient id="ik2kNcc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.12503 7.43752 -9.29421 -17.65118 19.188 15.438)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="q6terfbak"/><stop offset="1" class="o0jhwsvve"/></radialGradient><radialGradient id="iPevJDc" cx="0" cy="0" r="1" gradientTransform="matrix(4.75 5.375 -7.37137 6.51423 3.313 2.875)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="sxqkarmhv"/><stop offset=".899" class="k5f9f2bcb"/></radialGradient><radialGradient id="iCTYmle" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 9.612 10.335)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="i7eDgtb" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 2.817 7.055)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iC3AVab" cx="0" cy="0" r="1" gradientTransform="rotate(109.213 9.175 14.819)scale(2.18415 11.9086)" gradientUnits="userSpaceOnUse"><stop class="tkic8435m"/><stop offset="1" class="lfk3_oxxi"/></radialGradient><linearGradient id="ibe3EJd" x1="12.27" x2="13.996" y1="29.23" y2="22.735" gradientUnits="userSpaceOnUse"><stop class="nv8wg8y0e"/><stop offset="1" class="lb96bubco"/></linearGradient><linearGradient id="iPGvxPc" x1="12.988" x2="12.988" y1="30.424" y2="29.124" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset=".828" class="u5vkysn3x"/></linearGradient><linearGradient id="i0XU8re" x1="17.29" x2="19.004" y1="29.23" y2="22.727" gradientUnits="userSpaceOnUse"><stop class="nv8wg8y0e"/><stop offset="1" class="lb96bubco"/></linearGradient><linearGradient id="iS3bHtP" x1="21.73" x2="12.111" y1="29.106" y2="29.106" gradientUnits="userSpaceOnUse"><stop class="iwzyq_met"/><stop offset="1" class="gryo57x6u"/></linearGradient><linearGradient id="i147ciV" x1="18.015" x2="18.015" y1="30.424" y2="29.124" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset=".828" class="u5vkysn3x"/></linearGradient><linearGradient id="iYMAs4d" x1="3.242" x2="3.525" y1="12.539" y2="11.133" gradientUnits="userSpaceOnUse"><stop class="nm753ubfa"/><stop offset="1" class="nx__nbbgi"/></linearGradient><linearGradient id="i5gvotb" x1="9.367" x2="9.023" y1="10.103" y2="9.885" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iUSJEfg" x1="30" x2="18.5" y1="28.063" y2="14.875" gradientUnits="userSpaceOnUse"><stop class="i46bc3-mx"/><stop offset="1" class="f26dvj71f"/></linearGradient><linearGradient id="iwh8bUb" x1="22.188" x2="22.188" y1="26" y2="20.688" gradientUnits="userSpaceOnUse"><stop class="juaab144z"/><stop offset="1" class="dc84fnbeb"/></linearGradient><linearGradient id="iUX2Hwe" x1="15.75" x2="29.375" y1="-.563" y2="21.813" gradientUnits="userSpaceOnUse"><stop class="iyetbac0l"/><stop offset="1" class="slmxs-v9r"/></linearGradient><linearGradient id="iq6byki" x1="28.438" x2="23.938" y1="14.344" y2="16.25" gradientUnits="userSpaceOnUse"><stop class="iyetbac0l"/><stop offset="1" class="slmxs-v9r"/></linearGradient><filter id="ii3F4Sc" width="22.543" height="17.862" x="9.395" y="2.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4778" stdDeviation="1.375"/></filter><filter id="inJtL1c" width="8" height="5.344" x="22.188" y="12.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4778" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-chick" /></template>
<style>
.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bo3l8rtas {
  d: path("M9.465 10.996a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cxtlk-bre {
  stop-color: var(--svg-color--ffa56b, #FFA56B);
}

.dc84fnbeb {
  stop-color: var(--svg-color--ff946d, #FF946D);
  stop-opacity: 0;
}

.dgq40ga3c {
  stop-color: var(--svg-color--d6551c, #D6551C);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.f26dvj71f {
  stop-color: var(--svg-color--ff8c00, #FF8C00);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gryo57x6u {
  stop-color: var(--svg-color--f67f41, #F67F41);
  stop-opacity: 0;
}

.gu3v40bru {
  stop-color: var(--svg-color--fd8b44, #FD8B44);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.i46bc3-mx {
  stop-color: var(--svg-color--ff8c00, #FF8C00);
}

.iwzyq_met {
  stop-color: var(--svg-color--f67f41, #F67F41);
}

.iyetbac0l {
  stop-color: var(--svg-color--fff463, #FFF463);
}

.jmcpz2b_h {
  d: path("M21.26 23.938c3.82-.07 7.13-2.66 8.21-6.32c.34-1.17.53-2.4.53-3.68c0-.54-.34-1.02-.83-1.21l-11.64-3.04v2.74h-7.48v.41c0 6.05 4.95 11.1 10.99 11.1z");
}

.juaab144z {
  stop-color: var(--svg-color--ff946d, #FF946D);
}

.k5f9f2bcb {
  stop-color: var(--svg-color--cdb168, #CDB168);
  stop-opacity: 0;
}

.kn5wtootj {
  d: path("M15.5 28.438h-1.72l1.2-6h-1.5l-1.2 6h-1.8c-.73 0-1.33.52-1.47 1.21c-.04.15.08.29.24.29h7.47c.16 0 .28-.14.25-.29c-.14-.69-.74-1.21-1.47-1.21");
}

.lam99wdso {
  stop-color: var(--svg-color--ffa56b, #FFA56B);
  stop-opacity: 0;
}

.lb96bubco {
  stop-color: var(--svg-color--db592a, #DB592A);
}

.lfk3_oxxi {
  stop-color: var(--svg-color--e7a93f, #E7A93F);
  stop-opacity: 0;
}

.lhchj2cjw {
  d: path("m5.05 8.298l-2.72 1.99c-.44.32-.44.97 0 1.29l1.84 1.36z");
}

.n7tx1xrrh {
  stop-color: var(--svg-color--ff8d31, #FF8D31);
  stop-opacity: 0;
}

.nm753ubfa {
  stop-color: var(--svg-color--f0757c, #F0757C);
}

.nv8wg8y0e {
  stop-color: var(--svg-color--e46d33, #E46D33);
}

.nx__nbbgi {
  stop-color: var(--svg-color--f0757c, #F0757C);
  stop-opacity: 0;
}

.o0jhwsvve {
  stop-color: var(--svg-color--f7b168, #F7B168);
}

.onpnqw4yn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M28.438 14.156c-.48.625-2.05 1.869-4.5 1.844");
}

.ons_9-qyy {
  stop-color: var(--svg-color--ff8d31, #FF8D31);
}

.p_ptxbjeb {
  stop-color: var(--svg-color--f15cc7, #F15CC7);
}

.pkd70wjnk {
  d: path("M17.25 10.844c-.4-4.45-3.23-5.636-4.875-5.969c-1.437 8.125 4.203 11.634 7.25 12.188c4.813.875 9-1.75 9.563-3.438z");
}

.q6terfbak {
  stop-color: var(--svg-color--f7b168, #F7B168);
  stop-opacity: 0;
}

.r8pt_dbos {
  stop-color: var(--svg-color--ffb071, #FFB071);
}

.s6s2xhvkv {
  d: path("m29.03 12.688l-9.65-2.53a.96.96 0 0 1-.67-.67a7.47 7.47 0 0 0-7.23-5.55c-4.13 0-7.48 3.35-7.48 7.48v2.52c0 7.18 5.82 13 13 13s13-5.82 13-13c0-.59-.4-1.1-.97-1.25");
}

.sbvu292xv {
  stop-color: var(--svg-color--ffcf38, #FFCF38);
}

.slmxs-v9r {
  stop-color: var(--svg-color--fff463, #FFF463);
  stop-opacity: 0;
}

.sxqkarmhv {
  stop-color: var(--svg-color--cdb168, #CDB168);
}

.tkic8435m {
  stop-color: var(--svg-color--e7a93f, #E7A93F);
}

.u5vkysn3x {
  stop-color: var(--svg-color--f15cc7, #F15CC7);
  stop-opacity: 0;
}

.u9m2j0bdc {
  stop-color: var(--svg-color--db7b46, #DB7B46);
}

.x9c9s_vea {
  d: path("M20.55 28.438h-1.78l1.2-6h-1.5l-1.2 6h-1.8c-.73 0-1.33.52-1.47 1.21c-.03.15.09.29.25.29h7.53c.16 0 .28-.14.25-.29c-.14-.69-.75-1.21-1.48-1.21");
}

.xir1dwxgq {
  stop-color: var(--svg-color--d6551c, #D6551C);
  stop-opacity: 0;
}

.yiwommhny {
  stop-color: var(--svg-color--ffa1d9, #FFA1D9);
  stop-opacity: 0;
}

.zgyip0bcy {
  stop-color: var(--svg-color--ffa1d9, #FFA1D9);
}

</style>
