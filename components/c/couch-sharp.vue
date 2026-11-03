<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u38bfvbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:couch-sharp" /></template>
<style>
.u38bfvbuj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 18L5 18M19 18L22 18L22 11L20 11M5 18L2 18L2 11L4 11M12 5L10 5C6.6863 5 4 7.6863 4 11M12 5L14 5C17.3137 5 20 7.6863 20 11M12 5L12 14M12 14L6 14L6 11L4 11M12 14L18 14L18 11L20 11M19 18L19 20M5 18L5 20");
}

</style>
