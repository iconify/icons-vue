<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk-x42bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bean-bag-toss" /></template>
<style>
.hk-x42bez {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.94 1.861l1.932.518q2.414.647 1.767 3.061l-.518 1.932q-.647 2.414-3.061 1.767l-1.932-.518q-2.414-.647-1.767-3.061l.518-1.932q.647-2.414 3.061-1.767m-6.041 1.146q-5.893.803-8.57 6.158q-.067.133-.077.282q-.011.149.036.29q.048.142.145.254q.098.113.232.18q.066.033.137.052q.071.02.145.025t.147-.004t.143-.032t.134-.06t.12-.085t.101-.107t.079-.125q2.323-4.645 7.43-5.342q.148-.02.277-.095t.219-.194t.128-.263t.018-.292t-.095-.277t-.194-.219t-.263-.128t-.292-.018M5.848 12.68l-2.842 6q-.589 1.244.147 2.407t2.112 1.163h10.628q1.582-.001 2.259-1.43l2.842-6q.589-1.244-.147-2.407t-2.112-1.163H8.107q-1.582.001-2.259 1.43M13 14.25q3.75 0 3.75 2.5T13 19.25t-3.75-2.5t3.75-2.5");
}

</style>
