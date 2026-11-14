<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz5oivb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-peen-hammer" /></template>
<style>
.fz5oivb3i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.475 3.515l3.889 3.889q.733.732.733 1.768l-.001.079Q22 9.298 22 12.25q0 3-3 3q-2.936 0-2.999-2.874q-.055.003-.111.003q-.595 0-1.089-.242q-.165.41-.503.748L7.58 19.601q-1.591 1.591-3.181 0t0-3.181l6.717-6.718q.283-.284.616-.445l-1.499-1.5Q9.5 7.025 9.5 5.99q0-1.036.733-1.768l.707-.707q.732-.733 1.767-.733q1.036 0 1.768.733");
}

</style>
