<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibcj0r73f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ektara" /></template>
<style>
.ibcj0r73f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q2 0 2 2l2.647-1.412q.132-.07.28-.084q.149-.015.291.028q.143.044.258.139q.116.094.186.226t.084.28q.015.149-.028.291q-.044.143-.139.258q-.094.116-.226.186L14 5.45v3.8q0 .412-.145.764q1.428.431 2.564 1.567Q18.25 13.411 18.25 16t-1.831 4.419T12 22.25t-4.419-1.831Q5.75 18.589 5.75 16t1.831-4.419q1.136-1.136 2.564-1.567Q10 9.662 10 9.25v-5.5q0-2 2-2M9.5 16q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 16t-.732 1.768T12 18.5q-2.5 0-2.5-2.5");
}

</style>
