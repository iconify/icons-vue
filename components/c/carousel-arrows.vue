<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mei2axxgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carousel-arrows" /></template>
<style>
.mei2axxgh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.898 9.378L3.368 12l1.53 2.622q.075.129.095.277t-.018.292t-.128.263t-.219.194t-.277.095t-.292-.018t-.263-.128t-.194-.219l-1.75-3q-.05-.086-.076-.182T1.75 12t.026-.196t.076-.182l1.75-3q.037-.064.086-.119t.108-.1t.125-.077t.138-.051t.145-.024q.074-.004.147.006t.143.034t.134.061q.129.075.219.194t.128.263t.018.292t-.095.277m17.25 2.244l-1.75-3q-.075-.129-.194-.219t-.263-.128t-.292-.018t-.277.095t-.219.194t-.128.263t-.018.292t.095.277L20.632 12l-1.53 2.622q-.075.129-.095.277t.018.292t.128.263t.219.194t.277.095t.292-.018t.263-.128t.194-.219l1.75-3q.05-.086.076-.182T22.25 12t-.026-.196t-.076-.182M12 10q-2 0-2 2t2 2t2-2t-2-2m-6 2q0-1.5 1.5-1.5T9 12t-1.5 1.5T6 12m9 0q0-1.5 1.5-1.5T18 12t-1.5 1.5T15 12");
}

</style>
