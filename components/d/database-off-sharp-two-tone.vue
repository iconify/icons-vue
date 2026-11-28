<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s5duqew8q"/><path class="q-lf41b6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:database-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-lf41b6p {
  d: path("M4 4V20C4 21.105 7.582 22 12 22C16.418 22 20 21.105 20 20M4 12C4 13.105 7.582 14 12 14C12.669 14 13.319 13.98 13.941 13.941M1.707 1.707L22.293 22.293");
}

.s5duqew8q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.785 20.785C20.675 20.977 20.535 21.136 20.397 21.263C20.099 21.536 19.719 21.748 19.326 21.918C18.493 22.278 17.409 22.539 16.143 22.722C14.877 22.904 13.44 23 12 23C10.56 23 9.123 22.904 7.857 22.722C6.592 22.539 5.507 22.278 4.674 21.918C4.281 21.748 3.901 21.536 3.603 21.263C3.307 20.99 3 20.567 3 20V4C3 3.697 3.088 3.435 3.215 3.215L20.785 20.785ZM5.452 1.796C6.145 1.578 6.955 1.408 7.857 1.278C9.123 1.096 10.56 1 12 1C13.44 1 14.877 1.096 16.143 1.278C17.409 1.461 18.493 1.722 19.326 2.082C19.719 2.252 20.099 2.464 20.397 2.737C20.693 3.01 21 3.433 21 4V17.343L5.452 1.796Z");
  stroke: none;
}

</style>
