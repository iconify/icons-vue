<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sjrjyxbla"/><path class="csrr12bfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-graph-fill" /></template>
<style>
.csrr12bfa {
  fill: currentColor;
  d: path("M9 5C9 7.20914 7.20914 9 5 9C2.79086 9 1 7.20914 1 5C1 2.79086 2.79086 1 5 1C7.20914 1 9 2.79086 9 5ZM23 5C23 7.20914 21.2091 9 19 9C16.7909 9 15 7.20914 15 5C15 2.79086 16.7909 1 19 1C21.2091 1 23 2.79086 23 5ZM9 18.5C9 20.7091 7.20914 22.5 5 22.5C2.79086 22.5 1 20.7091 1 18.5C1 16.2909 2.79086 14.5 5 14.5C7.20914 14.5 9 16.2909 9 18.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sjrjyxbla {
  d: path("M5 15L5 8M12 21L12 3M19 8C19 10 18.8 12.4 16 14");
}

</style>
