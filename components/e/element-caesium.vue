<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3kv3xpwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-caesium" /></template>
<style>
.z3kv3xpwh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 2.25h-9.25q-2.123 0-3.624 1.501T2.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T16.625 2.25m-4.064 4.252Q16.75 11.215 16.75 14q0 1.968-1.391 3.359T12 18.75t-3.359-1.391T7.25 14q0-2.785 4.189-7.498q.05-.055.108-.1q.059-.045.126-.077q.066-.032.138-.051q.071-.018.145-.023q.074-.004.147.006t.143.034t.133.062q.064.037.119.086q.033.03.063.063");
}

</style>
