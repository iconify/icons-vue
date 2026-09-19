<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><ellipse fill="url(#i9JX9Fc)" transform="rotate(-57.793 22.42 7.685)" class="jdwtd1bem"/><path fill="url(#ihqnX4b)" clip-rule="evenodd" class="rp6x0pb8e"/><path fill="url(#iRhbnpd)" clip-rule="evenodd" class="rp6x0pb8e"/><path fill="url(#iixeJhd)" clip-rule="evenodd" class="ai128u6ww"/><path fill="url(#ikfqQSA)" class="rhxlgmb_b"/><path fill="url(#ibfishb)" class="z19y-4s6q"/><path fill="url(#iGmhEMe)" class="z19y-4s6q"/><path fill="url(#ij65hed)" class="z19y-4s6q"/><path fill="url(#iLmdIZc)" class="z19y-4s6q"/><path fill="url(#ik7OBgd)" class="fymfk0bes"/><path fill="url(#isccLXd)" class="fymfk0bes"/><path fill="url(#ipWvGPe)" class="fymfk0bes"/><path stroke="url(#ite8hbE)" class="v4znxef1j"/><path stroke="url(#iGAqyfY)" class="v4znxef1j"/><defs><radialGradient id="ihqnX4b" cx="0" cy="0" r="1" gradientTransform="rotate(-30.727 40.318 -13.729)scale(16.3317 22.6004)" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rlq1cpo9c"/><stop offset="1" class="xahg53b3p"/></radialGradient><radialGradient id="iixeJhd" cx="0" cy="0" r="1" gradientTransform="rotate(127.593 13.145 8.384)scale(10.8448)" gradientUnits="userSpaceOnUse"><stop class="belhawfwp"/><stop offset="1" class="juhxbocku"/></radialGradient><radialGradient id="ikfqQSA" cx="0" cy="0" r="1" gradientTransform="matrix(-8.13043 0 0 -4.81647 7.603 21.473)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="q4l1uybse"/><stop offset=".581" class="txs1n_y3h"/><stop offset="1" class="rbb8jubvr"/></radialGradient><radialGradient id="ibfishb" cx="0" cy="0" r="1" gradientTransform="matrix(0 21.3517 -9.72896 0 25.458 18.183)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="oplgr6bbh"/><stop offset=".362" class="xh9xu-boy"/><stop offset=".62" class="n0wv36bcy"/></radialGradient><radialGradient id="ik7OBgd" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 8.69613 -8.69613 2.5 10.5 22)" gradientUnits="userSpaceOnUse"><stop class="zwop2ozme"/><stop offset="1" class="jwnhq_b6g"/></radialGradient><radialGradient id="ite8hbE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21621 3.50865 -6.19495 -2.14737 16.265 17.491)" gradientUnits="userSpaceOnUse"><stop class="qmn7lactj"/><stop offset="1" class="d82oh_1cu"/></radialGradient><radialGradient id="iGAqyfY" cx="0" cy="0" r="1" gradientTransform="matrix(2.5201 -4 7.0625 4.44956 12.529 25)" gradientUnits="userSpaceOnUse"><stop class="pc7cqibkw"/><stop offset="1" class="d82oh_1cu"/></radialGradient><linearGradient id="i9JX9Fc" x1="22.211" x2="25.363" y1="9.684" y2="8.499" gradientUnits="userSpaceOnUse"><stop class="g_zm2dndm"/><stop offset="1" class="su98t29ia"/></linearGradient><linearGradient id="iRhbnpd" x1="24.386" x2="22.789" y1="5.745" y2="9.623" gradientUnits="userSpaceOnUse"><stop class="mwy9hz01p"/><stop offset="1" class="e4a529bmi"/></linearGradient><linearGradient id="iGmhEMe" x1="22.316" x2="26.638" y1="12.621" y2="12.594" gradientUnits="userSpaceOnUse"><stop offset=".413" class="cq0yeq2ec"/><stop offset=".629" class="wkle3mb8m"/></linearGradient><linearGradient id="ij65hed" x1="25.947" x2="25.947" y1="21.951" y2="19.032" gradientUnits="userSpaceOnUse"><stop offset=".413" class="j6a9lkbfp"/><stop offset=".826" class="wkle3mb8m"/></linearGradient><linearGradient id="iLmdIZc" x1="25.947" x2="25.947" y1="24.104" y2="19.667" gradientUnits="userSpaceOnUse"><stop offset=".632" class="c4zrzgpkm"/><stop offset=".974" class="mwct89vbj"/></linearGradient><linearGradient id="isccLXd" x1="5.203" x2="6.651" y1="18.36" y2="20.619" gradientUnits="userSpaceOnUse"><stop class="np9n_uvgu"/><stop offset="1" class="mbivedcjv"/></linearGradient><linearGradient id="ipWvGPe" x1="19.392" x2="17.713" y1="25.947" y2="23.457" gradientUnits="userSpaceOnUse"><stop class="fi8t-0bkc"/><stop offset="1" class="mbivedcjv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:billed-cap" /></template>
<style>
.ai128u6ww {
  fill-rule: evenodd;
  d: path("M20 7.35h-3A7.65 7.65 0 0 0 9.35 15v5.65h14.3V8.064A9.6 9.6 0 0 0 20 7.35m4 .482A10 10 0 0 0 20 7h-3a8 8 0 0 0-8 8v6h15z");
}

