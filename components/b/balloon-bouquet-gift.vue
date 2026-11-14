<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ocknb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balloon-bouquet-gift" /></template>
<style>
.s9ocknb7m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.5q1.243 0 2.121.879Q15 3.257 15 4.5q0 2.598-2.25 2.946v5.296l3.682-3.528Q15 8.573 15 6.5q0-3 3-3t3 3q0 2.841-2.69 2.992l-4.443 4.258h1.008q3.375 0 3.375 3.375v1.75q0 3.375-3.375 3.375h-5.75q-3.375 0-3.375-3.375v-1.75q0-3.375 3.375-3.375h1.008L5.69 9.492Q3 9.341 3 6.5q0-3 3-3t3 3q0 2.073-1.432 2.714l3.682 3.528V7.446Q9 7.098 9 4.5q0-3 3-3");
}

</style>
