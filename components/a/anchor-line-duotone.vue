<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fs9xvfbrd"/><path class="jzfybiepz"/><path class="iylwwoert"/><path class="s8523bbgv"/><path class="vm9i956_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:anchor-line-duotone" /></template>
<style>
.fs9xvfbrd {
  d: path("M12 7.5V11.5M12 11.5V22M12 11.5H8M12 11.5H16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iylwwoert {
  d: path("M4 13.5C4 18.2 7.6 22 12 22C16.4 22 20 18.2 20 13.5");
}

.jzfybiepz {
  d: path("M14.75 4.75C14.75 6.2688 13.5188 7.5 12 7.5C10.4812 7.5 9.25 6.2688 9.25 4.75C9.25 3.2312 10.4812 2 12 2C13.5188 2 14.75 3.2312 14.75 4.75Z");
}

.s8523bbgv {
  d: path("M2 15.7L4 13.5L6.6 14.9");
}

.vm9i956_w {
  d: path("M22.0004 15.7L20.0004 13.5L17.4004 14.9");
}

</style>
