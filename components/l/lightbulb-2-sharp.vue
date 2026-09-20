<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmudjrg8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lightbulb-2-sharp" /></template>
<style>
.qmudjrg8b {
  fill: currentColor;
  d: path("M8.75 17.616v-3.558q-1.29-.84-2.02-2.174Q6 10.552 6 9.02q0-2.502 1.749-4.26T12 3t4.251 1.749T18 9q0 1.552-.73 2.882t-2.02 2.176v3.557zM9.673 21v-1h4.654v1z");
}

</style>
