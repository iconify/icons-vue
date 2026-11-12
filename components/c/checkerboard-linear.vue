<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ar0zhnbxz"/><path class="njn_u_akb"/><path class="bilqnpbbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:checkerboard-linear" /></template>
<style>
.ar0zhnbxz {
  d: path("M12 22C7.286 22 4.9289 22 3.4645 20.536C2 19.071 2 16.714 2 12C2 7.286 2 4.929 3.4645 3.464C4.9289 2 7.286 2 12 2C16.714 2 19.0711 2 20.5355 3.464C22 4.929 22 7.286 22 12C22 16.714 22 19.071 20.5355 20.536C19.0711 22 16.714 22 12 22Z");
}

.bilqnpbbp {
  d: path("M21.9949 14.0053L14.0053 21.9948M12.0001 18.5001L18.5001 12.0001M2.00537 9.99469L9.99487 2.00513M12.0001 5.49996L5.50011 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.njn_u_akb {
  d: path("M12 2V12M12 12V22M12 12H2M12 12H22");
}

</style>
