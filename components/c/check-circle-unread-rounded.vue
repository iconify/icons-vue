<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="equfjtuwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-circle-unread-rounded" /></template>
<style>
.equfjtuwd {
  fill: currentColor;
  d: path("M8.488 20.292q-1.642-.709-2.857-1.924t-1.923-2.856T3 12.003t.71-3.502t1.928-2.855t2.851-1.93q1.634-.71 3.505-.71q.332 0 .644.018t.616.068q.356.059.523.371t.03.66q-.095.337-.143.673q-.048.337-.048.704q0 1.226.543 2.248q.543 1.021 1.453 1.683l-5.056 5.061l-2.49-2.496q-.147-.146-.345-.155t-.363.155t-.166.357t.166.357l2.633 2.632q.242.243.565.243t.565-.243l5.381-5.38q.471.202.964.312t1.034.11q.376 0 .708-.043q.333-.043.669-.149q.348-.105.662.05t.369.504q.05.304.068.61t.018.644q0 1.868-.71 3.51q-.711 1.643-1.93 2.858t-2.855 1.923t-3.502.709t-3.509-.708m8.243-13.02Q16 6.542 16 5.502t.729-1.771T18.498 3t1.771.729T21 5.498t-.728 1.771t-1.77.731t-1.771-.728");
}

</style>
