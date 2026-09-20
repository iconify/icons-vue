<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wysfd55hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:leaderboard" /></template>
<style>
.wysfd55hw {
  fill: currentColor;
  d: path("M3.77 20V10h4.153v10zm5.96 0V4h4.54v16zm6.347 0v-8h4.154v8z");
}

</style>
