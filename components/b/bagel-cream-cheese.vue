<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqp-uh7qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bagel-cream-cheese" /></template>
<style>
.nqp-uh7qc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.991 4.48Q1.751 5.845 1.75 7.999V15q0 2.651 3.29 4.296Q7.948 20.75 12 20.75t6.96-1.454q3.29-1.645 3.29-4.296V8q0-2.155-3.241-3.52Q16.086 3.25 12 3.25T4.991 4.48m15.759 9.294l-.026.038q-1.041 1.576-1.667 2.058q-.809.622-1.599.036q-1.524-1.208-4.307-.229q-2.155.759-3.121-.207q-1.505-1.505-4.113-1.215q-1.692.188-2.667-.589v-3.1q.705.517 1.741.954Q7.914 12.75 12 12.75t7.009-1.23q1.036-.437 1.741-.954zM3.288 15.421q1.188.503 2.795.324q1.892-.21 2.887.785q1.634 1.634 4.679.562q2.007-.706 2.882-.006l.019.014q1.154.866 2.314.54q-.268.161-.574.314Q15.698 19.25 12 19.25t-6.29-1.296q-2.154-1.077-2.422-2.533M12 5.75q1.604 0 2.77.5q1.48.634 1.48 1.75t-1.48 1.75q-1.166.5-2.77.5q-4.25 0-4.25-2.25T12 5.75");
}

</style>
