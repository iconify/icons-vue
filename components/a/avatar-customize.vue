<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofddltrnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:avatar-customize" /></template>
<style>
.ofddltrnt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m7 12.121v.754q0 .777.179 1.375H4q-1.75 0-1.75-1.75q0-2.798 2.468-4.577q2.32-1.673 5.782-1.673q3.12 0 5.313 1.359l-2.039 2.038q-1.024 1.025-1.024 2.474m1.25.754v-.754q0-.931.659-1.59l2.5-2.5q.659-.66 1.591-.66t1.592.66l.627.628q.66.659.66 1.591t-.66 1.592l-2.5 2.499q-.659.659-1.59.659h-.754Q14 22 14 19.875m1.5 0q0 .625.625.625h.754q.31 0 .53-.219l2.5-2.501q.22-.219.22-.53t-.22-.531l-.629-.628q-.219-.22-.53-.22t-.531.22l-2.499 2.5q-.22.22-.22.53z");
}

</style>
