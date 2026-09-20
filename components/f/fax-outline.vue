<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc7gp0bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fax-outline" /></template>
<style>
.kc7gp0bfu {
  fill: currentColor;
  d: path("M5 20.5q-1.042 0-1.77-.73q-.73-.728-.73-1.77v-7q0-1.042.73-1.77Q3.957 8.5 5 8.5q.617 0 1.132.275t.882.725H8.5V4.846h9V9.5H19q1.042 0 1.77.73q.73.728.73 1.77v7.5H7.014q-.368.45-.882.725T5 20.5m0-1q.617 0 1.059-.441Q6.5 18.617 6.5 18v-7q0-.617-.441-1.059Q5.617 9.5 5 9.5t-1.059.441Q3.5 10.383 3.5 11v7q0 .617.441 1.059q.442.441 1.059.441m4.5-10h7V5.846h-7zm-2 9h13V12q0-.617-.441-1.059Q19.617 10.5 19 10.5H7.5zm8.213-4.788Q16 13.425 16 13t-.288-.712T15 12t-.712.288T14 13t.288.713T15 14t.713-.288m3 0Q19 13.426 19 13t-.288-.712T18 12t-.712.288T17 13t.288.713T18 14t.713-.288m-3 3Q16 16.426 16 16t-.288-.712T15 15t-.712.288T14 16t.288.713T15 17t.713-.288m3 0Q19 16.426 19 16t-.288-.712T18 15t-.712.288T17 16t.288.713T18 17t.713-.288M9 17h4v-5H9zm-1.5 1.5v-8z");
}

</style>
