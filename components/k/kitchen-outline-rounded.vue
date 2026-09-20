<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke9u57bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:kitchen-outline-rounded" /></template>
<style>
.ke9u57bxc {
  fill: currentColor;
  d: path("M8.336 7.856q-.144-.143-.144-.356V5.884q0-.212.144-.356t.357-.143t.356.143t.143.357V7.5q0 .213-.144.356Q8.904 8 8.692 8q-.213 0-.357-.144m0 8.116q-.143-.144-.143-.356v-3.347q0-.212.144-.356t.357-.144t.356.144t.143.356v3.346q0 .213-.144.357q-.144.143-.356.143q-.213 0-.357-.143M6.616 21q-.666 0-1.14-.475T5 19.386V4.615q0-.666.475-1.14T6.615 3h10.77q.666 0 1.14.475T19 4.615v14.77q0 .666-.475 1.14t-1.14.475zm0-1h10.77q.269 0 .442-.173t.173-.442v-9H6v9q0 .269.173.442t.443.173M6 9.385h12v-4.77q0-.269-.173-.442T17.385 4H6.615q-.269 0-.442.173T6 4.616z");
}

</style>
