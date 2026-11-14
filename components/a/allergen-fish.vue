<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq6q8ybzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:allergen-fish" /></template>
<style>
.wq6q8ybzn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m9-3.187q-3.169 0-4.889 2.794q-.054.089-.083.189q-.028.1-.028.204t.028.204q.029.1.083.189q1.72 2.795 4.889 2.795q2.854 0 4.532-2.266q.202.443.618.784q.78.637 1.69.206t.91-1.439v-.946q0-1.007-.91-1.439q-.91-.431-1.69.206v.001q-.416.341-.618.783q-1.679-2.265-4.532-2.265");
}

</style>
