<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf6yk1brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:back-protector" /></template>
<style>
.mf6yk1brt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75H7Q2.75 1.75 2.75 6v3.5q0 1.489 2.036 3.786q1.07 1.208 1.464 1.901V19.5q0 2.75 3 2.75h5.5q3 0 3-2.75v-4.313q.394-.693 1.464-1.901Q21.25 10.989 21.25 9.5V6q0-4.25-4.25-4.25zM9.5 15v4.75q0 1.036.732 1.768T12 22.25t1.768-.732t.732-1.768V4.25q0-1.036-.732-1.768T12 1.75q-2.5 0-2.5 2.5z");
}

</style>
