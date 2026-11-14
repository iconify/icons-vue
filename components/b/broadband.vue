<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dz90ambxe"/><path class="x8057ux6p"/><path class="tvxnjffkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broadband" /></template>
<style>
.dz90ambxe {
  d: path("M12.321 19.5H7.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q6 17.836 6 17.75v-6.987q0-.18.037-.357t.109-.342t.176-.313q.105-.147.237-.27l5.25-4.875q.06-.056.125-.106t.134-.093t.143-.081q.073-.037.149-.067t.155-.052t.159-.038q.081-.015.162-.023q.082-.008.164-.008t.164.008q.081.008.162.023q.08.015.159.038q.079.022.155.052t.149.067t.143.081t.134.093t.125.106l5.25 4.875q.132.123.237.27t.176.313q.072.165.109.342t.037.357v1.591M2.5 14H6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tvxnjffkg {
  d: path("M16.75 18.5a1.75 3.5 0 1 0 3.5 0a1.75 3.5 0 1 0-3.5 0m-1.75 0h7");
}

.x8057ux6p {
  d: path("M15 18.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
