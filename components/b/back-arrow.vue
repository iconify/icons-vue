<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="obpyqwb8l"/><path class="il5h3bbzf"/><path fill="url(#iVakCrc)" class="y451ycchm"/><path fill="url(#ibA5V7c)" class="y451ycchm"/><path fill="url(#iGWjlFd)" class="y451ycchm"/><path fill="url(#iyrX8Fm)" class="y451ycchm"/><path fill="url(#imBsBVd)" class="y451ycchm"/><path fill="url(#iSpdkXc)" class="y451ycchm"/><path fill="url(#i9XDPze)" class="y451ycchm"/><path fill="url(#iptHQye)" class="y451ycchm"/><path class="ml0f4sbdl"/><path fill="url(#iVakCrc)" class="sqlzxcb8l"/><path fill="url(#iQJW7Eb)" class="sqlzxcb8l"/><path fill="url(#iVRy4vd)" class="sqlzxcb8l"/><path fill="url(#iUy2scd)" class="sqlzxcb8l"/><path fill="url(#iiqW9ic)" class="sqlzxcb8l"/><path fill="url(#itAg54d)" class="sqlzxcb8l"/><path fill="url(#iO9qCcb)" class="sqlzxcb8l"/><path class="bhv4byqgn"/><defs><radialGradient id="iVakCrc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -1.4375 22.03021 20.59345 6.373 15.438)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="oir76sqmm"/><stop offset=".586" class="x7eikgb-u"/><stop offset="1" class="ap-i9rbmn"/></radialGradient><radialGradient id="ibA5V7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 1.25 -12.3895 11.1506 6.123 6.125)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="ad3ffbcvf"/><stop offset="1" class="yhyazbcky"/></radialGradient><radialGradient id="iGWjlFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10937 4.53125 -2.1519 -.05194 12.592 4.828)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="f6i2duyld"/><stop offset="1" class="s3sd9uv-y"/></radialGradient><radialGradient id="iyrX8Fm" cx="0" cy="0" r="1" gradientTransform="matrix(-.12495 6.84375 -1.43338 -.02617 12.936 2.594)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="ou589vx9h"/><stop offset="1" class="hv7k72bel"/></radialGradient><radialGradient id="imBsBVd" cx="0" cy="0" r="1" gradientTransform="matrix(.76563 1.15625 -.61965 .4103 11.904 7.484)" gradientUnits="userSpaceOnUse"><stop class="qvuc3k65w"/><stop offset="1" class="d_3okdntd"/></radialGradient><radialGradient id="iSpdkXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23438 .79688 -.53183 -.15643 11.545 2.86)" gradientUnits="userSpaceOnUse"><stop class="goz-mx0tw"/><stop offset="1" class="zf_jv2vmi"/></radialGradient><radialGradient id="i9XDPze" cx="0" cy="0" r="1" gradientTransform="matrix(-.89064 1.70312 -1.83336 -.95874 12.92 14.11)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="m0mjg3bfp"/><stop offset=".489" class="rxncc3oqp"/><stop offset="1" class="grm0g-4db"/></radialGradient><radialGradient id="iptHQye" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 3.875 -.83036 .04687 12.373 16.563)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="kia1ijb7f"/><stop offset="1" class="c8lx21bwk"/></radialGradient><radialGradient id="iQJW7Eb" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 1.25 -12.3895 11.1506 6.123 6.126)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="ad3ffbcvf"/><stop offset="1" class="yhyazbcky"/></radialGradient><radialGradient id="iiqW9ic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.97363 43.6774 0 21.686 14.095)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="s1u8bgjjw"/><stop offset=".491" class="h4o422rpj"/><stop offset="1" class="gx0eq4bra"/></radialGradient><radialGradient id="itAg54d" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 .5625 -.35576 -.47435 28.983 8.283)" gradientUnits="userSpaceOnUse"><stop class="sa0qzmhen"/><stop offset="1" class="xzfa6pjho"/></radialGradient><radialGradient id="iO9qCcb" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 1.32813 -.82903 .53643 11.842 7.36)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="qvuc3k65w"/><stop offset="1" class="d_3okdntd"/></radialGradient><linearGradient id="iVRy4vd" x1="30.28" x2="27.967" y1="11.188" y2="11.188" gradientUnits="userSpaceOnUse"><stop offset=".122" class="t0-y0kktv"/><stop offset=".514" class="d2gu7fb7r"/><stop offset=".689" class="ctkqcab7d"/><stop offset="1" class="m57pq8bjw"/></linearGradient><linearGradient id="iUy2scd" x1="21.717" x2="21.717" y1="7.095" y2="8.907" gradientUnits="userSpaceOnUse"><stop offset=".122" class="t0-y0kktv"/><stop offset=".5" class="d2gu7fb7r"/><stop offset=".689" class="ctkqcab7d"/><stop offset="1" class="m57pq8bjw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:back-arrow" /></template>
<style>
.ad3ffbcvf {
  stop-color: var(--svg-color--483f6e, #483F6E);
}

.ap-i9rbmn {
  stop-color: var(--svg-color--7647cd, #7647CD);
  stop-opacity: 0;
}

.bhv4byqgn {
  fill: var(--svg-color--7763bb, #7763BB);
  d: path("M22.6 28.35a3.308 3.308 0 0 1-6.17-1.66v-2.38c0-1.83 1.48-3.31 3.31-3.31c1.18 0 2.28.64 2.87 1.65c.26.44.1 1-.33 1.26c-.44.26-1 .11-1.26-.33a1.5 1.5 0 0 0-1.28-.74c-.8 0-1.47.66-1.47 1.47v2.38c0 .81.67 1.47 1.47 1.47c.53 0 1.01-.28 1.28-.74c.26-.43.81-.59 1.26-.33c.42.26.58.82.32 1.26m4.629-3.48l2.6 3.68c.29.42.2.99-.23 1.29c-.42.29-.99.19-1.28-.22l-2.41-3.42l-.69.69v2.2c0 .51-.41.92-.92.92s-.92-.41-.92-.92v-7.17c0-.51.41-.92.92-.92s.92.41.92.92v2.37l3.01-3.02c.36-.36.94-.36 1.3 0s.36.94 0 1.3z");
}

.c8lx21bwk {
  stop-color: var(--svg-color--62529e, #62529E);
  stop-opacity: 0;
}

.ctkqcab7d {
  stop-color: var(--svg-color--8273c3, #8273C3);
}

.d_3okdntd {
  stop-color: var(--svg-color--a297d5, #A297D5);
  stop-opacity: 0;
}

.d2gu7fb7r {
  stop-color: var(--svg-color--8172c2, #8172C2);
}

.f6i2duyld {
  stop-color: var(--svg-color--968acd, #968ACD);
}

.ft5dv1b6b {
  fill: none;
}

.goz-mx0tw {
  stop-color: var(--svg-color--a096d0, #A096D0);
}

.grm0g-4db {
  stop-color: var(--svg-color--8155d1, #8155D1);
  stop-opacity: 0;
}

.gx0eq4bra {
  stop-color: var(--svg-color--8745e5, #8745E5);
  stop-opacity: 0;
}

.h4o422rpj {
  stop-color: var(--svg-color--8745e5, #8745E5);
}

.hv7k72bel {
  stop-color: var(--svg-color--6e5daf, #6E5DAF);
  stop-opacity: 0;
}

.il5h3bbzf {
  fill: var(--svg-color--7969b9, #7969B9);
  d: path("m2.36 11.23l8.31 7.57c.61.56 1.6.12 1.6-.71v-3.63c0-.35.29-.64.64-.64h15.86c.66 0 1.19-.53 1.19-1.19V8.42c0-.66-.53-1.19-1.19-1.19H12.91c-.35 0-.64-.29-.64-.64V2.96c0-.83-.99-1.27-1.6-.71L2.36 9.82a.946.946 0 0 0 0 1.41");
}

.kia1ijb7f {
  stop-color: var(--svg-color--62529e, #62529E);
}

.m0mjg3bfp {
  stop-color: var(--svg-color--5f36ba, #5F36BA);
}

.m57pq8bjw {
  stop-color: var(--svg-color--8172c2, #8172C2);
  stop-opacity: 0;
}

.ml0f4sbdl {
  fill: var(--svg-color--7969b9, #7969B9);
  d: path("M12.272 14.46c0-.35.29-.64.64-.64h15.86c.66 0 1.19-.53 1.19-1.19V8.42c0-.66-.53-1.19-1.19-1.19h-15.86c-.35 0-.64-.29-.64-.64z");
}

.obpyqwb8l {
  fill: var(--svg-color--7763bb, #7763BB);
  d: path("m16.329 28.76l-2.54-6.95c-.16-.49-.62-.81-1.13-.81s-.97.32-1.12.79l-2.57 6.98c-.18.48.07 1 .55 1.18c.1.03.21.05.32.05c.37 0 .73-.23.86-.6l.41-1.13c.04.01.08.01.12.01h2.87c.03 0 .07 0 .1-.01l.41 1.12c.18.48.7.73 1.18.55c.47-.17.71-.7.54-1.18m-4.54-2.32l.87-2.38l.86 2.38zM8.23 23.71c0 .53-.15 1.02-.41 1.43a2.7 2.7 0 0 1 1.07 2.15c0 1.38-1.05 2.54-2.4 2.69c-.04.01-.09.02-.13.01c-.06.01-.12.01-.18.01H2.92a.92.92 0 0 1-.92-.93v-7.16c0-.5.41-.91.92-.91h2.6c.1 0 .19 0 .27.01l.095.015l.095.015c1.28.22 2.25 1.34 2.25 2.67m-2.7-.87H3.84v1.74h1.68c.48 0 .88-.39.88-.87a.87.87 0 0 0-.87-.87m-1.69 3.57v1.74h2.35a.87.87 0 0 0 0-1.74z");
}

.oir76sqmm {
  stop-color: var(--svg-color--5836ab, #5836AB);
}

.ou589vx9h {
  stop-color: var(--svg-color--6e5daf, #6E5DAF);
}

.qvuc3k65w {
  stop-color: var(--svg-color--a297d5, #A297D5);
}

.rxncc3oqp {
  stop-color: var(--svg-color--8649e1, #8649E1);
}

.s1u8bgjjw {
  stop-color: var(--svg-color--5e36b9, #5E36B9);
}

.s3sd9uv-y {
  stop-color: var(--svg-color--897dc2, #897DC2);
  stop-opacity: 0;
}

.sa0qzmhen {
  stop-color: var(--svg-color--a398d7, #A398D7);
}

.sqlzxcb8l {
  d: path("M12.272 14.46c0-.35.29-.64.64-.64h15.86c.66 0 1.19-.53 1.19-1.19V8.42c0-.66-.53-1.19-1.19-1.19h-15.86c-.35 0-.64-.29-.64-.64z");
}

.t0-y0kktv {
  stop-color: var(--svg-color--6454a3, #6454A3);
}

.x7eikgb-u {
  stop-color: var(--svg-color--7647cd, #7647CD);
}

.xzfa6pjho {
  stop-color: var(--svg-color--a398d7, #A398D7);
  stop-opacity: 0;
}

.y451ycchm {
  d: path("m2.36 11.23l8.31 7.57c.61.56 1.6.12 1.6-.71v-3.63c0-.35.29-.64.64-.64h15.86c.66 0 1.19-.53 1.19-1.19V8.42c0-.66-.53-1.19-1.19-1.19H12.91c-.35 0-.64-.29-.64-.64V2.96c0-.83-.99-1.27-1.6-.71L2.36 9.82a.946.946 0 0 0 0 1.41");
}

.yhyazbcky {
  stop-color: var(--svg-color--5f5395, #5F5395);
  stop-opacity: 0;
}

.zf_jv2vmi {
  stop-color: var(--svg-color--a096d0, #A096D0);
  stop-opacity: 0;
}

</style>
