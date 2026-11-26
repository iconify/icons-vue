<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swjdacg6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-or-sharp" /></template>
<style>
.swjdacg6s {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5C11.4139 5.6172 15.2606 7.9252 18 12C15.2606 16.0748 11.4139 18.3828 6 19C7.3684 15.8421 8 13.9473 8 12C8 10.0527 7.3684 8.1579 6 5ZM1 8L7.2031 8M1 16L7.2031 16M18 12L23 12");
}

</style>
