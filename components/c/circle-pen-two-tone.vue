<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e65d03r4b"/><path class="hupx43eas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-pen-two-tone" /></template>
<style>
.e65d03r4b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.8714 14.4285L14.9962 12.7786C15.1219 12.7283 15.2361 12.653 15.3319 12.5572L21.1945 6.6945C22.2685 5.6206 22.2685 3.8794 21.1945 2.8055C20.1206 1.7315 18.3794 1.7315 17.3055 2.8055L11.4428 8.6681C11.347 8.7639 11.2717 8.8781 11.2214 9.0038L9.5715 13.1286C9.423 13.5 9.51 13.9242 9.7929 14.2071C10.0758 14.49 10.5 14.577 10.8714 14.4285Z");
  stroke: none;
}

.hupx43eas {
  d: path("M12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22C17.5228 22 22 17.5228 22 12M10.5 13.5L14.6248 11.8501L20.4874 5.9874C21.1709 5.304 21.1709 4.196 20.4874 3.5126C19.804 2.8291 18.696 2.8291 18.0126 3.5126L12.1499 9.3752Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
