<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7v4kcb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heart-broken-rounded" /></template>
<style>
.f7v4kcb5a {
  fill: currentColor;
  d: path("M11.415 19.706q-.3-.125-.517-.337q-2.263-2.207-3.78-3.845T4.685 12.63t-1.3-2.243T3 8.5q0-2.089 1.456-3.544T8 3.5q1.4 0 2.477.493q1.077.494.785 1.501l-1.08 3.789q-.124.461.106.839t.633.378h1.964l-.554 5.966q-.025.2.162.224t.238-.15l2.1-6.817q.13-.461-.092-.842t-.627-.381h-1.958l1.275-3.813q.237-.721.987-.954t1.546-.233q2.088 0 3.544 1.456T20.962 8.5q0 .889-.41 1.886q-.41.999-1.33 2.28t-2.41 2.918t-3.674 3.785q-.217.231-.51.347q-.291.115-.603.115t-.61-.125");
}

</style>
