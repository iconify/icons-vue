<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrssu9nhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-r3-outline-rounded" /></template>
<style>
.xrssu9nhx {
  fill: currentColor;
  d: path("M12 5.442L10 2.77h4zm5.675 9.622Q20 13.86 20 12.136T17.675 9.2T12 7.985T6.325 9.199T4 12.136t2.325 2.928Q8.65 16.267 12 16.267t5.675-1.203m-1.406 1.594v2.746q0 .666-.474 1.14t-1.141.475H9.327q-.667 0-1.141-.474t-.475-1.141v-2.746q-2.12-.666-3.416-1.851T3 12.133Q3 9.99 5.62 8.486t6.376-1.505t6.38 1.505T21 12.133q0 1.488-1.295 2.674t-3.436 1.85m-5.244-2.007q.112-.115.112-.27v-1.626h.911l1.13 1.837q.05.08.133.127q.082.048.185.048q.23 0 .335-.199q.106-.198-.037-.384l-1.04-1.637q.5-.194.762-.53t.263-.843q0-.73-.468-1.127q-.469-.396-1.378-.396h-1.164q-.16 0-.281.121q-.12.121-.12.283v4.327q0 .154.11.269q.113.116.274.116t.273-.116m.112-2.57v-1.709h.717q.573 0 .852.213t.279.625q0 .439-.27.656q-.269.216-.848.216z");
}

</style>
