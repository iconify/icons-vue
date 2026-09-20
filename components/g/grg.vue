<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k5_31x32f"/><path class="xllw4opok"/><path class="q1xnlvbgz"/><path class="aii74l_4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:grg" /></template>
<style>
.aii74l_4b {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.25 3l-1 7l6 6z");
}

.ft5dv1b6b {
  fill: none;
}

.k5_31x32f {
  fill: var(--svg-color--054186, #054186);
  d: path("M12.75 21a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.q1xnlvbgz {
  fill: var(--svg-color--ffca57, #ffca57);
  d: path("m10.25 10.001l-7 1l13 5z");
}

.xllw4opok {
  fill: var(--svg-color--ffae00, #ffae00);
  d: path("m10.25 10l1-7l-8 8z");
}

</style>
