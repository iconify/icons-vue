<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="ikd2PFe" width="16" height="15" x="14" y="15" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path clip-rule="evenodd" class="zm5if97iu"/></mask><mask id="ioR2WFb" width="20" height="20" x="2" y="2" maskUnits="userSpaceOnUse" style="mask-type:alpha"><circle class="shu3xdl9q"/></mask><g class="ft5dv1b6b"><path stroke="url(#iUcxUPc)" class="nbafofb8n"/><g filter="url(#iHRp5db)" mask="url(#ikd2PFe)"><path class="fqrnqo6cf"/></g><path fill="url(#iYklx2X)" clip-rule="evenodd" class="zxgqnac6a"/><path fill="url(#iarUoOd)" clip-rule="evenodd" class="z5pl2xzcq"/><path fill="url(#inpgdIr)" clip-rule="evenodd" class="paxkombtz"/><path fill="url(#igi4Wue)" clip-rule="evenodd" class="pe-hcdwje"/><path fill="url(#iIlKFhe)" clip-rule="evenodd" class="rk76dpbdf"/><path fill="url(#izUfhxb)" clip-rule="evenodd" class="r6e49jbvr"/><path fill="url(#ilgQ5De)" clip-rule="evenodd" class="ulo4jtbxu"/><path fill="url(#ibBO25d)" clip-rule="evenodd" class="i6qc_hb1x"/><path fill="url(#iBtYbAc)" clip-rule="evenodd" class="wgkyvfbab"/><path fill="url(#i0emXXc)" clip-rule="evenodd" class="okaqvwfuz"/><path fill="url(#i5zwZqe)" clip-rule="evenodd" class="rcmt5nc4j"/><path fill="url(#icqdgqe)" clip-rule="evenodd" class="ds5120b1f"/><path fill="url(#itxwXXc)" clip-rule="evenodd" class="gra8ls-jf"/><g filter="url(#iDqIfyB)" mask="url(#ioR2WFb)"><path clip-rule="evenodd" class="yys_6ac2t"/></g><defs><linearGradient id="iUcxUPc" x1="25.022" x2="22.5" y1="22.762" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="cmv-3kb7p"/><stop offset=".443" class="j_1bc4bde"/><stop offset=".677" class="nb43gv8ag"/><stop offset="1" class="jlnlxeblx"/></linearGradient><linearGradient id="iYklx2X" x1="14.5" x2="22.5" y1="15.5" y2="23.5" gradientUnits="userSpaceOnUse"><stop class="cgvq1zbwe"/><stop offset=".766" class="biyk_42be"/></linearGradient><linearGradient id="iarUoOd" x1="5.5" x2="12" y1="4.5" y2="12" gradientUnits="userSpaceOnUse"><stop class="izngjubak"/><stop offset=".526" class="pib6chbsn"/><stop offset="1" class="njzgzhyyn"/></linearGradient><linearGradient id="inpgdIr" x1="12" x2="2.5" y1="12" y2="9" gradientUnits="userSpaceOnUse"><stop class="s5tb11dwq"/><stop offset=".516" class="wpg6z1bux"/><stop offset="1" class="rc5drub9v"/></linearGradient><linearGradient id="igi4Wue" x1="12" x2="2" y1="12" y2="14" gradientUnits="userSpaceOnUse"><stop class="y8n005blb"/><stop offset=".49" class="q0tt300qq"/><stop offset="1" class="n3e7_2bpk"/></linearGradient><linearGradient id="iIlKFhe" x1="12" x2="4.5" y1="12" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="t1ipivg1i"/><stop offset=".443" class="l53s6zsvi"/><stop offset="1" class="fz5r8ubck"/></linearGradient><linearGradient id="izUfhxb" x1="12" x2="9" y1="12" y2="21.5" gradientUnits="userSpaceOnUse"><stop class="hyq0yta2j"/><stop offset=".516" class="b542ieywi"/><stop offset="1" class="an3pmc6rt"/></linearGradient><linearGradient id="ilgQ5De" x1="12" x2="13.657" y1="12" y2="22" gradientUnits="userSpaceOnUse"><stop class="i3gm9lsll"/><stop offset=".51" class="jh8tc50oh"/><stop offset="1" class="t-uwemz_z"/></linearGradient><linearGradient id="ibBO25d" x1="19" x2="12" y1="19.5" y2="12" gradientUnits="userSpaceOnUse"><stop class="yff6ki9ni"/><stop offset=".5" class="br_in-kel"/><stop offset="1" class="nkorvvbdu"/></linearGradient><linearGradient id="iBtYbAc" x1="21.5" x2="12" y1="15" y2="12" gradientUnits="userSpaceOnUse"><stop class="tu59kf6wy"/><stop offset=".526" class="eepsn249m"/><stop offset="1" class="hcs31b7rs"/></linearGradient><linearGradient id="i0emXXc" x1="21.5" x2="12" y1="10" y2="12" gradientUnits="userSpaceOnUse"><stop class="hr8am0dus"/><stop offset=".516" class="k9lzvuxzs"/><stop offset="1" class="ed4a841rj"/></linearGradient><linearGradient id="i5zwZqe" x1="19.5" x2="12" y1="5.5" y2="12" gradientUnits="userSpaceOnUse"><stop class="i30y_lbur"/><stop offset=".5" class="v6lnmfblg"/><stop offset="1" class="llf5bkbxb"/></linearGradient><linearGradient id="icqdgqe" x1="15" x2="12" y1="2.5" y2="12" gradientUnits="userSpaceOnUse"><stop class="rrlhr_dah"/><stop offset="1" class="rhz58sbpe"/></linearGradient><linearGradient id="itxwXXc" x1="9.5" x2="12" y1="2.5" y2="12" gradientUnits="userSpaceOnUse"><stop class="v2rs84bpp"/><stop offset="1" class="lgu7q-95o"/></linearGradient><filter id="iHRp5db" width="14.75" height="14.25" x="15.75" y="14.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29825" stdDeviation=".5"/></filter><filter id="iDqIfyB" width="21" height="21" x="1.5" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29825" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:lollipop" /></template>
<style>
.an3pmc6rt {
  stop-color: var(--svg-color--b83a8b, #B83A8B);
}

.b542ieywi {
  stop-color: var(--svg-color--b93a90, #B93A90);
}

.biyk_42be {
  stop-color: var(--svg-color--b05c92, #B05C92);
  stop-opacity: 0;
}

.br_in-kel {
  stop-color: var(--svg-color--6d95f1, #6D95F1);
}

.cgvq1zbwe {
  stop-color: var(--svg-color--b05c92, #B05C92);
}

.cmv-3kb7p {
  stop-color: var(--svg-color--fddab2, #FDDAB2);
}

.ds5120b1f {
  fill-rule: evenodd;
  d: path("M17.135 3.417A9.95 9.95 0 0 0 12.096 2c2.141 4.27 1.64 6.836-.096 10c0 0 5.033-1.703 5.134-8.583");
}

.ed4a841rj {
  stop-color: var(--svg-color--edc47e, #EDC47E);
}

.eepsn249m {
  stop-color: var(--svg-color--76c5a0, #76C5A0);
}

.fqrnqo6cf {
  stroke: var(--svg-color--ffe5c1, #FFE5C1);
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29 27.5L17.25 16.25");
}

.ft5dv1b6b {
  fill: none;
}

.fz5r8ubck {
  stop-color: var(--svg-color--ff916d, #FF916D);
}

.gra8ls-jf {
  fill-rule: evenodd;
  d: path("M12.156 2.001L12 2a9.95 9.95 0 0 0-4.916 1.29C11.228 5.88 12.116 8.218 12 12c0 0 3.507-3.991.156-9.999");
}

.hcs31b7rs {
  stop-color: var(--svg-color--7ec1a4, #7EC1A4);
}

.hr8am0dus {
  stop-color: var(--svg-color--ffff90, #FFFF90);
}

.hyq0yta2j {
  stop-color: var(--svg-color--bd4c97, #BD4C97);
}

.i30y_lbur {
  stop-color: var(--svg-color--ffb281, #FFB281);
}

.i3gm9lsll {
  stop-color: var(--svg-color--b976db, #B976DB);
}

.i6qc_hb1x {
  fill-rule: evenodd;
  d: path("M16.866 20.738C10.96 17.211 12 12 12 12c2.095 3.32 3.973 4.747 8.614 5.082a10.05 10.05 0 0 1-3.748 3.656");
}

.izngjubak {
  stop-color: var(--svg-color--5e9beb, #5E9BEB);
}

.j_1bc4bde {
  stop-color: var(--svg-color--ea9bb3, #EA9BB3);
}

.jh8tc50oh {
  stop-color: var(--svg-color--af64d6, #AF64D6);
}

.jlnlxeblx {
  stop-color: var(--svg-color--c969ab, #C969AB);
}

.k9lzvuxzs {
  stop-color: var(--svg-color--ffd677, #FFD677);
}

.l53s6zsvi {
  stop-color: var(--svg-color--fe8765, #FE8765);
}

.lgu7q-95o {
  stop-color: var(--svg-color--bc79dd, #BC79DD);
}

.llf5bkbxb {
  stop-color: var(--svg-color--f18c79, #F18C79);
}

.n3e7_2bpk {
  stop-color: var(--svg-color--ffe885, #FFE885);
}

.nb43gv8ag {
  stop-color: var(--svg-color--e37dc3, #E37DC3);
}

.nbafofb8n {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--3-5px, 3.5px);
  d: path("M28.25 28.25L16.5 17");
}

.njzgzhyyn {
  stop-color: var(--svg-color--7ea4f4, #7EA4F4);
}

.nkorvvbdu {
  stop-color: var(--svg-color--7ca0f2, #7CA0F2);
}

.okaqvwfuz {
  fill-rule: evenodd;
  d: path("M21.999 12.156L22 12a9.96 9.96 0 0 0-1.292-4.92C18.038 10.964 15.792 11.881 12 12c0 0 3.991 3.507 9.999.156");
}

.paxkombtz {
  fill-rule: evenodd;
  d: path("M2 11.907a9.95 9.95 0 0 1 1.417-5.042C10.297 6.967 12 12 12 12c-3.333-1.748-5.71-2.094-10-.093");
}

.pe-hcdwje {
  fill-rule: evenodd;
  d: path("M3.293 16.921A9.96 9.96 0 0 1 2 11.844C8.01 8.494 12 12 12 12c-3.783.095-6.017 1.146-8.707 4.921");
}

.pib6chbsn {
  stop-color: var(--svg-color--6fa0f3, #6FA0F3);
}

.q0tt300qq {
  stop-color: var(--svg-color--ebc16a, #EBC16A);
}

.r6e49jbvr {
  fill-rule: evenodd;
  d: path("M6.865 20.583C6.967 13.703 12 12 12 12c-1.827 3.297-2.028 5.775-.093 10a9.95 9.95 0 0 1-5.042-1.417");
}

.rc5drub9v {
  stop-color: var(--svg-color--74d099, #74D099);
}

.rcmt5nc4j {
  fill-rule: evenodd;
  d: path("M17.082 3.386a10.05 10.05 0 0 1 3.656 3.748C17.211 13.04 12 12 12 12c3.107-1.928 4.712-3.772 5.082-8.614");
}

.rhz58sbpe {
  stop-color: var(--svg-color--c2509a, #C2509A);
}

.rk76dpbdf {
  fill-rule: evenodd;
  d: path("M6.921 20.616a10.05 10.05 0 0 1-3.66-3.75C6.79 10.959 12 12 12 12c-3.22 1.904-4.58 4.027-5.079 8.616");
}

.rrlhr_dah {
  stop-color: var(--svg-color--fc70bd, #FC70BD);
}

.s5tb11dwq {
  stop-color: var(--svg-color--7dc3a2, #7DC3A2);
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.t-uwemz_z {
  stop-color: var(--svg-color--9b4bc5, #9B4BC5);
}

.t1ipivg1i {
  stop-color: var(--svg-color--ed8876, #ED8876);
}

.tu59kf6wy {
  stop-color: var(--svg-color--90f7ba, #90F7BA);
}

.ulo4jtbxu {
  fill-rule: evenodd;
  d: path("M11.844 21.999C8.494 15.99 12 12 12 12c.173 3.837 1.18 6.105 4.92 8.708a9.95 9.95 0 0 1-5.076 1.29");
}

.v2rs84bpp {
  stop-color: var(--svg-color--db8bfb, #DB8BFB);
}

.v6lnmfblg {
  stop-color: var(--svg-color--ff9372, #FF9372);
}

.wgkyvfbab {
  fill-rule: evenodd;
  d: path("M20.583 17.135C13.703 17.033 12 12 12 12c3.342 1.803 5.852 2.093 10 .094a9.95 9.95 0 0 1-1.417 5.04");
}

.wpg6z1bux {
  stop-color: var(--svg-color--71c398, #71C398);
}

.y8n005blb {
  stop-color: var(--svg-color--eac27c, #EAC27C);
}

.yff6ki9ni {
  stop-color: var(--svg-color--5e92f8, #5E92F8);
}

.yys_6ac2t {
  fill: var(--svg-color--000, #000);
  fill-opacity: var(--svg-fill-opacity--0-32, 0.32);
  fill-rule: evenodd;
  d: path("M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2S2 6.477 2 12s4.477 10 10 10M2.125 12c0-5.454 4.421-9.875 9.875-9.875S21.875 6.546 21.875 12S17.454 21.875 12 21.875S2.125 17.454 2.125 12");
}

.z5pl2xzcq {
  fill-rule: evenodd;
  d: path("M3.386 6.918a10.05 10.05 0 0 1 3.75-3.658C13.351 6.72 12 12 12 12C9.96 8.791 8.015 7.264 3.386 6.918");
}

.zm5if97iu {
  fill: var(--svg-color--212121, #212121);
  fill-rule: evenodd;
  d: path("M15.236 15.79a1.75 1.75 0 0 1 2.474-.054l11.75 11.25a1.75 1.75 0 0 1-2.42 2.528l-11.75-11.25a1.75 1.75 0 0 1-.054-2.474");
}

.zxgqnac6a {
  fill-rule: evenodd;
  d: path("M15.236 15.79a1.75 1.75 0 0 1 2.474-.054l11.75 11.25a1.75 1.75 0 0 1-2.42 2.528l-11.75-11.25a1.75 1.75 0 0 1-.054-2.474");
}

</style>
