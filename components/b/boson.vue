<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedBoson0)" clip-rule="evenodd" class="m2_1osbyn"/><defs><linearGradient id="tokenBrandedBoson0" x1="19.222" x2="4.778" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="rb08y7syp"/><stop offset="1" class="b_6rjcc_b"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:boson" /></template>
<style>
.b_6rjcc_b {
  stop-color: var(--svg-color--5df6bd, #5DF6BD);
}

.ft5dv1b6b {
  fill: none;
}

.m2_1osbyn {
  fill-rule: evenodd;
  d: path("M2 5.056h20v13.889H2zm1.667 1.666h16.666v10.556H3.667zm15.555 9.445h-.089a4.06 4.06 0 0 1-3.46-1.962c-.39.412-1.134.978-1.973.978c-.983 0-1.605-.855-1.739-1.172c-.133-.305-.261-.694-.4-1.1c-.383-1.128-.811-2.389-1.411-2.389c-.467 0-.956 1.128-1.25 2.056a4.106 4.106 0 0 1-4.122 3.589v-1.528h.083A2.61 2.61 0 0 0 7.45 12a2.61 2.61 0 0 0-2.672-2.639V7.833h.083A4.06 4.06 0 0 1 8.406 9.94c.316-.483.922-1.1 1.744-1.1c1.017 0 1.756.5 1.972 1.111l.245.722c.416 1.278.922 2.823 1.639 2.823c.65 0 .927-1.24 1.1-2.134a4.106 4.106 0 0 1 4.116-3.528v1.528h-.089A2.61 2.61 0 0 0 16.55 12a2.61 2.61 0 0 0 1.648 2.455c.325.13.674.192 1.024.184z");
}

.rb08y7syp {
  stop-color: var(--svg-color--1ef6ad, #1EF6AD);
}

</style>
