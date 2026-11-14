<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u62s9rbpo"/><path class="nfnd-ablc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cashierless-store" /></template>
<style>
.nfnd-ablc {
  d: path("M3 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253t.175.236t.198.218t.218.198t.236.175t.253.152t.266.126t.277.099t.286.071q.144.029.291.044T6 12q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198t.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286q.029-.144.044-.291T9 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044Q11.853 12 12 12t.294-.014q.147-.015.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198q.105-.104.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286t.044-.291Q15 9.147 15 9q0 .23.035.457t.104.447q.07.219.171.425t.234.394q.132.189.292.354q.159.166.342.306q.182.14.384.25t.418.188m2.116-.028q.209-.082.404-.195q.194-.112.37-.252t.329-.305t.28-.351t.224-.388q.097-.203.164-.418q.066-.214.099-.437Q21 9.225 21 9M6.5 14.5h4v6h-4Zm8 3.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm0 3.5l7-7");
}

.u62s9rbpo {
  d: path("m3 9l1.5-5h15L21 9M4.5 11v9.5h7.1m7.9-8.6V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
