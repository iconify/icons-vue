<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_c1-0bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hot-tub-sharp" /></template>
<style>
.r_c1-0bpn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11L3 19L21 19L21 10M1 11L23 11M8 19L6.7236 21.5528M16 19L17.2764 21.5528M3 11L3 3L6 3C7.0463 3 8.0169 3.5451 8.5615 4.4384M7.2071 5.7929L10.2929 2.7071M15 2L15 3.1972C15 4.3727 14.6521 5.5219 14 6.5C13.8919 6.6622 13.7921 6.8291 13.7009 7L13.2301 7.8822M20 2L20 3.1972C20 4.3727 19.6521 5.5219 19 6.5C18.8919 6.6622 18.7921 6.8291 18.7009 7L18.2301 7.8822");
}

</style>
