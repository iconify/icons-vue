<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7xz-xbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-degree-sharp" /></template>
<style>
.z7xz-xbuz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 14C16 12.49 15.509 11.01 14.6 9.8L9.8 3.4C9.611 3.15 9.315 3 9 3C8.685 3 8.389 3.15 8.2 3.4L3.4 9.8C2.491 11.01 2 12.49 2 14C2 17.87 5.134 21 9 21C12.866 21 16 17.87 16 14ZM18 5C18 6.1 18.895 7 20 7C21.105 7 22 6.1 22 5C22 3.9 21.105 3 20 3C18.895 3 18 3.9 18 5Z");
}

</style>
