<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3smp0blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:category" /></template>
<style>
.y3smp0blb {
  fill: currentColor;
  d: path("M7.885 10.23L12 3.463l4.116 6.769zm9.606 11q-1.558 0-2.64-1.081t-1.082-2.64t1.082-2.649t2.64-1.09t2.649 1.09t1.09 2.649t-1.09 2.64t-2.649 1.082m-13.722-.5v-6.462h6.462v6.462z");
}

</style>
