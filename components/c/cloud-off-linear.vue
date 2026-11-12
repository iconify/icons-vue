<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="zgranabys"/><path class="kcgnukb2b"/><path class="h2jfsxbsc"/><path class="gyeb1ubcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-off-linear" /></template>
<style>
.gyeb1ubcp {
  d: path("M7.11523 11.6089C7.67963 11.7184 8.20433 11.9374 8.66573 12.2426");
}

.h2jfsxbsc {
  d: path("M7.11602 11.6089C6.88692 10.9978 6.76172 10.3369 6.76172 9.6471C6.76172 6.5283 9.32012 4 12.476 4C14.5256 4 16.3231 5.0664 17.3315 6.6683");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kcgnukb2b {
  d: path("M7.45508 20H16.2852C19.4411 20 21.9995 17.4717 21.9995 14.3529C21.9995 11.9589 20.492 9.91279 18.3639 9.09119");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.zgranabys {
  d: path("M7.1162 11.6089C6.8475 11.5567 6.5698 11.5294 6.2857 11.5294C3.9188 11.5294 2 13.4256 2 15.7647C2 17.4433 2.9881 18.8938 4.4209 19.5791");
}

</style>
