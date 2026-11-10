<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jhp21wblv"/><path clip-rule="evenodd" class="jc6cy4b3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:greater-than-equal-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jc6cy4b3p {
  fill-rule: evenodd;
  d: path("M16 18C16.5523 18 17 18.45 17 19C17 19.55 16.5523 20 16 20H8C7.4477 20 7 19.55 7 19C7 18.45 7.4477 18 8 18H16Z");
}

.jhp21wblv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.1522 4.47C7.445 4 8.0619 3.86 8.5301 4.15L16.5301 9.15C16.8223 9.33 16.9999 9.66 16.9999 10C16.9999 10.34 16.8223 10.66 16.5301 10.85L8.5301 15.85C8.0619 16.14 7.445 16 7.1522 15.53C6.8596 15.06 7.0015 14.45 7.4696 14.15L14.1131 10L7.4696 5.85C7.0015 5.55 6.8596 4.94 7.1522 4.47Z");
}

</style>
