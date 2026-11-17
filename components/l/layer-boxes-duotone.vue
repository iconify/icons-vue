<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cu2g3bb6b"/><path class="fn61a1l_q"/><path class="tzspw2esx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layer-boxes-duotone" /></template>
<style>
.cu2g3bb6b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.124 1.202C11.677 0.933 12.323 0.933 12.876 1.202L21.876 5.59C22.624 5.954 23 6.681 23 7.388V15.987C23 17.134 22.345 18.182 21.314 18.685L12.876 22.798C12.323 23.067 11.677 23.067 11.124 22.798L2.685 18.685C1.654 18.182 1 17.134 1 15.987L1.005 7.529C0.953 6.779 1.323 5.98 2.123 5.59L11.124 1.202Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.fn61a1l_q {
  d: path("M23 13.249L12.877 18.185C12.324 18.454 11.678 18.454 11.125 18.185L1.002 13.249L1.003 11.026L12.001 16.387L23 11.025V13.249Z");
}

.tzspw2esx {
  d: path("M11.124 1.202C11.677 0.933 12.323 0.933 12.876 1.202L21.876 5.59C22.628 5.957 23.005 6.69 23 7.401C22.995 8.104 22.619 8.824 21.877 9.186L12.876 13.573C12.323 13.843 11.677 13.843 11.124 13.573L2.124 9.186C1.457 8.861 1.081 8.244 1.011 7.609C0.926 6.837 1.294 5.994 2.123 5.59L11.124 1.202Z");
}

</style>
