<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dgj8sbb0m"/><path class="kh-7d0_ag"/><path class="t3b1pccrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:call-recorder" /></template>
<style>
.dgj8sbb0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.03 32.59v4.752M45.5 24c0 11.307-9.166 20.473-20.472 20.473a20.4 20.4 0 0 1-9.902-2.55L2.5 44.09l4.06-11.245A20.4 20.4 0 0 1 4.555 24c0-11.307 9.166-20.472 20.473-20.472S45.5 12.692 45.5 24");
}

.kh-7d0_ag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.095 9.274c2.136-.02 4.914 1.942 5.071 4.781V24.85a5.071 5.071 0 0 1-10.143 0V14.055c0-2.8 2.936-4.763 5.072-4.781m-5.071 5.693l2.287.027m-2.287 2.579l2.287.027m-2.287 2.578l2.287.027");
}

.t3b1pccrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.073 20.721l.124 3.748c.171 5.187 4.082 8.325 7.898 8.325s7.89-3.604 8.007-7.742l.12-4.304m-1.14 16.909H17.86");
}

</style>
