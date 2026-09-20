<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z434sr8gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-pin-rounded" /></template>
<style>
.z434sr8gp {
  fill: currentColor;
  d: path("M9.462 12.654h1.692v-2.365h1.692v2.365h1.692V8.596L12 6.904L9.461 8.596zm2.069 7.825q-.235-.077-.433-.25q-1.067-.981-2.164-2.185q-1.096-1.203-1.99-2.493t-1.468-2.633t-.572-2.622q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 1.279-.572 2.613q-.572 1.333-1.458 2.632q-.885 1.3-1.981 2.494T12.92 20.21q-.198.173-.442.26t-.479.086t-.47-.077");
}

</style>
