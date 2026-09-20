<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utozjwial"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-right-outline" /></template>
<style>
.utozjwial {
  fill: currentColor;
  d: path("M17.675 13.06Q20 11.86 20 10.137T17.675 7.2T12 5.984T6.325 7.2T4 10.136t2.325 2.924T12 14.262t5.675-1.2m-1.406 1.597v2.727q0 .666-.474 1.14T14.654 19H9.327q-.667 0-1.141-.475t-.475-1.14v-2.727q-2.12-.666-3.416-1.851T3 10.133Q3 7.99 5.62 6.486t6.376-1.505t6.38 1.505T21 10.133q0 1.488-1.295 2.674t-3.436 1.85m-5.902-1.891h.77v-2.012h.911l1.242 2.012h.893l-1.43-2.215q.5-.199.763-.534t.263-.844q0-.73-.469-1.127q-.468-.396-1.377-.396h-1.566zm.77-2.685V8.37h.717q.573 0 .852.213t.278.625q0 .439-.269.656q-.269.216-.848.216z");
}

</style>
