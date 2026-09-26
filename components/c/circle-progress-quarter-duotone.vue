<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l-_oj69zk"/><path class="wbm9ombma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-quarter-duotone" /></template>
<style>
.l-_oj69zk {
  stroke-opacity: 0.4;
  d: path("M3.9098 6.1222C4.5266 5.2732 5.2732 4.5266 6.1222 3.9098M10.4357 2.1231C11.4721 1.959 12.5279 1.959 13.5643 2.1231M17.8778 3.9098C18.7268 4.5266 19.4734 5.2732 20.0902 6.1222M21.8769 10.4357C22.041 11.4721 22.041 12.5279 21.8769 13.5643M20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wbm9ombma {
  d: path("M12 22C6.4772 22 2 17.5229 2 12");
}

</style>
