<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pctbq3zpw"/><path class="r1x844bjw"/><path class="cry8lfb2t"/><path class="objexznzi"/><path class="e_3m-5bsy"/><path class="eo12nb7ph"/><path class="w056dubvn"/><path fill="url(#tokenBrandedAngle0)" class="qjbmcn0eq"/><path class="kx8mkh0yv"/><defs><linearGradient id="tokenBrandedAngle0" x1="12" x2="12" y1="3.667" y2="20.327" gradientUnits="userSpaceOnUse"><stop class="uro8e3bht"/><stop offset="1" class="iszhw2bsw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:angle" /></template>
<style>
.cry8lfb2t {
  fill: var(--svg-color--f2e2d8, #F2E2D8);
  d: path("m3.667 16.261l4.166 4.072L7 18.317l-5-4.884l1.667 2.834z");
}

.e_3m-5bsy {
  fill: var(--svg-color--ffe6d6, #FFE6D6);
  d: path("m12 16.261l4.167 4.072l.833-2.016l-5-4.884v2.834z");
}

.eo12nb7ph {
  fill: var(--svg-color--131620, #131620);
  d: path("M12.084 13.406a.14.14 0 0 1 .15.033l4.86 4.778c.045.038.056.1.034.155l-.845 1.878a.14.14 0 0 1-.1.08a.14.14 0 0 1-.123-.035l-4.015-3.834a.14.14 0 0 1-.045-.094v-2.834a.14.14 0 0 1 .084-.127m-.084.26v2.39l4.111 3.894l.722-1.6z");
}

.ft5dv1b6b {
  fill: none;
}

.iszhw2bsw {
  stop-color: var(--svg-color--ffcaa3, #FFCAA3);
}

.kx8mkh0yv {
  fill: var(--svg-color--131620, #131620);
  d: path("M11.906 3.706a.14.14 0 0 1 .189 0l9.86 9.627a.14.14 0 0 1 .032.155a.14.14 0 0 1-.031.045l-4.861 4.884c-.056.055-.14.055-.19 0L12 13.627l-4.9 4.79a.134.134 0 0 1-.194 0l-4.861-4.884a.14.14 0 0 1 0-.2zM12 4l-9.666 9.433L7 18.123l4.906-4.79c.055-.055.139-.055.189 0L17 18.123l4.667-4.69z");
}

.objexznzi {
  fill: var(--svg-color--131620, #131620);
  d: path("M2.056 13.322a.14.14 0 0 1 .178.011l4.86 4.89a.1.1 0 0 1 .034.044l.833 1.872a.139.139 0 0 1-.222.155l-4.167-3.933a.1.1 0 0 1-.027-.028L2.017 13.5a.14.14 0 0 1 .039-.178m.733.945l.989 1.91l3.667 3.584l-.561-1.361l-4.095-4.139z");
}

.pctbq3zpw {
  fill: var(--svg-color--131620, #131620);
  d: path("M11.906 8.022a.14.14 0 0 1 .189 0l8.333 8.145a.14.14 0 0 1 0 .194l-4.167 3.933a.14.14 0 0 1-.189 0L12 16.461l-4.072 3.833a.14.14 0 0 1-.189 0l-4.166-3.933a.14.14 0 0 1 0-.194zm.094.295L3.867 16.26L7.834 20l4.072-3.833c.055-.056.139-.056.189 0L16.167 20l3.966-3.739z");
}

.qjbmcn0eq {
  d: path("m2 13.433l10-9.766l10 9.766l-5 4.889l-5-4.889l-5 4.889z");
}

.r1x844bjw {
  fill: var(--svg-color--131620, #131620);
  d: path("m12 16.261l-4.167 4.072L7 18.317l5-4.884v2.834z");
}

.uro8e3bht {
  stop-color: var(--svg-color--f6958c, #F6958C);
}

.w056dubvn {
  fill: var(--svg-color--131620, #131620);
  d: path("m20.333 16.261l-4.166 4.072l.833-2.016l5-4.884l-1.667 2.834z");
}

</style>
