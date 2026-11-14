<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7589sbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fertility" /></template>
<style>
.k7589sbzz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.288 4.822q-.315-.233-.614-.592q-.4-.48-.674-.48q-1.589 0-2.171-1.165q-.033-.066-.052-.137q-.02-.071-.025-.145t.004-.147t.032-.143t.06-.134t.085-.12t.107-.101q.059-.046.125-.079t.137-.052t.145-.025t.147.004t.143.032q.07.024.134.06q.065.037.12.085q.056.049.101.107q.046.059.079.125q.168.335.829.335q.976 0 1.826 1.02q.4.48.674.48q.2 0 .373.099Q7.37 3.75 8 3.75q1.159 0 2.007.565Q11 4.977 11 6t-.993 1.685Q9.159 8.25 8 8.25Q5 8.25 5 6q0-.697.288-1.178M9.02 9.02q-2.27 2.27-2.27 5.48t2.27 5.48t5.48 2.27t5.48-2.27t2.27-5.48t-2.27-5.48t-5.48-2.27t-5.48 2.27m1.73 5.48q0-3.75 3.75-3.75t3.75 3.75t-3.75 3.75t-3.75-3.75");
}

</style>
