<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f8m9b9b9z"/><path class="fn1p5fm9f"/><path class="x1se1px2n"/><path class="i3ie3ccuz"/><path class="r50xlibql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-fork-broken" /></template>
<style>
.f8m9b9b9z {
  d: path("M2 5C2 6.65685 3.34315 8 5 8C6.65685 8 8 6.65685 8 5C8 3.34315 6.65685 2 5 2");
}

.fn1p5fm9f {
  d: path("M22 5C22 6.65686 20.6569 8 19 8C17.3431 8 16 6.65686 16 5C16 3.34315 17.3431 2 19 2C20.6569 2 22 3.34315 22 5Z");
}

.i3ie3ccuz {
  d: path("M12 15.999L12 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r50xlibql {
  d: path("M19 8C19 9.88562 19 10.8284 17.9749 11.4142C16.9497 12 15.2998 12 12 12C8.70017 12 7.05025 12 6.02513 11.4142C5 10.8284 5 9.88562 5 8");
}

.x1se1px2n {
  d: path("M15 19.0039C15 20.6608 13.6569 22.0039 12 22.0039C10.3431 22.0039 9 20.6608 9 19.0039C9 17.3471 10.3431 16.0039 12 16.0039C13.6569 16.0039 15 17.3471 15 19.0039Z");
}

</style>
