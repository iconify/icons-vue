<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp5hlb-sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-collapse-sharp" /></template>
<style>
.bp5hlb-sz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 2L6 10M2.7071 6.7071L6 10L9.2929 6.7071M6 22L6 14M2.7071 17.2929L6 14L9.2929 17.2929M12 6L22 6M12 12L22 12M12 18L22 18");
}

</style>
