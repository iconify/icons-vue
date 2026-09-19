<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t7mop5b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-j" /></template>
<style>
.t7mop5b3w {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m9.095 35.334q0 3.703-1.251 5.867q-2.118 3.662-7.642 3.662c-5.524 0-6.153-.988-7.411-2.963q-1.884-2.963-1.885-8.082v-.668h5.729v.668q.073 3.366.693 4.734q.619 1.369 2.652 1.369q2.016 0 2.663-1.496q.388-.887.388-2.992V17.139h6.063v20.195z");
}

</style>
