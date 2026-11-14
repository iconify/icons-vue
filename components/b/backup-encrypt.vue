<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taa3v66sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:backup-encrypt" /></template>
<style>
.taa3v66sm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 5.5q0-3.25 8.25-3.25t8.25 3.25v7.638Q18.694 13 18 13q-2.49 0-3.209 1.772Q13.185 15 11 15q-4.732 0-6.75-1.069V18q0 .495 1.684 1.056q2.081.694 5.066.694q1.057 0 2-.087v.087q0 .77.27 1.428q-1.044.072-2.27.072q-8.25 0-8.25-3.25zm15 2.181Q15.732 8.75 11 8.75T4.25 7.681v4.069q0 .495 1.684 1.056Q8.015 13.5 11 13.5t5.066-.694q1.684-.561 1.684-1.056zm3.268 9.801q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
