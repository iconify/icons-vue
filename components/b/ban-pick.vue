<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pofe-ab4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ban-pick" /></template>
<style>
.pofe-ab4i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75H7q-1.76 0-3.005 1.245T2.75 6v10q0 1.76 1.245 3.005T7 20.25h5q.48 0 .922-.093Q12.5 19.166 12.5 18q0-2.278 1.611-3.889q.953-.953 2.139-1.342V6q0-1.76-1.245-3.005T12 1.75m-.7 6.4l1.125 1.5q1.013 1.35 0 2.7l-1.125 1.5q-.675.9-1.8.9t-1.8-.9l-1.125-1.5q-1.012-1.35 0-2.7L7.7 8.15q.675-.9 1.8-.9t1.8.9m3.695 6.845Q13.75 16.24 13.75 18q0 1.636 1.075 2.826q.055.115.145.204q.089.09.204.145Q16.364 22.25 18 22.25q1.76 0 3.005-1.245T22.25 18q0-1.636-1.075-2.826q-.055-.115-.145-.204q-.089-.09-.204-.145Q19.636 13.75 18 13.75q-1.76 0-3.005 1.245m.514 4.435q-.259-.585-.259-1.43q0-2.75 2.75-2.75q.744 0 1.346.344zM18 20.75q-.845 0-1.43-.259l3.836-3.837q.344.602.344 1.346q0 1.139-.805 1.945q-.806.805-1.945.805");
}

</style>
