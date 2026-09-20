<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":140};
const content = `<defs><linearGradient id="SVGKKxv1bVF" x1="49.979%" x2="49.979%" y1="-702.201%" y2="97.969%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGKJGOvfkX" x1="50%" x2="50%" y1="-602.243%" y2="197.926%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGHlnzSbhR" x1="49.979%" x2="49.979%" y1="-602.243%" y2="197.926%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGAy1YRdVi" x1="50.021%" x2="50.021%" y1="-502.498%" y2="298.01%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVG3bRWbdAG" x1="50%" x2="50%" y1="-502.498%" y2="298.01%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGSMH1tNET" x1="49.979%" x2="49.979%" y1="-502.498%" y2="298.01%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGDk6zTd0J" x1="50.021%" x2="50.021%" y1="-402.285%" y2="397.884%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGGTyrYbWF" x1="50%" x2="50%" y1="-402.285%" y2="397.884%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGhKvCPd4J" x1="49.979%" x2="49.979%" y1="-402.285%" y2="397.884%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGe4QvmexB" x1="50.021%" x2="50.021%" y1="-302.328%" y2="497.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVG2WfQ9gmL" x1="50%" x2="50%" y1="-302.328%" y2="497.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGsud9beXr" x1="49.979%" x2="49.979%" y1="-302.328%" y2="497.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVG44g0ZdjB" x1="50.021%" x2="50.021%" y1="-202.328%" y2="597.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGAi8oHeYv" x1="50%" x2="50%" y1="-202.328%" y2="597.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGPjGq4blz" x1="49.979%" x2="49.979%" y1="-202.328%" y2="597.842%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGXj60LuIn" x1="50%" x2="50%" y1="-102.37%" y2="697.799%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVGStkKYT6k" x1="49.979%" x2="49.979%" y1="-102.37%" y2="697.799%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient><linearGradient id="SVG1PTmweIq" x1="49.979%" x2="49.979%" y1="-2.37%" y2="797.799%"><stop offset="0%" class="jvygbekff"/><stop offset="100%" class="q_s9d9jzm"/></linearGradient></defs><path fill="url(#SVGKKxv1bVF)" class="new7msb2m"/><path fill="url(#SVGKKxv1bVF)" class="sum-ilzts"/><path fill="url(#SVGKKxv1bVF)" class="d6xx6acxl"/><path fill="url(#SVGKKxv1bVF)" class="f2yb8nbud"/><path fill="url(#SVGKJGOvfkX)" class="nz3yshbaz"/><path fill="url(#SVGHlnzSbhR)" class="eo76xkblk"/><path fill="url(#SVGHlnzSbhR)" class="f4mb9fbtg"/><path fill="url(#SVGHlnzSbhR)" class="rigymjb7t"/><path fill="url(#SVGHlnzSbhR)" class="hplvhebxn"/><path fill="url(#SVGHlnzSbhR)" class="ceyi84hml"/><path fill="url(#SVGAy1YRdVi)" class="v92fwbbau"/><path fill="url(#SVG3bRWbdAG)" class="g7ws59-4r"/><path fill="url(#SVGSMH1tNET)" class="zhnl9huup"/><path fill="url(#SVGSMH1tNET)" class="a0xdxlrkj"/><path fill="url(#SVGSMH1tNET)" class="enx_79bno"/><path fill="url(#SVGSMH1tNET)" class="d8kbf1_nx"/><path fill="url(#SVGSMH1tNET)" class="mpy9f5b2d"/><path fill="url(#SVGSMH1tNET)" class="vkba8_b9o"/><path fill="url(#SVGDk6zTd0J)" class="qf__hrb8u"/><path fill="url(#SVGGTyrYbWF)" class="ppmamzb2d"/><path fill="url(#SVGhKvCPd4J)" class="l3-3lybif"/><path fill="url(#SVGhKvCPd4J)" class="szz2accgg"/><path fill="url(#SVGhKvCPd4J)" class="fctzsgeia"/><path fill="url(#SVGhKvCPd4J)" class="oofya7b0d"/><path fill="url(#SVGhKvCPd4J)" class="iv3cl2djn"/><path fill="url(#SVGhKvCPd4J)" class="dhtweeb4c"/><path fill="url(#SVGe4QvmexB)" class="gxk7jf54k"/><path fill="url(#SVG2WfQ9gmL)" class="gjdcb_bze"/><path fill="url(#SVGsud9beXr)" class="pcgfq-bcr"/><path fill="url(#SVGsud9beXr)" class="y_mb9yb7i"/><path fill="url(#SVGsud9beXr)" class="ln8tw2m_b"/><path fill="url(#SVGsud9beXr)" class="zxxaadbzd"/><path fill="url(#SVGsud9beXr)" class="fqtto5mrf"/><path fill="url(#SVGsud9beXr)" class="gice1i_4s"/><path fill="url(#SVG44g0ZdjB)" class="l0p1cu6hq"/><path fill="url(#SVGAi8oHeYv)" class="avcy8couu"/><path fill="url(#SVGPjGq4blz)" class="jlrwpcbop"/><path fill="url(#SVGPjGq4blz)" class="w1h3dwbae"/><path fill="url(#SVGPjGq4blz)" class="db-b7-b-p"/><path fill="url(#SVGPjGq4blz)" class="rwjoyfboh"/><path fill="url(#SVGPjGq4blz)" class="m2po0-b0v"/><path fill="url(#SVGPjGq4blz)" class="tpsk40b7o"/><path fill="url(#SVGXj60LuIn)" class="fn9a0zbwx"/><path fill="url(#SVGStkKYT6k)" class="nvm4d4bpq"/><path fill="url(#SVGStkKYT6k)" class="h6_qvpb5k"/><path fill="url(#SVGStkKYT6k)" class="r8c_1vrgm"/><path fill="url(#SVGStkKYT6k)" class="q1d3p4xoa"/><path fill="url(#SVGStkKYT6k)" class="rvvk-f7ql"/><path fill="url(#SVG1PTmweIq)" class="cqak80ozn"/><path fill="url(#SVG1PTmweIq)" class="qn8v09blj"/><path fill="url(#SVG1PTmweIq)" class="l41aal3yz"/><path fill="url(#SVG1PTmweIq)" class="cwc427bgh"/><path class="fpb25iu7m"/><path class="etl679bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:hcaptcha" /></template>
<style>
.a0xdxlrkj {
  d: path("M69.88 87.353h17.474v17.466H69.88z");
}

.avcy8couu {
  d: path("M104.82 34.94h17.466v17.474H104.82z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.ceyi84hml {
  d: path("M17.474 104.82h17.474v17.474H17.474z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.cqak80ozn {
  d: path("M87.353 0h17.474v17.474H87.353z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cwc427bgh {
  d: path("M34.94 0h17.474v17.474H34.94z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.d6xx6acxl {
  d: path("M52.413 122.286h17.474v17.474H52.413z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.d8kbf1_nx {
  d: path("M34.94 87.353h17.474v17.466H34.94z");
}

.db-b7-b-p {
  d: path("M52.413 34.94h17.474v17.474H52.413z");
}

.dhtweeb4c {
  d: path("M0 69.88h17.474v17.474H0z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.enx_79bno {
  d: path("M52.413 87.353h17.474v17.466H52.413z");
}

.eo76xkblk {
  d: path("M87.353 104.82h17.474v17.474H87.353z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.etl679bjs {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
  d: path("M196.765 101.056h-13.421V78.132c0-5.302-.666-9.901-6.256-9.901s-7.336 4.947-7.336 11.402v21.386h-13.31V40.072h13.31l-.003 16.17a652 652 0 0 1-.078 7.522a13.1 13.1 0 0 1 12.09-7.069c11.801 0 14.941 7.885 15.003 18.332zm52.79-18.39l4.49 11.143l-.326.348c-3.038 3.191-9.101 7.956-20.432 7.956c-16.926 0-30.177-11.831-30.177-31.464s13.414-31.457 30.17-31.457c11.831 0 18.257 5.213 19.758 6.892l-4.17 11.831c-1.087-1.479-7.254-6.367-14.841-6.367c-9.754 0-17.26 6.892-17.26 18.827s7.839 18.738 17.26 18.738c7.173 0 12.341-3.002 15.529-6.448m46.668 18.39h-12.755l-.252-4.592l-.597.629c-1.881 1.955-5.18 4.939-11.16 4.939c-7.255 0-14.923-4.156-14.923-13.873s8.423-12.992 16.01-13.31l10.352-.444v-1.013c0-4.6-3.083-6.98-8.422-6.98c-4.461.16-8.8 1.502-12.571 3.89L258.4 61.11a38.65 38.65 0 0 1 17.592-4.437c7.668 0 12.09 1.856 15.336 5.036s4.918 7.394 4.918 14.789zM282.965 81.88l-6.589.444c-4.082.177-6.5 2.033-6.5 5.302s2.588 5.39 6.256 5.39a8.13 8.13 0 0 0 6.833-3.978zm48.02 20.166c-6.085 0-10.418-2.389-13.007-6.449v21.445h-13.317V57.486h12.674l-.103 5.568h.17c3.002-3.8 7.394-6.366 13.672-6.366c11.832 0 19.345 9.812 19.345 22.627s-7.506 22.732-19.433 22.732m-3.837-34.2c-5.672 0-9.613 4.591-9.613 11.313s3.919 11.314 9.613 11.314s9.68-4.622 9.68-11.351s-3.92-11.299-9.673-11.299zm54.195.42h-9.088v15.64l.004.51c.045 3.273.53 4.12 1.165 4.881c.665.799 1.42 1.058 3.165 1.058a11.8 11.8 0 0 0 4-.8l.666 11.049a34.2 34.2 0 0 1-9.502 1.442c-4.755 0-7.92-1.48-10.005-4.068c-2.045-2.537-2.888-6.048-2.92-12.428l-.001-17.283h-5.835V57.575h5.835V45.743h13.421v11.832h9.095zM417.6 86.105l3.157 10.707l-.35.332c-1.267 1.174-5.786 4.881-15.327 4.881c-11.254 0-21.673-8.134-21.673-22.627c0-14.494 10.589-22.717 21.843-22.717c10.508 0 15.256 4.592 15.256 4.592l-2.921 10.693a16.36 16.36 0 0 0-10.59-3.89c-5.671 0-10.167 4.156-10.167 11.048s4.082 11.225 10.352 11.225a15.83 15.83 0 0 0 10.42-4.244m49.108 14.952h-13.414V78.132c0-5.302-.666-9.901-6.256-9.901c-5.516 0-7.289 4.816-7.335 11.145v21.643h-13.311V40.072h13.31l-.003 16.17c-.016 3.882-.078 7.522-.078 7.522a13.1 13.1 0 0 1 12.09-7.069c11.92 0 15.004 8.045 15.004 18.65zm45.27 0h-12.756l-.251-4.592l-.597.629c-1.882 1.955-5.181 4.939-11.161 4.939c-7.254 0-14.922-4.156-14.922-13.873s8.422-12.992 16.01-13.31l10.352-.444v-1.013c0-4.6-3.084-6.98-8.423-6.98a25.2 25.2 0 0 0-12.57 3.89l-3.506-9.192a38.65 38.65 0 0 1 17.592-4.437c7.668 0 12.09 1.856 15.337 5.036S512 69.103 512 76.498zM498.719 81.88l-6.588.444c-4.082.177-6.5 2.033-6.5 5.302s2.588 5.39 6.255 5.39a8.13 8.13 0 0 0 6.833-3.978z");
}

.f2yb8nbud {
  d: path("M34.94 122.286h17.474v17.474H34.94z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.f4mb9fbtg {
  d: path("M69.88 104.82h17.474v17.474H69.88z");
}

.fctzsgeia {
  d: path("M52.413 69.88h17.474v17.474H52.413z");
}

.fn9a0zbwx {
  d: path("M104.82 17.474h17.466v17.474H104.82z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.fpb25iu7m {
  fill: var(--svg-color--fff, #fff);
  d: path("M45.995 64.334L50.86 53.44c1.774-2.795 1.538-6.211-.407-8.134q-.39-.39-.858-.688a5.38 5.38 0 0 0-4.488-.51a7.34 7.34 0 0 0-4.045 3.143S34.406 62.78 31.914 69.79s-1.479 19.803 8.068 29.386c10.13 10.131 24.824 12.468 34.178 5.428a6 6 0 0 0 1.102-.74l28.84-24.099c1.404-1.175 3.482-3.55 1.611-6.27c-1.87-2.722-5.257-.85-6.655.051L82.451 85.623a.74.74 0 0 1-1.073-.126a2.04 2.04 0 0 1 .163-2.44l25.46-21.607c2.218-1.982 2.507-4.859.74-6.833s-4.504-1.878-6.715.126L78.103 72.667a1.02 1.02 0 0 1-1.48-.192a1.41 1.41 0 0 1-.118-1.878l25.963-25.194a5.08 5.08 0 0 0 .259-7.165a4.85 4.85 0 0 0-3.527-1.48a5.18 5.18 0 0 0-3.646 1.48L69.059 63.12c-.636.636-1.878 0-2.026-.74a.8.8 0 0 1 .229-.739l20.306-23.123a5.006 5.006 0 1 0-7.062-7.084L49.7 65.45c-1.102 1.102-2.729 1.154-3.505.518a1.154 1.154 0 0 1-.2-1.634");
}

.fqtto5mrf {
  d: path("M17.474 52.413h17.474v17.474H17.474z");
}

.g7ws59-4r {
  d: path("M104.82 87.353h17.466v17.466H104.82z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.gice1i_4s {
  d: path("M0 52.413h17.474v17.474H0z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.gjdcb_bze {
  d: path("M104.82 52.413h17.466v17.474H104.82z");
}

.gxk7jf54k {
  d: path("M122.286 52.413h17.474v17.474h-17.474z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.h6_qvpb5k {
  d: path("M69.88 17.474h17.474v17.474H69.88z");
}

.hplvhebxn {
  d: path("M34.94 104.82h17.474v17.474H34.94z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.iv3cl2djn {
  d: path("M17.474 69.88h17.474v17.474H17.474z");
}

.jlrwpcbop {
  d: path("M87.353 34.94h17.474v17.474H87.353z");
}

.jvygbekff {
  stop-color: var(--svg-color--00d4bf, #00d4bf);
}

.l0p1cu6hq {
  d: path("M122.286 34.94h17.474v17.474h-17.474z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.l3-3lybif {
  d: path("M87.353 69.88h17.474v17.474H87.353z");
}

.l41aal3yz {
  d: path("M52.413 0h17.474v17.474H52.413z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.ln8tw2m_b {
  d: path("M52.413 52.413h17.474v17.474H52.413z");
}

.m2po0-b0v {
  d: path("M17.474 34.94h17.474v17.474H17.474z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.mpy9f5b2d {
  d: path("M17.474 87.353h17.474v17.466H17.474z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.new7msb2m {
  d: path("M87.353 122.286h17.474v17.474H87.353z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.nvm4d4bpq {
  d: path("M87.353 17.474h17.474v17.474H87.353z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.nz3yshbaz {
  d: path("M104.82 104.82h17.466v17.474H104.82z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.oofya7b0d {
  d: path("M34.94 69.88h17.474v17.474H34.94z");
}

.pcgfq-bcr {
  d: path("M87.353 52.413h17.474v17.474H87.353z");
}

.ppmamzb2d {
  d: path("M104.82 69.88h17.466v17.474H104.82z");
}

.q_s9d9jzm {
  stop-color: var(--svg-color--0074bf, #0074bf);
}

.q1d3p4xoa {
  d: path("M34.94 17.474h17.474v17.474H34.94z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.qf__hrb8u {
  d: path("M122.286 69.88h17.474v17.474h-17.474z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.qn8v09blj {
  d: path("M69.88 0h17.474v17.474H69.88z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.r8c_1vrgm {
  d: path("M52.413 17.474h17.474v17.474H52.413z");
}

.rigymjb7t {
  d: path("M52.413 104.82h17.474v17.474H52.413z");
}

.rvvk-f7ql {
  d: path("M17.474 17.474h17.474v17.474H17.474z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.rwjoyfboh {
  d: path("M34.94 34.94h17.474v17.474H34.94z");
}

.sum-ilzts {
  d: path("M69.88 122.286h17.474v17.474H69.88z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.szz2accgg {
  d: path("M69.88 69.88h17.474v17.474H69.88z");
}

.tpsk40b7o {
  d: path("M0 34.94h17.474v17.474H0z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v92fwbbau {
  d: path("M122.286 87.353h17.474v17.466h-17.474z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vkba8_b9o {
  d: path("M0 87.353h17.474v17.466H0z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w1h3dwbae {
  d: path("M69.88 34.94h17.474v17.474H69.88z");
}

.y_mb9yb7i {
  d: path("M69.88 52.413h17.474v17.474H69.88z");
}

.zhnl9huup {
  d: path("M87.353 87.353h17.474v17.466H87.353z");
}

.zxxaadbzd {
  d: path("M34.94 52.413h17.474v17.474H34.94z");
}

</style>