.belhawfwp {
  stop-color: var(--svg-color--bbe5ff, #BBE5FF);
}

.c4zrzgpkm {
  stop-color: var(--svg-color--966cfc, #966CFC);
}

.cq0yeq2ec {
  stop-color: var(--svg-color--456cf8, #456CF8);
}

.d82oh_1cu {
  stop-color: var(--svg-color--3a5ad5, #3A5AD5);
  stop-opacity: 0;
}

.e4a529bmi {
  stop-color: var(--svg-color--93c2fd, #93C2FD);
  stop-opacity: 0;
}

.fi8t-0bkc {
  stop-color: var(--svg-color--3758d2, #3758D2);
}

.ft5dv1b6b {
  fill: none;
}

.fymfk0bes {
  d: path("M9.033 17.125c7.367.005 11.345 1.57 14.772 3.893c-1.97 1.97-3.917 3.857-6.805 3.857c-1.472 0-2.747-.468-3.884-1.076a21 21 0 0 1-1.608-.974q-.18-.117-.353-.233c-.377-.249-.74-.49-1.09-.7c-1.272-.762-2.792-1.14-4.242-1.267a13 13 0 0 0-3.088.099z");
}

.g_zm2dndm {
  stop-color: var(--svg-color--5c6eff, #5C6EFF);
}

.j6a9lkbfp {
  stop-color: var(--svg-color--5478fa, #5478FA);
}

.jdwtd1bem {
  cx: 22.42px;
  cy: 7.685px;
  rx: 1.313px;
  ry: 1.68px;
}

.juhxbocku {
  stop-color: var(--svg-color--bbe5ff, #BBE5FF);
  stop-opacity: 0;
}

.jwnhq_b6g {
  stop-color: var(--svg-color--4563dd, #4563DD);
}

.mbivedcjv {
  stop-color: var(--svg-color--4f6fdf, #4F6FDF);
  stop-opacity: 0;
}

.mwct89vbj {
  stop-color: var(--svg-color--6659ff, #6659FF);
  stop-opacity: 0;
}

.mwy9hz01p {
  stop-color: var(--svg-color--b5e1ff, #B5E1FF);
}

.n0wv36bcy {
  stop-color: var(--svg-color--dde5ff, #DDE5FF);
}

.np9n_uvgu {
  stop-color: var(--svg-color--4765d7, #4765D7);
}

.oplgr6bbh {
  stop-color: var(--svg-color--6c8dff, #6C8DFF);
}

.pc7cqibkw {
  stop-color: var(--svg-color--3a5ad5, #3A5AD5);
  stop-opacity: 0.56;
}

.q4l1uybse {
  stop-color: var(--svg-color--4b4a8e, #4B4A8E);
}

.qmn7lactj {
  stop-color: var(--svg-color--3a5ad5, #3A5AD5);
}

.rbb8jubvr {
  stop-color: var(--svg-color--847aea, #847AEA);
}

.rhxlgmb_b {
  d: path("M4.5 24c-2 0-3.5-2.5-2.5-3l3.527-1c2.324.5 6.573 1.5 4.973 1.5c-2 0-3.5 2.5-6 2.5");
}

.rlq1cpo9c {
  stop-color: var(--svg-color--336aee, #336AEE);
}

.rp6x0pb8e {
  fill-rule: evenodd;
  d: path("M17 7h3a10 10 0 0 1 4 .832V21H9v-6a8 8 0 0 1 8-8");
}

.su98t29ia {
  stop-color: var(--svg-color--8099ff, #8099FF);
}

.txs1n_y3h {
  stop-color: var(--svg-color--3f3c8b, #3F3C8B);
}

.v4znxef1j {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.033 17.125c7.367.005 11.345 1.57 14.772 3.893c-1.97 1.97-3.917 3.857-6.805 3.857c-1.472 0-2.747-.468-3.884-1.076a21 21 0 0 1-1.608-.974q-.18-.117-.353-.233c-.377-.249-.74-.49-1.09-.7c-1.272-.762-2.792-1.14-4.242-1.267a13 13 0 0 0-3.088.099z");
}

.wkle3mb8m {
  stop-color: var(--svg-color--6e92ff, #6E92FF);
  stop-opacity: 0;
}

.xahg53b3p {
  stop-color: var(--svg-color--a8d5ff, #A8D5FF);
}

.xh9xu-boy {
  stop-color: var(--svg-color--7d9eff, #7D9EFF);
}

.z19y-4s6q {
  d: path("M24 7.832V21h5a1 1 0 0 0 1-1v-3c0-4.1-2.468-7.625-6-9.168");
}

.zwop2ozme {
  stop-color: var(--svg-color--6f86f9, #6F86F9);
}

</style>
