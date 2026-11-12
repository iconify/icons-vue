<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwnu8vvwz"/><path class="ah0oz-g8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forbidden-circle-bold-duotone" /></template>
<style>
.ah0oz-g8a {
  fill: currentColor;
  d: path("M18.5211 4.41821L4.41797 18.5211C4.58006 18.7091 4.75031 18.8926 4.9287 19.071C5.1071 19.2494 5.29057 19.4196 5.47863 19.5817L19.5817 5.47889C19.4196 5.29078 19.2493 5.10728 19.0708 4.92884C18.8925 4.75048 18.7091 4.58028 18.5211 4.41821Z");
}

.jwnu8vvwz {
  fill: currentColor;
  d: path("M4.92893 4.92893C1.02369 8.83418 1.02369 15.1658 4.92893 19.0711C8.83418 22.9763 15.1656 22.9761 19.0708 19.0708C22.9761 15.1656 22.9763 8.83418 19.0711 4.92893C15.1658 1.02369 8.83418 1.02369 4.92893 4.92893Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
