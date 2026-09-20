<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8mo6rb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blinds-2-closed-outline-rounded" /></template>
<style>
.s8mo6rb9f {
  fill: currentColor;
  d: path("M6.435 20h11.111q.173 0 .27-.154q.096-.154 0-.307l-1.324-2.327h-1.28v.557q0 .213-.144.357t-.357.143q-.194 0-.347-.143q-.153-.144-.153-.357v-.557H7.49l-1.323 2.327q-.097.153 0 .307q.096.154.269.154m8.777-9.442h2.334q.173 0 .27-.154q.096-.154 0-.308L16.492 7.77h-1.28zM5.385 4q-.589 0-.987.398T4 5.385v1.384h16V5.391q0-.585-.398-.988T18.616 4zM4 6.77h16zm11.212 8.5h2.334q.173 0 .27-.145q.096-.144 0-.298l-1.324-2.346h-1.28zm-8.777 0h7.777v-2.79H7.489l-1.323 2.347q-.097.154 0 .298q.096.144.269.144m0-4.711h7.777V7.769H7.489l-1.323 2.327q-.097.154 0 .308q.096.154.269.154M6.596 21q-.666 0-1.14-.475t-.475-1.14V7.769H3.808q-.343 0-.576-.232T3 6.962V5.377q0-.99.696-1.684T5.385 3h13.23q.981 0 1.683.702T21 5.388v1.574q0 .343-.232.575t-.576.232H19v11.616q0 .666-.475 1.14t-1.14.475z");
}

</style>
