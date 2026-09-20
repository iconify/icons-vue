<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be6kk-bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:high-quality-off" /></template>
<style>
.be6kk-bsf {
  fill: currentColor;
  d: path("M17.385 14.727v-4.342q0-.444-.317-.761q-.316-.316-.76-.316h-2.231q-.425 0-.732.311t-.345.742l.885.866V10.5q0-.115.096-.212t.211-.096h2q.116 0 .212.096q.096.097.096.212v3.342zm-10.77-.035H7.5v-2h2.616v2H11v-3.5l-.885-.884v1.5H7.5v-2.5h-.885zm14.173 3.439L7.658 5h11.727q.69 0 1.153.463T21 6.616v10.746q0 .217-.04.41t-.172.359M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h.193l9.692 9.692h-1.415L2.36 3.97l.708-.707l17.15 17.15l-.707.707L17.38 19z");
}

</style>
