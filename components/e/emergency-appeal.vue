<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcjwqrb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-appeal" /></template>
<style>
.xcjwqrb5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5h3l6.5-4V16L7 12H4a1.5 1.5 0 0 1-1.5-1.5V9A1.5 1.5 0 0 1 4 7.5M6 12l1.25 5.5m9-10.25a3.5 3.5 0 0 1 0 5m2.5-7.75q.166.197.316.406q.151.209.286.429q.135.219.253.448t.22.466q.101.236.184.48q.084.244.149.493q.066.249.113.502q.047.254.075.51t.038.513q.009.258-.001.515t-.038.513q-.029.256-.076.51q-.047.253-.113.502t-.149.492t-.186.481q-.101.236-.22.465M18 14.5V18m0 3h.01");
}

</style>
