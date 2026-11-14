<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuub9lyyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kick-target-paddle" /></template>
<style>
.yuub9lyyc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.127 4.873Q13.003 2.75 10 2.75T4.873 4.873T2.75 10v4q0 3.003 2.123 5.127T10 21.25t5.127-2.123q1.077-1.078 1.607-2.381q3.891-.133 3.891-4.746t-3.891-4.746q-.53-1.303-1.607-2.381M6.995 8.995Q8.24 7.75 10 7.75t3.005 1.245T14.25 12t-1.245 3.005T10 16.25t-3.005-1.245T5.75 12t1.245-3.005M19.125 12q0 2.811-1.964 3.191q.089-.577.089-1.191v-4q0-.614-.089-1.191q1.964.38 1.964 3.191");
}

</style>
