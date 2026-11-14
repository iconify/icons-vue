<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk5qqzzhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-small" /></template>
<style>
.jk5qqzzhk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M11.47 17.03l-3.75-3.75q-.03-.029-.056-.061q-1.968-2.461.492-4.43q1.02-.815 2.317-.671q.872.097 1.527.59q.655-.493 1.527-.59q1.297-.144 2.317.671q2.46 1.969.492 4.43q-.026.032-.056.061l-3.75 3.75q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094");
}

</style>
