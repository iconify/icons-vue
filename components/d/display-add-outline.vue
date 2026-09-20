<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0k77uqig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:display-add-outline" /></template>
<style>
.q0k77uqig {
  fill: currentColor;
  d: path("M4 5v12zm4 16v-2H4q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h9.35q-.175.475-.262.975T13 5H4v12h16v-6.075q.55-.1 1.05-.275t.95-.45V17q0 .825-.587 1.413T20 19h-4v2zM18 9V6h-3V4h3V1h2v3h3v2h-3v3z");
}

</style>
