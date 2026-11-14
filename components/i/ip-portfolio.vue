<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="texcxbcjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ip-portfolio" /></template>
<style>
.texcxbcjh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5q0-2.25 2.25-2.25h5q.084 0 .167.019q.082.018.158.055t.142.089t.119.118L11.36 5.25H20q2.25 0 2.25 2.25V19q0 2.25-2.25 2.25H4q-2.25 0-2.25-2.25zm7.068 5.068Q7.5 11.386 7.5 13.25t1.318 3.182T12 17.75t3.182-1.318T16.5 13.25t-1.318-3.182T12 8.75t-3.182 1.318");
}

</style>
