<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqx5x-_0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dry-stone-wall" /></template>
<style>
.kqx5x-_0r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 8.75V7.226q0-1.751 1.646-2.35l1.005-.365q.846-.308 1.695-.005l1.745.623q1.659.593 1.659 2.354V8.75q0 2.5-2.5 2.5H15q-2.5 0-2.5-2.5M3.75 7.375V8.75q0 2.5 2.5 2.5h2.5q2.5 0 2.5-2.5V7.202q0-2.074-2.039-2.457l-1.816-.34q-1.081-.203-1.961.457l-.684.513q-1 .75-1 2M9 15.186v2.064q0 2.5 2.5 2.5h1q1.036 0 1.768-.732T15 17.25v-1.863q0-1.624-1.485-2.285l-.59-.261q-.886-.394-1.806-.088l-.481.16Q9 13.459 9 15.186M1.75 17.25v-1.849q0-1.303 1.084-2.025l.243-.161q.724-.484 1.593-.411l.892.074q2.188.182 2.188 2.377v1.995q0 2.5-2.5 2.5h-1q-2.5 0-2.5-2.5m14.5 0v-1.975q0-1.89 1.853-2.26l.661-.132q.841-.169 1.609.215l.494.247q1.384.692 1.383 2.237v1.668q0 1.036-.732 1.768t-1.768.732h-1q-2.5 0-2.5-2.5");
}

</style>
