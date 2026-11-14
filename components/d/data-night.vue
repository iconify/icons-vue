<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sav8nibjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-night" /></template>
<style>
.sav8nibjs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.912 7.397q.065.123.082.26q.017.138-.016.273q-.036.145-.124.265q-.089.12-.216.197q-.128.077-.275.1q-.148.022-.293-.014q-4.793-1.183-8.284 2.308T8.478 19.07q.033.135.016.273q-.017.137-.082.26q-.035.065-.082.122t-.104.104t-.122.082t-.136.057t-.144.028q-.073.008-.147 0q-.073-.007-.144-.028t-.136-.056q-4.111-2.193-4.796-6.801t2.608-7.902t7.902-2.608t6.801 4.796M18.5 13.25q-3.75 0-3.75 2.25v4q0 2.25 3.75 2.25t3.75-2.25v-4q0-2.25-3.75-2.25m0 3q-2.25 0-2.25-.75t2.25-.75t2.25.75t-2.25.75m-2.25 3.25v-2.054q.872.304 2.25.304t2.25-.304V19.5q0 .75-2.25.75t-2.25-.75");
}

</style>
