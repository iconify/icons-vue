<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdu5_u5oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:equalizer-rounded" /></template>
<style>
.pdu5_u5oo {
  fill: currentColor;
  d: path("M5.434 18.566Q5 18.133 5 17.5v-2.808q0-.632.434-1.066q.433-.434 1.066-.434t1.066.434T8 14.692V17.5q0 .633-.434 1.066Q7.133 19 6.5 19t-1.066-.434M12 19q-.633 0-1.066-.434q-.434-.433-.434-1.066v-11q0-.633.434-1.066Q11.367 5 12 5t1.066.434T13.5 6.5v11q0 .633-.434 1.066Q12.633 19 12 19m4.434-.434Q16 18.133 16 17.5v-6.192q0-.633.434-1.067q.433-.433 1.066-.433t1.066.433q.434.434.434 1.067V17.5q0 .633-.434 1.066Q18.133 19 17.5 19t-1.066-.434");
}

</style>
