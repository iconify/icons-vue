<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o53ml77sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-vertical-top" /></template>
<style>
.o53ml77sg {
  fill: currentColor;
  d: path("M7.692 20.5V7.058h2.039V20.5zm6.577-6V7.058h2.039V14.5zM3 4.48v-1h18v1z");
}

</style>
