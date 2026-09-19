<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWJRREd)" class="w8wf901wc"/><path fill="url(#itlNzJb)" class="w8wf901wc"/><path class="w9__c2b-f"/><path fill="url(#iIWrz0b)" class="gj465513n"/><path fill="url(#iEtjZre)" class="gj465513n"/><path fill="url(#ioOW9vb)" class="gj465513n"/><path class="o-e-ksfig"/><g filter="url(#iAPOake)"><path class="og9hf7rkm"/></g><g filter="url(#i0JJr2i)"><path class="mnu6a4c8q"/></g><g filter="url(#iI1x8cS)"><path class="lny826jdg"/></g><g filter="url(#ieG4Nce)"><path class="uk8pdtpxx"/></g><g filter="url(#iV5EYxd)"><path class="b6s_lhiqk"/></g><g filter="url(#i0dAPMb)"><path class="up2xjwpps"/></g><g filter="url(#idTdNWb)"><path class="b0hsljb_y"/></g><g filter="url(#iCh0ezb)"><path class="wqpi35bdj"/></g><path fill="url(#iNVYFwe)" class="scijdqu8b"/><path fill="url(#iOSlt5D)" class="hyo-9fbxe"/><path fill="url(#iMhW1pG)" class="y4-4vz5uu"/><g filter="url(#i1KG15O)"><path class="i2pnegbfp"/></g><path fill="url(#iZH9Y3w)" class="y4-4vz5uu"/><path fill="url(#ibFy3xb)" class="ojuzoobft"/><g filter="url(#iN3GRje)"><path class="ir3izvp8q"/></g><path fill="url(#iK0x4ve)" class="e5gi4pbxl"/><path fill="url(#i34N6Lb)" class="chfqm8bpm"/><path fill="url(#imyTbHc)" class="ac-qbivmb"/><path fill="url(#i5OQUOe)" class="o2j2cjb3c"/><path fill="url(#iy6Bzlb)" class="a5078-b9a"/><path fill="url(#i25SDkp)" class="bpmznf23e"/><defs><radialGradient id="itlNzJb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.06252 6.25 -15.10068 -9.8155 27.5 14.813)" gradientUnits="userSpaceOnUse"><stop class="ud59sy5kv"/><stop offset="1" class="wfzkmfozg"/></radialGradient><radialGradient id="iIWrz0b" cx="0" cy="0" r="1" gradientTransform="rotate(98.409 1.112 13.937)scale(14.5312)" gradientUnits="userSpaceOnUse"><stop class="kjp7-fb0v"/><stop offset=".774" class="e4-wlnb0z"/><stop offset=".863" class="s_kc8jb8v"/><stop offset=".913" class="hr6y_ubcm"/></radialGradient><radialGradient id="iEtjZre" cx="0" cy="0" r="1" gradientTransform="rotate(66.819 -4.17 17.64)scale(14.9249)" gradientUnits="userSpaceOnUse"><stop class="xmfuj-m0l"/><stop offset=".823" class="b41qufb7k"/><stop offset=".927" class="z7kgqtb3n"/></radialGradient><radialGradient id="ioOW9vb" cx="0" cy="0" r="1" gradientTransform="rotate(90 .001 14.531)scale(15.595)" gradientUnits="userSpaceOnUse"><stop class="gx1_adb-h"/><stop offset="1" class="wyvl6sb2i"/></radialGradient><radialGradient id="iNVYFwe" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 9.626 6.193)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="iOSlt5D" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 2.5 11.036)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="iZH9Y3w" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 7.59 4.587)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="ibFy3xb" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 4.53 12.641)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="iK0x4ve" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 5.007 4.44)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="i34N6Lb" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 7.12 12.788)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="imyTbHc" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 2.804 5.798)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="i5OQUOe" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 9.322 11.426)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="iy6Bzlb" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 1.78 8.178)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="i25SDkp" cx="0" cy="0" r="1" gradientTransform="rotate(158.394 10.345 9.05)scale(1.69738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lw5yepbnd"/><stop offset=".368" class="ggdjj6bgt"/><stop offset=".714" class="mv4zbybov"/><stop offset="1" class="vuad6pb7r"/></radialGradient><filter id="iAPOake" width="3.96" height="3.96" x="18.172" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="i0JJr2i" width="3.96" height="3.96" x="20.63" y="11.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="iI1x8cS" width="3.96" height="3.96" x="19.462" y="16.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="ieG4Nce" width="3.96" height="3.96" x="15.7" y="20.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="iV5EYxd" width="3.96" height="3.96" x="10.512" y="21.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="i0dAPMb" width="3.96" height="3.96" x="6.032" y="18.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="idTdNWb" width="3.96" height="3.96" x="3.501" y="13.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="iCh0ezb" width="3.96" height="3.96" x="4.672" y="8.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="i1KG15O" width="3.96" height="3.96" x="13.533" y="4.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><filter id="iN3GRje" width="3.96" height="3.96" x="8.472" y="5.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30155" stdDeviation=".5"/></filter><linearGradient id="iWJRREd" x1="29.563" x2="14.875" y1="13.75" y2="31.563" gradientUnits="userSpaceOnUse"><stop class="m17ikkbye"/><stop offset=".469" class="v4j39jvte"/><stop offset=".733" class="hg5un_08w"/><stop offset="1" class="wv1d7pcyv"/></linearGradient><linearGradient id="iMhW1pG" x1="16.596" x2="15.206" y1="5.395" y2="6.786" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:kiwi-fruit" /></template>
<style>
.a5078-b9a {
  d: path("M6.052 16.19a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.ac-qbivmb {
  d: path("M7.152 11.22a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.aoo6bub-i {
  stop-color: var(--svg-color--513468, #513468);
}

.b0hsljb_y {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M5.481 16.49a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.b41qufb7k {
  stop-color: var(--svg-color--d6f76c, #D6F76C);
  stop-opacity: 0;
}

.b6s_lhiqk {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M12.493 23.963a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.bpmznf23e {
  d: path("M22.902 14.72a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.chfqm8bpm {
  d: path("M18.053 23.12a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.e4-wlnb0z {
  stop-color: var(--svg-color--a7d335, #A7D335);
  stop-opacity: 0.316;
}

.e5gi4pbxl {
  d: path("M10.903 7.79a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.ft5dv1b6b {
  fill: none;
}

.ggdjj6bgt {
  stop-color: var(--svg-color--533e60, #533E60);
}

.gj465513n {
  d: path("M14.532 27.06c6.92 0 12.53-5.61 12.53-12.53S21.452 2 14.532 2S2.002 7.61 2.002 14.53s5.61 12.53 12.53 12.53");
}

.gx1_adb-h {
  stop-color: var(--svg-color--b4e637, #B4E637);
}

.hg5un_08w {
  stop-color: var(--svg-color--8b5863, #8B5863);
}

.hr6y_ubcm {
  stop-color: var(--svg-color--7fa91c, #7FA91C);
}

.hyo-9fbxe {
  d: path("M8.492 21.44a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.i2pnegbfp {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M15.513 7.291a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.ir3izvp8q {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M10.452 8.069a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.kjp7-fb0v {
  stop-color: var(--svg-color--aedd38, #AEDD38);
  stop-opacity: 0;
}

.lny826jdg {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M21.442 19.68a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.lw5yepbnd {
  stop-color: var(--svg-color--7b6d83, #7B6D83);
}

.m17ikkbye {
  stop-color: var(--svg-color--a76051, #A76051);
}

.mnu6a4c8q {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M22.61 14.72a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.mv4zbybov {
  stop-color: var(--svg-color--584d5d, #584D5D);
}

.o-e-ksfig {
  fill: var(--svg-color--e5f892, #E5F892);
  d: path("M14.533 20.15a5.62 5.62 0 1 0 0-11.24a5.62 5.62 0 0 0 0 11.24");
}

.o2j2cjb3c {
  d: path("M21.803 19.68a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.og9hf7rkm {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M20.153 9.75a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.ojuzoobft {
  d: path("M13.003 23.79a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.s_kc8jb8v {
  stop-color: var(--svg-color--98bd30, #98BD30);
}

.scijdqu8b {
  d: path("M20.462 9.47a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.ud59sy5kv {
  stop-color: var(--svg-color--d29280, #D29280);
}

.uk8pdtpxx {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M17.68 23.4a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.up2xjwpps {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M8.012 21.65a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.v4j39jvte {
  stop-color: var(--svg-color--9d5952, #9D5952);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w8wf901wc {
  d: path("m26.333 8.62l-2.95-2.95l-17.71 17.71l2.95 2.95c4.89 4.89 12.82 4.89 17.71 0s4.89-12.82 0-17.71");
}

.w9__c2b-f {
  fill: var(--svg-color--abd837, #ABD837);
  d: path("M14.532 27.06c6.92 0 12.53-5.61 12.53-12.53S21.452 2 14.532 2S2.002 7.61 2.002 14.53s5.61 12.53 12.53 12.53");
}

.wfzkmfozg {
  stop-color: var(--svg-color--d2927f, #D2927F);
  stop-opacity: 0;
}

.wqpi35bdj {
  fill: var(--svg-color--7bae29, #7BAE29);
  d: path("M6.652 11.459a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.wv1d7pcyv {
  stop-color: var(--svg-color--67405c, #67405C);
}

.wyvl6sb2i {
  stop-color: var(--svg-color--b1e138, #B1E138);
  stop-opacity: 0;
}

.xmfuj-m0l {
  stop-color: var(--svg-color--aede37, #AEDE37);
  stop-opacity: 0;
}

.y4-4vz5uu {
  d: path("M15.943 7.12a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.z7kgqtb3n {
  stop-color: var(--svg-color--e4ff7e, #E4FF7E);
}

</style>
