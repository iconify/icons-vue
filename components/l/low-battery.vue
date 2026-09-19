<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4DPQCe)"><path fill="url(#iAbDTbe)" class="vlr-6ub1l"/><path fill="url(#iiTTA3c)" class="vlr-6ub1l"/></g><g filter="url(#in5C1UB)"><path fill="url(#iAw5LcT)" class="wk8eqmb8w"/><path fill="url(#i7i167b)" class="wk8eqmb8w"/></g><path fill="url(#izVXWTx)" class="k9ifomzon"/><path fill="url(#iyWVfgb)" class="k9ifomzon"/><path fill="url(#i4r7GMd)" class="k9ifomzon"/><path fill="url(#iGAsNgc)" class="xxd00c_ad"/><path fill="url(#iyFWD8d)" class="xxd00c_ad"/><path fill="url(#i400Fwc)" class="xxd00c_ad"/><path fill="url(#ijFc3sb)" transform="matrix(1 0 0 -1 7.977 20.003)" class="pzqz5gwhq"/><g filter="url(#iwFwHpe)"><path class="f0-my6v7j"/></g><g filter="url(#iWTK5ue)"><path class="cpmb8-bcg"/></g><path class="op769yqsc"/><defs><radialGradient id="iiTTA3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .48438 -2.86899 0 17.469 2.488)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="awqtyhbpb"/><stop offset="1" class="lhdtcbcje"/></radialGradient><radialGradient id="i7i167b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.60938 9.71875 0 20.656 6.034)" gradientUnits="userSpaceOnUse"><stop class="h6622gb-c"/><stop offset="1" class="cwtaagart"/></radialGradient><radialGradient id="i4r7GMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.48438 -8.5625 0 20.625 27.519)" gradientUnits="userSpaceOnUse"><stop offset=".4" class="pgnvwlbfg"/><stop offset="1" class="dtotehg2t"/></radialGradient><radialGradient id="iyFWD8d" cx="0" cy="0" r="1" gradientTransform="matrix(1.96874 9.17187 -18.37056 3.94324 15.5 20.003)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="z--1bsaxs"/><stop offset="1" class="is-fmvbzl"/></radialGradient><radialGradient id="i400Fwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -12.7973 0 19.625 16.956)" gradientUnits="userSpaceOnUse"><stop class="wwkq06b-l"/><stop offset="1" class="s7t4csbls"/></radialGradient><radialGradient id="ijFc3sb" cx="0" cy="0" r="1" gradientTransform="matrix(0 24.2031 -11.6484 0 11.648 0)" gradientUnits="userSpaceOnUse"><stop offset=".282" class="ha165cbhx"/><stop offset="1" class="z6-qfzm2e"/></radialGradient><linearGradient id="iAbDTbe" x1="12.813" x2="17.781" y1="3.55" y2="3.55" gradientUnits="userSpaceOnUse"><stop class="rmgkmrb5v"/><stop offset=".994" class="ipkb4gz7l"/></linearGradient><linearGradient id="iAw5LcT" x1="19.438" x2="8.531" y1="5.581" y2="5.581" gradientUnits="userSpaceOnUse"><stop class="v_oq59jpd"/><stop offset="1" class="so08fbb9y"/></linearGradient><linearGradient id="izVXWTx" x1="9.406" x2="22.906" y1="29.581" y2="29.488" gradientUnits="userSpaceOnUse"><stop class="vca2t4y6i"/><stop offset="1" class="jjh-tmbov"/></linearGradient><linearGradient id="iyWVfgb" x1="16.004" x2="16.004" y1="29.988" y2="28.644" gradientUnits="userSpaceOnUse"><stop offset=".093" class="a37_bobkd"/><stop offset="1" class="eipgzybpw"/></linearGradient><linearGradient id="iGAsNgc" x1="21.75" x2="9.094" y1="27.55" y2="27.55" gradientUnits="userSpaceOnUse"><stop class="hdms7abnt"/><stop offset="1" class="d8nqchuih"/></linearGradient><filter id="i4DPQCe" width="6.055" height="4.037" x="12.973" y="2.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.690196 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_874"/></filter><filter id="in5C1UB" width="16.305" height="2.069" x="7.977" y="4.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.560784 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_874"/></filter><filter id="iwFwHpe" width="4.763" height="4.817" x="13.619" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.537255 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4791_874"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4791_874" result="shape"/></filter><filter id="iWTK5ue" width="8.563" height="6.031" x="11.719" y="20.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_874" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:low-battery" /></template>
<style>
.a37_bobkd {
  stop-color: var(--svg-color--9b74bd, #9B74BD);
}

.awqtyhbpb {
  stop-color: var(--svg-color--dcdbdd, #DCDBDD);
}

.cpmb8-bcg {
  fill: var(--svg-color--c4345e, #C4345E);
  d: path("M17.881 22.952a.4.4 0 0 1 .4.4v1.232a.4.4 0 0 1-.4.4H14.12a.4.4 0 0 1-.4-.4v-1.232a.4.4 0 0 1 .4-.4z");
}

.cwtaagart {
  stop-color: var(--svg-color--d5d4d6, #D5D4D6);
  stop-opacity: 0;
}

.d8nqchuih {
  stop-color: var(--svg-color--bd4055, #BD4055);
}

.dtotehg2t {
  stop-color: var(--svg-color--cabbdb, #CABBDB);
  stop-opacity: 0;
}

.eipgzybpw {
  stop-color: var(--svg-color--a089b8, #A089B8);
  stop-opacity: 0;
}

.f0-my6v7j {
  fill: var(--svg-color--f6ecff, #F6ECFF);
  d: path("M15.384 8.675a.4.4 0 0 0-.4.4v.843a.05.05 0 0 1-.05.05h-.815a.4.4 0 0 0-.4.4v1.231a.4.4 0 0 0 .4.4h.815a.05.05 0 0 1 .05.05v.843c0 .221.18.4.4.4h1.232a.4.4 0 0 0 .4-.4v-.843a.05.05 0 0 1 .05-.05h.815a.4.4 0 0 0 .4-.4v-1.231a.4.4 0 0 0-.4-.4h-.815a.05.05 0 0 1-.05-.05v-.843a.4.4 0 0 0-.4-.4z");
}

.ft5dv1b6b {
  fill: none;
}

.h6622gb-c {
  stop-color: var(--svg-color--e7e4ea, #E7E4EA);
}

.ha165cbhx {
  stop-color: var(--svg-color--b9b2bf, #B9B2BF);
}

.hdms7abnt {
  stop-color: var(--svg-color--e84484, #E84484);
}

.ipkb4gz7l {
  stop-color: var(--svg-color--d0d0d1, #D0D0D1);
}

.is-fmvbzl {
  stop-color: var(--svg-color--c14a79, #C14A79);
}

.jjh-tmbov {
  stop-color: var(--svg-color--c4bbcf, #C4BBCF);
}

.k9ifomzon {
  d: path("M7.977 28.019c0 1.087.881 1.969 1.968 1.969h12.118a1.97 1.97 0 0 0 1.968-1.97z");
}

.lhdtcbcje {
  stop-color: var(--svg-color--cdcdce, #CDCDCE);
  stop-opacity: 0;
}

.op769yqsc {
  fill: var(--svg-color--f8ebff, #F8EBFF);
  d: path("M17.881 22.952a.4.4 0 0 1 .4.4v1.232a.4.4 0 0 1-.4.4H14.12a.4.4 0 0 1-.4-.4v-1.232a.4.4 0 0 1 .4-.4z");
}

.pgnvwlbfg {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
}

.pzqz5gwhq {
  d: path("M0 0h16.055v13.969H0z");
}

.rmgkmrb5v {
  stop-color: var(--svg-color--8b8b8c, #8B8B8C);
}

.s7t4csbls {
  stop-color: var(--svg-color--ee4c85, #EE4C85);
  stop-opacity: 0;
}

.so08fbb9y {
  stop-color: var(--svg-color--959396, #959396);
}

.v_oq59jpd {
  stop-color: var(--svg-color--cfcdd0, #CFCDD0);
}

.vca2t4y6i {
  stop-color: var(--svg-color--9a8aab, #9A8AAB);
}

.vlr-6ub1l {
  d: path("M12.973 2.777a.75.75 0 0 1 .75-.75h4.554a.75.75 0 0 1 .75.75v3.187h-6.054z");
}

.wk8eqmb8w {
  d: path("M7.977 6.034c0-1.087.881-1.968 1.968-1.968h12.118c1.087 0 1.968.881 1.968 1.968z");
}

.wwkq06b-l {
  stop-color: var(--svg-color--ee4c85, #EE4C85);
}

.xxd00c_ad {
  d: path("M7.977 20.003h16.055v8.016H7.977z");
}

.z--1bsaxs {
  stop-color: var(--svg-color--c14a79, #C14A79);
  stop-opacity: 0;
}

.z6-qfzm2e {
  stop-color: var(--svg-color--938d99, #938D99);
}

</style>
