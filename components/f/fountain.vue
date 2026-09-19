<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9HSaze)" class="qvvwvrbij"/><path fill="url(#iQnHPRd)" class="qvvwvrbij"/><path fill="url(#if77xNc)" class="qvvwvrbij"/><path fill="url(#i5clfJe)" class="ksxog5oie"/><path fill="url(#iDZcBql)" class="ksxog5oie"/><path fill="url(#ixJ6YVd)" class="ksxog5oie"/><path fill="url(#iljawee)" class="ksxog5oie"/><path fill="url(#ijzJcJK)" class="ksxog5oie"/><g filter="url(#iZeQCKb)"><path fill="url(#izuztsV)" class="qy8eq7brv"/><path fill="url(#iRC5TAb)" class="qy8eq7brv"/><path fill="url(#iYTvrQd)" class="qy8eq7brv"/><path fill="url(#iegRboc)" class="qy8eq7brv"/><path fill="url(#iNUwSie)" class="qy8eq7brv"/><path fill="url(#i0PJ2dd)" class="qy8eq7brv"/></g><path fill="url(#io6BX1X)" class="s21zoob0z"/><path fill="url(#iP2wWBb)" class="s21zoob0z"/><path fill="url(#i0kGjpe)" class="s21zoob0z"/><path fill="url(#iKfFSZc)" class="xq17sxpfu"/><path fill="url(#ih4coKu)" class="xq17sxpfu"/><path fill="url(#iXHqcpd)" class="xq17sxpfu"/><path fill="url(#ihx9iDc)" class="h9--onbhw"/><path fill="url(#iUu9o6c)" class="h9--onbhw"/><path fill="url(#iIDW5ze)" class="h9--onbhw"/><g filter="url(#iDJVpRy)"><path fill="url(#iJGMFpb)" class="pfwwgzu0s"/></g><g filter="url(#iP3BSNc)"><path fill="url(#iKtKNBe)" class="s4-xtwdyq"/></g><defs><radialGradient id="iDZcBql" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.355 -15.0954 0 23.922 15.635)" gradientUnits="userSpaceOnUse"><stop class="y3bzghb5o"/><stop offset=".841" class="tdg0-ybkh"/></radialGradient><radialGradient id="ixJ6YVd" cx="0" cy="0" r="1" gradientTransform="matrix(7.9375 4.9375 -5.2876 8.50031 3.985 17.323)" gradientUnits="userSpaceOnUse"><stop class="gv2icvbhu"/><stop offset="1" class="odzjh-w_q"/></radialGradient><radialGradient id="iljawee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78884 -10.4599 0 9.02 15.99)" gradientUnits="userSpaceOnUse"><stop class="ctpfdvgnw"/><stop offset="1" class="hgsgysilz"/></radialGradient><radialGradient id="ijzJcJK" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82186 -10.8978 0 21.833 15.99)" gradientUnits="userSpaceOnUse"><stop class="mxq3m0b9j"/><stop offset="1" class="ptbsy9bsz"/></radialGradient><radialGradient id="iRC5TAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.31411 -.29688 0 15.985 6.07)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="j5i-vhbmz"/><stop offset=".793" class="ozf3tlbcs"/></radialGradient><radialGradient id="iegRboc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.46875 1.07026 1.99782 18.923 11.291)" gradientUnits="userSpaceOnUse"><stop class="o3-bwko_s"/><stop offset="1" class="f6p23punf"/></radialGradient><radialGradient id="iNUwSie" cx="0" cy="0" r="1" gradientTransform="matrix(.0418 1.21207 -1.226 .04227 13.988 9.905)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="o1vp5bqck"/><stop offset="1" class="vj65s8bzz"/></radialGradient><radialGradient id="i0PJ2dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06966 1.2678 -1.15897 -.06368 18 9.905)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="o1vp5bqck"/><stop offset="1" class="vj65s8bzz"/></radialGradient><radialGradient id="io6BX1X" cx="0" cy="0" r="1" gradientTransform="rotate(126.135 11.83 9.48)scale(1.22765)" gradientUnits="userSpaceOnUse"><stop class="a4vo3u37p"/><stop offset="1" class="t3pigubsh"/></radialGradient><radialGradient id="i0kGjpe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14474 .8125 -.81994 -1.15521 26.13 5.76)" gradientUnits="userSpaceOnUse"><stop offset=".606" class="elnq0pnlc"/><stop offset="1" class="b0wqw_b7q"/></radialGradient><radialGradient id="iKfFSZc" cx="0" cy="0" r="1" gradientTransform="rotate(126.135 -.203 8.4)scale(1.22765)" gradientUnits="userSpaceOnUse"><stop class="rr50lj43s"/><stop offset="1" class="zwj-ylb9o"/></radialGradient><radialGradient id="iXHqcpd" cx="0" cy="0" r="1" gradientTransform="rotate(151.46 1.653 7.662)scale(2.02764 2.04618)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="bj7urccfd"/><stop offset="1" class="ubwg8_bfo"/></radialGradient><radialGradient id="iJGMFpb" cx="0" cy="0" r="1" gradientTransform="rotate(134.318 9.321 7.943)scale(3.71257 22.3165)" gradientUnits="userSpaceOnUse"><stop class="o0zo4vy6a"/><stop offset="1" class="qr6yuub4h"/></radialGradient><radialGradient id="iKtKNBe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.46874 2.28126 -13.71285 -26.86197 15.266 7.416)" gradientUnits="userSpaceOnUse"><stop class="o0zo4vy6a"/><stop offset="1" class="qr6yuub4h"/></radialGradient><linearGradient id="i9HSaze" x1="13.654" x2="17.799" y1="24.549" y2="28.694" gradientUnits="userSpaceOnUse"><stop class="w3lqi17-j"/><stop offset=".236" class="e1hl60rbr"/><stop offset="1" class="x9rc7dtjx"/></linearGradient><linearGradient id="iQnHPRd" x1="13.355" x2="15.377" y1="28.668" y2="27.506" gradientUnits="userSpaceOnUse"><stop class="f9--sfbmx"/><stop offset="1" class="j7tvf-bve"/></linearGradient><linearGradient id="if77xNc" x1="15.972" x2="15.972" y1="24.859" y2="25.418" gradientUnits="userSpaceOnUse"><stop class="i40s9_q3y"/><stop offset="1" class="y0u31klxt"/><stop offset="1" class="ok-yuyblb"/></linearGradient><linearGradient id="i5clfJe" x1="14.235" x2="15.985" y1="24.448" y2="15.572" gradientUnits="userSpaceOnUse"><stop class="swv20sbvv"/><stop offset="1" class="wae-w0imf"/><stop offset="1" class="p_atd7_dr"/></linearGradient><linearGradient id="izuztsV" x1="15.985" x2="15.985" y1="7.098" y2="15" gradientUnits="userSpaceOnUse"><stop class="u4mec_bbh"/><stop offset=".788" class="q9l4xcj1q"/></linearGradient><linearGradient id="iYTvrQd" x1="7.548" x2="10.016" y1="11.385" y2="11.385" gradientUnits="userSpaceOnUse"><stop class="vwdeo3e-r"/><stop offset="1" class="pj-vwovkb"/></linearGradient><linearGradient id="iP2wWBb" x1="25.985" x2="25.985" y1="5" y2="5.455" gradientUnits="userSpaceOnUse"><stop class="h0xoh1d_p"/><stop offset="1" class="p0zpzfbts"/></linearGradient><linearGradient id="ih4coKu" x1="5.985" x2="5.985" y1="13" y2="13.455" gradientUnits="userSpaceOnUse"><stop class="jsktuow-y"/><stop offset="1" class="uqzqlqbiq"/></linearGradient><linearGradient id="ihx9iDc" x1="10.848" x2="18.737" y1="29.979" y2="29.979" gradientUnits="userSpaceOnUse"><stop class="rekr77bfh"/><stop offset=".24" class="f47gh6a_u"/><stop offset="1" class="kamogiucd"/></linearGradient><linearGradient id="iUu9o6c" x1="20.747" x2="20.134" y1="29.979" y2="29.979" gradientUnits="userSpaceOnUse"><stop class="jzi6eccyg"/><stop offset="1" class="adckqac8n"/></linearGradient><linearGradient id="iIDW5ze" x1="15.798" x2="15.798" y1="27.846" y2="28.576" gradientUnits="userSpaceOnUse"><stop class="pamlbcc2j"/><stop offset="1" class="glgm11b9b"/></linearGradient><filter id="iZeQCKb" width="14" height="10.1" x="8.985" y="5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.835294 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7483"/></filter><filter id="iDJVpRy" width="8.109" height="7.344" x="15.141" y="4.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7483" stdDeviation=".5"/></filter><filter id="iP3BSNc" width="8.109" height="7.344" x="9.032" y="4.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7483" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fountain" /></template>
<style>
.a4vo3u37p {
  stop-color: var(--svg-color--d5f3ff, #D5F3FF);
}

.adckqac8n {
  stop-color: var(--svg-color--e1dfe3, #E1DFE3);
  stop-opacity: 0;
}

.b0wqw_b7q {
  stop-color: var(--svg-color--64b0f3, #64B0F3);
}

.bj7urccfd {
  stop-color: var(--svg-color--529ed7, #529ED7);
  stop-opacity: 0;
}

.ctpfdvgnw {
  stop-color: var(--svg-color--a4a3a4, #A4A3A4);
}

.e1hl60rbr {
  stop-color: var(--svg-color--93839d, #93839D);
}

.elnq0pnlc {
  stop-color: var(--svg-color--64b0f3, #64B0F3);
  stop-opacity: 0;
}

.f47gh6a_u {
  stop-color: var(--svg-color--a095a9, #A095A9);
}

.f6p23punf {
  stop-color: var(--svg-color--4fafec, #4FAFEC);
  stop-opacity: 0;
}

.f9--sfbmx {
  stop-color: var(--svg-color--666269, #666269);
}

.ft5dv1b6b {
  fill: none;
}

.glgm11b9b {
  stop-color: var(--svg-color--9f99a4, #9F99A4);
  stop-opacity: 0;
}

.gv2icvbhu {
  stop-color: var(--svg-color--807b83, #807B83);
}

.h0xoh1d_p {
  stop-color: var(--svg-color--c3e2f8, #C3E2F8);
}

.h9--onbhw {
  d: path("M10.848 28.994a1 1 0 0 1 1-1h7.899a1 1 0 0 1 1 1v.985h-9.899z");
}

.hgsgysilz {
  stop-color: var(--svg-color--a4a3a4, #A4A3A4);
  stop-opacity: 0;
}

.i40s9_q3y {
  stop-color: var(--svg-color--71657c, #71657C);
}

.j5i-vhbmz {
  stop-color: var(--svg-color--b6ddf7, #B6DDF7);
}

.j7tvf-bve {
  stop-color: var(--svg-color--666269, #666269);
  stop-opacity: 0;
}

.jsktuow-y {
  stop-color: var(--svg-color--b4d5ed, #B4D5ED);
}

.jzi6eccyg {
  stop-color: var(--svg-color--e1dfe3, #E1DFE3);
}

.kamogiucd {
  stop-color: var(--svg-color--eae6ed, #EAE6ED);
}

.ksxog5oie {
  d: path("M27.055 15.99H4.915c-.51 0-.93.38-.93.85V17c.05 4.4 4.03 7.99 8.89 7.99h6.22c4.86 0 8.83-3.59 8.89-7.99v-.17c0-.46-.42-.84-.93-.84");
}

.mxq3m0b9j {
  stop-color: var(--svg-color--f4f3f5, #F4F3F5);
}

.o0zo4vy6a {
  stop-color: var(--svg-color--dcf7ff, #DCF7FF);
}

.o1vp5bqck {
  stop-color: var(--svg-color--47b4ee, #47B4EE);
}

.o3-bwko_s {
  stop-color: var(--svg-color--4fafec, #4FAFEC);
}

.odzjh-w_q {
  stop-color: var(--svg-color--807b83, #807B83);
  stop-opacity: 0;
}

.ok-yuyblb {
  stop-color: var(--svg-color--71657c, #71657C);
  stop-opacity: 0;
}

.ozf3tlbcs {
  stop-color: var(--svg-color--b8ddf7, #B8DDF7);
  stop-opacity: 0;
}

.p_atd7_dr {
  stop-color: var(--svg-color--c4bbcb, #C4BBCB);
}

.p0zpzfbts {
  stop-color: var(--svg-color--c3e2f8, #C3E2F8);
  stop-opacity: 0;
}

.pamlbcc2j {
  stop-color: var(--svg-color--9f99a4, #9F99A4);
}

.pfwwgzu0s {
  d: path("M19.36 5.713c-1.625.013-3.219 1.313-3.219 2.89c.556-1.56 2.22-2.062 3.22-1.859c1.065.217 1.327 1.105 1.312 1.657v1.867a.79.79 0 0 0 1.578 0V8.401c0-.766-.86-2.703-2.89-2.688");
}

.pj-vwovkb {
  stop-color: var(--svg-color--46a6e7, #46A6E7);
  stop-opacity: 0;
}

.ptbsy9bsz {
  stop-color: var(--svg-color--f4f3f5, #F4F3F5);
  stop-opacity: 0;
}

.q9l4xcj1q {
  stop-color: var(--svg-color--52baf9, #52BAF9);
}

.qr6yuub4h {
  stop-color: var(--svg-color--dcf7ff, #DCF7FF);
  stop-opacity: 0;
}

.qvvwvrbij {
  d: path("M18.912 27.994V24.01h-5.88v3.984z");
}

.qy8eq7brv {
  d: path("M18.985 5c-1.2 0-2.27.538-3 1.376a3.97 3.97 0 0 0-3-1.376c-2.21 0-4 1.785-4 3.988v2.034h.01a1.99 1.99 0 0 0 1.99 1.934c1.08 0 1.96-.857 1.99-1.934v-1.007c0-.558.45-1.007 1.01-1.007c.44 0 .922.252.922.736l.28 4.35c.038.553.348.906.788.906s.73-.331.78-.907l.261-4.349c.04-.53.52-.726.96-.726c.56 0 1.01.449 1.01 1.007v1.007h.01a1.99 1.99 0 0 0 1.99 1.934c1.08 0 1.96-.857 1.99-1.934h.01V8.988a3.993 3.993 0 0 0-4-3.988");
}

.rekr77bfh {
  stop-color: var(--svg-color--7d7584, #7D7584);
}

.rr50lj43s {
  stop-color: var(--svg-color--a8d9f9, #A8D9F9);
}

.s21zoob0z {
  d: path("M25.985 7a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.s4-xtwdyq {
  d: path("M12.923 5.713c1.625.013 3.218 1.313 3.218 2.89c-.555-1.56-2.218-2.062-3.218-1.859c-1.066.217-1.328 1.105-1.313 1.657v1.867a.79.79 0 0 1-1.578 0V8.401c0-.766.86-2.703 2.89-2.688");
}

.swv20sbvv {
  stop-color: var(--svg-color--826b93, #826B93);
}

.t3pigubsh {
  stop-color: var(--svg-color--83c8fd, #83C8FD);
}

.tdg0-ybkh {
  stop-color: var(--svg-color--f5f3f7, #F5F3F7);
  stop-opacity: 0;
}

.u4mec_bbh {
  stop-color: var(--svg-color--c0e0f7, #C0E0F7);
}

.ubwg8_bfo {
  stop-color: var(--svg-color--529ed7, #529ED7);
}

.uqzqlqbiq {
  stop-color: var(--svg-color--b4d5ed, #B4D5ED);
  stop-opacity: 0;
}

.vj65s8bzz {
  stop-color: var(--svg-color--47b4ee, #47B4EE);
  stop-opacity: 0;
}

.vwdeo3e-r {
  stop-color: var(--svg-color--46a6e7, #46A6E7);
}

.w3lqi17-j {
  stop-color: var(--svg-color--6f6578, #6F6578);
}

.wae-w0imf {
  stop-color: var(--svg-color--d3d3d3, #D3D3D3);
}

.x9rc7dtjx {
  stop-color: var(--svg-color--e6e4e7, #E6E4E7);
}

.xq17sxpfu {
  d: path("M5.985 15a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.y0u31klxt {
  stop-color: var(--svg-color--93879c, #93879C);
  stop-opacity: 0;
}

.y3bzghb5o {
  stop-color: var(--svg-color--f5f3f7, #F5F3F7);
}

.zwj-ylb9o {
  stop-color: var(--svg-color--57b6f4, #57B6F4);
}

</style>
