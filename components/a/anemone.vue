<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbb8z8blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anemone" /></template>
<style>
.tbb8z8blx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.784 5.421q1.097-.429 2.639.051q3.382 1.052 2.525 4.488q-.331 1.324-1.05 2.04q.719.716 1.05 2.04q.857 3.436-2.525 4.488q-1.542.48-2.639.051q-.285 1.001-1.315 1.901q-2.469 2.161-4.938 0q-1.03-.9-1.315-1.901q-1.097.429-2.639-.051q-3.382-1.052-2.525-4.488q.331-1.324 1.05-2.04q-.719-.716-1.05-2.04q-.857-3.436 2.525-4.488q1.542-.48 2.639-.051q.285-1.001 1.315-1.901q2.469-2.161 4.938 0q1.03.9 1.315 1.901M12 9.25q-2.75 0-2.75 2.75T12 14.75T14.75 12T12 9.25m0 4q-1.25 0-1.25-1.25T12 10.75T13.25 12T12 13.25");
}

</style>
