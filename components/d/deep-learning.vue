<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygyy3vddc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:deep-learning" /></template>
<style>
.ygyy3vddc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.379 4.879Q1.5 5.757 1.5 7q0 3 3 3q.649 0 1.157-.14L7.304 12l-1.647 2.14Q5.149 14 4.5 14q-1.243 0-2.121.879Q1.5 15.757 1.5 17q0 3 3 3q2.598 0 2.946-2.25h1.608Q9.402 20 12 20q3 0 3-3q0-.596-.118-1.073l2.495-1.56Q18.122 15 19.5 15q3 0 3-3t-3-3q-1.378 0-2.123.633l-2.495-1.56Q15 7.596 15 7q0-3-3-3q-2.598 0-2.946 2.25H7.446Q7.098 4 4.5 4q-1.243 0-2.121.879M7.446 7.75h1.608q.122.788.519 1.3L8.25 10.77L6.927 9.05q.397-.512.519-1.3m3.397 2.11Q11.351 10 12 10q1.378 0 2.123-.633l2.495 1.56Q16.5 11.404 16.5 12t.118 1.073l-2.495 1.56Q13.378 14 12 14q-.649 0-1.157.14L9.196 12zm-1.27 5.09q-.397.512-.519 1.3H7.446q-.122-.788-.519-1.3l1.323-1.72z");
}

</style>
