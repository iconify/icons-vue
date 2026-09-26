<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id-pioxhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dollar-sign-fill" /></template>
<style>
.id-pioxhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2L12 22M16 4L10 4C7.7909 4 6 5.7909 6 8C6 10.2091 7.7909 12 10 12L14 12C16.2091 12 18 13.7909 18 16C18 18.2091 16.2091 20 14 20L8 20");
}

</style>
