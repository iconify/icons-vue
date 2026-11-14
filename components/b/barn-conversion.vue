<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9xcyyb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:barn-conversion" /></template>
<style>
.v9xcyyb6o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 11.382V20q0 2.25 2.25 2.25H10q-2.25 0-2.25-2.25v-9q0-2.25 2.25-2.25h4q.932 0 1.591.659T16.25 11v9q0 .932-.659 1.591T14 22.25h5.5q2.25 0 2.25-2.25v-8.618q0-.573-.275-1.077l-2.592-4.751q-.338-.62-.968-.935l-4.909-2.455q-1.006-.503-2.013 0L6.086 4.619q-.631.315-.969.935l-2.592 4.751q-.275.504-.275 1.077");
}

</style>
