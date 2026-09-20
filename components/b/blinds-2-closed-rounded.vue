<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsv3zcb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blinds-2-closed-rounded" /></template>
<style>
.nsv3zcb8c {
  fill: currentColor;
  d: path("M6.435 20h11.111q.173 0 .27-.154q.096-.154 0-.307l-1.324-2.327h-1.28v.557q0 .214-.144.357t-.357.143q-.194 0-.347-.143t-.153-.357v-.557H7.49l-1.323 2.327q-.097.153 0 .307q.096.154.269.154m8.777-9.442h2.334q.173 0 .27-.154q.096-.154 0-.308L16.492 7.77h-1.28zm0 4.711h2.334q.173 0 .27-.144q.096-.144 0-.298l-1.324-2.346h-1.28zm-8.777 0h7.777v-2.788H7.489l-1.323 2.346q-.097.154 0 .298q.096.144.269.144m0-4.711h7.777V7.769H7.489l-1.323 2.327q-.097.154 0 .308q.096.154.269.154M6.596 21q-.671 0-1.143-.472t-.472-1.144V7.77H3.808q-.348 0-.578-.23T3 6.961V5.384q0-1 .692-1.692T5.385 3h13.23q.981 0 1.683.702T21 5.385v1.577q0 .348-.23.578t-.578.23H19v11.615q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
