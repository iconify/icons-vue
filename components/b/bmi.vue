<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xragssrni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bmi" /></template>
<style>
.xragssrni {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 4q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 4t-.732 1.768T12 6.5Q9.5 6.5 9.5 4m4.25 3.5h-3.5q-2.319 0-3.157 1.637L5.615 11.6q-.639.975.074 1.892q.59.758 1.561.758q.47 0 .864-.212l-.344 2.756q-.296.707.106 1.31q.052.077.111.146H4.25q-2 0-2 2t2 2h15.5q.828 0 1.414-.586t.586-1.414t-.586-1.414t-1.414-.586h-3.737q.059-.069.111-.146q.402-.603.106-1.31l-.344-2.756q.394.212.864.212q.971 0 1.561-.758q.713-.917.074-1.892l-1.478-2.463Q16.069 7.5 13.75 7.5m-1.982 6.674l-.009-.06q-.009-.057-.009-.114q0 .1.018.174m.464 0q.018-.074.018-.174q0 .057-.009.114zm.286 4.076q-.255-.348-.267-.938L12 15.682l-.251 1.63q-.012.59-.267.938z");
}

</style>
