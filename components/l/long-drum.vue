<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igCJvab)" class="l7uuibbft"/><path fill="url(#iTvz96c)" class="l7uuibbft"/><path fill="url(#iOockZi)" class="l7uuibbft"/><g filter="url(#iMBGO7d)"><path fill="url(#iTQB1Ie)" class="ig4t2ebkb"/><path fill="url(#ijRvFte)" class="ig4t2ebkb"/></g><path fill="url(#iCSbWqq)" class="ig4t2ebkb"/><path fill="url(#iBJ3S7b)" clip-rule="evenodd" class="i9nvaefsd"/><path fill="url(#iYndvdb)" clip-rule="evenodd" class="i9nvaefsd"/><path fill="url(#iEYeXvd)" clip-rule="evenodd" class="i9nvaefsd"/><g filter="url(#ipTPyVd)"><path fill="url(#im7VI4d)" clip-rule="evenodd" class="bjrdpsbvs"/></g><path fill="url(#i4SwzKb)" clip-rule="evenodd" class="yhk29izqx"/><rect fill="url(#iYWk1se)" class="r062t6hnt"/><rect fill="url(#iuneELc)" class="r062t6hnt"/><rect fill="url(#ixQOL3i)" class="kdd_9mbld"/><rect fill="url(#iIdvo6M)" class="kdd_9mbld"/><rect fill="url(#ibEYQob)" class="kdd_9mbld"/><defs><linearGradient id="igCJvab" x1="16.012" x2="16.012" y1="13.375" y2="20.125" gradientUnits="userSpaceOnUse"><stop class="ulq6hbeas"/><stop offset="1" class="r8p8kwj1g"/></linearGradient><linearGradient id="iOockZi" x1="16.012" x2="16.012" y1="3.688" y2="4.625" gradientUnits="userSpaceOnUse"><stop class="kfypncbdc"/><stop offset="1" class="r6g0hmbif"/></linearGradient><linearGradient id="iTQB1Ie" x1="13.176" x2="20.238" y1="26.125" y2="26.125" gradientUnits="userSpaceOnUse"><stop class="pnxjn0bcx"/><stop offset=".686" class="q4rz2db3a"/></linearGradient><linearGradient id="ijRvFte" x1="9.363" x2="12.426" y1="25.188" y2="25.906" gradientUnits="userSpaceOnUse"><stop class="mts0v_bmf"/><stop offset="1" class="c6hcf54zf"/></linearGradient><linearGradient id="iCSbWqq" x1="16.551" x2="16.551" y1="30.188" y2="29.188" gradientUnits="userSpaceOnUse"><stop class="v2asr7btd"/><stop offset="1" class="i5oc52bfm"/></linearGradient><linearGradient id="iYndvdb" x1="15.48" x2="15.684" y1="18.727" y2="18.727" gradientUnits="userSpaceOnUse"><stop offset=".308" class="n6b_sfkxj"/><stop offset="1" class="t46m0vb6f"/></linearGradient><linearGradient id="iEYeXvd" x1="16.57" x2="16.363" y1="19.344" y2="19.344" gradientUnits="userSpaceOnUse"><stop offset=".222" class="s8awk6m8u"/><stop offset="1" class="h6telsh1z"/></linearGradient><linearGradient id="im7VI4d" x1="12.415" x2="12.415" y1="3.828" y2="19.031" gradientUnits="userSpaceOnUse"><stop offset=".6" class="f5p84fb1h"/><stop offset="1" class="xoauzsbuf"/></linearGradient><linearGradient id="i4SwzKb" x1="19.625" x2="19.625" y1="3.828" y2="19.678" gradientUnits="userSpaceOnUse"><stop offset=".214" class="b2cn2_uce"/><stop offset=".776" class="dctuee17d"/></linearGradient><linearGradient id="iYWk1se" x1="16.02" x2="16.02" y1="2.047" y2="4.188" gradientUnits="userSpaceOnUse"><stop class="pc9ylub6n"/><stop offset="1" class="ias4kubhf"/></linearGradient><linearGradient id="ixQOL3i" x1="16" x2="16" y1="18.711" y2="20.164" gradientUnits="userSpaceOnUse"><stop class="ini6xob9o"/><stop offset="1" class="p94160srr"/></linearGradient><radialGradient id="iTvz96c" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.9375 -10.0567 0 21.457 7.375)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="pgq4gn82e"/><stop offset="1" class="vnxcp989p"/></radialGradient><radialGradient id="iBJ3S7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.9063 -1.43774 0 16.52 11.531)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="eed22risw"/><stop offset="1" class="zmhbxgbnr"/></radialGradient><radialGradient id="iuneELc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -12.6042 0 21.082 2.625)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="xlblee48v"/><stop offset="1" class="yqs7xtbzs"/></radialGradient><radialGradient id="iIdvo6M" cx="0" cy="0" r="1" gradientTransform="matrix(0 .70313 -5.625 0 18.816 19.25)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="lav973tlk"/><stop offset="1" class="dr8o1jbbg"/></radialGradient><radialGradient id="ibEYQob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85156 -6.36841 0 10.8 19.313)" gradientUnits="userSpaceOnUse"><stop class="srw-aqwzy"/><stop offset="1" class="epmcg6b1c"/></radialGradient><filter id="iMBGO7d" width="14.423" height="11.016" x="8.757" y="18.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.458824 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19005"/></filter><filter id="ipTPyVd" width="4.925" height="15.95" x="9.902" y="3.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.203922 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19005"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:long-drum" /></template>
<style>
.b2cn2_uce {
  stop-color: var(--svg-color--60506b, #60506B);
}

.bjrdpsbvs {
  fill-rule: evenodd;
  d: path("M10.002 3.828h1v5.844c0 2.458.003 6.005 3.825 9.243l-.646.763c-4.179-3.54-4.179-7.49-4.179-10z");
}

.c6hcf54zf {
  stop-color: var(--svg-color--bf7d4b, #BF7D4B);
  stop-opacity: 0;
}

.dctuee17d {
  stop-color: var(--svg-color--48285c, #48285C);
}

.dr8o1jbbg {
  stop-color: var(--svg-color--746681, #746681);
  stop-opacity: 0;
}

.eed22risw {
  stop-color: var(--svg-color--4f3965, #4F3965);
}

.epmcg6b1c {
  stop-color: var(--svg-color--49454d, #49454D);
  stop-opacity: 0;
}

.f5p84fb1h {
  stop-color: var(--svg-color--51455e, #51455E);
}

.ft5dv1b6b {
  fill: none;
}

.h6telsh1z {
  stop-color: var(--svg-color--5d4f6a, #5D4F6A);
  stop-opacity: 0;
}

.i5oc52bfm {
  stop-color: var(--svg-color--bf6466, #BF6466);
  stop-opacity: 0;
}

.i9nvaefsd {
  fill-rule: evenodd;
  d: path("M15.52 19.813V3.742h1v16.07z");
}

.ias4kubhf {
  stop-color: var(--svg-color--f4ad93, #F4AD93);
}

.ig4t2ebkb {
  d: path("M11.3 19.438h9.423l2.432 9.517a.8.8 0 0 1-.775.998H9.658a.8.8 0 0 1-.776-.997z");
}

.ini6xob9o {
  stop-color: var(--svg-color--2b1d37, #2B1D37);
}

.kdd_9mbld {
  width: 10.867px;
  height: 1.453px;
  x: 10.566px;
  y: 18.711px;
  rx: 0.727px;
}

.kfypncbdc {
  stop-color: var(--svg-color--c07041, #C07041);
}

.l7uuibbft {
  d: path("M16.129 20.11v.015l-.117-.008l-.117.008v-.016c-1.767-.126-4.322-.492-7.297-3.773c-1.828-2.336-1.97-4.945-1.97-6.18V3.5h18.767v6.656c0 1.235-.141 3.844-1.97 6.18c-2.974 3.282-5.53 3.647-7.296 3.773");
}

.lav973tlk {
  stop-color: var(--svg-color--746681, #746681);
}

.mts0v_bmf {
  stop-color: var(--svg-color--b17e59, #B17E59);
}

.n6b_sfkxj {
  stop-color: var(--svg-color--442f54, #442F54);
}

.p94160srr {
  stop-color: var(--svg-color--5a316f, #5A316F);
}

.pc9ylub6n {
  stop-color: var(--svg-color--e1b177, #E1B177);
}

.pgq4gn82e {
  stop-color: var(--svg-color--e69f62, #E69F62);
}

.pnxjn0bcx {
  stop-color: var(--svg-color--cb8349, #CB8349);
}

.q4rz2db3a {
  stop-color: var(--svg-color--e7a672, #E7A672);
}

.r062t6hnt {
  width: 20.719px;
  height: 1.969px;
  x: 5.66px;
  y: 2.047px;
  rx: 0.984px;
}

.r6g0hmbif {
  stop-color: var(--svg-color--c07041, #C07041);
  stop-opacity: 0;
}

.r8p8kwj1g {
  stop-color: var(--svg-color--aa5961, #AA5961);
}

.s8awk6m8u {
  stop-color: var(--svg-color--5d4f6a, #5D4F6A);
}

.srw-aqwzy {
  stop-color: var(--svg-color--49454d, #49454D);
}

.t46m0vb6f {
  stop-color: var(--svg-color--442f54, #442F54);
  stop-opacity: 0;
}

.ulq6hbeas {
  stop-color: var(--svg-color--be7846, #BE7846);
}

.v2asr7btd {
  stop-color: var(--svg-color--bf6466, #BF6466);
}

.vnxcp989p {
  stop-color: var(--svg-color--e69f62, #E69F62);
  stop-opacity: 0;
}

.xlblee48v {
  stop-color: var(--svg-color--ffd8a2, #FFD8A2);
}

.xoauzsbuf {
  stop-color: var(--svg-color--43255b, #43255B);
}

.yhk29izqx {
  fill-rule: evenodd;
  d: path("M22.037 3.828h-1v5.844c0 2.458-.003 6.005-3.825 9.243l.647.763c4.178-3.54 4.178-7.49 4.178-10z");
}

.yqs7xtbzs {
  stop-color: var(--svg-color--ffd8a2, #FFD8A2);
  stop-opacity: 0;
}

.zmhbxgbnr {
  stop-color: var(--svg-color--3c1157, #3C1157);
}

</style>
