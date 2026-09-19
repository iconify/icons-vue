<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gtrx6bcwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kroger" /></template>
<style>
.gtrx6bcwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 20.662c0-4.84-3.584-13.245-12.732-13.245s-13.845 7.231-13.845 13.836a11.99 11.99 0 0 1-12.423 12m0-12.453v19.783m13.845 0l-6.324-9.604");
}

</style>
