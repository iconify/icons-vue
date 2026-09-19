<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBCJM0b)" class="aok5d6l7v"/><path fill="url(#iMrLJ3g)" class="aok5d6l7v"/><path fill="url(#iKV9Dgc)" class="aok5d6l7v"/><g filter="url(#ijfvJ1c)"><path fill="url(#i0Swvld)" class="wti-8mbin"/></g><g filter="url(#i35OgQc)"><path fill="url(#irF1Y5c)" class="eg70cjbwl"/></g><g filter="url(#i0oCEhd)"><path fill="url(#iFdm0Nd)" class="fujm0dbwh"/></g><g filter="url(#izXgjse)"><path fill="url(#iv80Xnd)" class="vds0v4bui"/></g><g filter="url(#iUYtjZb)"><path fill="url(#iYWhevz)" class="va_efdced"/></g><g filter="url(#iIRe1Kb)"><path fill="url(#iS0UVYc)" class="nl020acvi"/></g><path fill="url(#irKKzfe)" class="nl020acvi"/><g filter="url(#iX1IB7r)"><path fill="url(#itcnR0d)" class="sksco_z5t"/></g><g filter="url(#iT4y1fe)"><path fill="url(#iPe9mKb)" class="n_xtddl0g"/></g><g filter="url(#imGb63d)"><path fill="url(#iJpGAKd)" class="u1m_dgbne"/></g><g filter="url(#iZBZ5zd)"><path fill="url(#i5AygKd)" class="amscxtbvo"/></g><g filter="url(#i6gldID)"><path fill="url(#iIuvKge)" class="yc4dp6ktk"/></g><g filter="url(#i8ICPVc)"><path fill="url(#iaxKeQd)" class="yrmbk9z9s"/></g><g filter="url(#iCO4pgc)"><path fill="url(#iLzjyWb)" class="z89ft_hbc"/></g><g filter="url(#itHa6gb)"><path fill="url(#iZKIPAz)" class="brzhx8b_s"/></g><defs><linearGradient id="i0Swvld" x1="22.571" x2="24.241" y1="26.233" y2="24.802" gradientUnits="userSpaceOnUse"><stop class="e8ic6pqlj"/><stop offset="1" class="vsv10abek"/><stop offset="1" class="vsv10abek"/></linearGradient><linearGradient id="irF1Y5c" x1="16.418" x2="19.18" y1="24.597" y2="21.288" gradientUnits="userSpaceOnUse"><stop class="e8ic6pqlj"/><stop offset="1" class="vsv10abek"/><stop offset="1" class="vsv10abek"/></linearGradient><linearGradient id="iFdm0Nd" x1="14.381" x2="15.496" y1="19.493" y2="18.538" gradientUnits="userSpaceOnUse"><stop class="e8ic6pqlj"/><stop offset="1" class="vsv10abek"/><stop offset="1" class="vsv10abek"/></linearGradient><linearGradient id="iv80Xnd" x1="12.195" x2="13.008" y1="19.486" y2="19.138" gradientUnits="userSpaceOnUse"><stop class="e8ic6pqlj"/><stop offset="1" class="vsv10abek"/><stop offset="1" class="vsv10abek"/></linearGradient><linearGradient id="iYWhevz" x1="6.35" x2="17.564" y1="17.147" y2="6.692" gradientUnits="userSpaceOnUse"><stop class="e8ic6pqlj"/><stop offset="1" class="vsv10abek"/><stop offset="1" class="vsv10abek"/></linearGradient><linearGradient id="irKKzfe" x1="8.484" x2="2.797" y1="12.187" y2="19" gradientUnits="userSpaceOnUse"><stop class="cx7vypv3j"/><stop offset=".897" class="rfhww-btk"/></linearGradient><linearGradient id="itcnR0d" x1="18.645" x2="20.259" y1="19.143" y2="17.759" gradientUnits="userSpaceOnUse"><stop class="e8ic6pqlj"/><stop offset="1" class="vsv10abek"/><stop offset="1" class="vsv10abek"/></linearGradient><linearGradient id="iPe9mKb" x1="20.371" x2="18.672" y1="17.297" y2="19.719" gradientUnits="userSpaceOnUse"><stop class="ir_m84bhm"/><stop offset="1" class="c2dzpytss"/></linearGradient><linearGradient id="iJpGAKd" x1="15.61" x2="14.475" y1="18.212" y2="19.829" gradientUnits="userSpaceOnUse"><stop class="nkhi-wbsi"/><stop offset="1" class="yo6jqob0d"/></linearGradient><linearGradient id="i5AygKd" x1="24.953" x2="22.344" y1="24.109" y2="26.828" gradientUnits="userSpaceOnUse"><stop class="veugs_box"/><stop offset="1" class="b7japqb_y"/></linearGradient><linearGradient id="iIuvKge" x1="12.861" x2="11.726" y1="18.21" y2="19.019" gradientUnits="userSpaceOnUse"><stop class="a5q7jmesh"/><stop offset="1" class="ejtyaobpv"/></linearGradient><linearGradient id="iaxKeQd" x1="17.637" x2="19.307" y1="13.186" y2="11.755" gradientUnits="userSpaceOnUse"><stop class="e8ic6pqlj"/><stop offset="1" class="vsv10abek"/><stop offset="1" class="vsv10abek"/></linearGradient><linearGradient id="iLzjyWb" x1="19.864" x2="17.763" y1="11.303" y2="14.478" gradientUnits="userSpaceOnUse"><stop class="unntgpbby"/><stop offset="1" class="e2nuprbwr"/></linearGradient><linearGradient id="iZKIPAz" x1="20.984" x2="19.374" y1="21.01" y2="25.923" gradientUnits="userSpaceOnUse"><stop class="elk9w0--h"/><stop offset="1" class="vxo1-x6sa"/></linearGradient><filter id="ijfvJ1c" width="3.31" height="3.31" x="21.835" y="23.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4776" stdDeviation=".075"/></filter><filter id="i35OgQc" width="7.29" height="5.3" x="14.908" y="20.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4776" stdDeviation=".075"/></filter><filter id="i0oCEhd" width="2.31" height="2.31" x="13.84" y="17.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4776" stdDeviation=".075"/></filter><filter id="izXgjse" width="1.3" height="2.3" x="11.85" y="17.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4776" stdDeviation=".075"/></filter><filter id="iUYtjZb" width="22.086" height="20.324" x="1.959" y="2.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4776" stdDeviation=".075"/></filter><filter id="iIRe1Kb" width="22.19" height="20.412" x="2.009" y="2.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.588235 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 1 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4776" result="effect2_innerShadow_18_4776"/></filter><filter id="iX1IB7r" width="3.211" height="3.211" x="17.928" y="16.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4776" stdDeviation=".075"/></filter><filter id="iT4y1fe" width="3.11" height="3.11" x="18.109" y="16.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.992157 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.494118 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4776" result="effect2_innerShadow_18_4776"/></filter><filter id="imGb63d" width="2.21" height="2.11" x="13.999" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.992157 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.494118 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4776" result="effect2_innerShadow_18_4776"/></filter><filter id="iZBZ5zd" width="3.11" height="3.11" x="22.099" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.992157 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.466667 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4776" result="effect2_innerShadow_18_4776"/></filter><filter id="i6gldID" width="1.1" height="2.1" x="12.059" y="17.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.992157 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.494118 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4776" result="effect2_innerShadow_18_4776"/></filter><filter id="i8ICPVc" width="3.31" height="3.31" x="16.901" y="10.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4776" stdDeviation=".075"/></filter><filter id="iCO4pgc" width="3.21" height="3.11" x="16.999" y="11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.588235 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 1 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4776" result="effect2_innerShadow_18_4776"/></filter><filter id="itHa6gb" width="7.09" height="5.2" x="15.109" y="20.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.992157 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.439216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4776" result="effect2_innerShadow_18_4776"/></filter><radialGradient id="iBCJM0b" cx="0" cy="0" r="1" gradientTransform="matrix(-14.12225 19.0552 -25.89881 -19.1942 25.763 10.477)" gradientUnits="userSpaceOnUse"><stop class="erev8bxle"/><stop offset="1" class="ds15j6b6n"/></radialGradient><radialGradient id="iMrLJ3g" cx="0" cy="0" r="1" gradientTransform="matrix(-19.2977 17.52941 -23.20134 -25.54178 25.864 9.62)" gradientUnits="userSpaceOnUse"><stop offset=".494" class="at32sf_ds"/><stop offset="1" class="xf7ha3u1l"/></radialGradient><radialGradient id="iKV9Dgc" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.02 15.09)scale(16.7059)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="g1zentbmm"/><stop offset="1" class="pa2kfx6lo"/></radialGradient><radialGradient id="iS0UVYc" cx="0" cy="0" r="1" gradientTransform="matrix(-17.50009 9.4374 -9.521 -17.65509 20.86 6.437)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="y2mln9l1z"/><stop offset="1" class="rfhww-btk"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:globe-showing-asia-australia" /></template>
<style>
.a5q7jmesh {
  stop-color: var(--svg-color--59c897, #59C897);
}

.amscxtbvo {
  d: path("m23.9 24.21l-1.59 1.59c-.13.13-.21.31-.21.5c0 .39.32.71.71.71c.19 0 .37-.07.5-.21l1.59-1.59c.13-.13.21-.31.21-.5c0-.39-.32-.71-.71-.71c-.19 0-.37.07-.5.21");
}

.aok5d6l7v {
  d: path("M16.11 30c7.731 0 14-6.268 14-14s-6.269-14-14-14c-7.733 0-14 6.268-14 14s6.267 14 14 14");
}

.at32sf_ds {
  stop-color: var(--svg-color--465dc2, #465DC2);
  stop-opacity: 0;
}

.b7japqb_y {
  stop-color: var(--svg-color--4daa8c, #4DAA8C);
}

.brzhx8b_s {
  d: path("M15.11 22.74v1.23c0 .57.46 1.03 1.03 1.03h1.53c.27 0 .53.11.72.3l.41.41c.19.19.45.3.72.3h.94c.39 0 .75-.22.92-.57l.61-1.21c.07-.14.11-.3.11-.46v-1.12c0-.39-.22-.75-.57-.92l-1.21-.61c-.14-.07-.3-.11-.46-.11h-1.59c-.11 0-.22.02-.33.05l-2.14.71c-.41.14-.69.53-.69.97");
}

.c2dzpytss {
  stop-color: var(--svg-color--5ace9d, #5ACE9D);
}

.cx7vypv3j {
  stop-color: var(--svg-color--478b68, #478B68);
  stop-opacity: 0;
}

.ds15j6b6n {
  stop-color: var(--svg-color--3488ef, #3488EF);
}

.e2nuprbwr {
  stop-color: var(--svg-color--65e3a4, #65E3A4);
}

.e8ic6pqlj {
  stop-color: var(--svg-color--235897, #235897);
}

.eg70cjbwl {
  d: path("M15.058 22.826v1.23c0 .57.46 1.03 1.03 1.03h1.53c.27 0 .53.11.72.3l.41.41c.19.19.45.3.72.3h.94c.39 0 .75-.22.92-.57l.61-1.21c.07-.14.11-.3.11-.46v-1.12c0-.39-.22-.75-.57-.92l-1.21-.61c-.14-.07-.3-.11-.46-.11h-1.59c-.11 0-.22.02-.33.05l-2.14.71c-.41.14-.69.53-.69.97");
}

.ejtyaobpv {
  stop-color: var(--svg-color--50b892, #50B892);
}

.elk9w0--h {
  stop-color: var(--svg-color--53c899, #53C899);
}

.erev8bxle {
  stop-color: var(--svg-color--67ddff, #67DDFF);
}

.ft5dv1b6b {
  fill: none;
}

.fujm0dbwh {
  d: path("M15.47 18.086h-.95c-.29 0-.53.24-.53.53v.95c0 .29.24.53.53.53h.95c.29 0 .53-.24.53-.53v-.95c0-.29-.24-.53-.53-.53");
}

.g1zentbmm {
  stop-color: var(--svg-color--606ac7, #606AC7);
  stop-opacity: 0;
}

.ir_m84bhm {
  stop-color: var(--svg-color--62dca3, #62DCA3);
}

.n_xtddl0g {
  d: path("M18.11 17.71v.642c0 .428.093.812.71 1.039l1.16.539c.09.04.19.06.29.06h.14c.39 0 .71-.32.71-.71c0-.19-.07-.37-.21-.5l-1.59-1.59a.7.7 0 0 0-.5-.21c-.4.02-.71.34-.71.73");
}

.nkhi-wbsi {
  stop-color: var(--svg-color--52bf93, #52BF93);
}

.nl020acvi {
  d: path("m4.07 23.15l.59-.66c.28-.31.44-.72.44-1.14v-1.76c0-.33.26-.59.59-.59c.23 0 .41-.18.41-.41V18c0-.55-.45-1-1-1s-1-.45-1-1v-.51c0-.27.22-.49.49-.49c.28 0 .52.23.5.51c0 .27.22.49.49.49h.6c.51 0 .92-.41.92-.92v-.58c0-.28.22-.5.5-.5s.5.22.5.5v.95c0 .31.25.55.55.55c.25 0 .45.2.45.45v.93a.623.623 0 0 0 1.18.28l1.62-3.25a.76.76 0 0 1 .67-.41c.32 0 .6.21.71.51l.7 2.09a.58.58 0 0 0 1.13-.18V14.5c0-.28.22-.5.5-.5s.5-.22.5-.5v-1.44c0-.58.47-1.06 1.06-1.06c.52 0 .94-.42.93-.94v-.12c0-.52-.42-.94-.94-.94h-.56c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h1.63c.48 0 .87.39.87.87v.63c0 .28.22.5.5.5s.5-.22.5-.5v-.58c0-1.06.86-1.92 1.92-1.92h1.58c.28 0 .5-.22.5-.5s-.22-.5-.5-.5h-2.9c-.33 0-.6-.27-.6-.6c0-.22-.18-.4-.4-.4h-4.53c-.69 0-1.37-.21-1.94-.6l-2.17-1.462C5.823 4.964 2.11 10.048 2.11 16c0 2.612.715 5.057 1.96 7.15");
}

.pa2kfx6lo {
  stop-color: var(--svg-color--606ac7, #606AC7);
}

.rfhww-btk {
  stop-color: var(--svg-color--478b68, #478B68);
}

.sksco_z5t {
  d: path("M18.078 17.81v.621c0 .415.09.786.687 1.005l1.121.522a.7.7 0 0 0 .28.058h.136a.69.69 0 0 0 .687-.687a.65.65 0 0 0-.203-.483l-1.538-1.538a.7.7 0 0 0-.483-.203a.71.71 0 0 0-.687.706");
}

.u1m_dgbne {
  d: path("M15.58 18h-.95c-.29 0-.53.24-.53.53v.95c0 .29.24.53.53.53h.95c.29 0 .53-.24.53-.53v-.95c0-.29-.24-.53-.53-.53");
}

.unntgpbby {
  stop-color: var(--svg-color--6ef7ae, #6EF7AE);
}

.va_efdced {
  d: path("m4.052 23.15l.584-.654c.277-.307.436-.713.436-1.13v-1.743a.58.58 0 0 1 .584-.585a.4.4 0 0 0 .406-.406v-.584a.994.994 0 0 0-.99-.991a.994.994 0 0 1-.991-.99v-.506c0-.268.218-.485.485-.485c.278 0 .516.227.496.505c0 .267.218.485.485.485h.595a.91.91 0 0 0 .911-.911v-.575a.49.49 0 0 1 .495-.495a.49.49 0 0 1 .496.495v.941c0 .307.247.545.545.545c.247 0 .446.198.446.446v.921a.617.617 0 0 0 1.169.278l1.605-3.22a.75.75 0 0 1 .663-.406c.317 0 .595.208.704.505l.693 2.07a.574.574 0 0 0 1.12-.178V14.58a.49.49 0 0 1 .495-.495a.49.49 0 0 0 .495-.496v-1.426c0-.575.466-1.05 1.05-1.05a.915.915 0 0 0 .922-.932v-.118a.93.93 0 0 0-.931-.932h-.555a.49.49 0 0 1-.495-.495a.49.49 0 0 1 .495-.495h1.615c.475 0 .862.386.862.861v.625a.49.49 0 0 0 .495.495a.49.49 0 0 0 .495-.495v-.575c0-1.05.853-1.902 1.903-1.902H23.4a.49.49 0 0 0 .495-.496a.49.49 0 0 0-.495-.495h-2.873a.596.596 0 0 1-.594-.594a.397.397 0 0 0-.397-.397h-4.488a3.4 3.4 0 0 1-1.922-.594l-2.15-1.448C5.79 5.133 2.11 10.17 2.11 16.066c0 2.588.71 5.01 1.943 7.084");
}

.vds0v4bui {
  d: path("M12.5 20.086c-.28 0-.5-.22-.5-.5v-1c0-.28.22-.5.5-.5s.5.22.5.5v1c0 .28-.23.5-.5.5");
}

.veugs_box {
  stop-color: var(--svg-color--4fc193, #4FC193);
}

.vsv10abek {
  stop-color: var(--svg-color--235897, #235897);
  stop-opacity: 0;
}

.vxo1-x6sa {
  stop-color: var(--svg-color--459c87, #459C87);
}

.wti-8mbin {
  d: path("m23.785 24.335l-1.59 1.59c-.13.13-.21.31-.21.5c0 .39.32.71.71.71c.19 0 .37-.07.5-.21l1.59-1.59c.13-.13.21-.31.21-.5c0-.39-.32-.71-.71-.71c-.19 0-.37.07-.5.21");
}

.xf7ha3u1l {
  stop-color: var(--svg-color--465dc2, #465DC2);
}

.y2mln9l1z {
  stop-color: var(--svg-color--74ffb5, #74FFB5);
}

.yc4dp6ktk {
  d: path("M12.61 20c-.28 0-.5-.22-.5-.5v-1c0-.28.22-.5.5-.5s.5.22.5.5v1c0 .28-.23.5-.5.5");
}

.yo6jqob0d {
  stop-color: var(--svg-color--52bc93, #52BC93);
}

.yrmbk9z9s {
  d: path("m18.851 11.288l-1.59 1.59c-.13.13-.21.31-.21.5c0 .39.32.71.71.71c.19 0 .37-.07.5-.21l1.59-1.59c.13-.13.21-.31.21-.5c0-.39-.32-.71-.71-.71c-.19 0-.37.07-.5.21");
}

.z89ft_hbc {
  d: path("m18.9 11.21l-1.59 1.59c-.13.13-.21.31-.21.5c0 .39.32.71.71.71c.19 0 .37-.07.5-.21l1.59-1.59c.13-.13.21-.31.21-.5c0-.39-.32-.71-.71-.71c-.19 0-.37.07-.5.21");
}

</style>
