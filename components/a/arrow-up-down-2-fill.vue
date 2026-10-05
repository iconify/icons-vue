<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ysprl-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-down-2-fill" /></template>
<style>
.z6ysprl-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 22L7 11.7396M12 15.8947L7.3241 11.1367C7.1451 10.9544 6.8549 10.9544 6.6759 11.1367L2 15.8947M17 2L17 12.2604M12 8.1053L16.6759 12.8633C16.8549 13.0456 17.1451 13.0456 17.3241 12.8633L22 8.1053");
}

</style>
