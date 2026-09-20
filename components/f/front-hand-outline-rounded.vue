<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_-i6sb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:front-hand-outline-rounded" /></template>
<style>
.v_-i6sb1k {
  fill: currentColor;
  d: path("M13.184 2.644q.143.144.143.356v8q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356V3q0-.213.144-.356q.144-.144.356-.144q.213 0 .357.144m-3.674 1q.144.143.144.356v7q0 .213-.144.356q-.144.144-.357.144t-.356-.144T8.654 11V4q0-.213.144-.356t.356-.144t.356.144M12.504 22q-3.131 0-5.317-2.184T5 14.5v-9q0-.213.144-.356T5.501 5t.356.144T6 5.5v9q0 2.725 1.888 4.613T12.5 21t4.613-1.888T19 14.5v-4h-.5q-.617 0-1.059.441Q17 11.383 17 12v2.116q0 .343-.232.575q-.233.232-.576.232h-1.115q-1.056 0-1.778.722t-.722 1.778v.5q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356v-.5q0-1.457 1.021-2.479q1.021-1.021 2.479-1.021H16V5q0-.213.144-.356t.357-.144t.356.144T17 5v5.06q.308-.268.685-.414T18.5 9.5h.692q.344 0 .576.232t.232.576V14.5q0 3.132-2.183 5.316T12.504 22M13 15.25");
}

</style>
