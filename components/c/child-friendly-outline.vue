<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uerdpgbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:child-friendly-outline" /></template>
<style>
.uerdpgbow {
  fill: currentColor;
  d: path("M8.32 19.912q-.32-.32-.32-.796t.32-.797t.796-.319q.476 0 .796.32t.319.796t-.32.796t-.795.319t-.797-.32m8.462 0q-.32-.319-.32-.796q0-.476.32-.796t.796-.319q.477 0 .796.32t.32.796q0 .476-.32.796t-.796.319t-.796-.32M12.769 8.255L9.64 4.477q.823-.315 1.661-.454t1.73-.138q1.045 0 1.967.247t1.688.73zM12 17q-1.671 0-2.835-1.164Q8 14.67 8 13V6.492l-.692-.83q-.542-.675-.943-.938t-.811-.262q-.638 0-1.058.43t-.419 1.07h-1q0-1.021.728-1.761t1.787-.74q.693 0 1.24.38q.549.378 1.218 1.186l8.892 10.708q.33.384.115.825t-.71.44zm0-1h3.85L9 7.7V13q0 1.25.875 2.125T12 16m.425-4.15");
}

</style>
