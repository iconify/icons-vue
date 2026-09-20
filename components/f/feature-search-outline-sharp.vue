<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lty3ajm5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:feature-search-outline-sharp" /></template>
<style>
.lty3ajm5f {
  fill: currentColor;
  d: path("m18 12.52l1 1V21H3V5h6.98q-.084.277-.116.52T9.8 6H4v14h14zm.454-3.774l3.315 3.316l-.707.707l-3.316-3.315q-.448.396-1.038.587t-1.208.19q-1.567 0-2.649-1.082T11.769 6.5t1.082-2.649T15.5 2.769t2.649 1.082T19.231 6.5q0 .675-.21 1.237q-.21.561-.567 1.01m-1.015-.309q.792-.792.792-1.938t-.792-1.939T15.5 3.77t-1.939.793T12.77 6.5t.792 1.939t1.939.792t1.939-.792M4 12.519V20V6v6.23v-.28z");
}

</style>
