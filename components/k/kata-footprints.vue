<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce3e7wp_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kata-footprints" /></template>
<style>
.ce3e7wp_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 6q0-3.25 4-3.25t4 3.25t-4 3.25t-4-3.25M12 8.75q-4 0-4 3.25t4 3.25T16 12q0-1.405-1.245-2.362Q13.601 8.75 12 8.75M1.5 18q0-3.25 4-3.25t4 3.25t-4 3.25t-4-3.25");
}

</style>
