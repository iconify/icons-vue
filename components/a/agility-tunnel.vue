<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl0-s9boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:agility-tunnel" /></template>
<style>
.kl0-s9boq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.163 6.004Q12 2.99 4.837 6.004Q1.75 6.171 1.75 12.75q0 6.749 3.249 6.75h.002q.944 0 1.614-.571q6.045-2.08 12.09.51q.131.057.274.061h.022l.019-1.555l.114.047q1.616-.196 1.616-5.242q0-5.028-1.605-5.241zm-4.723.189q2.131.332 4.262 1.245l.003.001q.137.059.286.061H19q.074 0 .145.009l-.125 10.436q-2.381-.982-4.761-1.298q.991-1.669.991-5.397q0-3.37-.81-5.057m-2.359-.19q1.669.12 1.669 5.247q0 5.135-1.674 5.247q-2.167-.009-4.333.533q.507-1.613.507-4.28q0-4.371-1.363-5.912q2.597-.849 5.194-.835");
}

</style>
