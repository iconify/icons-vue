<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuwaywzzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hand-gesture-sharp" /></template>
<style>
.vuwaywzzt {
  fill: currentColor;
  d: path("M21.404 5.64q0-1.101-.77-1.87q-.768-.77-1.87-.77v-.885q1.47 0 2.498 1.027t1.027 2.499zM6.058 21.77q-1.594 0-2.711-1.12t-1.116-2.708h.885q0 1.22.861 2.081q.862.862 2.08.862zm3.533-.27L2.719 11.433l.937-.92L8 13.538v-8.98h1V11.5h2.673V2.558h1V11.5h2.673V3.558h1V11.5H19V5h1v16.5z");
}

</style>
