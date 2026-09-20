<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGeciwQcBX)" class="z_vy6zb1g"/><defs><linearGradient id="SVGeciwQcBX" x1="15.686" x2="5.921" y1="7.018" y2="10.375" gradientUnits="userSpaceOnUse"><stop class="htf9l1c4b"/><stop offset=".28" class="ou5k7ebjw"/><stop offset=".5" class="welg51r1o"/><stop offset="1" class="brdc_achv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:1art" /></template>
<style>
.brdc_achv {
  stop-color: var(--svg-color--a672dc, #a672dc);
}

.ft5dv1b6b {
  fill: none;
}

.htf9l1c4b {
  stop-color: var(--svg-color--836df7, #836df7);
}

.ou5k7ebjw {
  stop-color: var(--svg-color--2e8aca, #2e8aca);
}

.welg51r1o {
  stop-color: var(--svg-color--4978d6, #4978d6);
}

.z_vy6zb1g {
  d: path("M14.179 3.276c1.098-.696 2.592.006 2.622 1.212v14.988c0 .84-.876 1.524-1.8 1.524c-.912 0-1.782-.666-1.8-1.5V7.956s-2.442 1.518-3.618 2.124c-.138.072-.288.12-.462.126c-.204 0-.42-.036-.63-.114c-.69-.264-1.32-.93-1.29-1.692c.017-.444.216-.864.654-1.152l.024-.018l6.3-3.96z");
}

</style>
