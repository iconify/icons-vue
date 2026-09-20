<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa508v8li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:credit-card-clock-sharp" /></template>
<style>
.xa508v8li {
  fill: currentColor;
  d: path("m19.675 19.375l.7-.7L18.5 16.8V14h-1v3.2zM18.025 22q-2.1 0-3.562-1.45T13 17t1.463-3.55T18.025 12q2.075 0 3.525 1.463T23 17t-1.45 3.538T18.025 22M2 20V4h20v7.325q-.45-.325-.95-.575T20 10.325V8H4v4h9q-.975.95-1.537 2.238T10.9 17q0 .8.175 1.563t.5 1.437z");
}

</style>
