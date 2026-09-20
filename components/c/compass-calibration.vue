<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3o7n5b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:compass-calibration" /></template>
<style>
.g3o7n5b0y {
  fill: currentColor;
  d: path("M9.165 19.22Q8 18.056 8 16.385t1.165-2.836T12 12.385t2.836 1.164T16 16.384q0 1.672-1.164 2.836Q13.67 20.385 12 20.385T9.165 19.22m-2.126-7.8L3.462 7.803Q5.25 6.265 7.443 5.44Q9.637 4.616 12 4.616t4.557.825q2.193.825 3.982 2.364l-3.578 3.615q-1.044-.871-2.319-1.337T12 9.616t-2.642.466t-2.32 1.337");
}

</style>
