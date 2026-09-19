<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="n9qx6fdww"/><path fill="url(#iZPtpQb)" class="zbagvtbcd"/><path fill="url(#iu2Owkc)" class="zbagvtbcd"/><path fill="url(#iLSRhLb)" class="zbagvtbcd"/><path fill="url(#i8RNiTc)" class="cwrw_e3fa"/><path fill="url(#ir3Kohe)" class="cwrw_e3fa"/><path fill="url(#irvLvBc)" class="vxp2ubckm"/><path fill="url(#i0HQjbb)" class="vxp2ubckm"/><path class="olm8u5bad"/><path fill="url(#iISDqgc)" class="s4pecyzrm"/><path fill="url(#iVF9jqd)" class="rhtlkrbsa"/><path fill="url(#i2uakBe)" class="rhtlkrbsa"/><path fill="url(#iIIBtJe)" class="rhtlkrbsa"/><path fill="url(#itqRkDe)" class="nkcu8mb5v"/><path fill="url(#ixgQJLd)" class="piykfzi7f"/><g filter="url(#iPxXw4d)"><path stroke="url(#ibnuKgd)" class="xazlwwb1d"/></g><g filter="url(#iM6kJAb)"><path stroke="url(#iGs8ONb)" class="i2fo0vbwa"/></g><defs><radialGradient id="iZPtpQb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96875 1.65625 -1.6393 -1.9486 28.969 3.281)" gradientUnits="userSpaceOnUse"><stop class="kdv4vnbmc"/><stop offset=".676" class="eudn5-hzt"/><stop offset="1" class="lhya1d05q"/></radialGradient><radialGradient id="iu2Owkc" cx="0" cy="0" r="1" gradientTransform="rotate(100.008 12.294 12.604)scale(1.07892 1.06787)" gradientUnits="userSpaceOnUse"><stop class="r_r6sxbeu"/><stop offset="1" class="jxu14sbgu"/></radialGradient><radialGradient id="iLSRhLb" cx="0" cy="0" r="1" gradientTransform="rotate(173.83 14.655 3.438)scale(1.16299 1.15108)" gradientUnits="userSpaceOnUse"><stop class="d_5utmzgz"/><stop offset="1" class="lvnxqsbdx"/></radialGradient><radialGradient id="i8RNiTc" cx="0" cy="0" r="1" gradientTransform="translate(31.847 .638)scale(19.0985)" gradientUnits="userSpaceOnUse"><stop class="i8rjabw6g"/><stop offset="1" class="gquna2bfu"/></radialGradient><radialGradient id="ir3Kohe" cx="0" cy="0" r="1" gradientTransform="rotate(141.234 12.026 7.743)scale(10.5808)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="lewnwjyit"/><stop offset=".588" class="p-7ngdxqf"/><stop offset="1" class="t1omwbcyv"/></radialGradient><radialGradient id="irvLvBc" cx="0" cy="0" r="1" gradientTransform="rotate(135.428 6.06 7.301)scale(11.8444)" gradientUnits="userSpaceOnUse"><stop class="lewnwjyit"/><stop offset="1" class="fj0e2-j5w"/></radialGradient><radialGradient id="i0HQjbb" cx="0" cy="0" r="1" gradientTransform="rotate(72.449 -4.871 19.3)scale(9.83269)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="pmg8olb2q"/><stop offset=".501" class="lidobx__h"/><stop offset=".631" class="b8l3n-bdx"/><stop offset=".963" class="ugywo0b-j"/></radialGradient><radialGradient id="iISDqgc" cx="0" cy="0" r="1" gradientTransform="rotate(-42.064 15.545 -2.231)scale(4.64685)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kxzxqey3m"/><stop offset=".625" class="nzd6in_yg"/><stop offset="1" class="yg0ps8gyp"/></radialGradient><radialGradient id="iVF9jqd" cx="0" cy="0" r="1" gradientTransform="translate(29.522 12.444)scale(25.3866)" gradientUnits="userSpaceOnUse"><stop class="i8rjabw6g"/><stop offset="1" class="gquna2bfu"/></radialGradient><radialGradient id="i2uakBe" cx="0" cy="0" r="1" gradientTransform="rotate(133.559 8.148 13.782)scale(14.0582)" gradientUnits="userSpaceOnUse"><stop class="h2y3b6avw"/><stop offset=".467" class="o70d92b2i"/><stop offset=".697" class="lz9-zvx1l"/><stop offset="1" class="r1z2kybsx"/></radialGradient><radialGradient id="iIIBtJe" cx="0" cy="0" r="1" gradientTransform="rotate(-140.981 15.913 8.677)scale(23.3289)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="k05n1gbkm"/><stop offset=".402" class="nc32e38ho"/><stop offset=".615" class="h50dumb4c"/></radialGradient><radialGradient id="itqRkDe" cx="0" cy="0" r="1" gradientTransform="matrix(3.16001 -.0625 .06515 3.29422 20.965 18.813)" gradientUnits="userSpaceOnUse"><stop class="vnirzqvec"/><stop offset="1" class="ttz7o9byc"/></radialGradient><radialGradient id="ixgQJLd" cx="0" cy="0" r="1" gradientTransform="rotate(-42.064 35.814 -13.563)scale(6.90335)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kxzxqey3m"/><stop offset=".625" class="nzd6in_yg"/><stop offset="1" class="yg0ps8gyp"/></radialGradient><linearGradient id="ibnuKgd" x1="21.781" x2="26.281" y1="13.453" y2="18.031" gradientUnits="userSpaceOnUse"><stop class="xii7bdcla"/><stop offset=".169" class="so8lm6dse"/><stop offset=".413" class="ddxiu5h3b"/><stop offset=".718" class="sl5er3bgk"/><stop offset="1" class="v_j9libxz"/></linearGradient><linearGradient id="iGs8ONb" x1="9.418" x2="10.876" y1="5.475" y2="9.844" gradientUnits="userSpaceOnUse"><stop class="xii7bdcla"/><stop offset=".169" class="so8lm6dse"/><stop offset=".413" class="ddxiu5h3b"/><stop offset=".718" class="sl5er3bgk"/><stop offset="1" class="v_j9libxz"/></linearGradient><filter id="iPxXw4d" width="5.25" height="5.913" x="21.177" y="12.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32653" stdDeviation=".1"/></filter><filter id="iM6kJAb" width="2.293" height="5.491" x="9.002" y="4.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_32653" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:blueberries" /></template>
<style>
.b8l3n-bdx {
  stop-color: var(--svg-color--583b9c, #583B9C);
  stop-opacity: 0.252;
}

.cwrw_e3fa {
  d: path("M22.655 16.68a7.34 7.34 0 1 0 0-14.68a7.34 7.34 0 0 0 0 14.68");
}

.d_5utmzgz {
  stop-color: var(--svg-color--9280c3, #9280C3);
}

.ddxiu5h3b {
  stop-color: var(--svg-color--ae97f6, #AE97F6);
  stop-opacity: 0;
}

.eudn5-hzt {
  stop-color: var(--svg-color--755caf, #755CAF);
}

.fj0e2-j5w {
  stop-color: var(--svg-color--714bb3, #714BB3);
}

.ft5dv1b6b {
  fill: none;
}

.gquna2bfu {
  stop-color: var(--svg-color--625996, #625996);
}

.h2y3b6avw {
  stop-color: var(--svg-color--9e87d8, #9E87D8);
}

.h50dumb4c {
  stop-color: var(--svg-color--7862ad, #7862AD);
}

.i2fo0vbwa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M9.302 5.23c.35.283.63 1.32.629 1.535s.097.454.207.51c.137.07.858.557.857 1.483c0 .302-.197.998-.626 1.363");
}

.i8rjabw6g {
  stop-color: var(--svg-color--8c65c9, #8C65C9);
}

.jxu14sbgu {
  stop-color: var(--svg-color--8a79b9, #8A79B9);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.kdv4vnbmc {
  stop-color: var(--svg-color--8f7ebf, #8F7EBF);
}

.kxzxqey3m {
  stop-color: var(--svg-color--716380, #716380);
}

.lewnwjyit {
  stop-color: var(--svg-color--a38dd9, #A38DD9);
}

.lhya1d05q {
  stop-color: var(--svg-color--8672b9, #8672B9);
  stop-opacity: 0;
}

.lidobx__h {
  stop-color: var(--svg-color--573a9c, #573A9C);
  stop-opacity: 0.581;
}

.lvnxqsbdx {
  stop-color: var(--svg-color--9483c4, #9483C4);
  stop-opacity: 0;
}

.lz9-zvx1l {
  stop-color: var(--svg-color--7f58ca, #7F58CA);
}

.n9qx6fdww {
  fill: var(--svg-color--7a63b4, #7A63B4);
  d: path("M26.394 2.063c-.55.01-.818.448-.852.672l2.22 1.67l1.535 2.096c.285-.106.566-.375.616-.644c.079-.521-.061-.751-.258-.947c-.196-.196-.358-.247-.88-.253c.438-.252.718-.711.6-1.266c0 0-.123-.56-.69-.723c-.487-.151-1.019 0-1.338.588c.022-.269-.05-.627-.107-.706s-.297-.498-.846-.487");
}

.nc32e38ho {
  stop-color: var(--svg-color--715ba7, #715BA7);
  stop-opacity: 0;
}

.nkcu8mb5v {
  d: path("M23.74 14.838c-.561-.404-1.089-1.862-2.828-1.845c-1.74.018-2.074 1.195-2.619 1.652s-2.214.58-2.636 2.179c-.421 1.599.51 2.267.809 3.11c.299.844-.088 1.828 1.037 2.864c1.124 1.037 2.653.3 3.409.3s2.32.755 3.303-.194s.896-2.372 1.125-2.97c.228-.597 1.67-1.933.72-3.514c-.949-1.582-1.757-1.178-2.32-1.582");
}

.nzd6in_yg {
  stop-color: var(--svg-color--4b2e68, #4B2E68);
}

.o70d92b2i {
  stop-color: var(--svg-color--8d65da, #8D65DA);
}

.olm8u5bad {
  fill: var(--svg-color--a97de4, #A97DE4);
  d: path("M10.297 7.051c-.227-.405-.132-1.441-1.194-1.926s-1.6.136-2.06.258c-.462.123-1.51-.278-2.222.574c-.711.85-.336 1.522-.394 2.12c-.059.596-.574 1.084-.186 2.034s1.527.937 1.986 1.152s1.194 1.12 2.062.823c.868-.296 1.22-1.186 1.528-1.484s1.565-.699 1.438-1.93c-.126-1.23-.732-1.215-.959-1.62");
}

.p-7ngdxqf {
  stop-color: var(--svg-color--7e65b8, #7E65B8);
}

.piykfzi7f {
  d: path("M20.965 22.06a3.61 3.61 0 1 0 0-7.22a3.61 3.61 0 0 0 0 7.22");
}

.pmg8olb2q {
  stop-color: var(--svg-color--532ea8, #532EA8);
}

.r_r6sxbeu {
  stop-color: var(--svg-color--8978b8, #8978B8);
}

.r1z2kybsx {
  stop-color: var(--svg-color--7b48ca, #7B48CA);
}

.rhtlkrbsa {
  d: path("M18.695 30a8.97 8.97 0 1 0 0-17.94a8.97 8.97 0 0 0 0 17.94");
}

.s4pecyzrm {
  d: path("M7.285 10.89a2.43 2.43 0 1 0 0-4.86a2.43 2.43 0 0 0 0 4.86");
}

.sl5er3bgk {
  stop-color: var(--svg-color--cdaeff, #CDAEFF);
}

.so8lm6dse {
  stop-color: var(--svg-color--c7a7f9, #C7A7F9);
}

.t1omwbcyv {
  stop-color: var(--svg-color--4d348e, #4D348E);
}

.ttz7o9byc {
  stop-color: var(--svg-color--af7ff0, #AF7FF0);
}

.ugywo0b-j {
  stop-color: var(--svg-color--583b9c, #583B9C);
  stop-opacity: 0;
}

.v_j9libxz {
  stop-color: var(--svg-color--c19cfa, #C19CFA);
  stop-opacity: 0;
}

.vnirzqvec {
  stop-color: var(--svg-color--b382f3, #B382F3);
}

.vxp2ubckm {
  d: path("M9.985 19.14a7.98 7.98 0 1 0 0-15.96a7.98 7.98 0 0 0 0 15.96");
}

.xazlwwb1d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.477 13.227c.625.127 1.644 1.22 1.78 1.484c.138.264.415.494.59.494c.219 0 1.442.147 2.036 1.28c.193.368.392 1.342.086 2.054");
}

.xii7bdcla {
  stop-color: var(--svg-color--b993f4, #B993F4);
  stop-opacity: 0;
}

.yg0ps8gyp {
  stop-color: var(--svg-color--351a50, #351A50);
}

.zbagvtbcd {
  d: path("M26.394 2.063c-.55.01-.818.448-.852.672l2.22 1.67l1.535 2.096c.285-.106.566-.375.616-.644c.079-.521-.061-.751-.258-.947c-.196-.196-.358-.247-.88-.253c.438-.252.718-.711.6-1.266c0 0-.123-.56-.69-.723c-.487-.151-1.019 0-1.338.588c.022-.269-.05-.627-.107-.706s-.297-.498-.846-.487");
}

</style>
