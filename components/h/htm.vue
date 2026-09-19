<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u1_g1c6oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:htm" /></template>
<style>
.u1_g1c6oz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.933 28.078l1.793-7.768l2.093 7.776l5.681-7.764l-1.793 7.764M27.472 20.31h5.152m-4.371 7.776l1.795-7.776m-10.696 0l-1.795 7.776m6.947-7.776l-1.795 7.776m-4.251-3.903h5.152M4.5 17.068h29.119m-9.115 13.864h17.348");
}

</style>
