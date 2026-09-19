<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isevwlb)" class="rocn32bmg"/><path fill="url(#i40Xcrb)" class="rocn32bmg"/><path fill="url(#ixELxzc)" class="rocn32bmg"/><path fill="url(#i2eAOJz)" class="rocn32bmg"/><path fill="url(#i5JPRFe)" class="rocn32bmg"/><path fill="url(#ieHU4KL)" class="faflaombe"/><path fill="url(#iVGKrqc)" class="faflaombe"/><path fill="url(#iYxLzdb)" class="faflaombe"/><g filter="url(#ipyFsWc)"><path fill="url(#i4YRuWI)" class="ss1pwobwg"/></g><path fill="url(#itH2O2X)" class="wc-dsbbdp"/><path fill="url(#i5HK3Bd)" class="wc-dsbbdp"/><path fill="url(#icBL5xb)" class="wc-dsbbdp"/><g filter="url(#iNad7pe)"><path fill="url(#ijSmPRe)" class="ioo88rbrp"/></g><g filter="url(#iO4iiMb)"><path stroke="url(#ijSgkzd)" class="relew8bgh"/></g><path fill="url(#ijLSh9Z)" clip-rule="evenodd" class="fvhrjnb8a"/><path fill="url(#iynnm9c)" clip-rule="evenodd" class="fvhrjnb8a"/><path fill="url(#iuBHQqb)" clip-rule="evenodd" class="fvhrjnb8a"/><g filter="url(#iP63G3d)"><path fill="url(#iaDQhmc)" clip-rule="evenodd" class="x7eeugb6u"/></g><g filter="url(#i2pEneb)"><path class="veykxmb2m"/></g><g filter="url(#i9WkFkc)"><path fill="url(#iacGgPX)" class="e22-2ib0h"/><path fill="url(#iWxXpUD)" class="e22-2ib0h"/></g><g filter="url(#i07IgNg)"><path stroke="url(#iDLXVHe)" class="ncl6pwcsl"/></g><g filter="url(#i1pYvRd)"><path stroke="url(#iem2qOe)" class="di1_4ybpv"/></g><g filter="url(#ia5Sjod)"><path stroke="url(#ieITN2e)" class="t31qxbcpg"/></g><g filter="url(#iIWGyCd)"><path stroke="url(#i0CEX9I)" class="xk3s5bkrx"/></g><g filter="url(#ivxwYec)"><path stroke="url(#i42l0fY)" class="vkh0hkb9a"/></g><defs><radialGradient id="i5JPRFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.625 -.46875 0 16.207 26.92)" gradientUnits="userSpaceOnUse"><stop class="g_o8fz06n"/><stop offset="1" class="ju50frbjv"/></radialGradient><radialGradient id="iYxLzdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79687 .82813 -.17558 -.16895 23.99 24.902)" gradientUnits="userSpaceOnUse"><stop class="w3qgp_15u"/><stop offset="1" class="y7zl7wbxw"/></radialGradient><radialGradient id="icBL5xb" cx="0" cy="0" r="1" gradientTransform="rotate(158.54 3.954 13.737)scale(4.86879 6.63165)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="wo8bwxbie"/><stop offset="1" class="emp987nse"/></radialGradient><radialGradient id="ijLSh9Z" cx="0" cy="0" r="1" gradientTransform="rotate(61.675 .161 10.587)scale(20.0223 28.0788)" gradientUnits="userSpaceOnUse"><stop class="t3fepwb9e"/><stop offset=".965" class="sb_grh92i"/></radialGradient><radialGradient id="iynnm9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28126 2.625 -.5082 -.24805 20.732 7.015)" gradientUnits="userSpaceOnUse"><stop class="gxthlm7iv"/><stop offset="1" class="pnxk05mqj"/></radialGradient><radialGradient id="iuBHQqb" cx="0" cy="0" r="1" gradientTransform="rotate(-148.213 14.321 4.799)scale(2.61026 .68203)" gradientUnits="userSpaceOnUse"><stop class="gxthlm7iv"/><stop offset="1" class="pnxk05mqj"/></radialGradient><radialGradient id="iaDQhmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -15.6113 21.8929 0 16 16.158)" gradientUnits="userSpaceOnUse"><stop class="e11oo5b7y"/><stop offset="1" class="tbfpmacwz"/></radialGradient><radialGradient id="iacGgPX" cx="0" cy="0" r="1" gradientTransform="rotate(137.161 6.441 9.73)scale(4.68792 3.72969)" gradientUnits="userSpaceOnUse"><stop class="ka7j428ik"/><stop offset=".814" class="rjs3rrfgc"/></radialGradient><radialGradient id="iWxXpUD" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -3.35745 5.77551 3.97798 13.904 16.734)" gradientUnits="userSpaceOnUse"><stop class="x4pem_9hf"/><stop offset="1" class="f3qz4eboq"/></radialGradient><radialGradient id="iDLXVHe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 2.15625 -2.5 -2.5 19.31 3.578)" gradientUnits="userSpaceOnUse"><stop class="b92oz68he"/><stop offset="1" class="rjdt715pk"/></radialGradient><radialGradient id="iem2qOe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0625 1.78125 -3.875 -4.48685 25.623 9.203)" gradientUnits="userSpaceOnUse"><stop class="b92oz68he"/><stop offset="1" class="rjdt715pk"/></radialGradient><radialGradient id="ieITN2e" cx="0" cy="0" r="1" gradientTransform="rotate(101.415 4.86 18.285)scale(4.55893 1.85266)" gradientUnits="userSpaceOnUse"><stop class="b92oz68he"/><stop offset="1" class="rjdt715pk"/></radialGradient><radialGradient id="i0CEX9I" cx="0" cy="0" r="1" gradientTransform="rotate(149.201 4.853 12.53)scale(2.11322 2.4415)" gradientUnits="userSpaceOnUse"><stop class="b92oz68he"/><stop offset="1" class="rjdt715pk"/></radialGradient><radialGradient id="i42l0fY" cx="0" cy="0" r="1" gradientTransform="rotate(26.796 -10.927 24.989)scale(3.46593 2.37024)" gradientUnits="userSpaceOnUse"><stop class="b92oz68he"/><stop offset="1" class="rjdt715pk"/></radialGradient><linearGradient id="isevwlb" x1="16.002" x2="16.002" y1="29.772" y2="20.293" gradientUnits="userSpaceOnUse"><stop class="l9miucc0b"/><stop offset="1" class="sddv6hldr"/></linearGradient><linearGradient id="i40Xcrb" x1="14.878" x2="15.503" y1="27.902" y2="27.855" gradientUnits="userSpaceOnUse"><stop class="y8f693b9e"/><stop offset="1" class="wnjx4wbjd"/></linearGradient><linearGradient id="ixELxzc" x1="17" x2="16.503" y1="27.949" y2="27.949" gradientUnits="userSpaceOnUse"><stop class="y8f693b9e"/><stop offset="1" class="wnjx4wbjd"/></linearGradient><linearGradient id="i2eAOJz" x1="14.909" x2="15.347" y1="23.543" y2="23.559" gradientUnits="userSpaceOnUse"><stop class="lcl8i2bvp"/><stop offset="1" class="n4t4mlb3d"/></linearGradient><linearGradient id="ieHU4KL" x1="17.834" x2="25.009" y1="29.767" y2="24.987" gradientUnits="userSpaceOnUse"><stop class="gdhzxbc-m"/><stop offset="1" class="ol8o05bqz"/></linearGradient><linearGradient id="iVGKrqc" x1="19.271" x2="19.271" y1="30.105" y2="28.699" gradientUnits="userSpaceOnUse"><stop class="h26o556mt"/><stop offset="1" class="oy7h34bgk"/></linearGradient><linearGradient id="i4YRuWI" x1="22.739" x2="18.832" y1="25.226" y2="28.46" gradientUnits="userSpaceOnUse"><stop class="norg35btb"/><stop offset="1" class="n-xdwifnc"/></linearGradient><linearGradient id="itH2O2X" x1="12.448" x2="8.23" y1="24.687" y2="30.398" gradientUnits="userSpaceOnUse"><stop offset=".011" class="hinb-sbwy"/><stop offset="1" class="c3bch-exu"/><stop offset="1" class="o4i9h6buw"/></linearGradient><linearGradient id="i5HK3Bd" x1="13.823" x2="13.823" y1="30.179" y2="28.21" gradientUnits="userSpaceOnUse"><stop class="e-2abd5ql"/><stop offset="1" class="d7hfbsbga"/></linearGradient><linearGradient id="ijSmPRe" x1="14.464" x2="9.198" y1="28.71" y2="25.351" gradientUnits="userSpaceOnUse"><stop class="dq2vqeb7n"/><stop offset="1" class="ao7x5xbuq"/></linearGradient><linearGradient id="ijSgkzd" x1="14.464" x2="9.667" y1="27.078" y2="24.328" gradientUnits="userSpaceOnUse"><stop class="awtm28vjm"/><stop offset="1" class="q6d83lbcd"/></linearGradient><filter id="ipyFsWc" width="6.997" height="4.988" x="17.14" y="24.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".3"/></filter><filter id="iNad7pe" width="7.218" height="5.43" x="7.996" y="24.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".375"/></filter><filter id="iO4iiMb" width="4.727" height="5.051" x="10.488" y="24.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".25"/></filter><filter id="iP63G3d" width="22.265" height="21.789" x="4.867" y="1.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".5"/></filter><filter id="i2pEneb" width="9.56" height="9.56" x="10.874" y="8.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".5"/></filter><filter id="i9WkFkc" width="7.56" height="7.56" x="12.12" y="9.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.841667 0 0 0 0 0.504112 0 0 0 0 0.199896 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7495"/></filter><filter id="i07IgNg" width="5.542" height="6.284" x="15.073" y="1.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".3"/></filter><filter id="i1pYvRd" width="6.426" height="7.804" x="20.948" y="6.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".3"/></filter><filter id="ia5Sjod" width="3.257" height="7.506" x="21.292" y="15.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".3"/></filter><filter id="iIWGyCd" width="3.444" height="3.444" x="13.167" y="19.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".3"/></filter><filter id="ivxwYec" width="4.663" height="2.787" x="9.042" y="6.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7495" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:blossom" /></template>
<style>
.ao7x5xbuq {
  stop-color: var(--svg-color--619a6a, #619A6A);
}

.awtm28vjm {
  stop-color: var(--svg-color--86ad7a, #86AD7A);
}

.b92oz68he {
  stop-color: var(--svg-color--e9e2f0, #E9E2F0);
}

.c3bch-exu {
  stop-color: var(--svg-color--008461, #008461);
}

.d7hfbsbga {
  stop-color: var(--svg-color--6f7e82, #6F7E82);
  stop-opacity: 0;
}

.di1_4ybpv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.748 7.547c.906-.083 2.975.106 4 1.531c1.281 1.781.906 3.563 0 4.656");
}

.dq2vqeb7n {
  stop-color: var(--svg-color--6fa06a, #6FA06A);
}

.e-2abd5ql {
  stop-color: var(--svg-color--6f7e82, #6F7E82);
}

.e11oo5b7y {
  stop-color: var(--svg-color--e7d4f9, #E7D4F9);
}

.e22-2ib0h {
  d: path("M15.9 17.157a3.78 3.78 0 1 0 0-7.56a3.78 3.78 0 0 0 0 7.56");
}

.emp987nse {
  stop-color: var(--svg-color--92b196, #92B196);
}

.f3qz4eboq {
  stop-color: var(--svg-color--ec6f51, #EC6F51);
  stop-opacity: 0;
}

.faflaombe {
  d: path("M16.78 29.067c0-2.4 1.95-4.35 4.26-4.37l2.88-.01c.14 0 .26.12.25.27c-.14 2.66-2.34 4.81-5.04 4.81h-2.07a.28.28 0 0 1-.28-.28z");
}

.ft5dv1b6b {
  fill: none;
}

.fvhrjnb8a {
  fill-rule: evenodd;
  d: path("M23.456 16.384c-.136-.165-.042-.439.167-.485a4.51 4.51 0 1 0-2.741-8.554c-.205.086-.452-.1-.427-.32q.03-.255.03-.517a4.508 4.508 0 1 0-8.989.502c.025.218-.217.4-.42.317a4.508 4.508 0 1 0-2.758 8.558c.206.05.296.32.16.483a4.508 4.508 0 1 0 7.237 5.354a.3.3 0 0 1 .492 0a4.508 4.508 0 1 0 7.25-5.338");
}

.g_o8fz06n {
  stop-color: var(--svg-color--83b15d, #83B15D);
}

.gdhzxbc-m {
  stop-color: var(--svg-color--528c39, #528C39);
}

.gxthlm7iv {
  stop-color: var(--svg-color--e8def1, #E8DEF1);
}

.h26o556mt {
  stop-color: var(--svg-color--6a806e, #6A806E);
}

.hinb-sbwy {
  stop-color: var(--svg-color--629b53, #629B53);
}

.ioo88rbrp {
  d: path("M8.746 25.804c0 1.856 1.509 3.365 3.296 3.38l2.228.008a.195.195 0 0 0 .194-.209c-.109-2.058-1.81-3.721-3.9-3.721h-1.6c-.124 0-.217.1-.217.217z");
}

.ju50frbjv {
  stop-color: var(--svg-color--83b15d, #83B15D);
  stop-opacity: 0;
}

.ka7j428ik {
  stop-color: var(--svg-color--ffba5f, #FFBA5F);
}

.l9miucc0b {
  stop-color: var(--svg-color--5da112, #5DA112);
}

.lcl8i2bvp {
  stop-color: var(--svg-color--8fb87f, #8FB87F);
}

.n-xdwifnc {
  stop-color: var(--svg-color--7ba561, #7BA561);
}

.n4t4mlb3d {
  stop-color: var(--svg-color--8fb87f, #8FB87F);
  stop-opacity: 0;
}

.ncl6pwcsl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.873 2.703c.48-.094 1.725-.006 2.875 1.094s1.146 2.833 1 3.562");
}

.norg35btb {
  stop-color: var(--svg-color--87be58, #87BE58);
}

.o4i9h6buw {
  stop-color: var(--svg-color--4d9055, #4D9055);
}

.ol8o05bqz {
  stop-color: var(--svg-color--81bd52, #81BD52);
}

.oy7h34bgk {
  stop-color: var(--svg-color--6a806e, #6A806E);
  stop-opacity: 0;
}

.pnxk05mqj {
  stop-color: var(--svg-color--e8def1, #E8DEF1);
  stop-opacity: 0;
}

.q6d83lbcd {
  stop-color: var(--svg-color--86ad7a, #86AD7A);
  stop-opacity: 0;
}

.relew8bgh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.238 25.434c1.156.156 3.039 1.513 3.226 3.55");
}

.rjdt715pk {
  stop-color: var(--svg-color--e9e2f0, #E9E2F0);
  stop-opacity: 0;
}

.rjs3rrfgc {
  stop-color: var(--svg-color--fc8f39, #FC8F39);
}

.rocn32bmg {
  d: path("M17 19.637h-2v10.13h2z");
}

.sb_grh92i {
  stop-color: var(--svg-color--d7c0ef, #D7C0EF);
}

.sddv6hldr {
  stop-color: var(--svg-color--74a93f, #74A93F);
}

.ss1pwobwg {
  d: path("M17.74 28.492c0-1.79 1.53-3.244 3.341-3.259l2.26-.007c.109 0 .203.09.195.201c-.11 1.984-1.835 3.587-3.953 3.587h-1.624a.214.214 0 0 1-.22-.209z");
}

.t31qxbcpg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M22.873 16.422c.844.875 1.75 4.125-.781 5.906");
}

.t3fepwb9e {
  stop-color: var(--svg-color--bbb5c2, #BBB5C2);
}

.tbfpmacwz {
  stop-color: var(--svg-color--d0c3dc, #D0C3DC);
}

.veykxmb2m {
  fill: var(--svg-color--d2b9da, #D2B9DA);
  d: path("M15.654 17.534a3.78 3.78 0 1 0 0-7.56a3.78 3.78 0 0 0 0 7.56");
}

.vkh0hkb9a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.842 7.766c.542 0 1.912.237 3.062 1.187");
}

.w3qgp_15u {
  stop-color: var(--svg-color--9dd271, #9DD271);
}

.wc-dsbbdp {
  d: path("M7.91 25.387c0 2.4 1.95 4.35 4.26 4.37l2.88.01c.14 0 .26-.12.25-.27c-.14-2.66-2.34-4.81-5.04-4.81H8.19a.28.28 0 0 0-.28.28z");
}

.wnjx4wbjd {
  stop-color: var(--svg-color--51923c, #51923C);
  stop-opacity: 0;
}

.wo8bwxbie {
  stop-color: var(--svg-color--92b196, #92B196);
  stop-opacity: 0;
}

.x4pem_9hf {
  stop-color: var(--svg-color--ec6f51, #EC6F51);
}

.x7eeugb6u {
  fill-rule: evenodd;
  d: path("M22.813 16.105c-.134-.167-.04-.441.168-.49a4.102 4.102 0 1 0-2.49-7.79c-.206.083-.456-.103-.433-.324q.02-.205.02-.417a4.1 4.1 0 1 0-8.18.405c.022.218-.221.402-.426.32A4.1 4.1 0 1 0 8.965 15.6c.206.053.297.325.163.49a4.1 4.1 0 1 0 6.588 4.87a.306.306 0 0 1 .496 0a4.1 4.1 0 1 0 6.6-4.854");
}

.xk3s5bkrx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.967 22.297c.437-.167 1.544-.769 1.844-1.844");
}

.y7zl7wbxw {
  stop-color: var(--svg-color--9dd271, #9DD271);
  stop-opacity: 0;
}

.y8f693b9e {
  stop-color: var(--svg-color--51923c, #51923C);
}

</style>
