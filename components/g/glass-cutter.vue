<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc97l1bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glass-cutter" /></template>
<style>
.qc97l1bfa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.275 6.043q-.66.659-.66 1.591q0 .532.215.975l-.718.719q-.83-1.078-2.737-1.078h-7.25q-3.375 0-3.375 3.375v7.25q0 3.375 3.375 3.375h7.25q3.375 0 3.375-3.375v-7.25q0-.407-.049-.765l1.19-1.19q.443.215.975.215q.932 0 1.591-.66l1.768-1.768q.66-.659.66-1.591t-.659-1.591q-.66-.66-1.592-.66t-1.591.66zm-8.11 10.286q.133-.067.282-.077q.149-.011.29.036q.142.048.254.145q.113.098.18.232q.033.066.052.137q.02.071.025.145t-.004.147t-.032.143t-.06.134t-.085.12t-.107.101t-.125.079l-3 1.5q-.133.067-.282.077q-.149.011-.29-.036q-.142-.048-.254-.145q-.113-.098-.18-.232q-.033-.066-.052-.137q-.02-.071-.025-.145t.004-.147t.032-.143q.024-.07.06-.134q.037-.065.085-.12q.049-.056.107-.101q.059-.046.125-.079z");
}

</style>
