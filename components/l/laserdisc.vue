<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9pqaac7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:laserdisc" /></template>
<style>
.o9pqaac7u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m7.855 6.578q-3.608-1.314-4.439-5.063T7.05 7.05q2.716-2.715 6.465-1.884t5.063 4.439q.051.141.044.29t-.069.284t-.173.236t-.25.152q-.07.025-.143.036q-.073.012-.147.008q-.073-.003-.145-.02t-.139-.049t-.126-.075t-.11-.098t-.088-.118t-.064-.132Q16.136 7.283 13.19 6.63q-2.945-.653-5.079 1.481T6.63 13.19q.653 2.946 3.489 3.978q.069.026.132.064t.118.088q.054.05.098.11q.044.059.075.126t.049.139q.017.072.02.145q.004.074-.008.147q-.011.073-.036.143q-.051.14-.152.25t-.236.173t-.284.069q-.149.007-.29-.044M8.75 12q0-3.25 3.25-3.25T15.25 12T12 15.25T8.75 12");
}

</style>
