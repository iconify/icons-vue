<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGKKxv1bVF" x1="49.979%" x2="49.979%" y1="-702.201%" y2="97.969%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGKJGOvfkX" x1="50%" x2="50%" y1="-602.243%" y2="197.926%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGHlnzSbhR" x1="49.979%" x2="49.979%" y1="-602.243%" y2="197.926%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGAy1YRdVi" x1="50.021%" x2="50.021%" y1="-502.498%" y2="298.01%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVG3bRWbdAG" x1="50%" x2="50%" y1="-502.498%" y2="298.01%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGSMH1tNET" x1="49.979%" x2="49.979%" y1="-502.498%" y2="298.01%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGDk6zTd0J" x1="50.021%" x2="50.021%" y1="-402.285%" y2="397.884%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGGTyrYbWF" x1="50%" x2="50%" y1="-402.285%" y2="397.884%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGhKvCPd4J" x1="49.979%" x2="49.979%" y1="-402.285%" y2="397.884%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGe4QvmexB" x1="50.021%" x2="50.021%" y1="-302.328%" y2="497.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVG2WfQ9gmL" x1="50%" x2="50%" y1="-302.328%" y2="497.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGsud9beXr" x1="49.979%" x2="49.979%" y1="-302.328%" y2="497.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVG44g0ZdjB" x1="50.021%" x2="50.021%" y1="-202.328%" y2="597.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGAi8oHeYv" x1="50%" x2="50%" y1="-202.328%" y2="597.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGPjGq4blz" x1="49.979%" x2="49.979%" y1="-202.328%" y2="597.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGXj60LuIn" x1="50%" x2="50%" y1="-102.37%" y2="697.799%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGStkKYT6k" x1="49.979%" x2="49.979%" y1="-102.37%" y2="697.799%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVG1PTmweIq" x1="49.979%" x2="49.979%" y1="-2.37%" y2="797.799%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient></defs><path fill="url(#SVGKKxv1bVF)" class="oy6rzccvx"/><path fill="url(#SVGKKxv1bVF)" class="sks6o-7jc"/><path fill="url(#SVGKKxv1bVF)" class="g-3skpakb"/><path fill="url(#SVGKKxv1bVF)" class="mu5_erb_a"/><path fill="url(#SVGKJGOvfkX)" class="gio8cv2mu"/><path fill="url(#SVGHlnzSbhR)" class="cru9oxbxf"/><path fill="url(#SVGHlnzSbhR)" class="a_zyvesru"/><path fill="url(#SVGHlnzSbhR)" class="w4nuxu9hw"/><path fill="url(#SVGHlnzSbhR)" class="v-k8f2psb"/><path fill="url(#SVGHlnzSbhR)" class="dzulhsbul"/><path fill="url(#SVGAy1YRdVi)" class="w42kihbfk"/><path fill="url(#SVG3bRWbdAG)" class="w5e85v_ns"/><path fill="url(#SVGSMH1tNET)" class="pxnmmabmo"/><path fill="url(#SVGSMH1tNET)" class="jzj9lje7g"/><path fill="url(#SVGSMH1tNET)" class="zh20ghb8c"/><path fill="url(#SVGSMH1tNET)" class="mysfrxg7n"/><path fill="url(#SVGSMH1tNET)" class="jl53b39tj"/><path fill="url(#SVGSMH1tNET)" class="gq32q_bkg"/><path fill="url(#SVGDk6zTd0J)" class="nmd81hbkv"/><path fill="url(#SVGGTyrYbWF)" class="qjbcfv0je"/><path fill="url(#SVGhKvCPd4J)" class="yagk299tk"/><path fill="url(#SVGhKvCPd4J)" class="thvjxxbio"/><path fill="url(#SVGhKvCPd4J)" class="szoybrcgz"/><path fill="url(#SVGhKvCPd4J)" class="ccw30gbmt"/><path fill="url(#SVGhKvCPd4J)" class="gskhluhiq"/><path fill="url(#SVGhKvCPd4J)" class="rl63xd-0u"/><path fill="url(#SVGe4QvmexB)" class="k5n2do36p"/><path fill="url(#SVG2WfQ9gmL)" class="edol0r0wh"/><path fill="url(#SVGsud9beXr)" class="vtpr_acat"/><path fill="url(#SVGsud9beXr)" class="mssrlj6wv"/><path fill="url(#SVGsud9beXr)" class="y6xnycvpw"/><path fill="url(#SVGsud9beXr)" class="yxpvwk_mm"/><path fill="url(#SVGsud9beXr)" class="a2si61bdv"/><path fill="url(#SVGsud9beXr)" class="l1peajgpv"/><path fill="url(#SVG44g0ZdjB)" class="qrt--sbeu"/><path fill="url(#SVGAi8oHeYv)" class="snnceqafm"/><path fill="url(#SVGPjGq4blz)" class="qz-710b2f"/><path fill="url(#SVGPjGq4blz)" class="ahocgggyh"/><path fill="url(#SVGPjGq4blz)" class="h-q09rbwm"/><path fill="url(#SVGPjGq4blz)" class="mkun2t-qa"/><path fill="url(#SVGPjGq4blz)" class="ci_1sqbnm"/><path fill="url(#SVGPjGq4blz)" class="cqz6sblsx"/><path fill="url(#SVGXj60LuIn)" class="v0zeylhpp"/><path fill="url(#SVGStkKYT6k)" class="uolbo08qo"/><path fill="url(#SVGStkKYT6k)" class="plq6t4boq"/><path fill="url(#SVGStkKYT6k)" class="m_hk-rb9w"/><path fill="url(#SVGStkKYT6k)" class="btjkmsslt"/><path fill="url(#SVGStkKYT6k)" class="ts28xi6jy"/><path fill="url(#SVG1PTmweIq)" class="sgsv437al"/><path fill="url(#SVG1PTmweIq)" class="lfno2mzdq"/><path fill="url(#SVG1PTmweIq)" class="adrxheb7c"/><path fill="url(#SVG1PTmweIq)" class="gd-q6jkbf"/><path class="cyfqqfbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:hcaptcha-icon" /></template>
<style>
.a_zyvesru {
  d: path("M128 192h32.007v32.007H128z");
}

