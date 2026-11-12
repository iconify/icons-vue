<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxh9t6csl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-person-2-sharp" /></template>
<style>
.vxh9t6csl {
  fill: currentColor;
  d: path("M18 8V6h-4V5h5v3zM3 10V5h5v1H4v4zm0 9v-5h1v4h4v1zm9 0v-.9q0-.465.236-.843q.235-.378.656-.546q.843-.355 1.748-.533Q15.544 16 16.5 16q.917 0 1.822.178t1.786.534q.42.167.656.545q.236.377.236.843v.9zm3.09-5.59q-.59-.59-.59-1.41t.59-1.41T16.5 10t1.41.59t.59 1.41t-.59 1.41t-1.41.59t-1.41-.59");
}

</style>
