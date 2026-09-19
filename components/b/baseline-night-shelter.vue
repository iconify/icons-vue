<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu82cwb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-night-shelter" /></template>
<style>
.lu82cwb9e {
  fill: currentColor;
  d: path("M12 3L4 9v12h16V9zm-2.25 9.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5M17 18h-1v-1.5H8V18H7v-7h1v4.5h3.5V12H15c1.1 0 2 .9 2 2z");
}

</style>
