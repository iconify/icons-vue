<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wjk7vbbyo"/><path class="r3ta8vl-m"/><path class="agal7sbth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-stop-duotone" /></template>
<style>
.agal7sbth {
  fill: currentColor;
  d: path("M8 11C8 9.343146 9.343146 8 11 8L13 8C14.656854 8 16 9.343146 16 11L16 13C16 14.656854 14.656854 16 13 16L11 16C9.343146 16 8 14.656854 8 13Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r3ta8vl-m {
  d: path("M12 22C6.4772 22 2 17.5229 2 12C2 6.4772 6.4772 2 12 2");
}

.wjk7vbbyo {
  stroke-opacity: 0.4;
  d: path("M17.8778 3.9098C18.7268 4.5266 19.4734 5.2732 20.0902 6.1222M21.8769 10.4357C22.041 11.4721 22.041 12.5279 21.8769 13.5643M20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902");
}

</style>
