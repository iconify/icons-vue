<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npau1olhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:import-spark-sharp" /></template>
<style>
.npau1olhs {
  fill: currentColor;
  d: path("M4 8.73V4h7.923v1H5v3.73zm6.846 6.693l-.707-.72l2.203-2.203H4v-1h8.342l-2.204-2.204l.708-.719L14.27 12zM4 20v-4.73h1V19h14v-6.923h1V20zM18.404 9.692q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.362 2.387-1.359t1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.362 1.39 1.359 2.387t2.387 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.387 1.358q-.997.997-1.36 2.387q-.024.15-.2.15");
}

</style>
