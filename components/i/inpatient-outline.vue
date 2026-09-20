<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w76untjll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:inpatient-outline" /></template>
<style>
.w76untjll {
  fill: currentColor;
  d: path("M4.846 21q-.671 0-1.143-.472t-.472-1.144V4.616q0-.672.472-1.144T4.846 3h7.77q.67 0 1.143.472q.472.472.472 1.144v14.769q0 .67-.472 1.143q-.472.472-1.143.472zm-.615-9.206q.392-.39.902-.592T6.23 11h5q.588 0 1.098.202t.902.592V4.615q0-.269-.173-.442T12.616 4h-7.77q-.269 0-.442.173t-.173.443zm3.434-3.228Q7.23 8.133 7.23 7.5t.434-1.066Q8.098 6 8.73 6t1.066.434t.434 1.066t-.434 1.066T8.731 9t-1.066-.434m11.124 6.222L16 12l2.789-2.789l.707.689l-1.594 1.6h3.887v1h-3.887l1.594 1.6zM4.845 20h7.77q.269 0 .442-.173t.173-.442V14q0-.825-.588-1.412T11.231 12h-5q-.825 0-1.413.588T4.231 14v5.385q0 .269.173.442t.442.173m3.385-1.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2zM4.846 20h-.615h9z");
}

</style>
