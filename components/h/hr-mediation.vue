<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jidp5cq3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hr-mediation" /></template>
<style>
.jidp5cq3j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5q0-1.346.952-2.298T5 1.75h14q1.346 0 2.298.952T22.25 5v10q0 3.25-3.25 3.25h-7.743L6.96 21.592q-.058.045-.124.078q-.066.034-.137.053q-.071.02-.145.025t-.147-.004t-.143-.032q-.071-.024-.135-.06q-.064-.037-.12-.085t-.101-.107q-.077-.098-.117-.217q-.041-.118-.041-.243v-2.75H5q-3.25 0-3.25-3.25zm12.125 1.5h-3.75Q8.75 6.5 8.75 7.875t1.375 1.375h3.75q1.375 0 1.375-1.375T13.875 6.5m-3.75 4q-1.375 0-1.375 1.375t1.375 1.375h3.75q1.375 0 1.375-1.375T13.875 10.5z");
}

</style>
