<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iktcwib3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:account-student" /></template>
<style>
.iktcwib3z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.004 8.033l-5.912-3.284q-1.092-.606-2.184 0L4.996 8.034Q3.839 8.677 3.839 10t1.157 1.967l1.254.696V17q0 .084.019.167q.018.082.055.158t.089.142t.118.119Q8.612 19.25 12 19.25t5.469-1.664q.065-.053.118-.119t.089-.142t.055-.158t.019-.167v-4.337l1.254-.697q1.157-.643 1.157-1.966t-1.157-1.967m-2.754 5.464v3.127Q14.628 17.75 12 17.75t-4.25-1.126v-3.127l3.158 1.754q1.092.606 2.184 0z");
}

</style>
