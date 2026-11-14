<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdysfinri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:infinity-symbol" /></template>
<style>
.jdysfinri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.159 17.507q2.287-.936 3.99-4.114q1.702 1.922 3.81 2.401q2.677.608 4.141-1.344q2.588-3.45 0-6.9q-1.606-2.142-4.259-1.057q-2.287.936-3.99 4.114q-1.702-1.922-3.81-2.401Q5.364 7.598 3.9 9.55q-2.587 3.45 0 6.9q1.606 2.142 4.259 1.057");
}

</style>
