<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_6hfqbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:conical-hat" /></template>
<style>
.y_6hfqbwf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.443 3.998l-9 10q-.118.131-.166.301q-.04.144-.021.292q.018.148.091.278t.191.222t.261.132q1.975.548 3.95.861Q9.3 19.5 12 19.5t5.251-3.416q1.975-.313 3.95-.861q.17-.048.301-.166q.111-.099.175-.234t.072-.284t-.042-.289q-.05-.141-.15-.252l-9-10q-.026-.029-.055-.055q-.111-.1-.252-.15q-.14-.05-.289-.042t-.284.072t-.234.175m3.623 12.361Q13.489 18 12 18t-3.066-1.641q3.066.283 6.132 0");
}

</style>
