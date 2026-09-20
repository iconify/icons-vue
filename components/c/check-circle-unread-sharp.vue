<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0uxbnu3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-circle-unread-sharp" /></template>
<style>
.a0uxbnu3t {
  fill: currentColor;
  d: path("M8.488 20.292q-1.642-.709-2.857-1.924t-1.923-2.856T3 12.003t.709-3.502t1.924-2.855t2.857-1.93q1.643-.71 3.51-.71q.552 0 1.092.059t1.075.2q-.254.518-.403 1.069T13.617 5.5q0 1.226.543 2.248q.543 1.021 1.453 1.683l-5.056 5.061l-2.844-2.85l-.714.714l3.558 3.552l5.946-5.946q.471.202.964.312t1.034.11q.615 0 1.166-.148t1.069-.403q.142.534.2 1.075q.06.54.06 1.092q0 1.868-.711 3.51q-.711 1.643-1.93 2.858T15.5 20.29t-3.503.71t-3.509-.708m8.243-13.02Q16 6.542 16 5.502t.729-1.771T18.498 3t1.771.729T21 5.498t-.728 1.771t-1.77.731t-1.771-.728");
}

</style>
