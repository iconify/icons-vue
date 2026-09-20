<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olcam2bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fire-extinguisher-sharp" /></template>
<style>
.olcam2bce {
  fill: currentColor;
  d: path("M6.975 16v-3h10v3zM11.95 5.975q.425 0 .713-.288t.287-.712t-.287-.712t-.713-.288t-.712.288t-.288.712t.288.713t.712.287M7.05 11q.275-1.25 1.088-2.212t1.987-1.413q-.275-.225-.5-.488T9.25 6.3L5 5.475v-1l4.25-.8q.375-.775 1.1-1.237t1.6-.463q.6 0 1.113.213t.912.562L18 1.975v6l-4.025-.75q-.05.05-.088.075t-.087.075q1.175.45 1.987 1.413T16.876 11zm-.075 11v-4h10v4z");
}

</style>
