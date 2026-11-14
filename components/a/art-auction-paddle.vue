<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6jnjvb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:art-auction-paddle" /></template>
<style>
.q6jnjvb1g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.375 1.75h5.25q2.123 0 3.624 1.501t1.501 3.624v2.25q0 2.123-1.501 3.624t-3.624 1.501H14.3q.2.459.2 1v4.5q0 1.036-.732 1.768T12 22.25t-1.768-.732T9.5 19.75v-4.5q0-.564.127-1h-.252q-2.123 0-3.624-1.501T4.25 9.125v-2.25q0-2.123 1.501-3.624T9.375 1.75M8.75 8q0 3.25 3.25 3.25T15.25 8T12 4.75T8.75 8");
}

</style>
