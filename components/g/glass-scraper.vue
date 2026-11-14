<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd28_oa6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glass-scraper" /></template>
<style>
.hd28_oa6a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.005 2.631l6.364 6.364q1.591 1.59 0 3.181l-.706.708q-.66.66-1.592.66t-1.591-.66l-2.652-2.651l-.937.937q.822 1.298-.477 2.597l-6.187 6.188q-.659.66-1.591.66t-1.592-.66q-.659-.659-.659-1.591t.66-1.592l6.188-6.186q1.299-1.299 2.597-.477l.937-.937l-2.651-2.652q-.66-.659-.66-1.591t.66-1.591l.708-.708q1.59-1.59 3.181.001");
}

</style>
