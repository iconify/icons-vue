<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1DJmKc)"><rect fill="url(#iojZHjd)" class="k4uzdt81m"/></g><rect fill="url(#iLkNHqe)" class="k4uzdt81m"/><rect fill="url(#iZCsRbb)" class="k4uzdt81m"/><rect fill="url(#iy6ibub)" class="k4uzdt81m"/><g filter="url(#iuyEyWd)"><path fill="url(#iwjb5Yb)" class="w7p8xgbqo"/></g><path fill="url(#ipomiwh)" clip-rule="evenodd" class="uvna4ulbz"/><path fill="url(#i345xId)" clip-rule="evenodd" class="uvna4ulbz"/><path fill="url(#iMungCH)" clip-rule="evenodd" class="uvna4ulbz"/><path fill="url(#iKejTov)" clip-rule="evenodd" class="uvna4ulbz"/><path fill="url(#ic5aK6d)" clip-rule="evenodd" class="kfnbscbqv"/><path fill="url(#ioCEjln)" clip-rule="evenodd" class="kfnbscbqv"/><path fill="url(#i6lexCb)" clip-rule="evenodd" class="kfnbscbqv"/><g filter="url(#i2RADcd)"><path fill="url(#i2mp3OK)" class="sc-je_b5z"/></g><g filter="url(#iW645ye)"><path fill="url(#iXK1KdD)" class="joe5xsbsx"/></g><g filter="url(#iz3VLzb)"><path fill="url(#iz1fgGd)" class="frlrw1bdp"/></g><path fill="url(#ihA9tTb)" class="frlrw1bdp"/><g filter="url(#i6kR1od)"><rect fill="url(#i6Nf8Sb)" class="dojj77bgd"/></g><path fill="url(#i3S6lYd)" class="ootj-nohg"/><path fill="url(#iUOiCve)" class="ootj-nohg"/><g filter="url(#iGrDPdf)"><path fill="url(#iTtKvwT)" class="uv2zhglfs"/></g><g filter="url(#iU6l5Px)"><rect fill="url(#iaQAW0c)" class="wph9y-psm"/></g><g filter="url(#iq6SxAc)"><path fill="url(#iansojc)" class="whxobqbli"/></g><g filter="url(#iAzupSd)"><rect fill="url(#iawGxxd)" class="w7zcm_bph"/></g><defs><linearGradient id="iojZHjd" x1="27.125" x2="11.875" y1="3.883" y2="23.32" gradientUnits="userSpaceOnUse"><stop class="uyh48sl0l"/><stop offset="1" class="tx-ejek8w"/></linearGradient><linearGradient id="iLkNHqe" x1="21.475" x2="21.475" y1="30.224" y2="27.926" gradientUnits="userSpaceOnUse"><stop class="zj8kg6brj"/><stop offset="1" class="jbzt1quqs"/></linearGradient><linearGradient id="iwjb5Yb" x1="24.382" x2="24.382" y1="7.043" y2="29.198" gradientUnits="userSpaceOnUse"><stop class="o5wayzbvi"/><stop offset="1" class="stbgwbini"/></linearGradient><linearGradient id="ipomiwh" x1="16" x2="16" y1="4.367" y2="29.961" gradientUnits="userSpaceOnUse"><stop class="av2-vqbow"/><stop offset="1" class="ny3yfgb0o"/></linearGradient><linearGradient id="i345xId" x1="21.719" x2="21.719" y1="30.676" y2="27.195" gradientUnits="userSpaceOnUse"><stop class="h8su5dx7m"/><stop offset="1" class="nklmu6d-u"/></linearGradient><linearGradient id="iMungCH" x1="1.078" x2="6.391" y1="17.367" y2="17.367" gradientUnits="userSpaceOnUse"><stop class="lfsn49ywy"/><stop offset="1" class="c27919bru"/></linearGradient><linearGradient id="iKejTov" x1="30.766" x2="26.953" y1="18.055" y2="18.055" gradientUnits="userSpaceOnUse"><stop class="vsb_wlbyi"/><stop offset="1" class="bnoc2wb_b"/></linearGradient><linearGradient id="ic5aK6d" x1="24.187" x2="20.164" y1="18.334" y2="18.334" gradientUnits="userSpaceOnUse"><stop offset=".452" class="iv18v2a_k"/><stop offset="1" class="oi7mf8v1y"/></linearGradient><linearGradient id="ioCEjln" x1="21.029" x2="21.029" y1="30.534" y2="28.371" gradientUnits="userSpaceOnUse"><stop class="ad8_gdjmy"/><stop offset="1" class="e4rf81irl"/></linearGradient><linearGradient id="i6lexCb" x1="19.645" x2="19.645" y1="1.549" y2="10.158" gradientUnits="userSpaceOnUse"><stop offset=".668" class="etlos9d4n"/><stop offset="1" class="s_qnsac8i"/></linearGradient><linearGradient id="i2mp3OK" x1="15.362" x2="15.362" y1="17.036" y2="29.625" gradientUnits="userSpaceOnUse"><stop class="o5wayzbvi"/><stop offset="1" class="stbgwbini"/></linearGradient><linearGradient id="iXK1KdD" x1="6.234" x2="6.234" y1="9.428" y2="28.803" gradientUnits="userSpaceOnUse"><stop class="o5wayzbvi"/><stop offset="1" class="stbgwbini"/></linearGradient><linearGradient id="iz1fgGd" x1="25.02" x2="25.02" y1="5.594" y2="29.961" gradientUnits="userSpaceOnUse"><stop offset=".18" class="h24bu9byo"/><stop offset="1" class="fsgrapb9r"/></linearGradient><linearGradient id="ihA9tTb" x1="21.722" x2="23.538" y1="29.452" y2="29.366" gradientUnits="userSpaceOnUse"><stop offset=".011" class="mv_j09fky"/><stop offset="1" class="ryd8bmloc"/></linearGradient><linearGradient id="i6Nf8Sb" x1="26.827" x2="26.827" y1="6.527" y2="29.028" gradientUnits="userSpaceOnUse"><stop class="aamjxwftu"/><stop offset="1" class="v672d8bvj"/></linearGradient><linearGradient id="iUOiCve" x1="1.519" x2="5.975" y1="17.469" y2="17.469" gradientUnits="userSpaceOnUse"><stop class="k_g6hrbgm"/><stop offset="1" class="c9iz6qbji"/></linearGradient><linearGradient id="iTtKvwT" x1="16" x2="16" y1="16.647" y2="29.961" gradientUnits="userSpaceOnUse"><stop offset=".18" class="ksvv28h1p"/><stop offset="1" class="g1uk9gbes"/></linearGradient><linearGradient id="iaQAW0c" x1="17.806" x2="17.806" y1="17.555" y2="29.198" gradientUnits="userSpaceOnUse"><stop class="m7uhw607c"/><stop offset="1" class="xekvt6bii"/></linearGradient><linearGradient id="iansojc" x1="6.98" x2="6.98" y1="8.665" y2="29.961" gradientUnits="userSpaceOnUse"><stop offset=".18" class="dzca_wbvk"/><stop offset="1" class="jc8w9rbzr"/></linearGradient><linearGradient id="iawGxxd" x1="9.111" x2="9.111" y1="9.428" y2="29.198" gradientUnits="userSpaceOnUse"><stop class="u2tqxybva"/><stop offset="1" class="if12pab8v"/></linearGradient><filter id="i1DJmKc" width="30.406" height="29.906" x="1.047" y="1.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.87451 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23005"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.67451 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23005" result="effect2_innerShadow_18_23005"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.729412 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23005" result="effect3_innerShadow_18_23005"/></filter><filter id="iuyEyWd" width="7.754" height="24.155" x="20.505" y="6.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23005" stdDeviation=".5"/></filter><filter id="i2RADcd" width="7.754" height="14.589" x="11.485" y="16.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23005" stdDeviation=".5"/></filter><filter id="iW645ye" width="7.754" height="21.375" x="2.357" y="8.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23005" stdDeviation=".5"/></filter><filter id="iz3VLzb" width="6.644" height="24.367" x="22.073" y="5.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.482353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23005"/></filter><filter id="i6kR1od" width="2.865" height="24.502" x="25.394" y="5.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23005" stdDeviation=".5"/></filter><filter id="iGrDPdf" width="6.644" height="13.314" x="13.053" y="16.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.239216 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23005"/></filter><filter id="iU6l5Px" width="2.865" height="13.643" x="16.374" y="16.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23005" stdDeviation=".5"/></filter><filter id="iq6SxAc" width="6.644" height="21.296" x="4.033" y="8.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.792157 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23005"/></filter><filter id="iAzupSd" width="2.865" height="21.77" x="7.678" y="8.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23005" stdDeviation=".5"/></filter><radialGradient id="iZCsRbb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.58858 .20883 -.81418 -21.7886 29.953 16.403)" gradientUnits="userSpaceOnUse"><stop class="x4aqjrs3p"/><stop offset="1" class="nfy4fkukk"/></radialGradient><radialGradient id="iy6ibub" cx="0" cy="0" r="1" gradientTransform="matrix(-3.69009 3.2723 -3.38707 -3.81951 29.586 2.896)" gradientUnits="userSpaceOnUse"><stop class="iar3vjb-g"/><stop offset="1" class="vdus3ubud"/></radialGradient><radialGradient id="i3S6lYd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46588 0 0 -2.37936 14.324 20.93)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="gwkmeheof"/><stop offset="1" class="cww_33b8m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bar-chart" /></template>
<style>
.aamjxwftu {
  stop-color: var(--svg-color--53bfff, #53BFFF);
}

.ad8_gdjmy {
  stop-color: var(--svg-color--9070ad, #9070AD);
}

.av2-vqbow {
  stop-color: var(--svg-color--c2bec6, #C2BEC6);
}

.bnoc2wb_b {
  stop-color: var(--svg-color--d6d1da, #D6D1DA);
  stop-opacity: 0;
}

.c27919bru {
  stop-color: var(--svg-color--96909c, #96909C);
  stop-opacity: 0;
}

.c9iz6qbji {
  stop-color: var(--svg-color--88858d, #88858D);
  stop-opacity: 0;
}

.cww_33b8m {
  stop-color: var(--svg-color--86738a, #86738A);
  stop-opacity: 0;
}

.dojj77bgd {
  width: 0.865px;
  height: 22.501px;
  x: 26.394px;
  y: 6.527px;
  rx: 0.433px;
}

.dzca_wbvk {
  stop-color: var(--svg-color--abe263, #ABE263);
}

.e4rf81irl {
  stop-color: var(--svg-color--9070ad, #9070AD);
  stop-opacity: 0;
}

.etlos9d4n {
  stop-color: var(--svg-color--c3bfc7, #C3BFC7);
}

.frlrw1bdp {
  d: path("M27.967 29.5a3.8 3.8 0 0 1-1.814.461h-4.08V6.794a1.2 1.2 0 0 1 1.2-1.2h3.494a1.2 1.2 0 0 1 1.2 1.2z");
}

.fsgrapb9r {
  stop-color: var(--svg-color--3e79cb, #3E79CB);
}

.ft5dv1b6b {
  fill: none;
}

.g1uk9gbes {
  stop-color: var(--svg-color--dd385f, #DD385F);
}

.gwkmeheof {
  stop-color: var(--svg-color--86738a, #86738A);
}

.h24bu9byo {
  stop-color: var(--svg-color--36a4f2, #36A4F2);
}

.h8su5dx7m {
  stop-color: var(--svg-color--9e83b7, #9E83B7);
}

.iar3vjb-g {
  stop-color: var(--svg-color--f7f4f7, #F7F4F7);
}

.if12pab8v {
  stop-color: var(--svg-color--6ceda7, #6CEDA7);
}

.iv18v2a_k {
  stop-color: var(--svg-color--7c7695, #7C7695);
}

.jbzt1quqs {
  stop-color: var(--svg-color--cdbce0, #CDBCE0);
  stop-opacity: 0;
}

.jc8w9rbzr {
  stop-color: var(--svg-color--61e19b, #61E19B);
}

.joe5xsbsx {
  d: path("M9.11 28.437a4.4 4.4 0 0 1-1.77.366H3.357V10.382c0-.527.524-.954 1.171-.954H7.94c.647 0 1.172.427 1.172.954z");
}

.k_g6hrbgm {
  stop-color: var(--svg-color--88858d, #88858D);
}

.k4uzdt81m {
  width: 27.906px;
  height: 27.906px;
  x: 2.047px;
  y: 2.055px;
  rx: 3.8px;
}

.kfnbscbqv {
  fill-rule: evenodd;
  d: path("M11.523 2.055h-1v8.39H2.047v1h8.476v8.97H2.047v1h8.476v8.546h1v-8.547h9v8.547h1v-8.547h1.972v-1h-1.972v-8.969h1.972v-1h-1.972v-8.39h-1v8.39h-9zm9 9.39v8.97h-9v-8.97z");
}

.ksvv28h1p {
  stop-color: var(--svg-color--e93586, #E93586);
}

.lfsn49ywy {
  stop-color: var(--svg-color--96909c, #96909C);
}

.m7uhw607c {
  stop-color: var(--svg-color--fa5598, #FA5598);
}

.mv_j09fky {
  stop-color: var(--svg-color--404e95, #404E95);
}

.nfy4fkukk {
  stop-color: var(--svg-color--ded3e7, #DED3E7);
  stop-opacity: 0;
}

.nklmu6d-u {
  stop-color: var(--svg-color--9e83b7, #9E83B7);
  stop-opacity: 0;
}

.ny3yfgb0o {
  stop-color: var(--svg-color--baacc6, #BAACC6);
}

.o5wayzbvi {
  stop-color: var(--svg-color--9b98b3, #9B98B3);
}

.oi7mf8v1y {
  stop-color: var(--svg-color--7c7695, #7C7695);
  stop-opacity: 0;
}

.ootj-nohg {
  d: path("M13.459 10.445h-1.936v-8.39h-1v8.39H2.047v1h8.476v8.97H2.047v1h8.476v8.546h1v-8.547h1.936v-1h-1.936v-8.969h1.936z");
}

.ryd8bmloc {
  stop-color: var(--svg-color--2f66b3, #2F66B3);
  stop-opacity: 0;
}

.s_qnsac8i {
  stop-color: var(--svg-color--c3bfc7, #C3BFC7);
  stop-opacity: 0;
}

.sc-je_b5z {
  d: path("M18.24 29.387a6.5 6.5 0 0 1-1.772.238h-3.983V17.656c0-.342.524-.62 1.171-.62h3.412c.647 0 1.171.278 1.171.62z");
}

.stbgwbini {
  stop-color: var(--svg-color--9c83ae, #9C83AE);
}

.tx-ejek8w {
  stop-color: var(--svg-color--d5c9e3, #D5C9E3);
}

.u2tqxybva {
  stop-color: var(--svg-color--c9fe70, #C9FE70);
}

.uv2zhglfs {
  d: path("M18.947 29.961h-5.894V17.847a1.2 1.2 0 0 1 1.2-1.2h3.494a1.2 1.2 0 0 1 1.2 1.2z");
}

.uvna4ulbz {
  fill-rule: evenodd;
  d: path("M11.523 2.055h-1v8.39H2.047v1h8.476v8.97H2.047v1h8.476v8.546h1v-8.547h9v8.547h1v-8.547h8.43v-1h-8.43v-8.969h8.43v-1h-8.43v-8.39h-1v8.39h-9zm9 9.39v8.97h-9v-8.97z");
}

.uyh48sl0l {
  stop-color: var(--svg-color--d8d1e0, #D8D1E0);
}

.v672d8bvj {
  stop-color: var(--svg-color--508edc, #508EDC);
}

.vdus3ubud {
  stop-color: var(--svg-color--e2dce5, #E2DCE5);
  stop-opacity: 0;
}

.vsb_wlbyi {
  stop-color: var(--svg-color--d6d1da, #D6D1DA);
}

.w7p8xgbqo {
  d: path("M27.26 28.78a3.9 3.9 0 0 1-1.771.418h-3.984V8.134c0-.603.525-1.091 1.172-1.091h3.411c.647 0 1.171.488 1.171 1.09z");
}

.w7zcm_bph {
  width: 0.865px;
  height: 19.77px;
  x: 8.678px;
  y: 9.428px;
  rx: 0.433px;
}

.whxobqbli {
  d: path("M9.927 29.96h-4.08a3.8 3.8 0 0 1-1.814-.46V9.866a1.2 1.2 0 0 1 1.2-1.2h3.494a1.2 1.2 0 0 1 1.2 1.2z");
}

.wph9y-psm {
  width: 0.865px;
  height: 11.643px;
  x: 17.374px;
  y: 17.555px;
  rx: 0.433px;
}

.x4aqjrs3p {
  stop-color: var(--svg-color--f2edf5, #F2EDF5);
}

.xekvt6bii {
  stop-color: var(--svg-color--f34f70, #F34F70);
}

.zj8kg6brj {
  stop-color: var(--svg-color--a88ac4, #A88AC4);
}

</style>
