<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNMZ4sc)"><path fill="url(#i8xwWLc)" class="jjm8hac9p"/><path fill="url(#iyy5Lgc)" class="jjm8hac9p"/><path fill="url(#iOlg6jb)" class="jjm8hac9p"/></g><path fill="url(#igpQMpc)" class="iwq-nqblp"/><path fill="url(#ixd3V2d)" class="iwq-nqblp"/><path fill="url(#iiiydwe)" class="z4bv6vs0i"/><path fill="url(#icyTxhb)" class="z4bv6vs0i"/><g filter="url(#i4MOdPz)"><path fill="url(#iXqBXme)" class="a_a5qpb0b"/></g><path fill="url(#ieT5RAd)" class="eor89sb8h"/><path fill="url(#ishvnle)" class="eor89sb8h"/><path fill="url(#iQoF0fd)" class="eor89sb8h"/><path fill="url(#ioROuVc)" class="l3ndxrb2h"/><path fill="url(#iAnXadW)" class="l3ndxrb2h"/><path fill="url(#iN3npsf)" class="fr9dn7bng"/><path fill="url(#iwJnB7b)" class="fr9dn7bng"/><path fill="url(#ipsgsBd)" class="fr9dn7bng"/><g filter="url(#ihkcnmc)"><path fill="url(#itpuv2c)" class="we1pucrpm"/></g><g filter="url(#ixnZAVb)"><path fill="url(#i65VOeb)" class="t1-uzq7hg"/><path fill="url(#izgOa7c)" class="t1-uzq7hg"/></g><path fill="url(#icd7Dcc)" class="i3_dacc7f"/><path fill="url(#iN9D1Qc)" class="i3_dacc7f"/><path fill="url(#ihLKS0b)" class="kp6v68bgu"/><g filter="url(#ijiUcQb)"><path fill="url(#iXjgmne)" class="nqbc9yldy"/></g><defs><linearGradient id="i8xwWLc" x1="23.905" x2="23.905" y1="11.076" y2="27.259" gradientUnits="userSpaceOnUse"><stop class="chtz1da4s"/><stop offset="1" class="b1mvggbxq"/></linearGradient><linearGradient id="iyy5Lgc" x1="30.416" x2="29.089" y1="13.457" y2="13.646" gradientUnits="userSpaceOnUse"><stop offset=".014" class="mkilliegj"/><stop offset="1" class="l2-c3ac4j"/></linearGradient><linearGradient id="igpQMpc" x1="16.638" x2="30.189" y1="28.887" y2="28.887" gradientUnits="userSpaceOnUse"><stop class="i6-27kmxh"/><stop offset="1" class="u3fbxiccu"/><stop offset="1" class="ak6cm6bhy"/></linearGradient><linearGradient id="ixd3V2d" x1="23.063" x2="23.063" y1="27.756" y2="28.713" gradientUnits="userSpaceOnUse"><stop class="yow419b2s"/><stop offset="1" class="mldv6wybf"/></linearGradient><linearGradient id="iiiydwe" x1="15.615" x2="17.205" y1="21.013" y2="21.021" gradientUnits="userSpaceOnUse"><stop class="kbme0vjyw"/><stop offset="1" class="q4vxleboq"/></linearGradient><linearGradient id="iXqBXme" x1="16.442" x2="30.311" y1="29.257" y2="29.235" gradientUnits="userSpaceOnUse"><stop class="udq_fgbpb"/><stop offset="1" class="tobe2mb2f"/></linearGradient><linearGradient id="ieT5RAd" x1="16.843" x2="16.843" y1="7.036" y2="23.219" gradientUnits="userSpaceOnUse"><stop class="oozzqybsj"/><stop offset="1" class="ekao3b3br"/></linearGradient><linearGradient id="ishvnle" x1="24.388" x2="22.561" y1="9.317" y2="9.382" gradientUnits="userSpaceOnUse"><stop offset=".409" class="hnu1h1bpz"/><stop offset="1" class="v0v51qk4r"/></linearGradient><linearGradient id="ioROuVc" x1="9.575" x2="23.127" y1="24.848" y2="24.848" gradientUnits="userSpaceOnUse"><stop class="i6-27kmxh"/><stop offset="1" class="u3fbxiccu"/><stop offset="1" class="ak6cm6bhy"/></linearGradient><linearGradient id="iAnXadW" x1="16" x2="16" y1="23.717" y2="24.674" gradientUnits="userSpaceOnUse"><stop class="yow419b2s"/><stop offset="1" class="mldv6wybf"/></linearGradient><linearGradient id="iN3npsf" x1="8.553" x2="10.437" y1="16.974" y2="16.974" gradientUnits="userSpaceOnUse"><stop class="ytk_ftgeq"/><stop offset="1" class="nv1w8sl_w"/></linearGradient><linearGradient id="itpuv2c" x1="9.379" x2="23.249" y1="25.218" y2="25.196" gradientUnits="userSpaceOnUse"><stop class="s9_n5_iqg"/><stop offset="1" class="ymjuykbnp"/></linearGradient><linearGradient id="i65VOeb" x1="10.613" x2="10.613" y1="4" y2="20.179" gradientUnits="userSpaceOnUse"><stop class="x_23hmbuj"/><stop offset="1" class="c-3_5vb4p"/></linearGradient><linearGradient id="izgOa7c" x1="17.122" x2="15.795" y1="6.38" y2="6.57" gradientUnits="userSpaceOnUse"><stop offset=".014" class="roi4527px"/><stop offset="1" class="kz_tr5biv"/></linearGradient><linearGradient id="icd7Dcc" x1="3.347" x2="16.895" y1="21.807" y2="21.807" gradientUnits="userSpaceOnUse"><stop class="i6-27kmxh"/><stop offset="1" class="u3fbxiccu"/><stop offset="1" class="ak6cm6bhy"/></linearGradient><linearGradient id="iN9D1Qc" x1="9.77" x2="9.77" y1="20.676" y2="21.633" gradientUnits="userSpaceOnUse"><stop class="yow419b2s"/><stop offset="1" class="mldv6wybf"/></linearGradient><linearGradient id="ihLKS0b" x1="2.325" x2="3.914" y1="13.935" y2="13.943" gradientUnits="userSpaceOnUse"><stop class="ywma89b_b"/><stop offset="1" class="hyksm8u_q"/></linearGradient><linearGradient id="iXjgmne" x1="3.151" x2="17.017" y1="22.177" y2="22.155" gradientUnits="userSpaceOnUse"><stop class="of7n-miws"/><stop offset="1" class="hqtrfibic"/></linearGradient><radialGradient id="iOlg6jb" cx="0" cy="0" r="1" gradientTransform="matrix(6.0275 0 0 5.11709 17.414 27.259)" gradientUnits="userSpaceOnUse"><stop class="pn21r9bzc"/><stop offset="1" class="eh97cdcqo"/></radialGradient><radialGradient id="icyTxhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.21875 -2.46036 0 17.5 25.625)" gradientUnits="userSpaceOnUse"><stop class="rprqwac5u"/><stop offset="1" class="nwbnnobet"/></radialGradient><radialGradient id="iQoF0fd" cx="0" cy="0" r="1" gradientTransform="matrix(6.75 0 0 5.4622 11.008 22.813)" gradientUnits="userSpaceOnUse"><stop class="kegz0_bhx"/><stop offset="1" class="x2e7x846d"/></radialGradient><radialGradient id="iwJnB7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.4809 .78956 0 8.683 23.673)" gradientUnits="userSpaceOnUse"><stop class="m2ljdrbyw"/><stop offset="1" class="fmxcc54ex"/></radialGradient><radialGradient id="ipsgsBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28125 -1.86661 0 10.434 22.345)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="l6vxek_tw"/><stop offset="1" class="nh0plkx4p"/></radialGradient><filter id="iNMZ4sc" width="13.739" height="17.024" x="16.573" y="11.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.807843 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20855"/></filter><filter id="i4MOdPz" width="14.834" height="2.797" x="15.477" y="27.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.388235 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20855"/></filter><filter id="ihkcnmc" width="14.834" height="2.797" x="8.414" y="23.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.192157 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20855"/></filter><filter id="ixnZAVb" width="13.735" height="16.279" x="3.282" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.858824 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20855"/></filter><filter id="ijiUcQb" width="14.83" height="2.796" x="2.187" y="20.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.435294 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20855"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:books" /></template>
<style>
.a_a5qpb0b {
  d: path("M16.488 27.259a1.01 1.01 0 0 0-1.011 1.011v.674c0 .559.453 1.012 1.011 1.012h13.087c.44 0 .736-.226.736-.675H16.825a.674.674 0 0 1 0-1.348h13.486v-.674z");
}

.ak6cm6bhy {
  stop-color: var(--svg-color--e3d3f2, #E3D3F2);
}

.b1mvggbxq {
  stop-color: var(--svg-color--39adf1, #39ADF1);
}

.c-3_5vb4p {
  stop-color: var(--svg-color--74d891, #74D891);
}

.chtz1da4s {
  stop-color: var(--svg-color--56d1f3, #56D1F3);
}

.eh97cdcqo {
  stop-color: var(--svg-color--2e7cd5, #2E7CD5);
  stop-opacity: 0;
}

.ekao3b3br {
  stop-color: var(--svg-color--e0334c, #E0334C);
}

.eor89sb8h {
  d: path("M10.437 7.036H21.9c.745 0 1.349.604 1.349 1.349v14.834H10.437z");
}

.fmxcc54ex {
  stop-color: var(--svg-color--9b3f51, #9B3F51);
  stop-opacity: 0;
}

.fr9dn7bng {
  d: path("M9.426 7.036c-.559 0-1.012.453-1.012 1.012v16.52h.675c0-.373.301-.675.674-.675h.674V7.036z");
}

.ft5dv1b6b {
  fill: none;
}

.hnu1h1bpz {
  stop-color: var(--svg-color--f76594, #F76594);
}

.hqtrfibic {
  stop-color: var(--svg-color--2e7172, #2E7172);
}

.hyksm8u_q {
  stop-color: var(--svg-color--429b5b, #429B5B);
}

.i3_dacc7f {
  d: path("M2.524 20.516h14.493V22.2h-.337l-.337.337H2.523z");
}

.i6-27kmxh {
  stop-color: var(--svg-color--d5bceb, #D5BCEB);
}

.iwq-nqblp {
  d: path("M15.814 27.596h14.497v1.685h-.337l-.337.338H15.814z");
}

.jjm8hac9p {
  d: path("M16.573 11.076h12.39c.744 0 1.348.604 1.348 1.348V28H16.573z");
}

.kbme0vjyw {
  stop-color: var(--svg-color--44a3d2, #44A3D2);
}

.kegz0_bhx {
  stop-color: var(--svg-color--b21940, #B21940);
}

.kp6v68bgu {
  d: path("M3.198 4a1.01 1.01 0 0 0-1.011 1.011v16.516h.674c0-.373.302-.674.674-.674h.674V4z");
}

.kz_tr5biv {
  stop-color: var(--svg-color--b0ed5b, #B0ED5B);
  stop-opacity: 0;
}

.l2-c3ac4j {
  stop-color: var(--svg-color--60deff, #60DEFF);
  stop-opacity: 0;
}

.l3ndxrb2h {
  d: path("M8.751 23.556H23.25v1.686h-.337l-.338.337H8.751z");
}

.l6vxek_tw {
  stop-color: var(--svg-color--8f163a, #8F163A);
}

.m2ljdrbyw {
  stop-color: var(--svg-color--9b3f51, #9B3F51);
}

.mkilliegj {
  stop-color: var(--svg-color--7fecff, #7FECFF);
}

.mldv6wybf {
  stop-color: var(--svg-color--c5b1d6, #C5B1D6);
  stop-opacity: 0;
}

.nh0plkx4p {
  stop-color: var(--svg-color--8f163a, #8F163A);
  stop-opacity: 0;
}

.nqbc9yldy {
  d: path("M3.198 20.179a1.01 1.01 0 0 0-1.011 1.01v.675a1.01 1.01 0 0 0 1.01 1.011h13.084c.44 0 .736-.226.736-.674H3.535a.674.674 0 1 1 0-1.348h13.482v-.674z");
}

.nv1w8sl_w {
  stop-color: var(--svg-color--aa2c4d, #AA2C4D);
}

.nwbnnobet {
  stop-color: var(--svg-color--3163ae, #3163AE);
  stop-opacity: 0;
}

.of7n-miws {
  stop-color: var(--svg-color--2e7671, #2E7671);
}

.oozzqybsj {
  stop-color: var(--svg-color--e13074, #E13074);
}

.pn21r9bzc {
  stop-color: var(--svg-color--2e7cd5, #2E7CD5);
}

.q4vxleboq {
  stop-color: var(--svg-color--3c8fcc, #3C8FCC);
}

.roi4527px {
  stop-color: var(--svg-color--c0fa7c, #C0FA7C);
}

.rprqwac5u {
  stop-color: var(--svg-color--3163ae, #3163AE);
}

.s9_n5_iqg {
  stop-color: var(--svg-color--ab1f5c, #AB1F5C);
}

.t1-uzq7hg {
  d: path("M3.282 4h12.387c.744 0 1.348.604 1.348 1.348v14.83H3.282z");
}

.tobe2mb2f {
  stop-color: var(--svg-color--3666c3, #3666C3);
}

.u3fbxiccu {
  stop-color: var(--svg-color--dccced, #DCCCED);
}

.udq_fgbpb {
  stop-color: var(--svg-color--3769c5, #3769C5);
}

.v0v51qk4r {
  stop-color: var(--svg-color--fa6295, #FA6295);
  stop-opacity: 0;
}

.we1pucrpm {
  d: path("M9.426 23.22a1.01 1.01 0 0 0-1.012 1.01v.675c0 .558.453 1.011 1.012 1.011h13.086c.44 0 .737-.225.737-.674H9.763a.674.674 0 0 1 0-1.349h13.486v-.674z");
}

.x_23hmbuj {
  stop-color: var(--svg-color--a6e051, #A6E051);
}

.x2e7x846d {
  stop-color: var(--svg-color--b21940, #B21940);
  stop-opacity: 0;
}

.ymjuykbnp {
  stop-color: var(--svg-color--a51e5a, #A51E5A);
}

.yow419b2s {
  stop-color: var(--svg-color--9f84ae, #9F84AE);
}

.ytk_ftgeq {
  stop-color: var(--svg-color--9a3e4f, #9A3E4F);
}

.ywma89b_b {
  stop-color: var(--svg-color--63b33b, #63B33B);
}

.z4bv6vs0i {
  d: path("M16.488 11.076a1.01 1.01 0 0 0-1.011 1.011v16.52h.674c0-.372.302-.674.674-.674h.675V11.076z");
}

</style>
