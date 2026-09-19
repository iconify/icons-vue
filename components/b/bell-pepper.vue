<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iKfZDpc)" class="o9lax4x2u"/><path fill="url(#iI5H57d)" class="o9lax4x2u"/><path class="nvfe72bsc"/><path fill="url(#ihfFzye)" class="hwegq-trw"/><path fill="url(#ilDgOwc)" class="rd-u7lpin"/><path fill="url(#ijnS5oe)" class="rd-u7lpin"/><path fill="url(#iNwBCKc)" class="rd-u7lpin"/><path fill="url(#icThzcc)" class="rd-u7lpin"/><path fill="url(#iGA3e6d)" class="t702-oulg"/><path fill="url(#iFmiosd)" class="t702-oulg"/><path fill="url(#iIytDPo)" class="t702-oulg"/><path fill="url(#iWAxyZM)" class="t702-oulg"/><path fill="url(#iyYd5Cb)" class="t702-oulg"/><path fill="url(#iKYDOib)" class="y872wabtb"/><g filter="url(#iIYZ4vb)"><path fill="url(#iqcITkb)" class="d_bqi-b8c"/></g><g filter="url(#ixtC1ZE)"><path fill="url(#ibRU1Pc)" class="s-245sbet"/></g><path fill="url(#iQBiucp)" class="y872wabtb"/><path fill="url(#iyyZuFd)" class="y872wabtb"/><g filter="url(#ijCv8Cw)"><path fill="url(#i0ryRlf)" class="dq-vi8blw"/></g><g filter="url(#icgRfQe)"><path stroke="url(#izSBs5b)" class="jttj8-arr"/></g><g filter="url(#idnSNdL)"><path class="tnnit_quc"/></g><g filter="url(#i1pBv9V)"><path class="dnvchqb6q"/></g><defs><linearGradient id="ilDgOwc" x1="7.834" x2="7.834" y1="6.429" y2="34.017" gradientUnits="userSpaceOnUse"><stop class="evk787fvf"/><stop offset=".242" class="lxbw_3b4v"/><stop offset=".437" class="bovha9byr"/><stop offset=".615" class="fe7_gfbxt"/><stop offset=".783" class="nv_ol1cbf"/><stop offset=".943" class="v_niqrbzx"/><stop offset="1" class="c3bch-exu"/></linearGradient><linearGradient id="ijnS5oe" x1="3.438" x2="10.938" y1="18" y2="18" gradientUnits="userSpaceOnUse"><stop class="t6hsylbmn"/><stop offset=".517" class="thq01d6gu"/><stop offset="1" class="drjr-ubip"/></linearGradient><linearGradient id="iGA3e6d" x1="24.174" x2="24.174" y1="4.453" y2="32.04" gradientUnits="userSpaceOnUse"><stop class="evk787fvf"/><stop offset=".231" class="z643avbga"/><stop offset=".254" class="ude0g6cxo"/><stop offset=".396" class="ogbs7nb3x"/><stop offset=".558" class="dsoa8oexu"/><stop offset=".729" class="ii53l5blk"/><stop offset=".906" class="fu8-ipz5j"/><stop offset="1" class="c3bch-exu"/></linearGradient><linearGradient id="iFmiosd" x1="17.07" x2="27.547" y1="18.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="c3bch-exu"/><stop offset="1" class="u4iqm1b9p"/></linearGradient><linearGradient id="iIytDPo" x1="20.875" x2="29" y1="16.938" y2="16.938" gradientUnits="userSpaceOnUse"><stop class="l27z85bzf"/><stop offset=".569" class="bz2bjybwx"/><stop offset="1" class="q6bwxgbcj"/></linearGradient><linearGradient id="iKYDOib" x1="16.004" x2="16.004" y1="5.426" y2="33.013" gradientUnits="userSpaceOnUse"><stop class="evk787fvf"/><stop offset=".242" class="lxbw_3b4v"/><stop offset=".437" class="bovha9byr"/><stop offset=".615" class="fe7_gfbxt"/><stop offset=".783" class="nv_ol1cbf"/><stop offset=".943" class="v_niqrbzx"/><stop offset="1" class="c3bch-exu"/></linearGradient><linearGradient id="iqcITkb" x1="21.419" x2="26.5" y1="20.886" y2="20.886" gradientUnits="userSpaceOnUse"><stop class="jirspccyh"/><stop offset=".274" class="lk2n6sern"/><stop offset="1" class="ilvgpkb2m"/></linearGradient><linearGradient id="ibRU1Pc" x1="10.185" x2="7.875" y1="16.5" y2="16.5" gradientUnits="userSpaceOnUse"><stop class="quag-tb6g"/><stop offset=".513" class="iy6vg5s_x"/><stop offset="1" class="zusnncbrh"/></linearGradient><linearGradient id="iQBiucp" x1="10.004" x2="22.004" y1="16.375" y2="16.375" gradientUnits="userSpaceOnUse"><stop class="da43fmbzq"/><stop offset=".208" class="jwv05fbsi"/><stop offset=".609" class="qu_081xxu"/><stop offset="1" class="aisw_hb0j"/></linearGradient><linearGradient id="izSBs5b" x1="19.244" x2="19.244" y1="8.868" y2="25.993" gradientUnits="userSpaceOnUse"><stop offset=".427" class="mc3jpy5gm"/><stop offset="1" class="thdzj558s"/></linearGradient><radialGradient id="iKfZDpc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00002 -2.84373 3.62498 -3.8242 19 5.656)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="v75krblmo"/><stop offset=".53" class="o_jfybh7x"/><stop offset=".73" class="oh_d74gnk"/><stop offset=".945" class="rlfmujbcy"/></radialGradient><radialGradient id="iI5H57d" cx="0" cy="0" r="1" gradientTransform="matrix(-1 .625 -.67575 -1.08122 19.5 2.844)" gradientUnits="userSpaceOnUse"><stop class="hwcqckb3v"/><stop offset="1" class="exvkfxbbn"/></radialGradient><radialGradient id="ihfFzye" cx="0" cy="0" r="1" gradientTransform="rotate(143.643 8.185 6.703)scale(5.58772)" gradientUnits="userSpaceOnUse"><stop class="pszhdipgk"/><stop offset=".577" class="j4orskb3f"/><stop offset="1" class="j0zseeb2b"/></radialGradient><radialGradient id="iNwBCKc" cx="0" cy="0" r="1" gradientTransform="matrix(8.93748 19.56246 -17.03576 7.78312 -.313 11.125)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="ppy_bqbgj"/><stop offset="1" class="ur8sm4bhg"/></radialGradient><radialGradient id="icThzcc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.31245 6.93752 -6.524 -3.115 9.688 7)" gradientUnits="userSpaceOnUse"><stop class="j3_vxgb-l"/><stop offset="1" class="t6uvvutmv"/></radialGradient><radialGradient id="iWAxyZM" cx="0" cy="0" r="1" gradientTransform="matrix(-8.6876 27.49997 -11.72474 -3.704 30 9.063)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="q72dtnbjs"/><stop offset=".767" class="l4o-wccdy"/></radialGradient><radialGradient id="iyYd5Cb" cx="0" cy="0" r="1" gradientTransform="matrix(4.3125 8 -10.57885 5.70265 26.5 10.5)" gradientUnits="userSpaceOnUse"><stop class="uctroxvgp"/><stop offset="1" class="u0i76tbym"/></radialGradient><radialGradient id="iyyZuFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 23.9375 -25.4732 0 16.004 9.5)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="hehs4nbjr"/><stop offset=".881" class="z3h-vgb7n"/></radialGradient><radialGradient id="i0ryRlf" cx="0" cy="0" r="1" gradientTransform="matrix(5.375 -2.625 3.14946 6.4489 13.813 11.625)" gradientUnits="userSpaceOnUse"><stop class="dg6-9qb1p"/><stop offset=".387" class="sotl97bui"/><stop offset="1" class="tpcvbccri"/></radialGradient><filter id="iIYZ4vb" width="7.598" height="21.931" x="18.339" y="6.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32975" stdDeviation="1"/></filter><filter id="ixtC1ZE" width="5.881" height="21.938" x="7.244" y="7.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32975" stdDeviation=".5"/></filter><filter id="ijCv8Cw" width="11.438" height="9.03" x="10.281" y="5.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32975" stdDeviation="1"/></filter><filter id="icgRfQe" width="7.145" height="21.919" x="15.859" y="6.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32975" stdDeviation="1"/></filter><filter id="idnSNdL" width="5.812" height="5.661" x="23.415" y="6.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32975" stdDeviation=".5"/></filter><filter id="i1pBv9V" width="5.985" height="6.783" x="16.86" y="7.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32975" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bell-pepper" /></template>
<style>
.aisw_hb0j {
  stop-color: var(--svg-color--83b84c, #83B84C);
}

.bovha9byr {
  stop-color: var(--svg-color--438f0d, #438F0D);
}

.bz2bjybwx {
  stop-color: var(--svg-color--7db459, #7DB459);
}

.c3bch-exu {
  stop-color: var(--svg-color--008461, #008461);
}

.d_bqi-b8c {
  d: path("M23.938 18.346c0-7.682-1.778-9.85-3.038-10.283c-.592 6.009-.889 16.646 0 17.687c.89 1.04 2.173-1.603 3.038-1.437c-.075-1.219 0-.216 0-5.967");
}

.da43fmbzq {
  stop-color: var(--svg-color--538058, #538058);
}

.dg6-9qb1p {
  stop-color: var(--svg-color--629840, #629840);
}

.dnvchqb6q {
  fill: var(--svg-color--a3d061, #A3D061);
  d: path("M18.36 12.685c.144-1.905 1.03-4.13 1.738-3.737c2.81 1.564.276 2.962-1.738 3.737");
}

.dq-vi8blw {
  d: path("M13.757 7.682c-.817.05-1.324.854-1.476 1.25c1.4 1.292 4.27 3.85 4.542 3.75s2.044-2.875 2.896-4.25l-.625-.75c-1.438-.02-4.519-.05-5.337 0");
}

.drjr-ubip {
  stop-color: var(--svg-color--507a57, #507A57);
}

.dsoa8oexu {
  stop-color: var(--svg-color--3c8e16, #3C8E16);
}

.evk787fvf {
  stop-color: var(--svg-color--4e9100, #4E9100);
}

.exvkfxbbn {
  stop-color: var(--svg-color--ffff5c, #FFFF5C);
  stop-opacity: 0;
}

.fe7_gfbxt {
  stop-color: var(--svg-color--368d1e, #368D1E);
}

.ft5dv1b6b {
  fill: none;
}

.fu8-ipz5j {
  stop-color: var(--svg-color--10874d, #10874D);
}

.hehs4nbjr {
  stop-color: var(--svg-color--3d6176, #3D6176);
  stop-opacity: 0;
}

.hwcqckb3v {
  stop-color: var(--svg-color--ffff5e, #FFFF5E);
}

.hwegq-trw {
  d: path("M16.004 13.34a4.17 4.17 0 1 0 0-8.34a4.17 4.17 0 0 0 0 8.34");
}

.ii53l5blk {
  stop-color: var(--svg-color--2a8b2d, #2A8B2D);
}

.ilvgpkb2m {
  stop-color: var(--svg-color--71a868, #71A868);
}

.iy6vg5s_x {
  stop-color: var(--svg-color--3e6956, #3E6956);
}

.j0zseeb2b {
  stop-color: var(--svg-color--f5ff4b, #F5FF4B);
  stop-opacity: 0;
}

.j3_vxgb-l {
  stop-color: var(--svg-color--7caa51, #7CAA51);
}

.j4orskb3f {
  stop-color: var(--svg-color--ceec3a, #CEEC3A);
}

.jirspccyh {
  stop-color: var(--svg-color--36812e, #36812E);
}

.jttj8-arr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.484 8.868c.417.334 1.287 1.225 1.438 2.125c.15.9.062 10.375 0 15");
}

.jwv05fbsi {
  stop-color: var(--svg-color--4a844d, #4A844D);
}

.l27z85bzf {
  stop-color: var(--svg-color--769f37, #769F37);
}

.l4o-wccdy {
  stop-color: var(--svg-color--36616c, #36616C);
}

.lk2n6sern {
  stop-color: var(--svg-color--68a166, #68A166);
}

.lxbw_3b4v {
  stop-color: var(--svg-color--4b9103, #4B9103);
}

.mc3jpy5gm {
  stop-color: var(--svg-color--95c360, #95C360);
}

.nv_ol1cbf {
  stop-color: var(--svg-color--238a36, #238A36);
}

.nvfe72bsc {
  fill: var(--svg-color--a8c245, #A8C245);
  d: path("M16.004 13.34a4.17 4.17 0 1 0 0-8.34a4.17 4.17 0 0 0 0 8.34");
}

.o_jfybh7x {
  stop-color: var(--svg-color--f5ef41, #F5EF41);
}

.o9lax4x2u {
  d: path("M17.594 11.47h-.01l-2.12-3.75c-.63-1.2-.6-2.6.08-3.77c.69-1.22 2.02-1.95 3.42-1.95h.04c.55 0 1 .45 1 1s-.45 1-1 1h-.05c-.7 0-1.35.36-1.7.96c-.32.56-.33 1.23-.04 1.81l2.1 3.71v.01z");
}

.ogbs7nb3x {
  stop-color: var(--svg-color--479009, #479009);
}

.oh_d74gnk {
  stop-color: var(--svg-color--edee43, #EDEE43);
}

.ppy_bqbgj {
  stop-color: var(--svg-color--375e6f, #375E6F);
  stop-opacity: 0;
}

.pszhdipgk {
  stop-color: var(--svg-color--f7ff4d, #F7FF4D);
}

.q6bwxgbcj {
  stop-color: var(--svg-color--7db24e, #7DB24E);
}

.q72dtnbjs {
  stop-color: var(--svg-color--3b5e72, #3B5E72);
  stop-opacity: 0;
}

.qu_081xxu {
  stop-color: var(--svg-color--70a366, #70A366);
}

.quag-tb6g {
  stop-color: var(--svg-color--25533d, #25533D);
}

.rd-u7lpin {
  d: path("M8.494 30c-2.16 0-3.97-1.66-4.16-3.81l-1.32-15.12A3.75 3.75 0 0 1 6.754 7h2.78c1.73 0 3.12 1.4 3.12 3.12v15.7A4.16 4.16 0 0 1 8.494 30");
}

.rlfmujbcy {
  stop-color: var(--svg-color--b6c24b, #B6C24B);
}

.s-245sbet {
  d: path("M8.875 10.125c.61-1.145 1.73-1.73 2.313-2l.937 19.938c-1.042-.396-3.1-.384-3.688-2.063c-.437-1.25-.062-14.937.438-15.875");
}

.sotl97bui {
  stop-color: var(--svg-color--679d43, #679D43);
}

.t6hsylbmn {
  stop-color: var(--svg-color--55825f, #55825F);
}

.t6uvvutmv {
  stop-color: var(--svg-color--73a645, #73A645);
  stop-opacity: 0;
}

.t702-oulg {
  d: path("M23.514 30c2.16 0 3.97-1.66 4.16-3.81l1.31-15.11A3.74 3.74 0 0 0 25.254 7h-2.78c-1.73 0-3.12 1.4-3.12 3.12v15.7a4.16 4.16 0 0 0 4.16 4.18");
}

.thdzj558s {
  stop-color: var(--svg-color--8cbd5d, #8CBD5D);
  stop-opacity: 0;
}

.thq01d6gu {
  stop-color: var(--svg-color--3c7b4f, #3C7B4F);
}

.tnnit_quc {
  fill: var(--svg-color--afd962, #AFD962);
  d: path("M24.415 11.603c.659-1.68 2.27-4.093 2.907-3.594c2.533 1.981-.838 2.948-2.907 3.594");
}

.tpcvbccri {
  stop-color: var(--svg-color--87b73d, #87B73D);
}

.u0i76tbym {
  stop-color: var(--svg-color--a7d05f, #A7D05F);
  stop-opacity: 0;
}

.u4iqm1b9p {
  stop-color: var(--svg-color--008461, #008461);
  stop-opacity: 0;
}

.uctroxvgp {
  stop-color: var(--svg-color--abd45c, #ABD45C);
}

.ude0g6cxo {
  stop-color: var(--svg-color--4b9104, #4B9104);
}

.ur8sm4bhg {
  stop-color: var(--svg-color--365c6d, #365C6D);
}

.v_niqrbzx {
  stop-color: var(--svg-color--0a8654, #0A8654);
}

.v75krblmo {
  stop-color: var(--svg-color--b9be4f, #B9BE4F);
}

.y872wabtb {
  d: path("M16.004 30c-3.31 0-6-2.69-6-6V10.75c0-2.07 1.68-3.75 3.75-3.75h4.5c2.07 0 3.75 1.68 3.75 3.75V24c0 3.31-2.69 6-6 6");
}

.z3h-vgb7n {
  stop-color: var(--svg-color--415f7a, #415F7A);
}

.z643avbga {
  stop-color: var(--svg-color--4c9103, #4C9103);
}

.zusnncbrh {
  stop-color: var(--svg-color--447159, #447159);
  stop-opacity: 0;
}

</style>
