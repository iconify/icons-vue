<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgfqpogtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bracket" /></template>
<style>
.bgfqpogtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.719 19.518c-.224-.242-.398-.589-.469-1.018L11.5 15c-.25-1-1.75-1-2 0l-.75 3.5C8.5 20 7 20.5 6.5 19c-.75-2-.75-5-1.5-7c-1-2.5-1.5-5.5 0-7.5s4-1 5.5-.5c1.5-.5 4-1.5 5.5.5s1 5 0 7.5a9 9 0 0 0-.297.981M17.25 15.5h2.5a1.75 1.75 0 0 1 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75v-2.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
