<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibjfkpupm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:child-friendly-outline-sharp" /></template>
<style>
.ibjfkpupm {
  fill: currentColor;
  d: path("M8.32 19.916Q8 19.601 8 19.12t.315-.8t.796-.32t.8.315t.32.796t-.315.8t-.796.32t-.8-.315m8.46 0q-.319-.315-.319-.796t.315-.8t.797-.32q.48 0 .8.315t.32.796t-.316.8t-.795.32t-.801-.315M12.769 8.254L9.64 4.477q.823-.315 1.661-.454t1.73-.138q1.045 0 1.967.247t1.688.73zM8 17V6.492l-.692-.83q-.542-.675-.943-.938t-.811-.262q-.633 0-1.055.43t-.422 1.07h-1q0-1.018.73-1.76q.731-.74 1.785-.74q.693 0 1.24.378q.549.38 1.218 1.187L17.99 17zm1-1h6.85L9 7.7zm3.425-4.15");
}

</style>
