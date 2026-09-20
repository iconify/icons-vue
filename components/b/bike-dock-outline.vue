<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4oza4b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bike-dock-outline" /></template>
<style>
.u4oza4b2f {
  fill: currentColor;
  d: path("M4 20v-1l4.77-.917l.934-12.596q.061-.635.515-1.061T11.314 4h1.392q.64 0 1.094.426t.516 1.06l.915 12.597L20 19v1zm6.808-1.827h2.384V6.193q0-.502-.345-.848Q12.502 5 12 5t-.847.345t-.345.847z");
}

</style>
