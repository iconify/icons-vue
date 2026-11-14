<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a4_e5gszu"/><path class="rvsjzmote"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:county" /></template>
<style>
.a4_e5gszu {
  d: path("m13.719 20.809l-1.358.151q-.361.04-.708-.067l-5.292-1.628q-.2-.061-.379-.168q-.18-.107-.33-.253q-.149-.146-.26-.323t-.177-.375l-1.647-4.942Q3.5 13 3.483 12.785l-.399-5.192q-.009-.122-.002-.245q.008-.122.033-.242q.024-.12.066-.236q.041-.115.098-.224t.128-.208t.157-.189q.084-.088.181-.164t.202-.138l4.369-2.548q.161-.094.338-.152t.363-.077q.186-.02.371.001q.186.02.363.079l4.746 1.582q.246.082.505.09t.509-.061l2.946-.804q.093-.025.188-.04t.192-.02q.096-.004.192.002t.191.023t.187.043t.182.064t.173.084q.085.046.163.102q.079.055.151.119t.137.135q.065.072.121.15q.057.078.105.162q.047.083.085.172t.067.18q.028.093.046.187q.018.095.025.191l.308 4.003q.03.386-.106.749l-.413 1.101");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rvsjzmote {
  d: path("M18 21.75c-2-2.25-3-3.75-3-5a3 3 0 0 1 6 0c0 1.25-1 2.75-3 5");
}

</style>
