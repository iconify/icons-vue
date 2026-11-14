<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clh778bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-cover" /></template>
<style>
.clh778bfk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.525 12.092q-2.453-1.734-1.641-5.261Q3.933 2.266 8.588 2.79q4.322.487 4.637 4.56q2.958.476 4.495 3.408q1.657.103 2.909 1.279q1.434 1.347 1.496 3.315q.061 1.967-1.287 3.402q-1.347 1.434-3.315 1.496H6.525q-1.741.114-3.063-1.032q-1.333-1.156-1.458-2.915q-.126-1.759 1.029-3.092q.65-.751 1.492-1.119m7.179-4.828q-.346-2.652-3.284-2.983q-3.325-.375-4.075 2.886q-.609 2.649 1.359 3.882q1.468-3.395 5.503-3.753q.252-.023.497-.032");
}

</style>
