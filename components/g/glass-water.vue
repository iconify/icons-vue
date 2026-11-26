<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl60j5bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:glass-water" /></template>
<style>
.xl60j5bny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.0002 2H19.9998C20.6145 2 21.0837 2.5494 20.9874 3.1566L18.2674 20.3132C18.1134 21.2847 17.2758 22 16.2921 22H7.7079C6.7242 22 5.8866 21.2847 5.7326 20.3132L3.0125 3.1566C2.9163 2.5494 3.3855 2 4.0002 2ZM3.6219 7C6 6 9.5 6 12 7C14.5 8 18 8 20.3781 7");
}

</style>
