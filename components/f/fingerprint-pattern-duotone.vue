<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g5mx1d-ji"/><path class="cp1u7_asv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fingerprint-pattern-duotone" /></template>
<style>
.cp1u7_asv {
  d: path("M16 2.9377C18.7417 4.298 20.6042 6.9584 20.9443 10M3 11C3 10.581 3.0293 10.1624 3.0876 9.7474M3.9443 19C5.9121 16.7999 7 13.9517 7 11C7 8.2386 9.2386 6 12 6C12.5833 6 13.162 6.1021 13.7101 6.3015M16.166 17C15.6706 18.7475 14.9607 20.427 14.0526 22");
}

.g5mx1d-ji {
  stroke-opacity: 0.4;
  d: path("M4.9079 5.459C6.6135 3.2759 9.2296 2 12 2M20.8263 14C20.7091 15.0095 20.5327 16.0112 20.2982 17M16.6359 9.127C16.8764 9.7222 17 10.3581 17 11C17 11.6677 16.9696 12.3351 16.9089 13M12 11C12 15.0294 10.5687 18.9278 7.9615 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
