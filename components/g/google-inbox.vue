<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":240};
const content = `<defs><filter x="-.6%" y="-1.5%" width="101.2%" height="102.9%" filterUnits="objectBoundingBox" id="ssvg-id-google-inboxb"><feOffset dy="3" in="SourceAlpha" result="shadowOffsetInner1"/><feComposite in="shadowOffsetInner1" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="shadowInnerInner1"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.282269022 0" in="shadowInnerInner1"/></filter><filter x="-1.4%" y="-5.7%" width="105.5%" height="108.5%" filterUnits="objectBoundingBox" id="ssvg-id-google-inboxc"><feOffset dx="3" dy="-2" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur stdDeviation="1.5" in="shadowOffsetOuter1" result="shadowBlurOuter1"/><feColorMatrix values="0 0 0 0 0.181283504 0 0 0 0 0.347530335 0 0 0 0 0.727242827 0 0 0 0.4 0" in="shadowBlurOuter1"/></filter><filter x="-1.3%" y="-6.4%" width="105.1%" height="108.5%" filterUnits="objectBoundingBox" id="ssvg-id-google-inboxe"><feOffset dx="3" dy="-3" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur stdDeviation="1.5" in="shadowOffsetOuter1" result="shadowBlurOuter1"/><feColorMatrix values="0 0 0 0 0.181283504 0 0 0 0 0.347530335 0 0 0 0 0.727242827 0 0 0 0.1 0" in="shadowBlurOuter1"/></filter><filter x="-.6%" y="-5.3%" width="103.8%" height="106.4%" filterUnits="objectBoundingBox" id="ssvg-id-google-inboxg"><feOffset dy="3" in="SourceAlpha" result="shadowOffsetInner1"/><feComposite in="shadowOffsetInner1" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="shadowInnerInner1"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.129840353 0" in="shadowInnerInner1"/></filter><filter x="-310%" y="-41.3%" width="720%" height="182.7%" filterUnits="objectBoundingBox" id="ssvg-id-google-inboxh"><feGaussianBlur stdDeviation="15" in="SourceGraphic"/></filter><filter x="-1.8%" y="-2.3%" width="103.6%" height="104.6%" filterUnits="objectBoundingBox" id="ssvg-id-google-inboxk"><feOffset dy="5" in="SourceAlpha" result="shadowOffsetInner1"/><feComposite in="shadowOffsetInner1" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="shadowInnerInner1"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.5 0" in="shadowInnerInner1"/></filter><path id="ssvg-id-google-inboxa" class="v-w5gy0sj"/><path id="ssvg-id-google-inboxd" class="jmy6embam"/><path id="ssvg-id-google-inboxf" class="dv9j3ndcz"/><path id="ssvg-id-google-inboxj" class="fnab1vltu"/><linearGradient x1="33.969%" y1="100%" x2="97.74%" y2="11.915%" id="ssvg-id-google-inboxi"><stop offset="0%" class="tj_svngua"/><stop offset="0%" class="et1kdc30d"/><stop offset="40.899%" class="im2i7z74y"/><stop offset="83.991%" class="im2i7z74y"/><stop offset="84.011%" class="jfum6r0tw"/><stop offset="84.024%" class="vo_ubop8q"/><stop offset="84.078%" class="vo_ubop8q"/><stop offset="84.272%" class="vo_ubop8q"/><stop offset="100%" class="vo_ubop8q"/></linearGradient></defs><use xlink:href="#ssvg-id-google-inboxa" class="nahwtab5y"/><use filter="url(#ssvg-id-google-inboxb)" xlink:href="#ssvg-id-google-inboxa"/><path class="aua92f1in"/><use filter="url(#ssvg-id-google-inboxc)" xlink:href="#ssvg-id-google-inboxd"/><use xlink:href="#ssvg-id-google-inboxd" class="jp6_t0_yk"/><use filter="url(#ssvg-id-google-inboxe)" xlink:href="#ssvg-id-google-inboxf"/><use xlink:href="#ssvg-id-google-inboxf" class="ikb0u3b-p"/><use filter="url(#ssvg-id-google-inboxg)" xlink:href="#ssvg-id-google-inboxf"/><path filter="url(#ssvg-id-google-inboxh)" transform="rotate(45 160.874 83.099)" class="mygtwbcan"/><path class="ryn74hbia"/><path fill="url(#ssvg-id-google-inboxi)" class="px8jr7k2r"/><g><use xlink:href="#ssvg-id-google-inboxj" class="iuop2bcnb"/><use filter="url(#ssvg-id-google-inboxk)" xlink:href="#ssvg-id-google-inboxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-inbox" /></template>
<style>
.aua92f1in {
  d: path("M0 97.738h249.652V213.53c0 5.73-5.857 10.376-13.082 10.376H13.082C5.857 223.905 0 219.259 0 213.529V97.738z");
  fill: var(--svg-color--3f72db, #3F72DB);
}

.dv9j3ndcz {
  d: path("M249.652 97.738v128.065c0 7.21-5.848 13.055-13.056 13.055H13.084l236.568-141.12z");
}

.et1kdc30d {
  stop-color: var(--svg-color--3558b1, #3558B1);
}

.fnab1vltu {
  d: path("M123.968 128.707l-47.32-47.332l15.897-15.9l31.37 31.429l76.903-76.924l15.897 15.901l-77.485 77.505l-1.898 1.899z");
}

.ikb0u3b-p {
  fill: var(--svg-color--96ddfc, #96DDFC);
  fill-rule: evenodd;
}

.im2i7z74y {
  stop-color: var(--svg-color--3a4768, #3A4768);
}

.iuop2bcnb {
  fill: var(--svg-color--e5e5e5, #E5E5E5);
  fill-rule: evenodd;
}

.jfum6r0tw {
  stop-color: var(--svg-color--687eb7, #687EB7);
}

.jmy6embam {
  d: path("M0 97.738l219.296 141.12H13.056C5.844 238.858 0 233.013 0 225.803V97.738z");
}

.jp6_t0_yk {
  fill: var(--svg-color--36bbf7, #36BBF7);
  fill-rule: evenodd;
}

.mygtwbcan {
  fill: var(--svg-color--203364, #203364);
  d: path("M156.146 41.289l-2.53 96.225h14.517l-.753-108.83z");
}

.nahwtab5y {
  fill: var(--svg-color--3760c9, #3760C9);
  fill-rule: evenodd;
}

.px8jr7k2r {
  d: path("M123.968 130.253L76.648 82.92L92.546 67.02l31.37 31.43l76.903-76.924l16.322 15l-15.075 15.17l-62.835 63.236l-1.898 1.898z");
}

.ryn74hbia {
  d: path("M124.105 130.03l27.285 26.586l98.227-58.369s.38-7.006-1.079-10.144c-1.34-2.883-7.322-7.919-7.322-7.919l-40-28.71l-77.111 78.555z");
  fill: var(--svg-color--cbcbcb, #CBCBCB);
}

.tj_svngua {
  stop-color: var(--svg-color--335fcf, #335FCF);
}

.v-w5gy0sj {
  d: path("M.022 91.466C.008 87.983 3.293 83.532 10.06 78.68L116.012 2.704c4.934-3.538 12.946-3.538 17.887.005l105.618 75.733c6.913 4.957 10.192 9.5 10.031 13.024h.104v11.499H0V91.466h.022z");
}

.vo_ubop8q {
  stop-color: var(--svg-color--cbcbcb, #CBCBCB);
}

</style>
