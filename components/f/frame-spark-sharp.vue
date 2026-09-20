<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2k-8gi9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-spark-sharp" /></template>
<style>
.v2k-8gi9k {
  fill: currentColor;
  d: path("M20 10V6h-4V5h5v5zM3 10V5h5v1H4v4zm13 9v-1h4v-4h1v5zM3 19v-5h1v4h4v1zm9-2.904q.175 0 .2-.15q.362-1.39 1.359-2.387t2.387-1.359q.15-.05.15-.2q0-.175-.15-.2q-1.39-.362-2.387-1.359T12.2 8.054q-.03-.15-.2-.15q-.15 0-.2.15q-.362 1.39-1.359 2.387T8.054 11.8q-.15.025-.15.2q0 .15.15.2q1.39.361 2.387 1.359q.997.997 1.359 2.387q.05.15.2.15");
}

</style>
