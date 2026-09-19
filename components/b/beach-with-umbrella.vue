<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iAbpKYc)"><path fill="url(#i3FUVEd)" class="iosi0o1kb"/></g><g filter="url(#i5jo0Cc)"><path fill="url(#istIHAe)" class="mcc0s7zbt"/></g><path fill="url(#itoTcEd)" class="lne5q7jsk"/><path fill="url(#ieQppUU)" class="lne5q7jsk"/><g filter="url(#iv1lFfb)"><path fill="url(#i0u49vV)" class="j8btf4bnj"/><path fill="url(#iQjOwQt)" class="j8btf4bnj"/></g><path fill="url(#iSdbuZd)" class="mt8ta6b9y"/><path fill="url(#iaod2Ws)" class="mt8ta6b9y"/><path fill="url(#ivGKWkb)" class="mt8ta6b9y"/><path fill="url(#iYIfeae)" class="mt8ta6b9y"/><path fill="url(#i0W8UNd)" class="mt8ta6b9y"/><path fill="url(#igpgZGc)" class="gy6y_4bge"/><path fill="url(#iwP1wzb)" class="gy6y_4bge"/><path fill="url(#igpgZGc)" class="s0wxc_bst"/><path fill="url(#iwP1wzb)" class="s0wxc_bst"/><g filter="url(#iIOHfVb)"><path stroke="url(#iAuPDDc)" class="ub2wihfhw"/></g><defs><linearGradient id="i3FUVEd" x1="27.009" x2="12.019" y1="28.221" y2="19.827" gradientUnits="userSpaceOnUse"><stop class="mc141kmim"/><stop offset="1" class="q-6amzuqo"/></linearGradient><linearGradient id="itoTcEd" x1="1.99" x2="29.982" y1="19.038" y2="19.038" gradientUnits="userSpaceOnUse"><stop class="ah32vnkfr"/><stop offset="1" class="gub4hxbrv"/></linearGradient><linearGradient id="ieQppUU" x1="30.199" x2="29.153" y1="19.648" y2="19.648" gradientUnits="userSpaceOnUse"><stop class="u24c0qb0x"/><stop offset="1" class="ef69p1bwi"/></linearGradient><linearGradient id="i0u49vV" x1="24.987" x2="7.136" y1="6.984" y2="24.835" gradientUnits="userSpaceOnUse"><stop class="b0q6pm7mu"/><stop offset=".589" class="mcka7-bbd"/><stop offset="1" class="gvonp6ipi"/></linearGradient><linearGradient id="iSdbuZd" x1="22.12" x2="13.182" y1="13.472" y2="15.535" gradientUnits="userSpaceOnUse"><stop class="oy6067xru"/><stop offset="1" class="zrrcwbb_y"/></linearGradient><linearGradient id="ivGKWkb" x1="13.079" x2="15.974" y1="16.767" y2="13.872" gradientUnits="userSpaceOnUse"><stop class="kejfmdbko"/><stop offset=".481" class="nsufv7bxx"/><stop offset=".671" class="ygfb5ccyn"/></linearGradient><linearGradient id="iYIfeae" x1="29.681" x2="22.643" y1="22.386" y2="17.334" gradientUnits="userSpaceOnUse"><stop class="xxfr49bbn"/><stop offset="1" class="cbz7mezwl"/></linearGradient><linearGradient id="igpgZGc" x1="15.057" x2="23.995" y1="17.285" y2="8.347" gradientUnits="userSpaceOnUse"><stop class="juznobc-f"/><stop offset="1" class="ypx_bsb1m"/></linearGradient><linearGradient id="iwP1wzb" x1="13.682" x2="16.464" y1="18.097" y2="15.316" gradientUnits="userSpaceOnUse"><stop class="od64fdb3p"/><stop offset=".612" class="vrp2dlrjf"/><stop offset=".815" class="zkkiysb8n"/></linearGradient><linearGradient id="iAuPDDc" x1="7.776" x2="13.579" y1="23.764" y2="22.516" gradientUnits="userSpaceOnUse"><stop class="dzjbtxb4x"/><stop offset="1" class="vshfsjqvz"/></linearGradient><radialGradient id="istIHAe" cx="0" cy="0" r="1" gradientTransform="matrix(-19.2226 0 0 -5.27651 24.26 24.274)" gradientUnits="userSpaceOnUse"><stop class="bm2y0cwhb"/><stop offset="1" class="kijys3suk"/></radialGradient><radialGradient id="iQjOwQt" cx="0" cy="0" r="1" gradientTransform="matrix(-.70434 .59401 -.38087 -.4516 25.052 6.91)" gradientUnits="userSpaceOnUse"><stop class="tiylysb1q"/><stop offset=".993" class="k3wairh6y"/></radialGradient><radialGradient id="iaod2Ws" cx="0" cy="0" r="1" gradientTransform="rotate(-23.165 52.867 -30.276)scale(12.8413 20.2531)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="q0gz5lb2y"/><stop offset="1" class="db-p-k69c"/></radialGradient><radialGradient id="i0W8UNd" cx="0" cy="0" r="1" gradientTransform="rotate(-119.416 15.046 2.3)scale(13.489 22.5036)" gradientUnits="userSpaceOnUse"><stop class="jtvqakbza"/><stop offset=".611" class="jtvqakbza"/><stop offset="1" class="p1n-4_o0n"/></radialGradient><filter id="iAbpKYc" width="28.15" height="11.01" x="1.84" y="18.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.886275 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5055"/></filter><filter id="i5jo0Cc" width="19.717" height="7.568" x="6.78" y="20.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5055" stdDeviation=".5"/></filter><filter id="iv1lFfb" width="18.15" height="18.35" x="6.96" y="6.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.262745 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5055"/></filter><filter id="iIOHfVb" width="6.325" height="6.333" x="7.014" y="18.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5055" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:beach-with-umbrella" /></template>
<style>
.ah32vnkfr {
  stop-color: var(--svg-color--49ade8, #49ADE8);
}

.b0q6pm7mu {
  stop-color: var(--svg-color--a66459, #A66459);
}

.bm2y0cwhb {
  stop-color: var(--svg-color--d7731c, #D7731C);
}

.cbz7mezwl {
  stop-color: var(--svg-color--ee442b, #EE442B);
  stop-opacity: 0;
}

.db-p-k69c {
  stop-color: var(--svg-color--ea596b, #EA596B);
}

.dzjbtxb4x {
  stop-color: var(--svg-color--7f5951, #7F5951);
}

.ef69p1bwi {
  stop-color: var(--svg-color--7df8ff, #7DF8FF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gub4hxbrv {
  stop-color: var(--svg-color--6cedfd, #6CEDFD);
}

.gvonp6ipi {
  stop-color: var(--svg-color--7b4230, #7B4230);
}

.gy6y_4bge {
  d: path("M24.223 7.99c3.786 3.97 2.829 11.162-2.193 16.184l-3.576-3.578l.006-.002c4.96-4.959 7.479-10.518 5.763-12.603");
}

.iosi0o1kb {
  d: path("M5 29.034h21.98c1.66 0 3.01-1.35 3.01-3.01v-6a2 2 0 0 0-2-2h-24a2 2 0 0 0-2 2v6c0 1.67 1.35 3.01 3.01 3.01");
}

.j8btf4bnj {
  d: path("M24.24 6.974L7.11 24.104c-.2.2-.2.52 0 .72s.52.2.72 0l17.13-17.13c.2-.2.2-.52 0-.72s-.52-.2-.72 0");
}

.jtvqakbza {
  stop-color: var(--svg-color--ca3e4b, #CA3E4B);
  stop-opacity: 0;
}

.juznobc-f {
  stop-color: var(--svg-color--e5dfea, #E5DFEA);
}

.k3wairh6y {
  stop-color: var(--svg-color--c18e80, #C18E80);
  stop-opacity: 0;
}

.kejfmdbko {
  stop-color: var(--svg-color--cb3a43, #CB3A43);
}

.kijys3suk {
  stop-color: var(--svg-color--d7731c, #D7731C);
  stop-opacity: 0;
}

.lne5q7jsk {
  d: path("M27.99 17.034h-24a2 2 0 0 0-2 2v2h27.99v-2c0-1.1-.89-2-1.99-2");
}

.mc141kmim {
  stop-color: var(--svg-color--ffc250, #FFC250);
}

.mcc0s7zbt {
  d: path("M7.78 27.407c13.705 0 17.717-1.868 17.717-2.783S20.8 21.84 7.78 21.84z");
}

.mcka7-bbd {
  stop-color: var(--svg-color--8a3f42, #8A3F42);
}

.mt8ta6b9y {
  d: path("M22.81 24.944c.76.76 1.95.82 2.52.08c3.9-5.1 3.49-12.46-1.21-17.16s-12.08-5.12-17.18-1.22c-.74.56-.68 1.75.08 2.51l.76.76l7.579 7.643l6.681 6.617z");
}

.nsufv7bxx {
  stop-color: var(--svg-color--d92e49, #D92E49);
}

.od64fdb3p {
  stop-color: var(--svg-color--c9b9c9, #C9B9C9);
}

.oy6067xru {
  stop-color: var(--svg-color--ff6072, #FF6072);
}

.p1n-4_o0n {
  stop-color: var(--svg-color--ca3e4b, #CA3E4B);
}

.q-6amzuqo {
  stop-color: var(--svg-color--ffb000, #FFB000);
}

.q0gz5lb2y {
  stop-color: var(--svg-color--ea596b, #EA596B);
  stop-opacity: 0;
}

.s0wxc_bst {
  d: path("M23.95 7.717C19.979 3.937 12.8 4.894 7.78 9.914l3.55 3.578C16.295 8.53 21.862 6 23.95 7.717");
}

.tiylysb1q {
  stop-color: var(--svg-color--c18e80, #C18E80);
}

.u24c0qb0x {
  stop-color: var(--svg-color--7df8ff, #7DF8FF);
}

.ub2wihfhw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m7.389 24.368l5.575-5.583");
}

.vrp2dlrjf {
  stop-color: var(--svg-color--d4c9dc, #D4C9DC);
}

.vshfsjqvz {
  stop-color: var(--svg-color--7f5951, #7F5951);
  stop-opacity: 0;
}

.xxfr49bbn {
  stop-color: var(--svg-color--ee442b, #EE442B);
}

.ygfb5ccyn {
  stop-color: var(--svg-color--d92e49, #D92E49);
  stop-opacity: 0;
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

.zkkiysb8n {
  stop-color: var(--svg-color--d4c9dc, #D4C9DC);
  stop-opacity: 0;
}

.zrrcwbb_y {
  stop-color: var(--svg-color--ec3a51, #EC3A51);
}

</style>
