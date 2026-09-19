<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n00y7rkjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eapteka" /></template>
<style>
.n00y7rkjo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.596 18.14a2.736 2.736 0 0 1-2.736-2.736v-6A3.915 3.915 0 0 0 25.957 5.5h-3.914a3.915 3.915 0 0 0-3.903 3.903v6a2.736 2.736 0 0 1-2.736 2.737h-6A3.915 3.915 0 0 0 5.5 22.043v3.914a3.915 3.915 0 0 0 3.903 3.903h6.001a2.736 2.736 0 0 1 2.736 2.736v6a3.915 3.915 0 0 0 3.903 3.904h3.914a3.915 3.915 0 0 0 3.903-3.903v-6.001a2.736 2.736 0 0 1 2.736-2.736h6a3.915 3.915 0 0 0 3.904-3.903v-3.914a3.915 3.915 0 0 0-3.903-3.903");
}

</style>
