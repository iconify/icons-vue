<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fwp_vnljt"/><path class="n_jf2cc7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:leaf-broken" /></template>
<style>
.fwp_vnljt {
  d: path("M12 9L16.4317 4.56839M12 14.5L15 11.5M16.875 9.625L18.6142 7.88577M15.75 15.75L19.811 11.689M12 19.5L13.875 17.625");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_jf2cc7x {
  d: path("M12 22C16.4183 22 20 18.3541 20 13.8567C20 9.39453 17.4467 4.18759 13.4629 2.32555C12.9986 2.10852 12.4993 2 12 2M12 22C7.58172 22 4 18.3541 4 13.8567C4 12.2707 4.32258 10.5906 4.91731 9M12 22V2M12 2C11.5007 2 11.0014 2.10852 10.5371 2.32555C8.93605 3.07388 7.56606 4.36246 6.5 5.92583");
}

</style>
