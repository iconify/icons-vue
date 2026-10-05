<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fa0bqbbbr"/><path class="s_wgdnfog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-upload-sharp-duotone" /></template>
<style>
.fa0bqbbbr {
  stroke-opacity: 0.4;
  d: path("M4.5 16.7528L4 16.4641C2.7624 15.7496 2 14.4291 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 14.4291 21.2376 15.7496 20 16.4641L19.5 16.7528");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s_wgdnfog {
  d: path("M12 22L12 21L12 13M7.7071 17.2929L8 17L12 13L16 17L16.2929 17.2929");
}

</style>
