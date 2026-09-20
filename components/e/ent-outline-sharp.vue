<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw7p7fsmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ent-outline-sharp" /></template>
<style>
.jw7p7fsmr {
  fill: currentColor;
  d: path("M9.696 21h1l.568-5.5H14.5v-1h-3.133l.398-3.77h4.812v-1h-5.713zM7 21v-3.762q-1.425-1.3-2.212-2.922T4 10.986q0-3.327 2.333-5.657T12 3q2.702 0 4.884 1.645t2.83 4.25L20.987 14H18v5h-4v2h-1v-3h4v-5h2.7l-.95-3.875q-.575-2.294-2.47-3.71Q14.388 4 12 4Q9.1 4 7.05 6.03Q5 8.062 5 10.97q0 1.494.613 2.84q.612 1.346 1.737 2.392L8 16.8V21zm5.35-8.5");
}

</style>
