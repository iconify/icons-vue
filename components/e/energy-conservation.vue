<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb2ecibpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:energy-conservation" /></template>
<style>
.lb2ecibpn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.748 1.939l2.078 1.848q2.889.261 5.008 2.379q1.382 1.383 1.974 3.093Q22.25 9.408 22.25 12t-2.442 2.741q-.592 1.71-1.974 3.093q-1.922 1.921-4.476 2.315l.89.79q.112.1.177.234t.074.283t-.04.29t-.148.252q-.05.055-.108.1q-.059.045-.126.077q-.066.032-.138.051q-.071.018-.145.023q-.074.004-.147-.006t-.143-.034q-.07-.025-.133-.062q-.064-.037-.119-.086l-2.078-1.848q-2.889-.261-5.008-2.379q-1.382-1.383-1.974-3.093Q1.75 14.592 1.75 12t2.442-2.741q.592-1.71 1.974-3.093q1.922-1.921 4.476-2.315l-.89-.79q-.112-.1-.177-.234t-.074-.283t.04-.29t.148-.252q.05-.055.108-.1q.059-.045.126-.077q.066-.032.138-.051q.071-.018.145-.023q.074-.004.147.006t.143.034t.133.062q.064.037.119.086");
}

</style>
