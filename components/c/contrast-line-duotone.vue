<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xlrhvjb5s"/><path class="q83vvvkar"/><path class="pnkt3gb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:contrast-line-duotone" /></template>
<style>
.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pnkt3gb-r {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2 12C2 17.5228 6.4772 22 12 22V2C6.4772 2 2 6.4772 2 12Z");
}

.q83vvvkar {
  stroke-linecap: round;
  d: path("M12 2L2 12M12 17L7.8883 21.1117M12 12L4.9353 19.0646M12 7L2.8883 16.1117");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xlrhvjb5s {
  d: path("M12 22C17.5228 22 22 17.5228 22 12C22 6.4772 17.5228 2 12 2M12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2M12 22V2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
