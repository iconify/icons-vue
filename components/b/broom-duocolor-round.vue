<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gilwoj1ah"/><path class="fax3m1v-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-duocolor-round" /></template>
<style>
.fax3m1v-z {
  d: path("M12 20H6c-.919 0-1.46-1.081-1-2l2-4c.613-1.226 1.387-2 2-2h6c.613 0 1.387.774 2 2l2 4c.46.919-.081 2-1 2zm-2 0v-3m4 3v-3");
}

.gilwoj1ah {
  stroke-opacity: 0.4;
  d: path("M12 3v9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
