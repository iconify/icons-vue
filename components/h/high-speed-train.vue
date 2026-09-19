<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBzwuEd)" class="ndu9daczf"/><path fill="url(#i6oAgbb)" class="ndu9daczf"/><path fill="url(#igM5Sub)" class="e3r14_35z"/><path fill="url(#iGXg8By)" class="sz18xcb-z"/><path fill="url(#iGB7GnT)" class="p3tuhtsjy"/><path fill="url(#iVPGRib)" class="cfi1wacsd"/><g filter="url(#i7JbrIb)"><path fill="url(#i8GlAge)" class="v-34c-byo"/><path fill="url(#ieDainc)" class="v-34c-byo"/></g><g filter="url(#ixoRdHe)"><path fill="url(#i9AnzAd)" class="atm0mnbwl"/><path fill="url(#iREdeHe)" class="atm0mnbwl"/></g><path fill="url(#ixap84c)" class="atm0mnbwl"/><g filter="url(#icZlGFc)"><path fill="url(#ihABovd)" class="k-0cswbsd"/></g><path fill="url(#ios21Ez)" class="en7q_-bwm"/><g filter="url(#iLhpe6d)"><path fill="url(#i4cIxPd)" class="up1b3w8uq"/></g><path fill="url(#iNKaWIe)" class="ilnzjybiz"/><path fill="url(#i8Xp05b)" class="ilnzjybiz"/><path fill="url(#iG9w7XY)" class="ilnzjybiz"/><path fill="url(#iPOHVib)" class="luryh8bld"/><path fill="url(#ip9xGDe)" class="luryh8bld"/><path fill="url(#iSdW9Xb)" class="luryh8bld"/><path fill="url(#innLQFd)" class="luryh8bld"/><defs><linearGradient id="iBzwuEd" x1="29.99" x2="2.01" y1="22.501" y2="22.501" gradientUnits="userSpaceOnUse"><stop class="lakak1bft"/><stop offset="1" class="bf7ajnopd"/></linearGradient><linearGradient id="i8GlAge" x1="30" x2="10.719" y1="22.003" y2="22.003" gradientUnits="userSpaceOnUse"><stop class="qhpxizbui"/><stop offset="1" class="f9v60fb6j"/></linearGradient><linearGradient id="ieDainc" x1="19.505" x2="19.505" y1="20.688" y2="21.172" gradientUnits="userSpaceOnUse"><stop class="et-rjrb0h"/><stop offset="1" class="jn4m79byp"/></linearGradient><linearGradient id="i9AnzAd" x1="23.627" x2="23.627" y1="16.183" y2="8" gradientUnits="userSpaceOnUse"><stop class="wzfnbjzrx"/><stop offset="1" class="wd303gbdn"/><stop offset="1" class="gtvcb15gp"/></linearGradient><linearGradient id="iREdeHe" x1="4.644" x2="16.279" y1="21" y2="21" gradientUnits="userSpaceOnUse"><stop class="keb6axbkn"/><stop offset="1" class="bww-evb3w"/></linearGradient><linearGradient id="ixap84c" x1="29.99" x2="29.807" y1="15.633" y2="15.633" gradientUnits="userSpaceOnUse"><stop class="uu8s2_d7p"/><stop offset="1" class="njttvrbfw"/></linearGradient><linearGradient id="ihABovd" x1="17.24" x2="17.24" y1="19.289" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wdr8c08gg"/><stop offset="1" class="vjclfevac"/></linearGradient><linearGradient id="ios21Ez" x1="30" x2="4.1" y1="18.503" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="o6vyhbc-b"/><stop offset=".93" class="seoaq6l2b"/><stop offset=".992" class="iv-yp01kc"/></linearGradient><linearGradient id="i8Xp05b" x1="25.99" x2="25.99" y1="8.501" y2="9.875" gradientUnits="userSpaceOnUse"><stop class="ak0qvcbig"/><stop offset="1" class="i9_1rt0gd"/></linearGradient><linearGradient id="iG9w7XY" x1="25.99" x2="25.99" y1="14.278" y2="13.258" gradientUnits="userSpaceOnUse"><stop class="d9nme1bze"/><stop offset="1" class="pqjnjzbdl"/></linearGradient><linearGradient id="iPOHVib" x1="8.813" x2="19.416" y1="14" y2="10.296" gradientUnits="userSpaceOnUse"><stop class="woiy_eb1w"/><stop offset="1" class="y9x5w8b8u"/></linearGradient><linearGradient id="ip9xGDe" x1="14.491" x2="14.491" y1="14.366" y2="13.135" gradientUnits="userSpaceOnUse"><stop class="om7iyjbky"/><stop offset="1" class="kogq85buv"/></linearGradient><linearGradient id="iSdW9Xb" x1="5.256" x2="12.375" y1="14.743" y2="14" gradientUnits="userSpaceOnUse"><stop class="pzb6tkbrb"/><stop offset="1" class="la4wdn6yi"/></linearGradient><linearGradient id="innLQFd" x1="14.354" x2="14.354" y1="8.312" y2="10.672" gradientUnits="userSpaceOnUse"><stop class="szibmsb1z"/><stop offset="1" class="fy7vmtbhy"/></linearGradient><radialGradient id="i6oAgbb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.46875 0 0 -1.94032 10.965 22.344)" gradientUnits="userSpaceOnUse"><stop class="pf131bcat"/><stop offset="1" class="qi40r1byt"/></radialGradient><radialGradient id="igM5Sub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.9375 2.96875 0 6.777 29.781)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="tuzxx372l"/><stop offset="1" class="bo16rob1k"/></radialGradient><radialGradient id="iGXg8By" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.9375 2.96875 0 13.777 29.781)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="tuzxx372l"/><stop offset="1" class="bo16rob1k"/></radialGradient><radialGradient id="iGB7GnT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.9375 2.95885 0 20.758 29.781)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="tuzxx372l"/><stop offset="1" class="bo16rob1k"/></radialGradient><radialGradient id="iVPGRib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.9375 2.96875 0 27.757 29.781)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="tuzxx372l"/><stop offset="1" class="bo16rob1k"/></radialGradient><radialGradient id="i4cIxPd" cx="0" cy="0" r="1" gradientTransform="matrix(3.75568 0 0 1.64929 10.523 16.003)" gradientUnits="userSpaceOnUse"><stop class="ikds7dbvd"/><stop offset="1" class="vmpcc9dpd"/></radialGradient><radialGradient id="iNKaWIe" cx="0" cy="0" r="1" gradientTransform="matrix(.12713 4.38657 -7.64468 .22155 24.086 8.036)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="ywsh3hbup"/><stop offset="1" class="n7gt29b1w"/></radialGradient><filter id="i7JbrIb" width="21.29" height="2.3" x="9.01" y="20.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.313726 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9167"/></filter><filter id="ixoRdHe" width="26.78" height="13" x="4.01" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.631373 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9167"/></filter><filter id="icZlGFc" width="26.5" height="2.2" x="4.49" y="18.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.317647 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9167"/></filter><filter id="iLhpe6d" width="4" height="2" x="10" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.180392 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9167"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:high-speed-train" /></template>
<style>
.ak0qvcbig {
  stop-color: var(--svg-color--037ff5, #037FF5);
}

.atm0mnbwl {
  d: path("M15.1 8.52c.58-.34 1.25-.52 1.92-.52h12.97v13H7.82c-2.11 0-3.81-1.71-3.81-3.81c0-1.29.65-2.49 1.72-3.19z");
}

.bf7ajnopd {
  stop-color: var(--svg-color--231535, #231535);
}

.bo16rob1k {
  stop-color: var(--svg-color--2d203f, #2D203F);
}

.bww-evb3w {
  stop-color: var(--svg-color--d7ccd7, #D7CCD7);
  stop-opacity: 0;
}

.cfi1wacsd {
  d: path("M24.99 30v-6h3v6z");
}

.d9nme1bze {
  stop-color: var(--svg-color--2dd4ff, #2DD4FF);
}

.e3r14_35z {
  d: path("M4.01 30v-6h3v6z");
}

.en7q_-bwm {
  d: path("M4.49 19H30v-1H4.1c.08.36.22.69.39 1");
}

.et-rjrb0h {
  stop-color: var(--svg-color--295bb2, #295BB2);
}

.f9v60fb6j {
  stop-color: var(--svg-color--456bb0, #456BB0);
}

.ft5dv1b6b {
  fill: none;
}

.fy7vmtbhy {
  stop-color: var(--svg-color--047de4, #047DE4);
  stop-opacity: 0;
}

.gtvcb15gp {
  stop-color: var(--svg-color--efe8f1, #EFE8F1);
}

.i9_1rt0gd {
  stop-color: var(--svg-color--037ff5, #037FF5);
  stop-opacity: 0;
}

.ikds7dbvd {
  stop-color: var(--svg-color--ff6d46, #FF6D46);
}

.ilnzjybiz {
  d: path("M29.99 14h-7.05a.95.95 0 0 1-.95-.95V9.96c0-.53.43-.95.95-.95h7.05z");
}

.iv-yp01kc {
  stop-color: var(--svg-color--5dc9ed, #5DC9ED);
}

.jn4m79byp {
  stop-color: var(--svg-color--295bb2, #295BB2);
  stop-opacity: 0;
}

.k-0cswbsd {
  d: path("M7.82 21h22.17v-2H4.49c.64 1.19 1.89 2 3.33 2");
}

.keb6axbkn {
  stop-color: var(--svg-color--d7ccd7, #D7CCD7);
}

.kogq85buv {
  stop-color: var(--svg-color--1c9ce3, #1C9CE3);
  stop-opacity: 0;
}

.la4wdn6yi {
  stop-color: var(--svg-color--5bffff, #5BFFFF);
  stop-opacity: 0;
}

.lakak1bft {
  stop-color: var(--svg-color--532b82, #532B82);
}

.luryh8bld {
  d: path("M18.05 9h-3.76l-6.67 3.9S5.76 13.99 5.74 14h12.32c.53 0 .95-.43.95-.95V9.96a.973.973 0 0 0-.96-.96");
}

.n7gt29b1w {
  stop-color: var(--svg-color--50e9ff, #50E9FF);
}

.ndu9daczf {
  d: path("M29.99 21H2.01v3h27.98z");
}

.njttvrbfw {
  stop-color: var(--svg-color--f0eff1, #F0EFF1);
  stop-opacity: 0;
}

.o6vyhbc-b {
  stop-color: var(--svg-color--6cf0ff, #6CF0FF);
}

.om7iyjbky {
  stop-color: var(--svg-color--1c9ce3, #1C9CE3);
}

.p3tuhtsjy {
  d: path("M18 30v-6h2.99v6z");
}

.pf131bcat {
  stop-color: var(--svg-color--40305b, #40305B);
}

.pqjnjzbdl {
  stop-color: var(--svg-color--2dd4ff, #2DD4FF);
  stop-opacity: 0;
}

.pzb6tkbrb {
  stop-color: var(--svg-color--5bffff, #5BFFFF);
}

.qhpxizbui {
  stop-color: var(--svg-color--409ffb, #409FFB);
}

.qi40r1byt {
  stop-color: var(--svg-color--3d2d57, #3D2D57);
  stop-opacity: 0;
}

.seoaq6l2b {
  stop-color: var(--svg-color--70fbff, #70FBFF);
}

.sz18xcb-z {
  d: path("M11.01 30v-6h3v6z");
}

.szibmsb1z {
  stop-color: var(--svg-color--047de4, #047DE4);
}

.tuzxx372l {
  stop-color: var(--svg-color--5b4080, #5B4080);
}

.up1b3w8uq {
  d: path("M13 17h-2c-.55 0-1-.45-1-1s.45-1 1-1h2c.55 0 1 .45 1 1c0 .56-.45 1-1 1");
}

.uu8s2_d7p {
  stop-color: var(--svg-color--f0eff1, #F0EFF1);
}

.v-34c-byo {
  d: path("M29.99 21H9.01l1.4 1.41c.38.38.89.59 1.42.59H30v-2z");
}

.vjclfevac {
  stop-color: var(--svg-color--3d7ac3, #3D7AC3);
}

.vmpcc9dpd {
  stop-color: var(--svg-color--f43a21, #F43A21);
}

.wd303gbdn {
  stop-color: var(--svg-color--f4f4f4, #F4F4F4);
}

.wdr8c08gg {
  stop-color: var(--svg-color--50a9e4, #50A9E4);
}

.woiy_eb1w {
  stop-color: var(--svg-color--59fdff, #59FDFF);
}

.wzfnbjzrx {
  stop-color: var(--svg-color--ecdff2, #ECDFF2);
}

.y9x5w8b8u {
  stop-color: var(--svg-color--218fea, #218FEA);
}

.ywsh3hbup {
  stop-color: var(--svg-color--0686fb, #0686FB);
}

</style>