.a2si61bdv {
  d: path("M32.007 96.007h32.007v32.007H32.007z");
}

.adrxheb7c {
  d: path("M96.007 0h32.007v32.007H96.007z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.ahocgggyh {
  d: path("M128 64h32.007v32.007H128z");
}

.btjkmsslt {
  d: path("M64 32.007h32.007v32.007H64z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.ccw30gbmt {
  d: path("M64 128h32.007v32.007H64z");
}

.ci_1sqbnm {
  d: path("M32.007 64h32.007v32.007H32.007z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.cqz6sblsx {
  d: path("M0 64h32.007v32.007H0z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cru9oxbxf {
  d: path("M160.007 192h32.007v32.007h-32.007z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.cyfqqfbns {
  fill: var(--svg-color--fff, #fff);
  d: path("m84.25 117.841l8.912-19.951c3.251-5.12 2.818-11.378-.745-14.9a9 9 0 0 0-1.57-1.26a9.85 9.85 0 0 0-8.223-.934a13.44 13.44 0 0 0-7.409 5.756s-12.19 28.445-16.755 41.285c-4.565 12.841-2.709 36.274 14.778 53.828c18.556 18.557 45.47 22.837 62.605 9.942a10.8 10.8 0 0 0 2.018-1.354l52.825-44.143c2.574-2.154 6.38-6.502 2.953-11.487c-3.427-4.984-9.63-1.557-12.19.095l-30.423 22.12a1.354 1.354 0 0 1-1.964-.231a3.74 3.74 0 0 1 .298-4.47l46.636-39.578c4.063-3.63 4.592-8.9 1.354-12.516s-8.249-3.44-12.299.23l-41.989 32.833a1.87 1.87 0 0 1-2.709-.352a2.587 2.587 0 0 1-.217-3.44l47.557-46.148a9.305 9.305 0 0 0 .474-13.125a8.9 8.9 0 0 0-6.461-2.709a9.48 9.48 0 0 0-6.678 2.71l-48.531 45.578c-1.165 1.165-3.44 0-3.712-1.355c-.1-.493.058-1.004.42-1.354L160.4 70.556a9.17 9.17 0 1 0-12.936-12.976l-56.428 62.307c-2.018 2.018-4.998 2.113-6.42.948a2.113 2.113 0 0 1-.366-2.994");
}

.dzulhsbul {
  d: path("M32.007 192h32.007v32.007H32.007z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.edol0r0wh {
  d: path("M192 96.007h31.993v32.007H192z");
}

.g-3skpakb {
  d: path("M96.007 223.993h32.007V256H96.007z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.gd-q6jkbf {
  d: path("M64 0h32.007v32.007H64z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gio8cv2mu {
  d: path("M192 192h31.993v32.007H192z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.gq32q_bkg {
  d: path("M0 160.007h32.007V192H0z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gskhluhiq {
  d: path("M32.007 128h32.007v32.007H32.007z");
}

.h-q09rbwm {
  d: path("M96.007 64h32.007v32.007H96.007z");
}

.jl53b39tj {
  d: path("M32.007 160.007h32.007V192H32.007z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.jvygbekff {
  stop-color: var(--svg-color--00d4bf, #00d4bf);
}

.jzj9lje7g {
  d: path("M128 160.007h32.007V192H128z");
}

.k5n2do36p {
  d: path("M223.993 96.007H256v32.007h-32.007z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.l1peajgpv {
  d: path("M0 96.007h32.007v32.007H0z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.lfno2mzdq {
  d: path("M128 0h32.007v32.007H128z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.m_hk-rb9w {
  d: path("M96.007 32.007h32.007v32.007H96.007z");
}

.mkun2t-qa {
  d: path("M64 64h32.007v32.007H64z");
}

.mssrlj6wv {
  d: path("M128 96.007h32.007v32.007H128z");
}

.mu5_erb_a {
  d: path("M64 223.993h32.007V256H64z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mysfrxg7n {
  d: path("M64 160.007h32.007V192H64z");
}

.nmd81hbkv {
  d: path("M223.993 128H256v32.007h-32.007z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.oy6rzccvx {
  d: path("M160.007 223.993h32.007V256h-32.007z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.plq6t4boq {
  d: path("M128 32.007h32.007v32.007H128z");
}

.pxnmmabmo {
  d: path("M160.007 160.007h32.007V192h-32.007z");
}

.q_s9d9jzm {
  stop-color: var(--svg-color--0074bf, #0074bf);
}

.qjbcfv0je {
  d: path("M192 128h31.993v32.007H192z");
}

.qrt--sbeu {
  d: path("M223.993 64H256v32.007h-32.007z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qz-710b2f {
  d: path("M160.007 64h32.007v32.007h-32.007z");
}

.rl63xd-0u {
  d: path("M0 128h32.007v32.007H0z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.sgsv437al {
  d: path("M160.007 0h32.007v32.007h-32.007z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sks6o-7jc {
  d: path("M128 223.993h32.007V256H128z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.snnceqafm {
  d: path("M192 64h31.993v32.007H192z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.szoybrcgz {
  d: path("M96.007 128h32.007v32.007H96.007z");
}

.thvjxxbio {
  d: path("M128 128h32.007v32.007H128z");
}

.ts28xi6jy {
  d: path("M32.007 32.007h32.007v32.007H32.007z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.uolbo08qo {
  d: path("M160.007 32.007h32.007v32.007h-32.007z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.v-k8f2psb {
  d: path("M64 192h32.007v32.007H64z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.v0zeylhpp {
  d: path("M192 32.007h31.993v32.007H192z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.vtpr_acat {
  d: path("M160.007 96.007h32.007v32.007h-32.007z");
}

.w42kihbfk {
  d: path("M223.993 160.007H256V192h-32.007z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w4nuxu9hw {
  d: path("M96.007 192h32.007v32.007H96.007z");
}

.w5e85v_ns {
  d: path("M192 160.007h31.993V192H192z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.y6xnycvpw {
  d: path("M96.007 96.007h32.007v32.007H96.007z");
}

.yagk299tk {
  d: path("M160.007 128h32.007v32.007h-32.007z");
}

.yxpvwk_mm {
  d: path("M64 96.007h32.007v32.007H64z");
}

.zh20ghb8c {
  d: path("M96.007 160.007h32.007V192H96.007z");
}

</style>
