<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path class="ns5t1vbej"/><path fill="url(#iG5zTnB)" class="hj0f2lt9n"/><path fill="url(#iTVYo8d)" class="hj0f2lt9n"/><path fill="url(#iAZItKe)" class="hj0f2lt9n"/><g filter="url(#isEiTub)"><path fill="url(#iI0Be8y)" class="gjwexsblw"/></g><path class="wo-jpe6dv"/><path fill="url(#iBpRQYM)" class="fal3qogrm"/><path fill="url(#ii9lpDe)" class="fal3qogrm"/><path fill="url(#iOjXXOd)" class="fal3qogrm"/><g filter="url(#iV9wUnb)"><path fill="url(#i8xalzd)" class="l93ohit5i"/><path fill="url(#iwgClSc)" class="l93ohit5i"/></g><path fill="url(#icV4Owb)" class="eb0c8s2sl"/><path fill="url(#isfZZVb)" class="eb0c8s2sl"/><path fill="url(#ieIdP1c)" class="eb0c8s2sl"/><path fill="url(#ika8X2c)" class="eb0c8s2sl"/><path fill="url(#iQZvOhb)" class="eb0c8s2sl"/><g filter="url(#icailyd)"><path class="ckej57bji"/></g><g filter="url(#iZDJ1Hb)"><path class="oo9nsccte"/></g><path fill="url(#i1LHCjd)" class="o2oyy1bac"/><path fill="url(#isykUlc)" class="o2oyy1bac"/><path fill="url(#iT2X8Id)" class="o2oyy1bac"/><path fill="url(#iAfNVvd)" class="t69p4786v"/><path fill="url(#iykay0b)" class="t69p4786v"/><path fill="url(#iZMSH4c)" class="t69p4786v"/><g filter="url(#iaIBwIc)"><path class="pz7rffb7j"/></g><path fill="url(#iiCmyEe)" class="c-zl7tb5f"/><path fill="url(#imILVCb)" class="c-zl7tb5f"/><path fill="url(#i8TD2ib)" class="c-zl7tb5f"/><path fill="url(#ivjA2rs)" class="c-zl7tb5f"/><path stroke="url(#igLDSur)" class="pen27gfft"/><path stroke="url(#idppxxd)" class="pen27gfft"/><path stroke="url(#iq56Hxd)" class="w_k2f7dqm"/><g filter="url(#i0edccc)"><path stroke="url(#iT17AEs)" class="yocn5ubux"/></g><g filter="url(#ixxettb)"><path class="shlofhbsw"/></g><path fill="url(#i21m5gc)" class="ta1o4fycd"/><path fill="url(#icxeV0d)" class="ta1o4fycd"/><path fill="url(#iZzQIIb)" class="ta1o4fycd"/><path fill="url(#iX6Q4YN)" class="ta1o4fycd"/><path fill="url(#iZk2lVf)" class="ta1o4fycd"/><g filter="url(#iWGYwgc)"><path fill="url(#iB8838c)" class="tdfzryppf"/></g></g><defs><radialGradient id="iAZItKe" cx="0" cy="0" r="1" gradientTransform="rotate(142.716 12.878 8.159)scale(3.45634 3.61664)" gradientUnits="userSpaceOnUse"><stop class="pvg_dn36h"/><stop offset="1" class="bp63wtbqk"/></radialGradient><radialGradient id="iOjXXOd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.795 2.75 -2.87753 -2.92462 10.38 6.006)" gradientUnits="userSpaceOnUse"><stop class="pvg_dn36h"/><stop offset="1" class="bp63wtbqk"/></radialGradient><radialGradient id="i8xalzd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26563 -.84375 2.0565 -5.52207 8.052 8.709)" gradientUnits="userSpaceOnUse"><stop class="wrd9bsb_n"/><stop offset="1" class="g610b8hri"/></radialGradient><radialGradient id="icV4Owb" cx="0" cy="0" r="1" gradientTransform="matrix(0 24.5269 -23.9742 0 15.945 5.24)" gradientUnits="userSpaceOnUse"><stop class="cl2_31knn"/><stop offset="1" class="tt4jhcbao"/></radialGradient><radialGradient id="isfZZVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.1719 22.1925 0 16 28.052)" gradientUnits="userSpaceOnUse"><stop class="nfqwgzpyj"/><stop offset="1" class="wq4qn0v9e"/></radialGradient><radialGradient id="ieIdP1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 23.6719 -24.1663 0 16 6.615)" gradientUnits="userSpaceOnUse"><stop offset=".946" class="p-r478dug"/><stop offset="1" class="hoxqlnb2w"/></radialGradient><radialGradient id="ika8X2c" cx="0" cy="0" r="1" gradientTransform="matrix(-24.4375 0 0 -17.875 25.255 19.943)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="iju_516bg"/><stop offset="1" class="gzxj1cbun"/></radialGradient><radialGradient id="iQZvOhb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.87493 9.07814 -9.25503 -5.9894 25.255 5.927)" gradientUnits="userSpaceOnUse"><stop class="n5-vvdsog"/><stop offset="1" class="m7ke-sbjz"/></radialGradient><radialGradient id="iT2X8Id" cx="0" cy="0" r="1" gradientTransform="matrix(-.44799 -1.68959 1.82138 -.48293 12.161 16.474)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iZMSH4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.44799 -1.68959 1.82138 -.48293 20.161 16.474)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="i8TD2ib" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59376 3.15624 -2.80438 -2.30461 18.974 21.037)" gradientUnits="userSpaceOnUse"><stop class="hgkwwhboi"/><stop offset=".794" class="rj2yt7rxc"/></radialGradient><radialGradient id="ivjA2rs" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.6875 8.48106 0 16 27.6)" gradientUnits="userSpaceOnUse"><stop offset=".915" class="xn_isivjd"/><stop offset="1" class="dx2g9wbpq"/></radialGradient><radialGradient id="igLDSur" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.71875 -2.18838 0 14.249 22.838)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="e9ucyqbno"/><stop offset="1" class="smhtebbjh"/></radialGradient><radialGradient id="idppxxd" cx="0" cy="0" r="1" gradientTransform="rotate(70.994 -8.113 20.98)scale(2.97467 7.41114)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p981guc6t"/><stop offset="1" class="mjp0ecb6a"/></radialGradient><radialGradient id="iq56Hxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2035 1.69185 -4.7471 -.571 17.942 22.865)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p981guc6t"/><stop offset="1" class="mjp0ecb6a"/></radialGradient><radialGradient id="iX6Q4YN" cx="0" cy="0" r="1" gradientTransform="matrix(4.24468 -1.44104 .64706 1.90597 13.86 20.55)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="lm-pdjb-m"/><stop offset=".935" class="z17z3-a-u"/></radialGradient><radialGradient id="iZk2lVf" cx="0" cy="0" r="1" gradientTransform="rotate(145.376 5.522 12.379)scale(.79749 .48374)" gradientUnits="userSpaceOnUse"><stop class="xbybj_nwx"/><stop offset="1" class="unvvv2nza"/></radialGradient><linearGradient id="iG5zTnB" x1="24.786" x2="25.505" y1="9.787" y2="7.943" gradientUnits="userSpaceOnUse"><stop class="xghm3mbec"/><stop offset="1" class="b0m-kjk1r"/></linearGradient><linearGradient id="iTVYo8d" x1="21.255" x2="22.286" y1="5.724" y2="6.631" gradientUnits="userSpaceOnUse"><stop class="xghm3mbec"/><stop offset="1" class="b0m-kjk1r"/></linearGradient><linearGradient id="iI0Be8y" x1="25.474" x2="23.442" y1="8.474" y2="9.162" gradientUnits="userSpaceOnUse"><stop class="wrd9bsb_n"/><stop offset="1" class="bklxob5ur"/></linearGradient><linearGradient id="iBpRQYM" x1="7.224" x2="6.505" y1="9.787" y2="7.943" gradientUnits="userSpaceOnUse"><stop class="xghm3mbec"/><stop offset="1" class="b0m-kjk1r"/></linearGradient><linearGradient id="ii9lpDe" x1="6.286" x2="6.161" y1="11.881" y2="8.381" gradientUnits="userSpaceOnUse"><stop class="l_5cl4byj"/><stop offset="1" class="tn5zlwlzs"/></linearGradient><linearGradient id="iwgClSc" x1="7.364" x2="5.786" y1="9.615" y2="7.865" gradientUnits="userSpaceOnUse"><stop class="ij14mzb3i"/><stop offset=".435" class="l0k8m4kjf"/></linearGradient><linearGradient id="i1LHCjd" x1="12.75" x2="11.882" y1="16.052" y2="16.052" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="isykUlc" x1="12.984" x2="12.984" y1="17.592" y2="16.169" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iAfNVvd" x1="20.75" x2="19.882" y1="16.052" y2="16.052" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iykay0b" x1="20.984" x2="20.984" y1="17.592" y2="16.169" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iiCmyEe" x1="16" x2="16" y1="18.13" y2="26.787" gradientUnits="userSpaceOnUse"><stop class="okcl04jvm"/><stop offset="1" class="dc42xfuch"/></linearGradient><linearGradient id="imILVCb" x1="15.443" x2="15.443" y1="27.568" y2="23.443" gradientUnits="userSpaceOnUse"><stop class="psld4vyrv"/><stop offset="1" class="ti104777k"/></linearGradient><linearGradient id="iT17AEs" x1="12.328" x2="19.843" y1="22.78" y2="22.78" gradientUnits="userSpaceOnUse"><stop class="rj14edb9i"/><stop offset=".289" class="zkps8y4ss"/><stop offset=".445" class="zkps8y4ss"/><stop offset=".534" class="rj14edb9i"/><stop offset="1" class="zkps8y4ss"/></linearGradient><linearGradient id="i21m5gc" x1="15.583" x2="16.08" y1="19.068" y2="20.852" gradientUnits="userSpaceOnUse"><stop class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="icxeV0d" x1="15.764" x2="15.764" y1="19.426" y2="18.222" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="iZzQIIb" x1="15.161" x2="15.161" y1="21.446" y2="19.625" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iB8838c" x1="28.95" x2="20.185" y1="12.656" y2="17.511" gradientUnits="userSpaceOnUse"><stop class="m1gpd0z2n"/><stop offset="1" class="e-uzvzb4t"/></linearGradient><filter id="isEiTub" width="5.28" height="5.38" x="21.735" y="6.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.678431 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4110"/></filter><filter id="iV9wUnb" width="5.28" height="5.38" x="4.895" y="6.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.678431 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4110"/></filter><filter id="icailyd" width="2.5" height="3.986" x="10.438" y="14.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4110" stdDeviation=".25"/></filter><filter id="iZDJ1Hb" width="2.5" height="3.986" x="18.437" y="14.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4110" stdDeviation=".25"/></filter><filter id="iaIBwIc" width="11.759" height="10.345" x="9.678" y="17.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4110" stdDeviation=".5"/></filter><filter id="i0edccc" width="7.719" height="2.484" x="12.14" y="21.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4110" stdDeviation=".125"/></filter><filter id="ixxettb" width="5.027" height="3.975" x="13.215" y="18.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4110" stdDeviation=".35"/></filter><filter id="iWGYwgc" width="16.928" height="22.603" x="16.229" y="4.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4110" stdDeviation="2"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bear" /></template>
<style>
.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b0m-kjk1r {
  stop-color: var(--svg-color--8b5754, #8B5754);
  stop-opacity: 0;
}

.bklxob5ur {
  stop-color: var(--svg-color--ffb675, #FFB675);
}

.bp63wtbqk {
  stop-color: var(--svg-color--be8d80, #BE8D80);
  stop-opacity: 0;
}

.c-zl7tb5f {
  d: path("M16 18.13c-.733-.013-1.971.111-3.242.623c-1.458.587-2.115 2.241-1.696 3.756c.593 2.143 1.92 4.278 4.938 4.278s4.345-2.135 4.938-4.278c.419-1.515-.238-3.169-1.696-3.756c-1.27-.512-2.509-.636-3.242-.622");
}

.ckej57bji {
  fill: var(--svg-color--79393f, #79393F);
  d: path("M11.688 18.13c-.41 0-.75-.34-.75-.75v-1.486c0-.41.34-.75.75-.75s.75.34.75.75v1.486c0 .41-.33.75-.75.75");
}

.cl2_31knn {
  stop-color: var(--svg-color--a86f60, #A86F60);
}

.dc42xfuch {
  stop-color: var(--svg-color--ffa392, #FFA392);
}

.dx2g9wbpq {
  stop-color: var(--svg-color--fdae61, #FDAE61);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e-uzvzb4t {
  stop-color: var(--svg-color--bf8a80, #BF8A80);
  stop-opacity: 0;
}

.e9ucyqbno {
  stop-color: var(--svg-color--423539, #423539);
}

.eb0c8s2sl {
  d: path("M30.219 20.177v-.03c0-.536-.051-1.062-.153-1.568c-.314-2.055-1.28-5.719-4.225-8.677C21.606 5.653 16 5.932 16 5.932s-5.606-.279-9.841 3.97c-2.956 2.959-3.91 6.622-4.225 8.677a8 8 0 0 0-.153 1.578v.03c0 3.405 2.021 6.354 4.957 7.763c0 0 3.168 1.817 9.262 1.817s9.263-1.817 9.263-1.817c2.935-1.42 4.956-4.368 4.956-7.773");
}

.fal3qogrm {
  d: path("M7.585 13.843a4.533 4.533 0 1 1 0-9.066a4.533 4.533 0 0 1 0 9.066");
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.g610b8hri {
  stop-color: var(--svg-color--fbb47e, #FBB47E);
}

.gjwexsblw {
  d: path("M24.425 11.96a2.59 2.59 0 1 0 0-5.18a2.59 2.59 0 0 0 0 5.18");
}

.gzxj1cbun {
  stop-color: var(--svg-color--937c79, #937C79);
}

.hgkwwhboi {
  stop-color: var(--svg-color--fff2b4, #FFF2B4);
}

.hj0f2lt9n {
  d: path("M24.425 13.843a4.533 4.533 0 1 0 0-9.066a4.533 4.533 0 0 0 0 9.066");
}

.hoxqlnb2w {
  stop-color: var(--svg-color--945897, #945897);
}

.ij14mzb3i {
  stop-color: var(--svg-color--f78b3f, #F78B3F);
}

.iju_516bg {
  stop-color: var(--svg-color--937c79, #937C79);
  stop-opacity: 0;
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.l_5cl4byj {
  stop-color: var(--svg-color--704848, #704848);
}

.l0k8m4kjf {
  stop-color: var(--svg-color--f78b3f, #F78B3F);
  stop-opacity: 0;
}

.l93ohit5i {
  d: path("M7.585 11.96a2.59 2.59 0 1 1 0-5.18a2.59 2.59 0 0 1 0 5.18");
}

.lm-pdjb-m {
  stop-color: var(--svg-color--5c5458, #5C5458);
  stop-opacity: 0;
}

.m1gpd0z2n {
  stop-color: var(--svg-color--bf8a80, #BF8A80);
}

.m7ke-sbjz {
  stop-color: var(--svg-color--b17d6e, #B17D6E);
  stop-opacity: 0;
}

.mjp0ecb6a {
  stop-color: var(--svg-color--543057, #543057);
}

.n5-vvdsog {
  stop-color: var(--svg-color--b17d6e, #B17D6E);
}

.nfqwgzpyj {
  stop-color: var(--svg-color--863c6e, #863C6E);
}

.ns5t1vbej {
  fill: var(--svg-color--995f50, #995F50);
  d: path("M24.425 13.843a4.533 4.533 0 1 0 0-9.066a4.533 4.533 0 0 0 0 9.066");
}

.o2oyy1bac {
  d: path("M12 17.732c-.41 0-.75-.34-.75-.75v-1.486c0-.41.34-.75.75-.75s.75.34.75.75v1.486c0 .41-.33.75-.75.75");
}

.okcl04jvm {
  stop-color: var(--svg-color--f1ba7f, #F1BA7F);
}

.oo9nsccte {
  fill: var(--svg-color--79393f, #79393F);
  d: path("M19.687 18.045c-.41 0-.75-.34-.75-.75v-1.486c0-.41.34-.75.75-.75s.75.34.75.75v1.486c0 .41-.33.75-.75.75");
}

.p-r478dug {
  stop-color: var(--svg-color--945897, #945897);
  stop-opacity: 0;
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.p981guc6t {
  stop-color: var(--svg-color--533530, #533530);
}

.pen27gfft {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M15.995 22.28c0 1.045-.78 1.894-1.74 1.894s-1.74-.849-1.74-1.894");
}

.psld4vyrv {
  stop-color: var(--svg-color--e5788f, #E5788F);
}

.pvg_dn36h {
  stop-color: var(--svg-color--be8d80, #BE8D80);
}

.pz7rffb7j {
  fill: var(--svg-color--6a3257, #6A3257);
  d: path("M15.558 18.843a8.4 8.4 0 0 0-3.126.6c-1.405.566-2.038 2.16-1.634 3.621c.572 2.066 1.85 4.123 4.76 4.123c2.908 0 4.188-2.057 4.76-4.123c.403-1.46-.23-3.055-1.635-3.62a8.4 8.4 0 0 0-3.125-.6");
}

.rj14edb9i {
  stop-color: var(--svg-color--5f5356, #5F5356);
}

.rj2yt7rxc {
  stop-color: var(--svg-color--fff2b4, #FFF2B4);
  stop-opacity: 0;
}

.shlofhbsw {
  fill: var(--svg-color--db8e70, #DB8E70);
  d: path("m14.71 19.102l1.89-.178c.729-.069 1.157.597.832 1.177a4.3 4.3 0 0 1-.95 1.126a1.1 1.1 0 0 1-.594.263c-.2.02-.417-.03-.631-.147c0 0-.65-.34-1.145-.93c-.427-.508-.13-1.242.598-1.31");
}

.smhtebbjh {
  stop-color: var(--svg-color--3c223c, #3C223C);
}

.t69p4786v {
  d: path("M20 17.732c-.41 0-.75-.34-.75-.75v-1.486c0-.41.34-.75.75-.75s.75.34.75.75v1.486c0 .41-.33.75-.75.75");
}

.ta1o4fycd {
  d: path("M15.113 18.753h1.774c.683 0 1.023.725.67 1.29a4.2 4.2 0 0 1-.982 1.064a.96.96 0 0 1-.575.212a.96.96 0 0 1-.575-.212s-.574-.411-.982-1.065c-.353-.564-.013-1.289.67-1.289");
}

.tdfzryppf {
  d: path("M29.142 20.698c-.655-5.47-2.93-10.207-7.271-12.128c-.562-.248-1.202.016-1.492.558a1.31 1.31 0 0 0 .193 1.493c2.295 2.566 3.773 5.404 3.927 9.988c.056 1.687 1.742 2.94 3.303 2.3c.888-.366 1.455-1.257 1.34-2.21");
}

.ti104777k {
  stop-color: var(--svg-color--e5788f, #E5788F);
  stop-opacity: 0;
}

.tn5zlwlzs {
  stop-color: var(--svg-color--704848, #704848);
  stop-opacity: 0;
}

.tt4jhcbao {
  stop-color: var(--svg-color--8d5857, #8D5857);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.unvvv2nza {
  stop-color: var(--svg-color--6a5c5e, #6A5C5E);
  stop-opacity: 0;
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.w_k2f7dqm {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M19.485 22.28c0 1.045-.78 1.894-1.74 1.894s-1.74-.849-1.74-1.894");
}

.wo-jpe6dv {
  fill: var(--svg-color--966357, #966357);
  d: path("M7.585 13.843a4.533 4.533 0 1 1 0-9.066a4.533 4.533 0 0 1 0 9.066");
}

.wq4qn0v9e {
  stop-color: var(--svg-color--863c6e, #863C6E);
  stop-opacity: 0;
}

.wrd9bsb_n {
  stop-color: var(--svg-color--ff9a52, #FF9A52);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xbybj_nwx {
  stop-color: var(--svg-color--6a5c5e, #6A5C5E);
}

.xghm3mbec {
  stop-color: var(--svg-color--8b5754, #8B5754);
}

.xn_isivjd {
  stop-color: var(--svg-color--fdae61, #FDAE61);
  stop-opacity: 0;
}

.yocn5ubux {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.515 22.28c.042.52.534 1.581 1.61 1.656c1.343.094 1.812-.968 1.859-1.656c-.026.552.578 1.734 1.844 1.734c1.087 0 1.599-1.182 1.656-1.734");
}

.z17z3-a-u {
  stop-color: var(--svg-color--5c5458, #5C5458);
}

.zkps8y4ss {
  stop-color: var(--svg-color--5f5356, #5F5356);
  stop-opacity: 0;
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

</style>
