<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjuvquhkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dowel-pin" /></template>
<style>
.fjuvquhkx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 12.25h4.5V5.5q0-.122.038-.237q.039-.116.112-.213l1.5-2q.052-.07.119-.126t.146-.095t.163-.059t.172-.02h2q.087 0 .172.02t.163.059q.079.039.146.095t.119.126l1.5 2q.073.097.112.213q.038.115.038.237v6.75h4.5q1.036 0 1.768.732t.732 1.768v5q0 1.036-.732 1.768t-1.768.732H4.25q-1.036 0-1.768-.732T1.75 19.75v-5q0-1.036.732-1.768t1.768-.732");
}

</style>
