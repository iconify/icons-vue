<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plttebb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-r3-rounded" /></template>
<style>
.plttebb-p {
  fill: currentColor;
  d: path("M12 5.442L10 2.77h4zm4.27 11.216v2.746q0 .671-.473 1.143q-.472.472-1.143.472H9.327q-.671 0-1.143-.472t-.472-1.143v-2.746q-2.121-.666-3.417-1.851T3 12.133q0-2.14 2.624-3.646T12 6.98t6.376 1.506T21 12.133q0 1.488-1.295 2.674t-3.436 1.85m-5.244-2.003q.112-.112.112-.273v-1.627h.911l1.13 1.837q.05.08.132.127q.08.048.186.048q.223 0 .332-.199q.109-.198-.034-.384l-1.04-1.637q.5-.194.762-.528t.263-.845q0-.73-.468-1.127q-.469-.396-1.378-.396H10.77q-.162 0-.283.121t-.12.283v4.327q0 .161.11.273q.113.112.274.112t.273-.112m.111-2.573v-1.71h.718q.573 0 .852.213t.278.626q0 .438-.269.655q-.269.216-.848.216z");
}

</style>
