<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j5vqy7qwa"/><path class="ita3i21oe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-quarter-two-tone" /></template>
<style>
.ita3i21oe {
  d: path("M12 22C6.47715 22 2 17.5229 2 12");
}

.j5vqy7qwa {
  stroke-opacity: 0.4;
  d: path("M3.90983 6.12215C4.52663 5.2732 5.2732 4.52663 6.12215 3.90983M10.4357 2.12312C11.4721 1.95896 12.5279 1.95896 13.5643 2.12312M17.8778 3.90983C18.7268 4.52663 19.4734 5.2732 20.0902 6.12215M21.8769 10.4357C22.041 11.4721 22.041 12.5279 21.8769 13.5643M20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
