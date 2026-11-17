<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u831h0kyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-snow" /></template>
<style>
.u831h0kyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14V17.5M12 17.5V21M12 17.5L9 15.75M12 17.5L15 19.25M12 17.5L9 19.25M12 17.5L15 15.75M5 16.874C3.2748 16.43 2 14.864 2 13C2 10.791 3.7909 9 6 9C6 5.686 8.6863 3 12 3C15.3137 3 18 5.686 18 9C20.2091 9 22 10.791 22 13C22 14.864 20.7252 16.43 19 16.874");
}

</style>
