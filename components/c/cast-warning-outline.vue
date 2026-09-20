<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkuyssbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cast-warning-outline" /></template>
<style>
.bkuyssbvw {
  fill: currentColor;
  d: path("M3 17.077q.789 0 1.356.567T4.923 19H3zm0-3.385q2.214 0 3.76 1.548Q8.309 16.787 8.309 19h-1q0-1.786-1.261-3.028T3 14.692zm0-3.769q1.89 0 3.535.709q1.644.709 2.884 1.949t1.95 2.885t.708 3.534h-1q0-1.683-.636-3.147q-.635-1.464-1.732-2.562T6.147 11.56Q4.683 10.923 3 10.923zM19.385 19H14.46q0-.25-.008-.5t-.045-.5h4.977q.269 0 .442-.173t.173-.442v-4.896q.28-.08.521-.201q.24-.122.479-.255v5.352q0 .67-.472 1.143q-.472.472-1.143.472M3 7.539v-.923q0-.672.472-1.144T4.616 5h7.165q-.073.244-.1.485q-.027.24-.046.515h-7.02q-.269 0-.442.173T4 6.616v.976q-.25-.036-.5-.045q-.25-.008-.5-.008m12.165 1.72Q14 8.094 14 6.423t1.165-2.835T18 2.423t2.836 1.165T22 6.423t-1.164 2.836T18 10.423t-2.835-1.164M18 8.846q.2 0 .33-.13q.132-.131.132-.331t-.131-.331T18 7.923t-.33.13t-.132.332t.131.33q.131.131.331.131M17.616 7h.769V4h-.77z");
}

</style>
