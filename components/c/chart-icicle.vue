<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynm_j2w-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-icicle" /></template>
<style>
.ynm_j2w-v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 1.75h15.5q1.036 0 1.768.732t.732 1.768v1q0 1.036-.732 1.768t-1.768.732H4.25q-2.5 0-2.5-2.5v-1q0-1.036.732-1.768T4.25 1.75m4.75 7H4.25q-1.036 0-1.768.732T1.75 11.25v1q0 2.5 2.5 2.5H9q2.5 0 2.5-2.5v-1q0-1.036-.732-1.768T9 8.75m6 0h4.75q1.036 0 1.768.732t.732 1.768v1q0 1.036-.732 1.768t-1.768.732H15q-2.5 0-2.5-2.5v-1q0-2.5 2.5-2.5m-9 9.125q0-2.125-2.125-2.125T1.75 17.875v2.25q0 2.125 2.125 2.125T6 20.125zm3.375-2.125q2.125 0 2.125 2.125v2.25q0 2.125-2.125 2.125T7.25 20.125v-2.25q0-2.125 2.125-2.125m7.375 2.125q0-2.125-2.125-2.125T12.5 17.875v2.25q0 2.125 2.125 2.125t2.125-2.125zm3.375-2.125q2.125 0 2.125 2.125v2.25q0 2.125-2.125 2.125T18 20.125v-2.25q0-2.125 2.125-2.125");
}

</style>
