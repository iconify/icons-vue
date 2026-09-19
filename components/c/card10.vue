<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jsn2tbc0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:card10" /></template>
<style>
.jsn2tbc0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.657 24l5.643-8.213v21.042q0 1.542 1.543 1.542H38.37q5.13 0 5.129-5.13V14.759q0-5.13-5.13-5.129h-7.185v6.157h2.57q3.075 0 3.074 3.085v9.23q0 3.084-3.073 3.084h-9.242q-3.084 0-3.084-3.084v-9.23q0-3.085 3.084-3.085h2.57V9.63H9.63q-5.13 0-5.129 5.13v18.483q0 5.129 5.13 5.129h2.992");
}

</style>
