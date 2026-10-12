<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usuetbcec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-down-3" /></template>
<style>
.usuetbcec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 13L7 2.7396M12 6.8947L7.3241 2.1367C7.1451 1.9544 6.8549 1.9544 6.6759 2.1367L2 6.8947M17 11L17 21.2604M12 17.1053L16.6759 21.8633C16.8549 22.0456 17.1451 22.0456 17.3241 21.8633L22 17.1053");
}

</style>
